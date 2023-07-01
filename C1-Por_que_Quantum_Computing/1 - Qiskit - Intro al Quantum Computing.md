Recurso: https://learn.qiskit.org/course/introduction/why-quantum-computing#why-3-12


## Classifying computer algorithms

- **Complejidad lineal**: Podemos encontrar algoritmos que crecen **linealmente con el tamaño del problema**. Por ejemplo, la suma entre números conlleva un mayor tiempo a medida que usamos números más grandes.

- **Complejidad exponencial**: Adivinar una combinación de un PIN. Las posibles combinaciones de cifras entre 0 y 9 crecen como $10^d$ donde $d$ es el tamaño del PIN.

![[Complexity.png]]

## Why do we measure algorithms like this?

Si podemos encontrar algoritmos que crezcan de forma más eficiente, estos problemas intratables pueden convertirse de repente en manejables, incluso con ordenadores relativamente lentos o poco fiables. Aquí es donde entra en juego la computación cuántica.

**Computación Cuántica -> BUSCA ALGORITMOS COMPUTACIONALMENTE MÁS EFICIENTES**

## How can quantum computing help?

Los físicos crearon la física cuántica para explicar un comportamiento que nunca antes habían visto, y los informáticos descubrieron que podían (en teoría) explotar este comportamiento recién descubierto para crear algoritmos más eficientes. 

Como resultado, hay ciertos problemas que creemos intratables para los ordenadores convencionales, pero que son manejables para un ordenador "cuántico" que pueda explotar este comportamiento. Uno de ellos es la **factorización de números enteros**.

## Where are we now?

2 Problemas:
- Necesitamos más qubits
- Hay mucho ruido debido al entorno ideal necesario

Actualmente los ordenadores cuánticos son experimentales y, debido a las limitaciones mencionadas, aún tienen una performance peor que los algoritmos clásicos.

**Ventaja Cuántica**: Situación en la que tenga económicamente más sentido resolver un problema con un ordenador cuántico que con uno convencional.

![[Ventaja_Cuantica.png]]

La estimación para factorizar un número RSA de 617 dígitos en menos de un día suponía ~20 millones de qubits ruidosos. IBM dispone actualmente de un ordenador cuántico de 65 qubits, y su objetivo es crear un sistema con más de 1.000 qubits para 2023. Hay otros algoritmos que creemos que nos darán una ventaja cuántica mucho antes de este hito, pero aún puede parecer que estamos muy lejos.


## Vocabulary

Resources – 

A resource is anything the algorithm needs to run. In computer science, this usually means either the time needed by the algorithm, or the space (e.g. computer memory).

Intractable – 

An intractable problem is one which can be solved in theory, but requires too many resources in practice.

Core Year – 

Conventional computer chips are often made from processors called ["cores"](https://en.wikipedia.org/wiki/Multi-core_processor). A _core-year_ is the equivalent of using one of these cores continuously for a year. For reference, a modern laptops have around 2-4 cores. The meaning of this number depends on how powerful the core is, but this should give you a rough idea of the computing power involved.

RSA Number – 

RSA numbers are numbers taken from the RSA factoring challenge. These numbers are intentionally chosen to be difficult to factor.

'RSA' are the initials of three of the people that invented the protocol that uses these large numbers to encrypt information.

Qubit – 

A 'qubit' is a 'quantum bit'. We will study these later in this course.

Noise – 

Noise is useless information that's difficult to distinguish from useful information. For example, it's hard to hear someone talking to you if there are lots of other people talking loudly nearby.

Transistor – 

A transistor is an electronic device. They can be used to switch electric currents on and off, and can be used to build a computer processor.

Qiskit – 

Qiskit is a software development kit for working with quantum computers.

Math notations

NotationDescriptionThis is the average time our search algorithm takes to run.This is the number of digits in our secret number. Because this is a superscript, this means we are doing 10 to the power of d.'Proportional to': Everything to the left of this symbol is [proportional to](https://en.wikipedia.org/wiki/Proportionality_(mathematics)) the things on the right.