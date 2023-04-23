Download Link: https://assignmentchef.com/product/solved-685-621-homework5
<br>
<ol>

 <li>The following problem is known as the <em>Dutch Flag Problem</em>. In this problem, the task is to rearrange an array of characters <em>R</em>, <em>W</em>, and <em>B </em>(for red, white, and blue, which are the colors of the Dutch national flag) so that all the <em>R</em>’s come first, all the <em>W</em>’s come next, and all the <em>B</em>’s come last. Design a linear, in-place algorithm that solves this problem.</li>

 <li> Give an <em>O</em>(<em>n</em>lg<em>k</em>)-time algorithm to merge <em>k </em>sorted lists into one sorted list, where <em>n </em>is the total number of elements in all the input lists. (<em>Hints</em>: Use a heap for <em>k</em>-way merging.)</li>

 <li></li>

</ol>

<h2>(a)  Note this is a Collaborative Problem</h2>

Consider the following algorithm for doing a postorder traversal of a binary tree with root vertex <em>root</em>.

<strong>Algorithm 1 </strong>Postorder Traversal <strong>function </strong>Postorder(<em>root</em>) <strong>if </strong><em>root </em>6= null <strong>then</strong>

Postorder(<em>root.left</em>) Postorder(<em>root.right</em>) visit <em>root</em>

<h1>end if end function</h1>

Prove that this algorithm run in time Θ(<em>n</em>) when the input is an <em>n</em>-vertex binary tree.

<h2>(b)</h2>

We define an AVL binary search tree to be a tree with the binary search tree property where, for each node in the tree, the height of its children differs by no more than 1. For 1

this problem, assume we have a team of biologists that keep information about DNA sequences in an AVL binary search tree using the specific weight (an integer) of the structure as the key. The biologists routinely ask questions of the type, “Are there any structures in the tree with specific weight between <em>a </em>and <em>b</em>, inclusive?” and they hope to get an answer as soon as possible. Design an efficient algorithm that, given integers <em>a </em>and <em>b</em>, returns true if there exists a key <em>x </em>in the tree such that <em>a </em>≤ <em>x </em>≤ <em>b</em>, and false if no such tree exists in the tree. Describe your algorithm in pseudocode <em>and </em>English. What is the time complexity of your algorithm? Explain.

<ol start="4">

 <li>[50 points] <em>Note this is a Collaborative Problem</em></li>

</ol>

<h2>(a)</h2>

Using either the Radial Basis Neural Network, Feed Forward Neural Network or Probabilistic Neural Network, classify the IRIS data set and the data generated in Problem 3 from HW 4 to determine how well your classifier works on both data sets.

<h2>(b)</h2>

Using the Support Vector Machine, classify the IRIS data set and the data generated in Problem 3 from HW 4 to determine how well your classifier works on both data sets.

<ol start="5">

 <li>[10 Bonus Points]</li>

</ol>

Using your implementation of EM or the built-in EM algorithm add the Bayes Classifier of Equation 8 in the Machine Learning I document. Use the IRIS data set and the data generated in Problem 3 from HW 4 to determine how well your classifier works. Compare the results against the Neural Network algorithm and the Support Vector Machine.