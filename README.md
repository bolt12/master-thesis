# Selective Functors &amp; Probabilities

In functional programming, _selective applicative_ functors (SAF) are an abstraction between applicative functors and monads. 
This abstraction requires all effects to be statically declared, but provides a way to select which effects to execute dynamically. 
SAF have been shown to be a useful abstraction in several examples, including two industrial case studies. 
Selective functors have been used for their static analysis capabilities. 
The collection of information about all possible effects in a computation and the fact that they enable \emph{speculative} execution
make it possible to take advantage to describe probabilistic computations instead of using monads. 
In particular, selective functors appear to provide a way to obtain a more efficient implementation of probability distributions than monads.
    
This dissertation addresses a probabilistic interpretation for the _arrow_ and _selective_ abstractions in the light of the linear algebra of
programming discipline, as well as exploring ways of offering SAF capabilities to probabilistic programming, 
by exposing sampling as a concurrency problem. 
As a result, provides a Haskell type-safe matrix library capable of expressing probability distributions 
and probabilistic computations as typed matrices, and a probabilistic programming eDSL that explores various techniques in order to offer 
a novel, performant solution to probabilistic functional programming.
