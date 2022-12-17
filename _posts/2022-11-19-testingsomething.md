---
keywords: fastai
description: Lists and strings using variables
title: Data Abstraction
toc: true 
badges: true
comments: true
categories: [3.2]
nb_path: _notebooks/2022-11-19-testingsomething.ipynb
layout: notebook
---

<!--
#################################################
### THIS FILE WAS AUTOGENERATED! DO NOT EDIT! ###
#################################################
# file to edit: _notebooks/2022-11-19-testingsomething.ipynb
-->

<div class="container" id="notebook-container">
        
<div class="cell border-box-sizing text_cell rendered"><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<h2 id="Strings">Strings<a class="anchor-link" href="#Strings"> </a></h2><p>Strings is a series of characters (numbers, letters, etc), one example of a string is your name or your id because strings can contain both numbers and letters.</p>
<p>The following are all examples of strings being used in code, in this case, within print functions.</p>

</div>
</div>
</div>
    {% raw %}
    
<div class="cell border-box-sizing code_cell rendered">
<div class="input">

<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="nb">print</span><span class="p">(</span><span class="s2">&quot;hello world&quot;</span><span class="p">)</span>
<span class="nb">print</span><span class="p">(</span><span class="s1">&#39;hello&#39;</span><span class="p">)</span>
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">

<div class="output_area">

<div class="output_subarea output_stream output_stdout output_text">
<pre>hello world
hello
</pre>
</div>
</div>

</div>
</div>

</div>
    {% endraw %}

<div class="cell border-box-sizing text_cell rendered"><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<h2 id="Lists">Lists<a class="anchor-link" href="#Lists"> </a></h2><p>Lists are sequences of elements with each element being a variable. An example of a list can be the names of the students in this classroom.</p>
<h3 id="Features-of-Lists">Features of Lists<a class="anchor-link" href="#Features-of-Lists"> </a></h3><ul>
<li>The elements within the list can be accessed by index.</li>
<li>Can store various elements</li>
<li>The list is in order</li>
</ul>
<h3 id="Example-of-a-list">Example of a list<a class="anchor-link" href="#Example-of-a-list"> </a></h3>
</div>
</div>
</div>
    {% raw %}
    
<div class="cell border-box-sizing code_cell rendered">
<div class="input">

<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="n">thanksgivingList</span> <span class="o">=</span> <span class="p">[</span><span class="s2">&quot;cranberry pie&quot;</span><span class="p">,</span> <span class="s2">&quot;casserole&quot;</span><span class="p">,</span> <span class="s2">&quot;mashed potatoes&quot;</span><span class="p">,</span> <span class="s2">&quot;turkey&quot;</span><span class="p">]</span>
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">

<div class="output_area">

<div class="output_subarea output_stream output_stdout output_text">
<pre>casserole
casserole
</pre>
</div>
</div>

</div>
</div>

</div>
    {% endraw %}

<div class="cell border-box-sizing text_cell rendered"><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<h2 id="List-Index">List Index<a class="anchor-link" href="#List-Index"> </a></h2><p>An index is an element of a string. Indices typically start with 0, but Collegeboard has the index start at 1. Note that not all languages allow you to index from the end.</p>

</div>
</div>
</div>
    {% raw %}
    
<div class="cell border-box-sizing code_cell rendered">
<div class="input">

<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="nb">print</span><span class="p">(</span><span class="n">thanksgivingList</span><span class="p">[</span><span class="mi">1</span><span class="p">])</span> <span class="c1">#In this case, the index starts at 0, but in collegeboard, the index starts at 1</span>
<span class="nb">print</span><span class="p">(</span><span class="n">thanksgivingList</span><span class="p">[</span><span class="o">-</span><span class="mi">3</span><span class="p">])</span> <span class="c1">#Python can index from the end, in this case, &quot;turkey&quot; would be index -1 and 3. </span>
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">

<div class="output_area">

<div class="output_subarea output_stream output_stdout output_text">
<pre>casserole
casserole
</pre>
</div>
</div>

</div>
</div>

</div>
    {% endraw %}

<div class="cell border-box-sizing text_cell rendered"><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<h2 id="Questions">Questions<a class="anchor-link" href="#Questions"> </a></h2><ul>
<li>What is a list?</li>
<li>What is an element</li>
<li>What is an easy way to reference the elements in a list or string?</li>
<li>What is an example of a string?</li>
</ul>
<h2 id="Hacks">Hacks<a class="anchor-link" href="#Hacks"> </a></h2><ul>
<li>Create a list with indices </li>
<li>Index a part of the list that you created.</li>
<li>Try to index from the end </li>
</ul>

</div>
</div>
</div>
</div>
 
