# Do you believe in real numbers?
Slides and references for a talk given on 22/06/2021

## Abstract
As (applied) mathematicians, we often take real numbers for granted when working with them. Indeed, for many important theories and applications, real numbers somehow make things simpler than just using rational numbers. However, when one takes a closer look at how real numbers are defined, it turns out surprisingly that it is impossible to know anything about almost all of them!

In this talk, I will present a definition of real numbers, starting from the Peano axioms, and then show that the set of real numbers we can actually “know” is countable, for some reasonable definition of “knowing a number”. Along the way, I will introduce ideas from second order arithmetic, computation theory and algorithmic information theory (plus a pinch of Galois theory).

This talk is philosophical in spirit, and as such, aims to present interesting ideas without delving too deep into theory. No knowledge of the aforementioned topics is assumed.

## References and Further reading
* J. Stillwell, *Reverse Mathematics*, Princeton University Press, (2018).
* A. M. Turing, *On Computable numbers, with an application to the Entscheidungsproblem*, Proc. London Math. Soc. 40, pp. 230-265, (1936).
* Per Martin-Löf, *The Definition of Random Sequences*, Information and Control. 9 (6): 602–619, (1966).
* Ming Li, Paul M.B. Vitányi, *An Introduction to Kolmogorov Complexity and Its Applications*, Springer, (2008).

Stillwell's book is a delightful introduction to the logical foundations of analysis, and contains a detailed chapter on the arithmetisation of the real numbers. The papers by Turing and Martin-Löf can be easily found on the web, and are very much worth a read. Li and Vitányi's book is the standard reference on Kolmogorov complexity. The wikipedia pages on [Computable numbers](https://en.wikipedia.org/wiki/Computable_number), [Kolmogorov Complexity](https://en.wikipedia.org/wiki/Kolmogorov_complexity), and [Algorithmically Random Numbers](https://en.wikipedia.org/wiki/Algorithmically_random_sequence) are also worth checking out.

Finally, beyond computable numbers, [definable numbers](https://en.wikipedia.org/wiki/Definable_real_number) are numbers that can identified uniquely using a formula in a given formal language. Simpler languages such as first and second order arithmetic suffer the same problem as computable numbers, in that only countably many reals can be defined in them. However, there are models of ZFC (the base language for many fields, such as Measure Theory) where every real number is definable.