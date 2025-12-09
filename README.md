# Quantum-k-Nearest-Neighbors-QKNN-
 Implement a quantum version of the k-Nearest Neighbors algorithm for  Iris dataset. 
 
 Quantum KNN vs Classical KNN – Comparative Analysis

This project compares Classical k-Nearest Neighbors (KNN) with its quantum counterpart, Quantum KNN (QKNN), using a two-class subset of the Iris dataset. The goal is to evaluate whether quantum distance estimation can enhance similarity-based classification.

Key Features:-
->Implements Classical KNN using Euclidean distance (scikit-learn).
->Implements Quantum KNN using amplitude encoding and the Hadamard Test.
->Uses Qiskit AerSimulator for quantum circuit execution.
->Evaluates accuracy for k = 1 to 10.
->Includes normalization (L2) to prepare valid quantum states.

Findings:-
->Classical KNN achieves an accuracy of 0.90 for k = 3.
->QKNN achieves 0.833, slightly lower due to:
   Shot noise
   Controlled state-preparation errors
   Interference sensitivity
->QKNN shows stable behaviour and peaks near classical performance for some k values.
->Both methods converge near 0.90 for larger k.

Conclusion:-
The results show that while classical KNN currently performs better, QKNN successfully demonstrates quantum-based distance computation and lays groundwork for future quantum-accelerated machine learning as hardware continues to mature.
