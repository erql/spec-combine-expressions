# Combination Expressions for Reactive Streams 🐇

Spec of expressions for reactive streams combination

## Status

This is a very alpha version of the ideas for combination expressions:

## Draft:

`ABC` -- will concat three streams

`[ABC]` -- will merge three streams

`A{1}` -- will take exactly 1 element from A stream, throw otherwise

`A{1}B{1}` -- will take exactly 1 element from A stream and then concat exactly 1 element from stream B, and then will complete. Throw otherwise

`A{1, 5}` -- will take from 1 to 5 elements from A stream

`A{5ms}` -- listen to A for 5ms

`[ABC]{5ms}` -- merge A B C and listen to merged stream for 5ms

TBC

(c) Kostia Palchyk