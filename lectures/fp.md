I. FP elements

  1. Death to JS OOP

    1.1 this -> arg
      * implicit argument
      * auto-binding
      * only needed for prototype resolution
      * fuck methods
      * type constructors and operations
      
    1.2 rethinking polymorphism 
      * inheritance/overriding sucks (multilayer, scattered abstraction)
        Circle-Ellipse problem
      * mixin chaos
      * generalize type/structure creation -> explicit & declarative 
      * classic Form example: (fuck redundant types)
          Form class -> Form type (instance -> structure, methods -> functions)          
      * interfaces -> duck typing vs OOP & as a general modern practice
        row polymorphism (?)
      * functions as the most polymorphic entity (vs. type "aliasing" in OOP, naming vs type expressiveness)
     !* SOLID bull$h1t
        SOLID as an after-constraint, OOP is too arbitrary, no way to enforce
        S in FP 
        O (see above)
        L in FP (subtyping, covariance & contravariance)
        I solved with ADTs                         <-- yo, types
        D no D.Inj. & functions as implementations <-- yo, types
          hole-in-the-middle example

  2. Better functions

    2.1 Common functions and FP patterns
      * lambda calc. combinators (I, K) and so on
      * lodash / FP: negate example and why,  _.partial, _.flow
      * _.rearg and wrapper function
      * control flow using functions (hash map example)
      * memoization (cssqd example)

    2.2 Curried functions
      * lambda calculus
      * easy partial application
      * lodash _.curry[Right] and lodash FP
        examples

    2.3 Pure functions
      * Criteria and why they matter: predictability (tests) & debugging focus + tabular optimization (V8?)
        Parallel/Concurrent programming
      * Referential transparency example
                        
    2.3 Higher-order functions
      * HOFs and where to find them in JS (array method args, Promises)
      * HOFs vs. closures (example)
      * wrapping functions & _.wrap (example)
      * forcing types using HOFs: Maybe example

    2.4 recursion and CPS
      * recursion as a specific case of HOF
      * recursive flow control
      * CPS 
      * tail recursion
     !* TCO [in ES] and trampolining
  
    2.5 Point-free notation
      * Lambda calculus form
      * composition; tacit programming
      * composition of functions of variable arity -> finding the nature of a computation
      * reusing/abusing existing functions: example: constant using _.identity
      * expressive DSLs using point-free combinators (parsing/compiling example)
      * no(/generated) tests

  3. Lazy vs. Strict evaluation
    3.1 Lazy evaluation: good & evil (implicit state, memory management, generalization)
    3.2 Lazy JS with generators and really lazy async/await (and why it only makes sense with pure funcs)      
   !3.3 Modularity leveraging lazy evaluation https://hackhands.com/modular-code-lazy-evaluation-haskell/
    
  4. Side-effects and mutable state
    4.1 Why state is so bad: from DOM to microservices to Serverless
      => anything shared is not safe (source of change? order of change?)
    4.2 _F_SM vs objects (order and concurrency)
    4.2 What is inevitably stateful: IO, persistence, DOM(=> React, game World concept)
    4.3 Side effects and _simple_ ways of dealing with them: state-passing style, Redux
      * Immutable data structures: cons, Okasaki stuff, Immutable.js
     !* Pure components in React
    4.4 Beware of closures
      
  5. FRP
    5.1 events & pub/sub suck
    5.2 streams, signals, cells and operations 
    5.3 data flow UI application (data stream transformation example)
    5.4 RxJS/Bacon/...

  6. Beyond JS

    6.1 ClojureScript
      * Lisp motivation (forms, macros)
      * Data structures as functions
      * Side-effects in CL/JS (atoms)
      * Transducers & in JS
     ?* Dynamic typing
      
    6.2 PureScript/Haskell
      * Function syntax
      * Purity & side-effect tracking (example http://hal2016.haskell.org/program.html#russo)
      * Type checking & type inference
      * Advanced Type system: typeclasses, category-theory based types, ADTs
      * Language features: 
        curried pure functions
        pattern matching (Maybe/Either, aliases and _function_ examples)
        ! functors (arrays, binary trees, Maybe), applicatives and monads
        ! monadic I/O
     !* Liquid Haskell, logic programming & QuickCheck

    6.3 Elm
      * built-into features: data flow, messages, state management
     <* DOM DSL
      * time-traveling debugging


http://stevelosh.com/blog/2013/03/list-out-of-lambda
Light Table & Clojure demo
...

