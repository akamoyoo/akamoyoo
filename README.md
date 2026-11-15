# akamoyoo

PhD candidate at Penn State University.

I work on compilers, static analysis and reverse engineering, and on applications of LLMs and agents.
Most of what I build is systems code where performance and correctness both matter.

## Projects

- [**llvm-fn-effects**](https://github.com/akamoyoo/llvm-fn-effects) — a static analyser on LLVM that
  infers, for every function of a C++ program and without annotations, whether it can allocate, lock,
  enter the kernel, throw or abort through everything it calls, and states what each answer rests on.
  First release, with three reproducible cases on open-source low-latency projects.
- [**stillpath**](https://github.com/akamoyoo/stillpath) — a static checker for Rust hot paths: it checks
  that a function and everything it calls cannot allocate, panic or block, and reports a witness call
  chain and the assumptions behind each verdict. Research prototype, with an evaluation on six crates.
- [**paged-rolling-quantile**](https://github.com/akamoyoo/paged-rolling-quantile) — exact sliding-window
  quantiles in C++17, kept in sorted pages. Header-only, tested bit for bit against pandas, and measured
  against the simple baselines, including where they win.
- [**fastcoint**](https://github.com/akamoyoo/fastcoint) — Engle-Granger cointegration tests for all pairs
  of N series, and batched ADF tests, from a few N x N matrix products. Reproduces statsmodels to rounding,
  thousands of times faster on one core.
- [**fastnearcorr**](https://github.com/akamoyoo/fastnearcorr) — nearest correlation matrix by the
  semismooth Newton method, NumPy only, with a duality-gap certificate for every result.
- [**fpsplit**](https://github.com/akamoyoo/fpsplit) — lossless compression for columns of computed
  doubles. Header-only C++20 with a byte-level format specification and an independent reference decoder;
  smaller than pco on the measured factor columns and three times faster to compress, half as fast to read.
- [**talo**](https://github.com/akamoyoo/talo) — Jupyter-style resident Python sessions for the terminal and
  for coding agents.

## Research interests

- LLM and agent applications
- Static analysis
- Compilers
- Reverse engineering

## Contact

xsdai@psu.edu
