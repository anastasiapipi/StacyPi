References: qiskit.org

"""

Deutsch-Jozsa algorithm

This code creates the oracle to run Deutsch-Jozsa algorithm for n input qubits.
The oracle is then used to simulate the full circuit of the Deutsch-Jozsa algorithm
and analyse the outputs using noise free and noisy simulators.

HOW TO RUN THE FILE:

Inputs:
-the number of input qubits in n 
-input the string 'constant' to obtain an oracle for a constant function o 
r input the string 'balanced' to obtain an oracle for a balanced function. 



Outputs:

- n bits of 0's if function is contant 
- n bits 1's if function is balanced
-drawing of the circuit
-counts of outputs in noisy and noise free simulators
-execution times for different oracles with fixed n
-execution times for oracles with different n



"""

Bernstein Varizani algorithm

This code creates the oracle to run Bernstein Varizani for n input qubits.
The oracle is then used to simulate the full circuit of the Bernstein Varizani algorithm
and analyse the outputs using noise free and noisy simulators.

HOW TO RUN THE FILE:

Inputs:
-the number of input qubits in n 
-select secret bit string b or input the string 'random' to generate a random secret bit string



Outputs:

- returns secret bit string
-drawing of the circuit
-counts of outputs in noisy and noise free simulators
-execution times for different oracles with fixed n
-execution times for oracles with different n



"""

Simon's algorithm

This code creates the oracle to run Simon's for n input qubits.
The oracle is then used to simulate the full circuit of the Simon's algorithm
and analyse the outputs using noise free and noisy simulators.

HOW TO RUN THE FILE:

Inputs:
-the number of input qubits in n 
-select secret bit string b 



Outputs:

- return secret bit string plots and equations, solving them leads to secret bit string
-drawing of the circuit
-counts of outputs in noisy and noise free simulators
-execution times for different oracles with fixed n
-execution times for oracles with different n


"""

Grover's algorithm

This code creates the oracle to run Grover's for n input qubits.
The oracle is then used to simulate the full circuit of the Grover's algorithm
and analyse the outputs using noise free and noisy simulators.

HOW TO RUN THE FILE:

Inputs:
-the number of input qubits in n 
-select secret bit string b 



Outputs:

- returns bit string that we are looking for through unstructured search
-counts of outputs in noisy and noise free simulators
-execution times for different oracles with fixed n
-execution times for oracles with different n





"""

Quantum Approximate Optimization Algorithm for MaxCut NP-complete problem

This code outputs the solutions to a MaxCut NP-complete problem of your choice.


Inputs:
-Choose the number of edges,vertices and weights of the MaxCut graph
-Choose X-mixer by using string 'XO' or XY-mixer using 'XY' string 
-Choose IBM backend to run circuit

Ouputs:
-Solutions to MaxCut problem (output is a member of the qiskit circuit class)


"""

Quantum Circuit Simulator

The program simualtes the operations of a quantum computer by reading a .qasm file and executing the quantum gates 
on the qubits as instructed by the file. The program produces an intial state |0^{n}> where 'n' is the number of qubits
being simulated.

Input:
Assign the 'file_name' variable with the name of the QASM file you want to simulate. The number of qubits being 
simulated is defined as 'n0', it is read from the file bit can also be changed mannnually.

Output:
A list of strings indicating the state of each one of the qubits the program is simulating. 
e.g. if the final state of 3 qubits is |000>, the program returns ['0','0','0'].

