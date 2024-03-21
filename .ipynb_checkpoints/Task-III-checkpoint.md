# QML-HEP GSoC 2024 Tasks

## Task III: Open Task

Please comment on quantum computing or quantum machine learning. You can also
comment on one quantum algorithm or one quantum software you are familiar with.
You can also suggest methods you think are good and you would like to work on.

<hr>

#### A Little about how I developed my interest in the field
In High school, I was introduced to the concept of Schrodinger's Cat for the first time and it completely roped me in! Later, I enrolled in a course by the coding school on Quantum Computing, that turned out to be an enriching experience in understanding the fundamentals of quantum mechanics and computing. With time, I made a youtube series on the basics of quantum computing to encapsulate my learnings, which helped me in becoming IBM Quantum Advocate. Recently, I participated in TCS Quantum Challenge to develop a quantum solution for flight allocation problem. 

#### Quantum Mechanics and Computing
In the classical world, bits represents either of the 2 states, 0 or 1. We use bits to represent all the characters we use, all the code that the machine understands and even the emoticons. What do these bits represent physically? Flow of current through the transistors in our devices, if the current is flowing the bit will be 1 and if not then 0. Essentially, controlled flow of electrons through transistors gave rise to computers as we know them.

So What's the problem?

The number of transistors in a given area is exponentially increasing due to their decreasing size. They are so small now that the area of a coin contains billions of them and we can compare the size of an transistor with a skyscrapper, then the atom would be a man. As the size of transistors is getting smaller, its switch like property to the flow of currents is diminishing, electrons are able to move through the barrier that transistors used be, giving rise to quantum tunnelling. This breaks the switch like property of the Transistor, the basis of Classical Computing

Why Quantum Computing?
Simply put, it solves the physical limitations of classical Computing and adds Quantum speed up

Quantum Computing Basics
From Eistiens's photoelectric effect, we know photons are particles and from double slit experiment we know that electrons are wave-like, both of them together establish the wave-particle duality nature of particles. Meaning, a qubit (quantum bit) can be in multiple states simultaneously (0,1, and everything in between) until we measure it and it collapses into a classical bit of 1 or 0. Analogous to a spinning coin represting a qubit and then it collapses into a bit of heads or tails. In simple terms, classical computing is deterministic and quantum computing is probablistic. The same amount of information 8 classical bits store can be stored in 3 qubits, whichs given quantum solution an exponential speedup. Imagine, a child is searching for something in a room and can look at 3 places, it will look at the 3 places one by one, it finds the object in the last place and looking at each place cost a second then the total time taken was 3 seconds, but if their are 3 children they all can look at the 3 places simultaneously and 1 of them will find the object and time spent would only be 1 sec. That's how the multiple states represneted by a qubit add to quantum speed-up.

These 3 weird quantum properties enable the design of quantum algorithms which can compute in ways classical computers cannot, making quantum computers more powerful for solving certain types of problems are interference, superposition and entanglement.
Intereference: Wave like nature of particles
Superposition: Being in multiple states before measurement
Enatanglement: if one qubit is measured, then we can correctly predict the state of the qubit it is entangled with, without measuring for it and even if they are far away.



// fit in places
In my opinion, quantum mechanics lays down the mathematics for quantum computing solutions. How is the quantum realm different from classical? The bits become qubits. We know that a bit can be either 0 or 1, like the 2 sides of a coin. A qubit is just an extension of bit wherein we consider it's state to be 0, 1 and everyting in between at a given time until we measure the state and all the possibilites that are associated with a qubit collapse into a bit, like a spinning coin is 0 and 1 at the same time and on measurement collapases to either. But while it's spinning, we can encoding more number of possibilites which give quantum solution the advantage of speed-up over classical solutions. The 3 main concepts of quantum mecahnics are Superposition, Entanglement and Speed-up. Everything else is an extension of these 3 concepts.
Link: https://www.youtube.com/watch?v=WMRsQxDJ19Q&list=PLY6CWF3NWYvTducILRZCATDwW9DjZvumJ&index=1

#### Quantum Algorithm or Quantum Software


2 algos and learnt during were qaoa and wsqaoa, boiling them done to the very basics and we deal with superposition and entanglement. 

ps, how we approaches,, 2 algos, why them?