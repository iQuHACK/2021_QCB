# Quantum Whack-A-Mole
A slightly violent way to learn quantum circuits
## Team: QCB
Abhay Agarwal, Emiliia Dyrenkova, Andris Huang
## Abstract
Quantum computing is a recently booming field that attracts more and more people from different generations. Students started to hear about quantum computing and be interested in it at an earlier and earlier age. However, due to the intricate nature of the field, it is harder for young students to understand the mechanism or methodology of quantum algorithms than classical ones. As a result, we design the Quantum Whack-A-Mole game to give young students an interacting platform for implenting circuits in the form of a common game. The game requires 2 qubits to simulate four holes with their four states. The amplitude of each state indicates and represents the probability of finding the mole in the corresponding hole. In this game, the players are essentially asked to construct the ciruit by themselves to maximize the amplitude of any one of the state, i.e. maximizing the probability of finding the mole in one particular hole of their choice so that they could easily hit the mole. Through the game, players would improve their ability to implement quantum circuit by devising strategies to maximize the amplitude.

## How to play the game
1. To start with, the player is given the option to use a Quantum Hammer or a Classical Hammer. The Quantum Hammer will give the amplitude of the state that represents the corresponding "hole". The Classical Hammer is equivalent to a measurement, through which the player will terminate the game and find out if the mole is in the corresponding "hole".
2. If the players chose the Quantum Hammer, they will then have the option to add a gate to the circuit to manipulate the amplitude of a state (i.e. probability of finding the mole in the "hole") of their choice.
3. If the gate needs additional information (Ex. H, CNOT), the players will then be asked to input the information.
4. A circuit will be shown, and the players will be asked again for their hammer option.
5. The game ends when the players use the Classical Hammer to hit one "hole" of their choice. The quibts will be measured and the resulting state will be used to compare with the "hole" that the players choose. If the results match, a winning message will be shown; otherwise, the players will unfortunately loose the game.

## What Is Quantum About the Game
This game differs from the classical Whack-A-Mole in that the players could manipulate the probability of finding the mole in one hole of thier choice

## Details About the Implementation
We implement the code with qiskit and numpy and simulate the circuit using the IonQ simulator and quantum computer with 11 qubits. To access the code, download the scripts, install qiskit, and run mainpy.
## Date
January 31, 2021
