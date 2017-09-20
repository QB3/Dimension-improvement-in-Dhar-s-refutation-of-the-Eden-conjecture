# Dimension improvement in Dhar’s refutation of the Eden conjecture

This project implented the method presented in the following paper <https://arxiv.org/pdf/1705.08143.pdf>.
It extends an old idea of Dhar in oreder to prove wrong the Eden conjecture in dimension 22.

## Getting Started

Copy the following command in your terminal to get the repo : 
$ git clone https://github.com/QB3/Dimension-improvement-in-Dhar-s-refutation-of-the-Eden-conjecture.git

### Prerequisites

Tou you need to have C++ 2011 installed

## Structure of the code

The main chunck of code is in the fonctions.cpp file. 
All the functions used in the computation are in fonctions.cpp.
The other files are main files used for lauching computation on real examples.



## Running the tests

To run the tests you can do it from command line. For instance to launch the computation of \mathbb(E)(\tau_1) you can enter the following line

$ cd Dimension-improvement-in-Dhar-s-refutation-of-the-Eden-conjecture

$ g++ -std=c++11 fonctions.cpp calcul_Tau_1 -o calcul_Tau_1.exe

$ ./calcul_Tau_1.exe

You can change the parameter $n_i$ in order bound roughly $T_{n_i}$ with $n_i$ as big as you want

### Computation of \mathbb(E)(\tau_2)

$ g++ -std=c++11 fonctions.cpp calcul_Tau_2 -o calcul_Tau_2.exe

$ ./calcul_Tau_2.exe

You can change the parameter $n_i$, $n_j$ in order bound roughly $T_{n_i, j}$ $T_{i, n_j}$ with $n_i$ and $n_j$ as big as you want.

### Computation of \mathbb(E)(\tau_3)

$ g++ -std=c++11 fonctions.cpp calcul_Tau_3 -o calcul_Tau_3.exe

$ ./calcul_Tau_3.exe

### Computation of \mathbb(E)(\tau_4)

$ g++ -std=c++11 fonctions.cpp calcul_Tau_4 -o calcul_Tau_4.exe

$ ./calcul_Tau_4.exe

### Computation of \mathbb(E)(\tau_5)

$ g++ -std=c++11 fonctions.cpp calcul_Tau_5 -o calcul_Tau_5.exe

$ ./calcul_Tau_5.exe

## Authors

* **Quentin Bertrand** 
* **Jules Pertinand**

## Acknowledgments

* We would like to thank Lucas Gerin. He kindly introduced us to the subject and took the time to answer all our questions.
* We also wanted to thank Pr. Deepack Dhar, he took the time to correspond with us for more than one month and gave us plenty of new ideas to catch lowder dimensions.

