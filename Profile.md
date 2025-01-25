<h1 align="center">Hi, I'm Uğur Arıkan</h1>

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
* rust ❤️🦀
* frequently c#, react and typescript 👍
* curiously and closely watching go, f#, zig and mojo 🤔

<h2 style="font-family: consolas;">🎯 𝙸'𝚖 𝚞𝚙 𝚝𝚘</h2>

Two mature goals (i) OR & rust, and (ii) concurrency; and exciting side quests.

<h3 style="font-family: consolas; color:tomato">OR & rust</h3>

Among the milestones, current focus with highest priority is developing a **mathematical modeling** crate:
* expressive, solver-agnostic, type-safe, macro-free and concise with no more lines than model-on-paper
* below is a demo in c# and <a target="_blank" href="https://orxfun.github.io/orx-mathprog-gallery/">here</a> is the documentation

<h3 style="font-family: consolas; color:tomato">concurrent programming and parallel processing</h3>

This is an exciting and ongoing journey that started with working on pinned vectors; i.e., vectors with pinned elements guarantees.

> *see [PinnedVec](https://crates.io/crates/orx-pinned-vec) for the trait definition, and [SplitVec](https://crates.io/crates/orx-split-vec) and [FixedVec](https://crates.io/crates/orx-fixed-vec) for two implementations*

When memory locations of elements do not implicitly change while the vector grows, providing memory safety in a concurrent program becomes much easier.

> [ConcurrentBag](https://crates.io/crates/orx-concurrent-bag) and [ConcurrentOrderedBag](https://crates.io/crates/orx-concurrent-ordered-bag) are developed as two efficient concurrent grow-only collections aiming high performance concurrent collections.

Adding concurrent element safety through [ConcurrentOption](https://crates.io/crates/orx-concurrent-option) in addition to pinned element guarantees allows for a concurrent vector with grow & read & update functionalities, namely [ConcurrentVec](https://crates.io/crates/orx-concurrent-vec). The api of the concurrent vector will continue to grow with the objective to get closer to the standard vector and be its **concurrent counterpart**.

In another workstream, [ConcurrentIter](https://crates.io/crates/orx-concurrent-iter) is defined. Considering concurrent iterator as a concurrent provider of inputs and concurrent bags as the collector of outputs, it has been straightforward to develop the **parallel processing** crate [orx-parallel](https://crates.io/crates/orx-parallel) which is very efficient and conveniently configurable.

<h3 style="font-family: consolas; color:tomato">miscellaneous side quests</h3>

Some of the crates resulting from interesting side topics are as follows:

* [orx-iterable](https://crates.io/crates/orx-iterable) ➛ Defines and implements Iterable, Collection and CollectionMut traits to represent types that can be iterated over multiple times.
* [orx-tree](https://crates.io/crates/orx-tree) ➛ A beautiful, convenient and efficient 🌳.
* [orx-linked-list](https://crates.io/crates/orx-linked-list) ➛ A linked list implementation with unique features and an extended list of constant time methods providing high performance traversals and mutations.
* [orx-v](https://crates.io/crates/orx-v) ➛ Traits to unify all vectors!
* [orx-imp-vec](https://crates.io/crates/orx-imp-vec) ➛ ImpVec stands for immutable push vector 👿, it is a data structure which allows appending elements with a shared reference.
* [orx-priority-queue](https://crates.io/crates/orx-priority-queue) ➛ Priority queue traits and high performance d-ary heap implementations.
* [orx-pseudo-default](https://crates.io/crates/orx-pseudo-default) ➛ PseudoDefault trait allows to create a cheap default instance of a type, which does not claim to be useful.

Also,
* [orxfun-notes](https://orxfun.github.io/orxfun-notes/) ➛ articles on my observations & experiences

<h2 style="font-family: consolas;">Mathematical Modeling Demo</h2>

![knapsack](https://orxfun.github.io/orx-mathprog-gallery/data/concise/knapsack.PNG)

[mathematical modeling in action 🔎](https://orxfun.github.io/orx-mathprog-gallery/img/orx_model_building_knapsack.gif)

![knapsack](https://orxfun.github.io/orx-mathprog-gallery/img/orx_model_building_knapsack-540w.gif)

