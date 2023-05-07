Download Link: https://assignmentchef.com/product/solved-exercise-2
<br>
Exercise 2

<ul>

 <li>Modify the List class (file list.h so that it has two more functions, which will allow inserts and removes from anywhere in the linked list. Your functions should be called:insertMiddle</li>

 <li>removeMiddle</li>

</ul>

<pre class="ql-syntax">Your functions should have all the same features as the given <span class="hljs-keyword">insert</span> <span class="hljs-keyword">and</span> remove functions, <span class="hljs-keyword">except</span> that yours <span class="hljs-keyword">each</span> have one extra parameter. The <span class="hljs-keyword">second</span> parameter <span class="hljs-keyword">on</span> <span class="hljs-keyword">each</span> <span class="hljs-keyword">of</span> your functions should be <span class="hljs-keyword">of</span> <span class="hljs-keyword">type</span> <span class="hljs-built_in">int</span>, representing the <span class="hljs-keyword">position</span> <span class="hljs-keyword">at</span> which <span class="hljs-keyword">to</span> <span class="hljs-keyword">insert</span> (<span class="hljs-keyword">or</span> <span class="hljs-keyword">delete</span>). <span class="hljs-keyword">Sample</span> calls <span class="hljs-keyword">for</span> a <span class="hljs-keyword">list</span> <span class="hljs-keyword">of</span> integers:  L.insertMiddle(<span class="hljs-number">345</span>, <span class="hljs-number">5</span>);	// attempts to <span class="hljs-keyword">insert</span> the <span class="hljs-keyword">value</span> <span class="hljs-number">345</span>				//  <span class="hljs-keyword">as</span> the <span class="hljs-number">5</span>th item <span class="hljs-keyword">in</span> the <span class="hljs-keyword">list</span>  L.removeMiddle(x, <span class="hljs-number">10</span>);	// attempts to <span class="hljs-keyword">delete</span> the <span class="hljs-number">10</span>th item <span class="hljs-keyword">in</span> the				//  <span class="hljs-keyword">list</span> <span class="hljs-keyword">and</span> captures its <span class="hljs-keyword">value</span> <span class="hljs-keyword">into</span> x.</pre>

For insertMiddle, if the position number is larger than the number of items in the list, just insert the item at the <strong>back</strong>. If it’s too small (i.e. 0 or less), insert at the <strong>front</strong>. For removeMiddle, return false if the position is invalid (without removing anything).I’ve modified the menu program of Figure 21.5 so that it adds in two more menu options for testing these features. You can use it to test your class: