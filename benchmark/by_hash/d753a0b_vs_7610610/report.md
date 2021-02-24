# Benchmark Report

## Job Properties

*Commit(s):* [vtjnash/julia@d753a0b6a78d94d08c17b2c227916700e3359e4a](https://github.com/vtjnash/julia/commit/d753a0b6a78d94d08c17b2c227916700e3359e4a) vs [vtjnash/julia@76106100559e6dc61769cdbd3d53836e22ffa5e9](https://github.com/vtjnash/julia/commit/76106100559e6dc61769cdbd3d53836e22ffa5e9)

*Triggered By:* [link](https://github.com/vtjnash/julia/commit/d753a0b6a78d94d08c17b2c227916700e3359e4a#commitcomment-47515446)

*Tag Predicate:* `"misc"`

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
| `["misc", "18129"]` | 1.07 (5%) :x: | 1.00 (1%)  |
| `["misc", "allocation elision view", "conditional"]` | 0.78 (5%) :white_check_mark: | 1.00 (1%)  |
| `["misc", "bitshift", "(\"UInt32\", \"UInt32\")"]` | 0.92 (5%) :white_check_mark: | 1.00 (1%)  |
| `["misc", "foldl", "foldl(+, filter(...))"]` | 1.41 (5%) :x: | 1.00 (1%)  |
| `["misc", "foldl", "foldl(+, filter(...); init = 0.0)"]` | 0.36 (5%) :white_check_mark: | 1.00 (1%)  |
| `["misc", "issue 12165", "Float16"]` | 0.95 (5%) :white_check_mark: | 1.00 (1%)  |
| `["misc", "issue 12165", "Float32"]` | 0.89 (5%) :white_check_mark: | 1.00 (1%)  |
| `["misc", "issue 12165", "Float64"]` | 0.77 (5%) :white_check_mark: | 1.00 (1%)  |
| `["misc", "iterators", "zip(1:1000)"]` | 0.85 (5%) :white_check_mark: | 1.00 (1%)  |
| `["misc", "iterators", "zip(1:1000, 1:1000, 1:1000)"]` | 1.07 (5%) :x: | 1.00 (1%)  |
| `["misc", "repeat", "(200, 1, 24)"]` | 0.93 (5%) :white_check_mark: | 1.00 (1%)  |

## Benchmark Group List

Here's a list of all the benchmark groups executed by this job:

- `["misc"]`
- `["misc", "23042"]`
- `["misc", "afoldl"]`
- `["misc", "allocation elision view"]`
- `["misc", "bitshift"]`
- `["misc", "foldl"]`
- `["misc", "issue 12165"]`
- `["misc", "iterators"]`
- `["misc", "julia"]`
- `["misc", "parse"]`
- `["misc", "repeat"]`
- `["misc", "splatting"]`
- `["tuple", "misc"]`

## Version Info

#### Primary Build

```
Julia Version 1.5.3
Commit 788b2c77c1 (2020-11-09 13:37 UTC)
Platform Info:
  OS: Linux (x86_64-pc-linux-gnu)
      Ubuntu 20.04.2 LTS
  uname: Linux 5.4.0-1037-aws #39-Ubuntu SMP Thu Jan 14 02:56:06 UTC 2021 x86_64 x86_64
  CPU: Intel(R) Xeon(R) Platinum 8124M CPU @ 3.00GHz: 
              speed         user         nice          sys         idle          irq
       #1  3408 MHz     561213 s       3859 s      58108 s   14880106 s          0 s
       #2  3400 MHz    6035612 s         37 s     140461 s    9330882 s          0 s
       #3  3401 MHz      80882 s        225 s       6730 s   15419269 s          0 s
       #4  3402 MHz     109901 s        116 s       6828 s   15386815 s          0 s
       #5  3407 MHz      55060 s        169 s       8214 s   15174417 s          0 s
       #6  3403 MHz     128113 s        239 s       6908 s   15371150 s          0 s
       #7  3418 MHz      92278 s         92 s      12780 s   15402186 s          0 s
       #8  3411 MHz     108332 s        358 s       7666 s   15385155 s          0 s
       
  Memory: 30.362831115722656 GB (13887.6953125 MB free)
  Uptime: 155082.0 sec
  Load Avg:  2.05029296875  1.57275390625  0.79052734375
  WORD_SIZE: 64
  LIBM: libopenlibm
  LLVM: libLLVM-9.0.1 (ORCJIT, skylake-avx512)

```

#### Comparison Build

```
Julia Version 1.5.3
Commit 788b2c77c1 (2020-11-09 13:37 UTC)
Platform Info:
  OS: Linux (x86_64-pc-linux-gnu)
      Ubuntu 20.04.2 LTS
  uname: Linux 5.4.0-1037-aws #39-Ubuntu SMP Thu Jan 14 02:56:06 UTC 2021 x86_64 x86_64
  CPU: Intel(R) Xeon(R) Platinum 8124M CPU @ 3.00GHz: 
              speed         user         nice          sys         idle          irq
       #1  3388 MHz     590838 s       3859 s      59088 s   14880963 s          0 s
       #2  2987 MHz    6065253 s         37 s     141568 s    9331596 s          0 s
       #3  3401 MHz      81517 s        225 s       6806 s   15450016 s          0 s
       #4  3402 MHz     110049 s        116 s       6906 s   15418050 s          0 s
       #5  3400 MHz      55127 s        169 s       8275 s   15205753 s          0 s
       #6  3416 MHz     128270 s        239 s       6965 s   15402396 s          0 s
       #7  3408 MHz      92338 s         92 s      12840 s   15433527 s          0 s
       #8  3425 MHz     108393 s        358 s       7722 s   15416497 s          0 s
       
  Memory: 30.362831115722656 GB (15054.4375 MB free)
  Uptime: 155396.0 sec
  Load Avg:  1.919921875  1.84326171875  1.1455078125
  WORD_SIZE: 64
  LIBM: libopenlibm
  LLVM: libLLVM-9.0.1 (ORCJIT, skylake-avx512)

```
