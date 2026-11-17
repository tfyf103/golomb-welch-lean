# Golomb–Welch conjecture in Lean

This repository hosts reproducibility materials for the Lean 4 formalization of Theorem 1.1 of *The Golomb–Welch conjecture for arbitrary centre sets* by Bocong Chen, Jing Huang, and Gaojun Luo.

The theorem rules out tilings of the integer lattice by closed Lee balls for all dimensions \(n \ge 3\) and integer radii \(r \ge 2\), with arbitrary sets of centres. The entry point is `GolombWelch.main`, and the proof uses Lean 4.35.0.

## Reproduction

See [Releases](https://github.com/tfyf103/golomb-welch-lean/releases) for the versioned reproduction archive. The archive contains the proof sources, certificates, pinned dependencies, and reproduction instructions. The checksum for version `v1.0.0` is in [golomb-welch-lean-reproduction-v1.0.0.zip.sha256](golomb-welch-lean-reproduction-v1.0.0.zip.sha256).

## License

The original Lean formalization and reproduction scripts are available under the [MIT License](LICENSE). Bundled third-party dependencies retain their respective licenses.
