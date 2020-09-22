# QOSF-Mentorship
Solution of the task 2
## Task 2
Implement a circuit that returns $|01>$ and $|10>$ with equal probability.
Requirements :
-	The circuit should consist only of CNOTs, RXs and RYs. 
-	Start from all parameters in parametric gates being equal to 0 or randomly chosen. 
-	You should find the right set of parameters using gradient descent (you can use more advanced optimization methods if you like). 
-	Simulations must be done with sampling (i.e. a limited number of measurements per iteration) and noise. 

Compare the results for different numbers of measurements: 1, 10, 100, 1000. 

Bonus question:
How to make sure you produce state $\left|01\right> + \left|10\right>$ and not $\left|01\right> - \left|10\right>$?

(Actually for more careful readers, the “correct” version of this question is posted below:
How to make sure you produce state  $\left|01\right> + \left|10\right>$  and not any other combination of $\left|01\right> + e^{i\phi}\left|10\right>$|01> + |10⟩ (for example $\left|01\right> - \left|10\right>$)?)


## Solution

The solution const of the following steps:

1) Circuit implementation in qiskit.

2) Adding noise to the circuit.

3) Using error correction to filter the noise of the circuit.

4) The cost function.

5) The gradient descent optimization implementation.

6) Conclusion

7) Bonus Question
