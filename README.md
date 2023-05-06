Download Link: https://assignmentchef.com/product/solved-ee239as-homework1-linear-algebra-refresher
<br>
<ol>

 <li><strong>Linear algebra refresher.</strong>

  <ul>

   <li> Let <strong>A </strong>be a square matrix, and further let <strong>AA</strong><em><sup>T </sup></em>= <strong>I</strong>.

    <ol>

     <li> Construct a 2 × 2 example of <strong>A </strong>and derive the eigenvalues and eigenvectors of this example. Show all work (i.e., do not use a computer’s eigenvalue decomposition capabilities). You may not use a diagonal matrix as your 2 × 2 example. What do you notice about the eigenvalues and eigenvectors?</li>

     <li>) Show that <strong>A </strong>has eigenvalues with norm 1.</li>

    </ol></li>

  </ul></li>

</ol>

<ul>

 <li> Show that the eigenvectors of <strong>A </strong>corresponding to distinct eigenvalues are orthogonal. iv. (3 points) In words, describe what may happen to a vector <strong>x </strong>under the transformation <strong>Ax</strong>.</li>

</ul>

<ul>

 <li> Let <strong>A </strong>be a matrix.

  <ol>

   <li> What is the relationship between the singular vectors of <strong>A </strong>and the eigenvectors of <strong>AA</strong><em><sup>T</sup></em>? What about <strong>A</strong><em><sup>T</sup></em><strong>A</strong>?</li>

   <li> What is the relationship between the singular values of <strong>A </strong>and the eigenvalues of <strong>AA</strong><em><sup>T</sup></em>? What about <strong>A</strong><em><sup>T</sup></em><strong>A</strong>?</li>

  </ol></li>

 <li> True or False. Partial credit on an incorrect solution may be awarded if you justify your answer.</li>

</ul>

<ol>

 <li>Every linear operator in an <em>n</em>-dimensional vector space has <em>n </em>distinct eigenvalues. ii. A non-zero sum of two eigenvectors of a matrix <strong>A </strong>is an eigenvector.

  <ul>

   <li>If a matrix <strong>A </strong>has the positive semidefinite property, i.e., <strong>x</strong><em><sup>T</sup></em><strong>Ax </strong>≥ 0 for all <strong>x</strong>, then its eigenvalues must be non-negative.</li>

  </ul></li>

</ol>

<ol>

 <li>The rank of a matrix can exceed the number of non-zero eigenvalues.</li>

 <li>A non-zero sum of two eigenvectors of a matrix <strong>A </strong>corresponding to the same eigenvalue <em>λ </em>is always an eigenvector.</li>

</ol>

<ol start="2">

 <li><strong>Probability refresher.</strong>

  <ul>

   <li> A jar of coins is equally populated with two types of coins. One is type “H50” and comes up heads with probability 0<em>.</em> Another is type “H60” and comes up heads with probability 0<em>.</em>6.

    <ol>

     <li>You take one coin from the jar and flip it. It lands tails. What is the posterior probability that this is an H50 coin?</li>

     <li> You put the coin back, take another, and flip it 4 times. It lands T, H, H, H. How likely is the coin to be type H50?</li>

    </ol></li>

  </ul></li>

</ol>

<ul>

 <li> A new jar is now equally populated with coins of type H50, H55, and H60 (with probabilities of coming up heads 0<em>.</em>5, 0<em>.</em>55, and 0<em>.</em>6 respectively. You take one coin and flip it 10 times. It lands heads 9 times. How likely is the coin to be of each possible type?</li>

</ul>

<ul>

 <li> Consider a pregnancy test with the following statistics.

  <ul>

   <li>If the woman is pregnant, the test returns “positive” (or 1, indicating the woman is pregnant) 99% of the time.</li>

   <li>If the woman is not pregnant, the test returns “positive” 10% of the time.</li>

   <li>At any given point in time, 99% of the female population is not pregnant.</li>

  </ul></li>

</ul>

What is the probability that a woman is pregnant given she received a positive test?

The answer should make intuitive sense; given an explanation of the result that you find.

<ul>

 <li> Let <em>x</em><sub>1</sub><em>,x</em><sub>2</sub><em>,…,x<sub>n </sub></em>be identically distributed random variables. A random vector, <strong>x</strong>, is defined as</li>

</ul>

 <em>x</em><sub>1 </sub>  <em>x</em><sub>2 </sub> <strong>x </strong>=  … 





<em>x<sub>n</sub></em>

What is E(<strong>Ax </strong>+ <strong>b</strong>) in terms of E(<strong>x</strong>), given that <strong>A </strong>and <strong>b </strong>are deterministic?

<ul>

 <li> Let <strong>cov</strong></li>

</ul>

What is <strong>cov</strong>(<strong>Ax </strong>+ <strong>b</strong>) in terms of <strong>cov</strong>(<strong>x</strong>), given that <strong>A </strong>and <strong>b </strong>are deterministic?

<ol start="3">

 <li><strong>Multivariate derivatives.</strong>

  <ul>

   <li> Let <strong>x </strong>∈R<em><sup>n</sup></em>, <strong>y </strong>∈R<em><sup>m</sup></em>, and <strong>A </strong>∈R<em><sup>n</sup></em><sup>×<em>m</em></sup>. What is ∇<strong><sub>x</sub>x</strong><em><sup>T</sup></em><strong>Ay</strong>?</li>

   <li>What is ∇<strong><sub>y</sub>x</strong><em><sup>T</sup></em><strong>Ay</strong>?</li>

   <li>What is ∇<strong><sub>A</sub>x</strong><em><sup>T</sup></em><strong>Ay</strong>?</li>

   <li> Let <em>f </em>= <strong>x</strong><em><sup>T</sup></em><strong>Ax </strong>+ <strong>b</strong><em><sup>T</sup></em><strong>x</strong>. What is ∇<strong><sub>x</sub></strong><em>f</em>?</li>

   <li> Let <em>f </em>= tr(<strong>AB</strong>). What is ∇<strong><sub>A</sub></strong><em>f</em>?</li>

  </ul></li>

 <li><strong>Deriving least-squares with matrix derivatives.</strong></li>

</ol>

In least-squares, we seek to estimate some multivariate output <strong>y </strong>via the model

<strong>y</strong>ˆ = <strong>Wx</strong>

In the training set we’re given paired data examples (<strong>x</strong><sup>(<em>i</em>)</sup><em>,</em><strong>y</strong><sup>(<em>i</em>)</sup>) from <em>i </em>= 1<em>,…,n</em>. Leastsquares is the following quadratic optimization problem:

<strong>Wx</strong>

Derive the optimal <strong>W</strong>.

Hint: you may find the following derivatives useful:

<em>∂</em>tr(<strong>WA</strong>)                   <em><sub>T</sub></em>

= <strong>A</strong>

<em>∂</em><strong>W</strong>

<em>∂</em>tr(<strong>WAW</strong><em><sup>T</sup></em>)                         <em><sub>T</sub></em>

= <strong>WA </strong>+ <strong>WA</strong>

<em>∂</em><strong>W</strong>

<ol start="5">

 <li>(30 points) <strong>Hello World in Jupyer.</strong></li>

</ol>

Complete the Jupyter notebook linear regression.ipynb. Print out the Jupyter notebook and submit it to Gradescope.