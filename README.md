<h1 align="center">Hi, I'm Uğur Arıkan</h1>

<h2 style="font-family: consolas;">👋 𝙰𝚋𝚘𝚞𝚝 𝙼𝚎</h2>

- Operations Research (OR) Scientist / Practitioner ([resume tl;dr](https://orxfun.github.io/cv/)), studied in the Middle East Technical University, postdoc in Singapore University of Technology and Design
- Currently located in Bonn, Germany, working at DHL
- 💬 Reach me [orx.ugur.arikan@gmail.com](mailto:orx.ugur.arikan@gmail.com) 〰️ [https://www.linkedin.com/in/uarikan/](https://www.linkedin.com/in/uarikan/)
- Projects available at [https://github.com/orxfun](https://github.com/orxfun) mostly in [rust](https://crates.io/users/orxfun) & [C#](https://www.nuget.org/profiles/orx.ugur.arikan).


<h2 style="font-family: consolas;">🤟 I like</h2>

| all things OR                  | programming languages |
|--------------------------------|-----------------------|
| optimization                   | ⭐ rust, c#           |
| algorithms & data structures   | 👍 react, ts, c++     |
| multiobjective decision making | 👌🏽 go, f#  |
| speed & efficiency             | 🤔 zig    |

<h2 style="font-family: consolas;">🎈 𝙸'𝚖 currently 𝚞𝚙 𝚝𝚘</h2>

- An expressive, efficient and productive **mathematical programming / modeling** crate for rust. why?
  * I appreciate how early [good_lp](https://crates.io/crates/good_lp) allowed us to build mathematical models in rust. However, I find the taken common approach imperative, verbose and error-prone.
  * Working on a macro-free and concise api which does not require more lines than the model on the paper has.
  * You may see a demo in C# below, and find design choices of the underlying library **<a target="_blank" href="https://orxfun.github.io/orx-mathprog-gallery/" style="color:tomato;">here</a>**.
  * Targeting similar design choices with rust as summarized below:

|||||
|---|---|---|---|
| concise | simple | solver agnostic | reusable & composable model components |
| immutable | type safe | separation of model from data | abstraction over inputs |

- Working to make **self referential collections** convenient & efficient while staying safe. why?
  - Such collections are common building blocks of data structures used in many algorithms.
  - They can be be implemented unsafely, in unsafe rust or c++. They can also be implemented safely in garbage collected languages. Can we get the best of both, i.e., safe and efficient rust implementation.
  - Towards this target, I worked on <a target="_blank" href="https://crates.io/crates/orx-pinned-vec">orx-pinned-vec</a> & <a target="_blank" href="https://crates.io/crates/orx-fixed-vec">orx-fixed-vec</a> & <a target="_blank" href="https://crates.io/crates/orx-split-vec">orx-split-vec</a> & <a target="_blank" href="https://crates.io/crates/orx-imp-vec">orx-imp-vec</a> & <a target="_blank" href="https://crates.io/crates/orx-selfref-col">orx-selfref-col</a>.
  - This allowed me to build <a target="_blank" href="https://crates.io/crates/orx-linked-list">orx-linked-list</a> with regular `&` references and without any unsafe pointer access, unlike the std implementation.
  - Efficient & flexible trees 🌴 and graphs are in progress.
  - As a by-product, vectors with pinned elements led to convenient <a target="_blank" href="https://crates.io/crates/orx-concurrent-bag">orx-concurrent-bag</a>.

- Also working on efficient data structures that I need in algorithms, such as <a target="_blank" href="https://crates.io/crates/orx-priority-queue">orx-priority-queue</a>.

- And trying some experimental functional ideas such as <a target="_blank" href="https://crates.io/crates/orx-closure">orx-closure</a> and <a target="_blank" href="https://crates.io/crates/orx-funvec">orx-funvec</a>.

![knapsack](https://orxfun.github.io/orx-mathprog-gallery/data/concise/knapsack.PNG)

[mathematical modeling in action 🔎](https://orxfun.github.io/orx-mathprog-gallery/img/orx_model_building_knapsack.gif)

![knapsack](https://orxfun.github.io/orx-mathprog-gallery/img/orx_model_building_knapsack-540w.gif)
