---
keywords: fastai
title: List and Dictionary
toc: true
comments: true
categories: [Notebook]
nb_path: _notebooks/2022-08-29-dictionary.ipynb
layout: notebook
---

<!--
#################################################
### THIS FILE WAS AUTOGENERATED! DO NOT EDIT! ###
#################################################
# file to edit: _notebooks/2022-08-29-dictionary.ipynb
-->

<div class="container" id="notebook-container">
        
    {% raw %}
    
<div class="cell border-box-sizing code_cell rendered">
<div class="input">

<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="n">InfoDb</span> <span class="o">=</span> <span class="p">[]</span>

<span class="n">InfoDb</span><span class="o">.</span><span class="n">append</span><span class="p">({</span>
    <span class="s2">&quot;FirstName&quot;</span><span class="p">:</span> <span class="s2">&quot;Finn&quot;</span><span class="p">,</span>
    <span class="s2">&quot;LastName&quot;</span><span class="p">:</span> <span class="s2">&quot;Carpenter&quot;</span><span class="p">,</span>
    <span class="s2">&quot;DOB&quot;</span><span class="p">:</span> <span class="s2">&quot;December 12&quot;</span><span class="p">,</span>
    <span class="s2">&quot;Residence&quot;</span><span class="p">:</span> <span class="s2">&quot;San Diego&quot;</span><span class="p">,</span>
    <span class="s2">&quot;FavColor&quot;</span><span class="p">:</span> <span class="s2">&quot;Blue&quot;</span><span class="p">,</span>
    <span class="s2">&quot;Email&quot;</span><span class="p">:</span> <span class="s2">&quot;finnc51448@stu.powayusd.com&quot;</span><span class="p">,</span>
    <span class="s2">&quot;Owns_Cars&quot;</span><span class="p">:</span> <span class="p">[</span><span class="s2">&quot;2012 Nissan Xterra&quot;</span><span class="p">]</span>
<span class="p">})</span>

<span class="n">InfoDb</span><span class="o">.</span><span class="n">append</span><span class="p">({</span>
    <span class="s2">&quot;FirstName&quot;</span><span class="p">:</span> <span class="s2">&quot;Jake&quot;</span><span class="p">,</span> 
    <span class="s2">&quot;LastName&quot;</span><span class="p">:</span> <span class="s2">&quot;Warren&quot;</span><span class="p">,</span>
    <span class="s2">&quot;DOB&quot;</span><span class="p">:</span> <span class="s2">&quot;September 8&quot;</span><span class="p">,</span>
    <span class="s2">&quot;Residence&quot;</span><span class="p">:</span> <span class="s2">&quot;San Diego&quot;</span><span class="p">,</span>
    <span class="s2">&quot;FavColor&quot;</span><span class="p">:</span> <span class="s2">&quot;Blue&quot;</span><span class="p">,</span>
    <span class="s2">&quot;Email&quot;</span><span class="p">:</span> <span class="s2">&quot;jacobw22751@stu.powayusd.com&quot;</span><span class="p">,</span>
    <span class="s2">&quot;Owns_Cars&quot;</span><span class="p">:</span> <span class="p">[</span><span class="s2">&quot;2016-Toyota Tacoma&quot;</span><span class="p">]</span>
<span class="p">})</span>

<span class="n">InfoDb</span><span class="o">.</span><span class="n">append</span><span class="p">({</span>
    <span class="s2">&quot;FirstName&quot;</span><span class="p">:</span> <span class="nb">input</span><span class="p">(</span><span class="s2">&quot;Name:&quot;</span><span class="p">),</span> 
    <span class="s2">&quot;LastName&quot;</span><span class="p">:</span> <span class="nb">input</span><span class="p">(</span><span class="s2">&quot;Last Name:&quot;</span><span class="p">),</span>
    <span class="s2">&quot;DOB&quot;</span><span class="p">:</span> <span class="nb">input</span><span class="p">(</span><span class="s2">&quot;DOB:&quot;</span><span class="p">),</span>
    <span class="s2">&quot;Residence&quot;</span><span class="p">:</span> <span class="nb">input</span><span class="p">(</span><span class="s2">&quot;Residence&quot;</span><span class="p">),</span>
    <span class="s2">&quot;FavColor&quot;</span><span class="p">:</span> <span class="nb">input</span><span class="p">(</span><span class="s2">&quot;Favorite Color&quot;</span><span class="p">),</span>
    <span class="s2">&quot;Email&quot;</span><span class="p">:</span> <span class="nb">input</span><span class="p">(</span><span class="s2">&quot;Email:&quot;</span><span class="p">),</span>
    <span class="s2">&quot;Owns_Cars&quot;</span><span class="p">:</span> <span class="nb">input</span><span class="p">(</span><span class="s2">&quot;Owned_Cars:&quot;</span><span class="p">)</span>
<span class="p">})</span>

<span class="nb">print</span><span class="p">(</span><span class="n">InfoDb</span><span class="p">)</span>
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">

<div class="output_area">

