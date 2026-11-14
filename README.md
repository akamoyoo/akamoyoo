# akamoyoo

PhD candidate at Penn State University.

I work on compilers, static analysis and reverse engineering, and on applications of LLMs and agents.
Most of what I build is systems code where performance and correctness both matter.

## Projects

- [**Taut**](https://github.com/akamoyoo/taut) — a systems language in which function signatures carry
  compiler-checked contracts for sizes, ownership and effects. Design stage.
- [**stillpath**](https://github.com/akamoyoo/stillpath) — a static checker for Rust hot paths: it checks
  that a function and everything it calls cannot allocate, panic or block, and reports a witness call
  chain and the assumptions behind each verdict. Research prototype, with an evaluation on six crates.
- [**paged-rolling-quantile**](https://github.com/akamoyoo/paged-rolling-quantile) — exact sliding-window
  quantiles in C++17, kept in sorted pages. Header-only, tested bit for bit against pandas, and measured
  against the simple baselines, including where they win.
- [**talo**](https://github.com/akamoyoo/talo) — Jupyter-style resident Python sessions for the terminal and
  for coding agents.

## Research interests

- LLM and agent applications
- Static analysis
- Compilers
- Reverse engineering

## Contact

xsdai@psu.edu
