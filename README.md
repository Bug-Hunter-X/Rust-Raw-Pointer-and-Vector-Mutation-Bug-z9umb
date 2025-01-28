# Rust Raw Pointer and Vector Mutation Bug

This repository demonstrates a common error in Rust when working with raw pointers and mutable vectors. Modifying a vector through a raw pointer, bypassing Rust's ownership system, leads to undefined behavior.  The example showcases this issue and provides a safe solution.

## Bug Description
The `bug.rs` file contains code that directly modifies a vector's element via a raw pointer. This violates Rust's memory safety rules and is unsafe.

## Solution
The `bugSolution.rs` file demonstrates how to safely modify vector elements using Rust's standard library functions and safe mechanisms.