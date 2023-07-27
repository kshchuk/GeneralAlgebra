# GeneralAlgebra Qt Project

This is a collaborative Qt project aimed at implementing a system for long modular arithmetic over a prime modulo N. The project involves various mathematical tasks related to finite fields, polynomial rings, and more. The ultimate goal is to create a single program with a graphical user interface that integrates all the functionalities in a structured and organized manner.

## Features

The project will cover the following tasks:

1. **Graphical User Interface**:
   - Responsible for the overall architecture of the project.

2. **Finite Field**:
   - Addition, subtraction, and multiplication of numbers.
   - Finding the inverse element and division of numbers.
   - Fast modular exponentiation using Montgomery reduction.

3. **Factorization of Numbers**:
   - Naive algorithm and Pollard's algorithm.
   - Computing the square root of a number.
   - Computing the discrete logarithm of a number.
   - Finding the order of an element in a group and determining if the element is a generator of the multiplicative group of the field.

4. **Euler's Function and Carmichael Function**:
   - Calculating Euler's function of a given number.
   - Calculating Carmichael function of a given number.
   - Probability testing for primality using the Miller-Rabin test.

5. **Polynomial Rings**:
   - Addition, subtraction, and multiplication of two polynomials.
   - Finding the derivative of a polynomial and evaluating a polynomial at a given point.
   - Finding the quotient and remainder of polynomial division and the greatest common divisor of two polynomials.

6. **Circular Polynomials**:
   - Factorizing circular polynomials into irreducible factors using Ri polynomials.
   - Finding K irreducible polynomials of a given order.
   - Checking if a polynomial is irreducible.

7. **Additional Functionality**:
   - Normalization of polynomials.
   - Fast exponentiation of polynomials.
   - Finding the inverse polynomial using the extended Euclidean algorithm.

## Collaboration and Project Guidelines

- This is a group project, and each subgroup is responsible for specific tasks.
- The project should be written in C++.
- Collaboration and cooperation among subgroups are encouraged since many tasks rely on each other.
- Each subgroup commits their work to the shared GitHub project.
- Unit tests must be implemented to read data (polynomials, long numbers) from files and provide user-friendly data input.
- Each participant works on two tasks from the project, one from theme 1 and another from theme 2 or 3. Each task can have a maximum of two contributors. If a subgroup has fewer members, they can skip some tasks highlighted in yellow.

## Literature and References

- "Handbook of Applied Cryptography" by Alfred J. Menezes, Paul C. van Oorschot, Scott A. Vanstone.
- [Carmichael Function](https://en.wikipedia.org/wiki/Carmichael_function)
- [Modular Exponentiation](https://en.wikipedia.org/wiki/Modular_exponentiation)
- "Elliptic Curves, Number Theory, and Cryptography" (Second Edition)
- [Montgomery Modular Multiplication](https://en.wikipedia.org/wiki/Montgomery_modular_multiplication)
- [Montgomery Reduction Algorithm](https://www.nayuki.io/page/montgomery-reduction-algorithm)
- [Order and Cofactor of the Base Point](https://crypto.stackexchange.com/questions/33028/order-and-cofactor-of-the-base-point)
- [Baby-Step Giant-Step](https://en.wikipedia.org/wiki/Counting_points_on_elliptic_curves#Baby-step_giant-step)
- "Finite Fields" by Lidl R., Niederreiter G.
- [Montgomery Multiplication](https://maths-people.anu.edu.au/~brent/pd/MASCOS02t4.pdf)
