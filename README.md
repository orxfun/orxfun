<h1 align="center">Hi 👋, I'm Uğur Arıkan</h1>
<h3 align="center">Operations Research & Optimization & Rust</h3>


<h2 style="font-family: consolas;">📖 𝙰𝚋𝚘𝚞𝚝 𝙼𝚎</h2>

- Operations Research (OR) Scientist / Practitioner ([resume tl;dr](https://orxfun.github.io/cv/))
- 🎓 studied in the Middle East Technical University
- 🏫 then postdoc in Singapore University of Technology and Design
- 🌍 now located in Bonn, Germany, working at DHL
- 💬 reach me via [orx.ugur.arikan@gmail.com](mailto:orx.ugur.arikan@gmail.com) 〰️ [https://www.linkedin.com/in/uarikan/](https://www.linkedin.com/in/uarikan/)
- 💻 projects available here [https://github.com/orxfun](https://github.com/orxfun) mostly <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/rust/rust-plain.svg" alt="rust" width="15" height="15"/> but also some <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/csharp/csharp-original.svg" alt="csharp" width="15" height="15"/>


<h2 style="font-family: consolas;">🤟 I like</h2>

- all things OR
- optimization algorithms & data structures
- rust 🦀 to stay for long
- functional programming
- speed & efficiency


<h2 style="font-family: consolas;">🎈 𝙸'𝚖 currently 𝚞𝚙 𝚝𝚘</h2>

- an expressive, efficient and productive **mathematical programming** crate. why?
  * I appreciate how early [good_lp](https://crates.io/crates/good_lp) allowed us to build mathematical models in rust. however, I find the taken approach imperative, verbose and error-prone.
  * I am working on a macro-free and concise api which does not require more lines than the model on the paper has.
  * you may see a C# demo below, and find details and design choices of the underlying library **<a target="_blank" href="https://orxfun.github.io/orx-mathprog-gallery/" style="color:tomato;">here</a>**:
    * concise │ simple │ reusable │ immutable │ model & data separation │ abstraction over inputs │ generic over solvers
  * with rust, I am targeting these design choices; however,
    * development is different: challenging, educative and elegant,
    * init-commit in progress.

- rust crates which aim to make **self referential collections** convenient & efficient while safe. so far,
  - I needed to build <a target="_blank" href="https://crates.io/crates/orx-pinned-vec">orx-pinned-vec</a> & <a target="_blank" href="https://crates.io/crates/orx-fixed-vec">orx-fixed-vec</a> & <a target="_blank" href="https://crates.io/crates/orx-split-vec">orx-split-vec</a> & <a target="_blank" href="https://crates.io/crates/orx-imp-vec">orx-imp-vec</a>
  - to be able to build <a target="_blank" href="https://crates.io/crates/orx-linked-list">orx-linked-list</a> with this alternative thin-reference approach.
  - an efficient & flexible **tree** and **graph** are in progress 🚧

- efficient data structures that I need in algorithms, such as <a target="_blank" href="https://crates.io/crates/orx-priority-queue">orx-priority-queue</a>

- and some experimental functional ideas such as <a target="_blank" href="https://crates.io/crates/orx-closure">orx-closure</a> and <a target="_blank" href="https://crates.io/crates/orx-funvec">orx-funvec</a>

![knapsack](https://orxfun.github.io/orx-mathprog-gallery/data/concise/knapsack.PNG)

![Orx.MathProg](img/builder-pattern.gif)
