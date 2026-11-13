+++
template = "index.html"
+++

## Research Themes

### Fallingwater: Compiling Python DSLs to Heterogeneous Architectures
Heterogeneous hardware has become increasingly prevalent, and having programming systems utilize 
different hardware types leads to generality, efficiency, portability, and agility. 
Therefore, this project proposes compilers from high-level Python
domain-specific languages and libraries, which are highly used, to target
multiple heterogeneous hardware architectures.  This effort is in collaboration with [Stanford University](https://ppl.stanford.edu/#projects) and falls under a larger question of how modernize compiler 
technology towards [Machine learning and Optimization-guided Compilers for
Heterogeneous Architctures
(MOCHA)](https://www.darpa.mil/research/programs/mocha-machine-learning).

### Programming Systems for Sparse Accelerators
Generations of hardware and software optimization and development has centered
around dense applications. However, a new class of sparse workloads (algorithms
that work directly on compressed sparse data) can be accelerated in
hardware, but it is unclear how to use and program these accelerators. 
This line of work lays the foundation for how to program hardware accelerators for sparse
computations from high-level sparse languages—or sparse domain-specific languages (DSLs). 
Detailed existing research and future (ongoing) work can be found at
[Programming Systems for Sparse
Accelerators](https://weiya711.github.io/assets/owhsu-thesis.pdf).  

### Multimodal Inference Serving
Coming soon!

### Architectural Abstractions for LLM Serving
Coming soon!

### Scheduling by Navigation
Scheduling languages such as Halide are pervasive in domain-specific optimizing compilers. Authoring *good* schedules, however, is difficult due to the complexity of modern workloads and the vastness of the scheduling space. In this [project](https://capra.cs.cornell.edu/latte26/paper/latte26-final6.pdf) we use [Honeybee](https://honeybee-lang.org/), an interactive program synthesis tool with strong guarantees on both the interaction and the resulting schedule, to explore methods that scaffold the schedule writing process.
