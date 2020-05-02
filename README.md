<!-- Describe task in general -->
In mathematics, a set is a well-defined collection of distinct objects, considered as an object in its own right. For example, the numbers 2, 4, and 6 are distinct objects when considered separately, but when they are considered collectively they form a single set of size three, written {2, 4, 6}. The concept of a set is one of the most fundamental in mathematics.[4] Developed at the end of the 19th century,[5] set theory is now a ubiquitous part of mathematics, and can be used as a foundation from which nearly all of mathematics can be derived.
<p>
    <p>If every element of set <i>A</i> is also in <i>B</i>, then <i>A</i> is said to be a <i>subset</i> of <i>B</i>, written <i>A</i> ⊆ <i>B</i> (pronounced <i>A is contained in B</i>).<sup id="cite_ref-Hausdorff2005_30-0" class="reference"><a href="#cite_note-Hausdorff2005-30">[30]</a></sup> Equivalently, one can write <i>B</i> ⊇ <i>A</i>, read as <i>B is a superset of A</i>, <i>B includes A</i>, or <i>B contains A</i>.<sup id="cite_ref-Comninos2010_31-0" class="reference"><a href="#cite_note-Comninos2010-31">[31]</a></sup> The <a href="/wiki/Relation_(mathematics)" class="mw-redirect" title="Relation (mathematics)">relationship</a> between sets established by ⊆ is called <i>inclusion</i> or <i>containment</i>. Two sets are equal if they contain each other: <i>A</i> ⊆ <i>B</i> and <i>B</i> ⊆ <i>A</i> is equivalent to <i>A</i> = <i>B</i>.<sup id="cite_ref-Lucas1990_25-2" class="reference"><a href="#cite_note-Lucas1990-25">[25]</a></sup>
    </p>

If we represent a set {1, 2, 3, 4} by a list [1, 2, 3, 4], how can we do set operations in python using lists ?
</p>

<p style="text-align: center;">
    <img  title="example" src="{{MEDIA}}subset.png" alt="example" style="max-height: 83px"/>
</p>

<!-- Explain input and output values -->
<p>
    <strong>Input: </strong> Two arguments. Both are str.
</p>

<p>
    <strong>Output: </strong> bool. 
</p>


<!-- Give some usage examples -->
<div class="for_info_only">
    <p>
        <strong>Example:</strong>
    </p>

{% if interpreter.slug == "js-node" %}
<pre class="brush: javascript">

subset([1, 2, 3], [3, 1, 2]) == True
subset([1, 2], [3, 1, 2]) == True
subset([1, 2, 4], [3, 1, 2]) == False
</pre>
{% else %}
<pre class="brush: python">
subset([1, 2, 3], [3, 1, 2]) == True
subset([1, 2], [3, 1, 2]) == True
subset([1, 2, 4], [3, 1, 2]) == False
</pre>
{% endif %}
</div>


<!-- Here you can explain how it can be used in development -->
<!-- The section is optional -->
<p class="for_info_only">

    <strong>How it’s used: </strong>
    <i>(set operations are used to solve many many problems)</i>
</p>

<!-- Here you can explain some constraints for input-->
<!-- The section is optional -->
<p>
    <strong>Precondition:</strong>
    <i>Both sets are represented by arrays (python lists)</i>
</p>
