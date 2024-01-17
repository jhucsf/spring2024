---
layout: mathjax
title: "Assignment 1: Big Integers"
---

Milestone 1: due *TBD*

Milestone 2: due *TBD*

Assignment type: **Pair**, you may work with one partner

# Overview

In this assignment, you will implement a `BigInt` C++ data type which
allows arbitrary-precision integer arithmetic.

## Milestones, grading criteria

Milestone 1 (15% of the assignment grade):

* Implementation of functions (15%)
  - constructors
  - destructor
  - `get_bit_vector()` member function
  - `git_bits(unsigned)` member function
  - `is_negative()` member function
  - `operator-()` (unary minus) member function
  - `to_hex()` member function

<div class='admonition danger'>
  <div class='title'>Important!</div>
  <div class='content' markdown='1'>
Milestone 1 is intended as a warm-up, since you might not have
written C++ code in a while. For that reason, it is a very
lightweight milestone. Milestone 2 will require significantly
more work.
  </div>
</div>

Milestone 2 (85% of the assignment grade):

* Implementation of functions (65%)
  - `is_bit_set(unsigned)` member function
  - `operator+(const BigInt &)`
  - `operator*(const BigInt &)`
  - `operator-(const BigInt &)` (two-operand subtraction)
  - `compare(const BigInt &)` member function
  - `operator<<(unsigned)` (left shift)
  - `operator/(const BigInt &)` (challenging!)
  - `to_dec()` member function (challenging!)
* Comprehensiveness and quality of your unit tests (10%)
* Design and coding style (10%)

<div class='admonition danger'>
  <div class='title'>Important!</div>
  <div class='content' markdown='1'>
Division (`operator/`) and conversion to base-10 (`to_dec()`) are challenging.
Each is worth at most 1% of the overall assignment grade. You should work
on them only after implementing and testing the other member functions.
  </div>
</div>

## Getting started

Yo.

# Machine integers, arbitrary-precision integers

Yo.
