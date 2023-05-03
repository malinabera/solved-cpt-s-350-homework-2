Download Link: https://assignmentchef.com/product/solved-cpt-s-350-homework-2
<br>



Please print your name!

<ol>

 <li>(easy) Write psuedo-code for partition(<em>A,p,q</em>).</li>

 <li>(standard) Consider insertsort. Suppose that the input array <em>A </em>has 1% probability to be monotonically decreasing. Show that, in this case, the average-case complexity of insertsort is Θ(<em>n</em><sup>2</sup>).</li>

 <li>(not hard) Let iqsort(<em>A,</em>1<em>,n</em>) be an algorithm that sorts an array <em>A </em>with <em>n </em> It works as follows:</li>

</ol>

iqsort(<em>A,p,q</em>){ if <em>p </em>≥ <em>q</em>, return; <em>r</em>=partition(<em>A,p,q</em>);

//run quick sort on the low part quicksort(<em>A,p,r </em>− 1); //run insert sort on the high part insertsort(<em>A,r </em>+ 1<em>,q</em>);

}

Compute the best-case, worst-case, and average-case complexities of iqsort.

<ol start="4">

 <li>(hard) Let mixsort(<em>A,</em>1<em>,n</em>) be an algorithm that sorts an array <em>A </em>with <em>n </em> It works as follows:</li>

</ol>

mixsort(<em>A,p,q</em>){ if <em>p </em>≥ <em>q</em>, return; <em>r</em>=partition(<em>A,p,q</em>);

//run mixsort on the low part mixsort(<em>A,p,r </em>− 1);

//run insert sort on the high part insertsort(<em>A,r </em>+ 1<em>,q</em>);

}

Compute the best-case, worst-case, and average-case complexities of mixsort.

1