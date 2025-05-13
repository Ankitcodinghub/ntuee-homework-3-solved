# ntuee-homework-3-solved
**TO GET THIS SOLUTION VISIT:** [NTUEE Homework 3 Solved](https://www.ankitcodinghub.com/product/ntuee-homework-3-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;93642&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;NTUEE Homework 3 Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
1.&nbsp; Consider the semidefinite optimization problem minimize f0(x) = cT x

x∈Rn

subject to f1(x) = G +

</div>
<div class="column">
(1)

</div>
</div>
<div class="layoutArea">
<div class="column">
xiFi ⪯ O, wherec∈Rn,G,F1,…,Fn ∈Sn,f0 :Rn →R,andf1 :Rn →Sn.

</div>
</div>
<div class="layoutArea">
<div class="column">
(a) (5%) Determine if Problem (1) is a convex problem. Justify your answer.

</div>
</div>
<div class="layoutArea">
<div class="column">
<ol start="2">
<li>(b) &nbsp;(5%) Write the Lagrangian of the problem L(x, Z) where Z ∈ Sn is the Langrange multiplier associated with the generalized inequality constraint.</li>
<li>(c) &nbsp;(5%) Find the Lagrange dual function g(Z) and its domain dom g.</li>
<li>(d) &nbsp;(5%) Formulate the Lagrange dual problem. Determine if it is a convex problem.</li>
<li>(e) &nbsp;(7%) If Problem (1) is convex, please take the parameters defined in Table 1 and use CVX to solve the problem. Write down the optimal value and the optimal point you obtained from CVX. Denote them as p∗CVX and x∗CVX, respectively.</li>
<li>(f) &nbsp;(5%) Find a generalized logarithm ψ() that is concave, close, twice continuously differentiable, with dom ψ = int Sn+, and for all s &gt; 0, ψ(sy) = ψ(y)+θlogs. Find the degree θ of the ψ function you chose.</li>
<li>(g) &nbsp;(5%) Formulate the centrality problem with parameter t, where the objective function is written as f(x) = tf0(x)−ψ(−f1(x)). Find the domain of f.</li>
<li>(h) &nbsp;(8%) Find the gradient ▽f(x) and Hessian ▽2f(x), of f, respectively.

(Hint: It might be useful to note that if A is an invertible matrix whose entries are functions of a, then

∂A−1 = −A−1 ∂A A−1.) ∂a ∂a
</li>
<li>(i) &nbsp;(5%) Write a matlab m-file as a function which takes inputs t, c, F1 , F2 , F3 , G, and x, and evaluates the objective function at the point x, as well as the gradient and the Hessian.

Hint: the function can have a header that looks like the following, where F is a three-way array.

<pre>     function [f, g, H] = my_objective(x, t, c, F, G)
</pre>
</li>
<li>(j) &nbsp;(5%) From this step on, write another m-file as the main function for your program to solve the centrality problem. Set c, Fi’s, and G as in Table 1 and set the initial point x(0) = 0. Hint: the function may be declared something simliar to the following. You don’t have to use exactly the same names of the function parameters, though. 1
<pre>     function [x_central, lambda_2_2] = centrality_problem(x_init, t, c, F, G, alpha, beta)
</pre>
</li>
<li>(k) &nbsp;(5%) Use the Newton step’s formula: ∆x = −(▽2f(x))−1▽f(x) and calculate the Newton step ∆x(k) nt nt
for the kth inner iteration.
</li>
<li>(l) &nbsp;(5%) Calculate the Newton decrement λ(k)(x) = (−▽f(x)T∆x(k))1/2. Store the values of λ(k)2/2 of
each iteration for future use.
</li>
<li>(m) &nbsp;(5%) Perform backtracking line search along search direction using β = 0.7 starting from s = 1 until
f(x + s∆x(k)) ≤ f(x) − αsλ(k)(x)2, where α = 0.1. 2 nt
</li>
<li>(n) &nbsp;(5%) Perform the update x(k+1) = x(k) + s∆x(k). Determine whether λ2/2 ≤ ε where ε = 10−8. nt inner
Terminate the iteration loop if it is true.
</li>
</ol>
1The m-file for solving the centrality problem shall return the central point as will as a list of λ2/2 for each iteration.

2We use s to denote the backtracking parameter instead of t because t has been used as the centrality problem’s parameter.

</div>
</div>
<div class="layoutArea">
<div class="column">
∑n i=1

</div>
</div>
<div class="layoutArea">
<div class="column">
nt

</div>
</div>
<div class="layoutArea">
<div class="column">
1

</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
<ol start="15">
<li>(o) &nbsp;(5%) In your main script m-file, set μ = 2 and t(0) = 1. Write a loop to solve the centrality problem for t, starting from t = t(0), by calling the function you wrote from (j) to (n). Terminate this outer loop if n/t &lt; εouter where εouter = 10−8. When an outer loop iteration is done, do not reset the inner loop index k, letting it represent the total number of Newton steps being run at any given moment. Use l to denote the outer loop index and denote the centrality point of the lth outer loop as x∗(t(l)) where t(l) = μt · t(0) is the centrailty problem’s parameter in the lth outer iteration, l ≥ 0.</li>
<li>(p) &nbsp;(5%) Compare the optimal value p∗ and optimal point x∗ you obtained with those obtained from CVX as in (e). Specifically, calculate |p∗ − p∗CVX| and ||x∗ − x∗CVX||2, respectively.</li>
<li>(q) &nbsp;(5%) Plot f0(x∗(t(l))) − p∗ versus l in log-scale.</li>
<li>(r) &nbsp;(5%) Plot λ(k)2/2 versus k in log-scale.</li>
<li>(s) &nbsp;(5%) Submit your source code as hw3.m or hw3.py.

Parameters n  F1  F2 </li>
</ol>
</div>
</div>
<div class="layoutArea">
<div class="column">
3

</div>
</div>
<div class="layoutArea">
<div class="column">
0.9  −0.4

0.6

</div>
<div class="column">
−0.4 0.6

3.9 −1.0 

−1.0 2.7 F3

</div>
<div class="column">


</div>
<div class="column">
0.5

0.8 −1.0

</div>
<div class="column">
0.8 −1.0

1.7 −2.6  −2.6 5.4

G

</div>
</div>
<div class="layoutArea">
<div class="column">
Parameters  c 

−4

 −2  −4

</div>
</div>
<table>
<tbody>
<tr>
<td>
<div class="layoutArea">
<div class="column">


</div>
</div>
<div class="layoutArea">
<div class="column">
0.2 0.1  0.1 0.6

0.6 −0.1

</div>
<div class="column">
0.6 −0.1 

3.3

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">


−1.2 0.5 −1.2

 0.5 −1.4 −1.0  −1.2 −1.0 −3.3

</div>
</div>
</td>
<td></td>
</tr>
</tbody>
</table>
<div class="layoutArea">
<div class="column">
Guidelines of Homework Submission:

</div>
</div>
<div class="layoutArea">
<div class="column">
Table 1: Parameters for the SDP Problem

</div>
</div>
</div>