<div class="output_subarea output_stream output_stdout output_text">
<pre>[{&#39;FirstName&#39;: &#39;Finn&#39;, &#39;LastName&#39;: &#39;Carpenter&#39;, &#39;DOB&#39;: &#39;December 12&#39;, &#39;Residence&#39;: &#39;San Diego&#39;, &#39;FavColor&#39;: &#39;Blue&#39;, &#39;Email&#39;: &#39;finnc51448@stu.powayusd.com&#39;, &#39;Owns_Cars&#39;: [&#39;2012 Nissan Xterra&#39;]}, {&#39;FirstName&#39;: &#39;Jake&#39;, &#39;LastName&#39;: &#39;Warren&#39;, &#39;DOB&#39;: &#39;September 8&#39;, &#39;Residence&#39;: &#39;San Diego&#39;, &#39;FavColor&#39;: &#39;Blue&#39;, &#39;Email&#39;: &#39;jacobw22751@stu.powayusd.com&#39;, &#39;Owns_Cars&#39;: [&#39;2016-Toyota Tacoma&#39;]}, {&#39;FirstName&#39;: &#39;erika&#39;, &#39;LastName&#39;: &#39;carpenter&#39;, &#39;DOB&#39;: &#39;2/16/1965&#39;, &#39;Residence&#39;: &#39;San Diego&#39;, &#39;FavColor&#39;: &#39;orange&#39;, &#39;Email&#39;: &#39;bakecarp@aol.com&#39;, &#39;Owns_Cars&#39;: &#39;tesla&#39;}]
</pre>
</div>
</div>

</div>
</div>

</div>
    {% endraw %}

    {% raw %}
    
<div class="cell border-box-sizing code_cell rendered">
<div class="input">

<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="k">def</span> <span class="nf">print_data</span><span class="p">(</span><span class="n">d_rec</span><span class="p">):</span>
    <span class="nb">print</span><span class="p">(</span><span class="n">d_rec</span><span class="p">[</span><span class="s2">&quot;FirstName&quot;</span><span class="p">],</span> <span class="n">d_rec</span><span class="p">[</span><span class="s2">&quot;LastName&quot;</span><span class="p">])</span>  <span class="c1"># using comma puts space between values</span>
    <span class="nb">print</span><span class="p">(</span><span class="s2">&quot;</span><span class="se">\t</span><span class="s2">&quot;</span><span class="p">,</span> <span class="s2">&quot;Residence:&quot;</span><span class="p">,</span> <span class="n">d_rec</span><span class="p">[</span><span class="s2">&quot;Residence&quot;</span><span class="p">])</span> <span class="c1"># \t is a tab indent</span>
    <span class="nb">print</span><span class="p">(</span><span class="s2">&quot;</span><span class="se">\t</span><span class="s2">&quot;</span><span class="p">,</span> <span class="s2">&quot;FavColor:&quot;</span><span class="p">,</span> <span class="n">d_rec</span><span class="p">[</span><span class="s2">&quot;FavColor&quot;</span><span class="p">])</span>
    <span class="nb">print</span><span class="p">(</span><span class="s2">&quot;</span><span class="se">\t</span><span class="s2">&quot;</span><span class="p">,</span> <span class="s2">&quot;Birth Day:&quot;</span><span class="p">,</span> <span class="n">d_rec</span><span class="p">[</span><span class="s2">&quot;DOB&quot;</span><span class="p">])</span>
    <span class="nb">print</span><span class="p">(</span><span class="s2">&quot;</span><span class="se">\t</span><span class="s2">&quot;</span><span class="p">,</span> <span class="s2">&quot;Cars:&quot;</span><span class="p">,</span> <span class="n">d_rec</span><span class="p">[</span><span class="s2">&quot;Owns_Cars&quot;</span><span class="p">])</span>  <span class="c1"># end=&quot;&quot; make sure no return occurs</span>
    <span class="nb">print</span><span class="p">()</span>

<span class="k">def</span> <span class="nf">for_loop</span><span class="p">():</span>
    <span class="nb">print</span><span class="p">(</span><span class="s2">&quot;For loop output</span><span class="se">\n</span><span class="s2">&quot;</span><span class="p">)</span>
    <span class="k">for</span> <span class="n">record</span> <span class="ow">in</span> <span class="n">InfoDb</span><span class="p">:</span>
        <span class="n">print_data</span><span class="p">(</span><span class="n">record</span><span class="p">)</span>

<span class="n">for_loop</span><span class="p">()</span>
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">

<div class="output_area">

<div class="output_subarea output_stream output_stdout output_text">
<pre>For loop output

Finn Carpenter
	 Residence: San Diego
	 FavColor: Blue
	 Birth Day: December 12
	 Cars: [&#39;2012 Nissan Xterra&#39;]

Jake Warren
	 Residence: San Diego
	 FavColor: Blue
	 Birth Day: September 8
	 Cars: [&#39;2016-Toyota Tacoma&#39;]

erika carpenter
	 Residence: San Diego
	 FavColor: orange
	 Birth Day: 2/16/1965
	 Cars: tesla

</pre>
</div>
</div>

</div>
</div>

</div>
    {% endraw %}

</div>
 

