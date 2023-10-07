# Binary-classification-on-an-IBM-quantum-computer

Implementation of a binary classifier on an IBM quantum machine. In particular, a classification algorithm based on cosine similarity is used to test different quantum processors. This work is my bachelor's thesis in physics.

Given a training dataset consisting of $N$ real $d$-dimensional vectors and their binary labels, the algorithm can correctly classify any other $d$-dimensional unlabelled input vector. To test the algorithm on quantum processors, quantum circuits, with $N = d = 2$, were implemented using IBM Quantum,
which is an online platform that offers cloud access to IBM’s quantum computers. 
The software development kit Qiskit was used to implement and run the algorithm and to save the obtained results. Different training datasets were examinated, for each of which different unlabelled input vectors were considered. \
The results obtained are not yet optimal. The classification is performed correctly only under certain conditions on the training and test vectors. See [Thesis.pdf](Thesis.pdf) for more details. 
