# Education
This repository will serve as an index of my Computer Science education. I decided to start keeping track of all the resources that I use to help document my growth as a Software Engineer, as well as to help serve as a Blueprint for others.

## Books

### General

1. The Art of Unix Programming - Great introduction to fundamentals of UNIX design, as well as UNIX's history. A bit dated in some areas, but some of the design philosophies are timeless.

2. The Cathedral and the Bazaar - Great introduction to the history of Linux and the open-source community in general.

3. Hackers and Painters - Great thoughts on software design, as well as an introduction to the value of Lisp as a programming language.

4. The Elements of Computing Systems - Computer Science 101, from NAND gates and DFF's all the way through assemblers, compilers, and operating systems. Comes with a great built-in project where you implement your own computer system, starting with NAND gates and eventually reaching an implementation of Tetris. [This](https://github.com/richardartoul/nand2tetris) repository represents my progress on that project so far.

### Languages

#### Clojure

1. [Brave Clojure](http://www.braveclojure.com/) - Best introductory text to Clojure that I could find. The author does an excellent job of explaining complex topics (like, what is a Lisp? What is a Macro? How do I think like a Lisp programmer?) in very simple and concrete terms.

## Articles

### Languages

#### JavaScript

1. [Combining Promises and Generators to Write Elegant Asynchronous Code in JavaScript](http://richardartoul.github.io/javascript/2015/07/16/promises-generators.html) - A blog post that I wrote.
2. [JavaScript Hidden Classes and Inline Caching in V8](http://richardartoul.github.io/jekyll/update/2015/04/26/hidden-classes.html) - A blog post I wrote that covers how the V8 engine optimizes your code under the hood.

### Computer Science

#### Concurrency, Parallelism, Threads, and Multithreading

1. [15 Minute Presentation](https://goo.gl/oi7osR) I created that summarizes my research on these concepts.
2. [Concurrency is Not Parallelism](https://www.youtube.com/watch?v=cN_DpYBzKso) - Fantastic 30 minute video that concretely explains what concurrency is, and how its different than parallelism.

#### Hashing and Load Balancing

1. [Consistent Hashing](http://www.tom-e-white.com/2007/11/consistent-hashing.html) - Explains how consistent hashing can be used to reduce the amount of re-hashing that needs to be done when a hash table is resized. Particularly useful for building a distributed hash table (across multiple servers) where you want to be able to add and remove new nodes without rehashing every item.

#### Regular Expressions

1. [Regular Expression Match Can Be Simple and Fast](https://swtch.com/~rsc/regexp/regexp1.html) - Great explanation of the main two algorithms for implementing regular expressions, as well as the tradeoffs between each of them.

[This](https://github.com/richardartoul/regex-engine) repository represents a simple regular expression engine I wrote in JavaScript to better understand the algorithms at work.

### Databases

#### PostGRES

1. What postGRES has over other open source SQL databases [Part 1](https://www.compose.io/articles/what-postgresql-has-over-other-open-source-sql-databases-part-ii/) [Part 2](https://www.compose.io/articles/what-postgresql-has-over-other-open-source-sql-databases-part-ii/)

### Scalability

1. [Introduction to Microservices](https://www.nginx.com/blog/introduction-to-microservices/) - Best introduction to microservices and how they can help you build scalable back-end services that I could find.

#### Authentication and Secuirty

1. [10 Things You Should Know About JSON Web Tokens and Cookies](https://auth0.com/blog/2014/01/27/ten-things-you-should-know-about-tokens-and-cookies/) - Good introduction to the difference between using JWT's vs. Cookies. This website in general has a lot of great resources on JWTs.
