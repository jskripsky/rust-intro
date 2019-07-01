# Rust Overview

## Features (10')
* ownership/borrow and lifetime tracking
* memory safe and type safe
* free of null, dangling pointers, "double free"
* free of data races
* no implicit boxing
* protocol enforcement using ownership

## History (10')
* started in 2006 as O'Caml variant
  * starting with top-down abstractions
* O'Caml-based compiler until 2011
* early iterations had GC, classes, typestate...

## Examples (30')
* lock/guard
* FIXME: more to come

## Compiler Components  (10')
* HIR, MIR, LLVM
* RLS

### Future
* [Miri](https://github.com/rust-lang/miri)
* [Chalk](https://github.com/rust-lang/chalk)

## Analogies (5')
* C++ vs. Rust =^= Subversion vs. git
  * new workflows become possible (fearless branch/fork and merge =^= fearless parallelization or refactoring)
* bottom-up abstractions vs. top-down abstractions
* real analysis vs. complex analysis

## OO or not? (10')

### Not OO
* no inheritance (composition instead)
* no exceptions ("Result" types instead)
* no (function) overloading

### OO
* encapsulation
* polymorphism

## Functional or not? (10')

### Not functional
* Turing-machine vs. lambda calculus
* zero-cost abstractions (incl. monomorphization of generic functions)
* embraces mutability
* "manual" memory management (i.e. no garbage collection)
* unsafe code possible
* simple FFI
* no monads

### Functional
* immutability by default
* (almost) everything is an expression (incl. "if ... else ...")
* (variable) type inference
* polymorphism through generics (type-checked)
* ADTs and pattern matching
* strong type system
* higher-order functions
* compiler "understands" flow of data (through code)
* formal definition of semantics (coming even for unsafe code!)
