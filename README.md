# AGAI-Quantum-Walk-On-Circular-Graphs-with-Search-Algorithms

## Work value: 
Make a complete experimental circuit, successfully compare classical and quantum random walks. 
The preliminary conclusion clearly shows the difference between classical bell-shaped distribution and quantum diffusion symmetrical distribution. 
This research can also be used as quantum teaching because The distribution of quantum random walk is very different from the classical one. 
It is very valuable as an introductory algorithm for beginners, and it can explain the phase interference problem at the beginning without misleading students. 
The H-gate combination must be able to Generate an average probability.

## Originality: 
For those who are new to quantum, random generation will think of the H gate that can produce an average superposition state.
In this experiment, it is found that the H gate cannot produce a symmetrical random walk, and the initial value of the phase of the H gate is corrected.
And successfully proposed a spherical quantum walk that has not been explained so far, and we can see the random distribution of its quantum. In the future, we hope that quantum random walk can be used to solve the mapping of enzymes in the real world to understand the contact with mutagens.
The time evolution of time enzymes, this problem only requires 33 nodes, these nodes can be mapped to 7 qubit circuits, the increase of qubits will increase the total time of 100 flips to 49 seconds.


## Features of the work: 
This work uses quantum computers in the emerging field of the 21st century for research and exploration, and uses the perspective of high school students to interpret the distribution of the quantum core algorithm-quantum random walk, and corrects the wave phase interference effect of the H gate. A new type of quantum random walk is used for phase correction. In the second part, a two-dimensional quantum walk circuit-spherical quantum walk, which is different from the mathematical formula in the paper, is also successfully proposed. The simulator is also used to see the distribution of quantum random walks, and the correction is also used. The latter quantum walk is different from the classical random walk to search for the target.


Here's a quick video presentation for our results.


The presentation file.


(The evolution of quantum random walk with Hadamard coin in 1D)

![mygif](https://user-images.githubusercontent.com/29524895/114307270-df84b200-9aac-11eb-9a89-21b3595e8328.gif)


One distinct feature in quantum random walk to its classical counterpart is that this coin register will continue interfere with its position state until it is measured, after all intermediate steps. The results are very different from classical random walks as it doesn’t converge to a Gaussian distribution, but rather evolves into an asymmetric probability distribution.

![CvQ](https://user-images.githubusercontent.com/29524895/114307395-6cc80680-9aad-11eb-8b76-9422735df91b.png)

In addition to the deviation from Gaussian, in this work we focus more on the asymmetric distribution in the quantum random walk where we see in above graph. As indicated in ref 3, such asymmetry arises because the Hadamard coin operator treats each basis vectors, |↑> and |↓> , differently by observing the phase difference.

In the Hadamard coin operator, the rightwards path interferes more destructively as it is multiplied by -1, however, the leftwards path undergoes more constructive interference and the system tends to take steps towards the left. To reach symmetric results, both base vectors will start in a superposition of states (between |↑> and |↓>). Another way to reach symmetry is use a different coin operator which doesn’t bias the coin towards a certain base vector.
