<h1 align="center">Hi, I'm Uğur Arıkan</h1>

<h2 style="font-family: consolas;">👋 𝙰𝚋𝚘𝚞𝚝 𝙼𝚎</h2>

* Operations Research (OR) Scientist / Practitioner ([wiki](https://en.wikipedia.org/wiki/Operations_research))
* Middle East Technical University & Singapore University of Technology and Design
* Located in Bonn Germany, working at DHL
* | [github](https://github.com/orxfun) | [email](mailto:orx.ugur.arikan@gmail.com) | [linkedin](https://www.linkedin.com/in/uarikan/) | [cv](https://orxfun.github.io/cv/) | [crates](https://crates.io/users/orxfun) | [nuget](https://www.nuget.org/profiles/orx.ugur.arikan) |


<h2 style="font-family: consolas;">🤟 I like</h2>

All things OR, *optimization, networks, routing, algorithms, multi objective decision making*.

Programming, *algorithms, data structures, speed, efficiency and recently concurrency*.

Also love programming languages:

* rust 🤟 every day, to stay for a long time
* c#, react, typescript 👍 quiet often
* go, f# 👌🏽 zig, nim 🤔 watching closely

<h2 style="font-family: consolas;">🎈 𝙸'𝚖 currently 𝚞𝚙 𝚝𝚘</h2>

<h3 style="font-family: consolas; color:tomato">mathematical programming / modeling</h3>

An expressive, efficient and productive mathematical programming / modeling crate for rust.
  * macro-free and concise api which does not require more lines than model-on-paper has
  * concise, simple, solver agnostic, immutable, type safe
  * with a separation of model and data, and hence, enable abstraction over inputs
  * with reusable & composable model components
  * below is a demo of my attempt in C# and <a target="_blank" href="https://orxfun.github.io/orx-mathprog-gallery/">here</a> is the documentation

<h3 style="font-family: consolas; color:tomato">concurrent programming and parallel processing</h3>

Working more and more on concurrent programming and parallel processing in rust. One thing lead to another, and I got more and more interested:
* First, worked on defining the <a target="_blank" href="https://crates.io/crates/orx-pinned-vec">PinnedVec</a> trait and its implementations such as the <a target="_blank" href="https://crates.io/crates/orx-split-vec">SplitVec</a> and <a target="_blank" href="https://crates.io/crates/orx-fixed-vec">FixedVec</a>. A pinned vector is nothing but a vector which keeps its elements pinned in their memory locations.
* Turns out this feature is very useful in defining concurrent collections such as <a target="_blank" href="https://crates.io/crates/orx-concurrent-bag">ConcurrentBag</a>, <a target="_blank" href="https://crates.io/crates/orx-concurrent-vec">ConcurrentVec</a> or  <a target="_blank" href="https://crates.io/crates/orx-concurrent-ordered-bag">ConcurrentOrderedBag</a>. This allows to write outputs of a computation concurrently.
* Then, the missing piece is to provide inputs concurrently with the convenience of an iterator. And hence, the <a target="_blank" href="https://crates.io/crates/orx-concurrent-iter">ConcurrentIter</a>.
* Having concurrent readers and concurrent writers, we can have a very simple yet very performant parallel iterator <a target="_blank" href="https://crates.io/crates/orx-parallel">PartIter</a>.

<h3 style="font-family: consolas; color:tomato">self referential collections</h3>

Working on convenient and efficient self referential collections.
* Such collections are common building blocks of data structures used in many algorithms, but they are tricky to build in rust, certainly trickier than garbage collected languages.
* The goal is to define how to create such collections safely and efficiently in rust.
* Again the PinnedVec serves as the starting point since we want our references to stay valid.
* Second goal is to define and provide core functionalities of such collections. <a target="_blank" href="https://crates.io/crates/orx-selfref-col">SelfRefCol</a> aims to serve as the core structure for self referential collection.
* As the first consumer, worked on building the famously tricky <a target="_blank" href="https://crates.io/crates/orx-linked-list">LinkedList</a> on top of SelfRefCol, which turned out to be very efficient.
* Efficient & flexible trees 🌴 and graphs are in progress. To continue with graphs.

<h3 style="font-family: consolas; color:tomato">also</h3>

* working on efficient data structures as I need in algorithms, such as <a target="_blank" href="https://crates.io/crates/orx-priority-queue">PriorityQueue</a> trait and efficient d-ary heap implementations.
* and whenever I have time, I am trying some experimental ideas such as <a target="_blank" href="https://crates.io/crates/orx-closure">Closure</a> and <a target="_blank" href="https://crates.io/crates/orx-funvec">FunVec</a>.

<h2 style="font-family: consolas;">Mathematical Modeling Demo</h2>

![knapsack](https://orxfun.github.io/orx-mathprog-gallery/data/concise/knapsack.PNG)

[mathematical modeling in action 🔎](https://orxfun.github.io/orx-mathprog-gallery/img/orx_model_building_knapsack.gif)

![knapsack](https://orxfun.github.io/orx-mathprog-gallery/img/orx_model_building_knapsack-540w.gif)
