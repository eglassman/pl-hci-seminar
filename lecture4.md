---
title: Notes for Lecture 4
layout: post
---

The goal of research in programming languages is to come up with
reusable insights and solutions. The problem is general and abstract.
A problem space instead of a problem. Defining a language to express
the problem, enable many different problems and many different
solutions to be explored.

As an example, consider this paper by Bastani, Zhang and Solar-Lezama
_Probabilistic Verification of Fairness Properties via Concentration_
(forthcoming at OOPSLA 2019). It defines a probabilistic solution to
the problem of deciding whether a black-box (such as a neural network)
is fair. What is fair? They don't solve the problem for a particular
definition of fair, but instead define a language for specifying
fairness properties.

What is a language? A language has syntax and semantics. Any powerful
general language has primitives, means of composition and means of
abstraction. The semantics give meaning to the syntax, ideally
denotationally -- by decomposing the meaning of a whole into the
meaning of parts.

What is programming? It's manipulating processes that blindly
manipulate symbols. A programming language can elevate the level of
discourse beyond the mere manipulation of symbols.

For HCI, we need to think of UIs beyond just interaction primitives
(such as clicks, gestures). How could they compose better? We can also
think of making the programming process less like the processes that
are programmed (blindly manipulating symbols!).
