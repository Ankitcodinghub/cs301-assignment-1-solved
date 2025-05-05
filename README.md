# cs301-assignment-1-solved
**TO GET THIS SOLUTION VISIT:** [CS301 Assignment 1 Solved](https://www.ankitcodinghub.com/product/cs301-assignment-1-solved-2/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;101330&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CS301 Assignment 1 Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 0px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            <span class="kksr-muted">Rate this product</span>
    </div>
    </div>
<div class="page" title="Page 1">
<div class="layoutArea">
<div class="column">
Problem 1 (Recurrences (10 points)) Give an asymptotic tight bound for T (n) in each of the following recurrences. Assume that T (n) is constant for n ≤ 2. No explanation is needed.

(a) T(n) = 2T(n/2) + n3 (b) T(n) = 7T(n/2) + n2

√

(c) T(n) = 2T(n/4) + n (d) T(n)=T(n−1)+n

Problem 2 (Longest Common Subsequence – Python) Consider the two algorithms for the Longest Common Subsequence problem, shown in Figures 1 and 2. Each algorithm takes two strings, X and Y, and two natural numbers, i and j, and re- turns the length of the longest common subsequence (LCS) between the prefixes X[0..i] and Y[0..j] of the given strings. The algorithm shown in Figure 1

is a naive recursive algorithm whereas the algorithm shown in Figure 2 is a slight variation with memoization. We can compute the length of the LCS of two given strings, using these two algorithms, as illustrated in Figure 3.

In the following, m is the length of the string X, and n is the length of the string Y.

(a) (20 points) According to the cost model of Python, the cost of computing the length of a string using the function len is O(1), and the cost of finding the maximum of a list of k numbers using the function max is O(k). Based on this cost model:

(i) What is the best asymptotic worst-case running time of the naive recur- sive algorithm shown in Figure 1? Please explain.

(ii) What is the best asymptotic worst-case running time of the recursive al- gorithm with memoization, shown in Figure 2? Please explain.

1

</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
CS301, Fall 2022

<pre>def lcs(X,Y,i,j):
    if (i == 0 or j == 0):
</pre>
<pre>       return 0
    elif X[i-1] == Y[j-1]:
</pre>
<pre>       return 1 + lcs(X,Y,i-1,j-1)
    else:
</pre>
</div>
<div class="column">
Assignment 1

</div>
</div>
<div class="layoutArea">
<div class="column">
<pre>       return max(lcs(X,Y,i,j-1),lcs(X,Y,i-1,j))
</pre>
Figure 1: A recursive algorithm to compute the LCS of two strings

<pre>def lcs(X,Y,i,j):
    if c[i][j] &gt;= 0:
</pre>
<pre>       return c[i][j]
</pre>
<pre>    if (i == 0 or j == 0):
       c[i][j] = 0
</pre>
<pre>    elif X[i-1] == Y[j-1]:
       c[i][j] = 1 + lcs(X,Y,i-1,j-1)
</pre>
<pre>    else:
       c[i][j] = max(lcs(X,Y,i,j-1),lcs(X,Y,i-1,j))
</pre>
<pre>    return c[i][j]
</pre>
Figure 2: A recursive algorithm to compute the LCS of two strings, with memo- ization

<pre>X = "acggacgggatctgggtccg"
Y = "tcccacatggtgcttccccg"
</pre>
<pre>lX = len(X)
lY = len(Y)
</pre>
<pre>#uncomment the next line to initialize c (for memoization)
#c = [[-1 for k in range(lY+1)] for l in range(lX+1)]
</pre>
<pre>print "Length of LCS is ", lcs(X,Y,lX,lY)
</pre>
Figure 3: An example: Computing the length of the LCS of two given DNA se- quences

2

</div>
</div>
</div>
<div class="page" title="Page 3">
<div class="layoutArea">
<div class="column">
CS301, Fall 2022 Assignment 1

(b) (30 points) Implement these two algorithms using Python. For each algorithm, determine its scalability experimentally by running it with different lengths of strings, in the worst case.

<ol>
<li>(i) &nbsp;Fill in following table with the running times in seconds.
Algorithm m=n=5 m=n=10 m=n=15 m=n=20 m=n=25 Naive

Memoziation

Specify the properties of your machine (e.g., CPU, RAM, OS) where you run your programs.
</li>
<li>(ii) &nbsp;Plot these experimental results in a graph.</li>
<li>(iii) &nbsp;Discussthescalabilityofthealgorithmswithrespecttotheseexperimen- tal results. Do the experimental results confirm the theoretical results you found in (a)?</li>
</ol>
(c) (40points)Foreachalgorithm,determineitsaveragerunningtimeexperimen- tally by running it with randomly generated DNA sequences of length m = n. For each length 5, 10, 15, 20, 25, you can randomly generate 30 pairs of DNA sequences, using Sequence Manipulation Suite.1

<ol>
<li>(i) &nbsp;Fill in following table with the average running times in seconds (μ), and the standard deviation (σ).
Algorithm m=n=5 m=n=10 m=n=15 m=n=20 m=n=25 μσμσμσμσμσ

Naive Memoization
</li>
<li>(ii) &nbsp;Plot these experimental results in a graph.</li>
<li>(iii) &nbsp;Discuss how the average running times observed in your experiments grow, compared to the worst case running times observed in (b).</li>
</ol>
&nbsp;

</div>
</div>
</div>
