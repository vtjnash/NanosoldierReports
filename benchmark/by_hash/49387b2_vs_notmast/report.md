# Benchmark Report

## Job Properties

*Commit(s):* [vtjnash/julia@49387b2bc67f90650e5c2a982d8fb31e7e6d90b7](https://github.com/vtjnash/julia/commit/49387b2bc67f90650e5c2a982d8fb31e7e6d90b7) vs [vtjnash/julia@notmaster^](https://github.com/vtjnash/julia/commit/notmaster^)

*Triggered By:* [link](https://github.com/vtjnash/julia/commit/49387b2bc67f90650e5c2a982d8fb31e7e6d90b7#commitcomment-47821795)

*Tag Predicate:* `"io"`

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
| `["io", "array_limit", "(\"display\", \"Matrix{Float64}(10000, 10000)\")"]` | 0.97 (5%)  | 0.91 (1%) :white_check_mark: |
| `["parallel", "remotecall", "(\"identity\", 1024)"]` | 0.88 (5%) :white_check_mark: | 1.00 (1%)  |
| `["parallel", "remotecall", "(\"identity\", 4096)"]` | 0.90 (5%) :white_check_mark: | 0.99 (1%)  |

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
       #1-40   800 MHz    5662494 s       5494 s     541042 s  699708440 s          0 s
       
  Memory: 376.5897979736328 GB (26017.8125 MB free)
  Uptime: 1.765252e6 sec
  Load Avg:  1.25  1.39  2.63
  WORD_SIZE: 64
  LIBM: libopenlibm
  LLVM: libLLVM-11.0.1 (ORCJIT, skylake-avx512)

```

#### Comparison Build

```
Julia Version 1.7.0-DEV.646
Commit de7d695c28 (2021-03-02 20:56 UTC)
Platform Info:
  OS: Linux (x86_64-linux-gnu)
      Ubuntu 18.04.5 LTS
  uname: Linux 4.15.0-135-generic #139-Ubuntu SMP Mon Jan 18 17:38:24 UTC 2021 x86_64 x86_64
  CPU: Intel(R) Xeon(R) Silver 4114 CPU @ 2.20GHz: 
                 speed         user         nice          sys         idle          irq
       #1-40   800 MHz    5673093 s       5494 s     542007 s  700019968 s          0 s
       
  Memory: 376.5897979736328 GB (25630.9375 MB free)
  Uptime: 1.766061e6 sec
  Load Avg:  1.27  1.62  2.07
  WORD_SIZE: 64
  LIBM: libopenlibm
  LLVM: libLLVM-11.0.1 (ORCJIT, skylake-avx512)

```
