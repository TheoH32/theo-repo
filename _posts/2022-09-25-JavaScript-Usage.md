---
keywords: fastai
title: JavaScript Usage
toc: true
layout: default
description: Using JavaScript for the first time
nb_path: _notebooks/2022-09-25-JavaScript-Usage.ipynb
layout: notebook
---

<!--
#################################################
### THIS FILE WAS AUTOGENERATED! DO NOT EDIT! ###
#################################################
# file to edit: _notebooks/2022-09-25-JavaScript-Usage.ipynb
-->

<div class="container" id="notebook-container">
        
<div class="cell border-box-sizing text_cell rendered"><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<h1 id="This-is-documented-usage-of-some-JavaScript!">This is documented usage of some JavaScript!<a class="anchor-link" href="#This-is-documented-usage-of-some-JavaScript!"> </a></h1>
</div>
</div>
</div>
<div class="cell border-box-sizing text_cell rendered"><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<h2 id="Showing-how-variables-can-be-useful">Showing how variables can be useful<a class="anchor-link" href="#Showing-how-variables-can-be-useful"> </a></h2>
</div>
</div>
</div>
    {% raw %}
    
<div class="cell border-box-sizing code_cell rendered">
<div class="input">

<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-javascript"><pre><span></span><span class="nx">console</span><span class="p">.</span><span class="nx">log</span><span class="p">(</span><span class="s1">&#39;My name is Theo&#39;</span><span class="p">)</span>
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">

<div class="output_area">

<div class="output_subarea output_stream output_stdout output_text">
<pre>My name is Theo
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
<div class=" highlight hl-javascript"><pre><span></span><span class="kd">var</span> <span class="nx">msg</span> <span class="o">=</span> <span class="s1">&#39;My name is Theo&#39;</span>
<span class="nx">console</span><span class="p">.</span><span class="nx">log</span><span class="p">(</span><span class="nx">msg</span><span class="p">)</span>
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">

<div class="output_area">

<div class="output_subarea output_stream output_stdout output_text">
<pre>My name is Theo
</pre>
</div>
</div>

</div>
</div>

</div>
    {% endraw %}

<div class="cell border-box-sizing text_cell rendered"><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<h2 id="Real-world-application">Real world application<a class="anchor-link" href="#Real-world-application"> </a></h2>
</div>
</div>
</div>
    {% raw %}
    
<div class="cell border-box-sizing code_cell rendered">
<div class="input">

<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-javascript"><pre><span></span><span class="kd">var</span> <span class="nx">bread</span> <span class="o">=</span> <span class="mf">4</span><span class="p">;</span>
<span class="kd">var</span> <span class="nx">meat</span> <span class="o">=</span> <span class="mf">6</span><span class="p">;</span>
<span class="kd">var</span> <span class="nx">cake</span> <span class="o">=</span> <span class="mf">5</span><span class="p">;</span>
<span class="kd">var</span> <span class="nx">soda</span> <span class="o">=</span> <span class="mf">2</span><span class="p">;</span>

<span class="kd">let</span> <span class="nx">total</span> <span class="o">=</span> <span class="nx">cake</span> <span class="o">+</span> <span class="nx">bread</span><span class="p">;</span>
<span class="kd">var</span> <span class="nx">msg</span> <span class="o">=</span> <span class="s1">&#39;The price of cake and bread is &#39;</span><span class="p">;</span>
<span class="nx">console</span><span class="p">.</span><span class="nx">log</span><span class="p">(</span><span class="nx">msg</span> <span class="o">+</span> <span class="nx">total</span><span class="p">);</span>
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">

<div class="output_area">

<div class="output_subarea output_stream output_stdout output_text">
<pre>The price of cake and bread is 9
</pre>
</div>
</div>

</div>
</div>

</div>
    {% endraw %}

<div class="cell border-box-sizing text_cell rendered"><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<h2 id="Table-Building">Table Building<a class="anchor-link" href="#Table-Building"> </a></h2>
</div>
</div>
</div>
    {% raw %}
    
