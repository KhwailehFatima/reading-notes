# Reading

[Functional Programming Concepts](https://medium.com/the-renaissance-developer/concepts-of-functional-programming-in-javascript-6bc84220d2aa)
* What is functional programming?

Functional programming is a programming paradigm — a style of building the structure and elements of computer programs — that treats computation as the evaluation of mathematical functions and avoids changing-state and mutable data

* What is a pure function and how do we know if something is a pure function?

The first fundamental concept we learn when we want to understand functional programming 

It returns the same result if given the same arguments (it is also referred as deterministic)
It does not cause any observable side effects

* What are the benefits of a pure function?

The code’s definitely easier to test. We don’t need to mock anything. So we can unit test pure functions with different context

* What is immutability?
state cannot change after it’s created

* What is Referential transparency?

pure functions + immutable data = referential transparency


[Node JS Tutorial for Beginners #6 - Modules and require()](https://www.youtube.com/watch?v=xHLd36QoS4k)

* What is a module?

a file containing related code


* What does the word ‘require’ do?

to pass a global object with related path

* How do we bring another module into the file the we are working in?
module.export=counter;

* What do we have to do to make a module available?
to make it a reference to the desired function

