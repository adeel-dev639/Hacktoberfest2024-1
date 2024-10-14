<h4>Binary Search Using Recursion</h4>
<h3>Explanation:</h3>
<ul>
<li>you have to find in target Number in Array arr</li>
<li>At First Declare Array and target then call search Function</li>
<li>In this Function,I pass Array (arr),Target (target),Start(s),End(e)</li>
<li>here s is Starting Index of Array,e is the End index of Array</li>
<li>then a condition if s grater then e then return -1</li>
<li>then m is middle index element</li>
<li>if arr[m] is equal to target,then return m</li>
<li>then else if condition if arr[m] is less then target then again call search Function But cange value of s to m+1.</li>
<li>and then else condition Again call search Function but change value of e to m-1</li>
<li>After Completion the program if target is present it will return target's Index , if not found then print -1.</li>
</ul>