<h1 align="center">Uğur Arıkan</h1>

I am an <span style="color:tomato">**operations research (OR)**</span> scientist, interested in optimization, algorithms and systems thinking & design; and a rust developer 🦀.

| [github](https://github.com/orxfun) | [email](mailto:orx.ugur.arikan@gmail.com) | [discord](https://discord.gg/Jr9XDVqDtV) | [linkedin](https://www.linkedin.com/in/uarikan/) | [cv](https://orxfun.github.io/cv/) | [crates](https://crates.io/users/orxfun) |



<h2 style="font-family: consolas;">❤️ I like</h2>

I am enthusiastic about all things <span style="color:tomato">**OR**</span>: decision science, mathematical optimization, algorithms, networks, routing, multiobjective decision making and decision making under uncertainty. I enjoy <span style="color:tomato">**computation**</span> a lot, working on efficient concurrent data structures and parallel computation. Least but not the least, I love <span style="color:tomato">**rust**</span> ❤️🦀.



<h2 style="font-family: consolas;">🎯 𝙸'𝚖 𝚞𝚙 𝚝𝚘</h2>

<h3 style="font-family: consolas; color:tomato">OR & rust</h3>

Two of the big challenges in applying OR in practice might be (i) to explain complex solutions to decision makers and (ii) to address uniqueness or custom requirements of each real life problem. I am not yet actively working on (i) but I find using LLMs for this purpose very promising and watching the advances closely.

For the latter, we are seeking flexible tools which allow for conveniently representing different sets of real life constraints. Although speed is an important feature in optimization tools, we even consider sacrificing performance to be able to deliver faster.

Imo, speed and type system of rust makes it the perfect language for rich and flexible optimization algorithms. It allows us to compose real life constraints as if we are working with a dynamic high level language, while our solutions are performant and memory efficient. For more details on this fitness, you may see the following [article](https://orxfun.github.io/orxfun-notes/#/zero-cost-composition-2025-10-15) and [talk](https://orxfun.github.io/talk-composing-zero-cost-abstractions-in-route-optimization/).

My work on OR & rust goal is currently split into two parallel streams:
* Composable, flexible and efficient <span style="color:tomato">**local search**</span> algorithms ([orx-local-search](https://github.com/orxfun/orx-local-search)). I will probably branch from this to focus specifically on <span style="color:tomato">**vehicle routing**</span> algorithms.
* An expressive, solver-agnostic, type-safe, macro-free and concise <span style="color:tomato">**mathematical modeling**</span> tool ([orx-math-model](https://github.com/orxfun/orx-math-model)). You may see a prototype in c# below ([zoom in 🔎](https://orxfun.github.io/orx-mathprog-gallery/img/orx_model_building_knapsack.gif)).

![knapsack](https://orxfun.github.io/orx-mathprog-gallery/img/orx_model_building_knapsack-540w.gif)






<h3 style="font-family: consolas; color:tomato">concurrency and parallel computing</h3>

I am working on a high performance, configurable and expressive parallel computation library in rust, [orx-parallel](https://crates.io/crates/orx-parallel). The crate is considerably mature, but also continuously improving with many new exciting challenges.

The journey to build a parallel computation crate involved developing pinned vectors ([PinnedVec](https://crates.io/crates/orx-pinned-vec), [SplitVec](https://crates.io/crates/orx-split-vec) and [FixedVec](https://crates.io/crates/orx-fixed-vec)) and various concurrent data structures such as [ConcurrentBag](https://crates.io/crates/orx-concurrent-bag), [ConcurrentOrderedBag](https://crates.io/crates/orx-concurrent-ordered-bag), [ConcurrentIter](https://crates.io/crates/orx-concurrent-iter), [ConcurrentRecursiveIter](https://crates.io/crates/orx-concurrent-recursive-iter). While improving the parallel computation library, these data structures continue to evolve.

On the other hand, [ConcurrentVec](https://crates.io/crates/orx-concurrent-vec) is developed without parallel computation in focus. It is designed to be the concurrent counterpart of the standard vec.




<h3 style="font-family: consolas; color:tomato">miscellaneous side quests</h3>

I also work on various side topics which are either relevant to efficient computation, or to improve ergonomics, or related to rust patterns. Some examples are:

* [orx-iterable](https://crates.io/crates/orx-iterable) ➛ Defines and implements Iterable, Collection and CollectionMut traits to represent types that can be iterated over multiple times.
* [orx-tree](https://crates.io/crates/orx-tree) ➛ A beautiful, convenient and efficient 🌳.
* [orx-v](https://crates.io/crates/orx-v) ➛ Traits to unify all vectors!
* [orx-priority-queue](https://crates.io/crates/orx-priority-queue) ➛ Priority queue traits and high performance d-ary heap implementations.
* [orx-meta](https://crates.io/crates/orx-meta) ➛ Meta structures such as statically typed queues of heterogeneous elements.

Finally, I write articles on this journey at [orxfun-notes](https://orxfun.github.io/orxfun-notes/).




<h2 style="font-family: consolas;">Connect</h2>

If you are interested in what I aim, feel free to [email](mailto:orx.ugur.arikan@gmail.com), open an issue or contribute to the repos on [github](https://github.com/orxfun), or share your ideas at [discord](https://discord.gg/Jr9XDVqDtV), or [sponsor](https://github.com/sponsors/orxfun).
