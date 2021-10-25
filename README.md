# QiskitFallFest2021Project
## Grover's Algorithm and Its Implementation on Hash Function
Our project uses Grover's Algorithm to search for potential collisions in a hash function.
Team member: Yundi Li, Sidh Suchdev, Lingyang Kong

## What's Grover's Algorithm?
Grover's algorithm is a quantum algorithm that can solve an unstructured search problem in significantly less time than traditional searching algorithms. It finds solutions in two steps: converting the problem into an *oracle* and marks the solutions by *amplification*. A oracle is a quantum circuit that represents the problem so the algorithm can perform calculations on it. Amplitude tells the probabily that a state happens. Grover's algorithm increases amplitudes of correct states and decreases amplitudes of incorrect ones - this is amplification.

## What's a Hash Function?
A hash function returns a unique value to a given input. This practice is called *hashing*. The function is useful in multiple ways; the most common implementations are to simplify the input and verify for uniqueness. For instance, the *SHA-256* is a function that gives a unique value by hashing the content in the file. However, hash functions are not impervious; they might give the same hash value for different inputs - we call this case *collision*. Collisions are problematic since they are by definition inconsistent with the purpose of hashing, especially in the field of cryptography.

## Our goal
We want to demonstrate that Grover's algorithm can be used to find collisions for hash functions. We will use the algorithm to find all possible inputs for a given hash value (output). Collisions would occur if we could see multiple states with equal nonzero probability on a histogram.

## Guidance
#[Our notebook](https://github.com/TexanElite/QiskitFallFest2021Project/blob/master/fall_fest_ut_austin_2021.ipynb)# presents our code along with explanations in text and quantum circuits. It can be opened in IBM Quantum Lab
