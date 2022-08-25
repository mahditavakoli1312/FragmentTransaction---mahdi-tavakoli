<h1 class="code-line" data-line-start=0 data-line-end=1 ><a id="FragmentTransaction_0"></a>FragmentTransaction</h1>
<p class="has-line-data" data-line-start="1" data-line-end="2"><em>Mahdi Tavakoli</em></p>
<p class="has-line-data" data-line-start="3" data-line-end="4">FragmentTransaction is used for the simplicity of fragment transactions…</p>
<h1 class="code-line" data-line-start=5 data-line-end=6 ><a id="Static_function_in_FragmentTransaction_class___5"></a>Static function in FragmentTransaction class  :</h1>
<ul>
<li class="has-line-data" data-line-start="7" data-line-end="8">addFragment</li>
<li class="has-line-data" data-line-start="8" data-line-end="9">replaceFragment</li>
<li class="has-line-data" data-line-start="9" data-line-end="10">addFragmentWithAddToBackStack</li>
<li class="has-line-data" data-line-start="10" data-line-end="11">replaceFragmentWithAddToBackStack</li>
</ul>
<h2 class="code-line" data-line-start=14 data-line-end=15 ><a id="Input_arguments_of_functions__14"></a>Input arguments of functions :</h2>
<ul>
<li class="has-line-data" data-line-start="15" data-line-end="16">addFragment</li>
</ul>
<pre><code class="has-line-data" data-line-start="17" data-line-end="23" class="language-sh">        addFragment(
            fragment: Fragment,
            supportFragmentManager: FragmentManager,
            fragmentHolderId: Int
        ) 
</code></pre>
<ul>
<li class="has-line-data" data-line-start="24" data-line-end="25">replaceFragment</li>
</ul>
<pre><code class="has-line-data" data-line-start="26" data-line-end="32" class="language-sh">        replaceFragment(
            fragment: Fragment,
            supportFragmentManager: FragmentManager,
            fragmentHolderId: Int
        )
</code></pre>
<ul>
<li class="has-line-data" data-line-start="32" data-line-end="33">addFragmentWithAddToBackStack</li>
</ul>
<pre><code class="has-line-data" data-line-start="34" data-line-end="41" class="language-sh">         addFragmentWithAddToBackStack(
            fragment: Fragment,
            supportFragmentManager: FragmentManager,
            fragmentHolderId: Int,
            backStackName: String? = null
        )
</code></pre>
<ul>
<li class="has-line-data" data-line-start="41" data-line-end="42">replaceFragmentWithAddToBackStack</li>
</ul>
<pre><code class="has-line-data" data-line-start="43" data-line-end="50" class="language-sh">        replaceFragmentWithAddToBackStack(
            fragment: Fragment,
            supportFragmentManager: FragmentManager,
            fragmentHolderId: Int,
            backStackName: String? = null
        )
</code></pre>
<blockquote>
<p class="has-line-data" data-line-start="50" data-line-end="51">Note: this functions is <code>static</code></p>
</blockquote>
<blockquote>
<p class="has-line-data" data-line-start="53" data-line-end="55">Note: If you develop this class, send me a merge request to check<br>
Or you can email me. <code>mahditavakoli7878@gmail.com</code></p>
</blockquote>

<blockquote>
<p class="has-line-data" data-line-start="53" data-line-end="55">Note: add androidx.fragment<br> to dependency 
</blockquote>


