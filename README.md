# The Lay of the Layers

Repository for the FPL'26 submission titled *"The Lay of the Layers: Enabling Heterogeneous 3D FPGA Architectures and Analyzing at Scale When They Win."*

## Repository Structure

- **`vtr-9-modified`** — submodule containing the modified VTR-9 code.
- **`static_vtr_binary`** — static build of the modified VTR-9 code.
- **`data/`** — per-architecture results and summary files (see below).

## Data Files

The `data/` folder contains the following:

- **`benchmark_characteristics.csv`** — statistics about each benchmark, both pre- and post-packing.
- **`successful_seeds_averaged.csv`** — average CPD and WL for each architecture on each benchmark, restricted to benchmarks that ran successfully.
- **`runtime.csv`** — runtime and memory usage for each architecture on each benchmark, reported per seed.
- **`post_packing_fanout_vectors.json`** — post-packing fanout for each benchmark.

## Note

The benchmarks' Verilog, BLIF, and netlist files will be released on Hugging Face upon acceptance. Combined, they total approximately 300 GB and therefore cannot be hosted on GitHub.
