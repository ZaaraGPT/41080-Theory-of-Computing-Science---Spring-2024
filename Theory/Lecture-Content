# Week 1

What problems can be computed efficiently? Computibility theory accounts for problems which can be solved by computers.

**Integer multiplication** - Given 2 integers _a_ and _b_ compute *a*x*b*

When we multiply 113x127 we do around 20 operations of multiplication and addition (long multiplication) to produce the result.\
Given two n-digit integers, the long multiplication method gives an algorithm in time Θ(n^2) - being any mathmatical function. Polynomial time.

In algorithm analysis, measure the running time of algorithm in terms of the input size n - the function unit. This is no concrete number, instead used to observe the increasing trend - Asymptotic analysis. Practical efficiency can be different thus providing us two viewpoints for application assessment.

> So... how fast can we multiply integers? _Given two n-digit integers, the long multiplication method gives an algorithm in time Θ(n^2)._ Can this be improved? Karatsuba proposed Θ(n^1.58). Further? Θ(n*logn*). Theoretically should be faster in determining the result but such an algorithim would be too complicated to run in comparison. Asymptotic and Practical analysis differs!

**Integer factorisation** - Given integer _c_, compute non-trivial factorisation of c = *a*x*b*

Finding the proper factors to the number 14351. (Attempt square root and developing the answer, Proper factors must contain a prime number)\
The time to calculate is roughly the function exp(1/2n). Improved is exp(3√n). Exponential time.

Applying this function, a 240 digit integer this time is estimated to take 900 years of computation! The HTTPS protocol (Transport Layer Security) utilises the RSA protocol which ensures security due to requiring factorisation to break RSA.

**Cobham-Edmonds thesis** - A function that can be efficiently solved by a computer ONLY IF it admits a polynomial-time algorithim. This establishes the complexity class P.

Complexity class NP - NP is the set of decision problems for which the problem instances, where the answer is "yes", have proofs verifiable in polynomial time by a deterministic Turing machine. Eg. Hamiltonian cycle.

So we formulate questions as... Is there a (P) Polynomial-time for the (NP) Hamiltonian cycle problem?