<div class="cell border-box-sizing code_cell rendered">
<div class="input">

<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-javascript"><pre><span></span><span class="kd">let</span> <span class="nx">team</span> <span class="o">=</span> <span class="p">[</span>
    <span class="p">{</span> <span class="nx">name</span><span class="o">:</span> <span class="s1">&#39;Theo Huntalas&#39;</span><span class="p">,</span> <span class="nx">role</span><span class="o">:</span> <span class="s1">&#39;Scrum Master&#39;</span> <span class="p">},</span>
    <span class="p">{</span> <span class="nx">name</span><span class="o">:</span> <span class="s1">&#39;Kush Sirohi&#39;</span><span class="p">,</span> <span class="nx">role</span><span class="o">:</span> <span class="s1">&#39;Dev Ops&#39;</span> <span class="p">},</span>
    <span class="p">{</span> <span class="nx">name</span><span class="o">:</span> <span class="s1">&#39;Mani Taleban&#39;</span><span class="p">,</span> <span class="nx">role</span><span class="o">:</span> <span class="s1">&#39;Frontend Dev&#39;</span> <span class="p">},</span>
    <span class="p">{</span> <span class="nx">name</span><span class="o">:</span> <span class="s1">&#39;Kaiden Do&#39;</span><span class="p">,</span> <span class="nx">role</span><span class="o">:</span> <span class="s1">&#39;Backend Dev&#39;</span> <span class="p">}</span>
<span class="p">];</span>

<span class="nx">console</span><span class="p">.</span><span class="nx">log</span><span class="p">(</span><span class="nx">team</span><span class="p">)</span>
</pre></div>

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
<div class=" highlight hl-javascript"><pre><span></span><span class="c1">// define an HTML conversion &quot;method&quot; associated with Classroom</span>
<span class="nx">Classroom</span><span class="p">.</span><span class="nx">prototype</span><span class="p">.</span><span class="nx">_toHtml</span> <span class="o">=</span> <span class="kd">function</span><span class="p">()</span> <span class="p">{</span>
    <span class="c1">// HTML Style is build using inline structure</span>
    <span class="kd">var</span> <span class="nx">style</span> <span class="o">=</span> <span class="p">(</span>
      <span class="s2">&quot;display:inline-block;&quot;</span> <span class="o">+</span>
      <span class="s2">&quot;background:purple;&quot;</span> <span class="o">+</span>
      <span class="s2">&quot;border: 2px solid grey;&quot;</span> <span class="o">+</span>
      <span class="s2">&quot;box-shadow: 0.8em 0.4em 0.4em grey;&quot;</span>
    <span class="p">);</span>
  
    <span class="c1">// HTML Body of Table is build as a series of concatenations (+=)</span>
    <span class="kd">var</span> <span class="nx">body</span> <span class="o">=</span> <span class="s2">&quot;&quot;</span><span class="p">;</span>
    <span class="c1">// Heading for Array Columns</span>
    <span class="nx">body</span> <span class="o">+=</span> <span class="s2">&quot;&lt;tr&gt;&quot;</span><span class="p">;</span>
    <span class="nx">body</span> <span class="o">+=</span> <span class="s2">&quot;&lt;th&gt;&lt;mark&gt;&quot;</span> <span class="o">+</span> <span class="s2">&quot;Name&quot;</span> <span class="o">+</span> <span class="s2">&quot;&lt;/mark&gt;&lt;/th&gt;&quot;</span><span class="p">;</span>
    <span class="nx">body</span> <span class="o">+=</span> <span class="s2">&quot;&lt;th&gt;&lt;mark&gt;&quot;</span> <span class="o">+</span> <span class="s2">&quot;Role&quot;</span> <span class="o">+</span> <span class="s2">&quot;&lt;/mark&gt;&lt;/th&gt;&quot;</span><span class="p">;</span>
    <span class="nx">body</span> <span class="o">+=</span> <span class="s2">&quot;&lt;/tr&gt;&quot;</span><span class="p">;</span>
    <span class="c1">// Data of Array, iterate through each row of compsci.classroom </span>
    <span class="k">for</span> <span class="p">(</span><span class="kd">var</span> <span class="nx">row</span> <span class="k">of</span> <span class="nx">compsci</span><span class="p">.</span><span class="nx">classroom</span><span class="p">)</span> <span class="p">{</span>
      <span class="c1">// tr for each row, a new line</span>
      <span class="nx">body</span> <span class="o">+=</span> <span class="s2">&quot;&lt;tr&gt;&quot;</span><span class="p">;</span>
      <span class="c1">// td for each column of data</span>
      <span class="nx">body</span> <span class="o">+=</span> <span class="s2">&quot;&lt;td&gt;&quot;</span> <span class="o">+</span> <span class="nx">row</span><span class="p">.</span><span class="nx">name</span> <span class="o">+</span> <span class="s2">&quot;&lt;/td&gt;&quot;</span><span class="p">;</span>
      <span class="nx">body</span> <span class="o">+=</span> <span class="s2">&quot;&lt;td&gt;&quot;</span> <span class="o">+</span> <span class="nx">row</span><span class="p">.</span><span class="nx">ghID</span> <span class="o">+</span> <span class="s2">&quot;&lt;/td&gt;&quot;</span><span class="p">;</span>
      <span class="nx">body</span> <span class="o">+=</span> <span class="s2">&quot;&lt;td&gt;&quot;</span> <span class="o">+</span> <span class="nx">row</span><span class="p">.</span><span class="nx">classOf</span> <span class="o">+</span> <span class="s2">&quot;&lt;/td&gt;&quot;</span><span class="p">;</span>
      <span class="nx">body</span> <span class="o">+=</span> <span class="s2">&quot;&lt;td&gt;&quot;</span> <span class="o">+</span> <span class="nx">row</span><span class="p">.</span><span class="nx">role</span> <span class="o">+</span> <span class="s2">&quot;&lt;/td&gt;&quot;</span><span class="p">;</span>
      <span class="c1">// tr to end line</span>
      <span class="nx">body</span> <span class="o">+=</span> <span class="s2">&quot;&lt;tr&gt;&quot;</span><span class="p">;</span>
    <span class="p">}</span>
  
     <span class="c1">// Build and HTML fragment of div, table, table body</span>
    <span class="k">return</span> <span class="p">(</span>
      <span class="s2">&quot;&lt;div style=&#39;&quot;</span> <span class="o">+</span> <span class="nx">style</span> <span class="o">+</span> <span class="s2">&quot;&#39;&gt;&quot;</span> <span class="o">+</span>
        <span class="s2">&quot;&lt;table&gt;&quot;</span> <span class="o">+</span>
          <span class="nx">body</span> <span class="o">+</span>
        <span class="s2">&quot;&lt;/table&gt;&quot;</span> <span class="o">+</span>
      <span class="s2">&quot;&lt;/div&gt;&quot;</span>
    <span class="p">);</span>
  
  <span class="p">};</span>
  
  <span class="c1">// IJavaScript HTML processor receive parameter of defined HTML fragment</span>
  <span class="nx">$$</span><span class="p">.</span><span class="nx">html</span><span class="p">(</span><span class="nx">compsci</span><span class="p">.</span><span class="nx">_toHtml</span><span class="p">());</span>
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">

<div class="output_area">

<div class="output_subarea output_text output_error">
<pre>
evalmachine.&lt;anonymous&gt;:3
Classroom.prototype._toHtml = function() {
^

ReferenceError: Classroom is not defined
    at evalmachine.&lt;anonymous&gt;:3:1
    at Script.runInThisContext (vm.js:96:20)
    at Object.runInThisContext (vm.js:303:38)
    at run ([eval]:1020:15)
    at onRunRequest ([eval]:864:18)
    at onMessage ([eval]:828:13)
    at process.emit (events.js:182:13)
    at emit (internal/child_process.js:812:12)
    at process._tickCallback (internal/process/next_tick.js:63:19)</pre>
</div>
</div>

</div>
</div>

</div>
    {% endraw %}

</div>
 

