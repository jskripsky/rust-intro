# Rust Concepts

## Ownership (30')
* Ownership (T)
  * move semantics
* Borrowing (&T, &mut T)
* Lifetimes (&'static T)
  * Lifetime elision

## Basic Types (10')
* `String`, `&String` and `&str`
* `Vector<u8>` and `&[u8]`

## Structs (10')
* Structs
* Implementation
* `self`, `&self`

## Traits (30')
* Traits (ad hoc polymorphism, similar to Haskell type classes, incl. nomenclature from category theory)
* Trait objects
* Associated types

## Enums (15')
* Enums
  * `Option<&T>` instead of null
  * Pattern matching
  
## Crates and Cargo (30')
* Crates
* Modules
* Cargo

## Macros (30')
* why you want hygiene
* declarative macros
  * println!
* procedural macros
* #[derive]

## Automated Tests (15')
* unit tests
* doc tests
