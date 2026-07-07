# The Lay of the Layers

Repository for the FPL'26 submission titled *"The Lay of the Layers: Enabling Heterogeneous 3D FPGA Architectures and Analyzing at Scale When They Win."*

## Repository Structure

- **`vtr-9-modified`** — submodule containing the modified VTR-9 code.
- **`static_vtr_binary`** — static build of the modified VTR-9 code.
- **`data/`** — per-architecture results and summary files (see below).
- **`architectures/`** — architecture XML files for the 3D FPGA architectures evaluated in the paper.

## Data Files

The `data/` folder contains the following:

- **`benchmark_characteristics.csv`** — statistics about each benchmark, both pre- and post-packing.
- **`successful_seeds_averaged.csv`** — average CPD and WL for each architecture on each benchmark, restricted to benchmarks that ran successfully.
- **`runtime.csv`** — runtime and memory usage for each architecture on each benchmark, reported per seed.
- **`post_packing_fanout_vectors.json`** — post-packing fanout for each benchmark.

## Note

The benchmarks' BLIF, and netlist files are released on Hugging Face. Combined, they total approximately 230 GB. They can be found here: [https://huggingface.co/datasets/IY2002/The-Lay-of-the-Layers](https://huggingface.co/datasets/IY2002/The-Lay-of-the-Layers)

[![DOI](https://zenodo.org/badge/1200976505.svg)](https://doi.org/10.5281/zenodo.20335974)
