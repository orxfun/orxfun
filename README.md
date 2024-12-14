<h1 align="center">Hi, I'm Uğur Arıkan</h1>

<h2 style="font-family: consolas;">👋 whoami</h2>

I am an operations research (<span style="color:tomato">OR</span>) scientist, interested in optimization, algorithms and systems thinking & design.

```
me |> Middle East Technical University (Ankara)
   |> Singapore University of Technology and Design (Singapore)
   |> DHL Data & Analytics (Bonn)
```

| [github](https://github.com/orxfun) | [email](mailto:orx.ugur.arikan@gmail.com) | [linkedin](https://www.linkedin.com/in/uarikan/) | [cv](https://orxfun.github.io/cv/) | [crates](https://crates.io/users/orxfun) | [nuget](https://www.nuget.org/profiles/orx.ugur.arikan) |


<h2 style="font-family: consolas;">❤️ I like</h2>

I am very enthusiastic about all things <span style="color:tomato">OR</span>; my interests include mathematical programming, optimization algorithms, networks, routing, multiobjective decision making and decision making under uncertainty.

I also like programming languages.
* rust being my favorite ❤️🦀 after a nice transition, it is now an important part of my daily tasks. hoping and working for it to stay for a long time.
* also frequently use c#, react and typescript, which I find comfortable 👍
* and I am curiously and closely watching go, f#, zig and mojo 🤔

<h2 style="font-family: consolas;">🎯 𝙸'𝚖 𝚞𝚙 𝚝𝚘</h2>

Goals evolve and change shape. There are two mature goals: (i) OR & rust, and (ii) concurrency. However, exciting side quests appear on the way and join. Current workflows can be summarized as follows.

<h3 style="font-family: consolas; color:tomato">OR & rust</h3>

Two things I am most experienced in and enthusiastic about. After working on optimization algorithms on various languages, I am convinced that rust is the perfect match. Obviously, its speed and memory safety play an important role on this. However, a factor which is at least as important is its powerful type system that allows us to be very productive while developing efficient polymorphic algorithms.

The main goal is to contribute to OR ecosystem in rust. There are different milestones. Current focus with highest priority is developing a **mathematical modeling** crate.

<h4 style="font-family: consolas; color:orange">mathematical modeling</h4>

> [(*wikipedia*)](https://en.wikipedia.org/wiki/Mathematical_optimization) Mathematical optimization is the selection of a best element, with regard to some criteria, from some set of available alternatives.

Alternatively, it is a mathematical representation of a decision problem; which provides us with the optimal decision when solved. Mathematical modeling is the translation of the real-world problem into mathematics.

Mathematical modelers use an almost standard syntax while writing the problem on paper, which is concise, expressive, composable and reusable.

When the mathematical modeling tool do not have these properties, the entire modeling and optimization process becomes less productive, hard to maintain and error prone. This is the current situation in rust. Hence, the goal is to develop an expressive, efficient and productive mathematical modeling crate for rust with the following features:
  * macro-free and concise api which does not require more lines than model-on-paper has
  * simple, solver agnostic, immutable, type safe
  * with a separation of model and data, and hence, enable abstraction over inputs
  * with reusable & composable model components
  * below is a demo in c# and <a target="_blank" href="https://orxfun.github.io/orx-mathprog-gallery/">here</a> is the documentation

<h3 style="font-family: consolas; color:tomato">concurrent programming and parallel processing</h3>

This is an exciting and ongoing journey that started with working on pinned vectors; i.e., vectors with pinned elements guarantees.

> *see [PinnedVec](https://crates.io/crates/orx-pinned-vec) for the trait definition, and [SplitVec](https://crates.io/crates/orx-split-vec) and [FixedVec](https://crates.io/crates/orx-fixed-vec) for two implementations*

When memory locations of elements do not implicitly change while the vector grows, providing memory safety in a concurrent program becomes much easier.

> [ConcurrentBag](https://crates.io/crates/orx-concurrent-bag) and [ConcurrentOrderedBag](https://crates.io/crates/orx-concurrent-ordered-bag) are developed as two efficient concurrent grow-only collections aiming high performance concurrent collections.

Adding concurrent element safety through [ConcurrentOption](https://crates.io/crates/orx-concurrent-option) in addition to pinned element guarantees allows for a concurrent vector with grow & read & update functionalities, namely [ConcurrentVec](https://crates.io/crates/orx-concurrent-vec). The api of the concurrent vector will continue to grow with the objective to get closer to the standard vector and be its **concurrent counterpart**.

In another workstream, [ConcurrentIter](https://crates.io/crates/orx-concurrent-iter) is defined. Considering concurrent iterator as a concurrent provider of inputs and concurrent bags as the collector of outputs, it has been straightforward to develop the **parallel processing** crate [orx-parallel](https://crates.io/crates/orx-parallel) which is very efficient and conveniently configurable. But why do we need another crate while we have rayon:
* because they are different which is great, orx-parallel approaches with a different perspective.
* it is performant, simple and customizable per computation.
* it is possible to abstract parallel runner which will hopefully lead to interesting strategies and experiments (see the related [discussion](https://github.com/orxfun/orx-parallel/discussions/26)).

<h3 style="font-family: consolas; color:tomato">self referential collections</h3>

This is another interesting topic in the intersection of OR and rust.
* Self referential collections are often used as core data structures for algorithms.
* The goal is to define sort of a core construct which would make it convenient to build and generate variants. <a target="_blank" href="https://crates.io/crates/orx-selfref-col">SelfRefCol</a> aims to fulfil this goal defining the collection variants and handling most of the work in providing safe and efficient storage where elements are referencing other elements.
* Started working on the [LinkedList](https://crates.io/crates/orx-linked-list) which turned out to be very efficient with unique properties.
* Currently working on efficient & flexible trees 🌴
* Graphs are the next steps.

<h3 style="font-family: consolas; color:tomato">miscellaneous side quests</h3>

As mentioned, many interesting topics appear which either help to achieve the goals or improve the rust ecosystem, or both. Some of the crates resulting from these experiences are as follows:

* [orx-iterable](https://crates.io/crates/orx-iterable) ➛ Defines and implements Iterable, Collection and CollectionMut traits to represent types that can be iterated over multiple times.
* [orx-v](https://crates.io/crates/orx-v) ➛ Traits to unify all vectors!
* [orx-imp-vec](https://crates.io/crates/orx-imp-vec) ➛ ImpVec stands for immutable push vector 👿, it is a data structure which allows appending elements with a shared reference.
* [orx-priority-queue](https://crates.io/crates/orx-priority-queue) ➛ Priority queue traits and high performance d-ary heap implementations.
* [https://crates.io/crates/orx-pseudo-default](https://crates.io/crates/orx-pseudo-default) ➛ PseudoDefault trait allows to create a cheap default instance of a type, which does not claim to be useful.

*as you might guess, **orx** for all things OR.*

<h3 style="font-family: consolas; color:tomato">blog</h3>

Writing my observations, experiences and opinions related to the development towards the goals in [orxfun-notes](https://orxfun.github.io/orxfun-notes/). Also trying to submit the articles to [this week in rust](https://this-week-in-rust.org/) whenever it fits (*twir is awesome*).

<h2 style="font-family: consolas;">Mathematical Modeling Demo</h2>

![knapsack](https://orxfun.github.io/orx-mathprog-gallery/data/concise/knapsack.PNG)

[mathematical modeling in action 🔎](https://orxfun.github.io/orx-mathprog-gallery/img/orx_model_building_knapsack.gif)

![knapsack](https://orxfun.github.io/orx-mathprog-gallery/img/orx_model_building_knapsack-540w.gif)
