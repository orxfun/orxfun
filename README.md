<style>
    .header {
        font-family: consolas;
    }
    .two-columns {
        display: grid;
        grid-template-columns: auto auto;
        gap: 2rem;
    }
    .four-crates {
        display: flex;
        gap: 2rem;
    }
    .crate {
        color: black;
        border-top: 1px solid rgb(240,240,240);
        border-left: 1px solid rgb(240,240,240);
        border-right: 2px solid lightgray;
        border-bottom: 2px solid lightgray;
        border-radius: 5px;
        padding: 2px 10px;
        font-family: consolas;
    }
    .crate:hover {
        color: black;
        background-color: rgb(255,255,240);
    }
    .crate:active {
        background-color: rgb(255,255,220);
        border-top: 1px solid lightgray;
        border-left: 1px solid lightgray;
         border-right: 2px solid rgb(240,240,240);
        border-bottom: 2px solid rgb(240,240,240);
        color: black;
    }
    * {
        line-height: 1.75rem;
    }
</style>

<h1 align="center">Hi 👋, I'm Uğur Arikan</h1>
<h3 align="center">Operations Research & Optimization & Rust</h3>


## :book: 𝙰𝚋𝚘𝚞𝚝 𝙼𝚎{#identifier .header}

Operations Research (OR) Scientist, some prefer Decision Scientist
🎓 studied in the Middle East Technical University
🏫 then postdoc in Singapore University of Technology and Design
🌍 now I'm located in Bonn, Germany, working at DHL
💬 reach me via orx.ugur.arikan@gmail.com || [https://www.linkedin.com/in/uarikan/](https://www.linkedin.com/in/uarikan/)
💻 projects available here [https://github.com/orxfun](https://github.com/orxfun) mostly <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/rust/rust-plain.svg" alt="rust" width="15" height="15"/> but also some <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/csharp/csharp-original.svg" alt="csharp" width="15" height="15"/>

<div class="two-columns">

<div>

## 🤟 I like{#identifier .header}
- all things OR
- optimization algorithms
- data structures
- Rust <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/rust/rust-plain.svg" alt="rust" width="15" height="15"/>
- functional programming
- speed & efficiency
</div>


<div>

## 🎈 𝙸'𝚖 currently 𝚞𝚙 𝚝𝚘{#identifier .header}

- an expressive **mathematical programming** crate. why? I am not a fan of the [good_lp](https://crates.io/crates/good_lp) approach. Further, I find it error-prone. I'd love a concise and macro-free api which does not require more lines than the model on the paper has.

- crates which make **self referential collections** in Rust convenient & efficient while safe, the challenge is fun. so far,
  - I needed to build <a class="crate" href="https://crates.io/crates/orx-pinned-vec"><img src="https://crates.io/assets/cargo.png" alt="" width="15" height="15"/> orx-pinned-vec</a> <a class="crate" href="https://crates.io/crates/orx-fixed-vec"><img src="https://crates.io/assets/cargo.png" alt="" width="15" height="15"/> orx-fixed-vec</a> <a class="crate" href="https://crates.io/crates/orx-split-vec"><img src="https://crates.io/assets/cargo.png" alt="" width="15" height="15"/> orx-split-vec</a> <a class="crate" href="https://crates.io/crates/orx-imp-vec"><img src="https://crates.io/assets/cargo.png" alt="" width="15" height="15"/> orx-imp-vec</a>
  - to be able to build <a class="crate" href="https://crates.io/crates/orx-linked-list"><img src="https://crates.io/assets/cargo.png" alt="" width="15" height="15"/> orx-linked-list</a> or a **tree** (wip) or a **graph** 🎯

- efficient data structures that I require in certain algorithms, such as <a class="crate" href="https://crates.io/crates/orx-priority-queue"><img src="https://crates.io/assets/cargo.png" alt="" width="15" height="15"/>orx-priority-queue</a>

- and some experimental functional ideas such as <a class="crate" href="https://crates.io/crates/orx-closure"><img src="https://crates.io/assets/cargo.png" alt="" width="15" height="15"/>orx-closure</a> and <a class="crate" href="https://crates.io/crates/orx-funvec"><img src="https://crates.io/assets/cargo.png" alt="" width="15" height="15"/>orx-funvec</a>

</div>

</div>
