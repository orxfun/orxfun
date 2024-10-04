<h1 align="center">Hi, I'm Uğur Arıkan</h1>

<h2 style="font-family: consolas;">👋 𝙰𝚋𝚘𝚞𝚝 𝙼𝚎</h2>

Operations Research, optimization, algorithms, systems design. like programming languages. love rust.

* Middle East Technical University
* Singapore University of Technology and Design
* Now in Bonn, Germany
* | [github](https://github.com/orxfun) | [email](mailto:orx.ugur.arikan@gmail.com) | [linkedin](https://www.linkedin.com/in/uarikan/) | [cv](https://orxfun.github.io/cv/) | [crates](https://crates.io/users/orxfun) | [nuget](https://www.nuget.org/profiles/orx.ugur.arikan) |


<h2 style="font-family: consolas;">🤟 I like</h2>

All things OR, *optimization, networks, routing, algorithms, multi objective decision making*.

Programming, *algorithms, data structures, speed, efficiency and recently concurrency*.

And I like programming languages:

* rust ❤️ every day
* c#, react, typescript 👍 often
* go, f# 👌🏽 zig, nim 🤔 watching

<h2 style="font-family: consolas;">🎈 𝙸'𝚖 currently 𝚞𝚙 𝚝𝚘</h2>

<h3 style="font-family: consolas; color:tomato">mathematical programming / modeling</h3>

An expressive, efficient and productive mathematical programming / modeling crate for rust.
  * macro-free and concise api which does not require more lines than model-on-paper has
  * simple, solver agnostic, immutable, type safe
  * with a separation of model and data, and hence, enable abstraction over inputs
  * with reusable & composable model components
  * below is a demo of my attempt in C# and <a target="_blank" href="https://orxfun.github.io/orx-mathprog-gallery/">here</a> is the documentation

<h3 style="font-family: consolas; color:tomato">concurrent programming and parallel processing</h3>

Working more and more on concurrent programming and parallel processing in rust. One thing lead to another, and I got more and more interested:
* Started with defining the <a target="_blank" href="https://crates.io/crates/orx-pinned-vec">PinnedVec</a> trait and its implementations such as the <a target="_blank" href="https://crates.io/crates/orx-split-vec">SplitVec</a> and <a target="_blank" href="https://crates.io/crates/orx-fixed-vec">FixedVec</a>. A pinned vector is a vector which keeps its elements pinned in their memory locations.
* Turns out this feature is very useful in defining concurrent collections such as <a target="_blank" href="https://crates.io/crates/orx-concurrent-vec">ConcurrentVec</a>, <a target="_blank" href="https://crates.io/crates/orx-concurrent-bag">ConcurrentBag</a> or  <a target="_blank" href="https://crates.io/crates/orx-concurrent-ordered-bag">ConcurrentOrderedBag</a>.
* On the counterpart of the concurrent collections, <a target="_blank" href="https://crates.io/crates/orx-concurrent-iter">ConcurrentIter</a> allows concurrent iterations.
* Having concurrent readers and concurrent writers, we can have a simple and performant parallel iterator <a target="_blank" href="https://crates.io/crates/orx-parallel">Par</a>.

<h3 style="font-family: consolas; color:tomato">self referential collections</h3>

Working on convenient and efficient self referential collections.
* Such collections are often used as core data structures for algorithms.
* The goal is to define sort of a core construct which would make it convenient to build and generate variants. <a target="_blank" href="https://crates.io/crates/orx-selfref-col">SelfRefCol</a> aims to fulfil this goal defining the collection variants and handling most of the work in providing safe and efficient storage where elements are referencing other elements.
* As it is the most simplest of them, worked on the <a target="_blank" href="https://crates.io/crates/orx-linked-list">linked list</a> which turned out to be very efficient.
* Efficient & flexible trees 🌴 and graphs are the next steps.

<h3 style="font-family: consolas; color:tomato">also</h3>

* working on efficient data structures as I need in algorithms, such as <a target="_blank" href="https://crates.io/crates/orx-priority-queue">PriorityQueue</a> trait and efficient d-ary heap implementations.
* and whenever I have time, I am trying some experimental ideas such as <a target="_blank" href="https://crates.io/crates/orx-closure">Closure</a> and <a target="_blank" href="https://crates.io/crates/orx-funvec">FunVec</a>.

<h2 style="font-family: consolas;">Mathematical Modeling Demo</h2>

![knapsack](https://orxfun.github.io/orx-mathprog-gallery/data/concise/knapsack.PNG)

[mathematical modeling in action 🔎](https://orxfun.github.io/orx-mathprog-gallery/img/orx_model_building_knapsack.gif)

![knapsack](https://orxfun.github.io/orx-mathprog-gallery/img/orx_model_building_knapsack-540w.gif)
