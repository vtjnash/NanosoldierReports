# Benchmark Report

## Job Properties

*Commit(s):* [vtjnash/julia@d753a0b6a78d94d08c17b2c227916700e3359e4a](https://github.com/vtjnash/julia/commit/d753a0b6a78d94d08c17b2c227916700e3359e4a) vs [vtjnash/julia@76106100559e6dc61769cdbd3d53836e22ffa5e9](https://github.com/vtjnash/julia/commit/76106100559e6dc61769cdbd3d53836e22ffa5e9)

*Triggered By:* [link](https://github.com/vtjnash/julia/commit/d753a0b6a78d94d08c17b2c227916700e3359e4a#commitcomment-47438489)

*Tag Predicate:* `"micro"`

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
| `["micro", "fib"]` | 1.09 (5%) :x: | 1.00 (1%)  |

## Benchmark Group List

Here's a list of all the benchmark groups executed by this job:

- `["micro"]`

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
       #1  3404 MHz      29244 s         65 s       1794 s    1254317 s          0 s
       #2  3414 MHz       6119 s         21 s       1461 s    1278066 s          0 s
       #3  3401 MHz      18916 s         55 s       2073 s    1264704 s          0 s
       #4  3405 MHz      14224 s         26 s       1760 s    1266533 s          0 s
       #5  3402 MHz      16384 s        113 s       2027 s     997911 s          0 s
       #6  3402 MHz      25691 s         65 s       2385 s    1256693 s          0 s
       #7  3395 MHz      14686 s         28 s       1632 s    1269335 s          0 s
       #8  3400 MHz       8382 s        201 s       1302 s    1273319 s          0 s
       
  Memory: 30.362831115722656 GB (15659.91796875 MB free)
  Uptime: 12858.0 sec
  Load Avg:  0.9912109375  0.65283203125  0.3466796875
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
       #1  3400 MHz      49199 s         65 s       2369 s    1254784 s          0 s
       #2  3410 MHz       6179 s         21 s       1491 s    1298977 s          0 s
       #3  3407 MHz      18943 s         55 s       2099 s    1285654 s          0 s
       #4  3399 MHz      14256 s         26 s       1791 s    1287473 s          0 s
       #5  3410 MHz      16420 s        113 s       2061 s    1018853 s          0 s
       #6  3401 MHz      25723 s         65 s       2411 s    1277637 s          0 s
       #7  3392 MHz      14747 s         28 s       1658 s    1290258 s          0 s
       #8  3400 MHz       8747 s        201 s       1357 s    1293896 s          0 s
       
  Memory: 30.362831115722656 GB (15659.29296875 MB free)
  Uptime: 13069.0 sec
  Load Avg:  1.0  0.83544921875  0.4873046875
  WORD_SIZE: 64
  LIBM: libopenlibm
  LLVM: libLLVM-9.0.1 (ORCJIT, skylake-avx512)

```
