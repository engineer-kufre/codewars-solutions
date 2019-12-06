### Problem:
<p>Well met with Fibonacci bigger brother, AKA Tribonacci.</p>
<p>As the name may already reveal, it works basically like a Fibonacci, but summing the last 3 (instead of 2) numbers of the sequence to generate the next. And, worse part of it, regrettably I won&apos;t get to hear non-native Italian speakers trying to pronounce it :(</p>
<p>So, if we are to start our Tribonacci sequence with <code>[1, 1, 1]</code> as a starting input (AKA <em>signature</em>), we have this sequence:</p>
<pre><code class="language-py">[<span class="hljs-number">1</span>, <span class="hljs-number">1</span> ,<span class="hljs-number">1</span>, <span class="hljs-number">3</span>, <span class="hljs-number">5</span>, <span class="hljs-number">9</span>, <span class="hljs-number">17</span>, <span class="hljs-number">31</span>, ...]</code></pre>
<p>But what if we started with <code>[0, 0, 1]</code> as a signature? As starting with <code>[0, 1]</code> instead of <code>[1, 1]</code> basically <em>shifts</em> the common Fibonacci sequence by once place, you may be tempted to think that we would get the same sequence shifted by 2 places, but that is not the case and we would get:</p>
<pre><code class="language-py">[<span class="hljs-number">0</span>, <span class="hljs-number">0</span>, <span class="hljs-number">1</span>, <span class="hljs-number">1</span>, <span class="hljs-number">2</span>, <span class="hljs-number">4</span>, <span class="hljs-number">7</span>, <span class="hljs-number">13</span>, <span class="hljs-number">24</span>, ...]</code></pre>
<p>Well, you may have guessed it by now, but to be clear: you need to create a fibonacci function that given a <strong>signature</strong> array/list, returns <strong>the first n elements - signature included</strong> of the so seeded sequence.</p>
<p>Signature will always contain 3 numbers; n will always be a non-negative number; if <code>n == 0</code>, then return an empty array (except in C return NULL) and be ready for anything else which is not clearly specified ;)</p>
<p>If you enjoyed this kata more advanced and generalized version of it can be found in the <a href="http://www.codewars.com/kata/fibonacci-tribonacci-and-friends" target="_blank" title="Xbonacci sequence">Xbonacci kata</a></p>
<p>*[Personal thanks to Professor <a href="https://www.coursera.org/instructor/jimfowler" target="_blank" title="Jim Fowler">Jim Fowler</a> on Coursera for his awesome classes that I really recommend to any math enthusiast and for showing me this mathematical curiosity too with his usual contagious passion :)]*</p>

### Solution