# MCMC
## Monte Carlo Method

![image](https://github.com/deepanshuIITM/MCMC/assets/137225940/4a1436fe-db46-417f-b643-d5060a848099)

![image](https://github.com/deepanshuIITM/MCMC/assets/137225940/5282b414-56eb-4d37-a53f-829acb012734)

**Fig. The integral of a complex function using Monte Carlo Simulation**

![image](https://github.com/deepanshuIITM/MCMC/assets/137225940/0fc4d292-94f7-4292-a551-290e7920272e)

**Variation of integral value for different Sample Size**

## Markov Chain Monte Carlo Method for identifying manufacturing defects

![image](https://github.com/deepanshuIITM/MCMC/assets/137225940/fc5e78bc-6c08-44f2-9d25-83dc17456908)

![image](https://github.com/deepanshuIITM/MCMC/assets/137225940/fcc6af4a-dbce-44a2-815a-9c017c9eb4a0)

**Fig. Three states in MCMC algorithms for non-defective manufacturing of bolt assembly**

Given Probability Transition matrix P:
<br> $$
\begin{pmatrix}
1-p & p & 0 & 0 \\
p & 1-2p & p & 0 \\
0 & p & 1-2p & p \\
0 & 0 & p & 1-p \\
\end{pmatrix}
$$
<br> For p = $\frac{1}{3}$ Probability Transition matrix P:
<br>$$
\begin{pmatrix}
2/3 & 1/3 & 0 & 0 \\
1/3 & 1/3 & 1/3 & 0 \\
0 & 1/3 & 1/3 & 1/3 \\
0 & 0 & 1/3 & 2/3 \\
\end{pmatrix}
$$
<br> Now, $P_{4\times4} \pi_{4\times1} = \pi_{4\times1}$ ..... (1)
<br> Where $\pi_{4\times1} = [\pi_{1} , \pi_{2}, \pi_{3}, \pi_{4}]$
<br> From (1) we will get the following equations:
<br> $$ \frac{2}{3} \pi_{1} + \frac{1}{3} \pi_{2} = \pi_{1} ........(i)$$
<br> $$ \frac{1}{3} \pi_{1} + \frac{1}{3} \pi_{2} + \frac{1}{3} \pi_{3} = \pi_{2} .........(ii)$$
<br> $$ \frac{1}{3} \pi_{2} + \frac{1}{3} \pi_{3} + \frac{1}{3} \pi_{4} = \pi_{3} .........(iii)$$
<br> $$ \frac{1}{3} \pi_{3} + \frac{2}{3} \pi_{4} = \pi_{4} ........(iv)$$
<br> From equation (i) : $\pi_{1} = \pi_{2}$
<br> From equation (ii) : $\pi_{3} = \pi_{2}$  (Using  $\pi_{1} = \pi_{2}$)
<br> From equation (iii) : $\pi_{3} = \pi_{4}$ 
<br> Again $\sum_{i = 1}^{4} \pi_{i} = 1  $
<br> So, $\fbox{$\pi_{1} = \pi_{2} = \pi_{3} = \pi_{4} = 0.25$}$

**References:**
[1]. Bertsekas, D., & Tsitsiklis, J. N. (2008). Introduction to probability (Vol. 1). Athena Scientific.

