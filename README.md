# Homework 3

## Setup

Submit your own work for this assignment.
You can talk to other students about the problem, and you can share and exchange ideas (but not code).
If you talk to other students, include a comment in your files indicating who you worked with.

You can use any programming platform you like to write the code.
I recommend https://replit.com since it supports both Java and Clojure.

## Instructions

1. Write a recursive Java version of the Clojure `recursive-sum` function on page 53.
The method signature should be `public static int recursive_sum(List<Integer>)`, it should not have any mutable variables, and it should be defined in the class `Sum`.
You can include any test or demonstration methods that you want.
Submit your code in a file named `Sum.java`.

2. Rewrite the Clojure `recursive-sum` function on page 53, so that it uses Clojure's `loop` and `recur` special forms instead of explicit recursion.
You can include any test or demonstration functions that you want.
Submit your code in a file named `recursive-sum.clj`.
Here is a guide on how to use `loop` and `recur`: https://forum.freecodecamp.org/t/clojure-guide-how-to-use-loop-and-recur/18418

3. Write a `reverse-list` function in Clojure. This should take a list, and return a list with the same elements but in the opposite order.
You can include any test or demonstration functions that you want. 
You can use either explicit recursion, or the `loop` and `recur` forms.
Submit your code in a file named `reverse-list.clj`.
Here is a demonstration of some Clojure functions that you might find helpful:

```clojure
(println [
         (cons 5 [6 7])
         (first [5 6 7])
         (rest [5 6 7])
         (empty? [5 6 7])
         (empty? [])
         (empty? '())
         (concat [6 7] [9 8]) 
         (list 5)         
])
```
