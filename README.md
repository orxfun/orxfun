<h1 align="center">Hi, I'm Uğur Arıkan</h1>
<h3 align="center">Operations Research & Optimization & Rust</h3>


<h2 style="font-family: consolas;">👋 𝙰𝚋𝚘𝚞𝚝 𝙼𝚎</h2>

- Operations Research (OR) Scientist / Practitioner ([resume tl;dr](https://orxfun.github.io/cv/))
- 🎓 Studied in the Middle East Technical University
- 🏫 Postdoc in Singapore University of Technology and Design
- 🌍 Currently located in Bonn, Germany, working at DHL
- 💬 Reach me [orx.ugur.arikan@gmail.com](mailto:orx.ugur.arikan@gmail.com) 〰️ [https://www.linkedin.com/in/uarikan/](https://www.linkedin.com/in/uarikan/)
- 💻 Projects available at [https://github.com/orxfun](https://github.com/orxfun) currently mostly in <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/rust/rust-plain.svg" alt="rust" title="rust" width="20" height="20"/> & <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/csharp/csharp-original.svg" alt="csharp" title="C#" width="18" height="18"/> published in <a href="https://crates.io/users/orxfun"><img src="https://crates.io/assets/cargo.png" width="20"/></a> and <a href="https://www.nuget.org/profiles/orx.ugur.arikan"><img src="https://www.nuget.org/Content/gallery/img/default-package-icon.svg" width="20"/></a>


<h2 style="font-family: consolas;">🤟 I like</h2>

| all things OR                  | programming languages |
|--------------------------------|-----------------------|
| optimization                   | ⭐ rust, c#           |
| algorithms & data structures   | 👍 react, ts, c++     |
| multiobjective decision making | 👌🏽 f#, ocaml, go      |
| speed & efficiency             | 🤔 zig, nim          |

<h2 style="font-family: consolas;">🎈 𝙸'𝚖 currently 𝚞𝚙 𝚝𝚘</h2>

- An expressive, efficient and productive **mathematical programming / modeling** crate for rust. why?
  * I appreciate how early [good_lp](https://crates.io/crates/good_lp) allowed us to build mathematical models in rust. However, I find the taken common approach imperative, verbose and error-prone.
  * Working on a macro-free and concise api which does not require more lines than the model on the paper has.
    * macros are super-powerful but doesn't have the exact same feeling of the regular type system.
  * You may see a demo in C# below, and find design choices of the underlying library **<a target="_blank" href="https://orxfun.github.io/orx-mathprog-gallery/" style="color:tomato;">here</a>**.
  * With rust 🦀 I am targeting these design choices summarized in the table below; however, development is different: challenging, educative and elegant.

|||||
|---|---|---|---|
| concise | simple | solver agnostic | reusable & composable model components |
| immutable | type safe | separation of model from data | abstraction over inputs |

- Working to make **self referential collections** convenient & efficient while staying safe. why?
  - Such collections are common building blocks of data structures used in many algorithms.
    * They can be rapidly be implemented unsafely, in another language like c++ or unsafe rust.
    * They can be rapidly be implemented safely in garbage collected languages but with lots of indirection.
  - Can we get best of both, can we implement in rust safely but without additional indirection and withtout wide pointers?
    * So far, I needed to build <a target="_blank" href="https://crates.io/crates/orx-pinned-vec">orx-pinned-vec</a> & <a target="_blank" href="https://crates.io/crates/orx-fixed-vec">orx-fixed-vec</a> & <a target="_blank" href="https://crates.io/crates/orx-split-vec">orx-split-vec</a> & <a target="_blank" href="https://crates.io/crates/orx-imp-vec">orx-imp-vec</a>,
    * in order to be able to build <a target="_blank" href="https://crates.io/crates/orx-linked-list">orx-linked-list</a> with this alternative thin-reference approach.
  - Efficient & flexible trees 🌴 and graphs are in progress 🚧

- Also working on efficient data structures that I need in algorithms, such as <a target="_blank" href="https://crates.io/crates/orx-priority-queue">orx-priority-queue</a>.

- And trying some experimental functional ideas such as <a target="_blank" href="https://crates.io/crates/orx-closure">orx-closure</a> and <a target="_blank" href="https://crates.io/crates/orx-funvec">orx-funvec</a>.

![knapsack](https://orxfun.github.io/orx-mathprog-gallery/data/concise/knapsack.PNG)

[mathematical modeling in action 🔎](https://orxfun.github.io/orx-mathprog-gallery/img/orx_model_building_knapsack.gif)

![knapsack](https://orxfun.github.io/orx-mathprog-gallery/img/orx_model_building_knapsack-540w.gif)
