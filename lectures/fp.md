Introduction to FP

1. FP Overview [2h+]
  * Evolution of imperative programming
  * Lisp interpreter
  * Turing machine, Backus speech
  * Haskell origins
  * Lambda calculus
  * Type theory
  * Category theory
  * Denotational semantics
  * Immutable data, Circle-Ellipse, mutable collections problem
  * Formal logic, Curry-Howard isomorphism
  * FP today: landscape, languages, Computer Science, communities, the Rift between scientific and commercial programming
  * Correctness proof and code verification

2. Lambda Calculus [1.5h]
  * Application, abstraction, terms
  * Reduction/conversion
  * SKI, iota
  * Church encoding: Boolean, Integer and related functions, Tuples
  * => Sum & Product types

Task: Church encoding exercises

3. Combinators-based DSLs  [1.5h]
  * Predicate logic: basic functions
  * Filtering with predicate combinators
 (*) Transforming predicate trees

3. Basic Data Structures [1.5h]
  * Immutability & persistence
  * List as a computation, recursive definition
  * List: Folding, mapping, etc.
  * ...

Task: List functions

4. Recursion [1.5h]
  * Recursion, Y combinator, memoization
  * Divide & Conquer algorithms
  * Basic recursion schemes
  * TCO, trampolining

Task: D&C problems: imperative vs. recursive

5. Lazy evaluation [1.5h]
  * Pros and cons of LE
  * LE & pure functions
  * Lazily-evaluated sequences (<= List)
  * LE for modularity: producer & consumer, tic-tac-toe pearl

6. Types I [2h]
  * ADTs, Sum & Product revision
  * Maybe 
  * Functor, variance, Bifunctor etc.
  * Lenses

7. Applicative validation [2h]
  * What's wrong with imperative exception handling
  * Applicative functors
  * Applicative validation with Either
  * Validation functors

8. Types II [1.5h]
  * Monad: definition, motivation
  * Do notation
  * Maybe/Either example
  
9. Types III [2h] 
  * IO monad
  * Continuation monad
  * State monad

10. Mogensen-Scott encoding [1.5h]
  * Scott encoding: Maybe, Either, enums, Bool, List, Binary Tree
  * matching function  
  * Mogensen extension
  
11. Typeclasses [2.5h]
  * Encoding typeclasses as function args/products
  * Show typeclass
  * Monoid typeclass
  * Functor, Applicative, Monad typeclasses
  * Writer monad
  * Foldable & Traversable
  * Deriving Functor and Applicative from Monad

12. Parsing I [2h]
  * Parser monad, combinators
  * Lazy JSON parser

13. Parsing II [2.5h]
  * Lazy JSON parser (continued)
  * Aeson
  * Parsing untyped lambda-calculus
  * Transforming ASTs
  * Code generation and optimization  

14. Correctness verification [4h]
  * Generative testing: QuickCheck, jsverify
  * Theorem proving, Liquid Haskell 
  * Dependent types
  * Prove correctness: example app

