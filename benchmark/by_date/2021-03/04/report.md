# Benchmark Report

## Job Properties

*Commit:* [vtjnash/julia@49387b2bc67f90650e5c2a982d8fb31e7e6d90b7](https://github.com/vtjnash/julia/commit/49387b2bc67f90650e5c2a982d8fb31e7e6d90b7)

*Comparison Diff:* [link](https://github.com/vtjnash/julia/compare/d753a0b6a78d94d08c17b2c227916700e3359e4a..49387b2bc67f90650e5c2a982d8fb31e7e6d90b7)

*Triggered By:* [link](https://github.com/vtjnash/julia/commit/49387b2bc67f90650e5c2a982d8fb31e7e6d90b7#commitcomment-47869137)

*Tag Predicate:* `"io"`

*Daily Job:* 2021-03-04 vs [2021-02-23](../../2021-02/23)/report.md

## Results

*Note: If Chrome is your browser, I strongly recommend installing the [Wide GitHub](https://chrome.google.com/webstore/detail/wide-github/kaalofacklcidaampbokdplbklpeldpj?hl=en)
extension, which makes the result table easier to read.*

Below is a table of this job's results, obtained by running the benchmarks found in
[JuliaCI/BaseBenchmarks.jl](https://github.com/JuliaCI/BaseBenchmarks.jl). The values
listed in the `ID` column have the structure `[parent_group, child_group, ..., key]`,
and can be used to index into the BaseBenchmarks suite to retrieve the corresponding
benchmarks.

The percentages accompanying time and memory values in the below table are noise tolerances. The "true"
time/memory value for a given benchmark is expected to fall within this percentage of the reported value.

A ratio greater than `1.0` denotes a possible regression (marked with :x:), while a ratio less
than `1.0` denotes a possible improvement (marked with :white_check_mark:). Only significant results - results
that indicate possible regressions or improvements - are shown below (thus, an empty table means that all
benchmark results remained invariant between builds).

| ID | time ratio | memory ratio |
|----|------------|--------------|
| `["io", "array_limit", "(\"display\", \"Matrix{Float64}(10000, 10000)\")"]` | 1.05 (5%) :x: | 0.91 (1%) :white_check_mark: |
| `["io", "array_limit", "(\"display\", \"Matrix{Float64}(100000000, 1)\")"]` | 1.11 (5%) :x: | 1.00 (1%)  |
| `["io", "array_limit", "(\"display\", \"Vector{Float64}(100000000,)\")"]` | 1.11 (5%) :x: | 1.00 (1%)  |
| `["io", "read", "read"]` | 0.85 (5%) :white_check_mark: | 1.00 (1%)  |
| `["io", "read", "readstring"]` | 1.37 (5%) :x: | 1.00 (1%)  |
| `["io", "serialization", "(\"deserialize\", \"Matrix{Float64}\")"]` | 1.14 (5%) :x: | 1.00 (1%)  |
| `["io", "serialization", "(\"deserialize\", \"Vector{String}\")"]` | 1.11 (5%) :x: | 1.00 (1%)  |
| `["io", "serialization", "(\"serialize\", \"Matrix{Float64}\")"]` | 1.12 (5%) :x: | 1.00 (1%)  |
| `["io", "serialization", "(\"serialize\", \"Vector{String}\")"]` | 1.16 (5%) :x: | 1.00 (1%)  |
| `["io", "skipchars"]` | 1.14 (5%) :x: | 1.00 (1%)  |
| `["parallel", "remotecall", "(\"identity\", 1024)"]` | 1.16 (5%) :x: | 1.01 (1%)  |
| `["parallel", "remotecall", "(\"identity\", 2)"]` | 1.18 (5%) :x: | 1.02 (1%) :x: |
| `["parallel", "remotecall", "(\"identity\", 4096)"]` | 1.16 (5%) :x: | 1.00 (1%)  |
| `["parallel", "remotecall", "(\"identity\", 512)"]` | 1.15 (5%) :x: | 1.01 (1%) :x: |
| `["parallel", "remotecall", "(\"identity\", 64)"]` | 1.17 (5%) :x: | 1.02 (1%) :x: |

## Benchmark Group List

Here's a list of all the benchmark groups executed by this job:

- `["io", "array_limit"]`
- `["io", "read"]`
- `["io", "serialization"]`
- `["io"]`
- `["parallel", "remotecall"]`

## Version Info

#### Primary Build

```
Julia Version 1.7.0-DEV.647
Commit 49387b2bc6 (2021-03-02 21:03 UTC)
Platform Info:
  OS: Linux (x86_64-linux-gnu)
      Ubuntu 18.04.5 LTS
  uname: Linux 4.15.0-135-generic #139-Ubuntu SMP Mon Jan 18 17:38:24 UTC 2021 x86_64 x86_64
  CPU: Intel(R) Xeon(R) Silver 4114 CPU @ 2.20GHz: 
                 speed         user         nice          sys         idle          irq
       #1-40   800 MHz    6595098 s       5602 s     616878 s  731551620 s          0 s
       
  Memory: 376.5897979736328 GB (31352.38671875 MB free)
  Uptime: 1.847412e6 sec
  Load Avg:  1.42  1.16  0.94
  WORD_SIZE: 64
  LIBM: libopenlibm
  LLVM: libLLVM-11.0.1 (ORCJIT, skylake-avx512)

```
