# Benchmark Report

## Job Properties

*Commit(s):* [vtjnash/julia@d753a0b6a78d94d08c17b2c227916700e3359e4a](https://github.com/vtjnash/julia/commit/d753a0b6a78d94d08c17b2c227916700e3359e4a)

*Triggered By:* [link](https://github.com/vtjnash/julia/commit/d753a0b6a78d94d08c17b2c227916700e3359e4a#commitcomment-47466138)

*Tag Predicate:* `ALL`

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

| ID | time | GC time | memory | allocations |
|----|------|---------|--------|-------------|
| `["array", "accumulate", "(\"accumulate!\", \"Float64\")"]` | 1.201 μs (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "accumulate", "(\"accumulate!\", \"Int\")"]` | 331.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "accumulate", "(\"accumulate\", \"Float64\")"]` | 1.370 μs (5%) | 0.000 ns | 7.94 KiB (1%) | 1 |
| `["array", "accumulate", "(\"accumulate\", \"Int\")"]` | 740.000 ns (5%) | 0.000 ns | 7.94 KiB (1%) | 1 |
| `["array", "accumulate", "(\"cumsum!\", \"Float64\")"]` | 1.211 μs (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "accumulate", "(\"cumsum!\", \"Float64\", \"dim1\")"]` | 1.171 ms (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "accumulate", "(\"cumsum!\", \"Float64\", \"dim2\")"]` | 1.198 ms (5%) | 0.000 ns | 48 bytes (1%) | 3 |
| `["array", "accumulate", "(\"cumsum!\", \"Int\")"]` | 330.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "accumulate", "(\"cumsum\", \"Float64\")"]` | 1.398 μs (5%) | 0.000 ns | 7.94 KiB (1%) | 1 |
| `["array", "accumulate", "(\"cumsum\", \"Float64\", \"dim1\")"]` | 1.240 ms (5%) | 0.000 ns | 7.63 MiB (1%) | 2 |
| `["array", "accumulate", "(\"cumsum\", \"Float64\", \"dim2\")"]` | 1.271 ms (5%) | 0.000 ns | 7.63 MiB (1%) | 5 |
| `["array", "accumulate", "(\"cumsum\", \"Int\")"]` | 754.000 ns (5%) | 0.000 ns | 7.94 KiB (1%) | 1 |
| `["array", "any/all", "(\"all\", \"BitArray\")"]` | 95.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "any/all", "(\"all\", \"UnitRange{Int64} generator\")"]` | 2.988 μs (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "any/all", "(\"all\", \"UnitRange{Int64}\")"]` | 2.987 μs (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "any/all", "(\"all\", \"Vector{Bool}\")"]` | 3.959 μs (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "any/all", "(\"all\", \"Vector{Float32} generator\")"]` | 4.603 μs (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "any/all", "(\"all\", \"Vector{Float32}\")"]` | 4.599 μs (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "any/all", "(\"all\", \"Vector{Float64} generator\")"]` | 4.643 μs (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "any/all", "(\"all\", \"Vector{Float64}\")"]` | 4.645 μs (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "any/all", "(\"all\", \"Vector{Int16} generator\")"]` | 3.962 μs (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "any/all", "(\"all\", \"Vector{Int16}\")"]` | 3.966 μs (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "any/all", "(\"all\", \"Vector{Int64} generator\")"]` | 4.255 μs (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "any/all", "(\"all\", \"Vector{Int64}\")"]` | 4.253 μs (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "any/all", "(\"any\", \"BitArray\")"]` | 93.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "any/all", "(\"any\", \"UnitRange{Int64} generator\")"]` | 2.988 μs (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "any/all", "(\"any\", \"UnitRange{Int64}\")"]` | 2.986 μs (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "any/all", "(\"any\", \"Vector{Bool}\")"]` | 3.963 μs (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "any/all", "(\"any\", \"Vector{Float32} generator\")"]` | 5.928 μs (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "any/all", "(\"any\", \"Vector{Float32}\")"]` | 5.928 μs (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "any/all", "(\"any\", \"Vector{Float64} generator\")"]` | 4.642 μs (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "any/all", "(\"any\", \"Vector{Float64}\")"]` | 5.928 μs (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "any/all", "(\"any\", \"Vector{Int16} generator\")"]` | 3.981 μs (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "any/all", "(\"any\", \"Vector{Int16}\")"]` | 3.964 μs (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "any/all", "(\"any\", \"Vector{Int64} generator\")"]` | 4.257 μs (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "any/all", "(\"any\", \"Vector{Int64}\")"]` | 4.254 μs (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "bool", "bitarray_bool_load!"]` | 1.715 ms (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "bool", "bitarray_true_fill!"]` | 1.904 μs (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "bool", "bitarray_true_load!"]` | 1.327 ms (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "bool", "boolarray_bool_load!"]` | 599.027 μs (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "bool", "boolarray_true_fill!"]` | 27.928 μs (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "bool", "boolarray_true_load!"]` | 323.288 μs (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "cat", "(\"catnd\", 5)"]` | 21.277 μs (5%) | 0.000 ns | 43.16 KiB (1%) | 76 |
| `["array", "cat", "(\"catnd\", 500)"]` | 3.048 ms (5%) | 0.000 ns | 11.49 MiB (1%) | 79 |
| `["array", "cat", "(\"catnd_setind\", 5)"]` | 19.133 μs (5%) | 0.000 ns | 41.73 KiB (1%) | 41 |
| `["array", "cat", "(\"catnd_setind\", 500)"]` | 2.227 ms (5%) | 0.000 ns | 11.48 MiB (1%) | 44 |
| `["array", "cat", "(\"hcat\", 5)"]` | 80.000 ns (5%) | 0.000 ns | 896 bytes (1%) | 1 |
| `["array", "cat", "(\"hcat\", 500)"]` | 1.175 ms (5%) | 0.000 ns | 7.63 MiB (1%) | 2 |
| `["array", "cat", "(\"hcat_setind\", 5)"]` | 204.000 ns (5%) | 0.000 ns | 896 bytes (1%) | 1 |
| `["array", "cat", "(\"hcat_setind\", 500)"]` | 1.100 ms (5%) | 0.000 ns | 7.63 MiB (1%) | 2 |
| `["array", "cat", "(\"hvcat\", 5)"]` | 226.000 ns (5%) | 0.000 ns | 896 bytes (1%) | 1 |
| `["array", "cat", "(\"hvcat\", 500)"]` | 1.193 ms (5%) | 0.000 ns | 7.63 MiB (1%) | 2 |
| `["array", "cat", "(\"hvcat_setind\", 5)"]` | 202.000 ns (5%) | 0.000 ns | 896 bytes (1%) | 1 |
| `["array", "cat", "(\"hvcat_setind\", 500)"]` | 1.195 ms (5%) | 0.000 ns | 7.63 MiB (1%) | 2 |
| `["array", "cat", "(\"vcat\", 5)"]` | 207.000 ns (5%) | 0.000 ns | 896 bytes (1%) | 1 |
| `["array", "cat", "(\"vcat\", 500)"]` | 1.176 ms (5%) | 0.000 ns | 7.63 MiB (1%) | 2 |
| `["array", "cat", "(\"vcat_setind\", 5)"]` | 205.000 ns (5%) | 0.000 ns | 896 bytes (1%) | 1 |
| `["array", "cat", "(\"vcat_setind\", 500)"]` | 1.172 ms (5%) | 0.000 ns | 7.63 MiB (1%) | 2 |
| `["array", "cat", "4467"]` | 150.876 ns (5%) | 0.000 ns | 368 bytes (1%) | 8 |
| `["array", "comprehension", "(\"collect\", \"StepRangeLen{Float64, Base.TwicePrecision{Float64}, Base.TwicePrecision{Float64}}\")"]` | 58.368 ms (5%) | 0.000 ns | 76.29 MiB (1%) | 2 |
| `["array", "comprehension", "(\"collect\", \"Vector{Float64}\")"]` | 52.022 ms (5%) | 0.000 ns | 76.29 MiB (1%) | 2 |
| `["array", "comprehension", "(\"comprehension_collect\", \"StepRangeLen{Float64, Base.TwicePrecision{Float64}, Base.TwicePrecision{Float64}}\")"]` | 58.771 ms (5%) | 0.000 ns | 76.29 MiB (1%) | 2 |
| `["array", "comprehension", "(\"comprehension_collect\", \"Vector{Float64}\")"]` | 39.248 ms (5%) | 0.000 ns | 76.29 MiB (1%) | 2 |
| `["array", "comprehension", "(\"comprehension_indexing\", \"StepRangeLen{Float64, Base.TwicePrecision{Float64}, Base.TwicePrecision{Float64}}\")"]` | 191.405 ms (30%) | 0.000 ns | 76.29 MiB (1%) | 2 |
| `["array", "comprehension", "(\"comprehension_indexing\", \"Vector{Float64}\")"]` | 88.450 ms (30%) | 0.000 ns | 76.29 MiB (1%) | 2 |
| `["array", "comprehension", "(\"comprehension_iteration\", \"StepRangeLen{Float64, Base.TwicePrecision{Float64}, Base.TwicePrecision{Float64}}\")"]` | 191.442 ms (5%) | 0.000 ns | 76.29 MiB (1%) | 2 |
| `["array", "comprehension", "(\"comprehension_iteration\", \"Vector{Float64}\")"]` | 88.104 ms (5%) | 0.000 ns | 76.29 MiB (1%) | 2 |
| `["array", "convert", "(\"Complex{Float64}\", \"Int\")"]` | 7.192 μs (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "convert", "(\"Float64\", \"Int\")"]` | 4.502 μs (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "convert", "(\"Int\", \"Complex{Float64}\")"]` | 20.668 μs (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "convert", "(\"Int\", \"Float64\")"]` | 15.662 μs (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "equality", "(\"==\", \"BitArray\")"]` | 47.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "equality", "(\"==\", \"UnitRange{Int64}\")"]` | 23.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "equality", "(\"==\", \"Vector{Bool}\")"]` | 5.922 μs (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "equality", "(\"==\", \"Vector{Float32}\")"]` | 7.449 μs (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "equality", "(\"==\", \"Vector{Float64}\")"]` | 7.456 μs (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "equality", "(\"==\", \"Vector{Int16}\")"]` | 464.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "equality", "(\"==\", \"Vector{Int64} == UnitRange{Int64}\")"]` | 5.931 μs (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "equality", "(\"==\", \"Vector{Int64} == Vector{Float32}\")"]` | 17.700 μs (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "equality", "(\"==\", \"Vector{Int64} == Vector{Float64}\")"]` | 17.695 μs (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "equality", "(\"==\", \"Vector{Int64} == Vector{Int16}\")"]` | 5.930 μs (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "equality", "(\"==\", \"Vector{Int64} == Vector{Int64}\")"]` | 1.660 μs (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "equality", "(\"==\", \"Vector{Int64}\")"]` | 1.798 μs (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "equality", "(\"isequal\", \"BitArray\")"]` | 17.690 μs (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "equality", "(\"isequal\", \"UnitRange{Int64}\")"]` | 23.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "equality", "(\"isequal\", \"Vector{Bool}\")"]` | 5.922 μs (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "equality", "(\"isequal\", \"Vector{Float32}\")"]` | 16.545 μs (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "equality", "(\"isequal\", \"Vector{Float64}\")"]` | 16.894 μs (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "equality", "(\"isequal\", \"Vector{Int16}\")"]` | 5.930 μs (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "equality", "(\"isequal\", \"Vector{Int64} isequal UnitRange{Int64}\")"]` | 4.470 μs (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "equality", "(\"isequal\", \"Vector{Int64} isequal Vector{Float32}\")"]` | 19.641 μs (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "equality", "(\"isequal\", \"Vector{Int64} isequal Vector{Float64}\")"]` | 20.638 μs (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "equality", "(\"isequal\", \"Vector{Int64} isequal Vector{Int16}\")"]` | 5.930 μs (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "equality", "(\"isequal\", \"Vector{Int64} isequal Vector{Int64}\")"]` | 24.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "equality", "(\"isequal\", \"Vector{Int64}\")"]` | 5.936 μs (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "growth", "(\"append!\", 2048)"]` | 4.716 μs (5%) | 0.000 ns | 32.06 KiB (1%) | 1 |
| `["array", "growth", "(\"append!\", 256)"]` | 474.000 ns (5%) | 0.000 ns | 4.06 KiB (1%) | 1 |
| `["array", "growth", "(\"append!\", 8)"]` | 51.000 ns (5%) | 0.000 ns | 144 bytes (1%) | 1 |
| `["array", "growth", "(\"prerend!\", 2048)"]` | 4.831 μs (5%) | 0.000 ns | 64.06 KiB (1%) | 1 |
| `["array", "growth", "(\"prerend!\", 256)"]` | 482.000 ns (5%) | 0.000 ns | 8.06 KiB (1%) | 1 |
| `["array", "growth", "(\"prerend!\", 8)"]` | 55.000 ns (5%) | 0.000 ns | 272 bytes (1%) | 1 |
| `["array", "growth", "(\"push_multiple!\", 2048)"]` | 15.697 μs (5%) | 0.000 ns | 32.06 KiB (1%) | 1 |
| `["array", "growth", "(\"push_multiple!\", 256)"]` | 2.010 μs (5%) | 0.000 ns | 4.06 KiB (1%) | 1 |
| `["array", "growth", "(\"push_multiple!\", 8)"]` | 94.000 ns (5%) | 0.000 ns | 144 bytes (1%) | 1 |
| `["array", "growth", "(\"push_single!\", 2048)"]` | 2.448 μs (5%) | 0.000 ns | 32.06 KiB (1%) | 1 |
| `["array", "growth", "(\"push_single!\", 256)"]` | 281.000 ns (5%) | 0.000 ns | 4.06 KiB (1%) | 1 |
| `["array", "growth", "(\"push_single!\", 8)"]` | 47.000 ns (5%) | 0.000 ns | 144 bytes (1%) | 1 |
| `["array", "index", "(\"mapr_access\", \"Base.ReinterpretArray{BaseBenchmarks.ArrayBenchmarks.PairVals{Float32}, 2, Float32, Matrix{Float32}, false}\")"]` | 280.419 μs (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"mapr_access\", \"Base.ReinterpretArray{BaseBenchmarks.ArrayBenchmarks.PairVals{Float32}, 2, Float64, Matrix{Float64}, false}\")"]` | 1.487 ms (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"mapr_access\", \"Base.ReinterpretArray{BaseBenchmarks.ArrayBenchmarks.PairVals{Int32}, 2, Int32, Matrix{Int32}, false}\")"]` | 266.515 μs (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"mapr_access\", \"Base.ReinterpretArray{BaseBenchmarks.ArrayBenchmarks.PairVals{Int32}, 2, Int64, Matrix{Int64}, false}\")"]` | 1.036 ms (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"mapr_access\", \"Base.ReinterpretArray{Float32, 2, Int32, Matrix{Int32}, false}\")"]` | 474.530 μs (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"mapr_access\", \"BaseBenchmarks.ArrayBenchmarks.ArrayLF{Float32, 2}\")"]` | 534.210 μs (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"mapr_access\", \"BaseBenchmarks.ArrayBenchmarks.ArrayLF{Int32, 2}\")"]` | 500.828 μs (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"mapr_access\", \"BaseBenchmarks.ArrayBenchmarks.ArrayLSLS{Float32, 2}\")"]` | 155.388 μs (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"mapr_access\", \"BaseBenchmarks.ArrayBenchmarks.ArrayLSLS{Int32, 2}\")"]` | 154.837 μs (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"mapr_access\", \"BaseBenchmarks.ArrayBenchmarks.ArrayLS{Float32, 2}\")"]` | 155.576 μs (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"mapr_access\", \"BaseBenchmarks.ArrayBenchmarks.ArrayLS{Int32, 2}\")"]` | 154.657 μs (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"mapr_access\", \"BitMatrix\")"]` | 852.578 μs (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"mapr_access\", \"Matrix{Float32}\")"]` | 155.114 μs (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"mapr_access\", \"Matrix{Float64}\")"]` | 168.467 μs (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"mapr_access\", \"Matrix{Int32}\")"]` | 154.351 μs (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"mapr_access\", \"Matrix{Int64}\")"]` | 169.550 μs (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"mapr_access\", \"SubArray{Float32, 2, Array{Float32, 3}, Tuple{Int64, Base.Slice{Base.OneTo{Int64}}, Base.Slice{Base.OneTo{Int64}}}, true}\")"]` | 260.326 μs (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"mapr_access\", \"SubArray{Float32, 2, Base.ReshapedArray{Float32, 2, SubArray{Float32, 3, Array{Float32, 3}, Tuple{Base.Slice{Base.OneTo{Int64}}, Base.Slice{Base.OneTo{Int64}}, Base.Slice{Base.OneTo{Int64}}}, true}, Tuple{}}, Tuple{Base.Slice{Base.OneTo{Int64}}, UnitRange{Int64}}, true}\")"]` | 105.000 ns (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"mapr_access\", \"SubArray{Float32, 2, Base.ReshapedArray{Float32, 2, SubArray{Float32, 3, BaseBenchmarks.ArrayBenchmarks.ArrayLS{Float32, 3}, Tuple{Base.Slice{Base.OneTo{Int64}}, Base.Slice{Base.OneTo{Int64}}, Base.Slice{Base.OneTo{Int64}}}, false}, Tuple{Base.MultiplicativeInverses.SignedMultiplicativeInverse{Int64}, Base.MultiplicativeInverses.SignedMultiplicativeInverse{Int64}}}, Tuple{Base.Slice{Base.OneTo{Int64}}, UnitRange{Int64}}, false}\")"]` | 148.000 ns (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"mapr_access\", \"SubArray{Float32, 2, BaseBenchmarks.ArrayBenchmarks.ArrayLS{Float32, 2}, Tuple{Base.Slice{Base.OneTo{Int64}}, Base.Slice{Base.OneTo{Int64}}}, false}\")"]` | 161.996 μs (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"mapr_access\", \"SubArray{Float32, 2, BaseBenchmarks.ArrayBenchmarks.ArrayLS{Float32, 3}, Tuple{Int64, Base.Slice{Base.OneTo{Int64}}, Base.Slice{Base.OneTo{Int64}}}, false}\")"]` | 235.631 μs (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"mapr_access\", \"SubArray{Float32, 2, Matrix{Float32}, Tuple{Base.Slice{Base.OneTo{Int64}}, Base.Slice{Base.OneTo{Int64}}}, true}\")"]` | 192.549 μs (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"mapr_access\", \"SubArray{Float32, 2, Matrix{Float32}, Tuple{UnitRange{Int64}, UnitRange{Int64}}, false}\")"]` | 161.987 μs (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"mapr_access\", \"SubArray{Int32, 2, Array{Int32, 3}, Tuple{Int64, Base.Slice{Base.OneTo{Int64}}, Base.Slice{Base.OneTo{Int64}}}, true}\")"]` | 243.350 μs (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"mapr_access\", \"SubArray{Int32, 2, Base.ReshapedArray{Int32, 2, SubArray{Int32, 3, Array{Int32, 3}, Tuple{Base.Slice{Base.OneTo{Int64}}, Base.Slice{Base.OneTo{Int64}}, Base.Slice{Base.OneTo{Int64}}}, true}, Tuple{}}, Tuple{Base.Slice{Base.OneTo{Int64}}, UnitRange{Int64}}, true}\")"]` | 100.000 ns (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"mapr_access\", \"SubArray{Int32, 2, Base.ReshapedArray{Int32, 2, SubArray{Int32, 3, BaseBenchmarks.ArrayBenchmarks.ArrayLS{Int32, 3}, Tuple{Base.Slice{Base.OneTo{Int64}}, Base.Slice{Base.OneTo{Int64}}, Base.Slice{Base.OneTo{Int64}}}, false}, Tuple{Base.MultiplicativeInverses.SignedMultiplicativeInverse{Int64}, Base.MultiplicativeInverses.SignedMultiplicativeInverse{Int64}}}, Tuple{Base.Slice{Base.OneTo{Int64}}, UnitRange{Int64}}, false}\")"]` | 143.000 ns (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"mapr_access\", \"SubArray{Int32, 2, BaseBenchmarks.ArrayBenchmarks.ArrayLS{Int32, 2}, Tuple{Base.Slice{Base.OneTo{Int64}}, Base.Slice{Base.OneTo{Int64}}}, false}\")"]` | 160.255 μs (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"mapr_access\", \"SubArray{Int32, 2, BaseBenchmarks.ArrayBenchmarks.ArrayLS{Int32, 3}, Tuple{Int64, Base.Slice{Base.OneTo{Int64}}, Base.Slice{Base.OneTo{Int64}}}, false}\")"]` | 242.560 μs (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"mapr_access\", \"SubArray{Int32, 2, Matrix{Int32}, Tuple{Base.Slice{Base.OneTo{Int64}}, Base.Slice{Base.OneTo{Int64}}}, true}\")"]` | 163.299 μs (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"mapr_access\", \"SubArray{Int32, 2, Matrix{Int32}, Tuple{UnitRange{Int64}, UnitRange{Int64}}, false}\")"]` | 156.961 μs (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sum\", \"3darray\")"]` | 160.000 ns (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sum\", \"3dsubarray\")"]` | 2.821 μs (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumcartesian\", \"1.0:0.00010001000100010001:2.0\")"]` | 24.382 μs (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumcartesian\", \"1.0:1.0:100000.0\")"]` | 234.105 μs (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumcartesian\", \"100000:-1:1\")"]` | 88.279 μs (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumcartesian\", \"1:100000\")"]` | 74.256 μs (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumcartesian\", \"Array{Float64, 3}\")"]` | 1.592 μs (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumcartesian\", \"Base.ReinterpretArray{BaseBenchmarks.ArrayBenchmarks.PairVals{Float32}, 2, Float32, Matrix{Float32}, false}\")"]` | 147.186 μs (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumcartesian\", \"Base.ReinterpretArray{BaseBenchmarks.ArrayBenchmarks.PairVals{Float32}, 2, Float64, Matrix{Float64}, false}\")"]` | 294.327 μs (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumcartesian\", \"Base.ReinterpretArray{BaseBenchmarks.ArrayBenchmarks.PairVals{Int32}, 2, Int32, Matrix{Int32}, false}\")"]` | 56.412 μs (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumcartesian\", \"Base.ReinterpretArray{BaseBenchmarks.ArrayBenchmarks.PairVals{Int32}, 2, Int64, Matrix{Int64}, false}\")"]` | 371.177 μs (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumcartesian\", \"Base.ReinterpretArray{Float32, 2, Int32, Matrix{Int32}, false}\")"]` | 294.181 μs (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumcartesian\", \"Base.ReinterpretArray{Int32, 3, Float64, Array{Float64, 3}, false}\")"]` | 4.092 μs (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumcartesian\", \"BaseBenchmarks.ArrayBenchmarks.ArrayLF{Float32, 2}\")"]` | 294.196 μs (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumcartesian\", \"BaseBenchmarks.ArrayBenchmarks.ArrayLF{Int32, 2}\")"]` | 19.992 μs (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumcartesian\", \"BaseBenchmarks.ArrayBenchmarks.ArrayLSLS{Float32, 2}\")"]` | 294.177 μs (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumcartesian\", \"BaseBenchmarks.ArrayBenchmarks.ArrayLSLS{Int32, 2}\")"]` | 17.888 μs (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumcartesian\", \"BaseBenchmarks.ArrayBenchmarks.ArrayLS{Float32, 2}\")"]` | 294.173 μs (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumcartesian\", \"BaseBenchmarks.ArrayBenchmarks.ArrayLS{Int32, 2}\")"]` | 17.869 μs (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumcartesian\", \"BitMatrix\")"]` | 448.611 μs (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumcartesian\", \"Matrix{Float32}\")"]` | 294.190 μs (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumcartesian\", \"Matrix{Float64}\")"]` | 294.192 μs (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumcartesian\", \"Matrix{Int32}\")"]` | 19.988 μs (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumcartesian\", \"Matrix{Int64}\")"]` | 71.721 μs (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumcartesian\", \"SubArray{Float32, 2, Array{Float32, 3}, Tuple{Int64, Base.Slice{Base.OneTo{Int64}}, Base.Slice{Base.OneTo{Int64}}}, true}\")"]` | 297.551 μs (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumcartesian\", \"SubArray{Float32, 2, Base.ReshapedArray{Float32, 2, SubArray{Float32, 3, Array{Float32, 3}, Tuple{Base.Slice{Base.OneTo{Int64}}, Base.Slice{Base.OneTo{Int64}}, Base.Slice{Base.OneTo{Int64}}}, true}, Tuple{}}, Tuple{Base.Slice{Base.OneTo{Int64}}, UnitRange{Int64}}, true}\")"]` | 2.376 μs (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumcartesian\", \"SubArray{Float32, 2, Base.ReshapedArray{Float32, 2, SubArray{Float32, 3, BaseBenchmarks.ArrayBenchmarks.ArrayLS{Float32, 3}, Tuple{Base.Slice{Base.OneTo{Int64}}, Base.Slice{Base.OneTo{Int64}}, Base.Slice{Base.OneTo{Int64}}}, false}, Tuple{Base.MultiplicativeInverses.SignedMultiplicativeInverse{Int64}, Base.MultiplicativeInverses.SignedMultiplicativeInverse{Int64}}}, Tuple{Base.Slice{Base.OneTo{Int64}}, UnitRange{Int64}}, false}\")"]` | 8.374 μs (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumcartesian\", \"SubArray{Float32, 2, BaseBenchmarks.ArrayBenchmarks.ArrayLS{Float32, 2}, Tuple{Base.Slice{Base.OneTo{Int64}}, Base.Slice{Base.OneTo{Int64}}}, false}\")"]` | 297.423 μs (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumcartesian\", \"SubArray{Float32, 2, BaseBenchmarks.ArrayBenchmarks.ArrayLS{Float32, 3}, Tuple{Int64, Base.Slice{Base.OneTo{Int64}}, Base.Slice{Base.OneTo{Int64}}}, false}\")"]` | 293.086 μs (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumcartesian\", \"SubArray{Float32, 2, Matrix{Float32}, Tuple{Base.Slice{Base.OneTo{Int64}}, Base.Slice{Base.OneTo{Int64}}}, true}\")"]` | 297.481 μs (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumcartesian\", \"SubArray{Float32, 2, Matrix{Float32}, Tuple{UnitRange{Int64}, UnitRange{Int64}}, false}\")"]` | 297.412 μs (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumcartesian\", \"SubArray{Float64, 3, Array{Float64, 3}, Tuple{UnitRange{Int64}, UnitRange{Int64}, UnitRange{Int64}}, false}\")"]` | 1.207 μs (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumcartesian\", \"SubArray{Int32, 2, Array{Int32, 3}, Tuple{Int64, Base.Slice{Base.OneTo{Int64}}, Base.Slice{Base.OneTo{Int64}}}, true}\")"]` | 297.632 μs (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumcartesian\", \"SubArray{Int32, 2, Base.ReshapedArray{Int32, 2, SubArray{Int32, 3, Array{Int32, 3}, Tuple{Base.Slice{Base.OneTo{Int64}}, Base.Slice{Base.OneTo{Int64}}, Base.Slice{Base.OneTo{Int64}}}, true}, Tuple{}}, Tuple{Base.Slice{Base.OneTo{Int64}}, UnitRange{Int64}}, true}\")"]` | 2.236 μs (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumcartesian\", \"SubArray{Int32, 2, Base.ReshapedArray{Int32, 2, SubArray{Int32, 3, BaseBenchmarks.ArrayBenchmarks.ArrayLS{Int32, 3}, Tuple{Base.Slice{Base.OneTo{Int64}}, Base.Slice{Base.OneTo{Int64}}, Base.Slice{Base.OneTo{Int64}}}, false}, Tuple{Base.MultiplicativeInverses.SignedMultiplicativeInverse{Int64}, Base.MultiplicativeInverses.SignedMultiplicativeInverse{Int64}}}, Tuple{Base.Slice{Base.OneTo{Int64}}, UnitRange{Int64}}, false}\")"]` | 8.007 μs (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumcartesian\", \"SubArray{Int32, 2, BaseBenchmarks.ArrayBenchmarks.ArrayLS{Int32, 2}, Tuple{Base.Slice{Base.OneTo{Int64}}, Base.Slice{Base.OneTo{Int64}}}, false}\")"]` | 224.634 μs (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumcartesian\", \"SubArray{Int32, 2, BaseBenchmarks.ArrayBenchmarks.ArrayLS{Int32, 3}, Tuple{Int64, Base.Slice{Base.OneTo{Int64}}, Base.Slice{Base.OneTo{Int64}}}, false}\")"]` | 296.402 μs (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumcartesian\", \"SubArray{Int32, 2, Matrix{Int32}, Tuple{Base.Slice{Base.OneTo{Int64}}, Base.Slice{Base.OneTo{Int64}}}, true}\")"]` | 158.653 μs (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumcartesian\", \"SubArray{Int32, 2, Matrix{Int32}, Tuple{UnitRange{Int64}, UnitRange{Int64}}, false}\")"]` | 224.589 μs (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumcartesian_view\", \"1.0:0.00010001000100010001:2.0\")"]` | 21.894 μs (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumcartesian_view\", \"1.0:1.0:100000.0\")"]` | 219.029 μs (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumcartesian_view\", \"100000:-1:1\")"]` | 1.882 ms (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumcartesian_view\", \"1:100000\")"]` | 8.159 μs (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumcartesian_view\", \"Array{Float64, 3}\")"]` | 1.590 μs (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumcartesian_view\", \"Base.ReinterpretArray{BaseBenchmarks.ArrayBenchmarks.PairVals{Float32}, 2, Float32, Matrix{Float32}, false}\")"]` | 38.416 μs (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumcartesian_view\", \"Base.ReinterpretArray{BaseBenchmarks.ArrayBenchmarks.PairVals{Float32}, 2, Float64, Matrix{Float64}, false}\")"]` | 73.240 μs (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumcartesian_view\", \"Base.ReinterpretArray{BaseBenchmarks.ArrayBenchmarks.PairVals{Int32}, 2, Int32, Matrix{Int32}, false}\")"]` | 37.489 μs (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumcartesian_view\", \"Base.ReinterpretArray{BaseBenchmarks.ArrayBenchmarks.PairVals{Int32}, 2, Int64, Matrix{Int64}, false}\")"]` | 73.264 μs (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumcartesian_view\", \"Base.ReinterpretArray{Float32, 2, Int32, Matrix{Int32}, false}\")"]` | 27.830 μs (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumcartesian_view\", \"Base.ReinterpretArray{Int32, 3, Float64, Array{Float64, 3}, false}\")"]` | 2.388 μs (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumcartesian_view\", \"BaseBenchmarks.ArrayBenchmarks.ArrayLF{Float32, 2}\")"]` | 27.289 μs (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumcartesian_view\", \"BaseBenchmarks.ArrayBenchmarks.ArrayLF{Int32, 2}\")"]` | 19.962 μs (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumcartesian_view\", \"BaseBenchmarks.ArrayBenchmarks.ArrayLSLS{Float32, 2}\")"]` | 27.019 μs (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumcartesian_view\", \"BaseBenchmarks.ArrayBenchmarks.ArrayLSLS{Int32, 2}\")"]` | 17.925 μs (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumcartesian_view\", \"BaseBenchmarks.ArrayBenchmarks.ArrayLS{Float32, 2}\")"]` | 26.984 μs (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumcartesian_view\", \"BaseBenchmarks.ArrayBenchmarks.ArrayLS{Int32, 2}\")"]` | 17.869 μs (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumcartesian_view\", \"BitMatrix\")"]` | 1.050 ms (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumcartesian_view\", \"Matrix{Float32}\")"]` | 27.286 μs (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumcartesian_view\", \"Matrix{Float64}\")"]` | 72.531 μs (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumcartesian_view\", \"Matrix{Int32}\")"]` | 19.957 μs (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumcartesian_view\", \"Matrix{Int64}\")"]` | 71.388 μs (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumcartesian_view\", \"SubArray{Float32, 2, Array{Float32, 3}, Tuple{Int64, Base.Slice{Base.OneTo{Int64}}, Base.Slice{Base.OneTo{Int64}}}, true}\")"]` | 294.232 μs (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumcartesian_view\", \"SubArray{Float32, 2, Base.ReshapedArray{Float32, 2, SubArray{Float32, 3, Array{Float32, 3}, Tuple{Base.Slice{Base.OneTo{Int64}}, Base.Slice{Base.OneTo{Int64}}, Base.Slice{Base.OneTo{Int64}}}, true}, Tuple{}}, Tuple{Base.Slice{Base.OneTo{Int64}}, UnitRange{Int64}}, true}\")"]` | 2.376 μs (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumcartesian_view\", \"SubArray{Float32, 2, Base.ReshapedArray{Float32, 2, SubArray{Float32, 3, BaseBenchmarks.ArrayBenchmarks.ArrayLS{Float32, 3}, Tuple{Base.Slice{Base.OneTo{Int64}}, Base.Slice{Base.OneTo{Int64}}, Base.Slice{Base.OneTo{Int64}}}, false}, Tuple{Base.MultiplicativeInverses.SignedMultiplicativeInverse{Int64}, Base.MultiplicativeInverses.SignedMultiplicativeInverse{Int64}}}, Tuple{Base.Slice{Base.OneTo{Int64}}, UnitRange{Int64}}, false}\")"]` | 8.240 μs (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumcartesian_view\", \"SubArray{Float32, 2, BaseBenchmarks.ArrayBenchmarks.ArrayLS{Float32, 2}, Tuple{Base.Slice{Base.OneTo{Int64}}, Base.Slice{Base.OneTo{Int64}}}, false}\")"]` | 26.987 μs (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumcartesian_view\", \"SubArray{Float32, 2, BaseBenchmarks.ArrayBenchmarks.ArrayLS{Float32, 3}, Tuple{Int64, Base.Slice{Base.OneTo{Int64}}, Base.Slice{Base.OneTo{Int64}}}, false}\")"]` | 293.051 μs (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumcartesian_view\", \"SubArray{Float32, 2, Matrix{Float32}, Tuple{Base.Slice{Base.OneTo{Int64}}, Base.Slice{Base.OneTo{Int64}}}, true}\")"]` | 27.282 μs (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumcartesian_view\", \"SubArray{Float32, 2, Matrix{Float32}, Tuple{UnitRange{Int64}, UnitRange{Int64}}, false}\")"]` | 26.417 μs (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumcartesian_view\", \"SubArray{Float64, 3, Array{Float64, 3}, Tuple{UnitRange{Int64}, UnitRange{Int64}, UnitRange{Int64}}, false}\")"]` | 1.208 μs (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumcartesian_view\", \"SubArray{Int32, 2, Array{Int32, 3}, Tuple{Int64, Base.Slice{Base.OneTo{Int64}}, Base.Slice{Base.OneTo{Int64}}}, true}\")"]` | 147.703 μs (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumcartesian_view\", \"SubArray{Int32, 2, Base.ReshapedArray{Int32, 2, SubArray{Int32, 3, Array{Int32, 3}, Tuple{Base.Slice{Base.OneTo{Int64}}, Base.Slice{Base.OneTo{Int64}}, Base.Slice{Base.OneTo{Int64}}}, true}, Tuple{}}, Tuple{Base.Slice{Base.OneTo{Int64}}, UnitRange{Int64}}, true}\")"]` | 1.207 μs (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumcartesian_view\", \"SubArray{Int32, 2, Base.ReshapedArray{Int32, 2, SubArray{Int32, 3, BaseBenchmarks.ArrayBenchmarks.ArrayLS{Int32, 3}, Tuple{Base.Slice{Base.OneTo{Int64}}, Base.Slice{Base.OneTo{Int64}}, Base.Slice{Base.OneTo{Int64}}}, false}, Tuple{Base.MultiplicativeInverses.SignedMultiplicativeInverse{Int64}, Base.MultiplicativeInverses.SignedMultiplicativeInverse{Int64}}}, Tuple{Base.Slice{Base.OneTo{Int64}}, UnitRange{Int64}}, false}\")"]` | 7.820 μs (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumcartesian_view\", \"SubArray{Int32, 2, BaseBenchmarks.ArrayBenchmarks.ArrayLS{Int32, 2}, Tuple{Base.Slice{Base.OneTo{Int64}}, Base.Slice{Base.OneTo{Int64}}}, false}\")"]` | 17.851 μs (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumcartesian_view\", \"SubArray{Int32, 2, BaseBenchmarks.ArrayBenchmarks.ArrayLS{Int32, 3}, Tuple{Int64, Base.Slice{Base.OneTo{Int64}}, Base.Slice{Base.OneTo{Int64}}}, false}\")"]` | 146.010 μs (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumcartesian_view\", \"SubArray{Int32, 2, Matrix{Int32}, Tuple{Base.Slice{Base.OneTo{Int64}}, Base.Slice{Base.OneTo{Int64}}}, true}\")"]` | 19.893 μs (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumcartesian_view\", \"SubArray{Int32, 2, Matrix{Int32}, Tuple{UnitRange{Int64}, UnitRange{Int64}}, false}\")"]` | 15.882 μs (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumcolon\", \"1.0:0.00010001000100010001:2.0\")"]` | 23.399 μs (50%) | 0.000 ns | 78.20 KiB (1%) | 2 |
| `["array", "index", "(\"sumcolon\", \"1.0:1.0:100000.0\")"]` | 231.538 μs (50%) | 0.000 ns | 781.33 KiB (1%) | 2 |
| `["array", "index", "(\"sumcolon\", \"100000:-1:1\")"]` | 94.119 μs (50%) | 0.000 ns | 781.33 KiB (1%) | 2 |
| `["array", "index", "(\"sumcolon\", \"1:100000\")"]` | 89.345 μs (50%) | 0.000 ns | 781.33 KiB (1%) | 2 |
| `["array", "index", "(\"sumcolon\", \"Base.ReinterpretArray{BaseBenchmarks.ArrayBenchmarks.PairVals{Float32}, 2, Float32, Matrix{Float32}, false}\")"]` | 297.806 μs (50%) | 0.000 ns | 1.04 MiB (1%) | 500 |
| `["array", "index", "(\"sumcolon\", \"Base.ReinterpretArray{BaseBenchmarks.ArrayBenchmarks.PairVals{Float32}, 2, Float64, Matrix{Float64}, false}\")"]` | 561.786 μs (50%) | 0.000 ns | 1.98 MiB (1%) | 500 |
| `["array", "index", "(\"sumcolon\", \"Base.ReinterpretArray{BaseBenchmarks.ArrayBenchmarks.PairVals{Int32}, 2, Int32, Matrix{Int32}, false}\")"]` | 297.385 μs (50%) | 0.000 ns | 1.04 MiB (1%) | 500 |
| `["array", "index", "(\"sumcolon\", \"Base.ReinterpretArray{BaseBenchmarks.ArrayBenchmarks.PairVals{Int32}, 2, Int64, Matrix{Int64}, false}\")"]` | 565.098 μs (50%) | 0.000 ns | 1.98 MiB (1%) | 500 |
| `["array", "index", "(\"sumcolon\", \"Base.ReinterpretArray{Float32, 2, Int32, Matrix{Int32}, false}\")"]` | 416.908 μs (50%) | 0.000 ns | 1.04 MiB (1%) | 500 |
| `["array", "index", "(\"sumcolon\", \"BaseBenchmarks.ArrayBenchmarks.ArrayLF{Float32, 2}\")"]` | 301.638 μs (50%) | 0.000 ns | 1.04 MiB (1%) | 500 |
| `["array", "index", "(\"sumcolon\", \"BaseBenchmarks.ArrayBenchmarks.ArrayLF{Int32, 2}\")"]` | 300.682 μs (50%) | 0.000 ns | 1.04 MiB (1%) | 500 |
| `["array", "index", "(\"sumcolon\", \"BaseBenchmarks.ArrayBenchmarks.ArrayLSLS{Float32, 2}\")"]` | 304.250 μs (50%) | 0.000 ns | 1.04 MiB (1%) | 500 |
| `["array", "index", "(\"sumcolon\", \"BaseBenchmarks.ArrayBenchmarks.ArrayLSLS{Int32, 2}\")"]` | 304.232 μs (50%) | 0.000 ns | 1.04 MiB (1%) | 500 |
| `["array", "index", "(\"sumcolon\", \"BaseBenchmarks.ArrayBenchmarks.ArrayLS{Float32, 2}\")"]` | 299.152 μs (50%) | 0.000 ns | 1.04 MiB (1%) | 500 |
| `["array", "index", "(\"sumcolon\", \"BaseBenchmarks.ArrayBenchmarks.ArrayLS{Int32, 2}\")"]` | 298.733 μs (50%) | 0.000 ns | 1.04 MiB (1%) | 500 |
| `["array", "index", "(\"sumcolon\", \"BitMatrix\")"]` | 31.914 μs (50%) | 0.000 ns | 85.94 KiB (1%) | 1000 |
| `["array", "index", "(\"sumcolon\", \"Matrix{Float32}\")"]` | 301.011 μs (50%) | 0.000 ns | 1.04 MiB (1%) | 500 |
| `["array", "index", "(\"sumcolon\", \"Matrix{Float64}\")"]` | 383.682 μs (50%) | 0.000 ns | 1.98 MiB (1%) | 500 |
| `["array", "index", "(\"sumcolon\", \"Matrix{Int32}\")"]` | 298.495 μs (50%) | 0.000 ns | 1.04 MiB (1%) | 500 |
| `["array", "index", "(\"sumcolon\", \"Matrix{Int64}\")"]` | 388.208 μs (50%) | 0.000 ns | 1.98 MiB (1%) | 500 |
| `["array", "index", "(\"sumcolon\", \"SubArray{Float32, 2, Array{Float32, 3}, Tuple{Int64, Base.Slice{Base.OneTo{Int64}}, Base.Slice{Base.OneTo{Int64}}}, true}\")"]` | 362.680 μs (50%) | 0.000 ns | 1.04 MiB (1%) | 500 |
| `["array", "index", "(\"sumcolon\", \"SubArray{Float32, 2, Base.ReshapedArray{Float32, 2, SubArray{Float32, 3, Array{Float32, 3}, Tuple{Base.Slice{Base.OneTo{Int64}}, Base.Slice{Base.OneTo{Int64}}, Base.Slice{Base.OneTo{Int64}}}, true}, Tuple{}}, Tuple{Base.Slice{Base.OneTo{Int64}}, UnitRange{Int64}}, true}\")"]` | 14.984 μs (50%) | 0.000 ns | 46.88 KiB (1%) | 500 |
| `["array", "index", "(\"sumcolon\", \"SubArray{Float32, 2, Base.ReshapedArray{Float32, 2, SubArray{Float32, 3, BaseBenchmarks.ArrayBenchmarks.ArrayLS{Float32, 3}, Tuple{Base.Slice{Base.OneTo{Int64}}, Base.Slice{Base.OneTo{Int64}}, Base.Slice{Base.OneTo{Int64}}}, false}, Tuple{Base.MultiplicativeInverses.SignedMultiplicativeInverse{Int64}, Base.MultiplicativeInverses.SignedMultiplicativeInverse{Int64}}}, Tuple{Base.Slice{Base.OneTo{Int64}}, UnitRange{Int64}}, false}\")"]` | 22.814 μs (50%) | 0.000 ns | 46.88 KiB (1%) | 500 |
| `["array", "index", "(\"sumcolon\", \"SubArray{Float32, 2, BaseBenchmarks.ArrayBenchmarks.ArrayLS{Float32, 2}, Tuple{Base.Slice{Base.OneTo{Int64}}, Base.Slice{Base.OneTo{Int64}}}, false}\")"]` | 302.476 μs (50%) | 0.000 ns | 1.04 MiB (1%) | 500 |
| `["array", "index", "(\"sumcolon\", \"SubArray{Float32, 2, BaseBenchmarks.ArrayBenchmarks.ArrayLS{Float32, 3}, Tuple{Int64, Base.Slice{Base.OneTo{Int64}}, Base.Slice{Base.OneTo{Int64}}}, false}\")"]` | 361.356 μs (50%) | 0.000 ns | 1.04 MiB (1%) | 499 |
| `["array", "index", "(\"sumcolon\", \"SubArray{Float32, 2, Matrix{Float32}, Tuple{Base.Slice{Base.OneTo{Int64}}, Base.Slice{Base.OneTo{Int64}}}, true}\")"]` | 300.475 μs (50%) | 0.000 ns | 1.04 MiB (1%) | 500 |
| `["array", "index", "(\"sumcolon\", \"SubArray{Float32, 2, Matrix{Float32}, Tuple{UnitRange{Int64}, UnitRange{Int64}}, false}\")"]` | 303.189 μs (50%) | 0.000 ns | 1.04 MiB (1%) | 500 |
| `["array", "index", "(\"sumcolon\", \"SubArray{Int32, 2, Array{Int32, 3}, Tuple{Int64, Base.Slice{Base.OneTo{Int64}}, Base.Slice{Base.OneTo{Int64}}}, true}\")"]` | 365.120 μs (50%) | 0.000 ns | 1.04 MiB (1%) | 500 |
| `["array", "index", "(\"sumcolon\", \"SubArray{Int32, 2, Base.ReshapedArray{Int32, 2, SubArray{Int32, 3, Array{Int32, 3}, Tuple{Base.Slice{Base.OneTo{Int64}}, Base.Slice{Base.OneTo{Int64}}, Base.Slice{Base.OneTo{Int64}}}, true}, Tuple{}}, Tuple{Base.Slice{Base.OneTo{Int64}}, UnitRange{Int64}}, true}\")"]` | 14.928 μs (50%) | 0.000 ns | 46.88 KiB (1%) | 500 |
| `["array", "index", "(\"sumcolon\", \"SubArray{Int32, 2, Base.ReshapedArray{Int32, 2, SubArray{Int32, 3, BaseBenchmarks.ArrayBenchmarks.ArrayLS{Int32, 3}, Tuple{Base.Slice{Base.OneTo{Int64}}, Base.Slice{Base.OneTo{Int64}}, Base.Slice{Base.OneTo{Int64}}}, false}, Tuple{Base.MultiplicativeInverses.SignedMultiplicativeInverse{Int64}, Base.MultiplicativeInverses.SignedMultiplicativeInverse{Int64}}}, Tuple{Base.Slice{Base.OneTo{Int64}}, UnitRange{Int64}}, false}\")"]` | 22.608 μs (50%) | 0.000 ns | 46.88 KiB (1%) | 500 |
| `["array", "index", "(\"sumcolon\", \"SubArray{Int32, 2, BaseBenchmarks.ArrayBenchmarks.ArrayLS{Int32, 2}, Tuple{Base.Slice{Base.OneTo{Int64}}, Base.Slice{Base.OneTo{Int64}}}, false}\")"]` | 302.284 μs (50%) | 0.000 ns | 1.04 MiB (1%) | 500 |
| `["array", "index", "(\"sumcolon\", \"SubArray{Int32, 2, BaseBenchmarks.ArrayBenchmarks.ArrayLS{Int32, 3}, Tuple{Int64, Base.Slice{Base.OneTo{Int64}}, Base.Slice{Base.OneTo{Int64}}}, false}\")"]` | 361.030 μs (50%) | 0.000 ns | 1.04 MiB (1%) | 499 |
| `["array", "index", "(\"sumcolon\", \"SubArray{Int32, 2, Matrix{Int32}, Tuple{Base.Slice{Base.OneTo{Int64}}, Base.Slice{Base.OneTo{Int64}}}, true}\")"]` | 302.865 μs (50%) | 0.000 ns | 1.04 MiB (1%) | 500 |
| `["array", "index", "(\"sumcolon\", \"SubArray{Int32, 2, Matrix{Int32}, Tuple{UnitRange{Int64}, UnitRange{Int64}}, false}\")"]` | 304.161 μs (50%) | 0.000 ns | 1.04 MiB (1%) | 500 |
| `["array", "index", "(\"sumcolon_view\", \"1.0:0.00010001000100010001:2.0\")"]` | 36.000 ns (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumcolon_view\", \"1.0:1.0:100000.0\")"]` | 36.000 ns (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumcolon_view\", \"100000:-1:1\")"]` | 58.000 ns (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumcolon_view\", \"1:100000\")"]` | 36.000 ns (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumcolon_view\", \"Base.ReinterpretArray{BaseBenchmarks.ArrayBenchmarks.PairVals{Float32}, 2, Float32, Matrix{Float32}, false}\")"]` | 2.703 μs (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumcolon_view\", \"Base.ReinterpretArray{BaseBenchmarks.ArrayBenchmarks.PairVals{Float32}, 2, Float64, Matrix{Float64}, false}\")"]` | 2.528 μs (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumcolon_view\", \"Base.ReinterpretArray{BaseBenchmarks.ArrayBenchmarks.PairVals{Int32}, 2, Int32, Matrix{Int32}, false}\")"]` | 1.820 μs (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumcolon_view\", \"Base.ReinterpretArray{BaseBenchmarks.ArrayBenchmarks.PairVals{Int32}, 2, Int64, Matrix{Int64}, false}\")"]` | 1.872 μs (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumcolon_view\", \"Base.ReinterpretArray{Float32, 2, Int32, Matrix{Int32}, false}\")"]` | 624.000 ns (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumcolon_view\", \"BaseBenchmarks.ArrayBenchmarks.ArrayLF{Float32, 2}\")"]` | 628.000 ns (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumcolon_view\", \"BaseBenchmarks.ArrayBenchmarks.ArrayLF{Int32, 2}\")"]` | 240.000 ns (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumcolon_view\", \"BaseBenchmarks.ArrayBenchmarks.ArrayLSLS{Float32, 2}\")"]` | 628.000 ns (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumcolon_view\", \"BaseBenchmarks.ArrayBenchmarks.ArrayLSLS{Int32, 2}\")"]` | 245.000 ns (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumcolon_view\", \"BaseBenchmarks.ArrayBenchmarks.ArrayLS{Float32, 2}\")"]` | 624.000 ns (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumcolon_view\", \"BaseBenchmarks.ArrayBenchmarks.ArrayLS{Int32, 2}\")"]` | 245.000 ns (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumcolon_view\", \"BitMatrix\")"]` | 716.000 ns (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumcolon_view\", \"Matrix{Float32}\")"]` | 621.000 ns (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumcolon_view\", \"Matrix{Float64}\")"]` | 621.000 ns (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumcolon_view\", \"Matrix{Int32}\")"]` | 235.000 ns (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumcolon_view\", \"Matrix{Int64}\")"]` | 232.000 ns (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumcolon_view\", \"SubArray{Float32, 2, Array{Float32, 3}, Tuple{Int64, Base.Slice{Base.OneTo{Int64}}, Base.Slice{Base.OneTo{Int64}}}, true}\")"]` | 629.000 ns (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumcolon_view\", \"SubArray{Float32, 2, Base.ReshapedArray{Float32, 2, SubArray{Float32, 3, Array{Float32, 3}, Tuple{Base.Slice{Base.OneTo{Int64}}, Base.Slice{Base.OneTo{Int64}}, Base.Slice{Base.OneTo{Int64}}}, true}, Tuple{}}, Tuple{Base.Slice{Base.OneTo{Int64}}, UnitRange{Int64}}, true}\")"]` | 614.000 ns (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumcolon_view\", \"SubArray{Float32, 2, Base.ReshapedArray{Float32, 2, SubArray{Float32, 3, BaseBenchmarks.ArrayBenchmarks.ArrayLS{Float32, 3}, Tuple{Base.Slice{Base.OneTo{Int64}}, Base.Slice{Base.OneTo{Int64}}, Base.Slice{Base.OneTo{Int64}}}, false}, Tuple{Base.MultiplicativeInverses.SignedMultiplicativeInverse{Int64}, Base.MultiplicativeInverses.SignedMultiplicativeInverse{Int64}}}, Tuple{Base.Slice{Base.OneTo{Int64}}, UnitRange{Int64}}, false}\")"]` | 7.239 μs (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumcolon_view\", \"SubArray{Float32, 2, BaseBenchmarks.ArrayBenchmarks.ArrayLS{Float32, 2}, Tuple{Base.Slice{Base.OneTo{Int64}}, Base.Slice{Base.OneTo{Int64}}}, false}\")"]` | 628.000 ns (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumcolon_view\", \"SubArray{Float32, 2, BaseBenchmarks.ArrayBenchmarks.ArrayLS{Float32, 3}, Tuple{Int64, Base.Slice{Base.OneTo{Int64}}, Base.Slice{Base.OneTo{Int64}}}, false}\")"]` | 627.000 ns (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumcolon_view\", \"SubArray{Float32, 2, Matrix{Float32}, Tuple{Base.Slice{Base.OneTo{Int64}}, Base.Slice{Base.OneTo{Int64}}}, true}\")"]` | 629.000 ns (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumcolon_view\", \"SubArray{Float32, 2, Matrix{Float32}, Tuple{UnitRange{Int64}, UnitRange{Int64}}, false}\")"]` | 626.000 ns (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumcolon_view\", \"SubArray{Int32, 2, Array{Int32, 3}, Tuple{Int64, Base.Slice{Base.OneTo{Int64}}, Base.Slice{Base.OneTo{Int64}}}, true}\")"]` | 275.000 ns (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumcolon_view\", \"SubArray{Int32, 2, Base.ReshapedArray{Int32, 2, SubArray{Int32, 3, Array{Int32, 3}, Tuple{Base.Slice{Base.OneTo{Int64}}, Base.Slice{Base.OneTo{Int64}}, Base.Slice{Base.OneTo{Int64}}}, true}, Tuple{}}, Tuple{Base.Slice{Base.OneTo{Int64}}, UnitRange{Int64}}, true}\")"]` | 160.000 ns (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumcolon_view\", \"SubArray{Int32, 2, Base.ReshapedArray{Int32, 2, SubArray{Int32, 3, BaseBenchmarks.ArrayBenchmarks.ArrayLS{Int32, 3}, Tuple{Base.Slice{Base.OneTo{Int64}}, Base.Slice{Base.OneTo{Int64}}, Base.Slice{Base.OneTo{Int64}}}, false}, Tuple{Base.MultiplicativeInverses.SignedMultiplicativeInverse{Int64}, Base.MultiplicativeInverses.SignedMultiplicativeInverse{Int64}}}, Tuple{Base.Slice{Base.OneTo{Int64}}, UnitRange{Int64}}, false}\")"]` | 7.090 μs (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumcolon_view\", \"SubArray{Int32, 2, BaseBenchmarks.ArrayBenchmarks.ArrayLS{Int32, 2}, Tuple{Base.Slice{Base.OneTo{Int64}}, Base.Slice{Base.OneTo{Int64}}}, false}\")"]` | 249.000 ns (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumcolon_view\", \"SubArray{Int32, 2, BaseBenchmarks.ArrayBenchmarks.ArrayLS{Int32, 3}, Tuple{Int64, Base.Slice{Base.OneTo{Int64}}, Base.Slice{Base.OneTo{Int64}}}, false}\")"]` | 268.000 ns (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumcolon_view\", \"SubArray{Int32, 2, Matrix{Int32}, Tuple{Base.Slice{Base.OneTo{Int64}}, Base.Slice{Base.OneTo{Int64}}}, true}\")"]` | 243.000 ns (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumcolon_view\", \"SubArray{Int32, 2, Matrix{Int32}, Tuple{UnitRange{Int64}, UnitRange{Int64}}, false}\")"]` | 241.000 ns (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumeach\", \"1.0:0.00010001000100010001:2.0\")"]` | 22.372 μs (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumeach\", \"1.0:1.0:100000.0\")"]` | 223.714 μs (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumeach\", \"100000:-1:1\")"]` | 36.000 ns (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumeach\", \"1:100000\")"]` | 26.000 ns (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumeach\", \"Array{Float64, 3}\")"]` | 1.586 μs (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumeach\", \"Base.ReinterpretArray{BaseBenchmarks.ArrayBenchmarks.PairVals{Float32}, 2, Float32, Matrix{Float32}, false}\")"]` | 147.163 μs (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumeach\", \"Base.ReinterpretArray{BaseBenchmarks.ArrayBenchmarks.PairVals{Float32}, 2, Float64, Matrix{Float64}, false}\")"]` | 294.279 μs (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumeach\", \"Base.ReinterpretArray{BaseBenchmarks.ArrayBenchmarks.PairVals{Int32}, 2, Int32, Matrix{Int32}, false}\")"]` | 51.637 μs (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumeach\", \"Base.ReinterpretArray{BaseBenchmarks.ArrayBenchmarks.PairVals{Int32}, 2, Int64, Matrix{Int64}, false}\")"]` | 222.802 μs (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumeach\", \"Base.ReinterpretArray{Float32, 2, Int32, Matrix{Int32}, false}\")"]` | 294.161 μs (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumeach\", \"Base.ReinterpretArray{Int32, 3, Float64, Array{Float64, 3}, false}\")"]` | 2.201 μs (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumeach\", \"BaseBenchmarks.ArrayBenchmarks.ArrayLF{Float32, 2}\")"]` | 294.184 μs (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumeach\", \"BaseBenchmarks.ArrayBenchmarks.ArrayLF{Int32, 2}\")"]` | 18.150 μs (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumeach\", \"BaseBenchmarks.ArrayBenchmarks.ArrayLSLS{Float32, 2}\")"]` | 294.174 μs (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumeach\", \"BaseBenchmarks.ArrayBenchmarks.ArrayLSLS{Int32, 2}\")"]` | 17.942 μs (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumeach\", \"BaseBenchmarks.ArrayBenchmarks.ArrayLS{Float32, 2}\")"]` | 294.175 μs (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumeach\", \"BaseBenchmarks.ArrayBenchmarks.ArrayLS{Int32, 2}\")"]` | 17.878 μs (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumeach\", \"BitMatrix\")"]` | 349.318 μs (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumeach\", \"Matrix{Float32}\")"]` | 294.183 μs (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumeach\", \"Matrix{Float64}\")"]` | 294.214 μs (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumeach\", \"Matrix{Int32}\")"]` | 18.120 μs (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumeach\", \"Matrix{Int64}\")"]` | 70.977 μs (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumeach\", \"SubArray{Float32, 2, Array{Float32, 3}, Tuple{Int64, Base.Slice{Base.OneTo{Int64}}, Base.Slice{Base.OneTo{Int64}}}, true}\")"]` | 294.230 μs (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumeach\", \"SubArray{Float32, 2, Base.ReshapedArray{Float32, 2, SubArray{Float32, 3, Array{Float32, 3}, Tuple{Base.Slice{Base.OneTo{Int64}}, Base.Slice{Base.OneTo{Int64}}, Base.Slice{Base.OneTo{Int64}}}, true}, Tuple{}}, Tuple{Base.Slice{Base.OneTo{Int64}}, UnitRange{Int64}}, true}\")"]` | 2.377 μs (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumeach\", \"SubArray{Float32, 2, Base.ReshapedArray{Float32, 2, SubArray{Float32, 3, BaseBenchmarks.ArrayBenchmarks.ArrayLS{Float32, 3}, Tuple{Base.Slice{Base.OneTo{Int64}}, Base.Slice{Base.OneTo{Int64}}, Base.Slice{Base.OneTo{Int64}}}, false}, Tuple{Base.MultiplicativeInverses.SignedMultiplicativeInverse{Int64}, Base.MultiplicativeInverses.SignedMultiplicativeInverse{Int64}}}, Tuple{Base.Slice{Base.OneTo{Int64}}, UnitRange{Int64}}, false}\")"]` | 8.363 μs (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumeach\", \"SubArray{Float32, 2, BaseBenchmarks.ArrayBenchmarks.ArrayLS{Float32, 2}, Tuple{Base.Slice{Base.OneTo{Int64}}, Base.Slice{Base.OneTo{Int64}}}, false}\")"]` | 294.193 μs (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumeach\", \"SubArray{Float32, 2, BaseBenchmarks.ArrayBenchmarks.ArrayLS{Float32, 3}, Tuple{Int64, Base.Slice{Base.OneTo{Int64}}, Base.Slice{Base.OneTo{Int64}}}, false}\")"]` | 293.105 μs (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumeach\", \"SubArray{Float32, 2, Matrix{Float32}, Tuple{Base.Slice{Base.OneTo{Int64}}, Base.Slice{Base.OneTo{Int64}}}, true}\")"]` | 294.204 μs (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumeach\", \"SubArray{Float32, 2, Matrix{Float32}, Tuple{UnitRange{Int64}, UnitRange{Int64}}, false}\")"]` | 297.414 μs (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumeach\", \"SubArray{Float64, 3, Array{Float64, 3}, Tuple{UnitRange{Int64}, UnitRange{Int64}, UnitRange{Int64}}, false}\")"]` | 1.282 μs (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumeach\", \"SubArray{Int32, 2, Array{Int32, 3}, Tuple{Int64, Base.Slice{Base.OneTo{Int64}}, Base.Slice{Base.OneTo{Int64}}}, true}\")"]` | 143.868 μs (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumeach\", \"SubArray{Int32, 2, Base.ReshapedArray{Int32, 2, SubArray{Int32, 3, Array{Int32, 3}, Tuple{Base.Slice{Base.OneTo{Int64}}, Base.Slice{Base.OneTo{Int64}}, Base.Slice{Base.OneTo{Int64}}}, true}, Tuple{}}, Tuple{Base.Slice{Base.OneTo{Int64}}, UnitRange{Int64}}, true}\")"]` | 106.000 ns (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumeach\", \"SubArray{Int32, 2, Base.ReshapedArray{Int32, 2, SubArray{Int32, 3, BaseBenchmarks.ArrayBenchmarks.ArrayLS{Int32, 3}, Tuple{Base.Slice{Base.OneTo{Int64}}, Base.Slice{Base.OneTo{Int64}}, Base.Slice{Base.OneTo{Int64}}}, false}, Tuple{Base.MultiplicativeInverses.SignedMultiplicativeInverse{Int64}, Base.MultiplicativeInverses.SignedMultiplicativeInverse{Int64}}}, Tuple{Base.Slice{Base.OneTo{Int64}}, UnitRange{Int64}}, false}\")"]` | 7.974 μs (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumeach\", \"SubArray{Int32, 2, BaseBenchmarks.ArrayBenchmarks.ArrayLS{Int32, 2}, Tuple{Base.Slice{Base.OneTo{Int64}}, Base.Slice{Base.OneTo{Int64}}}, false}\")"]` | 151.725 μs (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumeach\", \"SubArray{Int32, 2, BaseBenchmarks.ArrayBenchmarks.ArrayLS{Int32, 3}, Tuple{Int64, Base.Slice{Base.OneTo{Int64}}, Base.Slice{Base.OneTo{Int64}}}, false}\")"]` | 162.062 μs (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumeach\", \"SubArray{Int32, 2, Matrix{Int32}, Tuple{Base.Slice{Base.OneTo{Int64}}, Base.Slice{Base.OneTo{Int64}}}, true}\")"]` | 18.196 μs (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumeach\", \"SubArray{Int32, 2, Matrix{Int32}, Tuple{UnitRange{Int64}, UnitRange{Int64}}, false}\")"]` | 158.995 μs (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumeach_view\", \"1.0:0.00010001000100010001:2.0\")"]` | 22.374 μs (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumeach_view\", \"1.0:1.0:100000.0\")"]` | 218.948 μs (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumeach_view\", \"100000:-1:1\")"]` | 1.853 ms (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumeach_view\", \"1:100000\")"]` | 8.177 μs (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumeach_view\", \"Array{Float64, 3}\")"]` | 47.159 μs (50%) | 0.000 ns | 103.98 KiB (1%) | 2662 |
| `["array", "index", "(\"sumeach_view\", \"Base.ReinterpretArray{BaseBenchmarks.ArrayBenchmarks.PairVals{Float32}, 2, Float32, Matrix{Float32}, false}\")"]` | 518.590 μs (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumeach_view\", \"Base.ReinterpretArray{BaseBenchmarks.ArrayBenchmarks.PairVals{Float32}, 2, Float64, Matrix{Float64}, false}\")"]` | 984.534 μs (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumeach_view\", \"Base.ReinterpretArray{BaseBenchmarks.ArrayBenchmarks.PairVals{Int32}, 2, Int32, Matrix{Int32}, false}\")"]` | 455.550 μs (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumeach_view\", \"Base.ReinterpretArray{BaseBenchmarks.ArrayBenchmarks.PairVals{Int32}, 2, Int64, Matrix{Int64}, false}\")"]` | 1.007 ms (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumeach_view\", \"Base.ReinterpretArray{Float32, 2, Int32, Matrix{Int32}, false}\")"]` | 884.671 μs (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumeach_view\", \"Base.ReinterpretArray{Int32, 3, Float64, Array{Float64, 3}, false}\")"]` | 9.852 μs (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumeach_view\", \"BaseBenchmarks.ArrayBenchmarks.ArrayLF{Float32, 2}\")"]` | 16.821 μs (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumeach_view\", \"BaseBenchmarks.ArrayBenchmarks.ArrayLF{Int32, 2}\")"]` | 18.120 μs (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumeach_view\", \"BaseBenchmarks.ArrayBenchmarks.ArrayLSLS{Float32, 2}\")"]` | 27.003 μs (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumeach_view\", \"BaseBenchmarks.ArrayBenchmarks.ArrayLSLS{Int32, 2}\")"]` | 17.854 μs (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumeach_view\", \"BaseBenchmarks.ArrayBenchmarks.ArrayLS{Float32, 2}\")"]` | 26.989 μs (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumeach_view\", \"BaseBenchmarks.ArrayBenchmarks.ArrayLS{Int32, 2}\")"]` | 17.851 μs (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumeach_view\", \"BitMatrix\")"]` | 7.920 ms (50%) | 0.000 ns | 19.07 MiB (1%) | 250000 |
| `["array", "index", "(\"sumeach_view\", \"Matrix{Float32}\")"]` | 9.086 ms (50%) | 0.000 ns | 19.07 MiB (1%) | 500000 |
| `["array", "index", "(\"sumeach_view\", \"Matrix{Float64}\")"]` | 8.957 ms (50%) | 0.000 ns | 19.07 MiB (1%) | 500000 |
| `["array", "index", "(\"sumeach_view\", \"Matrix{Int32}\")"]` | 8.825 ms (50%) | 0.000 ns | 19.07 MiB (1%) | 500000 |
| `["array", "index", "(\"sumeach_view\", \"Matrix{Int64}\")"]` | 8.844 ms (50%) | 0.000 ns | 19.07 MiB (1%) | 500000 |
| `["array", "index", "(\"sumeach_view\", \"SubArray{Float32, 2, Array{Float32, 3}, Tuple{Int64, Base.Slice{Base.OneTo{Int64}}, Base.Slice{Base.OneTo{Int64}}}, true}\")"]` | 294.225 μs (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumeach_view\", \"SubArray{Float32, 2, Base.ReshapedArray{Float32, 2, SubArray{Float32, 3, Array{Float32, 3}, Tuple{Base.Slice{Base.OneTo{Int64}}, Base.Slice{Base.OneTo{Int64}}, Base.Slice{Base.OneTo{Int64}}}, true}, Tuple{}}, Tuple{Base.Slice{Base.OneTo{Int64}}, UnitRange{Int64}}, true}\")"]` | 132.000 ns (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumeach_view\", \"SubArray{Float32, 2, Base.ReshapedArray{Float32, 2, SubArray{Float32, 3, BaseBenchmarks.ArrayBenchmarks.ArrayLS{Float32, 3}, Tuple{Base.Slice{Base.OneTo{Int64}}, Base.Slice{Base.OneTo{Int64}}, Base.Slice{Base.OneTo{Int64}}}, false}, Tuple{Base.MultiplicativeInverses.SignedMultiplicativeInverse{Int64}, Base.MultiplicativeInverses.SignedMultiplicativeInverse{Int64}}}, Tuple{Base.Slice{Base.OneTo{Int64}}, UnitRange{Int64}}, false}\")"]` | 7.878 μs (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumeach_view\", \"SubArray{Float32, 2, BaseBenchmarks.ArrayBenchmarks.ArrayLS{Float32, 2}, Tuple{Base.Slice{Base.OneTo{Int64}}, Base.Slice{Base.OneTo{Int64}}}, false}\")"]` | 26.986 μs (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumeach_view\", \"SubArray{Float32, 2, BaseBenchmarks.ArrayBenchmarks.ArrayLS{Float32, 3}, Tuple{Int64, Base.Slice{Base.OneTo{Int64}}, Base.Slice{Base.OneTo{Int64}}}, false}\")"]` | 293.050 μs (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumeach_view\", \"SubArray{Float32, 2, Matrix{Float32}, Tuple{Base.Slice{Base.OneTo{Int64}}, Base.Slice{Base.OneTo{Int64}}}, true}\")"]` | 16.860 μs (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumeach_view\", \"SubArray{Float32, 2, Matrix{Float32}, Tuple{UnitRange{Int64}, UnitRange{Int64}}, false}\")"]` | 26.467 μs (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumeach_view\", \"SubArray{Float64, 3, Array{Float64, 3}, Tuple{UnitRange{Int64}, UnitRange{Int64}, UnitRange{Int64}}, false}\")"]` | 1.206 μs (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumeach_view\", \"SubArray{Int32, 2, Array{Int32, 3}, Tuple{Int64, Base.Slice{Base.OneTo{Int64}}, Base.Slice{Base.OneTo{Int64}}}, true}\")"]` | 147.695 μs (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumeach_view\", \"SubArray{Int32, 2, Base.ReshapedArray{Int32, 2, SubArray{Int32, 3, Array{Int32, 3}, Tuple{Base.Slice{Base.OneTo{Int64}}, Base.Slice{Base.OneTo{Int64}}, Base.Slice{Base.OneTo{Int64}}}, true}, Tuple{}}, Tuple{Base.Slice{Base.OneTo{Int64}}, UnitRange{Int64}}, true}\")"]` | 106.000 ns (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumeach_view\", \"SubArray{Int32, 2, Base.ReshapedArray{Int32, 2, SubArray{Int32, 3, BaseBenchmarks.ArrayBenchmarks.ArrayLS{Int32, 3}, Tuple{Base.Slice{Base.OneTo{Int64}}, Base.Slice{Base.OneTo{Int64}}, Base.Slice{Base.OneTo{Int64}}}, false}, Tuple{Base.MultiplicativeInverses.SignedMultiplicativeInverse{Int64}, Base.MultiplicativeInverses.SignedMultiplicativeInverse{Int64}}}, Tuple{Base.Slice{Base.OneTo{Int64}}, UnitRange{Int64}}, false}\")"]` | 7.361 μs (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumeach_view\", \"SubArray{Int32, 2, BaseBenchmarks.ArrayBenchmarks.ArrayLS{Int32, 2}, Tuple{Base.Slice{Base.OneTo{Int64}}, Base.Slice{Base.OneTo{Int64}}}, false}\")"]` | 17.822 μs (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumeach_view\", \"SubArray{Int32, 2, BaseBenchmarks.ArrayBenchmarks.ArrayLS{Int32, 3}, Tuple{Int64, Base.Slice{Base.OneTo{Int64}}, Base.Slice{Base.OneTo{Int64}}}, false}\")"]` | 146.310 μs (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumeach_view\", \"SubArray{Int32, 2, Matrix{Int32}, Tuple{Base.Slice{Base.OneTo{Int64}}, Base.Slice{Base.OneTo{Int64}}}, true}\")"]` | 18.210 μs (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumeach_view\", \"SubArray{Int32, 2, Matrix{Int32}, Tuple{UnitRange{Int64}, UnitRange{Int64}}, false}\")"]` | 15.895 μs (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumelt\", \"1.0:0.00010001000100010001:2.0\")"]` | 23.437 μs (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumelt\", \"1.0:1.0:100000.0\")"]` | 228.062 μs (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumelt\", \"100000:-1:1\")"]` | 29.452 μs (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumelt\", \"1:100000\")"]` | 24.000 ns (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumelt\", \"Array{Float64, 3}\")"]` | 1.586 μs (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumelt\", \"Base.ReinterpretArray{BaseBenchmarks.ArrayBenchmarks.PairVals{Float32}, 2, Float32, Matrix{Float32}, false}\")"]` | 220.738 μs (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumelt\", \"Base.ReinterpretArray{BaseBenchmarks.ArrayBenchmarks.PairVals{Float32}, 2, Float64, Matrix{Float64}, false}\")"]` | 294.490 μs (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumelt\", \"Base.ReinterpretArray{BaseBenchmarks.ArrayBenchmarks.PairVals{Int32}, 2, Int32, Matrix{Int32}, false}\")"]` | 202.378 μs (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumelt\", \"Base.ReinterpretArray{BaseBenchmarks.ArrayBenchmarks.PairVals{Int32}, 2, Int64, Matrix{Int64}, false}\")"]` | 295.859 μs (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumelt\", \"Base.ReinterpretArray{Float32, 2, Int32, Matrix{Int32}, false}\")"]` | 294.169 μs (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumelt\", \"Base.ReinterpretArray{Int32, 3, Float64, Array{Float64, 3}, false}\")"]` | 5.511 μs (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumelt\", \"BaseBenchmarks.ArrayBenchmarks.ArrayLF{Float32, 2}\")"]` | 294.205 μs (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumelt\", \"BaseBenchmarks.ArrayBenchmarks.ArrayLF{Int32, 2}\")"]` | 147.146 μs (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumelt\", \"BaseBenchmarks.ArrayBenchmarks.ArrayLSLS{Float32, 2}\")"]` | 443.791 μs (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumelt\", \"BaseBenchmarks.ArrayBenchmarks.ArrayLSLS{Int32, 2}\")"]` | 517.455 μs (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumelt\", \"BaseBenchmarks.ArrayBenchmarks.ArrayLS{Float32, 2}\")"]` | 443.769 μs (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumelt\", \"BaseBenchmarks.ArrayBenchmarks.ArrayLS{Int32, 2}\")"]` | 279.165 μs (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumelt\", \"BitMatrix\")"]` | 349.361 μs (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumelt\", \"Matrix{Float32}\")"]` | 294.183 μs (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumelt\", \"Matrix{Float64}\")"]` | 294.187 μs (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumelt\", \"Matrix{Int32}\")"]` | 18.256 μs (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumelt\", \"Matrix{Int64}\")"]` | 71.174 μs (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumelt\", \"SubArray{Float32, 2, Array{Float32, 3}, Tuple{Int64, Base.Slice{Base.OneTo{Int64}}, Base.Slice{Base.OneTo{Int64}}}, true}\")"]` | 294.319 μs (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumelt\", \"SubArray{Float32, 2, Base.ReshapedArray{Float32, 2, SubArray{Float32, 3, Array{Float32, 3}, Tuple{Base.Slice{Base.OneTo{Int64}}, Base.Slice{Base.OneTo{Int64}}, Base.Slice{Base.OneTo{Int64}}}, true}, Tuple{}}, Tuple{Base.Slice{Base.OneTo{Int64}}, UnitRange{Int64}}, true}\")"]` | 2.376 μs (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumelt\", \"SubArray{Float32, 2, Base.ReshapedArray{Float32, 2, SubArray{Float32, 3, BaseBenchmarks.ArrayBenchmarks.ArrayLS{Float32, 3}, Tuple{Base.Slice{Base.OneTo{Int64}}, Base.Slice{Base.OneTo{Int64}}, Base.Slice{Base.OneTo{Int64}}}, false}, Tuple{Base.MultiplicativeInverses.SignedMultiplicativeInverse{Int64}, Base.MultiplicativeInverses.SignedMultiplicativeInverse{Int64}}}, Tuple{Base.Slice{Base.OneTo{Int64}}, UnitRange{Int64}}, false}\")"]` | 7.543 μs (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumelt\", \"SubArray{Float32, 2, BaseBenchmarks.ArrayBenchmarks.ArrayLS{Float32, 2}, Tuple{Base.Slice{Base.OneTo{Int64}}, Base.Slice{Base.OneTo{Int64}}}, false}\")"]` | 444.181 μs (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumelt\", \"SubArray{Float32, 2, BaseBenchmarks.ArrayBenchmarks.ArrayLS{Float32, 3}, Tuple{Int64, Base.Slice{Base.OneTo{Int64}}, Base.Slice{Base.OneTo{Int64}}}, false}\")"]` | 589.204 μs (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumelt\", \"SubArray{Float32, 2, Matrix{Float32}, Tuple{Base.Slice{Base.OneTo{Int64}}, Base.Slice{Base.OneTo{Int64}}}, true}\")"]` | 294.239 μs (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumelt\", \"SubArray{Float32, 2, Matrix{Float32}, Tuple{UnitRange{Int64}, UnitRange{Int64}}, false}\")"]` | 591.381 μs (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumelt\", \"SubArray{Float64, 3, Array{Float64, 3}, Tuple{UnitRange{Int64}, UnitRange{Int64}, UnitRange{Int64}}, false}\")"]` | 2.824 μs (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumelt\", \"SubArray{Int32, 2, Array{Int32, 3}, Tuple{Int64, Base.Slice{Base.OneTo{Int64}}, Base.Slice{Base.OneTo{Int64}}}, true}\")"]` | 172.511 μs (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumelt\", \"SubArray{Int32, 2, Base.ReshapedArray{Int32, 2, SubArray{Int32, 3, Array{Int32, 3}, Tuple{Base.Slice{Base.OneTo{Int64}}, Base.Slice{Base.OneTo{Int64}}, Base.Slice{Base.OneTo{Int64}}}, true}, Tuple{}}, Tuple{Base.Slice{Base.OneTo{Int64}}, UnitRange{Int64}}, true}\")"]` | 1.391 μs (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumelt\", \"SubArray{Int32, 2, Base.ReshapedArray{Int32, 2, SubArray{Int32, 3, BaseBenchmarks.ArrayBenchmarks.ArrayLS{Int32, 3}, Tuple{Base.Slice{Base.OneTo{Int64}}, Base.Slice{Base.OneTo{Int64}}, Base.Slice{Base.OneTo{Int64}}}, false}, Tuple{Base.MultiplicativeInverses.SignedMultiplicativeInverse{Int64}, Base.MultiplicativeInverses.SignedMultiplicativeInverse{Int64}}}, Tuple{Base.Slice{Base.OneTo{Int64}}, UnitRange{Int64}}, false}\")"]` | 7.250 μs (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumelt\", \"SubArray{Int32, 2, BaseBenchmarks.ArrayBenchmarks.ArrayLS{Int32, 2}, Tuple{Base.Slice{Base.OneTo{Int64}}, Base.Slice{Base.OneTo{Int64}}}, false}\")"]` | 371.992 μs (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumelt\", \"SubArray{Int32, 2, BaseBenchmarks.ArrayBenchmarks.ArrayLS{Int32, 3}, Tuple{Int64, Base.Slice{Base.OneTo{Int64}}, Base.Slice{Base.OneTo{Int64}}}, false}\")"]` | 443.126 μs (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumelt\", \"SubArray{Int32, 2, Matrix{Int32}, Tuple{Base.Slice{Base.OneTo{Int64}}, Base.Slice{Base.OneTo{Int64}}}, true}\")"]` | 173.031 μs (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumelt\", \"SubArray{Int32, 2, Matrix{Int32}, Tuple{UnitRange{Int64}, UnitRange{Int64}}, false}\")"]` | 591.384 μs (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumelt_boundscheck\", \"1.0:0.00010001000100010001:2.0\")"]` | 24.598 μs (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumelt_boundscheck\", \"1.0:1.0:100000.0\")"]` | 245.854 μs (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumelt_boundscheck\", \"100000:-1:1\")"]` | 58.873 μs (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumelt_boundscheck\", \"1:100000\")"]` | 88.274 μs (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumelt_boundscheck\", \"Array{Float64, 3}\")"]` | 1.586 μs (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumelt_boundscheck\", \"Base.ReinterpretArray{BaseBenchmarks.ArrayBenchmarks.PairVals{Float32}, 2, Float32, Matrix{Float32}, false}\")"]` | 257.478 μs (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumelt_boundscheck\", \"Base.ReinterpretArray{BaseBenchmarks.ArrayBenchmarks.PairVals{Float32}, 2, Float64, Matrix{Float64}, false}\")"]` | 294.360 μs (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumelt_boundscheck\", \"Base.ReinterpretArray{BaseBenchmarks.ArrayBenchmarks.PairVals{Int32}, 2, Int32, Matrix{Int32}, false}\")"]` | 184.098 μs (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumelt_boundscheck\", \"Base.ReinterpretArray{BaseBenchmarks.ArrayBenchmarks.PairVals{Int32}, 2, Int64, Matrix{Int64}, false}\")"]` | 441.335 μs (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumelt_boundscheck\", \"Base.ReinterpretArray{Float32, 2, Int32, Matrix{Int32}, false}\")"]` | 294.206 μs (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumelt_boundscheck\", \"Base.ReinterpretArray{Int32, 3, Float64, Array{Float64, 3}, false}\")"]` | 3.561 μs (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumelt_boundscheck\", \"BaseBenchmarks.ArrayBenchmarks.ArrayLF{Float32, 2}\")"]` | 294.208 μs (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumelt_boundscheck\", \"BaseBenchmarks.ArrayBenchmarks.ArrayLF{Int32, 2}\")"]` | 81.294 μs (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumelt_boundscheck\", \"BaseBenchmarks.ArrayBenchmarks.ArrayLSLS{Float32, 2}\")"]` | 735.379 μs (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumelt_boundscheck\", \"BaseBenchmarks.ArrayBenchmarks.ArrayLSLS{Int32, 2}\")"]` | 808.877 μs (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumelt_boundscheck\", \"BaseBenchmarks.ArrayBenchmarks.ArrayLS{Float32, 2}\")"]` | 735.388 μs (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumelt_boundscheck\", \"BaseBenchmarks.ArrayBenchmarks.ArrayLS{Int32, 2}\")"]` | 735.388 μs (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumelt_boundscheck\", \"BitMatrix\")"]` | 386.100 μs (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumelt_boundscheck\", \"Matrix{Float32}\")"]` | 294.177 μs (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumelt_boundscheck\", \"Matrix{Float64}\")"]` | 294.188 μs (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumelt_boundscheck\", \"Matrix{Int32}\")"]` | 18.041 μs (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumelt_boundscheck\", \"Matrix{Int64}\")"]` | 71.319 μs (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumelt_boundscheck\", \"SubArray{Float32, 2, Array{Float32, 3}, Tuple{Int64, Base.Slice{Base.OneTo{Int64}}, Base.Slice{Base.OneTo{Int64}}}, true}\")"]` | 294.343 μs (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumelt_boundscheck\", \"SubArray{Float32, 2, Base.ReshapedArray{Float32, 2, SubArray{Float32, 3, Array{Float32, 3}, Tuple{Base.Slice{Base.OneTo{Int64}}, Base.Slice{Base.OneTo{Int64}}, Base.Slice{Base.OneTo{Int64}}}, true}, Tuple{}}, Tuple{Base.Slice{Base.OneTo{Int64}}, UnitRange{Int64}}, true}\")"]` | 2.376 μs (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumelt_boundscheck\", \"SubArray{Float32, 2, Base.ReshapedArray{Float32, 2, SubArray{Float32, 3, BaseBenchmarks.ArrayBenchmarks.ArrayLS{Float32, 3}, Tuple{Base.Slice{Base.OneTo{Int64}}, Base.Slice{Base.OneTo{Int64}}, Base.Slice{Base.OneTo{Int64}}}, false}, Tuple{Base.MultiplicativeInverses.SignedMultiplicativeInverse{Int64}, Base.MultiplicativeInverses.SignedMultiplicativeInverse{Int64}}}, Tuple{Base.Slice{Base.OneTo{Int64}}, UnitRange{Int64}}, false}\")"]` | 12.101 μs (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumelt_boundscheck\", \"SubArray{Float32, 2, BaseBenchmarks.ArrayBenchmarks.ArrayLS{Float32, 2}, Tuple{Base.Slice{Base.OneTo{Int64}}, Base.Slice{Base.OneTo{Int64}}}, false}\")"]` | 735.359 μs (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumelt_boundscheck\", \"SubArray{Float32, 2, BaseBenchmarks.ArrayBenchmarks.ArrayLS{Float32, 3}, Tuple{Int64, Base.Slice{Base.OneTo{Int64}}, Base.Slice{Base.OneTo{Int64}}}, false}\")"]` | 732.499 μs (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumelt_boundscheck\", \"SubArray{Float32, 2, Matrix{Float32}, Tuple{Base.Slice{Base.OneTo{Int64}}, Base.Slice{Base.OneTo{Int64}}}, true}\")"]` | 294.213 μs (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumelt_boundscheck\", \"SubArray{Float32, 2, Matrix{Float32}, Tuple{UnitRange{Int64}, UnitRange{Int64}}, false}\")"]` | 882.413 μs (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumelt_boundscheck\", \"SubArray{Float64, 3, Array{Float64, 3}, Tuple{UnitRange{Int64}, UnitRange{Int64}, UnitRange{Int64}}, false}\")"]` | 7.496 μs (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumelt_boundscheck\", \"SubArray{Int32, 2, Array{Int32, 3}, Tuple{Int64, Base.Slice{Base.OneTo{Int64}}, Base.Slice{Base.OneTo{Int64}}}, true}\")"]` | 173.390 μs (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumelt_boundscheck\", \"SubArray{Int32, 2, Base.ReshapedArray{Int32, 2, SubArray{Int32, 3, Array{Int32, 3}, Tuple{Base.Slice{Base.OneTo{Int64}}, Base.Slice{Base.OneTo{Int64}}, Base.Slice{Base.OneTo{Int64}}}, true}, Tuple{}}, Tuple{Base.Slice{Base.OneTo{Int64}}, UnitRange{Int64}}, true}\")"]` | 1.285 μs (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumelt_boundscheck\", \"SubArray{Int32, 2, Base.ReshapedArray{Int32, 2, SubArray{Int32, 3, BaseBenchmarks.ArrayBenchmarks.ArrayLS{Int32, 3}, Tuple{Base.Slice{Base.OneTo{Int64}}, Base.Slice{Base.OneTo{Int64}}, Base.Slice{Base.OneTo{Int64}}}, false}, Tuple{Base.MultiplicativeInverses.SignedMultiplicativeInverse{Int64}, Base.MultiplicativeInverses.SignedMultiplicativeInverse{Int64}}}, Tuple{Base.Slice{Base.OneTo{Int64}}, UnitRange{Int64}}, false}\")"]` | 12.346 μs (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumelt_boundscheck\", \"SubArray{Int32, 2, BaseBenchmarks.ArrayBenchmarks.ArrayLS{Int32, 2}, Tuple{Base.Slice{Base.OneTo{Int64}}, Base.Slice{Base.OneTo{Int64}}}, false}\")"]` | 735.365 μs (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumelt_boundscheck\", \"SubArray{Int32, 2, BaseBenchmarks.ArrayBenchmarks.ArrayLS{Int32, 3}, Tuple{Int64, Base.Slice{Base.OneTo{Int64}}, Base.Slice{Base.OneTo{Int64}}}, false}\")"]` | 732.472 μs (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumelt_boundscheck\", \"SubArray{Int32, 2, Matrix{Int32}, Tuple{Base.Slice{Base.OneTo{Int64}}, Base.Slice{Base.OneTo{Int64}}}, true}\")"]` | 153.925 μs (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumelt_boundscheck\", \"SubArray{Int32, 2, Matrix{Int32}, Tuple{UnitRange{Int64}, UnitRange{Int64}}, false}\")"]` | 882.409 μs (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumlinear\", \"1.0:0.00010001000100010001:2.0\")"]` | 22.380 μs (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumlinear\", \"1.0:1.0:100000.0\")"]` | 218.855 μs (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumlinear\", \"100000:-1:1\")"]` | 35.000 ns (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumlinear\", \"1:100000\")"]` | 26.000 ns (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumlinear\", \"Array{Float64, 3}\")"]` | 1.586 μs (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumlinear\", \"Base.ReinterpretArray{BaseBenchmarks.ArrayBenchmarks.PairVals{Float32}, 2, Float32, Matrix{Float32}, false}\")"]` | 147.162 μs (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumlinear\", \"Base.ReinterpretArray{BaseBenchmarks.ArrayBenchmarks.PairVals{Float32}, 2, Float64, Matrix{Float64}, false}\")"]` | 294.258 μs (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumlinear\", \"Base.ReinterpretArray{BaseBenchmarks.ArrayBenchmarks.PairVals{Int32}, 2, Int32, Matrix{Int32}, false}\")"]` | 51.653 μs (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumlinear\", \"Base.ReinterpretArray{BaseBenchmarks.ArrayBenchmarks.PairVals{Int32}, 2, Int64, Matrix{Int64}, false}\")"]` | 223.003 μs (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumlinear\", \"Base.ReinterpretArray{Float32, 2, Int32, Matrix{Int32}, false}\")"]` | 294.182 μs (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumlinear\", \"Base.ReinterpretArray{Int32, 3, Float64, Array{Float64, 3}, false}\")"]` | 2.200 μs (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumlinear\", \"BaseBenchmarks.ArrayBenchmarks.ArrayLF{Float32, 2}\")"]` | 294.188 μs (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumlinear\", \"BaseBenchmarks.ArrayBenchmarks.ArrayLF{Int32, 2}\")"]` | 18.192 μs (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumlinear\", \"BaseBenchmarks.ArrayBenchmarks.ArrayLSLS{Float32, 2}\")"]` | 661.867 μs (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumlinear\", \"BaseBenchmarks.ArrayBenchmarks.ArrayLSLS{Int32, 2}\")"]` | 661.869 μs (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumlinear\", \"BaseBenchmarks.ArrayBenchmarks.ArrayLS{Float32, 2}\")"]` | 661.857 μs (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumlinear\", \"BaseBenchmarks.ArrayBenchmarks.ArrayLS{Int32, 2}\")"]` | 661.853 μs (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumlinear\", \"BitMatrix\")"]` | 349.321 μs (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumlinear\", \"Matrix{Float32}\")"]` | 294.182 μs (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumlinear\", \"Matrix{Float64}\")"]` | 294.213 μs (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumlinear\", \"Matrix{Int32}\")"]` | 18.121 μs (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumlinear\", \"Matrix{Int64}\")"]` | 71.117 μs (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumlinear\", \"SubArray{Float32, 2, Array{Float32, 3}, Tuple{Int64, Base.Slice{Base.OneTo{Int64}}, Base.Slice{Base.OneTo{Int64}}}, true}\")"]` | 294.224 μs (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumlinear\", \"SubArray{Float32, 2, Base.ReshapedArray{Float32, 2, SubArray{Float32, 3, Array{Float32, 3}, Tuple{Base.Slice{Base.OneTo{Int64}}, Base.Slice{Base.OneTo{Int64}}, Base.Slice{Base.OneTo{Int64}}}, true}, Tuple{}}, Tuple{Base.Slice{Base.OneTo{Int64}}, UnitRange{Int64}}, true}\")"]` | 2.376 μs (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumlinear\", \"SubArray{Float32, 2, Base.ReshapedArray{Float32, 2, SubArray{Float32, 3, BaseBenchmarks.ArrayBenchmarks.ArrayLS{Float32, 3}, Tuple{Base.Slice{Base.OneTo{Int64}}, Base.Slice{Base.OneTo{Int64}}, Base.Slice{Base.OneTo{Int64}}}, false}, Tuple{Base.MultiplicativeInverses.SignedMultiplicativeInverse{Int64}, Base.MultiplicativeInverses.SignedMultiplicativeInverse{Int64}}}, Tuple{Base.Slice{Base.OneTo{Int64}}, UnitRange{Int64}}, false}\")"]` | 12.259 μs (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumlinear\", \"SubArray{Float32, 2, BaseBenchmarks.ArrayBenchmarks.ArrayLS{Float32, 2}, Tuple{Base.Slice{Base.OneTo{Int64}}, Base.Slice{Base.OneTo{Int64}}}, false}\")"]` | 735.369 μs (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumlinear\", \"SubArray{Float32, 2, BaseBenchmarks.ArrayBenchmarks.ArrayLS{Float32, 3}, Tuple{Int64, Base.Slice{Base.OneTo{Int64}}, Base.Slice{Base.OneTo{Int64}}}, false}\")"]` | 732.491 μs (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumlinear\", \"SubArray{Float32, 2, Matrix{Float32}, Tuple{Base.Slice{Base.OneTo{Int64}}, Base.Slice{Base.OneTo{Int64}}}, true}\")"]` | 294.210 μs (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumlinear\", \"SubArray{Float32, 2, Matrix{Float32}, Tuple{UnitRange{Int64}, UnitRange{Int64}}, false}\")"]` | 735.353 μs (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumlinear\", \"SubArray{Float64, 3, Array{Float64, 3}, Tuple{UnitRange{Int64}, UnitRange{Int64}, UnitRange{Int64}}, false}\")"]` | 7.284 μs (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumlinear\", \"SubArray{Int32, 2, Array{Int32, 3}, Tuple{Int64, Base.Slice{Base.OneTo{Int64}}, Base.Slice{Base.OneTo{Int64}}}, true}\")"]` | 147.876 μs (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumlinear\", \"SubArray{Int32, 2, Base.ReshapedArray{Int32, 2, SubArray{Int32, 3, Array{Int32, 3}, Tuple{Base.Slice{Base.OneTo{Int64}}, Base.Slice{Base.OneTo{Int64}}, Base.Slice{Base.OneTo{Int64}}}, true}, Tuple{}}, Tuple{Base.Slice{Base.OneTo{Int64}}, UnitRange{Int64}}, true}\")"]` | 106.000 ns (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumlinear\", \"SubArray{Int32, 2, Base.ReshapedArray{Int32, 2, SubArray{Int32, 3, BaseBenchmarks.ArrayBenchmarks.ArrayLS{Int32, 3}, Tuple{Base.Slice{Base.OneTo{Int64}}, Base.Slice{Base.OneTo{Int64}}, Base.Slice{Base.OneTo{Int64}}}, false}, Tuple{Base.MultiplicativeInverses.SignedMultiplicativeInverse{Int64}, Base.MultiplicativeInverses.SignedMultiplicativeInverse{Int64}}}, Tuple{Base.Slice{Base.OneTo{Int64}}, UnitRange{Int64}}, false}\")"]` | 24.091 μs (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumlinear\", \"SubArray{Int32, 2, BaseBenchmarks.ArrayBenchmarks.ArrayLS{Int32, 2}, Tuple{Base.Slice{Base.OneTo{Int64}}, Base.Slice{Base.OneTo{Int64}}}, false}\")"]` | 661.847 μs (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumlinear\", \"SubArray{Int32, 2, BaseBenchmarks.ArrayBenchmarks.ArrayLS{Int32, 3}, Tuple{Int64, Base.Slice{Base.OneTo{Int64}}, Base.Slice{Base.OneTo{Int64}}}, false}\")"]` | 732.479 μs (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumlinear\", \"SubArray{Int32, 2, Matrix{Int32}, Tuple{Base.Slice{Base.OneTo{Int64}}, Base.Slice{Base.OneTo{Int64}}}, true}\")"]` | 18.206 μs (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumlinear\", \"SubArray{Int32, 2, Matrix{Int32}, Tuple{UnitRange{Int64}, UnitRange{Int64}}, false}\")"]` | 808.876 μs (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumlinear_view\", \"1.0:0.00010001000100010001:2.0\")"]` | 22.349 μs (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumlinear_view\", \"1.0:1.0:100000.0\")"]` | 223.712 μs (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumlinear_view\", \"100000:-1:1\")"]` | 1.853 ms (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumlinear_view\", \"1:100000\")"]` | 8.167 μs (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumlinear_view\", \"Array{Float64, 3}\")"]` | 47.022 μs (50%) | 0.000 ns | 103.98 KiB (1%) | 2662 |
| `["array", "index", "(\"sumlinear_view\", \"Base.ReinterpretArray{BaseBenchmarks.ArrayBenchmarks.PairVals{Float32}, 2, Float32, Matrix{Float32}, false}\")"]` | 518.762 μs (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumlinear_view\", \"Base.ReinterpretArray{BaseBenchmarks.ArrayBenchmarks.PairVals{Float32}, 2, Float64, Matrix{Float64}, false}\")"]` | 985.692 μs (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumlinear_view\", \"Base.ReinterpretArray{BaseBenchmarks.ArrayBenchmarks.PairVals{Int32}, 2, Int32, Matrix{Int32}, false}\")"]` | 455.596 μs (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumlinear_view\", \"Base.ReinterpretArray{BaseBenchmarks.ArrayBenchmarks.PairVals{Int32}, 2, Int64, Matrix{Int64}, false}\")"]` | 1.007 ms (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumlinear_view\", \"Base.ReinterpretArray{Float32, 2, Int32, Matrix{Int32}, false}\")"]` | 884.505 μs (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumlinear_view\", \"Base.ReinterpretArray{Int32, 3, Float64, Array{Float64, 3}, false}\")"]` | 9.848 μs (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumlinear_view\", \"BaseBenchmarks.ArrayBenchmarks.ArrayLF{Float32, 2}\")"]` | 16.839 μs (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumlinear_view\", \"BaseBenchmarks.ArrayBenchmarks.ArrayLF{Int32, 2}\")"]` | 18.124 μs (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumlinear_view\", \"BaseBenchmarks.ArrayBenchmarks.ArrayLSLS{Float32, 2}\")"]` | 10.151 ms (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumlinear_view\", \"BaseBenchmarks.ArrayBenchmarks.ArrayLSLS{Int32, 2}\")"]` | 10.209 ms (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumlinear_view\", \"BaseBenchmarks.ArrayBenchmarks.ArrayLS{Float32, 2}\")"]` | 10.759 ms (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumlinear_view\", \"BaseBenchmarks.ArrayBenchmarks.ArrayLS{Int32, 2}\")"]` | 10.192 ms (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumlinear_view\", \"BitMatrix\")"]` | 7.922 ms (50%) | 0.000 ns | 19.07 MiB (1%) | 250000 |
| `["array", "index", "(\"sumlinear_view\", \"Matrix{Float32}\")"]` | 9.081 ms (50%) | 0.000 ns | 19.07 MiB (1%) | 500000 |
| `["array", "index", "(\"sumlinear_view\", \"Matrix{Float64}\")"]` | 8.948 ms (50%) | 0.000 ns | 19.07 MiB (1%) | 500000 |
| `["array", "index", "(\"sumlinear_view\", \"Matrix{Int32}\")"]` | 8.846 ms (50%) | 0.000 ns | 19.07 MiB (1%) | 500000 |
| `["array", "index", "(\"sumlinear_view\", \"Matrix{Int64}\")"]` | 8.848 ms (50%) | 0.000 ns | 19.07 MiB (1%) | 500000 |
| `["array", "index", "(\"sumlinear_view\", \"SubArray{Float32, 2, Array{Float32, 3}, Tuple{Int64, Base.Slice{Base.OneTo{Int64}}, Base.Slice{Base.OneTo{Int64}}}, true}\")"]` | 294.207 μs (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumlinear_view\", \"SubArray{Float32, 2, Base.ReshapedArray{Float32, 2, SubArray{Float32, 3, Array{Float32, 3}, Tuple{Base.Slice{Base.OneTo{Int64}}, Base.Slice{Base.OneTo{Int64}}, Base.Slice{Base.OneTo{Int64}}}, true}, Tuple{}}, Tuple{Base.Slice{Base.OneTo{Int64}}, UnitRange{Int64}}, true}\")"]` | 132.000 ns (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumlinear_view\", \"SubArray{Float32, 2, Base.ReshapedArray{Float32, 2, SubArray{Float32, 3, BaseBenchmarks.ArrayBenchmarks.ArrayLS{Float32, 3}, Tuple{Base.Slice{Base.OneTo{Int64}}, Base.Slice{Base.OneTo{Int64}}, Base.Slice{Base.OneTo{Int64}}}, false}, Tuple{Base.MultiplicativeInverses.SignedMultiplicativeInverse{Int64}, Base.MultiplicativeInverses.SignedMultiplicativeInverse{Int64}}}, Tuple{Base.Slice{Base.OneTo{Int64}}, UnitRange{Int64}}, false}\")"]` | 54.207 μs (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumlinear_view\", \"SubArray{Float32, 2, BaseBenchmarks.ArrayBenchmarks.ArrayLS{Float32, 2}, Tuple{Base.Slice{Base.OneTo{Int64}}, Base.Slice{Base.OneTo{Int64}}}, false}\")"]` | 10.233 ms (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumlinear_view\", \"SubArray{Float32, 2, BaseBenchmarks.ArrayBenchmarks.ArrayLS{Float32, 3}, Tuple{Int64, Base.Slice{Base.OneTo{Int64}}, Base.Slice{Base.OneTo{Int64}}}, false}\")"]` | 9.352 ms (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumlinear_view\", \"SubArray{Float32, 2, Matrix{Float32}, Tuple{Base.Slice{Base.OneTo{Int64}}, Base.Slice{Base.OneTo{Int64}}}, true}\")"]` | 16.842 μs (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumlinear_view\", \"SubArray{Float32, 2, Matrix{Float32}, Tuple{UnitRange{Int64}, UnitRange{Int64}}, false}\")"]` | 10.186 ms (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumlinear_view\", \"SubArray{Float64, 3, Array{Float64, 3}, Tuple{UnitRange{Int64}, UnitRange{Int64}, UnitRange{Int64}}, false}\")"]` | 82.999 μs (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumlinear_view\", \"SubArray{Int32, 2, Array{Int32, 3}, Tuple{Int64, Base.Slice{Base.OneTo{Int64}}, Base.Slice{Base.OneTo{Int64}}}, true}\")"]` | 147.685 μs (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumlinear_view\", \"SubArray{Int32, 2, Base.ReshapedArray{Int32, 2, SubArray{Int32, 3, Array{Int32, 3}, Tuple{Base.Slice{Base.OneTo{Int64}}, Base.Slice{Base.OneTo{Int64}}, Base.Slice{Base.OneTo{Int64}}}, true}, Tuple{}}, Tuple{Base.Slice{Base.OneTo{Int64}}, UnitRange{Int64}}, true}\")"]` | 106.000 ns (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumlinear_view\", \"SubArray{Int32, 2, Base.ReshapedArray{Int32, 2, SubArray{Int32, 3, BaseBenchmarks.ArrayBenchmarks.ArrayLS{Int32, 3}, Tuple{Base.Slice{Base.OneTo{Int64}}, Base.Slice{Base.OneTo{Int64}}, Base.Slice{Base.OneTo{Int64}}}, false}, Tuple{Base.MultiplicativeInverses.SignedMultiplicativeInverse{Int64}, Base.MultiplicativeInverses.SignedMultiplicativeInverse{Int64}}}, Tuple{Base.Slice{Base.OneTo{Int64}}, UnitRange{Int64}}, false}\")"]` | 53.844 μs (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumlinear_view\", \"SubArray{Int32, 2, BaseBenchmarks.ArrayBenchmarks.ArrayLS{Int32, 2}, Tuple{Base.Slice{Base.OneTo{Int64}}, Base.Slice{Base.OneTo{Int64}}}, false}\")"]` | 10.237 ms (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumlinear_view\", \"SubArray{Int32, 2, BaseBenchmarks.ArrayBenchmarks.ArrayLS{Int32, 3}, Tuple{Int64, Base.Slice{Base.OneTo{Int64}}, Base.Slice{Base.OneTo{Int64}}}, false}\")"]` | 9.243 ms (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumlinear_view\", \"SubArray{Int32, 2, Matrix{Int32}, Tuple{Base.Slice{Base.OneTo{Int64}}, Base.Slice{Base.OneTo{Int64}}}, true}\")"]` | 18.193 μs (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumlinear_view\", \"SubArray{Int32, 2, Matrix{Int32}, Tuple{UnitRange{Int64}, UnitRange{Int64}}, false}\")"]` | 10.136 ms (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumlogical\", \"1.0:0.00010001000100010001:2.0\")"]` | 10.106 μs (50%) | 0.000 ns | 21.00 KiB (1%) | 4 |
| `["array", "index", "(\"sumlogical\", \"1.0:1.0:100000.0\")"]` | 98.248 μs (50%) | 0.000 ns | 207.80 KiB (1%) | 4 |
| `["array", "index", "(\"sumlogical\", \"100000:-1:1\")"]` | 63.627 μs (50%) | 0.000 ns | 207.80 KiB (1%) | 4 |
| `["array", "index", "(\"sumlogical\", \"1:100000\")"]` | 63.597 μs (50%) | 0.000 ns | 207.80 KiB (1%) | 4 |
| `["array", "index", "(\"sumlogical\", \"Base.ReinterpretArray{BaseBenchmarks.ArrayBenchmarks.PairVals{Float32}, 2, Float32, Matrix{Float32}, false}\")"]` | 80.888 μs (50%) | 0.000 ns | 304.83 KiB (1%) | 502 |
| `["array", "index", "(\"sumlogical\", \"Base.ReinterpretArray{BaseBenchmarks.ArrayBenchmarks.PairVals{Float32}, 2, Float64, Matrix{Float64}, false}\")"]` | 182.609 μs (50%) | 0.000 ns | 531.42 KiB (1%) | 502 |
| `["array", "index", "(\"sumlogical\", \"Base.ReinterpretArray{BaseBenchmarks.ArrayBenchmarks.PairVals{Int32}, 2, Int32, Matrix{Int32}, false}\")"]` | 73.413 μs (50%) | 0.000 ns | 304.83 KiB (1%) | 502 |
| `["array", "index", "(\"sumlogical\", \"Base.ReinterpretArray{BaseBenchmarks.ArrayBenchmarks.PairVals{Int32}, 2, Int64, Matrix{Int64}, false}\")"]` | 183.458 μs (50%) | 0.000 ns | 531.42 KiB (1%) | 502 |
| `["array", "index", "(\"sumlogical\", \"Base.ReinterpretArray{Float32, 2, Int32, Matrix{Int32}, false}\")"]` | 114.259 μs (50%) | 0.000 ns | 304.86 KiB (1%) | 502 |
| `["array", "index", "(\"sumlogical\", \"BaseBenchmarks.ArrayBenchmarks.ArrayLF{Float32, 2}\")"]` | 92.159 μs (50%) | 0.000 ns | 304.86 KiB (1%) | 502 |
| `["array", "index", "(\"sumlogical\", \"BaseBenchmarks.ArrayBenchmarks.ArrayLF{Int32, 2}\")"]` | 92.202 μs (50%) | 0.000 ns | 304.86 KiB (1%) | 502 |
| `["array", "index", "(\"sumlogical\", \"BaseBenchmarks.ArrayBenchmarks.ArrayLSLS{Float32, 2}\")"]` | 93.076 μs (50%) | 0.000 ns | 304.86 KiB (1%) | 502 |
| `["array", "index", "(\"sumlogical\", \"BaseBenchmarks.ArrayBenchmarks.ArrayLSLS{Int32, 2}\")"]` | 120.278 μs (50%) | 0.000 ns | 304.86 KiB (1%) | 502 |
| `["array", "index", "(\"sumlogical\", \"BaseBenchmarks.ArrayBenchmarks.ArrayLS{Float32, 2}\")"]` | 120.000 μs (50%) | 0.000 ns | 304.86 KiB (1%) | 502 |
| `["array", "index", "(\"sumlogical\", \"BaseBenchmarks.ArrayBenchmarks.ArrayLS{Int32, 2}\")"]` | 93.228 μs (50%) | 0.000 ns | 304.86 KiB (1%) | 502 |
| `["array", "index", "(\"sumlogical\", \"BitMatrix\")"]` | 194.036 μs (50%) | 0.000 ns | 62.67 KiB (1%) | 1002 |
| `["array", "index", "(\"sumlogical\", \"Matrix{Float32}\")"]` | 92.194 μs (50%) | 0.000 ns | 304.86 KiB (1%) | 502 |
| `["array", "index", "(\"sumlogical\", \"Matrix{Float64}\")"]` | 124.378 μs (50%) | 0.000 ns | 531.42 KiB (1%) | 502 |
| `["array", "index", "(\"sumlogical\", \"Matrix{Int32}\")"]` | 92.988 μs (50%) | 0.000 ns | 304.86 KiB (1%) | 502 |
| `["array", "index", "(\"sumlogical\", \"Matrix{Int64}\")"]` | 125.322 μs (50%) | 0.000 ns | 531.42 KiB (1%) | 502 |
| `["array", "index", "(\"sumlogical\", \"SubArray{Float32, 2, Array{Float32, 3}, Tuple{Int64, Base.Slice{Base.OneTo{Int64}}, Base.Slice{Base.OneTo{Int64}}}, true}\")"]` | 172.852 μs (50%) | 0.000 ns | 304.86 KiB (1%) | 502 |
| `["array", "index", "(\"sumlogical\", \"SubArray{Float32, 2, Base.ReshapedArray{Float32, 2, SubArray{Float32, 3, Array{Float32, 3}, Tuple{Base.Slice{Base.OneTo{Int64}}, Base.Slice{Base.OneTo{Int64}}, Base.Slice{Base.OneTo{Int64}}}, true}, Tuple{}}, Tuple{Base.Slice{Base.OneTo{Int64}}, UnitRange{Int64}}, true}\")"]` | 16.451 μs (50%) | 0.000 ns | 47.00 KiB (1%) | 502 |
| `["array", "index", "(\"sumlogical\", \"SubArray{Float32, 2, Base.ReshapedArray{Float32, 2, SubArray{Float32, 3, BaseBenchmarks.ArrayBenchmarks.ArrayLS{Float32, 3}, Tuple{Base.Slice{Base.OneTo{Int64}}, Base.Slice{Base.OneTo{Int64}}, Base.Slice{Base.OneTo{Int64}}}, false}, Tuple{Base.MultiplicativeInverses.SignedMultiplicativeInverse{Int64}, Base.MultiplicativeInverses.SignedMultiplicativeInverse{Int64}}}, Tuple{Base.Slice{Base.OneTo{Int64}}, UnitRange{Int64}}, false}\")"]` | 19.168 μs (50%) | 0.000 ns | 47.00 KiB (1%) | 502 |
| `["array", "index", "(\"sumlogical\", \"SubArray{Float32, 2, BaseBenchmarks.ArrayBenchmarks.ArrayLS{Float32, 2}, Tuple{Base.Slice{Base.OneTo{Int64}}, Base.Slice{Base.OneTo{Int64}}}, false}\")"]` | 92.029 μs (50%) | 0.000 ns | 304.86 KiB (1%) | 502 |
| `["array", "index", "(\"sumlogical\", \"SubArray{Float32, 2, BaseBenchmarks.ArrayBenchmarks.ArrayLS{Float32, 3}, Tuple{Int64, Base.Slice{Base.OneTo{Int64}}, Base.Slice{Base.OneTo{Int64}}}, false}\")"]` | 171.953 μs (50%) | 0.000 ns | 304.25 KiB (1%) | 501 |
| `["array", "index", "(\"sumlogical\", \"SubArray{Float32, 2, Matrix{Float32}, Tuple{Base.Slice{Base.OneTo{Int64}}, Base.Slice{Base.OneTo{Int64}}}, true}\")"]` | 121.098 μs (50%) | 0.000 ns | 304.86 KiB (1%) | 502 |
| `["array", "index", "(\"sumlogical\", \"SubArray{Float32, 2, Matrix{Float32}, Tuple{UnitRange{Int64}, UnitRange{Int64}}, false}\")"]` | 96.993 μs (50%) | 0.000 ns | 304.86 KiB (1%) | 502 |
| `["array", "index", "(\"sumlogical\", \"SubArray{Int32, 2, Array{Int32, 3}, Tuple{Int64, Base.Slice{Base.OneTo{Int64}}, Base.Slice{Base.OneTo{Int64}}}, true}\")"]` | 172.939 μs (50%) | 0.000 ns | 304.86 KiB (1%) | 502 |
| `["array", "index", "(\"sumlogical\", \"SubArray{Int32, 2, Base.ReshapedArray{Int32, 2, SubArray{Int32, 3, Array{Int32, 3}, Tuple{Base.Slice{Base.OneTo{Int64}}, Base.Slice{Base.OneTo{Int64}}, Base.Slice{Base.OneTo{Int64}}}, true}, Tuple{}}, Tuple{Base.Slice{Base.OneTo{Int64}}, UnitRange{Int64}}, true}\")"]` | 16.203 μs (50%) | 0.000 ns | 47.00 KiB (1%) | 502 |
| `["array", "index", "(\"sumlogical\", \"SubArray{Int32, 2, Base.ReshapedArray{Int32, 2, SubArray{Int32, 3, BaseBenchmarks.ArrayBenchmarks.ArrayLS{Int32, 3}, Tuple{Base.Slice{Base.OneTo{Int64}}, Base.Slice{Base.OneTo{Int64}}, Base.Slice{Base.OneTo{Int64}}}, false}, Tuple{Base.MultiplicativeInverses.SignedMultiplicativeInverse{Int64}, Base.MultiplicativeInverses.SignedMultiplicativeInverse{Int64}}}, Tuple{Base.Slice{Base.OneTo{Int64}}, UnitRange{Int64}}, false}\")"]` | 18.961 μs (50%) | 0.000 ns | 47.00 KiB (1%) | 502 |
| `["array", "index", "(\"sumlogical\", \"SubArray{Int32, 2, BaseBenchmarks.ArrayBenchmarks.ArrayLS{Int32, 2}, Tuple{Base.Slice{Base.OneTo{Int64}}, Base.Slice{Base.OneTo{Int64}}}, false}\")"]` | 93.289 μs (50%) | 0.000 ns | 304.86 KiB (1%) | 502 |
| `["array", "index", "(\"sumlogical\", \"SubArray{Int32, 2, BaseBenchmarks.ArrayBenchmarks.ArrayLS{Int32, 3}, Tuple{Int64, Base.Slice{Base.OneTo{Int64}}, Base.Slice{Base.OneTo{Int64}}}, false}\")"]` | 172.418 μs (50%) | 0.000 ns | 304.25 KiB (1%) | 501 |
| `["array", "index", "(\"sumlogical\", \"SubArray{Int32, 2, Matrix{Int32}, Tuple{Base.Slice{Base.OneTo{Int64}}, Base.Slice{Base.OneTo{Int64}}}, true}\")"]` | 93.594 μs (50%) | 0.000 ns | 304.86 KiB (1%) | 502 |
| `["array", "index", "(\"sumlogical\", \"SubArray{Int32, 2, Matrix{Int32}, Tuple{UnitRange{Int64}, UnitRange{Int64}}, false}\")"]` | 97.640 μs (50%) | 0.000 ns | 304.86 KiB (1%) | 502 |
| `["array", "index", "(\"sumlogical_view\", \"1.0:0.00010001000100010001:2.0\")"]` | 4.691 μs (50%) | 0.000 ns | 21.00 KiB (1%) | 4 |
| `["array", "index", "(\"sumlogical_view\", \"1.0:1.0:100000.0\")"]` | 44.878 μs (50%) | 0.000 ns | 207.80 KiB (1%) | 4 |
| `["array", "index", "(\"sumlogical_view\", \"100000:-1:1\")"]` | 45.349 μs (50%) | 0.000 ns | 207.80 KiB (1%) | 4 |
| `["array", "index", "(\"sumlogical_view\", \"1:100000\")"]` | 45.159 μs (50%) | 0.000 ns | 207.80 KiB (1%) | 4 |
| `["array", "index", "(\"sumlogical_view\", \"Base.ReinterpretArray{BaseBenchmarks.ArrayBenchmarks.PairVals{Float32}, 2, Float32, Matrix{Float32}, false}\")"]` | 66.419 μs (50%) | 0.000 ns | 304.83 KiB (1%) | 502 |
| `["array", "index", "(\"sumlogical_view\", \"Base.ReinterpretArray{BaseBenchmarks.ArrayBenchmarks.PairVals{Float32}, 2, Float64, Matrix{Float64}, false}\")"]` | 99.974 μs (50%) | 0.000 ns | 531.42 KiB (1%) | 502 |
| `["array", "index", "(\"sumlogical_view\", \"Base.ReinterpretArray{BaseBenchmarks.ArrayBenchmarks.PairVals{Int32}, 2, Int32, Matrix{Int32}, false}\")"]` | 66.427 μs (50%) | 0.000 ns | 304.83 KiB (1%) | 502 |
| `["array", "index", "(\"sumlogical_view\", \"Base.ReinterpretArray{BaseBenchmarks.ArrayBenchmarks.PairVals{Int32}, 2, Int64, Matrix{Int64}, false}\")"]` | 99.711 μs (50%) | 0.000 ns | 531.42 KiB (1%) | 502 |
| `["array", "index", "(\"sumlogical_view\", \"Base.ReinterpretArray{Float32, 2, Int32, Matrix{Int32}, false}\")"]` | 98.022 μs (50%) | 0.000 ns | 531.42 KiB (1%) | 502 |
| `["array", "index", "(\"sumlogical_view\", \"BaseBenchmarks.ArrayBenchmarks.ArrayLF{Float32, 2}\")"]` | 102.520 μs (50%) | 0.000 ns | 531.42 KiB (1%) | 502 |
| `["array", "index", "(\"sumlogical_view\", \"BaseBenchmarks.ArrayBenchmarks.ArrayLF{Int32, 2}\")"]` | 101.958 μs (50%) | 0.000 ns | 531.42 KiB (1%) | 502 |
| `["array", "index", "(\"sumlogical_view\", \"BaseBenchmarks.ArrayBenchmarks.ArrayLSLS{Float32, 2}\")"]` | 102.809 μs (50%) | 0.000 ns | 531.42 KiB (1%) | 502 |
| `["array", "index", "(\"sumlogical_view\", \"BaseBenchmarks.ArrayBenchmarks.ArrayLSLS{Int32, 2}\")"]` | 102.712 μs (50%) | 0.000 ns | 531.42 KiB (1%) | 502 |
| `["array", "index", "(\"sumlogical_view\", \"BaseBenchmarks.ArrayBenchmarks.ArrayLS{Float32, 2}\")"]` | 103.627 μs (50%) | 0.000 ns | 531.42 KiB (1%) | 502 |
| `["array", "index", "(\"sumlogical_view\", \"BaseBenchmarks.ArrayBenchmarks.ArrayLS{Int32, 2}\")"]` | 103.045 μs (50%) | 0.000 ns | 531.42 KiB (1%) | 502 |
| `["array", "index", "(\"sumlogical_view\", \"BitMatrix\")"]` | 99.501 μs (50%) | 0.000 ns | 531.42 KiB (1%) | 502 |
| `["array", "index", "(\"sumlogical_view\", \"Matrix{Float32}\")"]` | 98.855 μs (50%) | 0.000 ns | 531.42 KiB (1%) | 502 |
| `["array", "index", "(\"sumlogical_view\", \"Matrix{Float64}\")"]` | 96.624 μs (50%) | 0.000 ns | 531.42 KiB (1%) | 502 |
| `["array", "index", "(\"sumlogical_view\", \"Matrix{Int32}\")"]` | 98.044 μs (50%) | 0.000 ns | 531.42 KiB (1%) | 502 |
| `["array", "index", "(\"sumlogical_view\", \"Matrix{Int64}\")"]` | 97.356 μs (50%) | 0.000 ns | 531.42 KiB (1%) | 502 |
| `["array", "index", "(\"sumlogical_view\", \"SubArray{Float32, 2, Array{Float32, 3}, Tuple{Int64, Base.Slice{Base.OneTo{Int64}}, Base.Slice{Base.OneTo{Int64}}}, true}\")"]` | 96.984 μs (50%) | 0.000 ns | 531.42 KiB (1%) | 502 |
| `["array", "index", "(\"sumlogical_view\", \"SubArray{Float32, 2, Base.ReshapedArray{Float32, 2, SubArray{Float32, 3, Array{Float32, 3}, Tuple{Base.Slice{Base.OneTo{Int64}}, Base.Slice{Base.OneTo{Int64}}, Base.Slice{Base.OneTo{Int64}}}, true}, Tuple{}}, Tuple{Base.Slice{Base.OneTo{Int64}}, UnitRange{Int64}}, true}\")"]` | 30.653 μs (50%) | 0.000 ns | 47.00 KiB (1%) | 502 |
| `["array", "index", "(\"sumlogical_view\", \"SubArray{Float32, 2, Base.ReshapedArray{Float32, 2, SubArray{Float32, 3, BaseBenchmarks.ArrayBenchmarks.ArrayLS{Float32, 3}, Tuple{Base.Slice{Base.OneTo{Int64}}, Base.Slice{Base.OneTo{Int64}}, Base.Slice{Base.OneTo{Int64}}}, false}, Tuple{Base.MultiplicativeInverses.SignedMultiplicativeInverse{Int64}, Base.MultiplicativeInverses.SignedMultiplicativeInverse{Int64}}}, Tuple{Base.Slice{Base.OneTo{Int64}}, UnitRange{Int64}}, false}\")"]` | 41.097 μs (50%) | 0.000 ns | 47.00 KiB (1%) | 502 |
| `["array", "index", "(\"sumlogical_view\", \"SubArray{Float32, 2, BaseBenchmarks.ArrayBenchmarks.ArrayLS{Float32, 2}, Tuple{Base.Slice{Base.OneTo{Int64}}, Base.Slice{Base.OneTo{Int64}}}, false}\")"]` | 101.796 μs (50%) | 0.000 ns | 531.42 KiB (1%) | 502 |
| `["array", "index", "(\"sumlogical_view\", \"SubArray{Float32, 2, BaseBenchmarks.ArrayBenchmarks.ArrayLS{Float32, 3}, Tuple{Int64, Base.Slice{Base.OneTo{Int64}}, Base.Slice{Base.OneTo{Int64}}}, false}\")"]` | 102.530 μs (50%) | 0.000 ns | 530.36 KiB (1%) | 501 |
| `["array", "index", "(\"sumlogical_view\", \"SubArray{Float32, 2, Matrix{Float32}, Tuple{Base.Slice{Base.OneTo{Int64}}, Base.Slice{Base.OneTo{Int64}}}, true}\")"]` | 98.116 μs (50%) | 0.000 ns | 531.42 KiB (1%) | 502 |
| `["array", "index", "(\"sumlogical_view\", \"SubArray{Float32, 2, Matrix{Float32}, Tuple{UnitRange{Int64}, UnitRange{Int64}}, false}\")"]` | 135.766 μs (50%) | 0.000 ns | 531.42 KiB (1%) | 502 |
| `["array", "index", "(\"sumlogical_view\", \"SubArray{Int32, 2, Array{Int32, 3}, Tuple{Int64, Base.Slice{Base.OneTo{Int64}}, Base.Slice{Base.OneTo{Int64}}}, true}\")"]` | 97.973 μs (50%) | 0.000 ns | 531.42 KiB (1%) | 502 |
| `["array", "index", "(\"sumlogical_view\", \"SubArray{Int32, 2, Base.ReshapedArray{Int32, 2, SubArray{Int32, 3, Array{Int32, 3}, Tuple{Base.Slice{Base.OneTo{Int64}}, Base.Slice{Base.OneTo{Int64}}, Base.Slice{Base.OneTo{Int64}}}, true}, Tuple{}}, Tuple{Base.Slice{Base.OneTo{Int64}}, UnitRange{Int64}}, true}\")"]` | 29.673 μs (50%) | 0.000 ns | 47.00 KiB (1%) | 502 |
| `["array", "index", "(\"sumlogical_view\", \"SubArray{Int32, 2, Base.ReshapedArray{Int32, 2, SubArray{Int32, 3, BaseBenchmarks.ArrayBenchmarks.ArrayLS{Int32, 3}, Tuple{Base.Slice{Base.OneTo{Int64}}, Base.Slice{Base.OneTo{Int64}}, Base.Slice{Base.OneTo{Int64}}}, false}, Tuple{Base.MultiplicativeInverses.SignedMultiplicativeInverse{Int64}, Base.MultiplicativeInverses.SignedMultiplicativeInverse{Int64}}}, Tuple{Base.Slice{Base.OneTo{Int64}}, UnitRange{Int64}}, false}\")"]` | 40.338 μs (50%) | 0.000 ns | 47.00 KiB (1%) | 502 |
| `["array", "index", "(\"sumlogical_view\", \"SubArray{Int32, 2, BaseBenchmarks.ArrayBenchmarks.ArrayLS{Int32, 2}, Tuple{Base.Slice{Base.OneTo{Int64}}, Base.Slice{Base.OneTo{Int64}}}, false}\")"]` | 101.486 μs (50%) | 0.000 ns | 531.42 KiB (1%) | 502 |
| `["array", "index", "(\"sumlogical_view\", \"SubArray{Int32, 2, BaseBenchmarks.ArrayBenchmarks.ArrayLS{Int32, 3}, Tuple{Int64, Base.Slice{Base.OneTo{Int64}}, Base.Slice{Base.OneTo{Int64}}}, false}\")"]` | 102.330 μs (50%) | 0.000 ns | 530.36 KiB (1%) | 501 |
| `["array", "index", "(\"sumlogical_view\", \"SubArray{Int32, 2, Matrix{Int32}, Tuple{Base.Slice{Base.OneTo{Int64}}, Base.Slice{Base.OneTo{Int64}}}, true}\")"]` | 97.096 μs (50%) | 0.000 ns | 531.42 KiB (1%) | 502 |
| `["array", "index", "(\"sumlogical_view\", \"SubArray{Int32, 2, Matrix{Int32}, Tuple{UnitRange{Int64}, UnitRange{Int64}}, false}\")"]` | 136.078 μs (50%) | 0.000 ns | 531.42 KiB (1%) | 502 |
| `["array", "index", "(\"sumrange\", \"1.0:0.00010001000100010001:2.0\")"]` | 24.923 μs (50%) | 0.000 ns | 78.20 KiB (1%) | 2 |
| `["array", "index", "(\"sumrange\", \"1.0:1.0:100000.0\")"]` | 247.783 μs (50%) | 0.000 ns | 781.33 KiB (1%) | 2 |
| `["array", "index", "(\"sumrange\", \"100000:-1:1\")"]` | 72.690 μs (50%) | 0.000 ns | 781.33 KiB (1%) | 2 |
| `["array", "index", "(\"sumrange\", \"1:100000\")"]` | 72.708 μs (50%) | 0.000 ns | 781.33 KiB (1%) | 2 |
| `["array", "index", "(\"sumrange\", \"Base.ReinterpretArray{BaseBenchmarks.ArrayBenchmarks.PairVals{Float32}, 2, Float32, Matrix{Float32}, false}\")"]` | 334.869 μs (50%) | 0.000 ns | 1.04 MiB (1%) | 500 |
| `["array", "index", "(\"sumrange\", \"Base.ReinterpretArray{BaseBenchmarks.ArrayBenchmarks.PairVals{Float32}, 2, Float64, Matrix{Float64}, false}\")"]` | 634.643 μs (50%) | 0.000 ns | 1.98 MiB (1%) | 500 |
| `["array", "index", "(\"sumrange\", \"Base.ReinterpretArray{BaseBenchmarks.ArrayBenchmarks.PairVals{Int32}, 2, Int32, Matrix{Int32}, false}\")"]` | 332.327 μs (50%) | 0.000 ns | 1.04 MiB (1%) | 500 |
| `["array", "index", "(\"sumrange\", \"Base.ReinterpretArray{BaseBenchmarks.ArrayBenchmarks.PairVals{Int32}, 2, Int64, Matrix{Int64}, false}\")"]` | 633.068 μs (50%) | 0.000 ns | 1.98 MiB (1%) | 500 |
| `["array", "index", "(\"sumrange\", \"Base.ReinterpretArray{Float32, 2, Int32, Matrix{Int32}, false}\")"]` | 485.175 μs (50%) | 0.000 ns | 1.04 MiB (1%) | 500 |
| `["array", "index", "(\"sumrange\", \"BaseBenchmarks.ArrayBenchmarks.ArrayLF{Float32, 2}\")"]` | 420.106 μs (50%) | 0.000 ns | 1.04 MiB (1%) | 500 |
| `["array", "index", "(\"sumrange\", \"BaseBenchmarks.ArrayBenchmarks.ArrayLF{Int32, 2}\")"]` | 422.413 μs (50%) | 0.000 ns | 1.04 MiB (1%) | 500 |
| `["array", "index", "(\"sumrange\", \"BaseBenchmarks.ArrayBenchmarks.ArrayLSLS{Float32, 2}\")"]` | 415.330 μs (50%) | 0.000 ns | 1.04 MiB (1%) | 500 |
| `["array", "index", "(\"sumrange\", \"BaseBenchmarks.ArrayBenchmarks.ArrayLSLS{Int32, 2}\")"]` | 419.018 μs (50%) | 0.000 ns | 1.04 MiB (1%) | 500 |
| `["array", "index", "(\"sumrange\", \"BaseBenchmarks.ArrayBenchmarks.ArrayLS{Float32, 2}\")"]` | 422.006 μs (50%) | 0.000 ns | 1.04 MiB (1%) | 500 |
| `["array", "index", "(\"sumrange\", \"BaseBenchmarks.ArrayBenchmarks.ArrayLS{Int32, 2}\")"]` | 419.128 μs (50%) | 0.000 ns | 1.04 MiB (1%) | 500 |
| `["array", "index", "(\"sumrange\", \"BitMatrix\")"]` | 31.664 μs (50%) | 0.000 ns | 85.94 KiB (1%) | 1000 |
| `["array", "index", "(\"sumrange\", \"Matrix{Float32}\")"]` | 335.560 μs (50%) | 0.000 ns | 1.04 MiB (1%) | 500 |
| `["array", "index", "(\"sumrange\", \"Matrix{Float64}\")"]` | 406.028 μs (50%) | 0.000 ns | 1.98 MiB (1%) | 500 |
| `["array", "index", "(\"sumrange\", \"Matrix{Int32}\")"]` | 332.497 μs (50%) | 0.000 ns | 1.04 MiB (1%) | 500 |
| `["array", "index", "(\"sumrange\", \"Matrix{Int64}\")"]` | 406.267 μs (50%) | 0.000 ns | 1.98 MiB (1%) | 500 |
| `["array", "index", "(\"sumrange\", \"SubArray{Float32, 2, Array{Float32, 3}, Tuple{Int64, Base.Slice{Base.OneTo{Int64}}, Base.Slice{Base.OneTo{Int64}}}, true}\")"]` | 472.395 μs (50%) | 0.000 ns | 1.04 MiB (1%) | 500 |
| `["array", "index", "(\"sumrange\", \"SubArray{Float32, 2, Base.ReshapedArray{Float32, 2, SubArray{Float32, 3, Array{Float32, 3}, Tuple{Base.Slice{Base.OneTo{Int64}}, Base.Slice{Base.OneTo{Int64}}, Base.Slice{Base.OneTo{Int64}}}, true}, Tuple{}}, Tuple{Base.Slice{Base.OneTo{Int64}}, UnitRange{Int64}}, true}\")"]` | 16.843 μs (50%) | 0.000 ns | 46.88 KiB (1%) | 500 |
| `["array", "index", "(\"sumrange\", \"SubArray{Float32, 2, Base.ReshapedArray{Float32, 2, SubArray{Float32, 3, BaseBenchmarks.ArrayBenchmarks.ArrayLS{Float32, 3}, Tuple{Base.Slice{Base.OneTo{Int64}}, Base.Slice{Base.OneTo{Int64}}, Base.Slice{Base.OneTo{Int64}}}, false}, Tuple{Base.MultiplicativeInverses.SignedMultiplicativeInverse{Int64}, Base.MultiplicativeInverses.SignedMultiplicativeInverse{Int64}}}, Tuple{Base.Slice{Base.OneTo{Int64}}, UnitRange{Int64}}, false}\")"]` | 23.459 μs (50%) | 0.000 ns | 46.88 KiB (1%) | 500 |
| `["array", "index", "(\"sumrange\", \"SubArray{Float32, 2, BaseBenchmarks.ArrayBenchmarks.ArrayLS{Float32, 2}, Tuple{Base.Slice{Base.OneTo{Int64}}, Base.Slice{Base.OneTo{Int64}}}, false}\")"]` | 422.700 μs (50%) | 0.000 ns | 1.04 MiB (1%) | 500 |
| `["array", "index", "(\"sumrange\", \"SubArray{Float32, 2, BaseBenchmarks.ArrayBenchmarks.ArrayLS{Float32, 3}, Tuple{Int64, Base.Slice{Base.OneTo{Int64}}, Base.Slice{Base.OneTo{Int64}}}, false}\")"]` | 473.992 μs (50%) | 0.000 ns | 1.04 MiB (1%) | 499 |
| `["array", "index", "(\"sumrange\", \"SubArray{Float32, 2, Matrix{Float32}, Tuple{Base.Slice{Base.OneTo{Int64}}, Base.Slice{Base.OneTo{Int64}}}, true}\")"]` | 419.884 μs (50%) | 0.000 ns | 1.04 MiB (1%) | 500 |
| `["array", "index", "(\"sumrange\", \"SubArray{Float32, 2, Matrix{Float32}, Tuple{UnitRange{Int64}, UnitRange{Int64}}, false}\")"]` | 427.061 μs (50%) | 0.000 ns | 1.04 MiB (1%) | 500 |
| `["array", "index", "(\"sumrange\", \"SubArray{Int32, 2, Array{Int32, 3}, Tuple{Int64, Base.Slice{Base.OneTo{Int64}}, Base.Slice{Base.OneTo{Int64}}}, true}\")"]` | 477.200 μs (50%) | 0.000 ns | 1.04 MiB (1%) | 500 |
| `["array", "index", "(\"sumrange\", \"SubArray{Int32, 2, Base.ReshapedArray{Int32, 2, SubArray{Int32, 3, Array{Int32, 3}, Tuple{Base.Slice{Base.OneTo{Int64}}, Base.Slice{Base.OneTo{Int64}}, Base.Slice{Base.OneTo{Int64}}}, true}, Tuple{}}, Tuple{Base.Slice{Base.OneTo{Int64}}, UnitRange{Int64}}, true}\")"]` | 16.330 μs (50%) | 0.000 ns | 46.88 KiB (1%) | 500 |
| `["array", "index", "(\"sumrange\", \"SubArray{Int32, 2, Base.ReshapedArray{Int32, 2, SubArray{Int32, 3, BaseBenchmarks.ArrayBenchmarks.ArrayLS{Int32, 3}, Tuple{Base.Slice{Base.OneTo{Int64}}, Base.Slice{Base.OneTo{Int64}}, Base.Slice{Base.OneTo{Int64}}}, false}, Tuple{Base.MultiplicativeInverses.SignedMultiplicativeInverse{Int64}, Base.MultiplicativeInverses.SignedMultiplicativeInverse{Int64}}}, Tuple{Base.Slice{Base.OneTo{Int64}}, UnitRange{Int64}}, false}\")"]` | 24.205 μs (50%) | 0.000 ns | 46.88 KiB (1%) | 500 |
| `["array", "index", "(\"sumrange\", \"SubArray{Int32, 2, BaseBenchmarks.ArrayBenchmarks.ArrayLS{Int32, 2}, Tuple{Base.Slice{Base.OneTo{Int64}}, Base.Slice{Base.OneTo{Int64}}}, false}\")"]` | 420.057 μs (50%) | 0.000 ns | 1.04 MiB (1%) | 500 |
| `["array", "index", "(\"sumrange\", \"SubArray{Int32, 2, BaseBenchmarks.ArrayBenchmarks.ArrayLS{Int32, 3}, Tuple{Int64, Base.Slice{Base.OneTo{Int64}}, Base.Slice{Base.OneTo{Int64}}}, false}\")"]` | 476.839 μs (50%) | 0.000 ns | 1.04 MiB (1%) | 499 |
| `["array", "index", "(\"sumrange\", \"SubArray{Int32, 2, Matrix{Int32}, Tuple{Base.Slice{Base.OneTo{Int64}}, Base.Slice{Base.OneTo{Int64}}}, true}\")"]` | 418.348 μs (50%) | 0.000 ns | 1.04 MiB (1%) | 500 |
| `["array", "index", "(\"sumrange\", \"SubArray{Int32, 2, Matrix{Int32}, Tuple{UnitRange{Int64}, UnitRange{Int64}}, false}\")"]` | 427.852 μs (50%) | 0.000 ns | 1.04 MiB (1%) | 500 |
| `["array", "index", "(\"sumrange_view\", \"1.0:0.00010001000100010001:2.0\")"]` | 37.000 ns (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumrange_view\", \"1.0:1.0:100000.0\")"]` | 37.000 ns (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumrange_view\", \"100000:-1:1\")"]` | 58.000 ns (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumrange_view\", \"1:100000\")"]` | 36.000 ns (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumrange_view\", \"Base.ReinterpretArray{BaseBenchmarks.ArrayBenchmarks.PairVals{Float32}, 2, Float32, Matrix{Float32}, false}\")"]` | 2.886 μs (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumrange_view\", \"Base.ReinterpretArray{BaseBenchmarks.ArrayBenchmarks.PairVals{Float32}, 2, Float64, Matrix{Float64}, false}\")"]` | 2.783 μs (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumrange_view\", \"Base.ReinterpretArray{BaseBenchmarks.ArrayBenchmarks.PairVals{Int32}, 2, Int32, Matrix{Int32}, false}\")"]` | 1.973 μs (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumrange_view\", \"Base.ReinterpretArray{BaseBenchmarks.ArrayBenchmarks.PairVals{Int32}, 2, Int64, Matrix{Int64}, false}\")"]` | 2.247 μs (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumrange_view\", \"Base.ReinterpretArray{Float32, 2, Int32, Matrix{Int32}, false}\")"]` | 625.000 ns (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumrange_view\", \"BaseBenchmarks.ArrayBenchmarks.ArrayLF{Float32, 2}\")"]` | 628.000 ns (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumrange_view\", \"BaseBenchmarks.ArrayBenchmarks.ArrayLF{Int32, 2}\")"]` | 241.000 ns (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumrange_view\", \"BaseBenchmarks.ArrayBenchmarks.ArrayLSLS{Float32, 2}\")"]` | 623.000 ns (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumrange_view\", \"BaseBenchmarks.ArrayBenchmarks.ArrayLSLS{Int32, 2}\")"]` | 246.000 ns (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumrange_view\", \"BaseBenchmarks.ArrayBenchmarks.ArrayLS{Float32, 2}\")"]` | 628.000 ns (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumrange_view\", \"BaseBenchmarks.ArrayBenchmarks.ArrayLS{Int32, 2}\")"]` | 243.000 ns (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumrange_view\", \"BitMatrix\")"]` | 717.000 ns (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumrange_view\", \"Matrix{Float32}\")"]` | 621.000 ns (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumrange_view\", \"Matrix{Float64}\")"]` | 622.000 ns (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumrange_view\", \"Matrix{Int32}\")"]` | 232.000 ns (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumrange_view\", \"Matrix{Int64}\")"]` | 232.000 ns (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumrange_view\", \"SubArray{Float32, 2, Array{Float32, 3}, Tuple{Int64, Base.Slice{Base.OneTo{Int64}}, Base.Slice{Base.OneTo{Int64}}}, true}\")"]` | 627.000 ns (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumrange_view\", \"SubArray{Float32, 2, Base.ReshapedArray{Float32, 2, SubArray{Float32, 3, Array{Float32, 3}, Tuple{Base.Slice{Base.OneTo{Int64}}, Base.Slice{Base.OneTo{Int64}}, Base.Slice{Base.OneTo{Int64}}}, true}, Tuple{}}, Tuple{Base.Slice{Base.OneTo{Int64}}, UnitRange{Int64}}, true}\")"]` | 616.000 ns (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumrange_view\", \"SubArray{Float32, 2, Base.ReshapedArray{Float32, 2, SubArray{Float32, 3, BaseBenchmarks.ArrayBenchmarks.ArrayLS{Float32, 3}, Tuple{Base.Slice{Base.OneTo{Int64}}, Base.Slice{Base.OneTo{Int64}}, Base.Slice{Base.OneTo{Int64}}}, false}, Tuple{Base.MultiplicativeInverses.SignedMultiplicativeInverse{Int64}, Base.MultiplicativeInverses.SignedMultiplicativeInverse{Int64}}}, Tuple{Base.Slice{Base.OneTo{Int64}}, UnitRange{Int64}}, false}\")"]` | 7.531 μs (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumrange_view\", \"SubArray{Float32, 2, BaseBenchmarks.ArrayBenchmarks.ArrayLS{Float32, 2}, Tuple{Base.Slice{Base.OneTo{Int64}}, Base.Slice{Base.OneTo{Int64}}}, false}\")"]` | 627.000 ns (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumrange_view\", \"SubArray{Float32, 2, BaseBenchmarks.ArrayBenchmarks.ArrayLS{Float32, 3}, Tuple{Int64, Base.Slice{Base.OneTo{Int64}}, Base.Slice{Base.OneTo{Int64}}}, false}\")"]` | 626.000 ns (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumrange_view\", \"SubArray{Float32, 2, Matrix{Float32}, Tuple{Base.Slice{Base.OneTo{Int64}}, Base.Slice{Base.OneTo{Int64}}}, true}\")"]` | 629.000 ns (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumrange_view\", \"SubArray{Float32, 2, Matrix{Float32}, Tuple{UnitRange{Int64}, UnitRange{Int64}}, false}\")"]` | 627.000 ns (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumrange_view\", \"SubArray{Int32, 2, Array{Int32, 3}, Tuple{Int64, Base.Slice{Base.OneTo{Int64}}, Base.Slice{Base.OneTo{Int64}}}, true}\")"]` | 274.000 ns (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumrange_view\", \"SubArray{Int32, 2, Base.ReshapedArray{Int32, 2, SubArray{Int32, 3, Array{Int32, 3}, Tuple{Base.Slice{Base.OneTo{Int64}}, Base.Slice{Base.OneTo{Int64}}, Base.Slice{Base.OneTo{Int64}}}, true}, Tuple{}}, Tuple{Base.Slice{Base.OneTo{Int64}}, UnitRange{Int64}}, true}\")"]` | 162.000 ns (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumrange_view\", \"SubArray{Int32, 2, Base.ReshapedArray{Int32, 2, SubArray{Int32, 3, BaseBenchmarks.ArrayBenchmarks.ArrayLS{Int32, 3}, Tuple{Base.Slice{Base.OneTo{Int64}}, Base.Slice{Base.OneTo{Int64}}, Base.Slice{Base.OneTo{Int64}}}, false}, Tuple{Base.MultiplicativeInverses.SignedMultiplicativeInverse{Int64}, Base.MultiplicativeInverses.SignedMultiplicativeInverse{Int64}}}, Tuple{Base.Slice{Base.OneTo{Int64}}, UnitRange{Int64}}, false}\")"]` | 7.384 μs (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumrange_view\", \"SubArray{Int32, 2, BaseBenchmarks.ArrayBenchmarks.ArrayLS{Int32, 2}, Tuple{Base.Slice{Base.OneTo{Int64}}, Base.Slice{Base.OneTo{Int64}}}, false}\")"]` | 247.000 ns (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumrange_view\", \"SubArray{Int32, 2, BaseBenchmarks.ArrayBenchmarks.ArrayLS{Int32, 3}, Tuple{Int64, Base.Slice{Base.OneTo{Int64}}, Base.Slice{Base.OneTo{Int64}}}, false}\")"]` | 269.000 ns (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumrange_view\", \"SubArray{Int32, 2, Matrix{Int32}, Tuple{Base.Slice{Base.OneTo{Int64}}, Base.Slice{Base.OneTo{Int64}}}, true}\")"]` | 243.000 ns (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumrange_view\", \"SubArray{Int32, 2, Matrix{Int32}, Tuple{UnitRange{Int64}, UnitRange{Int64}}, false}\")"]` | 243.000 ns (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "(\"sumvector\", \"1.0:0.00010001000100010001:2.0\")"]` | 120.000 ns (50%) | 0.000 ns | 256 bytes (1%) | 2 |
| `["array", "index", "(\"sumvector\", \"1.0:1.0:100000.0\")"]` | 122.000 ns (50%) | 0.000 ns | 256 bytes (1%) | 2 |
| `["array", "index", "(\"sumvector\", \"100000:-1:1\")"]` | 120.000 ns (50%) | 0.000 ns | 256 bytes (1%) | 2 |
| `["array", "index", "(\"sumvector\", \"1:100000\")"]` | 110.000 ns (50%) | 0.000 ns | 256 bytes (1%) | 2 |
| `["array", "index", "(\"sumvector\", \"Base.ReinterpretArray{BaseBenchmarks.ArrayBenchmarks.PairVals{Float32}, 2, Float32, Matrix{Float32}, false}\")"]` | 22.781 μs (50%) | 0.000 ns | 62.63 KiB (1%) | 501 |
| `["array", "index", "(\"sumvector\", \"Base.ReinterpretArray{BaseBenchmarks.ArrayBenchmarks.PairVals{Float32}, 2, Float64, Matrix{Float64}, false}\")"]` | 28.425 μs (50%) | 0.000 ns | 62.63 KiB (1%) | 501 |
| `["array", "index", "(\"sumvector\", \"Base.ReinterpretArray{BaseBenchmarks.ArrayBenchmarks.PairVals{Int32}, 2, Int32, Matrix{Int32}, false}\")"]` | 22.172 μs (50%) | 0.000 ns | 62.63 KiB (1%) | 501 |
| `["array", "index", "(\"sumvector\", \"Base.ReinterpretArray{BaseBenchmarks.ArrayBenchmarks.PairVals{Int32}, 2, Int64, Matrix{Int64}, false}\")"]` | 28.310 μs (50%) | 0.000 ns | 62.63 KiB (1%) | 501 |
| `["array", "index", "(\"sumvector\", \"Base.ReinterpretArray{Float32, 2, Int32, Matrix{Int32}, false}\")"]` | 22.303 μs (50%) | 0.000 ns | 54.81 KiB (1%) | 501 |
| `["array", "index", "(\"sumvector\", \"BaseBenchmarks.ArrayBenchmarks.ArrayLF{Float32, 2}\")"]` | 21.380 μs (50%) | 0.000 ns | 54.81 KiB (1%) | 501 |
| `["array", "index", "(\"sumvector\", \"BaseBenchmarks.ArrayBenchmarks.ArrayLF{Int32, 2}\")"]` | 22.177 μs (50%) | 0.000 ns | 54.81 KiB (1%) | 501 |
| `["array", "index", "(\"sumvector\", \"BaseBenchmarks.ArrayBenchmarks.ArrayLSLS{Float32, 2}\")"]` | 20.073 μs (50%) | 0.000 ns | 54.81 KiB (1%) | 501 |
| `["array", "index", "(\"sumvector\", \"BaseBenchmarks.ArrayBenchmarks.ArrayLSLS{Int32, 2}\")"]` | 21.090 μs (50%) | 0.000 ns | 54.81 KiB (1%) | 501 |
| `["array", "index", "(\"sumvector\", \"BaseBenchmarks.ArrayBenchmarks.ArrayLS{Float32, 2}\")"]` | 19.775 μs (50%) | 0.000 ns | 54.81 KiB (1%) | 501 |
| `["array", "index", "(\"sumvector\", \"BaseBenchmarks.ArrayBenchmarks.ArrayLS{Int32, 2}\")"]` | 21.341 μs (50%) | 0.000 ns | 54.81 KiB (1%) | 501 |
| `["array", "index", "(\"sumvector\", \"BitMatrix\")"]` | 24.023 μs (50%) | 0.000 ns | 62.63 KiB (1%) | 1001 |
| `["array", "index", "(\"sumvector\", \"Matrix{Float32}\")"]` | 20.765 μs (50%) | 0.000 ns | 54.81 KiB (1%) | 501 |
| `["array", "index", "(\"sumvector\", \"Matrix{Float64}\")"]` | 25.668 μs (50%) | 0.000 ns | 62.63 KiB (1%) | 501 |
| `["array", "index", "(\"sumvector\", \"Matrix{Int32}\")"]` | 21.053 μs (50%) | 0.000 ns | 54.81 KiB (1%) | 501 |
| `["array", "index", "(\"sumvector\", \"Matrix{Int64}\")"]` | 25.437 μs (50%) | 0.000 ns | 62.63 KiB (1%) | 501 |
| `["array", "index", "(\"sumvector\", \"SubArray{Float32, 2, Array{Float32, 3}, Tuple{Int64, Base.Slice{Base.OneTo{Int64}}, Base.Slice{Base.OneTo{Int64}}}, true}\")"]` | 27.512 μs (50%) | 0.000 ns | 54.81 KiB (1%) | 501 |
| `["array", "index", "(\"sumvector\", \"SubArray{Float32, 2, Base.ReshapedArray{Float32, 2, SubArray{Float32, 3, Array{Float32, 3}, Tuple{Base.Slice{Base.OneTo{Int64}}, Base.Slice{Base.OneTo{Int64}}, Base.Slice{Base.OneTo{Int64}}}, true}, Tuple{}}, Tuple{Base.Slice{Base.OneTo{Int64}}, UnitRange{Int64}}, true}\")"]` | 16.873 μs (50%) | 0.000 ns | 54.81 KiB (1%) | 501 |
| `["array", "index", "(\"sumvector\", \"SubArray{Float32, 2, Base.ReshapedArray{Float32, 2, SubArray{Float32, 3, BaseBenchmarks.ArrayBenchmarks.ArrayLS{Float32, 3}, Tuple{Base.Slice{Base.OneTo{Int64}}, Base.Slice{Base.OneTo{Int64}}, Base.Slice{Base.OneTo{Int64}}}, false}, Tuple{Base.MultiplicativeInverses.SignedMultiplicativeInverse{Int64}, Base.MultiplicativeInverses.SignedMultiplicativeInverse{Int64}}}, Tuple{Base.Slice{Base.OneTo{Int64}}, UnitRange{Int64}}, false}\")"]` | 25.359 μs (50%) | 0.000 ns | 54.81 KiB (1%) | 501 |
| `["array", "index", "(\"sumvector\", \"SubArray{Float32, 2, BaseBenchmarks.ArrayBenchmarks.ArrayLS{Float32, 2}, Tuple{Base.Slice{Base.OneTo{Int64}}, Base.Slice{Base.OneTo{Int64}}}, false}\")"]` | 34.009 μs (50%) | 0.000 ns | 54.81 KiB (1%) | 501 |
| `["array", "index", "(\"sumvector\", \"SubArray{Float32, 2, BaseBenchmarks.ArrayBenchmarks.ArrayLS{Float32, 3}, Tuple{Int64, Base.Slice{Base.OneTo{Int64}}, Base.Slice{Base.OneTo{Int64}}}, false}\")"]` | 27.106 μs (50%) | 0.000 ns | 54.70 KiB (1%) | 500 |
| `["array", "index", "(\"sumvector\", \"SubArray{Float32, 2, Matrix{Float32}, Tuple{Base.Slice{Base.OneTo{Int64}}, Base.Slice{Base.OneTo{Int64}}}, true}\")"]` | 20.480 μs (50%) | 0.000 ns | 54.81 KiB (1%) | 501 |
| `["array", "index", "(\"sumvector\", \"SubArray{Float32, 2, Matrix{Float32}, Tuple{UnitRange{Int64}, UnitRange{Int64}}, false}\")"]` | 20.609 μs (50%) | 0.000 ns | 54.81 KiB (1%) | 501 |
| `["array", "index", "(\"sumvector\", \"SubArray{Int32, 2, Array{Int32, 3}, Tuple{Int64, Base.Slice{Base.OneTo{Int64}}, Base.Slice{Base.OneTo{Int64}}}, true}\")"]` | 28.044 μs (50%) | 0.000 ns | 54.81 KiB (1%) | 501 |
| `["array", "index", "(\"sumvector\", \"SubArray{Int32, 2, Base.ReshapedArray{Int32, 2, SubArray{Int32, 3, Array{Int32, 3}, Tuple{Base.Slice{Base.OneTo{Int64}}, Base.Slice{Base.OneTo{Int64}}, Base.Slice{Base.OneTo{Int64}}}, true}, Tuple{}}, Tuple{Base.Slice{Base.OneTo{Int64}}, UnitRange{Int64}}, true}\")"]` | 16.903 μs (50%) | 0.000 ns | 54.81 KiB (1%) | 501 |
| `["array", "index", "(\"sumvector\", \"SubArray{Int32, 2, Base.ReshapedArray{Int32, 2, SubArray{Int32, 3, BaseBenchmarks.ArrayBenchmarks.ArrayLS{Int32, 3}, Tuple{Base.Slice{Base.OneTo{Int64}}, Base.Slice{Base.OneTo{Int64}}, Base.Slice{Base.OneTo{Int64}}}, false}, Tuple{Base.MultiplicativeInverses.SignedMultiplicativeInverse{Int64}, Base.MultiplicativeInverses.SignedMultiplicativeInverse{Int64}}}, Tuple{Base.Slice{Base.OneTo{Int64}}, UnitRange{Int64}}, false}\")"]` | 26.574 μs (50%) | 0.000 ns | 54.81 KiB (1%) | 501 |
| `["array", "index", "(\"sumvector\", \"SubArray{Int32, 2, BaseBenchmarks.ArrayBenchmarks.ArrayLS{Int32, 2}, Tuple{Base.Slice{Base.OneTo{Int64}}, Base.Slice{Base.OneTo{Int64}}}, false}\")"]` | 20.895 μs (50%) | 0.000 ns | 54.81 KiB (1%) | 501 |
| `["array", "index", "(\"sumvector\", \"SubArray{Int32, 2, BaseBenchmarks.ArrayBenchmarks.ArrayLS{Int32, 3}, Tuple{Int64, Base.Slice{Base.OneTo{Int64}}, Base.Slice{Base.OneTo{Int64}}}, false}\")"]` | 28.786 μs (50%) | 0.000 ns | 54.70 KiB (1%) | 500 |
| `["array", "index", "(\"sumvector\", \"SubArray{Int32, 2, Matrix{Int32}, Tuple{Base.Slice{Base.OneTo{Int64}}, Base.Slice{Base.OneTo{Int64}}}, true}\")"]` | 21.564 μs (50%) | 0.000 ns | 54.81 KiB (1%) | 501 |
| `["array", "index", "(\"sumvector\", \"SubArray{Int32, 2, Matrix{Int32}, Tuple{UnitRange{Int64}, UnitRange{Int64}}, false}\")"]` | 21.895 μs (50%) | 0.000 ns | 54.81 KiB (1%) | 501 |
| `["array", "index", "(\"sumvector_view\", \"1.0:0.00010001000100010001:2.0\")"]` | 89.000 ns (50%) | 0.000 ns | 128 bytes (1%) | 1 |
| `["array", "index", "(\"sumvector_view\", \"1.0:1.0:100000.0\")"]` | 86.000 ns (50%) | 0.000 ns | 128 bytes (1%) | 1 |
| `["array", "index", "(\"sumvector_view\", \"100000:-1:1\")"]` | 110.000 ns (50%) | 0.000 ns | 128 bytes (1%) | 1 |
| `["array", "index", "(\"sumvector_view\", \"1:100000\")"]` | 76.000 ns (50%) | 0.000 ns | 128 bytes (1%) | 1 |
| `["array", "index", "(\"sumvector_view\", \"Base.ReinterpretArray{BaseBenchmarks.ArrayBenchmarks.PairVals{Float32}, 2, Float32, Matrix{Float32}, false}\")"]` | 3.018 μs (50%) | 0.000 ns | 128 bytes (1%) | 1 |
| `["array", "index", "(\"sumvector_view\", \"Base.ReinterpretArray{BaseBenchmarks.ArrayBenchmarks.PairVals{Float32}, 2, Float64, Matrix{Float64}, false}\")"]` | 3.194 μs (50%) | 0.000 ns | 128 bytes (1%) | 1 |
| `["array", "index", "(\"sumvector_view\", \"Base.ReinterpretArray{BaseBenchmarks.ArrayBenchmarks.PairVals{Int32}, 2, Int32, Matrix{Int32}, false}\")"]` | 2.786 μs (50%) | 0.000 ns | 128 bytes (1%) | 1 |
| `["array", "index", "(\"sumvector_view\", \"Base.ReinterpretArray{BaseBenchmarks.ArrayBenchmarks.PairVals{Int32}, 2, Int64, Matrix{Int64}, false}\")"]` | 2.920 μs (50%) | 0.000 ns | 128 bytes (1%) | 1 |
| `["array", "index", "(\"sumvector_view\", \"Base.ReinterpretArray{Float32, 2, Int32, Matrix{Int32}, false}\")"]` | 1.282 μs (50%) | 0.000 ns | 128 bytes (1%) | 1 |
| `["array", "index", "(\"sumvector_view\", \"BaseBenchmarks.ArrayBenchmarks.ArrayLF{Float32, 2}\")"]` | 7.436 μs (50%) | 0.000 ns | 128 bytes (1%) | 1 |
| `["array", "index", "(\"sumvector_view\", \"BaseBenchmarks.ArrayBenchmarks.ArrayLF{Int32, 2}\")"]` | 7.428 μs (50%) | 0.000 ns | 128 bytes (1%) | 1 |
| `["array", "index", "(\"sumvector_view\", \"BaseBenchmarks.ArrayBenchmarks.ArrayLSLS{Float32, 2}\")"]` | 7.252 μs (50%) | 0.000 ns | 128 bytes (1%) | 1 |
| `["array", "index", "(\"sumvector_view\", \"BaseBenchmarks.ArrayBenchmarks.ArrayLSLS{Int32, 2}\")"]` | 7.120 μs (50%) | 0.000 ns | 128 bytes (1%) | 1 |
| `["array", "index", "(\"sumvector_view\", \"BaseBenchmarks.ArrayBenchmarks.ArrayLS{Float32, 2}\")"]` | 7.194 μs (50%) | 0.000 ns | 128 bytes (1%) | 1 |
| `["array", "index", "(\"sumvector_view\", \"BaseBenchmarks.ArrayBenchmarks.ArrayLS{Int32, 2}\")"]` | 7.126 μs (50%) | 0.000 ns | 128 bytes (1%) | 1 |
| `["array", "index", "(\"sumvector_view\", \"BitMatrix\")"]` | 4.223 μs (50%) | 0.000 ns | 128 bytes (1%) | 1 |
| `["array", "index", "(\"sumvector_view\", \"Matrix{Float32}\")"]` | 1.135 μs (50%) | 0.000 ns | 128 bytes (1%) | 1 |
| `["array", "index", "(\"sumvector_view\", \"Matrix{Float64}\")"]` | 854.000 ns (50%) | 0.000 ns | 128 bytes (1%) | 1 |
| `["array", "index", "(\"sumvector_view\", \"Matrix{Int32}\")"]` | 833.000 ns (50%) | 0.000 ns | 128 bytes (1%) | 1 |
| `["array", "index", "(\"sumvector_view\", \"Matrix{Int64}\")"]` | 846.000 ns (50%) | 0.000 ns | 128 bytes (1%) | 1 |
| `["array", "index", "(\"sumvector_view\", \"SubArray{Float32, 2, Array{Float32, 3}, Tuple{Int64, Base.Slice{Base.OneTo{Int64}}, Base.Slice{Base.OneTo{Int64}}}, true}\")"]` | 1.170 μs (50%) | 0.000 ns | 128 bytes (1%) | 1 |
| `["array", "index", "(\"sumvector_view\", \"SubArray{Float32, 2, Base.ReshapedArray{Float32, 2, SubArray{Float32, 3, Array{Float32, 3}, Tuple{Base.Slice{Base.OneTo{Int64}}, Base.Slice{Base.OneTo{Int64}}, Base.Slice{Base.OneTo{Int64}}}, true}, Tuple{}}, Tuple{Base.Slice{Base.OneTo{Int64}}, UnitRange{Int64}}, true}\")"]` | 965.000 ns (50%) | 0.000 ns | 128 bytes (1%) | 1 |
| `["array", "index", "(\"sumvector_view\", \"SubArray{Float32, 2, Base.ReshapedArray{Float32, 2, SubArray{Float32, 3, BaseBenchmarks.ArrayBenchmarks.ArrayLS{Float32, 3}, Tuple{Base.Slice{Base.OneTo{Int64}}, Base.Slice{Base.OneTo{Int64}}, Base.Slice{Base.OneTo{Int64}}}, false}, Tuple{Base.MultiplicativeInverses.SignedMultiplicativeInverse{Int64}, Base.MultiplicativeInverses.SignedMultiplicativeInverse{Int64}}}, Tuple{Base.Slice{Base.OneTo{Int64}}, UnitRange{Int64}}, false}\")"]` | 12.058 μs (50%) | 0.000 ns | 128 bytes (1%) | 1 |
| `["array", "index", "(\"sumvector_view\", \"SubArray{Float32, 2, BaseBenchmarks.ArrayBenchmarks.ArrayLS{Float32, 2}, Tuple{Base.Slice{Base.OneTo{Int64}}, Base.Slice{Base.OneTo{Int64}}}, false}\")"]` | 7.182 μs (50%) | 0.000 ns | 128 bytes (1%) | 1 |
| `["array", "index", "(\"sumvector_view\", \"SubArray{Float32, 2, BaseBenchmarks.ArrayBenchmarks.ArrayLS{Float32, 3}, Tuple{Int64, Base.Slice{Base.OneTo{Int64}}, Base.Slice{Base.OneTo{Int64}}}, false}\")"]` | 7.760 μs (50%) | 0.000 ns | 128 bytes (1%) | 1 |
| `["array", "index", "(\"sumvector_view\", \"SubArray{Float32, 2, Matrix{Float32}, Tuple{Base.Slice{Base.OneTo{Int64}}, Base.Slice{Base.OneTo{Int64}}}, true}\")"]` | 1.019 μs (50%) | 0.000 ns | 128 bytes (1%) | 1 |
| `["array", "index", "(\"sumvector_view\", \"SubArray{Float32, 2, Matrix{Float32}, Tuple{UnitRange{Int64}, UnitRange{Int64}}, false}\")"]` | 20.333 μs (50%) | 0.000 ns | 62.63 KiB (1%) | 501 |
| `["array", "index", "(\"sumvector_view\", \"SubArray{Int32, 2, Array{Int32, 3}, Tuple{Int64, Base.Slice{Base.OneTo{Int64}}, Base.Slice{Base.OneTo{Int64}}}, true}\")"]` | 1.146 μs (50%) | 0.000 ns | 128 bytes (1%) | 1 |
| `["array", "index", "(\"sumvector_view\", \"SubArray{Int32, 2, Base.ReshapedArray{Int32, 2, SubArray{Int32, 3, Array{Int32, 3}, Tuple{Base.Slice{Base.OneTo{Int64}}, Base.Slice{Base.OneTo{Int64}}, Base.Slice{Base.OneTo{Int64}}}, true}, Tuple{}}, Tuple{Base.Slice{Base.OneTo{Int64}}, UnitRange{Int64}}, true}\")"]` | 818.000 ns (50%) | 0.000 ns | 128 bytes (1%) | 1 |
| `["array", "index", "(\"sumvector_view\", \"SubArray{Int32, 2, Base.ReshapedArray{Int32, 2, SubArray{Int32, 3, BaseBenchmarks.ArrayBenchmarks.ArrayLS{Int32, 3}, Tuple{Base.Slice{Base.OneTo{Int64}}, Base.Slice{Base.OneTo{Int64}}, Base.Slice{Base.OneTo{Int64}}}, false}, Tuple{Base.MultiplicativeInverses.SignedMultiplicativeInverse{Int64}, Base.MultiplicativeInverses.SignedMultiplicativeInverse{Int64}}}, Tuple{Base.Slice{Base.OneTo{Int64}}, UnitRange{Int64}}, false}\")"]` | 11.974 μs (50%) | 0.000 ns | 128 bytes (1%) | 1 |
| `["array", "index", "(\"sumvector_view\", \"SubArray{Int32, 2, BaseBenchmarks.ArrayBenchmarks.ArrayLS{Int32, 2}, Tuple{Base.Slice{Base.OneTo{Int64}}, Base.Slice{Base.OneTo{Int64}}}, false}\")"]` | 7.213 μs (50%) | 0.000 ns | 128 bytes (1%) | 1 |
| `["array", "index", "(\"sumvector_view\", \"SubArray{Int32, 2, BaseBenchmarks.ArrayBenchmarks.ArrayLS{Int32, 3}, Tuple{Int64, Base.Slice{Base.OneTo{Int64}}, Base.Slice{Base.OneTo{Int64}}}, false}\")"]` | 7.599 μs (50%) | 0.000 ns | 128 bytes (1%) | 1 |
| `["array", "index", "(\"sumvector_view\", \"SubArray{Int32, 2, Matrix{Int32}, Tuple{Base.Slice{Base.OneTo{Int64}}, Base.Slice{Base.OneTo{Int64}}}, true}\")"]` | 990.000 ns (50%) | 0.000 ns | 128 bytes (1%) | 1 |
| `["array", "index", "(\"sumvector_view\", \"SubArray{Int32, 2, Matrix{Int32}, Tuple{UnitRange{Int64}, UnitRange{Int64}}, false}\")"]` | 20.627 μs (50%) | 0.000 ns | 62.63 KiB (1%) | 501 |
| `["array", "index", "2d"]` | 79.471 μs (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "3d"]` | 94.322 μs (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "4d"]` | 109.179 μs (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "5d"]` | 155.451 μs (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "6d"]` | 155.469 μs (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "7d"]` | 3.985 μs (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "ind2sub"]` | 735.428 μs (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "index", "sub2ind"]` | 595.565 ms (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "reductions", "(\"maxabs\", \"Float64\")"]` | 1.278 μs (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "reductions", "(\"maxabs\", \"Int64\")"]` | 330.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "reductions", "(\"mean\", \"Float64\")"]` | 125.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "reductions", "(\"mean\", \"Int64\")"]` | 126.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "reductions", "(\"norm1\", \"Float64\")"]` | 114.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "reductions", "(\"norm1\", \"Int64\")"]` | 1.198 μs (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "reductions", "(\"norm\", \"Float64\")"]` | 404.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "reductions", "(\"norm\", \"Int64\")"]` | 2.952 μs (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "reductions", "(\"norminf\", \"Float64\")"]` | 1.786 μs (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "reductions", "(\"norminf\", \"Int64\")"]` | 1.787 μs (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "reductions", "(\"perf_mapreduce\", \"Float64\")"]` | 1.198 μs (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "reductions", "(\"perf_mapreduce\", \"Int64\")"]` | 101.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "reductions", "(\"perf_reduce\", \"Float64\")"]` | 1.198 μs (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "reductions", "(\"perf_reduce\", \"Int64\")"]` | 102.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "reductions", "(\"sum\", \"Float64\")"]` | 119.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "reductions", "(\"sum\", \"Int64\")"]` | 104.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "reductions", "(\"sumabs2\", \"Float64\")"]` | 120.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "reductions", "(\"sumabs2\", \"Int64\")"]` | 182.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "reductions", "(\"sumabs\", \"Float64\")"]` | 122.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "reductions", "(\"sumabs\", \"Int64\")"]` | 108.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "reverse", "rev_load_fast!"]` | 789.705 μs (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "reverse", "rev_load_slow!"]` | 1.400 ms (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "reverse", "rev_loadmul_fast!"]` | 2.957 ms (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "reverse", "rev_loadmul_slow!"]` | 2.946 ms (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "setindex!", "(\"setindex!\", 1)"]` | 26.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "setindex!", "(\"setindex!\", 2)"]` | 26.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "setindex!", "(\"setindex!\", 3)"]` | 25.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "setindex!", "(\"setindex!\", 4)"]` | 26.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "setindex!", "(\"setindex!\", 5)"]` | 26.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "subarray", "(\"gramschmidt!\", 100)"]` | 2.750 ms (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "subarray", "(\"gramschmidt!\", 1000)"]` | 3.326 s (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "subarray", "(\"gramschmidt!\", 250)"]` | 19.343 ms (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "subarray", "(\"gramschmidt!\", 500)"]` | 88.396 ms (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["array", "subarray", "(\"lucompletepivCopy!\", 100)"]` | 5.799 ms (5%) | 0.000 ns | 5.79 MiB (1%) | 914 |
| `["array", "subarray", "(\"lucompletepivCopy!\", 1000)"]` | 5.884 s (5%) | 68.410 ms | 5.03 GiB (1%) | 9914 |
| `["array", "subarray", "(\"lucompletepivCopy!\", 250)"]` | 87.770 ms (5%) | 0.000 ns | 83.51 MiB (1%) | 2414 |
| `["array", "subarray", "(\"lucompletepivCopy!\", 500)"]` | 704.051 ms (5%) | 0.000 ns | 651.45 MiB (1%) | 4914 |
| `["array", "subarray", "(\"lucompletepivSub!\", 100)"]` | 5.475 ms (5%) | 0.000 ns | 3.14 MiB (1%) | 953 |
| `["array", "subarray", "(\"lucompletepivSub!\", 1000)"]` | 5.183 s (5%) | 22.799 ms | 2.53 GiB (1%) | 9953 |
| `["array", "subarray", "(\"lucompletepivSub!\", 250)"]` | 81.123 ms (5%) | 0.000 ns | 43.07 MiB (1%) | 2453 |
| `["array", "subarray", "(\"lucompletepivSub!\", 500)"]` | 646.147 ms (5%) | 0.000 ns | 330.72 MiB (1%) | 4953 |
| `["broadcast", "26942"]` | 182.757 ns (5%) | 0.000 ns | 544 bytes (1%) | 1 |
| `["broadcast", "dotop", "(\"Float64\", (1000, 1000), 2)"]` | 1.880 ms (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["broadcast", "dotop", "(\"Float64\", (1000000,), 1)"]` | 2.065 ms (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["broadcast", "dotop", "(\"Float64\", (1000000,), 2)"]` | 628.462 μs (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["broadcast", "fusion", "(\"Float64\", (1000, 1000), 2)"]` | 932.292 μs (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["broadcast", "fusion", "(\"Float64\", (1000, 1000), 3)"]` | 1.823 ms (5%) | 0.000 ns | 96 bytes (1%) | 3 |
| `["broadcast", "fusion", "(\"Float64\", (1000000,), 1)"]` | 939.430 μs (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["broadcast", "fusion", "(\"Float64\", (1000000,), 2)"]` | 923.571 μs (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["broadcast", "mix_scalar_tuple", "(10, \"scal_tup\")"]` | 23.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["broadcast", "mix_scalar_tuple", "(10, \"scal_tup_x3\")"]` | 27.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["broadcast", "mix_scalar_tuple", "(10, \"tup_tup\")"]` | 24.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["broadcast", "mix_scalar_tuple", "(3, \"scal_tup\")"]` | 23.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["broadcast", "mix_scalar_tuple", "(3, \"scal_tup_x3\")"]` | 26.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["broadcast", "mix_scalar_tuple", "(3, \"tup_tup\")"]` | 23.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["broadcast", "mix_scalar_tuple", "(5, \"scal_tup\")"]` | 23.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["broadcast", "mix_scalar_tuple", "(5, \"scal_tup_x3\")"]` | 27.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["broadcast", "mix_scalar_tuple", "(5, \"tup_tup\")"]` | 24.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["broadcast", "sparse", "((1000, 1000), 1)"]` | 7.282 μs (5%) | 0.000 ns | 24.50 KiB (1%) | 3 |
| `["broadcast", "sparse", "((1000, 1000), 2)"]` | 14.863 μs (5%) | 0.000 ns | 40.66 KiB (1%) | 5 |
| `["broadcast", "sparse", "((10000000,), 1)"]` | 21.891 μs (5%) | 0.000 ns | 156.66 KiB (1%) | 4 |
| `["broadcast", "sparse", "((10000000,), 2)"]` | 31.933 μs (5%) | 0.000 ns | 313.16 KiB (1%) | 4 |
| `["broadcast", "typeargs", "(\"array\", 10)"]` | 66.000 ns (5%) | 0.000 ns | 160 bytes (1%) | 1 |
| `["broadcast", "typeargs", "(\"array\", 3)"]` | 58.000 ns (5%) | 0.000 ns | 112 bytes (1%) | 1 |
| `["broadcast", "typeargs", "(\"array\", 5)"]` | 60.000 ns (5%) | 0.000 ns | 128 bytes (1%) | 1 |
| `["broadcast", "typeargs", "(\"tuple\", 10)"]` | 23.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["broadcast", "typeargs", "(\"tuple\", 3)"]` | 23.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["broadcast", "typeargs", "(\"tuple\", 5)"]` | 23.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["collection", "deletion", "(\"BitSet\", \"Int\", \"pop!\")"]` | 9.487 μs (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["collection", "deletion", "(\"Dict\", \"Any\", \"pop!\")"]` | 175.249 μs (25%) | 0.000 ns | 27.94 KiB (1%) | 894 |
| `["collection", "deletion", "(\"Dict\", \"Int\", \"pop!\")"]` | 5.210 μs (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["collection", "deletion", "(\"Dict\", \"String\", \"pop!\")"]` | 12.900 μs (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["collection", "deletion", "(\"IdDict\", \"Any\", \"filter!\")"]` | 25.643 μs (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["collection", "deletion", "(\"IdDict\", \"Any\", \"filter\")"]` | 37.562 μs (25%) | 0.000 ns | 24.48 KiB (1%) | 7 |
| `["collection", "deletion", "(\"IdDict\", \"Int\", \"filter!\")"]` | 13.254 μs (25%) | 0.000 ns | 2.36 KiB (1%) | 151 |
| `["collection", "deletion", "(\"IdDict\", \"Int\", \"filter\")"]` | 34.900 μs (25%) | 0.000 ns | 29.70 KiB (1%) | 341 |
| `["collection", "deletion", "(\"IdDict\", \"String\", \"filter!\")"]` | 28.936 μs (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["collection", "deletion", "(\"IdDict\", \"String\", \"filter\")"]` | 65.367 μs (25%) | 0.000 ns | 24.48 KiB (1%) | 7 |
| `["collection", "deletion", "(\"Set\", \"Any\", \"filter!\")"]` | 33.887 μs (25%) | 0.000 ns | 7.81 KiB (1%) | 500 |
| `["collection", "deletion", "(\"Set\", \"Any\", \"filter\")"]` | 44.973 μs (25%) | 0.000 ns | 27.97 KiB (1%) | 957 |
| `["collection", "deletion", "(\"Set\", \"Any\", \"pop!\")"]` | 114.817 μs (25%) | 0.000 ns | 13.97 KiB (1%) | 894 |
| `["collection", "deletion", "(\"Set\", \"Int\", \"filter!\")"]` | 4.212 μs (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["collection", "deletion", "(\"Set\", \"Int\", \"filter\")"]` | 6.953 μs (25%) | 0.000 ns | 13.22 KiB (1%) | 13 |
| `["collection", "deletion", "(\"Set\", \"Int\", \"pop!\")"]` | 4.785 μs (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["collection", "deletion", "(\"Set\", \"String\", \"filter!\")"]` | 22.212 μs (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["collection", "deletion", "(\"Set\", \"String\", \"filter\")"]` | 39.271 μs (25%) | 0.000 ns | 13.22 KiB (1%) | 13 |
| `["collection", "deletion", "(\"Set\", \"String\", \"pop!\")"]` | 11.428 μs (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["collection", "deletion", "(\"Vector\", \"Any\", \"filter!\")"]` | 1.809 μs (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["collection", "deletion", "(\"Vector\", \"Any\", \"filter\")"]` | 2.490 μs (25%) | 0.000 ns | 7.94 KiB (1%) | 1 |
| `["collection", "deletion", "(\"Vector\", \"Any\", \"pop!\")"]` | 2.975 μs (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["collection", "deletion", "(\"Vector\", \"Int\", \"filter!\")"]` | 630.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["collection", "deletion", "(\"Vector\", \"Int\", \"filter\")"]` | 826.000 ns (25%) | 0.000 ns | 7.94 KiB (1%) | 1 |
| `["collection", "deletion", "(\"Vector\", \"Int\", \"pop!\")"]` | 4.148 μs (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["collection", "deletion", "(\"Vector\", \"String\", \"filter!\")"]` | 3.738 μs (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["collection", "deletion", "(\"Vector\", \"String\", \"filter\")"]` | 5.431 μs (25%) | 0.000 ns | 7.94 KiB (1%) | 1 |
| `["collection", "deletion", "(\"Vector\", \"String\", \"pop!\")"]` | 2.975 μs (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["collection", "initialization", "(\"BitSet\", \"Int\", \"sorted\", \"iterator\")"]` | 2.177 μs (25%) | 0.000 ns | 384 bytes (1%) | 5 |
| `["collection", "initialization", "(\"BitSet\", \"Int\", \"sorted\", \"loop\")"]` | 2.083 μs (25%) | 0.000 ns | 384 bytes (1%) | 5 |
| `["collection", "initialization", "(\"BitSet\", \"Int\", \"sorted\", \"loop\", \"sizehint!\")"]` | 2.074 μs (25%) | 0.000 ns | 304 bytes (1%) | 4 |
| `["collection", "initialization", "(\"BitSet\", \"Int\", \"unsorted\", \"iterator\")"]` | 1.952 μs (25%) | 0.000 ns | 512 bytes (1%) | 5 |
| `["collection", "initialization", "(\"BitSet\", \"Int\", \"unsorted\", \"loop\")"]` | 1.806 μs (25%) | 0.000 ns | 512 bytes (1%) | 5 |
| `["collection", "initialization", "(\"BitSet\", \"Int\", \"unsorted\", \"loop\", \"sizehint!\")"]` | 1.817 μs (25%) | 0.000 ns | 576 bytes (1%) | 5 |
| `["collection", "initialization", "(\"Dict\", \"Any\", \"iterator\")"]` | 178.669 μs (25%) | 0.000 ns | 132.36 KiB (1%) | 2513 |
| `["collection", "initialization", "(\"Dict\", \"Any\", \"loop\")"]` | 150.272 μs (25%) | 0.000 ns | 123.39 KiB (1%) | 2007 |
| `["collection", "initialization", "(\"Dict\", \"Any\", \"loop\", \"sizehint!\")"]` | 78.107 μs (25%) | 0.000 ns | 43.67 KiB (1%) | 572 |
| `["collection", "initialization", "(\"Dict\", \"Int\", \"iterator\")"]` | 15.522 μs (25%) | 0.000 ns | 34.84 KiB (1%) | 7 |
| `["collection", "initialization", "(\"Dict\", \"Int\", \"loop\")"]` | 25.305 μs (25%) | 0.000 ns | 92.31 KiB (1%) | 18 |
| `["collection", "initialization", "(\"Dict\", \"Int\", \"loop\", \"sizehint!\")"]` | 15.422 μs (25%) | 0.000 ns | 34.84 KiB (1%) | 7 |
| `["collection", "initialization", "(\"Dict\", \"String\", \"iterator\")"]` | 45.053 μs (25%) | 0.000 ns | 34.84 KiB (1%) | 7 |
| `["collection", "initialization", "(\"Dict\", \"String\", \"loop\")"]` | 80.805 μs (25%) | 0.000 ns | 92.31 KiB (1%) | 18 |
| `["collection", "initialization", "(\"Dict\", \"String\", \"loop\", \"sizehint!\")"]` | 44.985 μs (25%) | 0.000 ns | 34.84 KiB (1%) | 7 |
| `["collection", "initialization", "(\"IdDict\", \"Any\", \"iterator\")"]` | 126.807 μs (25%) | 0.000 ns | 97.09 KiB (1%) | 513 |
| `["collection", "initialization", "(\"IdDict\", \"Any\", \"loop\")"]` | 129.621 μs (25%) | 0.000 ns | 96.34 KiB (1%) | 507 |
| `["collection", "initialization", "(\"IdDict\", \"Any\", \"loop\", \"sizehint!\")"]` | 107.335 μs (25%) | 0.000 ns | 88.34 KiB (1%) | 503 |
| `["collection", "initialization", "(\"IdDict\", \"Int\", \"iterator\")"]` | 75.855 μs (25%) | 0.000 ns | 40.14 KiB (1%) | 1009 |
| `["collection", "initialization", "(\"IdDict\", \"Int\", \"loop\")"]` | 69.002 μs (25%) | 0.000 ns | 40.14 KiB (1%) | 1009 |
| `["collection", "initialization", "(\"IdDict\", \"Int\", \"loop\", \"sizehint!\")"]` | 56.127 μs (25%) | 0.000 ns | 32.14 KiB (1%) | 1005 |
| `["collection", "initialization", "(\"IdDict\", \"String\", \"iterator\")"]` | 98.655 μs (25%) | 0.000 ns | 88.56 KiB (1%) | 9 |
| `["collection", "initialization", "(\"IdDict\", \"String\", \"loop\")"]` | 94.516 μs (25%) | 0.000 ns | 88.56 KiB (1%) | 9 |
| `["collection", "initialization", "(\"IdDict\", \"String\", \"loop\", \"sizehint!\")"]` | 75.325 μs (25%) | 0.000 ns | 80.56 KiB (1%) | 5 |
| `["collection", "initialization", "(\"Set\", \"Any\", \"iterator\")"]` | 73.508 μs (25%) | 0.000 ns | 39.23 KiB (1%) | 1323 |
| `["collection", "initialization", "(\"Set\", \"Any\", \"loop\")"]` | 140.872 μs (25%) | 0.000 ns | 92.38 KiB (1%) | 2757 |
| `["collection", "initialization", "(\"Set\", \"Any\", \"loop\", \"sizehint!\")"]` | 73.165 μs (25%) | 0.000 ns | 39.23 KiB (1%) | 1323 |
| `["collection", "initialization", "(\"Set\", \"Int\", \"iterator\")"]` | 14.303 μs (25%) | 0.000 ns | 18.66 KiB (1%) | 7 |
| `["collection", "initialization", "(\"Set\", \"Int\", \"loop\")"]` | 20.473 μs (25%) | 0.000 ns | 49.56 KiB (1%) | 17 |
| `["collection", "initialization", "(\"Set\", \"Int\", \"loop\", \"sizehint!\")"]` | 13.893 μs (25%) | 0.000 ns | 18.66 KiB (1%) | 7 |
| `["collection", "initialization", "(\"Set\", \"String\", \"iterator\")"]` | 43.903 μs (25%) | 0.000 ns | 18.66 KiB (1%) | 7 |
| `["collection", "initialization", "(\"Set\", \"String\", \"loop\")"]` | 76.001 μs (25%) | 0.000 ns | 49.56 KiB (1%) | 17 |
| `["collection", "initialization", "(\"Set\", \"String\", \"loop\", \"sizehint!\")"]` | 43.683 μs (25%) | 0.000 ns | 18.66 KiB (1%) | 7 |
| `["collection", "initialization", "(\"Vector\", \"Any\", \"iterator\")"]` | 1.769 μs (25%) | 0.000 ns | 7.94 KiB (1%) | 1 |
| `["collection", "initialization", "(\"Vector\", \"Any\", \"loop\")"]` | 9.355 μs (25%) | 0.000 ns | 16.39 KiB (1%) | 10 |
| `["collection", "initialization", "(\"Vector\", \"Any\", \"loop\", \"sizehint!\")"]` | 8.871 μs (25%) | 0.000 ns | 7.95 KiB (1%) | 2 |
| `["collection", "initialization", "(\"Vector\", \"Int\", \"iterator\")"]` | 1.105 μs (25%) | 0.000 ns | 7.94 KiB (1%) | 1 |
| `["collection", "initialization", "(\"Vector\", \"Int\", \"loop\")"]` | 7.687 μs (25%) | 0.000 ns | 16.39 KiB (1%) | 10 |
| `["collection", "initialization", "(\"Vector\", \"Int\", \"loop\", \"sizehint!\")"]` | 6.324 μs (25%) | 0.000 ns | 7.95 KiB (1%) | 2 |
| `["collection", "initialization", "(\"Vector\", \"String\", \"iterator\")"]` | 1.641 μs (25%) | 0.000 ns | 7.94 KiB (1%) | 1 |
| `["collection", "initialization", "(\"Vector\", \"String\", \"loop\")"]` | 9.405 μs (25%) | 0.000 ns | 16.39 KiB (1%) | 10 |
| `["collection", "initialization", "(\"Vector\", \"String\", \"loop\", \"sizehint!\")"]` | 9.026 μs (25%) | 0.000 ns | 7.95 KiB (1%) | 2 |
| `["collection", "iteration", "(\"BitSet\", \"Int\", \"iterate second\")"]` | 25.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["collection", "iteration", "(\"BitSet\", \"Int\", \"iterate\")"]` | 30.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["collection", "iteration", "(\"Dict\", \"Any\", \"iterate second\")"]` | 34.000 ns (25%) | 0.000 ns | 32 bytes (1%) | 1 |
| `["collection", "iteration", "(\"Dict\", \"Any\", \"iterate\")"]` | 35.000 ns (25%) | 0.000 ns | 32 bytes (1%) | 1 |
| `["collection", "iteration", "(\"Dict\", \"Int\", \"iterate second\")"]` | 38.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["collection", "iteration", "(\"Dict\", \"Int\", \"iterate\")"]` | 31.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["collection", "iteration", "(\"Dict\", \"String\", \"iterate second\")"]` | 38.000 ns (25%) | 0.000 ns | 32 bytes (1%) | 1 |
| `["collection", "iteration", "(\"Dict\", \"String\", \"iterate\")"]` | 40.000 ns (25%) | 0.000 ns | 32 bytes (1%) | 1 |
| `["collection", "iteration", "(\"IdDict\", \"Any\", \"iterate second\")"]` | 41.000 ns (25%) | 0.000 ns | 32 bytes (1%) | 1 |
| `["collection", "iteration", "(\"IdDict\", \"Any\", \"iterate\")"]` | 40.000 ns (25%) | 0.000 ns | 32 bytes (1%) | 1 |
| `["collection", "iteration", "(\"IdDict\", \"Int\", \"iterate second\")"]` | 37.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["collection", "iteration", "(\"IdDict\", \"Int\", \"iterate\")"]` | 36.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["collection", "iteration", "(\"IdDict\", \"String\", \"iterate second\")"]` | 39.000 ns (25%) | 0.000 ns | 32 bytes (1%) | 1 |
| `["collection", "iteration", "(\"IdDict\", \"String\", \"iterate\")"]` | 40.000 ns (25%) | 0.000 ns | 32 bytes (1%) | 1 |
| `["collection", "iteration", "(\"Set\", \"Any\", \"iterate second\")"]` | 96.000 ns (25%) | 0.000 ns | 32 bytes (1%) | 1 |
| `["collection", "iteration", "(\"Set\", \"Any\", \"iterate\")"]` | 96.000 ns (25%) | 0.000 ns | 32 bytes (1%) | 1 |
| `["collection", "iteration", "(\"Set\", \"Int\", \"iterate second\")"]` | 40.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["collection", "iteration", "(\"Set\", \"Int\", \"iterate\")"]` | 37.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["collection", "iteration", "(\"Set\", \"String\", \"iterate second\")"]` | 40.000 ns (25%) | 0.000 ns | 32 bytes (1%) | 1 |
| `["collection", "iteration", "(\"Set\", \"String\", \"iterate\")"]` | 38.000 ns (25%) | 0.000 ns | 32 bytes (1%) | 1 |
| `["collection", "iteration", "(\"Vector\", \"Any\", \"iterate second\")"]` | 88.000 ns (25%) | 0.000 ns | 32 bytes (1%) | 1 |
| `["collection", "iteration", "(\"Vector\", \"Any\", \"iterate\")"]` | 86.000 ns (25%) | 0.000 ns | 32 bytes (1%) | 1 |
| `["collection", "iteration", "(\"Vector\", \"Int\", \"iterate second\")"]` | 26.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["collection", "iteration", "(\"Vector\", \"Int\", \"iterate\")"]` | 25.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["collection", "iteration", "(\"Vector\", \"String\", \"iterate second\")"]` | 37.000 ns (25%) | 0.000 ns | 32 bytes (1%) | 1 |
| `["collection", "iteration", "(\"Vector\", \"String\", \"iterate\")"]` | 31.000 ns (25%) | 0.000 ns | 32 bytes (1%) | 1 |
| `["collection", "optimizations", "(\"BitSet\", \"Int8\")"]` | 177.991 μs (25%) | 0.000 ns | 160 bytes (1%) | 3 |
| `["collection", "optimizations", "(\"BitSet\", \"UInt16\")"]` | 166.172 μs (25%) | 0.000 ns | 28.34 KiB (1%) | 6 |
| `["collection", "optimizations", "(\"Dict\", \"abstract\", \"Bool\")"]` | 652.507 μs (25%) | 0.000 ns | 416 bytes (1%) | 4 |
| `["collection", "optimizations", "(\"Dict\", \"abstract\", \"Int8\")"]` | 941.815 μs (25%) | 0.000 ns | 2.00 KiB (1%) | 7 |
| `["collection", "optimizations", "(\"Dict\", \"abstract\", \"Nothing\")"]` | 970.844 μs (25%) | 0.000 ns | 352 bytes (1%) | 4 |
| `["collection", "optimizations", "(\"Dict\", \"abstract\", \"UInt16\")"]` | 1.996 ms (25%) | 0.000 ns | 640.66 KiB (1%) | 7 |
| `["collection", "optimizations", "(\"Dict\", \"concrete\", \"Bool\")"]` | 652.850 μs (25%) | 0.000 ns | 416 bytes (1%) | 4 |
| `["collection", "optimizations", "(\"Dict\", \"concrete\", \"Int8\")"]` | 941.818 μs (25%) | 0.000 ns | 2.00 KiB (1%) | 7 |
| `["collection", "optimizations", "(\"Dict\", \"concrete\", \"Nothing\")"]` | 970.780 μs (25%) | 0.000 ns | 352 bytes (1%) | 4 |
| `["collection", "optimizations", "(\"Dict\", \"concrete\", \"UInt16\")"]` | 1.987 ms (25%) | 0.000 ns | 640.66 KiB (1%) | 7 |
| `["collection", "optimizations", "(\"IdDict\", \"abstract\", \"Bool\")"]` | 2.956 ms (25%) | 0.000 ns | 368 bytes (1%) | 2 |
| `["collection", "optimizations", "(\"IdDict\", \"abstract\", \"Int8\")"]` | 4.079 ms (25%) | 0.000 ns | 8.36 KiB (1%) | 6 |
| `["collection", "optimizations", "(\"IdDict\", \"abstract\", \"Nothing\")"]` | 2.320 ms (25%) | 0.000 ns | 368 bytes (1%) | 2 |
| `["collection", "optimizations", "(\"IdDict\", \"abstract\", \"UInt16\")"]` | 10.532 ms (25%) | 0.000 ns | 4.34 MiB (1%) | 196925 |
| `["collection", "optimizations", "(\"IdDict\", \"concrete\", \"Bool\")"]` | 2.956 ms (25%) | 0.000 ns | 368 bytes (1%) | 2 |
| `["collection", "optimizations", "(\"IdDict\", \"concrete\", \"Int8\")"]` | 4.069 ms (25%) | 0.000 ns | 8.36 KiB (1%) | 6 |
| `["collection", "optimizations", "(\"IdDict\", \"concrete\", \"Nothing\")"]` | 2.310 ms (25%) | 0.000 ns | 368 bytes (1%) | 2 |
| `["collection", "optimizations", "(\"IdDict\", \"concrete\", \"UInt16\")"]` | 10.581 ms (25%) | 0.000 ns | 4.34 MiB (1%) | 196925 |
| `["collection", "optimizations", "(\"Set\", \"abstract\", \"Bool\")"]` | 618.690 μs (25%) | 0.000 ns | 384 bytes (1%) | 4 |
| `["collection", "optimizations", "(\"Set\", \"abstract\", \"Int8\")"]` | 958.984 μs (25%) | 0.000 ns | 1.45 KiB (1%) | 7 |
| `["collection", "optimizations", "(\"Set\", \"abstract\", \"Nothing\")"]` | 124.000 ns (25%) | 0.000 ns | 352 bytes (1%) | 4 |
| `["collection", "optimizations", "(\"Set\", \"abstract\", \"UInt16\")"]` | 1.867 ms (25%) | 0.000 ns | 384.57 KiB (1%) | 7 |
| `["collection", "optimizations", "(\"Set\", \"concrete\", \"Bool\")"]` | 618.680 μs (25%) | 0.000 ns | 384 bytes (1%) | 4 |
| `["collection", "optimizations", "(\"Set\", \"concrete\", \"Int8\")"]` | 958.328 μs (25%) | 0.000 ns | 1.45 KiB (1%) | 7 |
| `["collection", "optimizations", "(\"Set\", \"concrete\", \"Nothing\")"]` | 125.000 ns (25%) | 0.000 ns | 352 bytes (1%) | 4 |
| `["collection", "optimizations", "(\"Set\", \"concrete\", \"UInt16\")"]` | 1.864 ms (25%) | 0.000 ns | 384.57 KiB (1%) | 7 |
| `["collection", "optimizations", "(\"Vector\", \"abstract\", \"Nothing\")"]` | 57.000 ns (25%) | 0.000 ns | 80 bytes (1%) | 1 |
| `["collection", "optimizations", "(\"Vector\", \"concrete\", \"Nothing\")"]` | 57.000 ns (25%) | 0.000 ns | 80 bytes (1%) | 1 |
| `["collection", "queries & updates", "(\"BitSet\", \"Int\", \"first\")"]` | 32.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["collection", "queries & updates", "(\"BitSet\", \"Int\", \"in\", \"false\")"]` | 24.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["collection", "queries & updates", "(\"BitSet\", \"Int\", \"in\", \"true\")"]` | 25.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["collection", "queries & updates", "(\"BitSet\", \"Int\", \"last\")"]` | 29.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["collection", "queries & updates", "(\"BitSet\", \"Int\", \"length\")"]` | 30.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["collection", "queries & updates", "(\"BitSet\", \"Int\", \"pop!\", \"specified\")"]` | 28.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["collection", "queries & updates", "(\"BitSet\", \"Int\", \"pop!\", \"unspecified\")"]` | 37.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["collection", "queries & updates", "(\"BitSet\", \"Int\", \"push!\", \"new\")"]` | 28.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["collection", "queries & updates", "(\"BitSet\", \"Int\", \"push!\", \"overwrite\")"]` | 28.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["collection", "queries & updates", "(\"Dict\", \"Any\", \"getindex\")"]` | 38.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["collection", "queries & updates", "(\"Dict\", \"Any\", \"in\", \"false\")"]` | 61.000 ns (25%) | 0.000 ns | 16 bytes (1%) | 1 |
| `["collection", "queries & updates", "(\"Dict\", \"Any\", \"in\", \"true\")"]` | 58.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["collection", "queries & updates", "(\"Dict\", \"Any\", \"pop!\", \"specified\")"]` | 72.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["collection", "queries & updates", "(\"Dict\", \"Any\", \"pop!\", \"unspecified\")"]` | 294.000 ns (25%) | 0.000 ns | 32 bytes (1%) | 1 |
| `["collection", "queries & updates", "(\"Dict\", \"Any\", \"push!\", \"new\")"]` | 97.000 ns (25%) | 0.000 ns | 48 bytes (1%) | 3 |
| `["collection", "queries & updates", "(\"Dict\", \"Any\", \"push!\", \"overwrite\")"]` | 61.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["collection", "queries & updates", "(\"Dict\", \"Any\", \"setindex!\", \"new\")"]` | 103.000 ns (25%) | 0.000 ns | 48 bytes (1%) | 3 |
| `["collection", "queries & updates", "(\"Dict\", \"Any\", \"setindex!\", \"overwrite\")"]` | 68.000 ns (25%) | 0.000 ns | 16 bytes (1%) | 1 |
| `["collection", "queries & updates", "(\"Dict\", \"Int\", \"first\")"]` | 26.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["collection", "queries & updates", "(\"Dict\", \"Int\", \"getindex\")"]` | 29.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["collection", "queries & updates", "(\"Dict\", \"Int\", \"in\", \"false\")"]` | 28.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["collection", "queries & updates", "(\"Dict\", \"Int\", \"in\", \"true\")"]` | 28.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["collection", "queries & updates", "(\"Dict\", \"Int\", \"length\")"]` | 24.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["collection", "queries & updates", "(\"Dict\", \"Int\", \"pop!\", \"specified\")"]` | 54.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["collection", "queries & updates", "(\"Dict\", \"Int\", \"pop!\", \"unspecified\")"]` | 45.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["collection", "queries & updates", "(\"Dict\", \"Int\", \"push!\", \"new\")"]` | 39.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["collection", "queries & updates", "(\"Dict\", \"Int\", \"push!\", \"overwrite\")"]` | 46.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["collection", "queries & updates", "(\"Dict\", \"Int\", \"setindex!\", \"new\")"]` | 36.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["collection", "queries & updates", "(\"Dict\", \"Int\", \"setindex!\", \"overwrite\")"]` | 44.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["collection", "queries & updates", "(\"Dict\", \"String\", \"getindex\")"]` | 46.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["collection", "queries & updates", "(\"Dict\", \"String\", \"in\", \"false\")"]` | 49.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["collection", "queries & updates", "(\"Dict\", \"String\", \"in\", \"true\")"]` | 48.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["collection", "queries & updates", "(\"Dict\", \"String\", \"pop!\", \"specified\")"]` | 80.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["collection", "queries & updates", "(\"Dict\", \"String\", \"pop!\", \"unspecified\")"]` | 80.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["collection", "queries & updates", "(\"Dict\", \"String\", \"push!\", \"new\")"]` | 60.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["collection", "queries & updates", "(\"Dict\", \"String\", \"push!\", \"overwrite\")"]` | 59.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["collection", "queries & updates", "(\"Dict\", \"String\", \"setindex!\", \"new\")"]` | 61.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["collection", "queries & updates", "(\"Dict\", \"String\", \"setindex!\", \"overwrite\")"]` | 60.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["collection", "queries & updates", "(\"IdDict\", \"Any\", \"getindex\")"]` | 43.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["collection", "queries & updates", "(\"IdDict\", \"Any\", \"in\", \"false\")"]` | 56.000 ns (25%) | 0.000 ns | 16 bytes (1%) | 1 |
| `["collection", "queries & updates", "(\"IdDict\", \"Any\", \"in\", \"true\")"]` | 63.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["collection", "queries & updates", "(\"IdDict\", \"Any\", \"pop!\", \"specified\")"]` | 81.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["collection", "queries & updates", "(\"IdDict\", \"Any\", \"push!\", \"new\")"]` | 88.000 ns (25%) | 0.000 ns | 32 bytes (1%) | 2 |
| `["collection", "queries & updates", "(\"IdDict\", \"Any\", \"push!\", \"overwrite\")"]` | 64.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["collection", "queries & updates", "(\"IdDict\", \"Any\", \"setindex!\", \"new\")"]` | 87.000 ns (25%) | 0.000 ns | 32 bytes (1%) | 2 |
| `["collection", "queries & updates", "(\"IdDict\", \"Any\", \"setindex!\", \"overwrite\")"]` | 68.000 ns (25%) | 0.000 ns | 16 bytes (1%) | 1 |
| `["collection", "queries & updates", "(\"IdDict\", \"Int\", \"first\")"]` | 30.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["collection", "queries & updates", "(\"IdDict\", \"Int\", \"getindex\")"]` | 43.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["collection", "queries & updates", "(\"IdDict\", \"Int\", \"in\", \"false\")"]` | 52.000 ns (25%) | 0.000 ns | 16 bytes (1%) | 1 |
| `["collection", "queries & updates", "(\"IdDict\", \"Int\", \"in\", \"true\")"]` | 44.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["collection", "queries & updates", "(\"IdDict\", \"Int\", \"length\")"]` | 24.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["collection", "queries & updates", "(\"IdDict\", \"Int\", \"pop!\", \"specified\")"]` | 77.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["collection", "queries & updates", "(\"IdDict\", \"Int\", \"push!\", \"new\")"]` | 76.000 ns (25%) | 0.000 ns | 32 bytes (1%) | 2 |
| `["collection", "queries & updates", "(\"IdDict\", \"Int\", \"push!\", \"overwrite\")"]` | 58.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["collection", "queries & updates", "(\"IdDict\", \"Int\", \"setindex!\", \"new\")"]` | 76.000 ns (25%) | 0.000 ns | 32 bytes (1%) | 2 |
| `["collection", "queries & updates", "(\"IdDict\", \"Int\", \"setindex!\", \"overwrite\")"]` | 65.000 ns (25%) | 0.000 ns | 16 bytes (1%) | 1 |
| `["collection", "queries & updates", "(\"IdDict\", \"String\", \"getindex\")"]` | 48.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["collection", "queries & updates", "(\"IdDict\", \"String\", \"in\", \"false\")"]` | 49.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["collection", "queries & updates", "(\"IdDict\", \"String\", \"in\", \"true\")"]` | 48.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["collection", "queries & updates", "(\"IdDict\", \"String\", \"pop!\", \"specified\")"]` | 95.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["collection", "queries & updates", "(\"IdDict\", \"String\", \"push!\", \"new\")"]` | 74.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["collection", "queries & updates", "(\"IdDict\", \"String\", \"push!\", \"overwrite\")"]` | 66.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["collection", "queries & updates", "(\"IdDict\", \"String\", \"setindex!\", \"new\")"]` | 74.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["collection", "queries & updates", "(\"IdDict\", \"String\", \"setindex!\", \"overwrite\")"]` | 63.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["collection", "queries & updates", "(\"Set\", \"Any\", \"in\", \"false\")"]` | 54.000 ns (25%) | 0.000 ns | 16 bytes (1%) | 1 |
| `["collection", "queries & updates", "(\"Set\", \"Any\", \"in\", \"true\")"]` | 33.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["collection", "queries & updates", "(\"Set\", \"Any\", \"pop!\", \"specified\")"]` | 52.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["collection", "queries & updates", "(\"Set\", \"Any\", \"pop!\", \"unspecified\")"]` | 294.000 ns (25%) | 0.000 ns | 32 bytes (1%) | 2 |
| `["collection", "queries & updates", "(\"Set\", \"Any\", \"push!\", \"new\")"]` | 77.000 ns (25%) | 0.000 ns | 32 bytes (1%) | 2 |
| `["collection", "queries & updates", "(\"Set\", \"Any\", \"push!\", \"overwrite\")"]` | 41.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["collection", "queries & updates", "(\"Set\", \"Int\", \"first\")"]` | 28.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["collection", "queries & updates", "(\"Set\", \"Int\", \"in\", \"false\")"]` | 28.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["collection", "queries & updates", "(\"Set\", \"Int\", \"in\", \"true\")"]` | 28.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["collection", "queries & updates", "(\"Set\", \"Int\", \"length\")"]` | 24.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["collection", "queries & updates", "(\"Set\", \"Int\", \"pop!\", \"specified\")"]` | 37.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["collection", "queries & updates", "(\"Set\", \"Int\", \"pop!\", \"unspecified\")"]` | 43.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["collection", "queries & updates", "(\"Set\", \"Int\", \"push!\", \"new\")"]` | 34.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["collection", "queries & updates", "(\"Set\", \"Int\", \"push!\", \"overwrite\")"]` | 32.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["collection", "queries & updates", "(\"Set\", \"String\", \"in\", \"false\")"]` | 44.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["collection", "queries & updates", "(\"Set\", \"String\", \"in\", \"true\")"]` | 44.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["collection", "queries & updates", "(\"Set\", \"String\", \"pop!\", \"specified\")"]` | 73.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["collection", "queries & updates", "(\"Set\", \"String\", \"pop!\", \"unspecified\")"]` | 75.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["collection", "queries & updates", "(\"Set\", \"String\", \"push!\", \"new\")"]` | 58.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["collection", "queries & updates", "(\"Set\", \"String\", \"push!\", \"overwrite\")"]` | 54.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["collection", "queries & updates", "(\"Vector\", \"Any\", \"getindex\")"]` | 24.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["collection", "queries & updates", "(\"Vector\", \"Any\", \"in\", \"false\")"]` | 40.020 μs (25%) | 0.000 ns | 15.63 KiB (1%) | 1000 |
| `["collection", "queries & updates", "(\"Vector\", \"Any\", \"in\", \"true\")"]` | 1.109 μs (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["collection", "queries & updates", "(\"Vector\", \"Any\", \"pop!\", \"unspecified\")"]` | 35.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["collection", "queries & updates", "(\"Vector\", \"Any\", \"push!\")"]` | 1.250 μs (25%) | 0.000 ns | 15.70 KiB (1%) | 2 |
| `["collection", "queries & updates", "(\"Vector\", \"Any\", \"setindex!\")"]` | 32.000 ns (25%) | 0.000 ns | 16 bytes (1%) | 1 |
| `["collection", "queries & updates", "(\"Vector\", \"Int\", \"first\")"]` | 24.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["collection", "queries & updates", "(\"Vector\", \"Int\", \"getindex\")"]` | 24.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["collection", "queries & updates", "(\"Vector\", \"Int\", \"in\", \"false\")"]` | 470.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["collection", "queries & updates", "(\"Vector\", \"Int\", \"in\", \"true\")"]` | 140.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["collection", "queries & updates", "(\"Vector\", \"Int\", \"last\")"]` | 24.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["collection", "queries & updates", "(\"Vector\", \"Int\", \"length\")"]` | 24.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["collection", "queries & updates", "(\"Vector\", \"Int\", \"pop!\", \"unspecified\")"]` | 35.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["collection", "queries & updates", "(\"Vector\", \"Int\", \"push!\")"]` | 1.114 μs (25%) | 0.000 ns | 15.69 KiB (1%) | 1 |
| `["collection", "queries & updates", "(\"Vector\", \"Int\", \"setindex!\")"]` | 24.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["collection", "queries & updates", "(\"Vector\", \"String\", \"getindex\")"]` | 24.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["collection", "queries & updates", "(\"Vector\", \"String\", \"in\", \"false\")"]` | 2.091 μs (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["collection", "queries & updates", "(\"Vector\", \"String\", \"in\", \"true\")"]` | 2.449 μs (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["collection", "queries & updates", "(\"Vector\", \"String\", \"pop!\", \"unspecified\")"]` | 35.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["collection", "queries & updates", "(\"Vector\", \"String\", \"push!\")"]` | 1.179 μs (25%) | 0.000 ns | 15.69 KiB (1%) | 1 |
| `["collection", "queries & updates", "(\"Vector\", \"String\", \"setindex!\")"]` | 26.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["collection", "set operations", "(\"BitSet\", \"Int\", \"<\", \"BitSet\")"]` | 28.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["collection", "set operations", "(\"BitSet\", \"Int\", \"==\", \"BitSet\")"]` | 30.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["collection", "set operations", "(\"BitSet\", \"Int\", \"==\", \"self\")"]` | 38.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["collection", "set operations", "(\"BitSet\", \"Int\", \"intersect!\", \"BitSet\")"]` | 37.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["collection", "set operations", "(\"BitSet\", \"Int\", \"intersect!\", \"big\")"]` | 36.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["collection", "set operations", "(\"BitSet\", \"Int\", \"intersect!\", \"small\")"]` | 38.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["collection", "set operations", "(\"BitSet\", \"Int\", \"intersect\")"]` | 119.000 ns (25%) | 0.000 ns | 304 bytes (1%) | 4 |
| `["collection", "set operations", "(\"BitSet\", \"Int\", \"intersect\", \"BitSet\")"]` | 134.000 ns (25%) | 0.000 ns | 304 bytes (1%) | 4 |
| `["collection", "set operations", "(\"BitSet\", \"Int\", \"intersect\", \"BitSet\", \"BitSet\")"]` | 147.000 ns (25%) | 0.000 ns | 304 bytes (1%) | 4 |
| `["collection", "set operations", "(\"BitSet\", \"Int\", \"intersect\", \"Set\")"]` | 321.000 ns (25%) | 0.000 ns | 448 bytes (1%) | 5 |
| `["collection", "set operations", "(\"BitSet\", \"Int\", \"intersect\", \"Set\", \"Set\")"]` | 420.000 ns (25%) | 0.000 ns | 448 bytes (1%) | 5 |
| `["collection", "set operations", "(\"BitSet\", \"Int\", \"intersect\", \"Vector\")"]` | 248.000 ns (25%) | 0.000 ns | 544 bytes (1%) | 5 |
| `["collection", "set operations", "(\"BitSet\", \"Int\", \"intersect\", \"Vector\", \"Vector\")"]` | 495.000 ns (25%) | 0.000 ns | 1.67 KiB (1%) | 11 |
| `["collection", "set operations", "(\"BitSet\", \"Int\", \"setdiff!\", \"BitSet\")"]` | 37.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["collection", "set operations", "(\"BitSet\", \"Int\", \"setdiff!\", \"Set\")"]` | 131.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["collection", "set operations", "(\"BitSet\", \"Int\", \"setdiff!\", \"Vector\")"]` | 66.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["collection", "set operations", "(\"BitSet\", \"Int\", \"setdiff!\", \"big\")"]` | 32.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["collection", "set operations", "(\"BitSet\", \"Int\", \"setdiff!\", \"small\")"]` | 32.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["collection", "set operations", "(\"BitSet\", \"Int\", \"setdiff\", \"BitSet\")"]` | 135.000 ns (25%) | 0.000 ns | 304 bytes (1%) | 4 |
| `["collection", "set operations", "(\"BitSet\", \"Int\", \"setdiff\", \"Set\")"]` | 226.000 ns (25%) | 0.000 ns | 304 bytes (1%) | 4 |
| `["collection", "set operations", "(\"BitSet\", \"Int\", \"setdiff\", \"Vector\")"]` | 156.000 ns (25%) | 0.000 ns | 304 bytes (1%) | 4 |
| `["collection", "set operations", "(\"BitSet\", \"Int\", \"symdiff!\", \"BitSet\")"]` | 64.000 ns (25%) | 0.000 ns | 272 bytes (1%) | 1 |
| `["collection", "set operations", "(\"BitSet\", \"Int\", \"symdiff!\", \"Set\")"]` | 283.000 ns (25%) | 0.000 ns | 272 bytes (1%) | 1 |
| `["collection", "set operations", "(\"BitSet\", \"Int\", \"symdiff!\", \"Vector\")"]` | 219.000 ns (25%) | 0.000 ns | 272 bytes (1%) | 1 |
| `["collection", "set operations", "(\"BitSet\", \"Int\", \"symdiff!\", \"big\")"]` | 2.633 μs (25%) | 0.000 ns | 128.06 KiB (1%) | 1 |
| `["collection", "set operations", "(\"BitSet\", \"Int\", \"symdiff!\", \"small\")"]` | 2.806 μs (25%) | 0.000 ns | 32.13 KiB (1%) | 1 |
| `["collection", "set operations", "(\"BitSet\", \"Int\", \"symdiff\")"]` | 119.000 ns (25%) | 0.000 ns | 304 bytes (1%) | 4 |
| `["collection", "set operations", "(\"BitSet\", \"Int\", \"symdiff\", \"BitSet\")"]` | 161.000 ns (25%) | 0.000 ns | 576 bytes (1%) | 5 |
| `["collection", "set operations", "(\"BitSet\", \"Int\", \"symdiff\", \"BitSet\", \"BitSet\")"]` | 540.000 ns (25%) | 0.000 ns | 656 bytes (1%) | 8 |
| `["collection", "set operations", "(\"BitSet\", \"Int\", \"symdiff\", \"Set\")"]` | 417.000 ns (25%) | 0.000 ns | 624 bytes (1%) | 7 |
| `["collection", "set operations", "(\"BitSet\", \"Int\", \"symdiff\", \"Set\", \"Set\")"]` | 619.000 ns (25%) | 0.000 ns | 608 bytes (1%) | 7 |
| `["collection", "set operations", "(\"BitSet\", \"Int\", \"symdiff\", \"Vector\")"]` | 321.000 ns (25%) | 0.000 ns | 576 bytes (1%) | 5 |
| `["collection", "set operations", "(\"BitSet\", \"Int\", \"symdiff\", \"Vector\", \"Vector\")"]` | 490.000 ns (25%) | 0.000 ns | 576 bytes (1%) | 5 |
| `["collection", "set operations", "(\"BitSet\", \"Int\", \"union!\", \"BitSet\")"]` | 64.000 ns (25%) | 0.000 ns | 272 bytes (1%) | 1 |
| `["collection", "set operations", "(\"BitSet\", \"Int\", \"union!\", \"Set\")"]` | 200.000 ns (25%) | 0.000 ns | 272 bytes (1%) | 1 |
| `["collection", "set operations", "(\"BitSet\", \"Int\", \"union!\", \"Vector\")"]` | 122.000 ns (25%) | 0.000 ns | 272 bytes (1%) | 1 |
| `["collection", "set operations", "(\"BitSet\", \"Int\", \"union!\", \"big\")"]` | 2.678 μs (25%) | 0.000 ns | 128.06 KiB (1%) | 1 |
| `["collection", "set operations", "(\"BitSet\", \"Int\", \"union!\", \"small\")"]` | 2.813 μs (25%) | 0.000 ns | 32.13 KiB (1%) | 1 |
| `["collection", "set operations", "(\"BitSet\", \"Int\", \"union\")"]` | 118.000 ns (25%) | 0.000 ns | 304 bytes (1%) | 4 |
| `["collection", "set operations", "(\"BitSet\", \"Int\", \"union\", \"BitSet\")"]` | 159.000 ns (25%) | 0.000 ns | 576 bytes (1%) | 5 |
| `["collection", "set operations", "(\"BitSet\", \"Int\", \"union\", \"BitSet\", \"BitSet\")"]` | 181.000 ns (25%) | 0.000 ns | 576 bytes (1%) | 5 |
| `["collection", "set operations", "(\"BitSet\", \"Int\", \"union\", \"Set\")"]` | 296.000 ns (25%) | 0.000 ns | 576 bytes (1%) | 5 |
| `["collection", "set operations", "(\"BitSet\", \"Int\", \"union\", \"Set\", \"Set\")"]` | 430.000 ns (25%) | 0.000 ns | 576 bytes (1%) | 5 |
| `["collection", "set operations", "(\"BitSet\", \"Int\", \"union\", \"Vector\")"]` | 212.000 ns (25%) | 0.000 ns | 576 bytes (1%) | 5 |
| `["collection", "set operations", "(\"BitSet\", \"Int\", \"union\", \"Vector\", \"Vector\")"]` | 272.000 ns (25%) | 0.000 ns | 576 bytes (1%) | 5 |
| `["collection", "set operations", "(\"BitSet\", \"Int\", \"⊆\", \"BitSet\")"]` | 28.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["collection", "set operations", "(\"BitSet\", \"Int\", \"⊆\", \"Set\")"]` | 38.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["collection", "set operations", "(\"BitSet\", \"Int\", \"⊆\", \"Vector\")"]` | 39.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["collection", "set operations", "(\"BitSet\", \"Int\", \"⊆\", \"self\")"]` | 35.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["collection", "set operations", "(\"Set\", \"Int\", \"<\", \"Set\")"]` | 24.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["collection", "set operations", "(\"Set\", \"Int\", \"==\", \"Set\")"]` | 24.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["collection", "set operations", "(\"Set\", \"Int\", \"==\", \"self\")"]` | 4.389 μs (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["collection", "set operations", "(\"Set\", \"Int\", \"intersect\")"]` | 3.320 μs (25%) | 0.000 ns | 18.47 KiB (1%) | 4 |
| `["collection", "set operations", "(\"Set\", \"Int\", \"intersect\", \"BitSet\")"]` | 541.000 ns (25%) | 0.000 ns | 1.31 KiB (1%) | 7 |
| `["collection", "set operations", "(\"Set\", \"Int\", \"intersect\", \"BitSet\", \"BitSet\")"]` | 619.000 ns (25%) | 0.000 ns | 1.31 KiB (1%) | 7 |
| `["collection", "set operations", "(\"Set\", \"Int\", \"intersect\", \"Set\")"]` | 568.000 ns (25%) | 0.000 ns | 1.31 KiB (1%) | 7 |
| `["collection", "set operations", "(\"Set\", \"Int\", \"intersect\", \"Set\", \"Set\")"]` | 697.000 ns (25%) | 0.000 ns | 1.31 KiB (1%) | 7 |
| `["collection", "set operations", "(\"Set\", \"Int\", \"intersect\", \"Vector\")"]` | 503.000 ns (25%) | 0.000 ns | 1.31 KiB (1%) | 7 |
| `["collection", "set operations", "(\"Set\", \"Int\", \"intersect\", \"Vector\", \"Vector\")"]` | 1.045 μs (25%) | 0.000 ns | 2.40 KiB (1%) | 14 |
| `["collection", "set operations", "(\"Set\", \"Int\", \"setdiff!\", \"BitSet\")"]` | 234.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["collection", "set operations", "(\"Set\", \"Int\", \"setdiff!\", \"Set\")"]` | 268.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["collection", "set operations", "(\"Set\", \"Int\", \"setdiff!\", \"Vector\")"]` | 193.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["collection", "set operations", "(\"Set\", \"Int\", \"setdiff\", \"BitSet\")"]` | 3.428 μs (25%) | 0.000 ns | 18.47 KiB (1%) | 4 |
| `["collection", "set operations", "(\"Set\", \"Int\", \"setdiff\", \"Set\")"]` | 3.456 μs (25%) | 0.000 ns | 18.47 KiB (1%) | 4 |
| `["collection", "set operations", "(\"Set\", \"Int\", \"setdiff\", \"Vector\")"]` | 3.356 μs (25%) | 0.000 ns | 18.47 KiB (1%) | 4 |
| `["collection", "set operations", "(\"Set\", \"Int\", \"symdiff\")"]` | 3.174 μs (25%) | 0.000 ns | 18.47 KiB (1%) | 4 |
| `["collection", "set operations", "(\"Set\", \"Int\", \"symdiff\", \"BitSet\")"]` | 15.780 μs (25%) | 0.000 ns | 13.27 KiB (1%) | 15 |
| `["collection", "set operations", "(\"Set\", \"Int\", \"symdiff\", \"BitSet\", \"BitSet\")"]` | 17.172 μs (25%) | 0.000 ns | 13.36 KiB (1%) | 20 |
| `["collection", "set operations", "(\"Set\", \"Int\", \"symdiff\", \"Set\")"]` | 15.663 μs (25%) | 0.000 ns | 13.22 KiB (1%) | 13 |
| `["collection", "set operations", "(\"Set\", \"Int\", \"symdiff\", \"Set\", \"Set\")"]` | 16.311 μs (25%) | 0.000 ns | 13.22 KiB (1%) | 13 |
| `["collection", "set operations", "(\"Set\", \"Int\", \"symdiff\", \"Vector\")"]` | 15.580 μs (25%) | 0.000 ns | 13.27 KiB (1%) | 15 |
| `["collection", "set operations", "(\"Set\", \"Int\", \"symdiff\", \"Vector\", \"Vector\")"]` | 17.152 μs (25%) | 0.000 ns | 13.36 KiB (1%) | 20 |
| `["collection", "set operations", "(\"Set\", \"Int\", \"union!\", \"BitSet\")"]` | 306.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["collection", "set operations", "(\"Set\", \"Int\", \"union!\", \"Set\")"]` | 319.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["collection", "set operations", "(\"Set\", \"Int\", \"union!\", \"Vector\")"]` | 248.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["collection", "set operations", "(\"Set\", \"Int\", \"union\")"]` | 3.120 μs (25%) | 0.000 ns | 18.47 KiB (1%) | 4 |
| `["collection", "set operations", "(\"Set\", \"Int\", \"union\", \"BitSet\")"]` | 9.081 μs (25%) | 0.000 ns | 9.65 KiB (1%) | 9 |
| `["collection", "set operations", "(\"Set\", \"Int\", \"union\", \"BitSet\", \"BitSet\")"]` | 13.394 μs (25%) | 0.000 ns | 28.07 KiB (1%) | 13 |
| `["collection", "set operations", "(\"Set\", \"Int\", \"union\", \"Set\")"]` | 8.929 μs (25%) | 0.000 ns | 9.60 KiB (1%) | 7 |
| `["collection", "set operations", "(\"Set\", \"Int\", \"union\", \"Set\", \"Set\")"]` | 13.460 μs (25%) | 0.000 ns | 27.99 KiB (1%) | 10 |
| `["collection", "set operations", "(\"Set\", \"Int\", \"union\", \"Vector\")"]` | 9.023 μs (25%) | 0.000 ns | 9.65 KiB (1%) | 9 |
| `["collection", "set operations", "(\"Set\", \"Int\", \"union\", \"Vector\", \"Vector\")"]` | 13.101 μs (25%) | 0.000 ns | 28.07 KiB (1%) | 13 |
| `["collection", "set operations", "(\"Set\", \"Int\", \"⊆\", \"BitSet\")"]` | 38.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["collection", "set operations", "(\"Set\", \"Int\", \"⊆\", \"Set\")"]` | 27.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["collection", "set operations", "(\"Set\", \"Int\", \"⊆\", \"Vector\")"]` | 27.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["collection", "set operations", "(\"Set\", \"Int\", \"⊆\", \"self\")"]` | 4.328 μs (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["collection", "set operations", "(\"Vector\", \"Int\", \"intersect\")"]` | 29.889 μs (25%) | 0.000 ns | 65.95 KiB (1%) | 27 |
| `["collection", "set operations", "(\"Vector\", \"Int\", \"intersect\", \"BitSet\")"]` | 38.281 μs (25%) | 0.000 ns | 26.60 KiB (1%) | 8 |
| `["collection", "set operations", "(\"Vector\", \"Int\", \"intersect\", \"BitSet\", \"BitSet\")"]` | 39.895 μs (25%) | 0.000 ns | 26.66 KiB (1%) | 11 |
| `["collection", "set operations", "(\"Vector\", \"Int\", \"intersect\", \"Set\")"]` | 46.092 μs (25%) | 0.000 ns | 26.60 KiB (1%) | 8 |
| `["collection", "set operations", "(\"Vector\", \"Int\", \"intersect\", \"Set\", \"Set\")"]` | 48.577 μs (25%) | 0.000 ns | 26.70 KiB (1%) | 13 |
| `["collection", "set operations", "(\"Vector\", \"Int\", \"intersect\", \"Vector\")"]` | 48.042 μs (25%) | 0.000 ns | 27.73 KiB (1%) | 18 |
| `["collection", "set operations", "(\"Vector\", \"Int\", \"intersect\", \"Vector\", \"Vector\")"]` | 49.459 μs (25%) | 0.000 ns | 28.77 KiB (1%) | 22 |
| `["collection", "set operations", "(\"Vector\", \"Int\", \"setdiff\", \"BitSet\")"]` | 27.824 μs (25%) | 0.000 ns | 26.60 KiB (1%) | 8 |
| `["collection", "set operations", "(\"Vector\", \"Int\", \"setdiff\", \"Set\")"]` | 27.828 μs (25%) | 0.000 ns | 26.60 KiB (1%) | 8 |
| `["collection", "set operations", "(\"Vector\", \"Int\", \"setdiff\", \"Vector\")"]` | 28.098 μs (25%) | 0.000 ns | 26.63 KiB (1%) | 10 |
| `["collection", "set operations", "(\"Vector\", \"Int\", \"symdiff\")"]` | 49.186 μs (25%) | 0.000 ns | 21.16 KiB (1%) | 14 |
| `["collection", "set operations", "(\"Vector\", \"Int\", \"symdiff\", \"BitSet\")"]` | 55.866 μs (25%) | 0.000 ns | 21.59 KiB (1%) | 24 |
| `["collection", "set operations", "(\"Vector\", \"Int\", \"symdiff\", \"BitSet\", \"BitSet\")"]` | 57.188 μs (25%) | 0.000 ns | 21.64 KiB (1%) | 26 |
| `["collection", "set operations", "(\"Vector\", \"Int\", \"symdiff\", \"Set\")"]` | 56.385 μs (25%) | 0.000 ns | 21.69 KiB (1%) | 28 |
| `["collection", "set operations", "(\"Vector\", \"Int\", \"symdiff\", \"Set\", \"Set\")"]` | 58.200 μs (25%) | 0.000 ns | 21.80 KiB (1%) | 34 |
| `["collection", "set operations", "(\"Vector\", \"Int\", \"symdiff\", \"Vector\")"]` | 55.713 μs (25%) | 0.000 ns | 21.55 KiB (1%) | 22 |
| `["collection", "set operations", "(\"Vector\", \"Int\", \"symdiff\", \"Vector\", \"Vector\")"]` | 57.166 μs (25%) | 0.000 ns | 21.63 KiB (1%) | 25 |
| `["collection", "set operations", "(\"Vector\", \"Int\", \"union\")"]` | 29.880 μs (25%) | 0.000 ns | 65.95 KiB (1%) | 27 |
| `["collection", "set operations", "(\"Vector\", \"Int\", \"union\", \"BitSet\")"]` | 31.034 μs (25%) | 0.000 ns | 66.00 KiB (1%) | 29 |
| `["collection", "set operations", "(\"Vector\", \"Int\", \"union\", \"BitSet\", \"BitSet\")"]` | 31.224 μs (25%) | 0.000 ns | 66.00 KiB (1%) | 29 |
| `["collection", "set operations", "(\"Vector\", \"Int\", \"union\", \"Set\")"]` | 30.568 μs (25%) | 0.000 ns | 66.05 KiB (1%) | 31 |
| `["collection", "set operations", "(\"Vector\", \"Int\", \"union\", \"Set\", \"Set\")"]` | 31.380 μs (25%) | 0.000 ns | 66.13 KiB (1%) | 35 |
| `["collection", "set operations", "(\"Vector\", \"Int\", \"union\", \"Vector\")"]` | 30.269 μs (25%) | 0.000 ns | 65.95 KiB (1%) | 27 |
| `["collection", "set operations", "(\"Vector\", \"Int\", \"union\", \"Vector\", \"Vector\")"]` | 30.790 μs (25%) | 0.000 ns | 65.95 KiB (1%) | 27 |
| `["collection", "set operations", "(\"Vector\", \"Int\", \"⊆\", \"BitSet\")"]` | 28.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["collection", "set operations", "(\"Vector\", \"Int\", \"⊆\", \"Set\")"]` | 33.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["collection", "set operations", "(\"Vector\", \"Int\", \"⊆\", \"Vector\")"]` | 42.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["collection", "set operations", "(\"empty\", \"Int\", \"<\", \"BitSet\")"]` | 36.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["collection", "set operations", "(\"empty\", \"Int\", \"<\", \"Set\")"]` | 35.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["collection", "set operations", "(\"empty\", \"Int\", \"⊆\", \"BitSet\")"]` | 27.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["collection", "set operations", "(\"empty\", \"Int\", \"⊆\", \"Set\")"]` | 36.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["dates", "accessor", "day"]` | 0.023 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["dates", "accessor", "hour"]` | 0.023 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["dates", "accessor", "millisecond"]` | 0.023 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["dates", "accessor", "minute"]` | 0.023 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["dates", "accessor", "month"]` | 0.023 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["dates", "accessor", "second"]` | 0.023 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["dates", "accessor", "year"]` | 0.023 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["dates", "arithmetic", "(\"DateTime\", \"Day\")"]` | 23.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["dates", "arithmetic", "(\"DateTime\", \"Hour\")"]` | 23.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["dates", "arithmetic", "(\"DateTime\", \"Millisecond\")"]` | 23.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["dates", "arithmetic", "(\"DateTime\", \"Minute\")"]` | 23.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["dates", "arithmetic", "(\"DateTime\", \"Month\")"]` | 23.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["dates", "arithmetic", "(\"DateTime\", \"Second\")"]` | 23.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["dates", "arithmetic", "(\"DateTime\", \"Year\")"]` | 23.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["dates", "arithmetic", "(\"Date\", \"Day\")"]` | 23.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["dates", "arithmetic", "(\"Date\", \"Month\")"]` | 23.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["dates", "arithmetic", "(\"Date\", \"Year\")"]` | 23.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["dates", "construction", "Date"]` | 0.023 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["dates", "construction", "DateTime"]` | 0.023 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["dates", "conversion", "Date -> DateTime"]` | 0.023 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["dates", "conversion", "DateTime -> Date"]` | 0.023 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["dates", "parse", "(\"DateTime\", \"DateFormat\")"]` | 15.326 μs (5%) | 0.000 ns | 3.33 KiB (1%) | 51 |
| `["dates", "parse", "(\"DateTime\", \"ISODateTimeFormat\")"]` | 84.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["dates", "parse", "(\"DateTime\", \"RFC1123Format\", \"Lowercase\")"]` | 231.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["dates", "parse", "(\"DateTime\", \"RFC1123Format\", \"Mixedcase\")"]` | 358.000 ns (5%) | 0.000 ns | 128 bytes (1%) | 3 |
| `["dates", "parse", "(\"DateTime\", \"RFC1123Format\", \"Titlecase\")"]` | 231.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["dates", "parse", "(\"Date\", \"DateFormat\")"]` | 12.389 μs (5%) | 0.000 ns | 1.61 KiB (1%) | 25 |
| `["dates", "parse", "(\"Date\", \"ISODateFormat\")"]` | 69.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["dates", "parse", "Date"]` | 46.214 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["dates", "parse", "DateTime"]` | 60.922 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["dates", "query", "(\"dayofweek\", \"DateTime\")"]` | 23.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["dates", "query", "(\"dayofweek\", \"Date\")"]` | 23.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["dates", "query", "(\"dayofweekofmonth\", \"DateTime\")"]` | 23.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["dates", "query", "(\"dayofweekofmonth\", \"Date\")"]` | 23.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["dates", "query", "(\"dayofyear\", \"DateTime\")"]` | 23.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["dates", "query", "(\"dayofyear\", \"Date\")"]` | 23.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["dates", "query", "(\"daysofweekinmonth\", \"DateTime\")"]` | 49.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["dates", "query", "(\"daysofweekinmonth\", \"Date\")"]` | 46.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["dates", "query", "(\"firstdayofmonth\", \"DateTime\")"]` | 23.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["dates", "query", "(\"firstdayofmonth\", \"Date\")"]` | 23.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["dates", "query", "(\"firstdayofweek\", \"DateTime\")"]` | 23.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["dates", "query", "(\"firstdayofweek\", \"Date\")"]` | 23.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["dates", "query", "(\"isleapyear\", \"DateTime\")"]` | 23.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["dates", "query", "(\"isleapyear\", \"Date\")"]` | 23.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["dates", "query", "(\"lastdayofmonth\", \"DateTime\")"]` | 23.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["dates", "query", "(\"lastdayofmonth\", \"Date\")"]` | 23.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["dates", "query", "(\"lastdayofweek\", \"DateTime\")"]` | 23.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["dates", "query", "(\"lastdayofweek\", \"Date\")"]` | 23.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["dates", "string", "Date"]` | 281.402 ns (5%) | 0.000 ns | 560 bytes (1%) | 12 |
| `["dates", "string", "DateTime"]` | 597.722 ns (5%) | 0.000 ns | 1.19 KiB (1%) | 22 |
| `["find", "findall", "(\"> q0.5\", \"Vector{Bool}\")"]` | 1.562 μs (5%) | 0.000 ns | 8.48 KiB (1%) | 7 |
| `["find", "findall", "(\"> q0.5\", \"Vector{Float32}\")"]` | 1.758 μs (5%) | 0.000 ns | 8.55 KiB (1%) | 7 |
| `["find", "findall", "(\"> q0.5\", \"Vector{Float64}\")"]` | 1.516 μs (5%) | 0.000 ns | 8.55 KiB (1%) | 7 |
| `["find", "findall", "(\"> q0.5\", \"Vector{Int64}\")"]` | 2.510 μs (5%) | 0.000 ns | 8.55 KiB (1%) | 7 |
| `["find", "findall", "(\"> q0.5\", \"Vector{Int8}\")"]` | 1.730 μs (5%) | 0.000 ns | 8.55 KiB (1%) | 7 |
| `["find", "findall", "(\"> q0.5\", \"Vector{UInt64}\")"]` | 2.518 μs (5%) | 0.000 ns | 8.55 KiB (1%) | 7 |
| `["find", "findall", "(\"> q0.5\", \"Vector{UInt8}\")"]` | 1.626 μs (5%) | 0.000 ns | 8.55 KiB (1%) | 7 |
| `["find", "findall", "(\"> q0.8\", \"Vector{Bool}\")"]` | 973.000 ns (5%) | 0.000 ns | 4.56 KiB (1%) | 7 |
| `["find", "findall", "(\"> q0.8\", \"Vector{Float32}\")"]` | 1.224 μs (5%) | 0.000 ns | 6.25 KiB (1%) | 7 |
| `["find", "findall", "(\"> q0.8\", \"Vector{Float64}\")"]` | 1.121 μs (5%) | 0.000 ns | 6.25 KiB (1%) | 7 |
| `["find", "findall", "(\"> q0.8\", \"Vector{Int64}\")"]` | 2.014 μs (5%) | 0.000 ns | 6.25 KiB (1%) | 7 |
| `["find", "findall", "(\"> q0.8\", \"Vector{Int8}\")"]` | 1.292 μs (5%) | 0.000 ns | 6.25 KiB (1%) | 7 |
| `["find", "findall", "(\"> q0.8\", \"Vector{UInt64}\")"]` | 2.026 μs (5%) | 0.000 ns | 6.25 KiB (1%) | 7 |
| `["find", "findall", "(\"> q0.8\", \"Vector{UInt8}\")"]` | 1.169 μs (5%) | 0.000 ns | 6.25 KiB (1%) | 7 |
| `["find", "findall", "(\"> q0.95\", \"Vector{Bool}\")"]` | 985.000 ns (5%) | 0.000 ns | 4.56 KiB (1%) | 7 |
| `["find", "findall", "(\"> q0.95\", \"Vector{Float32}\")"]` | 1.072 μs (5%) | 0.000 ns | 4.97 KiB (1%) | 7 |
| `["find", "findall", "(\"> q0.95\", \"Vector{Float64}\")"]` | 1.010 μs (5%) | 0.000 ns | 4.97 KiB (1%) | 7 |
| `["find", "findall", "(\"> q0.95\", \"Vector{Int64}\")"]` | 1.921 μs (5%) | 0.000 ns | 4.97 KiB (1%) | 7 |
| `["find", "findall", "(\"> q0.95\", \"Vector{Int8}\")"]` | 1.151 μs (5%) | 0.000 ns | 4.92 KiB (1%) | 7 |
| `["find", "findall", "(\"> q0.95\", \"Vector{UInt64}\")"]` | 1.898 μs (5%) | 0.000 ns | 4.97 KiB (1%) | 7 |
| `["find", "findall", "(\"> q0.95\", \"Vector{UInt8}\")"]` | 1.051 μs (5%) | 0.000 ns | 4.97 KiB (1%) | 7 |
| `["find", "findall", "(\"> q0.99\", \"Vector{Bool}\")"]` | 976.000 ns (5%) | 0.000 ns | 4.56 KiB (1%) | 7 |
| `["find", "findall", "(\"> q0.99\", \"Vector{Float32}\")"]` | 1.030 μs (5%) | 0.000 ns | 4.64 KiB (1%) | 7 |
| `["find", "findall", "(\"> q0.99\", \"Vector{Float64}\")"]` | 945.000 ns (5%) | 0.000 ns | 4.64 KiB (1%) | 7 |
| `["find", "findall", "(\"> q0.99\", \"Vector{Int64}\")"]` | 1.874 μs (5%) | 0.000 ns | 4.64 KiB (1%) | 7 |
| `["find", "findall", "(\"> q0.99\", \"Vector{Int8}\")"]` | 1.096 μs (5%) | 0.000 ns | 4.64 KiB (1%) | 7 |
| `["find", "findall", "(\"> q0.99\", \"Vector{UInt64}\")"]` | 1.859 μs (5%) | 0.000 ns | 4.64 KiB (1%) | 7 |
| `["find", "findall", "(\"> q0.99\", \"Vector{UInt8}\")"]` | 1.022 μs (5%) | 0.000 ns | 4.61 KiB (1%) | 7 |
| `["find", "findall", "(\"BitVector\", \"10-90\")"]` | 123.000 ns (5%) | 0.000 ns | 896 bytes (1%) | 1 |
| `["find", "findall", "(\"BitVector\", \"50-50\")"]` | 512.000 ns (5%) | 0.000 ns | 4.00 KiB (1%) | 1 |
| `["find", "findall", "(\"BitVector\", \"90-10\")"]` | 899.000 ns (5%) | 0.000 ns | 7.19 KiB (1%) | 1 |
| `["find", "findall", "(\"Vector{Bool}\", \"10-90\")"]` | 876.000 ns (5%) | 0.000 ns | 896 bytes (1%) | 1 |
| `["find", "findall", "(\"Vector{Bool}\", \"50-50\")"]` | 1.196 μs (5%) | 0.000 ns | 4.00 KiB (1%) | 1 |
| `["find", "findall", "(\"Vector{Bool}\", \"90-10\")"]` | 1.417 μs (5%) | 0.000 ns | 7.19 KiB (1%) | 1 |
| `["find", "findall", "(\"ispos\", \"Vector{Bool}\")"]` | 1.505 μs (5%) | 0.000 ns | 8.45 KiB (1%) | 6 |
| `["find", "findall", "(\"ispos\", \"Vector{Float32}\")"]` | 1.695 μs (5%) | 0.000 ns | 12.39 KiB (1%) | 6 |
| `["find", "findall", "(\"ispos\", \"Vector{Float64}\")"]` | 1.690 μs (5%) | 0.000 ns | 12.39 KiB (1%) | 6 |
| `["find", "findall", "(\"ispos\", \"Vector{Int64}\")"]` | 1.568 μs (5%) | 0.000 ns | 8.64 KiB (1%) | 6 |
| `["find", "findall", "(\"ispos\", \"Vector{Int8}\")"]` | 1.590 μs (5%) | 0.000 ns | 8.58 KiB (1%) | 6 |
| `["find", "findall", "(\"ispos\", \"Vector{UInt64}\")"]` | 1.800 μs (5%) | 0.000 ns | 12.39 KiB (1%) | 6 |
| `["find", "findall", "(\"ispos\", \"Vector{UInt8}\")"]` | 1.866 μs (5%) | 0.000 ns | 12.39 KiB (1%) | 6 |
| `["find", "findnext", "(\"BitVector\", \"10-90\")"]` | 716.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["find", "findnext", "(\"BitVector\", \"50-50\")"]` | 3.644 μs (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["find", "findnext", "(\"BitVector\", \"90-10\")"]` | 6.488 μs (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["find", "findnext", "(\"Vector{Bool}\", \"50-50\")"]` | 948.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["find", "findnext", "(\"ispos\", \"Vector{Bool}\")"]` | 16.118 μs (5%) | 0.000 ns | 7.44 KiB (1%) | 476 |
| `["find", "findnext", "(\"ispos\", \"Vector{Float32}\")"]` | 23.842 μs (5%) | 0.000 ns | 15.30 KiB (1%) | 979 |
| `["find", "findnext", "(\"ispos\", \"Vector{Float64}\")"]` | 25.010 μs (5%) | 0.000 ns | 15.30 KiB (1%) | 979 |
| `["find", "findnext", "(\"ispos\", \"Vector{Int64}\")"]` | 15.989 μs (5%) | 0.000 ns | 8.22 KiB (1%) | 526 |
| `["find", "findnext", "(\"ispos\", \"Vector{Int8}\")"]` | 15.774 μs (5%) | 0.000 ns | 7.86 KiB (1%) | 503 |
| `["find", "findnext", "(\"ispos\", \"Vector{UInt64}\")"]` | 24.612 μs (5%) | 0.000 ns | 15.30 KiB (1%) | 979 |
| `["find", "findnext", "(\"ispos\", \"Vector{UInt8}\")"]` | 23.115 μs (5%) | 0.000 ns | 15.27 KiB (1%) | 977 |
| `["find", "findprev", "(\"BitVector\", \"10-90\")"]` | 778.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["find", "findprev", "(\"BitVector\", \"50-50\")"]` | 3.460 μs (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["find", "findprev", "(\"BitVector\", \"90-10\")"]` | 6.172 μs (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["find", "findprev", "(\"Vector{Bool}\", \"50-50\")"]` | 892.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["find", "findprev", "(\"ispos\", \"Vector{Bool}\")"]` | 14.949 μs (5%) | 0.000 ns | 7.44 KiB (1%) | 476 |
| `["find", "findprev", "(\"ispos\", \"Vector{Float32}\")"]` | 22.555 μs (5%) | 0.000 ns | 15.28 KiB (1%) | 978 |
| `["find", "findprev", "(\"ispos\", \"Vector{Float64}\")"]` | 22.949 μs (5%) | 0.000 ns | 15.28 KiB (1%) | 978 |
| `["find", "findprev", "(\"ispos\", \"Vector{Int64}\")"]` | 15.990 μs (5%) | 0.000 ns | 8.22 KiB (1%) | 526 |
| `["find", "findprev", "(\"ispos\", \"Vector{Int8}\")"]` | 15.398 μs (5%) | 0.000 ns | 7.86 KiB (1%) | 503 |
| `["find", "findprev", "(\"ispos\", \"Vector{UInt64}\")"]` | 23.451 μs (5%) | 0.000 ns | 15.28 KiB (1%) | 978 |
| `["find", "findprev", "(\"ispos\", \"Vector{UInt8}\")"]` | 22.618 μs (5%) | 0.000 ns | 15.25 KiB (1%) | 976 |
| `["io", "array_limit", "(\"display\", \"Matrix{Float64}(10000, 10000)\")"]` | 1.049 ms (5%) | 0.000 ns | 530.08 KiB (1%) | 7918 |
| `["io", "array_limit", "(\"display\", \"Matrix{Float64}(100000000, 1)\")"]` | 719.991 μs (5%) | 0.000 ns | 88.44 KiB (1%) | 1149 |
| `["io", "array_limit", "(\"display\", \"Vector{Float64}(100000000,)\")"]` | 714.034 μs (5%) | 0.000 ns | 87.38 KiB (1%) | 1123 |
| `["io", "read", "read"]` | 8.840 μs (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["io", "read", "readstring"]` | 21.827 ns (5%) | 0.000 ns | 64 bytes (1%) | 1 |
| `["io", "serialization", "(\"deserialize\", \"Matrix{Float64}\")"]` | 1.228 ms (5%) | 0.000 ns | 7.63 MiB (1%) | 22 |
| `["io", "serialization", "(\"deserialize\", \"Vector{String}\")"]` | 121.768 μs (5%) | 0.000 ns | 171.19 KiB (1%) | 1994 |
| `["io", "serialization", "(\"serialize\", \"Matrix{Float64}\")"]` | 4.688 ms (5%) | 0.000 ns | 7.63 MiB (1%) | 12 |
| `["io", "serialization", "(\"serialize\", \"Vector{String}\")"]` | 189.664 μs (5%) | 0.000 ns | 159.42 KiB (1%) | 514 |
| `["io", "skipchars"]` | 157.291 ms (5%) | 0.000 ns | 2.09 KiB (1%) | 18 |
| `["linalg", "arithmetic", "(\"*\", \"Matrix\", \"Matrix\", 1024)"]` | 27.735 ms (45%) | 0.000 ns | 8.00 MiB (1%) | 2 |
| `["linalg", "arithmetic", "(\"*\", \"Matrix\", \"Matrix\", 256)"]` | 565.555 μs (45%) | 0.000 ns | 512.08 KiB (1%) | 2 |
| `["linalg", "arithmetic", "(\"*\", \"Matrix\", \"Vector\", 1024)"]` | 331.765 μs (45%) | 0.000 ns | 8.13 KiB (1%) | 1 |
| `["linalg", "arithmetic", "(\"*\", \"Matrix\", \"Vector\", 256)"]` | 6.549 μs (45%) | 0.000 ns | 2.13 KiB (1%) | 1 |
| `["linalg", "arithmetic", "(\"*\", \"typename(Bidiagonal)\", \"Vector\", 1024)"]` | 2.335 μs (45%) | 0.000 ns | 16.25 KiB (1%) | 2 |
| `["linalg", "arithmetic", "(\"*\", \"typename(Bidiagonal)\", \"Vector\", 256)"]` | 1.010 μs (45%) | 0.000 ns | 4.25 KiB (1%) | 2 |
| `["linalg", "arithmetic", "(\"*\", \"typename(Bidiagonal)\", \"typename(Bidiagonal)\", 1024)"]` | 346.103 μs (45%) | 0.000 ns | 153.47 KiB (1%) | 27 |
| `["linalg", "arithmetic", "(\"*\", \"typename(Bidiagonal)\", \"typename(Bidiagonal)\", 256)"]` | 57.081 μs (45%) | 0.000 ns | 39.22 KiB (1%) | 23 |
| `["linalg", "arithmetic", "(\"*\", \"typename(Diagonal)\", \"Vector\", 1024)"]` | 855.000 ns (45%) | 0.000 ns | 8.13 KiB (1%) | 1 |
| `["linalg", "arithmetic", "(\"*\", \"typename(Diagonal)\", \"Vector\", 256)"]` | 335.000 ns (45%) | 0.000 ns | 2.13 KiB (1%) | 1 |
| `["linalg", "arithmetic", "(\"*\", \"typename(Diagonal)\", \"typename(Diagonal)\", 1024)"]` | 815.000 ns (45%) | 0.000 ns | 8.13 KiB (1%) | 1 |
| `["linalg", "arithmetic", "(\"*\", \"typename(Diagonal)\", \"typename(Diagonal)\", 256)"]` | 347.000 ns (45%) | 0.000 ns | 2.13 KiB (1%) | 1 |
| `["linalg", "arithmetic", "(\"*\", \"typename(LowerTriangular)\", \"Vector\", 1024)"]` | 180.273 μs (45%) | 0.000 ns | 8.13 KiB (1%) | 1 |
| `["linalg", "arithmetic", "(\"*\", \"typename(LowerTriangular)\", \"Vector\", 256)"]` | 6.867 μs (45%) | 0.000 ns | 2.13 KiB (1%) | 1 |
| `["linalg", "arithmetic", "(\"*\", \"typename(LowerTriangular)\", \"typename(LowerTriangular)\", 1024)"]` | 16.219 ms (45%) | 0.000 ns | 8.00 MiB (1%) | 2 |
| `["linalg", "arithmetic", "(\"*\", \"typename(LowerTriangular)\", \"typename(LowerTriangular)\", 256)"]` | 447.545 μs (45%) | 0.000 ns | 512.08 KiB (1%) | 2 |
| `["linalg", "arithmetic", "(\"*\", \"typename(SymTridiagonal)\", \"Vector\", 1024)"]` | 1.341 μs (45%) | 0.000 ns | 8.13 KiB (1%) | 1 |
| `["linalg", "arithmetic", "(\"*\", \"typename(SymTridiagonal)\", \"Vector\", 256)"]` | 517.000 ns (45%) | 0.000 ns | 2.13 KiB (1%) | 1 |
| `["linalg", "arithmetic", "(\"*\", \"typename(SymTridiagonal)\", \"typename(SymTridiagonal)\", 1024)"]` | 530.116 μs (45%) | 0.000 ns | 265.34 KiB (1%) | 27 |
| `["linalg", "arithmetic", "(\"*\", \"typename(SymTridiagonal)\", \"typename(SymTridiagonal)\", 256)"]` | 85.846 μs (45%) | 0.000 ns | 67.09 KiB (1%) | 23 |
| `["linalg", "arithmetic", "(\"*\", \"typename(Tridiagonal)\", \"Vector\", 1024)"]` | 1.569 μs (45%) | 0.000 ns | 8.13 KiB (1%) | 1 |
| `["linalg", "arithmetic", "(\"*\", \"typename(Tridiagonal)\", \"Vector\", 256)"]` | 496.000 ns (45%) | 0.000 ns | 2.13 KiB (1%) | 1 |
| `["linalg", "arithmetic", "(\"*\", \"typename(Tridiagonal)\", \"typename(Tridiagonal)\", 1024)"]` | 537.598 μs (45%) | 0.000 ns | 265.34 KiB (1%) | 27 |
| `["linalg", "arithmetic", "(\"*\", \"typename(Tridiagonal)\", \"typename(Tridiagonal)\", 256)"]` | 87.826 μs (45%) | 0.000 ns | 67.09 KiB (1%) | 23 |
| `["linalg", "arithmetic", "(\"*\", \"typename(UpperTriangular)\", \"Vector\", 1024)"]` | 178.906 μs (45%) | 0.000 ns | 8.13 KiB (1%) | 1 |
| `["linalg", "arithmetic", "(\"*\", \"typename(UpperTriangular)\", \"Vector\", 256)"]` | 6.499 μs (45%) | 0.000 ns | 2.13 KiB (1%) | 1 |
| `["linalg", "arithmetic", "(\"*\", \"typename(UpperTriangular)\", \"typename(UpperTriangular)\", 1024)"]` | 17.103 ms (45%) | 0.000 ns | 8.00 MiB (1%) | 2 |
| `["linalg", "arithmetic", "(\"*\", \"typename(UpperTriangular)\", \"typename(UpperTriangular)\", 256)"]` | 467.019 μs (45%) | 0.000 ns | 512.08 KiB (1%) | 2 |
| `["linalg", "arithmetic", "(\"+\", \"Matrix\", \"Matrix\", 1024)"]` | 1.043 ms (45%) | 0.000 ns | 8.00 MiB (1%) | 2 |
| `["linalg", "arithmetic", "(\"+\", \"Matrix\", \"Matrix\", 256)"]` | 204.922 μs (45%) | 0.000 ns | 512.08 KiB (1%) | 2 |
| `["linalg", "arithmetic", "(\"+\", \"Vector\", \"Vector\", 1024)"]` | 838.000 ns (45%) | 0.000 ns | 8.13 KiB (1%) | 1 |
| `["linalg", "arithmetic", "(\"+\", \"Vector\", \"Vector\", 256)"]` | 358.000 ns (45%) | 0.000 ns | 2.13 KiB (1%) | 1 |
| `["linalg", "arithmetic", "(\"+\", \"typename(Bidiagonal)\", \"typename(Bidiagonal)\", 1024)"]` | 2.029 μs (45%) | 0.000 ns | 16.28 KiB (1%) | 3 |
| `["linalg", "arithmetic", "(\"+\", \"typename(Bidiagonal)\", \"typename(Bidiagonal)\", 256)"]` | 985.000 ns (45%) | 0.000 ns | 4.28 KiB (1%) | 3 |
| `["linalg", "arithmetic", "(\"+\", \"typename(Diagonal)\", \"typename(Diagonal)\", 1024)"]` | 750.000 ns (45%) | 0.000 ns | 8.13 KiB (1%) | 1 |
| `["linalg", "arithmetic", "(\"+\", \"typename(Diagonal)\", \"typename(Diagonal)\", 256)"]` | 362.000 ns (45%) | 0.000 ns | 2.13 KiB (1%) | 1 |
| `["linalg", "arithmetic", "(\"+\", \"typename(LowerTriangular)\", \"typename(LowerTriangular)\", 1024)"]` | 1.052 ms (45%) | 0.000 ns | 8.00 MiB (1%) | 2 |
| `["linalg", "arithmetic", "(\"+\", \"typename(LowerTriangular)\", \"typename(LowerTriangular)\", 256)"]` | 61.673 μs (45%) | 0.000 ns | 512.08 KiB (1%) | 2 |
| `["linalg", "arithmetic", "(\"+\", \"typename(SymTridiagonal)\", \"typename(SymTridiagonal)\", 1024)"]` | 1.922 μs (45%) | 0.000 ns | 16.25 KiB (1%) | 2 |
| `["linalg", "arithmetic", "(\"+\", \"typename(SymTridiagonal)\", \"typename(SymTridiagonal)\", 256)"]` | 1.063 μs (45%) | 0.000 ns | 4.25 KiB (1%) | 2 |
| `["linalg", "arithmetic", "(\"+\", \"typename(Tridiagonal)\", \"typename(Tridiagonal)\", 1024)"]` | 3.140 μs (45%) | 0.000 ns | 24.42 KiB (1%) | 4 |
| `["linalg", "arithmetic", "(\"+\", \"typename(Tridiagonal)\", \"typename(Tridiagonal)\", 256)"]` | 1.501 μs (45%) | 0.000 ns | 6.42 KiB (1%) | 4 |
| `["linalg", "arithmetic", "(\"+\", \"typename(UpperTriangular)\", \"typename(UpperTriangular)\", 1024)"]` | 1.041 ms (45%) | 0.000 ns | 8.00 MiB (1%) | 2 |
| `["linalg", "arithmetic", "(\"+\", \"typename(UpperTriangular)\", \"typename(UpperTriangular)\", 256)"]` | 61.295 μs (45%) | 0.000 ns | 512.08 KiB (1%) | 2 |
| `["linalg", "arithmetic", "(\"-\", \"Matrix\", \"Matrix\", 1024)"]` | 1.043 ms (45%) | 0.000 ns | 8.00 MiB (1%) | 2 |
| `["linalg", "arithmetic", "(\"-\", \"Matrix\", \"Matrix\", 256)"]` | 58.830 μs (45%) | 0.000 ns | 512.08 KiB (1%) | 2 |
| `["linalg", "arithmetic", "(\"-\", \"Vector\", \"Vector\", 1024)"]` | 819.000 ns (45%) | 0.000 ns | 8.13 KiB (1%) | 1 |
| `["linalg", "arithmetic", "(\"-\", \"Vector\", \"Vector\", 256)"]` | 317.000 ns (45%) | 0.000 ns | 2.13 KiB (1%) | 1 |
| `["linalg", "arithmetic", "(\"-\", \"typename(Bidiagonal)\", \"typename(Bidiagonal)\", 1024)"]` | 2.056 μs (45%) | 0.000 ns | 16.28 KiB (1%) | 3 |
| `["linalg", "arithmetic", "(\"-\", \"typename(Bidiagonal)\", \"typename(Bidiagonal)\", 256)"]` | 972.000 ns (45%) | 0.000 ns | 4.28 KiB (1%) | 3 |
| `["linalg", "arithmetic", "(\"-\", \"typename(Diagonal)\", \"typename(Diagonal)\", 1024)"]` | 829.000 ns (45%) | 0.000 ns | 8.13 KiB (1%) | 1 |
| `["linalg", "arithmetic", "(\"-\", \"typename(Diagonal)\", \"typename(Diagonal)\", 256)"]` | 353.000 ns (45%) | 0.000 ns | 2.13 KiB (1%) | 1 |
| `["linalg", "arithmetic", "(\"-\", \"typename(LowerTriangular)\", \"typename(LowerTriangular)\", 1024)"]` | 1.048 ms (45%) | 0.000 ns | 8.00 MiB (1%) | 2 |
| `["linalg", "arithmetic", "(\"-\", \"typename(LowerTriangular)\", \"typename(LowerTriangular)\", 256)"]` | 57.970 μs (45%) | 0.000 ns | 512.08 KiB (1%) | 2 |
| `["linalg", "arithmetic", "(\"-\", \"typename(SymTridiagonal)\", \"typename(SymTridiagonal)\", 1024)"]` | 1.899 μs (45%) | 0.000 ns | 16.25 KiB (1%) | 2 |
| `["linalg", "arithmetic", "(\"-\", \"typename(SymTridiagonal)\", \"typename(SymTridiagonal)\", 256)"]` | 1.068 μs (45%) | 0.000 ns | 4.25 KiB (1%) | 2 |
| `["linalg", "arithmetic", "(\"-\", \"typename(Tridiagonal)\", \"typename(Tridiagonal)\", 1024)"]` | 3.131 μs (45%) | 0.000 ns | 24.42 KiB (1%) | 4 |
| `["linalg", "arithmetic", "(\"-\", \"typename(Tridiagonal)\", \"typename(Tridiagonal)\", 256)"]` | 1.490 μs (45%) | 0.000 ns | 6.42 KiB (1%) | 4 |
| `["linalg", "arithmetic", "(\"-\", \"typename(UpperTriangular)\", \"typename(UpperTriangular)\", 1024)"]` | 1.041 ms (45%) | 0.000 ns | 8.00 MiB (1%) | 2 |
| `["linalg", "arithmetic", "(\"-\", \"typename(UpperTriangular)\", \"typename(UpperTriangular)\", 256)"]` | 59.485 μs (45%) | 0.000 ns | 512.08 KiB (1%) | 2 |
| `["linalg", "arithmetic", "(\"/\", \"Matrix\", \"Matrix\", 1024)"]` | 105.324 ms (45%) | 0.000 ns | 24.01 MiB (1%) | 7 |
| `["linalg", "arithmetic", "(\"/\", \"Matrix\", \"Matrix\", 256)"]` | 3.959 ms (45%) | 0.000 ns | 1.50 MiB (1%) | 7 |
| `["linalg", "arithmetic", "(\"/\", \"typename(Diagonal)\", \"typename(Diagonal)\", 1024)"]` | 904.000 ns (45%) | 0.000 ns | 8.13 KiB (1%) | 1 |
| `["linalg", "arithmetic", "(\"/\", \"typename(Diagonal)\", \"typename(Diagonal)\", 256)"]` | 420.000 ns (45%) | 0.000 ns | 2.13 KiB (1%) | 1 |
| `["linalg", "arithmetic", "(\"/\", \"typename(LowerTriangular)\", \"typename(LowerTriangular)\", 1024)"]` | 29.173 ms (45%) | 0.000 ns | 8.00 MiB (1%) | 2 |
| `["linalg", "arithmetic", "(\"/\", \"typename(LowerTriangular)\", \"typename(LowerTriangular)\", 256)"]` | 1.019 ms (45%) | 0.000 ns | 512.08 KiB (1%) | 2 |
| `["linalg", "arithmetic", "(\"/\", \"typename(UpperTriangular)\", \"typename(UpperTriangular)\", 1024)"]` | 29.282 ms (45%) | 0.000 ns | 8.00 MiB (1%) | 2 |
| `["linalg", "arithmetic", "(\"/\", \"typename(UpperTriangular)\", \"typename(UpperTriangular)\", 256)"]` | 1.025 ms (45%) | 0.000 ns | 512.08 KiB (1%) | 2 |
| `["linalg", "arithmetic", "(\"3-arg mul!\", 2)"]` | 38.000 ns (45%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["linalg", "arithmetic", "(\"3-arg mul!\", 3)"]` | 45.000 ns (45%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["linalg", "arithmetic", "(\"5-arg mul!\", 2)"]` | 67.000 ns (45%) | 0.000 ns | 32 bytes (1%) | 1 |
| `["linalg", "arithmetic", "(\"5-arg mul!\", 3)"]` | 73.000 ns (45%) | 0.000 ns | 32 bytes (1%) | 1 |
| `["linalg", "arithmetic", "(\"\\\\\", \"HermitianSparseWithNonZeroPivots\", \"Vector\", 1024)"]` | 833.612 μs (45%) | 0.000 ns | 620.58 KiB (1%) | 58 |
| `["linalg", "arithmetic", "(\"\\\\\", \"HermitianSparseWithNonZeroPivots\", \"Vector\", 256)"]` | 174.728 μs (45%) | 0.000 ns | 148.06 KiB (1%) | 58 |
| `["linalg", "arithmetic", "(\"\\\\\", \"Matrix\", \"Matrix\", 1024)"]` | 93.352 ms (45%) | 0.000 ns | 16.01 MiB (1%) | 5 |
| `["linalg", "arithmetic", "(\"\\\\\", \"Matrix\", \"Matrix\", 256)"]` | 3.549 ms (45%) | 0.000 ns | 1.00 MiB (1%) | 5 |
| `["linalg", "arithmetic", "(\"\\\\\", \"Matrix\", \"Vector\", 1024)"]` | 21.691 ms (45%) | 0.000 ns | 8.02 MiB (1%) | 4 |
| `["linalg", "arithmetic", "(\"\\\\\", \"Matrix\", \"Vector\", 256)"]` | 675.442 μs (45%) | 0.000 ns | 516.33 KiB (1%) | 4 |
| `["linalg", "arithmetic", "(\"\\\\\", \"typename(Bidiagonal)\", \"Vector\", 1024)"]` | 8.240 μs (45%) | 0.000 ns | 8.13 KiB (1%) | 1 |
| `["linalg", "arithmetic", "(\"\\\\\", \"typename(Bidiagonal)\", \"Vector\", 256)"]` | 2.012 μs (45%) | 0.000 ns | 2.13 KiB (1%) | 1 |
| `["linalg", "arithmetic", "(\"\\\\\", \"typename(Diagonal)\", \"Vector\", 1024)"]` | 994.000 ns (45%) | 0.000 ns | 8.13 KiB (1%) | 1 |
| `["linalg", "arithmetic", "(\"\\\\\", \"typename(Diagonal)\", \"Vector\", 256)"]` | 421.000 ns (45%) | 0.000 ns | 2.13 KiB (1%) | 1 |
| `["linalg", "arithmetic", "(\"\\\\\", \"typename(Diagonal)\", \"typename(Diagonal)\", 1024)"]` | 964.000 ns (45%) | 0.000 ns | 8.13 KiB (1%) | 1 |
| `["linalg", "arithmetic", "(\"\\\\\", \"typename(Diagonal)\", \"typename(Diagonal)\", 256)"]` | 423.000 ns (45%) | 0.000 ns | 2.13 KiB (1%) | 1 |
| `["linalg", "arithmetic", "(\"\\\\\", \"typename(LowerTriangular)\", \"Vector\", 1024)"]` | 180.788 μs (45%) | 0.000 ns | 8.13 KiB (1%) | 1 |
| `["linalg", "arithmetic", "(\"\\\\\", \"typename(LowerTriangular)\", \"Vector\", 256)"]` | 6.720 μs (45%) | 0.000 ns | 2.13 KiB (1%) | 1 |
| `["linalg", "arithmetic", "(\"\\\\\", \"typename(LowerTriangular)\", \"typename(LowerTriangular)\", 1024)"]` | 33.514 ms (45%) | 0.000 ns | 8.00 MiB (1%) | 2 |
| `["linalg", "arithmetic", "(\"\\\\\", \"typename(LowerTriangular)\", \"typename(LowerTriangular)\", 256)"]` | 1.307 ms (45%) | 0.000 ns | 512.08 KiB (1%) | 2 |
| `["linalg", "arithmetic", "(\"\\\\\", \"typename(SymTridiagonal)\", \"Vector\", 1024)"]` | 17.339 μs (45%) | 0.000 ns | 24.38 KiB (1%) | 3 |
| `["linalg", "arithmetic", "(\"\\\\\", \"typename(SymTridiagonal)\", \"Vector\", 256)"]` | 4.502 μs (45%) | 0.000 ns | 6.38 KiB (1%) | 3 |
| `["linalg", "arithmetic", "(\"\\\\\", \"typename(Tridiagonal)\", \"Vector\", 1024)"]` | 29.592 μs (45%) | 0.000 ns | 48.84 KiB (1%) | 8 |
| `["linalg", "arithmetic", "(\"\\\\\", \"typename(Tridiagonal)\", \"Vector\", 256)"]` | 8.333 μs (45%) | 0.000 ns | 12.84 KiB (1%) | 8 |
| `["linalg", "arithmetic", "(\"\\\\\", \"typename(UpperTriangular)\", \"Vector\", 1024)"]` | 178.940 μs (45%) | 0.000 ns | 8.13 KiB (1%) | 1 |
| `["linalg", "arithmetic", "(\"\\\\\", \"typename(UpperTriangular)\", \"Vector\", 256)"]` | 6.634 μs (45%) | 0.000 ns | 2.13 KiB (1%) | 1 |
| `["linalg", "arithmetic", "(\"\\\\\", \"typename(UpperTriangular)\", \"typename(UpperTriangular)\", 1024)"]` | 40.428 ms (45%) | 0.000 ns | 8.00 MiB (1%) | 2 |
| `["linalg", "arithmetic", "(\"\\\\\", \"typename(UpperTriangular)\", \"typename(UpperTriangular)\", 256)"]` | 1.738 ms (45%) | 0.000 ns | 512.08 KiB (1%) | 2 |
| `["linalg", "arithmetic", "(\"cumsum!\", Float32, 1024)"]` | 1.201 μs (45%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["linalg", "arithmetic", "(\"cumsum!\", Float32, 256)"]` | 330.000 ns (45%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["linalg", "arithmetic", "(\"cumsum!\", Float64, 1024)"]` | 1.198 μs (45%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["linalg", "arithmetic", "(\"cumsum!\", Float64, 256)"]` | 330.000 ns (45%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["linalg", "arithmetic", "(\"cumsum!\", Int32, 1024)"]` | 581.000 ns (45%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["linalg", "arithmetic", "(\"cumsum!\", Int32, 256)"]` | 170.000 ns (45%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["linalg", "arithmetic", "(\"cumsum!\", Int64, 1024)"]` | 340.000 ns (45%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["linalg", "arithmetic", "(\"cumsum!\", Int64, 256)"]` | 116.000 ns (45%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["linalg", "arithmetic", "(\"exp\", \"typename(Hermitian)\", 1024)"]` | 751.009 ms (45%) | 0.000 ns | 80.82 MiB (1%) | 22 |
| `["linalg", "arithmetic", "(\"exp\", \"typename(Hermitian)\", 256)"]` | 18.765 ms (45%) | 0.000 ns | 5.21 MiB (1%) | 22 |
| `["linalg", "arithmetic", "(\"log\", \"typename(Hermitian)\", 1024)"]` | 754.445 ms (45%) | 0.000 ns | 80.85 MiB (1%) | 23 |
| `["linalg", "arithmetic", "(\"log\", \"typename(Hermitian)\", 256)"]` | 18.913 ms (45%) | 0.000 ns | 5.21 MiB (1%) | 23 |
| `["linalg", "arithmetic", "(\"mul!\", \"Matrix{Float32}\", \"Matrix{Float64}\", \"Matrix{Float64}\", 1024)"]` | 945.273 ms (45%) | 0.000 ns | 336 bytes (1%) | 6 |
| `["linalg", "arithmetic", "(\"mul!\", \"Matrix{Float32}\", \"Matrix{Float64}\", \"Matrix{Float64}\", 256)"]` | 14.708 ms (45%) | 0.000 ns | 336 bytes (1%) | 6 |
| `["linalg", "arithmetic", "(\"sqrt\", \"NPDUpperTriangular\", 1024)"]` | 553.458 ms (45%) | 0.000 ns | 16.00 MiB (1%) | 3 |
| `["linalg", "arithmetic", "(\"sqrt\", \"NPDUpperTriangular\", 256)"]` | 5.476 ms (45%) | 0.000 ns | 1.00 MiB (1%) | 3 |
| `["linalg", "arithmetic", "(\"sqrt\", \"typename(Hermitian)\", 1024)"]` | 753.599 ms (45%) | 0.000 ns | 80.85 MiB (1%) | 23 |
| `["linalg", "arithmetic", "(\"sqrt\", \"typename(Hermitian)\", 256)"]` | 18.867 ms (45%) | 0.000 ns | 5.21 MiB (1%) | 23 |
| `["linalg", "arithmetic", "(\"sqrt\", \"typename(UnitUpperTriangular)\", 1024)"]` | 454.302 ms (45%) | 0.000 ns | 8.00 MiB (1%) | 2 |
| `["linalg", "arithmetic", "(\"sqrt\", \"typename(UnitUpperTriangular)\", 256)"]` | 3.389 ms (45%) | 0.000 ns | 512.08 KiB (1%) | 2 |
| `["linalg", "arithmetic", "(\"sqrt\", \"typename(UpperTriangular)\", 1024)"]` | 454.548 ms (45%) | 0.000 ns | 8.00 MiB (1%) | 3 |
| `["linalg", "arithmetic", "(\"sqrt\", \"typename(UpperTriangular)\", 256)"]` | 3.504 ms (45%) | 0.000 ns | 512.09 KiB (1%) | 3 |
| `["linalg", "blas", "asum"]` | 54.597 ns (40%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["linalg", "blas", "axpy!"]` | 152.971 ns (40%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["linalg", "blas", "blascopy!"]` | 154.161 ns (40%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["linalg", "blas", "dot"]` | 57.614 ns (40%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["linalg", "blas", "dotc"]` | 246.393 ns (40%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["linalg", "blas", "dotu"]` | 246.341 ns (40%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["linalg", "blas", "gbmv!"]` | 271.402 μs (40%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["linalg", "blas", "gbmv"]` | 272.827 μs (40%) | 0.000 ns | 8.13 KiB (1%) | 1 |
| `["linalg", "blas", "gemm!"]` | 26.889 ms (40%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["linalg", "blas", "gemm"]` | 27.745 ms (40%) | 0.000 ns | 8.00 MiB (1%) | 2 |
| `["linalg", "blas", "gemv!"]` | 326.686 μs (40%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["linalg", "blas", "gemv"]` | 328.870 μs (40%) | 0.000 ns | 8.13 KiB (1%) | 1 |
| `["linalg", "blas", "ger!"]` | 697.633 μs (40%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["linalg", "blas", "her!"]` | 1.342 ms (40%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["linalg", "blas", "herk!"]` | 62.616 ms (40%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["linalg", "blas", "herk"]` | 65.229 ms (40%) | 0.000 ns | 16.00 MiB (1%) | 2 |
| `["linalg", "blas", "nrm2"]` | 385.658 ns (40%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["linalg", "blas", "sbmv!"]` | 242.944 μs (40%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["linalg", "blas", "sbmv"]` | 242.628 μs (40%) | 0.000 ns | 8.13 KiB (1%) | 1 |
| `["linalg", "blas", "scal!"]` | 150.198 ns (40%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["linalg", "blas", "scal"]` | 1.767 μs (40%) | 0.000 ns | 8.13 KiB (1%) | 1 |
| `["linalg", "blas", "symm!"]` | 27.389 ms (40%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["linalg", "blas", "symm"]` | 28.365 ms (40%) | 0.000 ns | 8.00 MiB (1%) | 2 |
| `["linalg", "blas", "symv!"]` | 175.753 μs (40%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["linalg", "blas", "symv"]` | 171.573 μs (40%) | 0.000 ns | 8.13 KiB (1%) | 1 |
| `["linalg", "blas", "syr!"]` | 549.219 μs (40%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["linalg", "blas", "syrk!"]` | 14.631 ms (40%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["linalg", "blas", "syrk"]` | 15.152 ms (40%) | 0.000 ns | 8.00 MiB (1%) | 2 |
| `["linalg", "blas", "trmm!"]` | 15.191 ms (40%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["linalg", "blas", "trmm"]` | 16.888 ms (40%) | 0.000 ns | 8.00 MiB (1%) | 2 |
| `["linalg", "blas", "trmv!"]` | 176.686 μs (40%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["linalg", "blas", "trmv"]` | 179.087 μs (40%) | 0.000 ns | 8.13 KiB (1%) | 1 |
| `["linalg", "blas", "trsm!"]` | 38.519 ms (40%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["linalg", "blas", "trsm"]` | 40.346 ms (40%) | 0.000 ns | 8.00 MiB (1%) | 2 |
| `["linalg", "blas", "trsv!"]` | 192.806 μs (40%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["linalg", "blas", "trsv"]` | 187.024 μs (40%) | 0.000 ns | 8.13 KiB (1%) | 1 |
| `["linalg", "factorization", "(\"cholesky\", \"Matrix\", 1024)"]` | 15.685 ms (45%) | 0.000 ns | 8.00 MiB (1%) | 4 |
| `["linalg", "factorization", "(\"cholesky\", \"Matrix\", 256)"]` | 496.417 μs (45%) | 0.000 ns | 512.13 KiB (1%) | 4 |
| `["linalg", "factorization", "(\"eigen\", \"Matrix\", 1024)"]` | 1.147 s (45%) | 0.000 ns | 33.09 MiB (1%) | 21 |
| `["linalg", "factorization", "(\"eigen\", \"Matrix\", 256)"]` | 45.474 ms (45%) | 0.000 ns | 2.27 MiB (1%) | 21 |
| `["linalg", "factorization", "(\"eigen\", \"typename(Bidiagonal)\", 1024)"]` | 3.519 ms (45%) | 0.000 ns | 8.01 MiB (1%) | 10 |
| `["linalg", "factorization", "(\"eigen\", \"typename(Bidiagonal)\", 256)"]` | 220.298 μs (45%) | 0.000 ns | 514.55 KiB (1%) | 9 |
| `["linalg", "factorization", "(\"eigen\", \"typename(Diagonal)\", 1024)"]` | 795.534 μs (45%) | 0.000 ns | 8.00 MiB (1%) | 2 |
| `["linalg", "factorization", "(\"eigen\", \"typename(Diagonal)\", 256)"]` | 40.803 μs (45%) | 0.000 ns | 512.08 KiB (1%) | 2 |
| `["linalg", "factorization", "(\"eigen\", \"typename(LowerTriangular)\", 1024)"]` | 90.680 ms (45%) | 0.000 ns | 32.03 MiB (1%) | 13 |
| `["linalg", "factorization", "(\"eigen\", \"typename(LowerTriangular)\", 256)"]` | 2.409 ms (45%) | 0.000 ns | 2.01 MiB (1%) | 12 |
| `["linalg", "factorization", "(\"eigen\", \"typename(SymTridiagonal)\", 1024)"]` | 114.681 ms (45%) | 0.000 ns | 8.27 MiB (1%) | 12 |
| `["linalg", "factorization", "(\"eigen\", \"typename(SymTridiagonal)\", 256)"]` | 6.205 ms (45%) | 0.000 ns | 581.11 KiB (1%) | 12 |
| `["linalg", "factorization", "(\"eigen\", \"typename(UpperTriangular)\", 1024)"]` | 74.521 ms (45%) | 0.000 ns | 24.03 MiB (1%) | 11 |
| `["linalg", "factorization", "(\"eigen\", \"typename(UpperTriangular)\", 256)"]` | 1.921 ms (45%) | 0.000 ns | 1.51 MiB (1%) | 10 |
| `["linalg", "factorization", "(\"lu\", \"Matrix\", 1024)"]` | 21.211 ms (45%) | 0.000 ns | 8.01 MiB (1%) | 3 |
| `["linalg", "factorization", "(\"lu\", \"Matrix\", 256)"]` | 654.137 μs (45%) | 0.000 ns | 514.20 KiB (1%) | 3 |
| `["linalg", "factorization", "(\"lu\", \"typename(Tridiagonal)\", 1024)"]` | 15.744 μs (45%) | 0.000 ns | 40.72 KiB (1%) | 7 |
| `["linalg", "factorization", "(\"lu\", \"typename(Tridiagonal)\", 256)"]` | 4.495 μs (45%) | 0.000 ns | 10.72 KiB (1%) | 7 |
| `["linalg", "factorization", "(\"qr\", \"Matrix\", 1024)"]` | 43.046 ms (45%) | 0.000 ns | 8.56 MiB (1%) | 6 |
| `["linalg", "factorization", "(\"qr\", \"Matrix\", 256)"]` | 1.440 ms (45%) | 0.000 ns | 656.23 KiB (1%) | 6 |
| `["linalg", "factorization", "(\"schur\", \"Matrix\", 1024)"]` | 1.068 s (45%) | 0.000 ns | 16.30 MiB (1%) | 11 |
| `["linalg", "factorization", "(\"schur\", \"Matrix\", 256)"]` | 41.294 ms (45%) | 0.000 ns | 1.08 MiB (1%) | 11 |
| `["linalg", "factorization", "(\"svd\", \"Matrix\", 1024)"]` | 537.201 ms (45%) | 0.000 ns | 48.13 MiB (1%) | 11 |
| `["linalg", "factorization", "(\"svd\", \"Matrix\", 256)"]` | 12.159 ms (45%) | 0.000 ns | 3.03 MiB (1%) | 10 |
| `["linalg", "factorization", "(\"svd\", \"typename(Bidiagonal)\", 1024)"]` | 56.521 ms (45%) | 0.000 ns | 40.11 MiB (1%) | 12 |
| `["linalg", "factorization", "(\"svd\", \"typename(Bidiagonal)\", 256)"]` | 3.702 ms (45%) | 0.000 ns | 2.53 MiB (1%) | 11 |
| `["linalg", "factorization", "(\"svd\", \"typename(Diagonal)\", 1024)"]` | 15.291 ms (45%) | 0.000 ns | 802.92 KiB (1%) | 10273 |
| `["linalg", "factorization", "(\"svd\", \"typename(Diagonal)\", 256)"]` | 1.023 ms (45%) | 0.000 ns | 198.86 KiB (1%) | 2587 |
| `["linalg", "factorization", "(\"svd\", \"typename(LowerTriangular)\", 1024)"]` | 522.537 ms (45%) | 0.000 ns | 56.13 MiB (1%) | 13 |
| `["linalg", "factorization", "(\"svd\", \"typename(LowerTriangular)\", 256)"]` | 12.072 ms (45%) | 0.000 ns | 3.53 MiB (1%) | 12 |
| `["linalg", "factorization", "(\"svd\", \"typename(UpperTriangular)\", 1024)"]` | 521.660 ms (45%) | 0.000 ns | 56.13 MiB (1%) | 13 |
| `["linalg", "factorization", "(\"svd\", \"typename(UpperTriangular)\", 256)"]` | 12.051 ms (45%) | 0.000 ns | 3.53 MiB (1%) | 12 |
| `["linalg", "small exp #29116"]` | 1.428 μs (5%) | 0.000 ns | 2.22 KiB (1%) | 23 |
| `["micro", "fib"]` | 35.437 μs (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["micro", "mandel"]` | 155.176 μs (5%) | 0.000 ns | 4.44 KiB (1%) | 1 |
| `["micro", "parseint"]` | 116.068 μs (5%) | 0.000 ns | 93.75 KiB (1%) | 2000 |
| `["micro", "pisum"]` | 5.887 ms (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["micro", "printfd"]` | 1.394 ms (5%) | 0.000 ns | 1.07 MiB (1%) | 20013 |
| `["micro", "quicksort"]` | 362.432 μs (5%) | 0.000 ns | 39.14 KiB (1%) | 2 |
| `["micro", "randmatmul"]` | 28.441 ms (5%) | 0.000 ns | 22.89 MiB (1%) | 6 |
| `["micro", "randmatstat"]` | 7.188 ms (5%) | 0.000 ns | 14.91 MiB (1%) | 12002 |
| `["misc", "18129"]` | 16.667 ms (5%) | 0.000 ns | 1.80 MiB (1%) | 2521 |
| `["misc", "20517"]` | 9.098 μs (5%) | 0.000 ns | 1.14 KiB (1%) | 1 |
| `["misc", "23042", "ComplexF32"]` | 2.698 μs (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["misc", "23042", "ComplexF64"]` | 5.385 μs (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["misc", "23042", "Float32"]` | 1.449 μs (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["misc", "23042", "Float64"]` | 2.695 μs (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["misc", "afoldl", "Complex{Float64}"]` | 81.684 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["misc", "afoldl", "Float64"]` | 80.261 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["misc", "afoldl", "Int"]` | 37.029 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["misc", "allocation elision view", "conditional"]` | 109.900 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["misc", "allocation elision view", "no conditional"]` | 96.662 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["misc", "bitshift", "(\"Int\", \"Int\")"]` | 24.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["misc", "bitshift", "(\"Int\", \"UInt\")"]` | 24.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["misc", "bitshift", "(\"UInt32\", \"UInt32\")"]` | 24.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["misc", "bitshift", "(\"UInt\", \"UInt\")"]` | 24.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["misc", "fastmath many args"]` | 24.745 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["misc", "foldl", "foldl(+, filter(...))"]` | 3.502 μs (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["misc", "foldl", "foldl(+, filter(...); init = 0.0)"]` | 2.244 μs (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["misc", "foldl", "foldl(+, flatten(filter(...)))"]` | 73.820 μs (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["misc", "issue 12165", "Float16"]` | 4.738 ms (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["misc", "issue 12165", "Float32"]` | 5.020 ms (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["misc", "issue 12165", "Float64"]` | 4.161 ms (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["misc", "iterators", "sum(flatten(collect((i,i+1) for i in 1:1000))"]` | 155.743 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["misc", "iterators", "sum(flatten(fill(rand(50), 100))))"]` | 5.968 μs (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["misc", "iterators", "zip(1:1)"]` | 29.184 ns (5%) | 0.000 ns | 96 bytes (1%) | 1 |
| `["misc", "iterators", "zip(1:1, 1:1)"]` | 30.923 ns (5%) | 0.000 ns | 96 bytes (1%) | 1 |
| `["misc", "iterators", "zip(1:1, 1:1, 1:1)"]` | 33.630 ns (5%) | 0.000 ns | 112 bytes (1%) | 1 |
| `["misc", "iterators", "zip(1:1, 1:1, 1:1, 1:1)"]` | 36.904 ns (5%) | 0.000 ns | 112 bytes (1%) | 1 |
| `["misc", "iterators", "zip(1:1000)"]` | 1.216 μs (5%) | 0.000 ns | 7.94 KiB (1%) | 1 |
| `["misc", "iterators", "zip(1:1000, 1:1000)"]` | 2.970 μs (5%) | 0.000 ns | 15.75 KiB (1%) | 1 |
| `["misc", "iterators", "zip(1:1000, 1:1000, 1:1000)"]` | 2.557 μs (5%) | 0.000 ns | 23.52 KiB (1%) | 2 |
| `["misc", "iterators", "zip(1:1000, 1:1000, 1:1000, 1:1000)"]` | 3.123 μs (5%) | 0.000 ns | 31.33 KiB (1%) | 2 |
| `["misc", "julia", "(\"macroexpand\", \"evalpoly\")"]` | 464.000 ns (5%) | 0.000 ns | 32 bytes (1%) | 2 |
| `["misc", "julia", "(\"parse\", \"array\")"]` | 1.686 ms (5%) | 0.000 ns | 15.16 KiB (1%) | 210 |
| `["misc", "julia", "(\"parse\", \"function\")"]` | 189.144 μs (5%) | 0.000 ns | 2.27 KiB (1%) | 40 |
| `["misc", "julia", "(\"parse\", \"nested\")"]` | 2.829 ms (5%) | 0.000 ns | 28.31 KiB (1%) | 408 |
| `["misc", "parse", "Float64"]` | 44.866 μs (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["misc", "parse", "Int"]` | 26.959 μs (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["misc", "perf highdim generator"]` | 6.872 μs (5%) | 0.000 ns | 32.20 KiB (1%) | 3 |
| `["misc", "repeat", "(200, 1, 24)"]` | 4.363 μs (5%) | 0.000 ns | 39.53 KiB (1%) | 13 |
| `["misc", "repeat", "(200, 24, 1)"]` | 12.560 μs (5%) | 0.000 ns | 75.34 KiB (1%) | 14 |
| `["misc", "splatting", "(3, 3, 3)"]` | 15.070 μs (5%) | 0.000 ns | 6.25 KiB (1%) | 300 |
| `["parallel", "remotecall", "(\"identity\", 1024)"]` | 54.956 μs (5%) | 0.000 ns | 3.44 KiB (1%) | 37 |
| `["parallel", "remotecall", "(\"identity\", 2)"]` | 51.823 μs (5%) | 0.000 ns | 1.33 KiB (1%) | 33 |
| `["parallel", "remotecall", "(\"identity\", 4096)"]` | 59.734 μs (5%) | 0.000 ns | 9.59 KiB (1%) | 37 |
| `["parallel", "remotecall", "(\"identity\", 512)"]` | 53.633 μs (5%) | 0.000 ns | 2.42 KiB (1%) | 37 |
| `["parallel", "remotecall", "(\"identity\", 64)"]` | 53.019 μs (5%) | 0.000 ns | 1.48 KiB (1%) | 35 |
| `["problem", "chaosgame", "chaosgame"]` | 91.877 ms (5%) | 0.000 ns | 512.23 KiB (1%) | 6 |
| `["problem", "fem", "sparse_fem"]` | 199.970 ms (5%) | 0.000 ns | 120.01 MiB (1%) | 137 |
| `["problem", "go", "go_game"]` | 482.860 ms (5%) | 0.000 ns | 386.84 MiB (1%) | 2932663 |
| `["problem", "grigoriadis khachiyan", "grigoriadis_khachiyan"]` | 1.847 s (5%) | 139.915 ms | 3.57 GiB (1%) | 2448213 |
| `["problem", "imdb", "centrality"]` | 530.826 ms (5%) | 0.000 ns | 72.72 MiB (1%) | 442258 |
| `["problem", "json", "parse_json"]` | 582.290 μs (5%) | 0.000 ns | 342.91 KiB (1%) | 13741 |
| `["problem", "laplacian", "laplace_iter_devec"]` | 15.185 ms (5%) | 0.000 ns | 64.16 KiB (1%) | 4 |
| `["problem", "laplacian", "laplace_iter_sub"]` | 49.356 ms (5%) | 0.000 ns | 120.59 MiB (1%) | 8194 |
| `["problem", "laplacian", "laplace_iter_vec"]` | 31.036 ms (5%) | 0.000 ns | 120.59 MiB (1%) | 8194 |
| `["problem", "laplacian", "laplace_sparse_matvec"]` | 5.805 ms (5%) | 0.000 ns | 18.89 MiB (1%) | 200 |
| `["problem", "monte carlo", "euro_option_devec"]` | 38.910 ms (5%) | 0.000 ns | 156.41 KiB (1%) | 4 |
| `["problem", "monte carlo", "euro_option_vec"]` | 24.140 ms (5%) | 0.000 ns | 234.61 KiB (1%) | 6 |
| `["problem", "raytrace", "raytrace"]` | 351.044 ms (5%) | 0.000 ns | 198.95 MiB (1%) | 3841801 |
| `["problem", "seismic", "(\"seismic\", \"Float32\")"]` | 964.979 μs (5%) | 0.000 ns | 937.97 KiB (1%) | 12 |
| `["problem", "seismic", "(\"seismic\", \"Float64\")"]` | 1.288 ms (5%) | 0.000 ns | 1.83 MiB (1%) | 12 |
| `["problem", "simplex", "simplex"]` | 14.097 ms (5%) | 0.000 ns | 251.30 KiB (1%) | 17 |
| `["problem", "spellcheck", "spellcheck"]` | 3.258 s (5%) | 138.698 ms | 1.56 GiB (1%) | 23983143 |
| `["problem", "stockcorr", "stockcorr"]` | 178.774 ms (5%) | 0.000 ns | 231.32 MiB (1%) | 20013 |
| `["problem", "ziggurat", "ziggurat"]` | 10.298 s (5%) | 839.998 ms | 19.00 GiB (1%) | 13000002 |
| `["random", "collections", "(\"rand!\", \"ImplicitRNG\", \"'a':'z'\")"]` | 5.789 μs (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["random", "collections", "(\"rand!\", \"ImplicitRNG\", \"large BitSet\")"]` | 4.957 μs (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["random", "collections", "(\"rand!\", \"ImplicitRNG\", \"large Dict\")"]` | 25.250 μs (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["random", "collections", "(\"rand!\", \"ImplicitRNG\", \"large Set\")"]` | 24.688 μs (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["random", "collections", "(\"rand!\", \"ImplicitRNG\", \"large String\")"]` | 6.088 μs (25%) | 0.000 ns | 3.69 KiB (1%) | 1 |
| `["random", "collections", "(\"rand!\", \"ImplicitRNG\", \"large Vector\")"]` | 3.873 μs (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["random", "collections", "(\"rand!\", \"ImplicitRNG\", \"small BitSet\")"]` | 4.776 μs (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["random", "collections", "(\"rand!\", \"ImplicitRNG\", \"small Dict\")"]` | 38.794 μs (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["random", "collections", "(\"rand!\", \"ImplicitRNG\", \"small Set\")"]` | 38.483 μs (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["random", "collections", "(\"rand!\", \"ImplicitRNG\", \"small String\")"]` | 4.235 μs (25%) | 0.000 ns | 112 bytes (1%) | 1 |
| `["random", "collections", "(\"rand!\", \"ImplicitRNG\", \"small Vector\")"]` | 3.876 μs (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["random", "collections", "(\"rand!\", \"MersenneTwister\", \"'a':'z'\")"]` | 5.783 μs (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["random", "collections", "(\"rand!\", \"MersenneTwister\", \"large BitSet\")"]` | 4.772 μs (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["random", "collections", "(\"rand!\", \"MersenneTwister\", \"large Dict\")"]` | 25.082 μs (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["random", "collections", "(\"rand!\", \"MersenneTwister\", \"large Set\")"]` | 24.892 μs (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["random", "collections", "(\"rand!\", \"MersenneTwister\", \"large String\")"]` | 6.059 μs (25%) | 0.000 ns | 3.69 KiB (1%) | 1 |
| `["random", "collections", "(\"rand!\", \"MersenneTwister\", \"large Vector\")"]` | 3.873 μs (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["random", "collections", "(\"rand!\", \"MersenneTwister\", \"small BitSet\")"]` | 4.770 μs (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["random", "collections", "(\"rand!\", \"MersenneTwister\", \"small Dict\")"]` | 39.029 μs (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["random", "collections", "(\"rand!\", \"MersenneTwister\", \"small Set\")"]` | 39.000 μs (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["random", "collections", "(\"rand!\", \"MersenneTwister\", \"small String\")"]` | 4.218 μs (25%) | 0.000 ns | 112 bytes (1%) | 1 |
| `["random", "collections", "(\"rand!\", \"MersenneTwister\", \"small Vector\")"]` | 3.871 μs (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["random", "collections", "(\"rand!\", \"RandomDevice\", \"'a':'z'\")"]` | 62.141 μs (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["random", "collections", "(\"rand!\", \"RandomDevice\", \"large BitSet\")"]` | 62.404 μs (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["random", "collections", "(\"rand!\", \"RandomDevice\", \"large Dict\")"]` | 133.052 μs (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["random", "collections", "(\"rand!\", \"RandomDevice\", \"large Set\")"]` | 133.953 μs (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["random", "collections", "(\"rand!\", \"RandomDevice\", \"large String\")"]` | 63.264 μs (25%) | 0.000 ns | 3.69 KiB (1%) | 1 |
| `["random", "collections", "(\"rand!\", \"RandomDevice\", \"large Vector\")"]` | 61.015 μs (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["random", "collections", "(\"rand!\", \"RandomDevice\", \"small BitSet\")"]` | 62.166 μs (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["random", "collections", "(\"rand!\", \"RandomDevice\", \"small Dict\")"]` | 456.424 μs (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["random", "collections", "(\"rand!\", \"RandomDevice\", \"small Set\")"]` | 458.172 μs (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["random", "collections", "(\"rand!\", \"RandomDevice\", \"small String\")"]` | 61.363 μs (25%) | 0.000 ns | 112 bytes (1%) | 1 |
| `["random", "collections", "(\"rand!\", \"RandomDevice\", \"small Vector\")"]` | 60.831 μs (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["random", "collections", "(\"rand\", \"ImplicitRNG\", \"'a':'z'\")"]` | 40.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["random", "collections", "(\"rand\", \"ImplicitRNG\", \"large BitSet\")"]` | 51.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["random", "collections", "(\"rand\", \"ImplicitRNG\", \"large Dict\")"]` | 41.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["random", "collections", "(\"rand\", \"ImplicitRNG\", \"large Set\")"]` | 42.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["random", "collections", "(\"rand\", \"ImplicitRNG\", \"large String\")"]` | 35.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["random", "collections", "(\"rand\", \"ImplicitRNG\", \"large Vector\")"]` | 32.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["random", "collections", "(\"rand\", \"ImplicitRNG\", \"small BitSet\")"]` | 54.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["random", "collections", "(\"rand\", \"ImplicitRNG\", \"small Dict\")"]` | 42.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["random", "collections", "(\"rand\", \"ImplicitRNG\", \"small Set\")"]` | 38.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["random", "collections", "(\"rand\", \"ImplicitRNG\", \"small String\")"]` | 38.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["random", "collections", "(\"rand\", \"ImplicitRNG\", \"small Vector\")"]` | 34.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["random", "collections", "(\"rand\", \"MersenneTwister\", \"'a':'z'\")"]` | 36.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["random", "collections", "(\"rand\", \"MersenneTwister\", \"large BitSet\")"]` | 48.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["random", "collections", "(\"rand\", \"MersenneTwister\", \"large Dict\")"]` | 36.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["random", "collections", "(\"rand\", \"MersenneTwister\", \"large Set\")"]` | 34.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["random", "collections", "(\"rand\", \"MersenneTwister\", \"large String\")"]` | 35.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["random", "collections", "(\"rand\", \"MersenneTwister\", \"large Vector\")"]` | 28.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["random", "collections", "(\"rand\", \"MersenneTwister\", \"small BitSet\")"]` | 47.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["random", "collections", "(\"rand\", \"MersenneTwister\", \"small Dict\")"]` | 44.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["random", "collections", "(\"rand\", \"MersenneTwister\", \"small Set\")"]` | 31.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["random", "collections", "(\"rand\", \"MersenneTwister\", \"small String\")"]` | 34.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["random", "collections", "(\"rand\", \"MersenneTwister\", \"small Vector\")"]` | 28.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["random", "collections", "(\"rand\", \"RandomDevice\", \"'a':'z'\")"]` | 96.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["random", "collections", "(\"rand\", \"RandomDevice\", \"large BitSet\")"]` | 104.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["random", "collections", "(\"rand\", \"RandomDevice\", \"large Dict\")"]` | 92.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["random", "collections", "(\"rand\", \"RandomDevice\", \"large Set\")"]` | 89.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["random", "collections", "(\"rand\", \"RandomDevice\", \"large String\")"]` | 92.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["random", "collections", "(\"rand\", \"RandomDevice\", \"large Vector\")"]` | 85.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["random", "collections", "(\"rand\", \"RandomDevice\", \"small BitSet\")"]` | 104.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["random", "collections", "(\"rand\", \"RandomDevice\", \"small Dict\")"]` | 94.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["random", "collections", "(\"rand\", \"RandomDevice\", \"small Set\")"]` | 90.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["random", "collections", "(\"rand\", \"RandomDevice\", \"small String\")"]` | 92.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["random", "collections", "(\"rand\", \"RandomDevice\", \"small Vector\")"]` | 85.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["random", "randstring", "(\"randstring\", \"MersenneTwister\")"]` | 96.000 ns (25%) | 0.000 ns | 128 bytes (1%) | 2 |
| `["random", "randstring", "(\"randstring\", \"MersenneTwister\", 100)"]` | 430.000 ns (25%) | 0.000 ns | 320 bytes (1%) | 2 |
| `["random", "randstring", "(\"randstring\", \"MersenneTwister\", \"\\\"qwèrtï\\\"\")"]` | 162.000 ns (25%) | 0.000 ns | 256 bytes (1%) | 3 |
| `["random", "randstring", "(\"randstring\", \"MersenneTwister\", \"\\\"qwèrtï\\\"\", 100)"]` | 1.051 μs (25%) | 0.000 ns | 752 bytes (1%) | 3 |
| `["random", "randstring", "(\"randstring\", \"MersenneTwister\", \"collect(UInt8, \\\"qwerty\\\"\")"]` | 96.000 ns (25%) | 0.000 ns | 128 bytes (1%) | 2 |
| `["random", "randstring", "(\"randstring\", \"MersenneTwister\", \"collect(UInt8, \\\"qwerty\\\"\", 100)"]` | 430.000 ns (25%) | 0.000 ns | 320 bytes (1%) | 2 |
| `["random", "ranges", "(\"RangeGenerator\", \"BigInt\", \"1:170141183460469231731687303715884105728\")"]` | 87.000 ns (25%) | 0.000 ns | 56 bytes (1%) | 2 |
| `["random", "ranges", "(\"RangeGenerator\", \"BigInt\", \"1:18446744073709551615\")"]` | 88.000 ns (25%) | 0.000 ns | 48 bytes (1%) | 2 |
| `["random", "ranges", "(\"RangeGenerator\", \"BigInt\", \"1:18446744073709551616\")"]` | 88.000 ns (25%) | 0.000 ns | 56 bytes (1%) | 2 |
| `["random", "ranges", "(\"RangeGenerator\", \"BigInt\", \"1:1\")"]` | 77.000 ns (25%) | 0.000 ns | 48 bytes (1%) | 2 |
| `["random", "ranges", "(\"RangeGenerator\", \"BigInt\", \"1:2^10000\")"]` | 223.000 ns (25%) | 0.000 ns | 1.27 KiB (1%) | 2 |
| `["random", "ranges", "(\"RangeGenerator\", \"BigInt\", \"1:4294967295\")"]` | 88.000 ns (25%) | 0.000 ns | 48 bytes (1%) | 2 |
| `["random", "ranges", "(\"RangeGenerator\", \"BigInt\", \"1:4294967297\")"]` | 86.000 ns (25%) | 0.000 ns | 48 bytes (1%) | 2 |
| `["random", "ranges", "(\"RangeGenerator\", \"Bool\", \"true:true\")"]` | 27.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["random", "ranges", "(\"RangeGenerator\", \"Int128\", \"1:18446744073709551615\")"]` | 28.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["random", "ranges", "(\"RangeGenerator\", \"Int128\", \"1:18446744073709551616\")"]` | 28.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["random", "ranges", "(\"RangeGenerator\", \"Int128\", \"1:1\")"]` | 28.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["random", "ranges", "(\"RangeGenerator\", \"Int128\", \"1:4294967295\")"]` | 28.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["random", "ranges", "(\"RangeGenerator\", \"Int128\", \"1:4294967297\")"]` | 28.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["random", "ranges", "(\"RangeGenerator\", \"Int16\", \"1:1\")"]` | 26.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["random", "ranges", "(\"RangeGenerator\", \"Int32\", \"1:1\")"]` | 26.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["random", "ranges", "(\"RangeGenerator\", \"Int64\", \"1:1\")"]` | 27.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["random", "ranges", "(\"RangeGenerator\", \"Int64\", \"1:4294967295\")"]` | 27.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["random", "ranges", "(\"RangeGenerator\", \"Int64\", \"1:4294967297\")"]` | 27.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["random", "ranges", "(\"RangeGenerator\", \"Int8\", \"1:1\")"]` | 26.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["random", "ranges", "(\"RangeGenerator\", \"UInt128\", \"1:170141183460469231731687303715884105728\")"]` | 28.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["random", "ranges", "(\"RangeGenerator\", \"UInt128\", \"1:18446744073709551615\")"]` | 30.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["random", "ranges", "(\"RangeGenerator\", \"UInt128\", \"1:18446744073709551616\")"]` | 28.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["random", "ranges", "(\"RangeGenerator\", \"UInt128\", \"1:1\")"]` | 28.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["random", "ranges", "(\"RangeGenerator\", \"UInt128\", \"1:4294967295\")"]` | 28.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["random", "ranges", "(\"RangeGenerator\", \"UInt128\", \"1:4294967297\")"]` | 28.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["random", "ranges", "(\"RangeGenerator\", \"UInt16\", \"1:1\")"]` | 26.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["random", "ranges", "(\"RangeGenerator\", \"UInt32\", \"1:1\")"]` | 26.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["random", "ranges", "(\"RangeGenerator\", \"UInt32\", \"1:4294967295\")"]` | 26.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["random", "ranges", "(\"RangeGenerator\", \"UInt64\", \"1:18446744073709551615\")"]` | 27.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["random", "ranges", "(\"RangeGenerator\", \"UInt64\", \"1:1\")"]` | 27.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["random", "ranges", "(\"RangeGenerator\", \"UInt64\", \"1:4294967295\")"]` | 27.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["random", "ranges", "(\"RangeGenerator\", \"UInt64\", \"1:4294967297\")"]` | 27.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["random", "ranges", "(\"RangeGenerator\", \"UInt8\", \"1:1\")"]` | 26.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["random", "ranges", "(\"rand!\", \"ImplicitRNG\", \"Int\", \"1:1000\")"]` | 773.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["random", "ranges", "(\"rand!\", \"MersenneTwister\", \"Int\", \"1:1000\")"]` | 768.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["random", "ranges", "(\"rand!\", \"RandomDevice\", \"Int\", \"1:1000\")"]` | 12.071 μs (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["random", "ranges", "(\"rand\", \"ImplicitRNG\", \"Int\", \"1:1000\")"]` | 30.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["random", "ranges", "(\"rand\", \"MersenneTwister\", \"BigInt\", \"RangeGenerator(1:1)\")"]` | 140.000 ns (25%) | 0.000 ns | 48 bytes (1%) | 4 |
| `["random", "ranges", "(\"rand\", \"MersenneTwister\", \"BigInt\", \"RangeGenerator(1:170141183460469231731687303715884105728)\")"]` | 144.000 ns (25%) | 0.000 ns | 56 bytes (1%) | 4 |
| `["random", "ranges", "(\"rand\", \"MersenneTwister\", \"BigInt\", \"RangeGenerator(1:18446744073709551615)\")"]` | 141.000 ns (25%) | 0.000 ns | 48 bytes (1%) | 4 |
| `["random", "ranges", "(\"rand\", \"MersenneTwister\", \"BigInt\", \"RangeGenerator(1:18446744073709551616)\")"]` | 113.000 ns (25%) | 0.000 ns | 48 bytes (1%) | 3 |
| `["random", "ranges", "(\"rand\", \"MersenneTwister\", \"BigInt\", \"RangeGenerator(1:2^10000)\")"]` | 324.000 ns (25%) | 0.000 ns | 1.27 KiB (1%) | 4 |
| `["random", "ranges", "(\"rand\", \"MersenneTwister\", \"BigInt\", \"RangeGenerator(1:4294967295)\")"]` | 141.000 ns (25%) | 0.000 ns | 48 bytes (1%) | 4 |
| `["random", "ranges", "(\"rand\", \"MersenneTwister\", \"BigInt\", \"RangeGenerator(1:4294967297)\")"]` | 142.000 ns (25%) | 0.000 ns | 48 bytes (1%) | 4 |
| `["random", "ranges", "(\"rand\", \"MersenneTwister\", \"Bool\", \"RangeGenerator(true:true)\")"]` | 27.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["random", "ranges", "(\"rand\", \"MersenneTwister\", \"Int128\", \"RangeGenerator(1:1)\")"]` | 32.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["random", "ranges", "(\"rand\", \"MersenneTwister\", \"Int128\", \"RangeGenerator(1:18446744073709551615)\")"]` | 33.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["random", "ranges", "(\"rand\", \"MersenneTwister\", \"Int128\", \"RangeGenerator(1:18446744073709551616)\")"]` | 33.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["random", "ranges", "(\"rand\", \"MersenneTwister\", \"Int128\", \"RangeGenerator(1:4294967295)\")"]` | 32.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["random", "ranges", "(\"rand\", \"MersenneTwister\", \"Int128\", \"RangeGenerator(1:4294967297)\")"]` | 32.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["random", "ranges", "(\"rand\", \"MersenneTwister\", \"Int16\", \"RangeGenerator(1:1)\")"]` | 27.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["random", "ranges", "(\"rand\", \"MersenneTwister\", \"Int32\", \"RangeGenerator(1:1)\")"]` | 27.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["random", "ranges", "(\"rand\", \"MersenneTwister\", \"Int64\", \"RangeGenerator(1:1)\")"]` | 27.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["random", "ranges", "(\"rand\", \"MersenneTwister\", \"Int64\", \"RangeGenerator(1:4294967295)\")"]` | 27.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["random", "ranges", "(\"rand\", \"MersenneTwister\", \"Int64\", \"RangeGenerator(1:4294967297)\")"]` | 27.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["random", "ranges", "(\"rand\", \"MersenneTwister\", \"Int8\", \"RangeGenerator(1:1)\")"]` | 27.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["random", "ranges", "(\"rand\", \"MersenneTwister\", \"Int\", \"1:1000\")"]` | 28.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["random", "ranges", "(\"rand\", \"MersenneTwister\", \"UInt128\", \"RangeGenerator(1:1)\")"]` | 32.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["random", "ranges", "(\"rand\", \"MersenneTwister\", \"UInt128\", \"RangeGenerator(1:170141183460469231731687303715884105728)\")"]` | 33.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["random", "ranges", "(\"rand\", \"MersenneTwister\", \"UInt128\", \"RangeGenerator(1:18446744073709551615)\")"]` | 33.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["random", "ranges", "(\"rand\", \"MersenneTwister\", \"UInt128\", \"RangeGenerator(1:18446744073709551616)\")"]` | 33.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["random", "ranges", "(\"rand\", \"MersenneTwister\", \"UInt128\", \"RangeGenerator(1:4294967295)\")"]` | 32.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["random", "ranges", "(\"rand\", \"MersenneTwister\", \"UInt128\", \"RangeGenerator(1:4294967297)\")"]` | 32.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["random", "ranges", "(\"rand\", \"MersenneTwister\", \"UInt16\", \"RangeGenerator(1:1)\")"]` | 27.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["random", "ranges", "(\"rand\", \"MersenneTwister\", \"UInt32\", \"RangeGenerator(1:1)\")"]` | 27.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["random", "ranges", "(\"rand\", \"MersenneTwister\", \"UInt32\", \"RangeGenerator(1:4294967295)\")"]` | 31.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["random", "ranges", "(\"rand\", \"MersenneTwister\", \"UInt64\", \"RangeGenerator(1:1)\")"]` | 27.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["random", "ranges", "(\"rand\", \"MersenneTwister\", \"UInt64\", \"RangeGenerator(1:18446744073709551615)\")"]` | 34.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["random", "ranges", "(\"rand\", \"MersenneTwister\", \"UInt64\", \"RangeGenerator(1:4294967295)\")"]` | 27.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["random", "ranges", "(\"rand\", \"MersenneTwister\", \"UInt64\", \"RangeGenerator(1:4294967297)\")"]` | 27.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["random", "ranges", "(\"rand\", \"MersenneTwister\", \"UInt8\", \"RangeGenerator(1:1)\")"]` | 27.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["random", "ranges", "(\"rand\", \"RandomDevice\", \"Int\", \"1:1000\")"]` | 84.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["random", "sequences", "(\"randcycle\", \"MersenneTwister\", \"1000\")"]` | 7.231 μs (25%) | 0.000 ns | 7.94 KiB (1%) | 1 |
| `["random", "sequences", "(\"randcycle\", \"MersenneTwister\", \"5\")"]` | 70.000 ns (25%) | 0.000 ns | 128 bytes (1%) | 1 |
| `["random", "sequences", "(\"randperm\", \"MersenneTwister\", \"1000\")"]` | 6.521 μs (25%) | 0.000 ns | 7.94 KiB (1%) | 1 |
| `["random", "sequences", "(\"randperm\", \"MersenneTwister\", \"5\")"]` | 68.000 ns (25%) | 0.000 ns | 128 bytes (1%) | 1 |
| `["random", "sequences", "(\"randsubseq!\", \"MersenneTwister\", \"0.2\")"]` | 4.913 μs (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["random", "sequences", "(\"randsubseq!\", \"MersenneTwister\", \"0.8\")"]` | 8.867 μs (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["random", "sequences", "(\"shuffle!\", \"MersenneTwister\")"]` | 7.031 μs (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["random", "types", "(\"rand!\", \"ImplicitRNG\", \"Float64\")"]` | 876.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["random", "types", "(\"rand!\", \"ImplicitRNG\", \"Int64\")"]` | 1.166 μs (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["random", "types", "(\"rand!\", \"MersenneTwister\", \"Bool\")"]` | 131.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["random", "types", "(\"rand!\", \"MersenneTwister\", \"ComplexF16\")"]` | 3.391 μs (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["random", "types", "(\"rand!\", \"MersenneTwister\", \"ComplexF32\")"]` | 2.802 μs (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["random", "types", "(\"rand!\", \"MersenneTwister\", \"ComplexF64\")"]` | 2.105 μs (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["random", "types", "(\"rand!\", \"MersenneTwister\", \"Complex{Int128}\")"]` | 6.196 μs (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["random", "types", "(\"rand!\", \"MersenneTwister\", \"Complex{Int16}\")"]` | 1.937 μs (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["random", "types", "(\"rand!\", \"MersenneTwister\", \"Complex{Int32}\")"]` | 2.500 μs (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["random", "types", "(\"rand!\", \"MersenneTwister\", \"Complex{Int64}\")"]` | 9.430 μs (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["random", "types", "(\"rand!\", \"MersenneTwister\", \"Complex{Int8}\")"]` | 2.505 μs (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["random", "types", "(\"rand!\", \"MersenneTwister\", \"Complex{UInt128}\")"]` | 6.284 μs (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["random", "types", "(\"rand!\", \"MersenneTwister\", \"Complex{UInt16}\")"]` | 1.933 μs (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["random", "types", "(\"rand!\", \"MersenneTwister\", \"Complex{UInt32}\")"]` | 1.940 μs (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["random", "types", "(\"rand!\", \"MersenneTwister\", \"Complex{UInt64}\")"]` | 9.433 μs (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["random", "types", "(\"rand!\", \"MersenneTwister\", \"Complex{UInt8}\")"]` | 2.506 μs (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["random", "types", "(\"rand!\", \"MersenneTwister\", \"Float16\")"]` | 1.404 μs (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["random", "types", "(\"rand!\", \"MersenneTwister\", \"Float32\")"]` | 838.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["random", "types", "(\"rand!\", \"MersenneTwister\", \"Float64\")"]` | 872.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["random", "types", "(\"rand!\", \"MersenneTwister\", \"Int128\")"]` | 2.524 μs (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["random", "types", "(\"rand!\", \"MersenneTwister\", \"Int16\")"]` | 203.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["random", "types", "(\"rand!\", \"MersenneTwister\", \"Int32\")"]` | 705.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["random", "types", "(\"rand!\", \"MersenneTwister\", \"Int64\")"]` | 1.153 μs (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["random", "types", "(\"rand!\", \"MersenneTwister\", \"Int8\")"]` | 165.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["random", "types", "(\"rand!\", \"MersenneTwister\", \"UInt128\")"]` | 2.511 μs (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["random", "types", "(\"rand!\", \"MersenneTwister\", \"UInt16\")"]` | 210.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["random", "types", "(\"rand!\", \"MersenneTwister\", \"UInt32\")"]` | 701.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["random", "types", "(\"rand!\", \"MersenneTwister\", \"UInt64\")"]` | 1.149 μs (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["random", "types", "(\"rand!\", \"MersenneTwister\", \"UInt8\")"]` | 180.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["random", "types", "(\"rand!\", \"RandomDevice\", \"Float64\")"]` | 56.858 μs (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["random", "types", "(\"rand!\", \"RandomDevice\", \"Int64\")"]` | 187.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["random", "types", "(\"rand\", \"ImplicitRNG\", \"Float64\")"]` | 31.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["random", "types", "(\"rand\", \"ImplicitRNG\", \"ImplicitFloat64\")"]` | 30.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["random", "types", "(\"rand\", \"ImplicitRNG\", \"Int64\")"]` | 28.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["random", "types", "(\"rand\", \"MersenneTwister\", \"Bool\")"]` | 24.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["random", "types", "(\"rand\", \"MersenneTwister\", \"ComplexF16\")"]` | 27.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["random", "types", "(\"rand\", \"MersenneTwister\", \"ComplexF32\")"]` | 26.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["random", "types", "(\"rand\", \"MersenneTwister\", \"ComplexF64\")"]` | 26.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["random", "types", "(\"rand\", \"MersenneTwister\", \"Complex{Int128}\")"]` | 26.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["random", "types", "(\"rand\", \"MersenneTwister\", \"Complex{Int16}\")"]` | 25.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["random", "types", "(\"rand\", \"MersenneTwister\", \"Complex{Int32}\")"]` | 25.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["random", "types", "(\"rand\", \"MersenneTwister\", \"Complex{Int64}\")"]` | 32.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["random", "types", "(\"rand\", \"MersenneTwister\", \"Complex{Int8}\")"]` | 25.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["random", "types", "(\"rand\", \"MersenneTwister\", \"Complex{UInt128}\")"]` | 26.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["random", "types", "(\"rand\", \"MersenneTwister\", \"Complex{UInt16}\")"]` | 25.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["random", "types", "(\"rand\", \"MersenneTwister\", \"Complex{UInt32}\")"]` | 25.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["random", "types", "(\"rand\", \"MersenneTwister\", \"Complex{UInt64}\")"]` | 32.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["random", "types", "(\"rand\", \"MersenneTwister\", \"Complex{UInt8}\")"]` | 25.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["random", "types", "(\"rand\", \"MersenneTwister\", \"Float16\")"]` | 26.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["random", "types", "(\"rand\", \"MersenneTwister\", \"Float32\")"]` | 25.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["random", "types", "(\"rand\", \"MersenneTwister\", \"Float64\")"]` | 24.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["random", "types", "(\"rand\", \"MersenneTwister\", \"ImplicitFloat64\")"]` | 24.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["random", "types", "(\"rand\", \"MersenneTwister\", \"Int128\")"]` | 25.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["random", "types", "(\"rand\", \"MersenneTwister\", \"Int16\")"]` | 24.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["random", "types", "(\"rand\", \"MersenneTwister\", \"Int32\")"]` | 24.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["random", "types", "(\"rand\", \"MersenneTwister\", \"Int64\")"]` | 24.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["random", "types", "(\"rand\", \"MersenneTwister\", \"Int8\")"]` | 24.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["random", "types", "(\"rand\", \"MersenneTwister\", \"UInt128\")"]` | 25.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["random", "types", "(\"rand\", \"MersenneTwister\", \"UInt16\")"]` | 24.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["random", "types", "(\"rand\", \"MersenneTwister\", \"UInt32\")"]` | 24.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["random", "types", "(\"rand\", \"MersenneTwister\", \"UInt64\")"]` | 24.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["random", "types", "(\"rand\", \"MersenneTwister\", \"UInt8\")"]` | 24.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["random", "types", "(\"rand\", \"RandomDevice\", \"Float64\")"]` | 81.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["random", "types", "(\"rand\", \"RandomDevice\", \"ImplicitFloat64\")"]` | 81.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["random", "types", "(\"rand\", \"RandomDevice\", \"Int64\")"]` | 80.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["random", "types", "(\"randexp!\", \"ImplicitRNG\", \"Float64\")"]` | 2.985 μs (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["random", "types", "(\"randexp!\", \"MersenneTwister\", \"Float16\")"]` | 15.996 μs (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["random", "types", "(\"randexp!\", \"MersenneTwister\", \"Float32\")"]` | 4.708 μs (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["random", "types", "(\"randexp!\", \"MersenneTwister\", \"Float64\")"]` | 2.995 μs (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["random", "types", "(\"randexp!\", \"RandomDevice\", \"Float64\")"]` | 59.063 μs (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["random", "types", "(\"randexp\", \"ImplicitRNG\", \"Float64\")"]` | 34.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["random", "types", "(\"randexp\", \"ImplicitRNG\", \"ImplicitFloat64\")"]` | 34.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["random", "types", "(\"randexp\", \"MersenneTwister\", \"Float16\")"]` | 30.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["random", "types", "(\"randexp\", \"MersenneTwister\", \"Float32\")"]` | 27.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["random", "types", "(\"randexp\", \"MersenneTwister\", \"Float64\")"]` | 26.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["random", "types", "(\"randexp\", \"MersenneTwister\", \"ImplicitFloat64\")"]` | 26.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["random", "types", "(\"randexp\", \"RandomDevice\", \"Float64\")"]` | 84.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["random", "types", "(\"randexp\", \"RandomDevice\", \"ImplicitFloat64\")"]` | 84.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["random", "types", "(\"randn!\", \"ImplicitRNG\", \"Float64\")"]` | 2.902 μs (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["random", "types", "(\"randn!\", \"MersenneTwister\", \"ComplexF16\")"]` | 34.636 μs (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["random", "types", "(\"randn!\", \"MersenneTwister\", \"ComplexF32\")"]` | 8.359 μs (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["random", "types", "(\"randn!\", \"MersenneTwister\", \"ComplexF64\")"]` | 8.482 μs (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["random", "types", "(\"randn!\", \"MersenneTwister\", \"Float16\")"]` | 15.929 μs (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["random", "types", "(\"randn!\", \"MersenneTwister\", \"Float32\")"]` | 3.176 μs (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["random", "types", "(\"randn!\", \"MersenneTwister\", \"Float64\")"]` | 2.815 μs (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["random", "types", "(\"randn!\", \"RandomDevice\", \"Float64\")"]` | 58.348 μs (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["random", "types", "(\"randn\", \"ImplicitRNG\", \"Float64\")"]` | 35.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["random", "types", "(\"randn\", \"ImplicitRNG\", \"ImplicitFloat64\")"]` | 35.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["random", "types", "(\"randn\", \"MersenneTwister\", \"ComplexF16\")"]` | 45.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["random", "types", "(\"randn\", \"MersenneTwister\", \"ComplexF32\")"]` | 33.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["random", "types", "(\"randn\", \"MersenneTwister\", \"ComplexF64\")"]` | 34.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["random", "types", "(\"randn\", \"MersenneTwister\", \"Float16\")"]` | 33.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["random", "types", "(\"randn\", \"MersenneTwister\", \"Float32\")"]` | 28.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["random", "types", "(\"randn\", \"MersenneTwister\", \"Float64\")"]` | 28.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["random", "types", "(\"randn\", \"MersenneTwister\", \"ImplicitFloat64\")"]` | 26.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["random", "types", "(\"randn\", \"RandomDevice\", \"Float64\")"]` | 82.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["random", "types", "(\"randn\", \"RandomDevice\", \"ImplicitFloat64\")"]` | 82.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "acos", "(\"0.5 <= abs(x) < 1\", \"negative argument\", \"Float32\")"]` | 24.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "acos", "(\"0.5 <= abs(x) < 1\", \"negative argument\", \"Float64\")"]` | 24.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "acos", "(\"0.5 <= abs(x) < 1\", \"positive argument\", \"Float32\")"]` | 36.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "acos", "(\"0.5 <= abs(x) < 1\", \"positive argument\", \"Float64\")"]` | 40.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "acos", "(\"abs(x) < 0.5\", \"negative argument\", \"Float32\")"]` | 34.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "acos", "(\"abs(x) < 0.5\", \"negative argument\", \"Float64\")"]` | 40.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "acos", "(\"abs(x) < 0.5\", \"positive argument\", \"Float32\")"]` | 32.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "acos", "(\"abs(x) < 0.5\", \"positive argument\", \"Float64\")"]` | 40.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "acos", "(\"one\", \"negative argument\", \"Float32\")"]` | 23.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "acos", "(\"one\", \"negative argument\", \"Float64\")"]` | 23.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "acos", "(\"one\", \"positive argument\", \"Float32\")"]` | 23.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "acos", "(\"one\", \"positive argument\", \"Float64\")"]` | 23.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "acos", "(\"small\", \"negative argument\", \"Float32\")"]` | 26.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "acos", "(\"small\", \"negative argument\", \"Float64\")"]` | 26.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "acos", "(\"small\", \"positive argument\", \"Float32\")"]` | 26.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "acos", "(\"small\", \"positive argument\", \"Float64\")"]` | 26.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "acos", "(\"zero\", \"Float32\")"]` | 26.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "acos", "(\"zero\", \"Float64\")"]` | 26.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "acosh", "(\"1 <= abs(x) < 2\", \"positive argument\", \"Float32\")"]` | 54.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "acosh", "(\"1 <= abs(x) < 2\", \"positive argument\", \"Float64\")"]` | 56.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "acosh", "(\"2 <= abs(x) < 2^28\", \"positive argument\", \"Float32\")"]` | 54.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "acosh", "(\"2 <= abs(x) < 2^28\", \"positive argument\", \"Float64\")"]` | 57.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "acosh", "(\"one\", \"Float32\")"]` | 23.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "acosh", "(\"one\", \"Float64\")"]` | 23.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "acosh", "(\"very large\", \"positive argument\", \"Float32\")"]` | 44.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "acosh", "(\"very large\", \"positive argument\", \"Float64\")"]` | 42.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "arithmetic", "(\"add\", \"BigFloat\", \"BigFloat\")"]` | 72.000 ns (50%) | 0.000 ns | 112 bytes (1%) | 2 |
| `["scalar", "arithmetic", "(\"add\", \"BigFloat\", \"BigInt\")"]` | 123.000 ns (50%) | 0.000 ns | 112 bytes (1%) | 2 |
| `["scalar", "arithmetic", "(\"add\", \"BigFloat\", \"ComplexF32\")"]` | 197.000 ns (50%) | 0.000 ns | 224 bytes (1%) | 4 |
| `["scalar", "arithmetic", "(\"add\", \"BigFloat\", \"ComplexF64\")"]` | 198.000 ns (50%) | 0.000 ns | 224 bytes (1%) | 4 |
| `["scalar", "arithmetic", "(\"add\", \"BigFloat\", \"Complex{BigFloat}\")"]` | 71.000 ns (50%) | 0.000 ns | 112 bytes (1%) | 2 |
| `["scalar", "arithmetic", "(\"add\", \"BigFloat\", \"Complex{BigInt}\")"]` | 152.000 ns (50%) | 0.000 ns | 224 bytes (1%) | 4 |
| `["scalar", "arithmetic", "(\"add\", \"BigFloat\", \"Complex{Int64}\")"]` | 148.000 ns (50%) | 0.000 ns | 224 bytes (1%) | 4 |
| `["scalar", "arithmetic", "(\"add\", \"BigFloat\", \"Complex{UInt64}\")"]` | 147.000 ns (50%) | 0.000 ns | 224 bytes (1%) | 4 |
| `["scalar", "arithmetic", "(\"add\", \"BigFloat\", \"Float32\")"]` | 170.000 ns (50%) | 0.000 ns | 112 bytes (1%) | 2 |
| `["scalar", "arithmetic", "(\"add\", \"BigFloat\", \"Float64\")"]` | 169.000 ns (50%) | 0.000 ns | 112 bytes (1%) | 2 |
| `["scalar", "arithmetic", "(\"add\", \"BigFloat\", \"Int64\")"]` | 118.000 ns (50%) | 0.000 ns | 112 bytes (1%) | 2 |
| `["scalar", "arithmetic", "(\"add\", \"BigFloat\", \"UInt64\")"]` | 116.000 ns (50%) | 0.000 ns | 112 bytes (1%) | 2 |
| `["scalar", "arithmetic", "(\"add\", \"BigInt\", \"BigFloat\")"]` | 124.000 ns (50%) | 0.000 ns | 112 bytes (1%) | 2 |
| `["scalar", "arithmetic", "(\"add\", \"BigInt\", \"BigInt\")"]` | 56.000 ns (50%) | 0.000 ns | 48 bytes (1%) | 2 |
| `["scalar", "arithmetic", "(\"add\", \"BigInt\", \"ComplexF32\")"]` | 229.000 ns (50%) | 0.000 ns | 448 bytes (1%) | 8 |
| `["scalar", "arithmetic", "(\"add\", \"BigInt\", \"ComplexF64\")"]` | 228.000 ns (50%) | 0.000 ns | 448 bytes (1%) | 8 |
| `["scalar", "arithmetic", "(\"add\", \"BigInt\", \"Complex{BigFloat}\")"]` | 125.000 ns (50%) | 0.000 ns | 112 bytes (1%) | 2 |
| `["scalar", "arithmetic", "(\"add\", \"BigInt\", \"Complex{BigInt}\")"]` | 53.000 ns (50%) | 0.000 ns | 48 bytes (1%) | 2 |
| `["scalar", "arithmetic", "(\"add\", \"BigInt\", \"Complex{Int64}\")"]` | 99.000 ns (50%) | 0.000 ns | 88 bytes (1%) | 5 |
| `["scalar", "arithmetic", "(\"add\", \"BigInt\", \"Complex{UInt64}\")"]` | 99.000 ns (50%) | 0.000 ns | 88 bytes (1%) | 5 |
| `["scalar", "arithmetic", "(\"add\", \"BigInt\", \"Float32\")"]` | 202.000 ns (50%) | 0.000 ns | 336 bytes (1%) | 6 |
| `["scalar", "arithmetic", "(\"add\", \"BigInt\", \"Float64\")"]` | 201.000 ns (50%) | 0.000 ns | 336 bytes (1%) | 6 |
| `["scalar", "arithmetic", "(\"add\", \"BigInt\", \"Int64\")"]` | 77.000 ns (50%) | 0.000 ns | 48 bytes (1%) | 3 |
| `["scalar", "arithmetic", "(\"add\", \"BigInt\", \"UInt64\")"]` | 76.000 ns (50%) | 0.000 ns | 48 bytes (1%) | 3 |
| `["scalar", "arithmetic", "(\"add\", \"ComplexF32\", \"BigFloat\")"]` | 198.000 ns (50%) | 0.000 ns | 224 bytes (1%) | 4 |
| `["scalar", "arithmetic", "(\"add\", \"ComplexF32\", \"BigInt\")"]` | 227.000 ns (50%) | 0.000 ns | 448 bytes (1%) | 8 |
| `["scalar", "arithmetic", "(\"add\", \"ComplexF32\", \"ComplexF32\")"]` | 23.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "arithmetic", "(\"add\", \"ComplexF32\", \"ComplexF64\")"]` | 23.000 ns (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "arithmetic", "(\"add\", \"ComplexF32\", \"Complex{BigFloat}\")"]` | 226.000 ns (50%) | 0.000 ns | 224 bytes (1%) | 4 |
| `["scalar", "arithmetic", "(\"add\", \"ComplexF32\", \"Complex{BigInt}\")"]` | 287.000 ns (50%) | 0.000 ns | 672 bytes (1%) | 12 |
| `["scalar", "arithmetic", "(\"add\", \"ComplexF32\", \"Complex{Int64}\")"]` | 23.000 ns (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "arithmetic", "(\"add\", \"ComplexF32\", \"Complex{UInt64}\")"]` | 23.000 ns (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "arithmetic", "(\"add\", \"ComplexF32\", \"Float32\")"]` | 23.000 ns (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "arithmetic", "(\"add\", \"ComplexF32\", \"Float64\")"]` | 23.000 ns (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "arithmetic", "(\"add\", \"ComplexF32\", \"Int64\")"]` | 23.000 ns (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "arithmetic", "(\"add\", \"ComplexF32\", \"UInt64\")"]` | 23.000 ns (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "arithmetic", "(\"add\", \"ComplexF64\", \"BigFloat\")"]` | 196.000 ns (50%) | 0.000 ns | 224 bytes (1%) | 4 |
| `["scalar", "arithmetic", "(\"add\", \"ComplexF64\", \"BigInt\")"]` | 230.000 ns (50%) | 0.000 ns | 448 bytes (1%) | 8 |
| `["scalar", "arithmetic", "(\"add\", \"ComplexF64\", \"ComplexF32\")"]` | 23.000 ns (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "arithmetic", "(\"add\", \"ComplexF64\", \"ComplexF64\")"]` | 23.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "arithmetic", "(\"add\", \"ComplexF64\", \"Complex{BigFloat}\")"]` | 227.000 ns (50%) | 0.000 ns | 224 bytes (1%) | 4 |
| `["scalar", "arithmetic", "(\"add\", \"ComplexF64\", \"Complex{BigInt}\")"]` | 285.000 ns (50%) | 0.000 ns | 672 bytes (1%) | 12 |
| `["scalar", "arithmetic", "(\"add\", \"ComplexF64\", \"Complex{Int64}\")"]` | 23.000 ns (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "arithmetic", "(\"add\", \"ComplexF64\", \"Complex{UInt64}\")"]` | 23.000 ns (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "arithmetic", "(\"add\", \"ComplexF64\", \"Float32\")"]` | 23.000 ns (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "arithmetic", "(\"add\", \"ComplexF64\", \"Float64\")"]` | 23.000 ns (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "arithmetic", "(\"add\", \"ComplexF64\", \"Int64\")"]` | 23.000 ns (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "arithmetic", "(\"add\", \"ComplexF64\", \"UInt64\")"]` | 23.000 ns (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "arithmetic", "(\"add\", \"Complex{BigFloat}\", \"BigFloat\")"]` | 72.000 ns (50%) | 0.000 ns | 112 bytes (1%) | 2 |
| `["scalar", "arithmetic", "(\"add\", \"Complex{BigFloat}\", \"BigInt\")"]` | 126.000 ns (50%) | 0.000 ns | 112 bytes (1%) | 2 |
| `["scalar", "arithmetic", "(\"add\", \"Complex{BigFloat}\", \"ComplexF32\")"]` | 226.000 ns (50%) | 0.000 ns | 224 bytes (1%) | 4 |
| `["scalar", "arithmetic", "(\"add\", \"Complex{BigFloat}\", \"ComplexF64\")"]` | 225.000 ns (50%) | 0.000 ns | 224 bytes (1%) | 4 |
| `["scalar", "arithmetic", "(\"add\", \"Complex{BigFloat}\", \"Complex{BigFloat}\")"]` | 100.000 ns (50%) | 0.000 ns | 224 bytes (1%) | 4 |
| `["scalar", "arithmetic", "(\"add\", \"Complex{BigFloat}\", \"Complex{BigInt}\")"]` | 160.000 ns (50%) | 0.000 ns | 224 bytes (1%) | 4 |
| `["scalar", "arithmetic", "(\"add\", \"Complex{BigFloat}\", \"Complex{Int64}\")"]` | 150.000 ns (50%) | 0.000 ns | 224 bytes (1%) | 4 |
| `["scalar", "arithmetic", "(\"add\", \"Complex{BigFloat}\", \"Complex{UInt64}\")"]` | 146.000 ns (50%) | 0.000 ns | 224 bytes (1%) | 4 |
| `["scalar", "arithmetic", "(\"add\", \"Complex{BigFloat}\", \"Float32\")"]` | 168.000 ns (50%) | 0.000 ns | 112 bytes (1%) | 2 |
| `["scalar", "arithmetic", "(\"add\", \"Complex{BigFloat}\", \"Float64\")"]` | 170.000 ns (50%) | 0.000 ns | 112 bytes (1%) | 2 |
| `["scalar", "arithmetic", "(\"add\", \"Complex{BigFloat}\", \"Int64\")"]` | 118.000 ns (50%) | 0.000 ns | 112 bytes (1%) | 2 |
| `["scalar", "arithmetic", "(\"add\", \"Complex{BigFloat}\", \"UInt64\")"]` | 118.000 ns (50%) | 0.000 ns | 112 bytes (1%) | 2 |
| `["scalar", "arithmetic", "(\"add\", \"Complex{BigInt}\", \"BigFloat\")"]` | 153.000 ns (50%) | 0.000 ns | 224 bytes (1%) | 4 |
| `["scalar", "arithmetic", "(\"add\", \"Complex{BigInt}\", \"BigInt\")"]` | 53.000 ns (50%) | 0.000 ns | 48 bytes (1%) | 2 |
| `["scalar", "arithmetic", "(\"add\", \"Complex{BigInt}\", \"ComplexF32\")"]` | 285.000 ns (50%) | 0.000 ns | 672 bytes (1%) | 12 |
| `["scalar", "arithmetic", "(\"add\", \"Complex{BigInt}\", \"ComplexF64\")"]` | 285.000 ns (50%) | 0.000 ns | 672 bytes (1%) | 12 |
| `["scalar", "arithmetic", "(\"add\", \"Complex{BigInt}\", \"Complex{BigFloat}\")"]` | 160.000 ns (50%) | 0.000 ns | 224 bytes (1%) | 4 |
| `["scalar", "arithmetic", "(\"add\", \"Complex{BigInt}\", \"Complex{BigInt}\")"]` | 80.000 ns (50%) | 0.000 ns | 88 bytes (1%) | 4 |
| `["scalar", "arithmetic", "(\"add\", \"Complex{BigInt}\", \"Complex{Int64}\")"]` | 100.000 ns (50%) | 0.000 ns | 88 bytes (1%) | 5 |
| `["scalar", "arithmetic", "(\"add\", \"Complex{BigInt}\", \"Complex{UInt64}\")"]` | 99.000 ns (50%) | 0.000 ns | 88 bytes (1%) | 5 |
| `["scalar", "arithmetic", "(\"add\", \"Complex{BigInt}\", \"Float32\")"]` | 230.000 ns (50%) | 0.000 ns | 448 bytes (1%) | 8 |
| `["scalar", "arithmetic", "(\"add\", \"Complex{BigInt}\", \"Float64\")"]` | 230.000 ns (50%) | 0.000 ns | 448 bytes (1%) | 8 |
| `["scalar", "arithmetic", "(\"add\", \"Complex{BigInt}\", \"Int64\")"]` | 77.000 ns (50%) | 0.000 ns | 48 bytes (1%) | 3 |
| `["scalar", "arithmetic", "(\"add\", \"Complex{BigInt}\", \"UInt64\")"]` | 76.000 ns (50%) | 0.000 ns | 48 bytes (1%) | 3 |
| `["scalar", "arithmetic", "(\"add\", \"Complex{Int64}\", \"BigFloat\")"]` | 149.000 ns (50%) | 0.000 ns | 224 bytes (1%) | 4 |
| `["scalar", "arithmetic", "(\"add\", \"Complex{Int64}\", \"BigInt\")"]` | 106.000 ns (50%) | 0.000 ns | 88 bytes (1%) | 5 |
| `["scalar", "arithmetic", "(\"add\", \"Complex{Int64}\", \"ComplexF32\")"]` | 23.000 ns (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "arithmetic", "(\"add\", \"Complex{Int64}\", \"ComplexF64\")"]` | 23.000 ns (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "arithmetic", "(\"add\", \"Complex{Int64}\", \"Complex{BigFloat}\")"]` | 150.000 ns (50%) | 0.000 ns | 224 bytes (1%) | 4 |
| `["scalar", "arithmetic", "(\"add\", \"Complex{Int64}\", \"Complex{BigInt}\")"]` | 100.000 ns (50%) | 0.000 ns | 88 bytes (1%) | 5 |
| `["scalar", "arithmetic", "(\"add\", \"Complex{Int64}\", \"Complex{Int64}\")"]` | 23.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "arithmetic", "(\"add\", \"Complex{Int64}\", \"Complex{UInt64}\")"]` | 23.000 ns (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "arithmetic", "(\"add\", \"Complex{Int64}\", \"Float32\")"]` | 23.000 ns (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "arithmetic", "(\"add\", \"Complex{Int64}\", \"Float64\")"]` | 23.000 ns (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "arithmetic", "(\"add\", \"Complex{Int64}\", \"Int64\")"]` | 23.000 ns (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "arithmetic", "(\"add\", \"Complex{Int64}\", \"UInt64\")"]` | 23.000 ns (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "arithmetic", "(\"add\", \"Complex{UInt64}\", \"BigFloat\")"]` | 149.000 ns (50%) | 0.000 ns | 224 bytes (1%) | 4 |
| `["scalar", "arithmetic", "(\"add\", \"Complex{UInt64}\", \"BigInt\")"]` | 98.000 ns (50%) | 0.000 ns | 88 bytes (1%) | 5 |
| `["scalar", "arithmetic", "(\"add\", \"Complex{UInt64}\", \"ComplexF32\")"]` | 23.000 ns (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "arithmetic", "(\"add\", \"Complex{UInt64}\", \"ComplexF64\")"]` | 23.000 ns (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "arithmetic", "(\"add\", \"Complex{UInt64}\", \"Complex{BigFloat}\")"]` | 146.000 ns (50%) | 0.000 ns | 224 bytes (1%) | 4 |
| `["scalar", "arithmetic", "(\"add\", \"Complex{UInt64}\", \"Complex{BigInt}\")"]` | 99.000 ns (50%) | 0.000 ns | 88 bytes (1%) | 5 |
| `["scalar", "arithmetic", "(\"add\", \"Complex{UInt64}\", \"Complex{Int64}\")"]` | 23.000 ns (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "arithmetic", "(\"add\", \"Complex{UInt64}\", \"Complex{UInt64}\")"]` | 23.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "arithmetic", "(\"add\", \"Complex{UInt64}\", \"Float32\")"]` | 23.000 ns (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "arithmetic", "(\"add\", \"Complex{UInt64}\", \"Float64\")"]` | 23.000 ns (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "arithmetic", "(\"add\", \"Complex{UInt64}\", \"Int64\")"]` | 23.000 ns (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "arithmetic", "(\"add\", \"Complex{UInt64}\", \"UInt64\")"]` | 23.000 ns (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "arithmetic", "(\"add\", \"Float32\", \"BigFloat\")"]` | 168.000 ns (50%) | 0.000 ns | 112 bytes (1%) | 2 |
| `["scalar", "arithmetic", "(\"add\", \"Float32\", \"BigInt\")"]` | 203.000 ns (50%) | 0.000 ns | 336 bytes (1%) | 6 |
| `["scalar", "arithmetic", "(\"add\", \"Float32\", \"ComplexF32\")"]` | 23.000 ns (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "arithmetic", "(\"add\", \"Float32\", \"ComplexF64\")"]` | 23.000 ns (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "arithmetic", "(\"add\", \"Float32\", \"Complex{BigFloat}\")"]` | 171.000 ns (50%) | 0.000 ns | 112 bytes (1%) | 2 |
| `["scalar", "arithmetic", "(\"add\", \"Float32\", \"Complex{BigInt}\")"]` | 228.000 ns (50%) | 0.000 ns | 448 bytes (1%) | 8 |
| `["scalar", "arithmetic", "(\"add\", \"Float32\", \"Complex{Int64}\")"]` | 23.000 ns (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "arithmetic", "(\"add\", \"Float32\", \"Complex{UInt64}\")"]` | 23.000 ns (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "arithmetic", "(\"add\", \"Float32\", \"Float32\")"]` | 23.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "arithmetic", "(\"add\", \"Float32\", \"Float64\")"]` | 23.000 ns (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "arithmetic", "(\"add\", \"Float32\", \"Int64\")"]` | 23.000 ns (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "arithmetic", "(\"add\", \"Float32\", \"UInt64\")"]` | 23.000 ns (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "arithmetic", "(\"add\", \"Float64\", \"BigFloat\")"]` | 169.000 ns (50%) | 0.000 ns | 112 bytes (1%) | 2 |
| `["scalar", "arithmetic", "(\"add\", \"Float64\", \"BigInt\")"]` | 202.000 ns (50%) | 0.000 ns | 336 bytes (1%) | 6 |
| `["scalar", "arithmetic", "(\"add\", \"Float64\", \"ComplexF32\")"]` | 23.000 ns (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "arithmetic", "(\"add\", \"Float64\", \"ComplexF64\")"]` | 23.000 ns (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "arithmetic", "(\"add\", \"Float64\", \"Complex{BigFloat}\")"]` | 170.000 ns (50%) | 0.000 ns | 112 bytes (1%) | 2 |
| `["scalar", "arithmetic", "(\"add\", \"Float64\", \"Complex{BigInt}\")"]` | 226.000 ns (50%) | 0.000 ns | 448 bytes (1%) | 8 |
| `["scalar", "arithmetic", "(\"add\", \"Float64\", \"Complex{Int64}\")"]` | 23.000 ns (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "arithmetic", "(\"add\", \"Float64\", \"Complex{UInt64}\")"]` | 23.000 ns (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "arithmetic", "(\"add\", \"Float64\", \"Float32\")"]` | 23.000 ns (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "arithmetic", "(\"add\", \"Float64\", \"Float64\")"]` | 23.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "arithmetic", "(\"add\", \"Float64\", \"Int64\")"]` | 23.000 ns (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "arithmetic", "(\"add\", \"Float64\", \"UInt64\")"]` | 23.000 ns (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "arithmetic", "(\"add\", \"Int64\", \"BigFloat\")"]` | 118.000 ns (50%) | 0.000 ns | 112 bytes (1%) | 2 |
| `["scalar", "arithmetic", "(\"add\", \"Int64\", \"BigInt\")"]` | 78.000 ns (50%) | 0.000 ns | 48 bytes (1%) | 3 |
| `["scalar", "arithmetic", "(\"add\", \"Int64\", \"ComplexF32\")"]` | 23.000 ns (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "arithmetic", "(\"add\", \"Int64\", \"ComplexF64\")"]` | 23.000 ns (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "arithmetic", "(\"add\", \"Int64\", \"Complex{BigFloat}\")"]` | 118.000 ns (50%) | 0.000 ns | 112 bytes (1%) | 2 |
| `["scalar", "arithmetic", "(\"add\", \"Int64\", \"Complex{BigInt}\")"]` | 78.000 ns (50%) | 0.000 ns | 48 bytes (1%) | 3 |
| `["scalar", "arithmetic", "(\"add\", \"Int64\", \"Complex{Int64}\")"]` | 23.000 ns (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "arithmetic", "(\"add\", \"Int64\", \"Complex{UInt64}\")"]` | 23.000 ns (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "arithmetic", "(\"add\", \"Int64\", \"Float32\")"]` | 23.000 ns (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "arithmetic", "(\"add\", \"Int64\", \"Float64\")"]` | 23.000 ns (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "arithmetic", "(\"add\", \"Int64\", \"Int64\")"]` | 23.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "arithmetic", "(\"add\", \"Int64\", \"UInt64\")"]` | 23.000 ns (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "arithmetic", "(\"add\", \"UInt64\", \"BigFloat\")"]` | 117.000 ns (50%) | 0.000 ns | 112 bytes (1%) | 2 |
| `["scalar", "arithmetic", "(\"add\", \"UInt64\", \"BigInt\")"]` | 77.000 ns (50%) | 0.000 ns | 48 bytes (1%) | 3 |
| `["scalar", "arithmetic", "(\"add\", \"UInt64\", \"ComplexF32\")"]` | 23.000 ns (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "arithmetic", "(\"add\", \"UInt64\", \"ComplexF64\")"]` | 23.000 ns (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "arithmetic", "(\"add\", \"UInt64\", \"Complex{BigFloat}\")"]` | 116.000 ns (50%) | 0.000 ns | 112 bytes (1%) | 2 |
| `["scalar", "arithmetic", "(\"add\", \"UInt64\", \"Complex{BigInt}\")"]` | 77.000 ns (50%) | 0.000 ns | 48 bytes (1%) | 3 |
| `["scalar", "arithmetic", "(\"add\", \"UInt64\", \"Complex{Int64}\")"]` | 23.000 ns (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "arithmetic", "(\"add\", \"UInt64\", \"Complex{UInt64}\")"]` | 23.000 ns (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "arithmetic", "(\"add\", \"UInt64\", \"Float32\")"]` | 23.000 ns (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "arithmetic", "(\"add\", \"UInt64\", \"Float64\")"]` | 23.000 ns (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "arithmetic", "(\"add\", \"UInt64\", \"Int64\")"]` | 23.000 ns (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "arithmetic", "(\"add\", \"UInt64\", \"UInt64\")"]` | 23.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "arithmetic", "(\"div\", \"BigFloat\", \"BigFloat\")"]` | 281.000 ns (50%) | 0.000 ns | 112 bytes (1%) | 2 |
| `["scalar", "arithmetic", "(\"div\", \"BigFloat\", \"BigInt\")"]` | 58.000 ns (50%) | 0.000 ns | 112 bytes (1%) | 2 |
| `["scalar", "arithmetic", "(\"div\", \"BigFloat\", \"ComplexF32\")"]` | 710.000 ns (50%) | 0.000 ns | 1.09 KiB (1%) | 20 |
| `["scalar", "arithmetic", "(\"div\", \"BigFloat\", \"ComplexF64\")"]` | 702.000 ns (50%) | 0.000 ns | 1.09 KiB (1%) | 20 |
| `["scalar", "arithmetic", "(\"div\", \"BigFloat\", \"Complex{BigFloat}\")"]` | 590.000 ns (50%) | 0.000 ns | 896 bytes (1%) | 16 |
| `["scalar", "arithmetic", "(\"div\", \"BigFloat\", \"Complex{BigInt}\")"]` | 675.000 ns (50%) | 0.000 ns | 1.09 KiB (1%) | 20 |
| `["scalar", "arithmetic", "(\"div\", \"BigFloat\", \"Complex{Int64}\")"]` | 670.000 ns (50%) | 0.000 ns | 1.09 KiB (1%) | 20 |
| `["scalar", "arithmetic", "(\"div\", \"BigFloat\", \"Complex{UInt64}\")"]` | 673.000 ns (50%) | 0.000 ns | 1.09 KiB (1%) | 20 |
| `["scalar", "arithmetic", "(\"div\", \"BigFloat\", \"Float32\")"]` | 170.000 ns (50%) | 0.000 ns | 112 bytes (1%) | 2 |
| `["scalar", "arithmetic", "(\"div\", \"BigFloat\", \"Float64\")"]` | 171.000 ns (50%) | 0.000 ns | 112 bytes (1%) | 2 |
| `["scalar", "arithmetic", "(\"div\", \"BigFloat\", \"Int64\")"]` | 52.000 ns (50%) | 0.000 ns | 112 bytes (1%) | 2 |
| `["scalar", "arithmetic", "(\"div\", \"BigFloat\", \"UInt64\")"]` | 52.000 ns (50%) | 0.000 ns | 112 bytes (1%) | 2 |
| `["scalar", "arithmetic", "(\"div\", \"BigInt\", \"BigFloat\")"]` | 341.000 ns (50%) | 0.000 ns | 224 bytes (1%) | 4 |
| `["scalar", "arithmetic", "(\"div\", \"BigInt\", \"BigInt\")"]` | 396.000 ns (50%) | 0.000 ns | 336 bytes (1%) | 6 |
| `["scalar", "arithmetic", "(\"div\", \"BigInt\", \"ComplexF32\")"]` | 702.000 ns (50%) | 0.000 ns | 1.09 KiB (1%) | 20 |
| `["scalar", "arithmetic", "(\"div\", \"BigInt\", \"ComplexF64\")"]` | 666.000 ns (50%) | 0.000 ns | 1.09 KiB (1%) | 20 |
| `["scalar", "arithmetic", "(\"div\", \"BigInt\", \"Complex{BigFloat}\")"]` | 551.000 ns (50%) | 0.000 ns | 896 bytes (1%) | 16 |
| `["scalar", "arithmetic", "(\"div\", \"BigInt\", \"Complex{BigInt}\")"]` | 649.000 ns (50%) | 0.000 ns | 1.09 KiB (1%) | 20 |
| `["scalar", "arithmetic", "(\"div\", \"BigInt\", \"Complex{Int64}\")"]` | 695.000 ns (50%) | 0.000 ns | 1.17 KiB (1%) | 24 |
| `["scalar", "arithmetic", "(\"div\", \"BigInt\", \"Complex{UInt64}\")"]` | 698.000 ns (50%) | 0.000 ns | 1.17 KiB (1%) | 24 |
| `["scalar", "arithmetic", "(\"div\", \"BigInt\", \"Float32\")"]` | 419.000 ns (50%) | 0.000 ns | 336 bytes (1%) | 6 |
| `["scalar", "arithmetic", "(\"div\", \"BigInt\", \"Float64\")"]` | 420.000 ns (50%) | 0.000 ns | 336 bytes (1%) | 6 |
| `["scalar", "arithmetic", "(\"div\", \"BigInt\", \"Int64\")"]` | 107.000 ns (50%) | 0.000 ns | 224 bytes (1%) | 4 |
| `["scalar", "arithmetic", "(\"div\", \"BigInt\", \"UInt64\")"]` | 106.000 ns (50%) | 0.000 ns | 224 bytes (1%) | 4 |
| `["scalar", "arithmetic", "(\"div\", \"ComplexF32\", \"BigFloat\")"]` | 420.000 ns (50%) | 0.000 ns | 224 bytes (1%) | 4 |
| `["scalar", "arithmetic", "(\"div\", \"ComplexF32\", \"BigInt\")"]` | 534.000 ns (50%) | 0.000 ns | 672 bytes (1%) | 12 |
| `["scalar", "arithmetic", "(\"div\", \"ComplexF32\", \"ComplexF32\")"]` | 23.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "arithmetic", "(\"div\", \"ComplexF32\", \"ComplexF64\")"]` | 23.000 ns (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "arithmetic", "(\"div\", \"ComplexF32\", \"Complex{BigFloat}\")"]` | 687.000 ns (50%) | 0.000 ns | 1.42 KiB (1%) | 26 |
| `["scalar", "arithmetic", "(\"div\", \"ComplexF32\", \"Complex{BigInt}\")"]` | 780.000 ns (50%) | 0.000 ns | 1.64 KiB (1%) | 30 |
| `["scalar", "arithmetic", "(\"div\", \"ComplexF32\", \"Complex{Int64}\")"]` | 23.000 ns (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "arithmetic", "(\"div\", \"ComplexF32\", \"Complex{UInt64}\")"]` | 23.000 ns (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "arithmetic", "(\"div\", \"ComplexF32\", \"Float32\")"]` | 23.000 ns (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "arithmetic", "(\"div\", \"ComplexF32\", \"Float64\")"]` | 23.000 ns (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "arithmetic", "(\"div\", \"ComplexF32\", \"Int64\")"]` | 23.000 ns (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "arithmetic", "(\"div\", \"ComplexF32\", \"UInt64\")"]` | 23.000 ns (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "arithmetic", "(\"div\", \"ComplexF64\", \"BigFloat\")"]` | 422.000 ns (50%) | 0.000 ns | 224 bytes (1%) | 4 |
| `["scalar", "arithmetic", "(\"div\", \"ComplexF64\", \"BigInt\")"]` | 536.000 ns (50%) | 0.000 ns | 672 bytes (1%) | 12 |
| `["scalar", "arithmetic", "(\"div\", \"ComplexF64\", \"ComplexF32\")"]` | 23.000 ns (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "arithmetic", "(\"div\", \"ComplexF64\", \"ComplexF64\")"]` | 23.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "arithmetic", "(\"div\", \"ComplexF64\", \"Complex{BigFloat}\")"]` | 689.000 ns (50%) | 0.000 ns | 1.42 KiB (1%) | 26 |
| `["scalar", "arithmetic", "(\"div\", \"ComplexF64\", \"Complex{BigInt}\")"]` | 771.000 ns (50%) | 0.000 ns | 1.64 KiB (1%) | 30 |
| `["scalar", "arithmetic", "(\"div\", \"ComplexF64\", \"Complex{Int64}\")"]` | 23.000 ns (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "arithmetic", "(\"div\", \"ComplexF64\", \"Complex{UInt64}\")"]` | 23.000 ns (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "arithmetic", "(\"div\", \"ComplexF64\", \"Float32\")"]` | 23.000 ns (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "arithmetic", "(\"div\", \"ComplexF64\", \"Float64\")"]` | 23.000 ns (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "arithmetic", "(\"div\", \"ComplexF64\", \"Int64\")"]` | 23.000 ns (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "arithmetic", "(\"div\", \"ComplexF64\", \"UInt64\")"]` | 23.000 ns (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "arithmetic", "(\"div\", \"Complex{BigFloat}\", \"BigFloat\")"]` | 311.000 ns (50%) | 0.000 ns | 224 bytes (1%) | 4 |
| `["scalar", "arithmetic", "(\"div\", \"Complex{BigFloat}\", \"BigInt\")"]` | 94.000 ns (50%) | 0.000 ns | 224 bytes (1%) | 4 |
| `["scalar", "arithmetic", "(\"div\", \"Complex{BigFloat}\", \"ComplexF32\")"]` | 687.000 ns (50%) | 0.000 ns | 1.42 KiB (1%) | 26 |
| `["scalar", "arithmetic", "(\"div\", \"Complex{BigFloat}\", \"ComplexF64\")"]` | 686.000 ns (50%) | 0.000 ns | 1.42 KiB (1%) | 26 |
| `["scalar", "arithmetic", "(\"div\", \"Complex{BigFloat}\", \"Complex{BigFloat}\")"]` | 572.000 ns (50%) | 0.000 ns | 1.20 KiB (1%) | 22 |
| `["scalar", "arithmetic", "(\"div\", \"Complex{BigFloat}\", \"Complex{BigInt}\")"]` | 658.000 ns (50%) | 0.000 ns | 1.42 KiB (1%) | 26 |
| `["scalar", "arithmetic", "(\"div\", \"Complex{BigFloat}\", \"Complex{Int64}\")"]` | 653.000 ns (50%) | 0.000 ns | 1.42 KiB (1%) | 26 |
| `["scalar", "arithmetic", "(\"div\", \"Complex{BigFloat}\", \"Complex{UInt64}\")"]` | 656.000 ns (50%) | 0.000 ns | 1.42 KiB (1%) | 26 |
| `["scalar", "arithmetic", "(\"div\", \"Complex{BigFloat}\", \"Float32\")"]` | 286.000 ns (50%) | 0.000 ns | 224 bytes (1%) | 4 |
| `["scalar", "arithmetic", "(\"div\", \"Complex{BigFloat}\", \"Float64\")"]` | 287.000 ns (50%) | 0.000 ns | 224 bytes (1%) | 4 |
| `["scalar", "arithmetic", "(\"div\", \"Complex{BigFloat}\", \"Int64\")"]` | 80.000 ns (50%) | 0.000 ns | 224 bytes (1%) | 4 |
| `["scalar", "arithmetic", "(\"div\", \"Complex{BigFloat}\", \"UInt64\")"]` | 77.000 ns (50%) | 0.000 ns | 224 bytes (1%) | 4 |
| `["scalar", "arithmetic", "(\"div\", \"Complex{BigInt}\", \"BigFloat\")"]` | 394.000 ns (50%) | 0.000 ns | 448 bytes (1%) | 8 |
| `["scalar", "arithmetic", "(\"div\", \"Complex{BigInt}\", \"BigInt\")"]` | 504.000 ns (50%) | 0.000 ns | 672 bytes (1%) | 12 |
| `["scalar", "arithmetic", "(\"div\", \"Complex{BigInt}\", \"ComplexF32\")"]` | 774.000 ns (50%) | 0.000 ns | 1.64 KiB (1%) | 30 |
| `["scalar", "arithmetic", "(\"div\", \"Complex{BigInt}\", \"ComplexF64\")"]` | 769.000 ns (50%) | 0.000 ns | 1.64 KiB (1%) | 30 |
| `["scalar", "arithmetic", "(\"div\", \"Complex{BigInt}\", \"Complex{BigFloat}\")"]` | 665.000 ns (50%) | 0.000 ns | 1.42 KiB (1%) | 26 |
| `["scalar", "arithmetic", "(\"div\", \"Complex{BigInt}\", \"Complex{BigInt}\")"]` | 688.000 ns (50%) | 0.000 ns | 1.20 KiB (1%) | 22 |
| `["scalar", "arithmetic", "(\"div\", \"Complex{BigInt}\", \"Complex{Int64}\")"]` | 768.000 ns (50%) | 0.000 ns | 1.28 KiB (1%) | 26 |
| `["scalar", "arithmetic", "(\"div\", \"Complex{BigInt}\", \"Complex{UInt64}\")"]` | 746.000 ns (50%) | 0.000 ns | 1.28 KiB (1%) | 26 |
| `["scalar", "arithmetic", "(\"div\", \"Complex{BigInt}\", \"Float32\")"]` | 555.000 ns (50%) | 0.000 ns | 672 bytes (1%) | 12 |
| `["scalar", "arithmetic", "(\"div\", \"Complex{BigInt}\", \"Float64\")"]` | 556.000 ns (50%) | 0.000 ns | 672 bytes (1%) | 12 |
| `["scalar", "arithmetic", "(\"div\", \"Complex{BigInt}\", \"Int64\")"]` | 157.000 ns (50%) | 0.000 ns | 448 bytes (1%) | 8 |
| `["scalar", "arithmetic", "(\"div\", \"Complex{BigInt}\", \"UInt64\")"]` | 155.000 ns (50%) | 0.000 ns | 448 bytes (1%) | 8 |
| `["scalar", "arithmetic", "(\"div\", \"Complex{Int64}\", \"BigFloat\")"]` | 335.000 ns (50%) | 0.000 ns | 224 bytes (1%) | 4 |
| `["scalar", "arithmetic", "(\"div\", \"Complex{Int64}\", \"BigInt\")"]` | 448.000 ns (50%) | 0.000 ns | 448 bytes (1%) | 8 |
| `["scalar", "arithmetic", "(\"div\", \"Complex{Int64}\", \"ComplexF32\")"]` | 23.000 ns (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "arithmetic", "(\"div\", \"Complex{Int64}\", \"ComplexF64\")"]` | 23.000 ns (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "arithmetic", "(\"div\", \"Complex{Int64}\", \"Complex{BigFloat}\")"]` | 653.000 ns (50%) | 0.000 ns | 1.42 KiB (1%) | 26 |
| `["scalar", "arithmetic", "(\"div\", \"Complex{Int64}\", \"Complex{BigInt}\")"]` | 757.000 ns (50%) | 0.000 ns | 1.28 KiB (1%) | 26 |
| `["scalar", "arithmetic", "(\"div\", \"Complex{Int64}\", \"Complex{Int64}\")"]` | 23.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "arithmetic", "(\"div\", \"Complex{Int64}\", \"Complex{UInt64}\")"]` | 23.000 ns (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "arithmetic", "(\"div\", \"Complex{Int64}\", \"Float32\")"]` | 23.000 ns (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "arithmetic", "(\"div\", \"Complex{Int64}\", \"Float64\")"]` | 23.000 ns (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "arithmetic", "(\"div\", \"Complex{Int64}\", \"Int64\")"]` | 23.000 ns (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "arithmetic", "(\"div\", \"Complex{Int64}\", \"UInt64\")"]` | 23.000 ns (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "arithmetic", "(\"div\", \"Complex{UInt64}\", \"BigFloat\")"]` | 334.000 ns (50%) | 0.000 ns | 224 bytes (1%) | 4 |
| `["scalar", "arithmetic", "(\"div\", \"Complex{UInt64}\", \"BigInt\")"]` | 443.000 ns (50%) | 0.000 ns | 448 bytes (1%) | 8 |
| `["scalar", "arithmetic", "(\"div\", \"Complex{UInt64}\", \"ComplexF32\")"]` | 23.000 ns (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "arithmetic", "(\"div\", \"Complex{UInt64}\", \"ComplexF64\")"]` | 23.000 ns (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "arithmetic", "(\"div\", \"Complex{UInt64}\", \"Complex{BigFloat}\")"]` | 654.000 ns (50%) | 0.000 ns | 1.42 KiB (1%) | 26 |
| `["scalar", "arithmetic", "(\"div\", \"Complex{UInt64}\", \"Complex{BigInt}\")"]` | 759.000 ns (50%) | 0.000 ns | 1.28 KiB (1%) | 26 |
| `["scalar", "arithmetic", "(\"div\", \"Complex{UInt64}\", \"Complex{Int64}\")"]` | 23.000 ns (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "arithmetic", "(\"div\", \"Complex{UInt64}\", \"Complex{UInt64}\")"]` | 23.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "arithmetic", "(\"div\", \"Complex{UInt64}\", \"Float32\")"]` | 23.000 ns (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "arithmetic", "(\"div\", \"Complex{UInt64}\", \"Float64\")"]` | 23.000 ns (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "arithmetic", "(\"div\", \"Complex{UInt64}\", \"Int64\")"]` | 23.000 ns (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "arithmetic", "(\"div\", \"Complex{UInt64}\", \"UInt64\")"]` | 23.000 ns (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "arithmetic", "(\"div\", \"Float32\", \"BigFloat\")"]` | 356.000 ns (50%) | 0.000 ns | 112 bytes (1%) | 2 |
| `["scalar", "arithmetic", "(\"div\", \"Float32\", \"BigInt\")"]` | 419.000 ns (50%) | 0.000 ns | 336 bytes (1%) | 6 |
| `["scalar", "arithmetic", "(\"div\", \"Float32\", \"ComplexF32\")"]` | 23.000 ns (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "arithmetic", "(\"div\", \"Float32\", \"ComplexF64\")"]` | 23.000 ns (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "arithmetic", "(\"div\", \"Float32\", \"Complex{BigFloat}\")"]` | 748.000 ns (50%) | 0.000 ns | 896 bytes (1%) | 16 |
| `["scalar", "arithmetic", "(\"div\", \"Float32\", \"Complex{BigInt}\")"]` | 858.000 ns (50%) | 0.000 ns | 1.09 KiB (1%) | 20 |
| `["scalar", "arithmetic", "(\"div\", \"Float32\", \"Complex{Int64}\")"]` | 23.000 ns (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "arithmetic", "(\"div\", \"Float32\", \"Complex{UInt64}\")"]` | 23.000 ns (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "arithmetic", "(\"div\", \"Float32\", \"Float32\")"]` | 23.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "arithmetic", "(\"div\", \"Float32\", \"Float64\")"]` | 23.000 ns (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "arithmetic", "(\"div\", \"Float32\", \"Int64\")"]` | 23.000 ns (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "arithmetic", "(\"div\", \"Float32\", \"UInt64\")"]` | 23.000 ns (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "arithmetic", "(\"div\", \"Float64\", \"BigFloat\")"]` | 357.000 ns (50%) | 0.000 ns | 112 bytes (1%) | 2 |
| `["scalar", "arithmetic", "(\"div\", \"Float64\", \"BigInt\")"]` | 421.000 ns (50%) | 0.000 ns | 336 bytes (1%) | 6 |
| `["scalar", "arithmetic", "(\"div\", \"Float64\", \"ComplexF32\")"]` | 23.000 ns (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "arithmetic", "(\"div\", \"Float64\", \"ComplexF64\")"]` | 23.000 ns (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "arithmetic", "(\"div\", \"Float64\", \"Complex{BigFloat}\")"]` | 753.000 ns (50%) | 0.000 ns | 896 bytes (1%) | 16 |
| `["scalar", "arithmetic", "(\"div\", \"Float64\", \"Complex{BigInt}\")"]` | 834.000 ns (50%) | 0.000 ns | 1.09 KiB (1%) | 20 |
| `["scalar", "arithmetic", "(\"div\", \"Float64\", \"Complex{Int64}\")"]` | 23.000 ns (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "arithmetic", "(\"div\", \"Float64\", \"Complex{UInt64}\")"]` | 23.000 ns (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "arithmetic", "(\"div\", \"Float64\", \"Float32\")"]` | 23.000 ns (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "arithmetic", "(\"div\", \"Float64\", \"Float64\")"]` | 23.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "arithmetic", "(\"div\", \"Float64\", \"Int64\")"]` | 23.000 ns (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "arithmetic", "(\"div\", \"Float64\", \"UInt64\")"]` | 23.000 ns (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "arithmetic", "(\"div\", \"Int64\", \"BigFloat\")"]` | 306.000 ns (50%) | 0.000 ns | 112 bytes (1%) | 2 |
| `["scalar", "arithmetic", "(\"div\", \"Int64\", \"BigInt\")"]` | 365.000 ns (50%) | 0.000 ns | 224 bytes (1%) | 4 |
| `["scalar", "arithmetic", "(\"div\", \"Int64\", \"ComplexF32\")"]` | 23.000 ns (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "arithmetic", "(\"div\", \"Int64\", \"ComplexF64\")"]` | 23.000 ns (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "arithmetic", "(\"div\", \"Int64\", \"Complex{BigFloat}\")"]` | 540.000 ns (50%) | 0.000 ns | 896 bytes (1%) | 16 |
| `["scalar", "arithmetic", "(\"div\", \"Int64\", \"Complex{BigInt}\")"]` | 624.000 ns (50%) | 0.000 ns | 1.09 KiB (1%) | 20 |
| `["scalar", "arithmetic", "(\"div\", \"Int64\", \"Complex{Int64}\")"]` | 23.000 ns (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "arithmetic", "(\"div\", \"Int64\", \"Complex{UInt64}\")"]` | 23.000 ns (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "arithmetic", "(\"div\", \"Int64\", \"Float32\")"]` | 23.000 ns (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "arithmetic", "(\"div\", \"Int64\", \"Float64\")"]` | 23.000 ns (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "arithmetic", "(\"div\", \"Int64\", \"Int64\")"]` | 23.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "arithmetic", "(\"div\", \"Int64\", \"UInt64\")"]` | 23.000 ns (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "arithmetic", "(\"div\", \"UInt64\", \"BigFloat\")"]` | 302.000 ns (50%) | 0.000 ns | 112 bytes (1%) | 2 |
| `["scalar", "arithmetic", "(\"div\", \"UInt64\", \"BigInt\")"]` | 364.000 ns (50%) | 0.000 ns | 224 bytes (1%) | 4 |
| `["scalar", "arithmetic", "(\"div\", \"UInt64\", \"ComplexF32\")"]` | 23.000 ns (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "arithmetic", "(\"div\", \"UInt64\", \"ComplexF64\")"]` | 23.000 ns (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "arithmetic", "(\"div\", \"UInt64\", \"Complex{BigFloat}\")"]` | 542.000 ns (50%) | 0.000 ns | 896 bytes (1%) | 16 |
| `["scalar", "arithmetic", "(\"div\", \"UInt64\", \"Complex{BigInt}\")"]` | 624.000 ns (50%) | 0.000 ns | 1.09 KiB (1%) | 20 |
| `["scalar", "arithmetic", "(\"div\", \"UInt64\", \"Complex{Int64}\")"]` | 23.000 ns (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "arithmetic", "(\"div\", \"UInt64\", \"Complex{UInt64}\")"]` | 23.000 ns (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "arithmetic", "(\"div\", \"UInt64\", \"Float32\")"]` | 23.000 ns (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "arithmetic", "(\"div\", \"UInt64\", \"Float64\")"]` | 23.000 ns (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "arithmetic", "(\"div\", \"UInt64\", \"Int64\")"]` | 23.000 ns (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "arithmetic", "(\"div\", \"UInt64\", \"UInt64\")"]` | 23.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "arithmetic", "(\"mul\", \"BigFloat\", \"BigFloat\")"]` | 101.000 ns (50%) | 0.000 ns | 112 bytes (1%) | 2 |
| `["scalar", "arithmetic", "(\"mul\", \"BigFloat\", \"BigInt\")"]` | 59.000 ns (50%) | 0.000 ns | 112 bytes (1%) | 2 |
| `["scalar", "arithmetic", "(\"mul\", \"BigFloat\", \"ComplexF32\")"]` | 219.000 ns (50%) | 0.000 ns | 224 bytes (1%) | 4 |
| `["scalar", "arithmetic", "(\"mul\", \"BigFloat\", \"ComplexF64\")"]` | 218.000 ns (50%) | 0.000 ns | 224 bytes (1%) | 4 |
| `["scalar", "arithmetic", "(\"mul\", \"BigFloat\", \"Complex{BigFloat}\")"]` | 132.000 ns (50%) | 0.000 ns | 224 bytes (1%) | 4 |
| `["scalar", "arithmetic", "(\"mul\", \"BigFloat\", \"Complex{BigInt}\")"]` | 88.000 ns (50%) | 0.000 ns | 224 bytes (1%) | 4 |
| `["scalar", "arithmetic", "(\"mul\", \"BigFloat\", \"Complex{Int64}\")"]` | 78.000 ns (50%) | 0.000 ns | 224 bytes (1%) | 4 |
| `["scalar", "arithmetic", "(\"mul\", \"BigFloat\", \"Complex{UInt64}\")"]` | 78.000 ns (50%) | 0.000 ns | 224 bytes (1%) | 4 |
| `["scalar", "arithmetic", "(\"mul\", \"BigFloat\", \"Float32\")"]` | 161.000 ns (50%) | 0.000 ns | 112 bytes (1%) | 2 |
| `["scalar", "arithmetic", "(\"mul\", \"BigFloat\", \"Float64\")"]` | 161.000 ns (50%) | 0.000 ns | 112 bytes (1%) | 2 |
| `["scalar", "arithmetic", "(\"mul\", \"BigFloat\", \"Int64\")"]` | 52.000 ns (50%) | 0.000 ns | 112 bytes (1%) | 2 |
| `["scalar", "arithmetic", "(\"mul\", \"BigFloat\", \"UInt64\")"]` | 51.000 ns (50%) | 0.000 ns | 112 bytes (1%) | 2 |
| `["scalar", "arithmetic", "(\"mul\", \"BigInt\", \"BigFloat\")"]` | 60.000 ns (50%) | 0.000 ns | 112 bytes (1%) | 2 |
| `["scalar", "arithmetic", "(\"mul\", \"BigInt\", \"BigInt\")"]` | 82.000 ns (50%) | 0.000 ns | 48 bytes (1%) | 3 |
| `["scalar", "arithmetic", "(\"mul\", \"BigInt\", \"ComplexF32\")"]` | 347.000 ns (50%) | 0.000 ns | 672 bytes (1%) | 12 |
| `["scalar", "arithmetic", "(\"mul\", \"BigInt\", \"ComplexF64\")"]` | 344.000 ns (50%) | 0.000 ns | 672 bytes (1%) | 12 |
| `["scalar", "arithmetic", "(\"mul\", \"BigInt\", \"Complex{BigFloat}\")"]` | 88.000 ns (50%) | 0.000 ns | 224 bytes (1%) | 4 |
| `["scalar", "arithmetic", "(\"mul\", \"BigInt\", \"Complex{BigInt}\")"]` | 105.000 ns (50%) | 0.000 ns | 88 bytes (1%) | 5 |
| `["scalar", "arithmetic", "(\"mul\", \"BigInt\", \"Complex{Int64}\")"]` | 101.000 ns (50%) | 0.000 ns | 88 bytes (1%) | 5 |
| `["scalar", "arithmetic", "(\"mul\", \"BigInt\", \"Complex{UInt64}\")"]` | 99.000 ns (50%) | 0.000 ns | 88 bytes (1%) | 5 |
| `["scalar", "arithmetic", "(\"mul\", \"BigInt\", \"Float32\")"]` | 234.000 ns (50%) | 0.000 ns | 336 bytes (1%) | 6 |
| `["scalar", "arithmetic", "(\"mul\", \"BigInt\", \"Float64\")"]` | 234.000 ns (50%) | 0.000 ns | 336 bytes (1%) | 6 |
| `["scalar", "arithmetic", "(\"mul\", \"BigInt\", \"Int64\")"]` | 78.000 ns (50%) | 0.000 ns | 48 bytes (1%) | 3 |
| `["scalar", "arithmetic", "(\"mul\", \"BigInt\", \"UInt64\")"]` | 78.000 ns (50%) | 0.000 ns | 48 bytes (1%) | 3 |
| `["scalar", "arithmetic", "(\"mul\", \"ComplexF32\", \"BigFloat\")"]` | 218.000 ns (50%) | 0.000 ns | 224 bytes (1%) | 4 |
| `["scalar", "arithmetic", "(\"mul\", \"ComplexF32\", \"BigInt\")"]` | 345.000 ns (50%) | 0.000 ns | 672 bytes (1%) | 12 |
| `["scalar", "arithmetic", "(\"mul\", \"ComplexF32\", \"ComplexF32\")"]` | 23.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "arithmetic", "(\"mul\", \"ComplexF32\", \"ComplexF64\")"]` | 23.000 ns (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "arithmetic", "(\"mul\", \"ComplexF32\", \"Complex{BigFloat}\")"]` | 453.000 ns (50%) | 0.000 ns | 672 bytes (1%) | 12 |
| `["scalar", "arithmetic", "(\"mul\", \"ComplexF32\", \"Complex{BigInt}\")"]` | 603.000 ns (50%) | 0.000 ns | 1.53 KiB (1%) | 28 |
| `["scalar", "arithmetic", "(\"mul\", \"ComplexF32\", \"Complex{Int64}\")"]` | 23.000 ns (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "arithmetic", "(\"mul\", \"ComplexF32\", \"Complex{UInt64}\")"]` | 23.000 ns (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "arithmetic", "(\"mul\", \"ComplexF32\", \"Float32\")"]` | 23.000 ns (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "arithmetic", "(\"mul\", \"ComplexF32\", \"Float64\")"]` | 23.000 ns (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "arithmetic", "(\"mul\", \"ComplexF32\", \"Int64\")"]` | 23.000 ns (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "arithmetic", "(\"mul\", \"ComplexF32\", \"UInt64\")"]` | 23.000 ns (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "arithmetic", "(\"mul\", \"ComplexF64\", \"BigFloat\")"]` | 218.000 ns (50%) | 0.000 ns | 224 bytes (1%) | 4 |
| `["scalar", "arithmetic", "(\"mul\", \"ComplexF64\", \"BigInt\")"]` | 346.000 ns (50%) | 0.000 ns | 672 bytes (1%) | 12 |
| `["scalar", "arithmetic", "(\"mul\", \"ComplexF64\", \"ComplexF32\")"]` | 23.000 ns (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "arithmetic", "(\"mul\", \"ComplexF64\", \"ComplexF64\")"]` | 23.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "arithmetic", "(\"mul\", \"ComplexF64\", \"Complex{BigFloat}\")"]` | 455.000 ns (50%) | 0.000 ns | 672 bytes (1%) | 12 |
| `["scalar", "arithmetic", "(\"mul\", \"ComplexF64\", \"Complex{BigInt}\")"]` | 601.000 ns (50%) | 0.000 ns | 1.53 KiB (1%) | 28 |
| `["scalar", "arithmetic", "(\"mul\", \"ComplexF64\", \"Complex{Int64}\")"]` | 23.000 ns (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "arithmetic", "(\"mul\", \"ComplexF64\", \"Complex{UInt64}\")"]` | 23.000 ns (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "arithmetic", "(\"mul\", \"ComplexF64\", \"Float32\")"]` | 23.000 ns (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "arithmetic", "(\"mul\", \"ComplexF64\", \"Float64\")"]` | 23.000 ns (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "arithmetic", "(\"mul\", \"ComplexF64\", \"Int64\")"]` | 23.000 ns (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "arithmetic", "(\"mul\", \"ComplexF64\", \"UInt64\")"]` | 23.000 ns (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "arithmetic", "(\"mul\", \"Complex{BigFloat}\", \"BigFloat\")"]` | 132.000 ns (50%) | 0.000 ns | 224 bytes (1%) | 4 |
| `["scalar", "arithmetic", "(\"mul\", \"Complex{BigFloat}\", \"BigInt\")"]` | 89.000 ns (50%) | 0.000 ns | 224 bytes (1%) | 4 |
| `["scalar", "arithmetic", "(\"mul\", \"Complex{BigFloat}\", \"ComplexF32\")"]` | 449.000 ns (50%) | 0.000 ns | 672 bytes (1%) | 12 |
| `["scalar", "arithmetic", "(\"mul\", \"Complex{BigFloat}\", \"ComplexF64\")"]` | 452.000 ns (50%) | 0.000 ns | 672 bytes (1%) | 12 |
| `["scalar", "arithmetic", "(\"mul\", \"Complex{BigFloat}\", \"Complex{BigFloat}\")"]` | 246.000 ns (50%) | 0.000 ns | 672 bytes (1%) | 12 |
| `["scalar", "arithmetic", "(\"mul\", \"Complex{BigFloat}\", \"Complex{BigInt}\")"]` | 208.000 ns (50%) | 0.000 ns | 672 bytes (1%) | 12 |
| `["scalar", "arithmetic", "(\"mul\", \"Complex{BigFloat}\", \"Complex{Int64}\")"]` | 189.000 ns (50%) | 0.000 ns | 672 bytes (1%) | 12 |
| `["scalar", "arithmetic", "(\"mul\", \"Complex{BigFloat}\", \"Complex{UInt64}\")"]` | 188.000 ns (50%) | 0.000 ns | 672 bytes (1%) | 12 |
| `["scalar", "arithmetic", "(\"mul\", \"Complex{BigFloat}\", \"Float32\")"]` | 279.000 ns (50%) | 0.000 ns | 224 bytes (1%) | 4 |
| `["scalar", "arithmetic", "(\"mul\", \"Complex{BigFloat}\", \"Float64\")"]` | 274.000 ns (50%) | 0.000 ns | 224 bytes (1%) | 4 |
| `["scalar", "arithmetic", "(\"mul\", \"Complex{BigFloat}\", \"Int64\")"]` | 78.000 ns (50%) | 0.000 ns | 224 bytes (1%) | 4 |
| `["scalar", "arithmetic", "(\"mul\", \"Complex{BigFloat}\", \"UInt64\")"]` | 78.000 ns (50%) | 0.000 ns | 224 bytes (1%) | 4 |
| `["scalar", "arithmetic", "(\"mul\", \"Complex{BigInt}\", \"BigFloat\")"]` | 89.000 ns (50%) | 0.000 ns | 224 bytes (1%) | 4 |
| `["scalar", "arithmetic", "(\"mul\", \"Complex{BigInt}\", \"BigInt\")"]` | 106.000 ns (50%) | 0.000 ns | 88 bytes (1%) | 5 |
| `["scalar", "arithmetic", "(\"mul\", \"Complex{BigInt}\", \"ComplexF32\")"]` | 596.000 ns (50%) | 0.000 ns | 1.53 KiB (1%) | 28 |
| `["scalar", "arithmetic", "(\"mul\", \"Complex{BigInt}\", \"ComplexF64\")"]` | 605.000 ns (50%) | 0.000 ns | 1.53 KiB (1%) | 28 |
| `["scalar", "arithmetic", "(\"mul\", \"Complex{BigInt}\", \"Complex{BigFloat}\")"]` | 207.000 ns (50%) | 0.000 ns | 672 bytes (1%) | 12 |
| `["scalar", "arithmetic", "(\"mul\", \"Complex{BigInt}\", \"Complex{BigInt}\")"]` | 218.000 ns (50%) | 0.000 ns | 256 bytes (1%) | 13 |
| `["scalar", "arithmetic", "(\"mul\", \"Complex{BigInt}\", \"Complex{Int64}\")"]` | 208.000 ns (50%) | 0.000 ns | 256 bytes (1%) | 13 |
| `["scalar", "arithmetic", "(\"mul\", \"Complex{BigInt}\", \"Complex{UInt64}\")"]` | 205.000 ns (50%) | 0.000 ns | 256 bytes (1%) | 13 |
| `["scalar", "arithmetic", "(\"mul\", \"Complex{BigInt}\", \"Float32\")"]` | 368.000 ns (50%) | 0.000 ns | 672 bytes (1%) | 12 |
| `["scalar", "arithmetic", "(\"mul\", \"Complex{BigInt}\", \"Float64\")"]` | 368.000 ns (50%) | 0.000 ns | 672 bytes (1%) | 12 |
| `["scalar", "arithmetic", "(\"mul\", \"Complex{BigInt}\", \"Int64\")"]` | 100.000 ns (50%) | 0.000 ns | 88 bytes (1%) | 5 |
| `["scalar", "arithmetic", "(\"mul\", \"Complex{BigInt}\", \"UInt64\")"]` | 99.000 ns (50%) | 0.000 ns | 88 bytes (1%) | 5 |
| `["scalar", "arithmetic", "(\"mul\", \"Complex{Int64}\", \"BigFloat\")"]` | 78.000 ns (50%) | 0.000 ns | 224 bytes (1%) | 4 |
| `["scalar", "arithmetic", "(\"mul\", \"Complex{Int64}\", \"BigInt\")"]` | 101.000 ns (50%) | 0.000 ns | 88 bytes (1%) | 5 |
| `["scalar", "arithmetic", "(\"mul\", \"Complex{Int64}\", \"ComplexF32\")"]` | 23.000 ns (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "arithmetic", "(\"mul\", \"Complex{Int64}\", \"ComplexF64\")"]` | 23.000 ns (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "arithmetic", "(\"mul\", \"Complex{Int64}\", \"Complex{BigFloat}\")"]` | 186.000 ns (50%) | 0.000 ns | 672 bytes (1%) | 12 |
| `["scalar", "arithmetic", "(\"mul\", \"Complex{Int64}\", \"Complex{BigInt}\")"]` | 213.000 ns (50%) | 0.000 ns | 256 bytes (1%) | 13 |
| `["scalar", "arithmetic", "(\"mul\", \"Complex{Int64}\", \"Complex{Int64}\")"]` | 23.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "arithmetic", "(\"mul\", \"Complex{Int64}\", \"Complex{UInt64}\")"]` | 23.000 ns (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "arithmetic", "(\"mul\", \"Complex{Int64}\", \"Float32\")"]` | 23.000 ns (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "arithmetic", "(\"mul\", \"Complex{Int64}\", \"Float64\")"]` | 23.000 ns (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "arithmetic", "(\"mul\", \"Complex{Int64}\", \"Int64\")"]` | 23.000 ns (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "arithmetic", "(\"mul\", \"Complex{Int64}\", \"UInt64\")"]` | 23.000 ns (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "arithmetic", "(\"mul\", \"Complex{UInt64}\", \"BigFloat\")"]` | 77.000 ns (50%) | 0.000 ns | 224 bytes (1%) | 4 |
| `["scalar", "arithmetic", "(\"mul\", \"Complex{UInt64}\", \"BigInt\")"]` | 100.000 ns (50%) | 0.000 ns | 88 bytes (1%) | 5 |
| `["scalar", "arithmetic", "(\"mul\", \"Complex{UInt64}\", \"ComplexF32\")"]` | 23.000 ns (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "arithmetic", "(\"mul\", \"Complex{UInt64}\", \"ComplexF64\")"]` | 23.000 ns (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "arithmetic", "(\"mul\", \"Complex{UInt64}\", \"Complex{BigFloat}\")"]` | 188.000 ns (50%) | 0.000 ns | 672 bytes (1%) | 12 |
| `["scalar", "arithmetic", "(\"mul\", \"Complex{UInt64}\", \"Complex{BigInt}\")"]` | 217.000 ns (50%) | 0.000 ns | 256 bytes (1%) | 13 |
| `["scalar", "arithmetic", "(\"mul\", \"Complex{UInt64}\", \"Complex{Int64}\")"]` | 23.000 ns (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "arithmetic", "(\"mul\", \"Complex{UInt64}\", \"Complex{UInt64}\")"]` | 23.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "arithmetic", "(\"mul\", \"Complex{UInt64}\", \"Float32\")"]` | 23.000 ns (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "arithmetic", "(\"mul\", \"Complex{UInt64}\", \"Float64\")"]` | 23.000 ns (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "arithmetic", "(\"mul\", \"Complex{UInt64}\", \"Int64\")"]` | 23.000 ns (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "arithmetic", "(\"mul\", \"Complex{UInt64}\", \"UInt64\")"]` | 23.000 ns (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "arithmetic", "(\"mul\", \"Float32\", \"BigFloat\")"]` | 162.000 ns (50%) | 0.000 ns | 112 bytes (1%) | 2 |
| `["scalar", "arithmetic", "(\"mul\", \"Float32\", \"BigInt\")"]` | 236.000 ns (50%) | 0.000 ns | 336 bytes (1%) | 6 |
| `["scalar", "arithmetic", "(\"mul\", \"Float32\", \"ComplexF32\")"]` | 23.000 ns (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "arithmetic", "(\"mul\", \"Float32\", \"ComplexF64\")"]` | 23.000 ns (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "arithmetic", "(\"mul\", \"Float32\", \"Complex{BigFloat}\")"]` | 273.000 ns (50%) | 0.000 ns | 224 bytes (1%) | 4 |
| `["scalar", "arithmetic", "(\"mul\", \"Float32\", \"Complex{BigInt}\")"]` | 367.000 ns (50%) | 0.000 ns | 672 bytes (1%) | 12 |
| `["scalar", "arithmetic", "(\"mul\", \"Float32\", \"Complex{Int64}\")"]` | 23.000 ns (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "arithmetic", "(\"mul\", \"Float32\", \"Complex{UInt64}\")"]` | 23.000 ns (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "arithmetic", "(\"mul\", \"Float32\", \"Float32\")"]` | 23.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "arithmetic", "(\"mul\", \"Float32\", \"Float64\")"]` | 23.000 ns (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "arithmetic", "(\"mul\", \"Float32\", \"Int64\")"]` | 23.000 ns (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "arithmetic", "(\"mul\", \"Float32\", \"UInt64\")"]` | 23.000 ns (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "arithmetic", "(\"mul\", \"Float64\", \"BigFloat\")"]` | 161.000 ns (50%) | 0.000 ns | 112 bytes (1%) | 2 |
| `["scalar", "arithmetic", "(\"mul\", \"Float64\", \"BigInt\")"]` | 235.000 ns (50%) | 0.000 ns | 336 bytes (1%) | 6 |
| `["scalar", "arithmetic", "(\"mul\", \"Float64\", \"ComplexF32\")"]` | 23.000 ns (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "arithmetic", "(\"mul\", \"Float64\", \"ComplexF64\")"]` | 23.000 ns (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "arithmetic", "(\"mul\", \"Float64\", \"Complex{BigFloat}\")"]` | 273.000 ns (50%) | 0.000 ns | 224 bytes (1%) | 4 |
| `["scalar", "arithmetic", "(\"mul\", \"Float64\", \"Complex{BigInt}\")"]` | 367.000 ns (50%) | 0.000 ns | 672 bytes (1%) | 12 |
| `["scalar", "arithmetic", "(\"mul\", \"Float64\", \"Complex{Int64}\")"]` | 23.000 ns (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "arithmetic", "(\"mul\", \"Float64\", \"Complex{UInt64}\")"]` | 23.000 ns (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "arithmetic", "(\"mul\", \"Float64\", \"Float32\")"]` | 23.000 ns (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "arithmetic", "(\"mul\", \"Float64\", \"Float64\")"]` | 23.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "arithmetic", "(\"mul\", \"Float64\", \"Int64\")"]` | 23.000 ns (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "arithmetic", "(\"mul\", \"Float64\", \"UInt64\")"]` | 23.000 ns (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "arithmetic", "(\"mul\", \"Int64\", \"BigFloat\")"]` | 52.000 ns (50%) | 0.000 ns | 112 bytes (1%) | 2 |
| `["scalar", "arithmetic", "(\"mul\", \"Int64\", \"BigInt\")"]` | 80.000 ns (50%) | 0.000 ns | 48 bytes (1%) | 3 |
| `["scalar", "arithmetic", "(\"mul\", \"Int64\", \"ComplexF32\")"]` | 23.000 ns (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "arithmetic", "(\"mul\", \"Int64\", \"ComplexF64\")"]` | 23.000 ns (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "arithmetic", "(\"mul\", \"Int64\", \"Complex{BigFloat}\")"]` | 77.000 ns (50%) | 0.000 ns | 224 bytes (1%) | 4 |
| `["scalar", "arithmetic", "(\"mul\", \"Int64\", \"Complex{BigInt}\")"]` | 100.000 ns (50%) | 0.000 ns | 88 bytes (1%) | 5 |
| `["scalar", "arithmetic", "(\"mul\", \"Int64\", \"Complex{Int64}\")"]` | 23.000 ns (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "arithmetic", "(\"mul\", \"Int64\", \"Complex{UInt64}\")"]` | 23.000 ns (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "arithmetic", "(\"mul\", \"Int64\", \"Float32\")"]` | 23.000 ns (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "arithmetic", "(\"mul\", \"Int64\", \"Float64\")"]` | 23.000 ns (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "arithmetic", "(\"mul\", \"Int64\", \"Int64\")"]` | 23.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "arithmetic", "(\"mul\", \"Int64\", \"UInt64\")"]` | 23.000 ns (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "arithmetic", "(\"mul\", \"UInt64\", \"BigFloat\")"]` | 52.000 ns (50%) | 0.000 ns | 112 bytes (1%) | 2 |
| `["scalar", "arithmetic", "(\"mul\", \"UInt64\", \"BigInt\")"]` | 78.000 ns (50%) | 0.000 ns | 48 bytes (1%) | 3 |
| `["scalar", "arithmetic", "(\"mul\", \"UInt64\", \"ComplexF32\")"]` | 23.000 ns (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "arithmetic", "(\"mul\", \"UInt64\", \"ComplexF64\")"]` | 23.000 ns (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "arithmetic", "(\"mul\", \"UInt64\", \"Complex{BigFloat}\")"]` | 77.000 ns (50%) | 0.000 ns | 224 bytes (1%) | 4 |
| `["scalar", "arithmetic", "(\"mul\", \"UInt64\", \"Complex{BigInt}\")"]` | 100.000 ns (50%) | 0.000 ns | 88 bytes (1%) | 5 |
| `["scalar", "arithmetic", "(\"mul\", \"UInt64\", \"Complex{Int64}\")"]` | 23.000 ns (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "arithmetic", "(\"mul\", \"UInt64\", \"Complex{UInt64}\")"]` | 23.000 ns (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "arithmetic", "(\"mul\", \"UInt64\", \"Float32\")"]` | 23.000 ns (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "arithmetic", "(\"mul\", \"UInt64\", \"Float64\")"]` | 23.000 ns (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "arithmetic", "(\"mul\", \"UInt64\", \"Int64\")"]` | 23.000 ns (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "arithmetic", "(\"mul\", \"UInt64\", \"UInt64\")"]` | 23.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "arithmetic", "(\"rem type\", \"BigInt\", \"BigInt\")"]` | 24.000 ns (40%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "arithmetic", "(\"rem type\", \"BigInt\", \"Bool\")"]` | 24.000 ns (40%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "arithmetic", "(\"rem type\", \"BigInt\", \"Int64\")"]` | 24.000 ns (40%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "arithmetic", "(\"rem type\", \"BigInt\", \"UInt64\")"]` | 24.000 ns (40%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "arithmetic", "(\"rem type\", \"Bool\", \"BigInt\")"]` | 44.000 ns (40%) | 0.000 ns | 40 bytes (1%) | 2 |
| `["scalar", "arithmetic", "(\"rem type\", \"Bool\", \"Bool\")"]` | 23.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "arithmetic", "(\"rem type\", \"Bool\", \"Int64\")"]` | 23.000 ns (40%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "arithmetic", "(\"rem type\", \"Bool\", \"UInt64\")"]` | 23.000 ns (40%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "arithmetic", "(\"rem type\", \"Char\", \"BigInt\")"]` | 46.000 ns (40%) | 0.000 ns | 40 bytes (1%) | 2 |
| `["scalar", "arithmetic", "(\"rem type\", \"Char\", \"Bool\")"]` | 23.000 ns (40%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "arithmetic", "(\"rem type\", \"Char\", \"Int64\")"]` | 23.000 ns (40%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "arithmetic", "(\"rem type\", \"Char\", \"UInt64\")"]` | 23.000 ns (40%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "arithmetic", "(\"rem type\", \"Int64\", \"BigInt\")"]` | 47.000 ns (40%) | 0.000 ns | 40 bytes (1%) | 2 |
| `["scalar", "arithmetic", "(\"rem type\", \"Int64\", \"Bool\")"]` | 23.000 ns (40%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "arithmetic", "(\"rem type\", \"Int64\", \"Int64\")"]` | 23.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "arithmetic", "(\"rem type\", \"Int64\", \"UInt64\")"]` | 23.000 ns (40%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "arithmetic", "(\"rem type\", \"UInt64\", \"BigInt\")"]` | 44.000 ns (40%) | 0.000 ns | 40 bytes (1%) | 2 |
| `["scalar", "arithmetic", "(\"rem type\", \"UInt64\", \"Bool\")"]` | 23.000 ns (40%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "arithmetic", "(\"rem type\", \"UInt64\", \"Int64\")"]` | 23.000 ns (40%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "arithmetic", "(\"rem type\", \"UInt64\", \"UInt64\")"]` | 23.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "arithmetic", "(\"sub\", \"BigFloat\", \"BigFloat\")"]` | 56.000 ns (50%) | 0.000 ns | 112 bytes (1%) | 2 |
| `["scalar", "arithmetic", "(\"sub\", \"BigFloat\", \"BigInt\")"]` | 92.000 ns (50%) | 0.000 ns | 112 bytes (1%) | 2 |
| `["scalar", "arithmetic", "(\"sub\", \"BigFloat\", \"ComplexF32\")"]` | 190.000 ns (50%) | 0.000 ns | 336 bytes (1%) | 6 |
| `["scalar", "arithmetic", "(\"sub\", \"BigFloat\", \"ComplexF64\")"]` | 190.000 ns (50%) | 0.000 ns | 336 bytes (1%) | 6 |
| `["scalar", "arithmetic", "(\"sub\", \"BigFloat\", \"Complex{BigFloat}\")"]` | 82.000 ns (50%) | 0.000 ns | 224 bytes (1%) | 4 |
| `["scalar", "arithmetic", "(\"sub\", \"BigFloat\", \"Complex{BigInt}\")"]` | 145.000 ns (50%) | 0.000 ns | 336 bytes (1%) | 6 |
| `["scalar", "arithmetic", "(\"sub\", \"BigFloat\", \"Complex{Int64}\")"]` | 141.000 ns (50%) | 0.000 ns | 336 bytes (1%) | 6 |
| `["scalar", "arithmetic", "(\"sub\", \"BigFloat\", \"Complex{UInt64}\")"]` | 140.000 ns (50%) | 0.000 ns | 336 bytes (1%) | 6 |
| `["scalar", "arithmetic", "(\"sub\", \"BigFloat\", \"Float32\")"]` | 133.000 ns (50%) | 0.000 ns | 112 bytes (1%) | 2 |
| `["scalar", "arithmetic", "(\"sub\", \"BigFloat\", \"Float64\")"]` | 136.000 ns (50%) | 0.000 ns | 112 bytes (1%) | 2 |
| `["scalar", "arithmetic", "(\"sub\", \"BigFloat\", \"Int64\")"]` | 84.000 ns (50%) | 0.000 ns | 112 bytes (1%) | 2 |
| `["scalar", "arithmetic", "(\"sub\", \"BigFloat\", \"UInt64\")"]` | 84.000 ns (50%) | 0.000 ns | 112 bytes (1%) | 2 |
| `["scalar", "arithmetic", "(\"sub\", \"BigInt\", \"BigFloat\")"]` | 92.000 ns (50%) | 0.000 ns | 112 bytes (1%) | 2 |
| `["scalar", "arithmetic", "(\"sub\", \"BigInt\", \"BigInt\")"]` | 57.000 ns (50%) | 0.000 ns | 48 bytes (1%) | 2 |
| `["scalar", "arithmetic", "(\"sub\", \"BigInt\", \"ComplexF32\")"]` | 245.000 ns (50%) | 0.000 ns | 560 bytes (1%) | 10 |
| `["scalar", "arithmetic", "(\"sub\", \"BigInt\", \"ComplexF64\")"]` | 237.000 ns (50%) | 0.000 ns | 560 bytes (1%) | 10 |
| `["scalar", "arithmetic", "(\"sub\", \"BigInt\", \"Complex{BigFloat}\")"]` | 120.000 ns (50%) | 0.000 ns | 224 bytes (1%) | 4 |
| `["scalar", "arithmetic", "(\"sub\", \"BigInt\", \"Complex{BigInt}\")"]` | 81.000 ns (50%) | 0.000 ns | 88 bytes (1%) | 4 |
| `["scalar", "arithmetic", "(\"sub\", \"BigInt\", \"Complex{Int64}\")"]` | 124.000 ns (50%) | 0.000 ns | 128 bytes (1%) | 7 |
| `["scalar", "arithmetic", "(\"sub\", \"BigInt\", \"Complex{UInt64}\")"]` | 122.000 ns (50%) | 0.000 ns | 128 bytes (1%) | 7 |
| `["scalar", "arithmetic", "(\"sub\", \"BigInt\", \"Float32\")"]` | 186.000 ns (50%) | 0.000 ns | 336 bytes (1%) | 6 |
| `["scalar", "arithmetic", "(\"sub\", \"BigInt\", \"Float64\")"]` | 186.000 ns (50%) | 0.000 ns | 336 bytes (1%) | 6 |
| `["scalar", "arithmetic", "(\"sub\", \"BigInt\", \"Int64\")"]` | 78.000 ns (50%) | 0.000 ns | 48 bytes (1%) | 3 |
| `["scalar", "arithmetic", "(\"sub\", \"BigInt\", \"UInt64\")"]` | 76.000 ns (50%) | 0.000 ns | 48 bytes (1%) | 3 |
| `["scalar", "arithmetic", "(\"sub\", \"ComplexF32\", \"BigFloat\")"]` | 164.000 ns (50%) | 0.000 ns | 224 bytes (1%) | 4 |
| `["scalar", "arithmetic", "(\"sub\", \"ComplexF32\", \"BigInt\")"]` | 214.000 ns (50%) | 0.000 ns | 448 bytes (1%) | 8 |
| `["scalar", "arithmetic", "(\"sub\", \"ComplexF32\", \"ComplexF32\")"]` | 23.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "arithmetic", "(\"sub\", \"ComplexF32\", \"ComplexF64\")"]` | 23.000 ns (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "arithmetic", "(\"sub\", \"ComplexF32\", \"Complex{BigFloat}\")"]` | 194.000 ns (50%) | 0.000 ns | 224 bytes (1%) | 4 |
| `["scalar", "arithmetic", "(\"sub\", \"ComplexF32\", \"Complex{BigInt}\")"]` | 269.000 ns (50%) | 0.000 ns | 672 bytes (1%) | 12 |
| `["scalar", "arithmetic", "(\"sub\", \"ComplexF32\", \"Complex{Int64}\")"]` | 23.000 ns (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "arithmetic", "(\"sub\", \"ComplexF32\", \"Complex{UInt64}\")"]` | 23.000 ns (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "arithmetic", "(\"sub\", \"ComplexF32\", \"Float32\")"]` | 23.000 ns (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "arithmetic", "(\"sub\", \"ComplexF32\", \"Float64\")"]` | 23.000 ns (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "arithmetic", "(\"sub\", \"ComplexF32\", \"Int64\")"]` | 23.000 ns (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "arithmetic", "(\"sub\", \"ComplexF32\", \"UInt64\")"]` | 23.000 ns (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "arithmetic", "(\"sub\", \"ComplexF64\", \"BigFloat\")"]` | 166.000 ns (50%) | 0.000 ns | 224 bytes (1%) | 4 |
| `["scalar", "arithmetic", "(\"sub\", \"ComplexF64\", \"BigInt\")"]` | 212.000 ns (50%) | 0.000 ns | 448 bytes (1%) | 8 |
| `["scalar", "arithmetic", "(\"sub\", \"ComplexF64\", \"ComplexF32\")"]` | 23.000 ns (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "arithmetic", "(\"sub\", \"ComplexF64\", \"ComplexF64\")"]` | 23.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "arithmetic", "(\"sub\", \"ComplexF64\", \"Complex{BigFloat}\")"]` | 194.000 ns (50%) | 0.000 ns | 224 bytes (1%) | 4 |
| `["scalar", "arithmetic", "(\"sub\", \"ComplexF64\", \"Complex{BigInt}\")"]` | 269.000 ns (50%) | 0.000 ns | 672 bytes (1%) | 12 |
| `["scalar", "arithmetic", "(\"sub\", \"ComplexF64\", \"Complex{Int64}\")"]` | 23.000 ns (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "arithmetic", "(\"sub\", \"ComplexF64\", \"Complex{UInt64}\")"]` | 23.000 ns (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "arithmetic", "(\"sub\", \"ComplexF64\", \"Float32\")"]` | 23.000 ns (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "arithmetic", "(\"sub\", \"ComplexF64\", \"Float64\")"]` | 23.000 ns (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "arithmetic", "(\"sub\", \"ComplexF64\", \"Int64\")"]` | 23.000 ns (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "arithmetic", "(\"sub\", \"ComplexF64\", \"UInt64\")"]` | 23.000 ns (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "arithmetic", "(\"sub\", \"Complex{BigFloat}\", \"BigFloat\")"]` | 58.000 ns (50%) | 0.000 ns | 112 bytes (1%) | 2 |
| `["scalar", "arithmetic", "(\"sub\", \"Complex{BigFloat}\", \"BigInt\")"]` | 92.000 ns (50%) | 0.000 ns | 112 bytes (1%) | 2 |
| `["scalar", "arithmetic", "(\"sub\", \"Complex{BigFloat}\", \"ComplexF32\")"]` | 192.000 ns (50%) | 0.000 ns | 224 bytes (1%) | 4 |
| `["scalar", "arithmetic", "(\"sub\", \"Complex{BigFloat}\", \"ComplexF64\")"]` | 191.000 ns (50%) | 0.000 ns | 224 bytes (1%) | 4 |
| `["scalar", "arithmetic", "(\"sub\", \"Complex{BigFloat}\", \"Complex{BigFloat}\")"]` | 84.000 ns (50%) | 0.000 ns | 224 bytes (1%) | 4 |
| `["scalar", "arithmetic", "(\"sub\", \"Complex{BigFloat}\", \"Complex{BigInt}\")"]` | 127.000 ns (50%) | 0.000 ns | 224 bytes (1%) | 4 |
| `["scalar", "arithmetic", "(\"sub\", \"Complex{BigFloat}\", \"Complex{Int64}\")"]` | 115.000 ns (50%) | 0.000 ns | 224 bytes (1%) | 4 |
| `["scalar", "arithmetic", "(\"sub\", \"Complex{BigFloat}\", \"Complex{UInt64}\")"]` | 111.000 ns (50%) | 0.000 ns | 224 bytes (1%) | 4 |
| `["scalar", "arithmetic", "(\"sub\", \"Complex{BigFloat}\", \"Float32\")"]` | 134.000 ns (50%) | 0.000 ns | 112 bytes (1%) | 2 |
| `["scalar", "arithmetic", "(\"sub\", \"Complex{BigFloat}\", \"Float64\")"]` | 135.000 ns (50%) | 0.000 ns | 112 bytes (1%) | 2 |
| `["scalar", "arithmetic", "(\"sub\", \"Complex{BigFloat}\", \"Int64\")"]` | 94.000 ns (50%) | 0.000 ns | 112 bytes (1%) | 2 |
| `["scalar", "arithmetic", "(\"sub\", \"Complex{BigFloat}\", \"UInt64\")"]` | 83.000 ns (50%) | 0.000 ns | 112 bytes (1%) | 2 |
| `["scalar", "arithmetic", "(\"sub\", \"Complex{BigInt}\", \"BigFloat\")"]` | 124.000 ns (50%) | 0.000 ns | 224 bytes (1%) | 4 |
| `["scalar", "arithmetic", "(\"sub\", \"Complex{BigInt}\", \"BigInt\")"]` | 56.000 ns (50%) | 0.000 ns | 48 bytes (1%) | 2 |
| `["scalar", "arithmetic", "(\"sub\", \"Complex{BigInt}\", \"ComplexF32\")"]` | 269.000 ns (50%) | 0.000 ns | 672 bytes (1%) | 12 |
| `["scalar", "arithmetic", "(\"sub\", \"Complex{BigInt}\", \"ComplexF64\")"]` | 267.000 ns (50%) | 0.000 ns | 672 bytes (1%) | 12 |
| `["scalar", "arithmetic", "(\"sub\", \"Complex{BigInt}\", \"Complex{BigFloat}\")"]` | 130.000 ns (50%) | 0.000 ns | 224 bytes (1%) | 4 |
| `["scalar", "arithmetic", "(\"sub\", \"Complex{BigInt}\", \"Complex{BigInt}\")"]` | 82.000 ns (50%) | 0.000 ns | 88 bytes (1%) | 4 |
| `["scalar", "arithmetic", "(\"sub\", \"Complex{BigInt}\", \"Complex{Int64}\")"]` | 100.000 ns (50%) | 0.000 ns | 88 bytes (1%) | 5 |
| `["scalar", "arithmetic", "(\"sub\", \"Complex{BigInt}\", \"Complex{UInt64}\")"]` | 99.000 ns (50%) | 0.000 ns | 88 bytes (1%) | 5 |
| `["scalar", "arithmetic", "(\"sub\", \"Complex{BigInt}\", \"Float32\")"]` | 212.000 ns (50%) | 0.000 ns | 448 bytes (1%) | 8 |
| `["scalar", "arithmetic", "(\"sub\", \"Complex{BigInt}\", \"Float64\")"]` | 212.000 ns (50%) | 0.000 ns | 448 bytes (1%) | 8 |
| `["scalar", "arithmetic", "(\"sub\", \"Complex{BigInt}\", \"Int64\")"]` | 78.000 ns (50%) | 0.000 ns | 48 bytes (1%) | 3 |
| `["scalar", "arithmetic", "(\"sub\", \"Complex{BigInt}\", \"UInt64\")"]` | 78.000 ns (50%) | 0.000 ns | 48 bytes (1%) | 3 |
| `["scalar", "arithmetic", "(\"sub\", \"Complex{Int64}\", \"BigFloat\")"]` | 121.000 ns (50%) | 0.000 ns | 224 bytes (1%) | 4 |
| `["scalar", "arithmetic", "(\"sub\", \"Complex{Int64}\", \"BigInt\")"]` | 70.000 ns (50%) | 0.000 ns | 80 bytes (1%) | 4 |
| `["scalar", "arithmetic", "(\"sub\", \"Complex{Int64}\", \"ComplexF32\")"]` | 23.000 ns (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "arithmetic", "(\"sub\", \"Complex{Int64}\", \"ComplexF64\")"]` | 23.000 ns (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "arithmetic", "(\"sub\", \"Complex{Int64}\", \"Complex{BigFloat}\")"]` | 116.000 ns (50%) | 0.000 ns | 224 bytes (1%) | 4 |
| `["scalar", "arithmetic", "(\"sub\", \"Complex{Int64}\", \"Complex{BigInt}\")"]` | 79.000 ns (50%) | 0.000 ns | 80 bytes (1%) | 4 |
| `["scalar", "arithmetic", "(\"sub\", \"Complex{Int64}\", \"Complex{Int64}\")"]` | 23.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "arithmetic", "(\"sub\", \"Complex{Int64}\", \"Complex{UInt64}\")"]` | 23.000 ns (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "arithmetic", "(\"sub\", \"Complex{Int64}\", \"Float32\")"]` | 23.000 ns (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "arithmetic", "(\"sub\", \"Complex{Int64}\", \"Float64\")"]` | 23.000 ns (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "arithmetic", "(\"sub\", \"Complex{Int64}\", \"Int64\")"]` | 23.000 ns (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "arithmetic", "(\"sub\", \"Complex{Int64}\", \"UInt64\")"]` | 23.000 ns (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "arithmetic", "(\"sub\", \"Complex{UInt64}\", \"BigFloat\")"]` | 116.000 ns (50%) | 0.000 ns | 224 bytes (1%) | 4 |
| `["scalar", "arithmetic", "(\"sub\", \"Complex{UInt64}\", \"BigInt\")"]` | 70.000 ns (50%) | 0.000 ns | 80 bytes (1%) | 4 |
| `["scalar", "arithmetic", "(\"sub\", \"Complex{UInt64}\", \"ComplexF32\")"]` | 23.000 ns (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "arithmetic", "(\"sub\", \"Complex{UInt64}\", \"ComplexF64\")"]` | 23.000 ns (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "arithmetic", "(\"sub\", \"Complex{UInt64}\", \"Complex{BigFloat}\")"]` | 115.000 ns (50%) | 0.000 ns | 224 bytes (1%) | 4 |
| `["scalar", "arithmetic", "(\"sub\", \"Complex{UInt64}\", \"Complex{BigInt}\")"]` | 71.000 ns (50%) | 0.000 ns | 80 bytes (1%) | 4 |
| `["scalar", "arithmetic", "(\"sub\", \"Complex{UInt64}\", \"Complex{Int64}\")"]` | 23.000 ns (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "arithmetic", "(\"sub\", \"Complex{UInt64}\", \"Complex{UInt64}\")"]` | 23.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "arithmetic", "(\"sub\", \"Complex{UInt64}\", \"Float32\")"]` | 23.000 ns (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "arithmetic", "(\"sub\", \"Complex{UInt64}\", \"Float64\")"]` | 23.000 ns (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "arithmetic", "(\"sub\", \"Complex{UInt64}\", \"Int64\")"]` | 23.000 ns (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "arithmetic", "(\"sub\", \"Complex{UInt64}\", \"UInt64\")"]` | 23.000 ns (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "arithmetic", "(\"sub\", \"Float32\", \"BigFloat\")"]` | 134.000 ns (50%) | 0.000 ns | 112 bytes (1%) | 2 |
| `["scalar", "arithmetic", "(\"sub\", \"Float32\", \"BigInt\")"]` | 184.000 ns (50%) | 0.000 ns | 336 bytes (1%) | 6 |
| `["scalar", "arithmetic", "(\"sub\", \"Float32\", \"ComplexF32\")"]` | 23.000 ns (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "arithmetic", "(\"sub\", \"Float32\", \"ComplexF64\")"]` | 23.000 ns (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "arithmetic", "(\"sub\", \"Float32\", \"Complex{BigFloat}\")"]` | 165.000 ns (50%) | 0.000 ns | 224 bytes (1%) | 4 |
| `["scalar", "arithmetic", "(\"sub\", \"Float32\", \"Complex{BigInt}\")"]` | 244.000 ns (50%) | 0.000 ns | 560 bytes (1%) | 10 |
| `["scalar", "arithmetic", "(\"sub\", \"Float32\", \"Complex{Int64}\")"]` | 23.000 ns (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "arithmetic", "(\"sub\", \"Float32\", \"Complex{UInt64}\")"]` | 23.000 ns (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "arithmetic", "(\"sub\", \"Float32\", \"Float32\")"]` | 23.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "arithmetic", "(\"sub\", \"Float32\", \"Float64\")"]` | 23.000 ns (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "arithmetic", "(\"sub\", \"Float32\", \"Int64\")"]` | 23.000 ns (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "arithmetic", "(\"sub\", \"Float32\", \"UInt64\")"]` | 23.000 ns (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "arithmetic", "(\"sub\", \"Float64\", \"BigFloat\")"]` | 136.000 ns (50%) | 0.000 ns | 112 bytes (1%) | 2 |
| `["scalar", "arithmetic", "(\"sub\", \"Float64\", \"BigInt\")"]` | 187.000 ns (50%) | 0.000 ns | 336 bytes (1%) | 6 |
| `["scalar", "arithmetic", "(\"sub\", \"Float64\", \"ComplexF32\")"]` | 23.000 ns (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "arithmetic", "(\"sub\", \"Float64\", \"ComplexF64\")"]` | 23.000 ns (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "arithmetic", "(\"sub\", \"Float64\", \"Complex{BigFloat}\")"]` | 165.000 ns (50%) | 0.000 ns | 224 bytes (1%) | 4 |
| `["scalar", "arithmetic", "(\"sub\", \"Float64\", \"Complex{BigInt}\")"]` | 238.000 ns (50%) | 0.000 ns | 560 bytes (1%) | 10 |
| `["scalar", "arithmetic", "(\"sub\", \"Float64\", \"Complex{Int64}\")"]` | 23.000 ns (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "arithmetic", "(\"sub\", \"Float64\", \"Complex{UInt64}\")"]` | 23.000 ns (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "arithmetic", "(\"sub\", \"Float64\", \"Float32\")"]` | 23.000 ns (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "arithmetic", "(\"sub\", \"Float64\", \"Float64\")"]` | 23.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "arithmetic", "(\"sub\", \"Float64\", \"Int64\")"]` | 23.000 ns (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "arithmetic", "(\"sub\", \"Float64\", \"UInt64\")"]` | 23.000 ns (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "arithmetic", "(\"sub\", \"Int64\", \"BigFloat\")"]` | 85.000 ns (50%) | 0.000 ns | 112 bytes (1%) | 2 |
| `["scalar", "arithmetic", "(\"sub\", \"Int64\", \"BigInt\")"]` | 48.000 ns (50%) | 0.000 ns | 40 bytes (1%) | 2 |
| `["scalar", "arithmetic", "(\"sub\", \"Int64\", \"ComplexF32\")"]` | 23.000 ns (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "arithmetic", "(\"sub\", \"Int64\", \"ComplexF64\")"]` | 23.000 ns (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "arithmetic", "(\"sub\", \"Int64\", \"Complex{BigFloat}\")"]` | 113.000 ns (50%) | 0.000 ns | 224 bytes (1%) | 4 |
| `["scalar", "arithmetic", "(\"sub\", \"Int64\", \"Complex{BigInt}\")"]` | 74.000 ns (50%) | 0.000 ns | 80 bytes (1%) | 4 |
| `["scalar", "arithmetic", "(\"sub\", \"Int64\", \"Complex{Int64}\")"]` | 23.000 ns (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "arithmetic", "(\"sub\", \"Int64\", \"Complex{UInt64}\")"]` | 23.000 ns (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "arithmetic", "(\"sub\", \"Int64\", \"Float32\")"]` | 23.000 ns (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "arithmetic", "(\"sub\", \"Int64\", \"Float64\")"]` | 23.000 ns (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "arithmetic", "(\"sub\", \"Int64\", \"Int64\")"]` | 23.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "arithmetic", "(\"sub\", \"Int64\", \"UInt64\")"]` | 23.000 ns (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "arithmetic", "(\"sub\", \"UInt64\", \"BigFloat\")"]` | 84.000 ns (50%) | 0.000 ns | 112 bytes (1%) | 2 |
| `["scalar", "arithmetic", "(\"sub\", \"UInt64\", \"BigInt\")"]` | 46.000 ns (50%) | 0.000 ns | 40 bytes (1%) | 2 |
| `["scalar", "arithmetic", "(\"sub\", \"UInt64\", \"ComplexF32\")"]` | 23.000 ns (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "arithmetic", "(\"sub\", \"UInt64\", \"ComplexF64\")"]` | 23.000 ns (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "arithmetic", "(\"sub\", \"UInt64\", \"Complex{BigFloat}\")"]` | 112.000 ns (50%) | 0.000 ns | 224 bytes (1%) | 4 |
| `["scalar", "arithmetic", "(\"sub\", \"UInt64\", \"Complex{BigInt}\")"]` | 72.000 ns (50%) | 0.000 ns | 80 bytes (1%) | 4 |
| `["scalar", "arithmetic", "(\"sub\", \"UInt64\", \"Complex{Int64}\")"]` | 23.000 ns (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "arithmetic", "(\"sub\", \"UInt64\", \"Complex{UInt64}\")"]` | 23.000 ns (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "arithmetic", "(\"sub\", \"UInt64\", \"Float32\")"]` | 23.000 ns (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "arithmetic", "(\"sub\", \"UInt64\", \"Float64\")"]` | 23.000 ns (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "arithmetic", "(\"sub\", \"UInt64\", \"Int64\")"]` | 23.000 ns (50%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "arithmetic", "(\"sub\", \"UInt64\", \"UInt64\")"]` | 23.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "asin", "(\"0.5 <= abs(x) < 0.975\", \"negative argument\", \"Float32\")"]` | 24.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "asin", "(\"0.5 <= abs(x) < 0.975\", \"negative argument\", \"Float64\")"]` | 42.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "asin", "(\"0.5 <= abs(x) < 0.975\", \"positive argument\", \"Float32\")"]` | 38.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "asin", "(\"0.5 <= abs(x) < 0.975\", \"positive argument\", \"Float64\")"]` | 42.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "asin", "(\"0.975 <= abs(x) < 1.0\", \"negative argument\", \"Float64\")"]` | 40.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "asin", "(\"0.975 <= abs(x) < 1.0\", \"positive argument\", \"Float64\")"]` | 40.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "asin", "(\"abs(x) < 0.5\", \"negative argument\", \"Float32\")"]` | 30.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "asin", "(\"abs(x) < 0.5\", \"negative argument\", \"Float64\")"]` | 37.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "asin", "(\"abs(x) < 0.5\", \"positive argument\", \"Float32\")"]` | 30.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "asin", "(\"abs(x) < 0.5\", \"positive argument\", \"Float64\")"]` | 36.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "asin", "(\"one\", \"negative argument\", \"Float32\")"]` | 23.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "asin", "(\"one\", \"negative argument\", \"Float64\")"]` | 23.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "asin", "(\"one\", \"positive argument\", \"Float32\")"]` | 23.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "asin", "(\"one\", \"positive argument\", \"Float64\")"]` | 23.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "asin", "(\"small\", \"negative argument\", \"Float32\")"]` | 26.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "asin", "(\"small\", \"negative argument\", \"Float64\")"]` | 26.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "asin", "(\"small\", \"positive argument\", \"Float32\")"]` | 26.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "asin", "(\"small\", \"positive argument\", \"Float64\")"]` | 26.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "asin", "(\"zero\", \"Float32\")"]` | 26.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "asin", "(\"zero\", \"Float64\")"]` | 26.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "asinh", "(\"0 <= abs(x) < 2^-28\", \"negative argument\", \"Float32\")"]` | 38.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "asinh", "(\"0 <= abs(x) < 2^-28\", \"negative argument\", \"Float64\")"]` | 54.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "asinh", "(\"0 <= abs(x) < 2^-28\", \"positive argument\", \"Float32\")"]` | 38.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "asinh", "(\"0 <= abs(x) < 2^-28\", \"positive argument\", \"Float64\")"]` | 54.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "asinh", "(\"2 <= abs(x) < 2^28\", \"negative argument\", \"Float32\")"]` | 55.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "asinh", "(\"2 <= abs(x) < 2^28\", \"negative argument\", \"Float64\")"]` | 58.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "asinh", "(\"2 <= abs(x) < 2^28\", \"positive argument\", \"Float32\")"]` | 55.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "asinh", "(\"2 <= abs(x) < 2^28\", \"positive argument\", \"Float64\")"]` | 58.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "asinh", "(\"2^-28 <= abs(x) < 2\", \"negative argument\", \"Float32\")"]` | 59.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "asinh", "(\"2^-28 <= abs(x) < 2\", \"negative argument\", \"Float64\")"]` | 64.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "asinh", "(\"2^-28 <= abs(x) < 2\", \"positive argument\", \"Float32\")"]` | 59.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "asinh", "(\"2^-28 <= abs(x) < 2\", \"positive argument\", \"Float64\")"]` | 62.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "asinh", "(\"very large\", \"negative argument\", \"Float32\")"]` | 45.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "asinh", "(\"very large\", \"negative argument\", \"Float64\")"]` | 45.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "asinh", "(\"very large\", \"positive argument\", \"Float32\")"]` | 45.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "asinh", "(\"very large\", \"positive argument\", \"Float64\")"]` | 44.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "asinh", "(\"very small\", \"negative argument\", \"Float32\")"]` | 26.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "asinh", "(\"very small\", \"negative argument\", \"Float64\")"]` | 26.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "asinh", "(\"very small\", \"positive argument\", \"Float32\")"]` | 26.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "asinh", "(\"very small\", \"positive argument\", \"Float64\")"]` | 26.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "asinh", "(\"zero\", \"Float32\")"]` | 26.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "asinh", "(\"zero\", \"Float64\")"]` | 26.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "atan", "(\"0 <= abs(x) < 7/16\", \"negative argument\", \"Float32\")"]` | 29.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "atan", "(\"0 <= abs(x) < 7/16\", \"negative argument\", \"Float64\")"]` | 36.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "atan", "(\"0 <= abs(x) < 7/16\", \"positive argument\", \"Float32\")"]` | 29.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "atan", "(\"0 <= abs(x) < 7/16\", \"positive argument\", \"Float64\")"]` | 36.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "atan", "(\"11/16 <= abs(x) < 19/16\", \"negative argument\", \"Float32\")"]` | 40.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "atan", "(\"11/16 <= abs(x) < 19/16\", \"negative argument\", \"Float64\")"]` | 44.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "atan", "(\"11/16 <= abs(x) < 19/16\", \"positive argument\", \"Float32\")"]` | 40.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "atan", "(\"11/16 <= abs(x) < 19/16\", \"positive argument\", \"Float64\")"]` | 44.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "atan", "(\"19/16 <= abs(x) < 39/16\", \"negative argument\", \"Float32\")"]` | 42.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "atan", "(\"19/16 <= abs(x) < 39/16\", \"negative argument\", \"Float64\")"]` | 46.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "atan", "(\"19/16 <= abs(x) < 39/16\", \"positive argument\", \"Float32\")"]` | 42.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "atan", "(\"19/16 <= abs(x) < 39/16\", \"positive argument\", \"Float64\")"]` | 46.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "atan", "(\"39/16 <= abs(x) < 2^66\", \"negative argument\", \"Float32\")"]` | 38.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "atan", "(\"39/16 <= abs(x) < 2^66\", \"negative argument\", \"Float64\")"]` | 42.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "atan", "(\"39/16 <= abs(x) < 2^66\", \"positive argument\", \"Float32\")"]` | 38.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "atan", "(\"39/16 <= abs(x) < 2^66\", \"positive argument\", \"Float64\")"]` | 43.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "atan", "(\"7/16 <= abs(x) < 11/16\", \"negative argument\", \"Float32\")"]` | 41.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "atan", "(\"7/16 <= abs(x) < 11/16\", \"negative argument\", \"Float64\")"]` | 45.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "atan", "(\"7/16 <= abs(x) < 11/16\", \"positive argument\", \"Float32\")"]` | 40.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "atan", "(\"7/16 <= abs(x) < 11/16\", \"positive argument\", \"Float64\")"]` | 45.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "atan", "(\"very large\", \"negative argument\", \"Float32\")"]` | 25.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "atan", "(\"very large\", \"negative argument\", \"Float64\")"]` | 25.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "atan", "(\"very large\", \"positive argument\", \"Float32\")"]` | 25.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "atan", "(\"very large\", \"positive argument\", \"Float64\")"]` | 25.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "atan", "(\"very small\", \"negative argument\", \"Float32\")"]` | 26.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "atan", "(\"very small\", \"negative argument\", \"Float64\")"]` | 26.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "atan", "(\"very small\", \"positive argument\", \"Float32\")"]` | 26.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "atan", "(\"very small\", \"positive argument\", \"Float64\")"]` | 26.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "atan", "(\"zero\", \"Float32\")"]` | 26.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "atan", "(\"zero\", \"Float64\")"]` | 26.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "atan2", "(\"abs(y/x) high\", \"y infinite\", \"y negative\", \"x finite\", \"x negative\", \"Float32\")"]` | 23.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "atan2", "(\"abs(y/x) high\", \"y infinite\", \"y negative\", \"x finite\", \"x negative\", \"Float64\")"]` | 23.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "atan2", "(\"abs(y/x) high\", \"y negative\", \"x negative\", \"Float32\")"]` | 23.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "atan2", "(\"abs(y/x) high\", \"y negative\", \"x negative\", \"Float64\")"]` | 23.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "atan2", "(\"abs(y/x) high\", \"y negative\", \"x positive\", \"Float32\")"]` | 26.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "atan2", "(\"abs(y/x) high\", \"y negative\", \"x positive\", \"Float64\")"]` | 44.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "atan2", "(\"abs(y/x) high\", \"y positive\", \"x negative\", \"Float32\")"]` | 23.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "atan2", "(\"abs(y/x) high\", \"y positive\", \"x negative\", \"Float64\")"]` | 23.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "atan2", "(\"abs(y/x) high\", \"y positive\", \"x positive\", \"Float32\")"]` | 26.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "atan2", "(\"abs(y/x) high\", \"y positive\", \"x positive\", \"Float64\")"]` | 44.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "atan2", "(\"abs(y/x) safe (large)\", \"y negative\", \"x negative\", \"Float32\")"]` | 47.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "atan2", "(\"abs(y/x) safe (large)\", \"y negative\", \"x negative\", \"Float64\")"]` | 53.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "atan2", "(\"abs(y/x) safe (large)\", \"y negative\", \"x positive\", \"Float32\")"]` | 46.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "atan2", "(\"abs(y/x) safe (large)\", \"y negative\", \"x positive\", \"Float64\")"]` | 50.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "atan2", "(\"abs(y/x) safe (large)\", \"y positive\", \"x negative\", \"Float32\")"]` | 47.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "atan2", "(\"abs(y/x) safe (large)\", \"y positive\", \"x negative\", \"Float64\")"]` | 53.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "atan2", "(\"abs(y/x) safe (large)\", \"y positive\", \"x positive\", \"Float32\")"]` | 45.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "atan2", "(\"abs(y/x) safe (large)\", \"y positive\", \"x positive\", \"Float64\")"]` | 50.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "atan2", "(\"abs(y/x) safe (small)\", \"y negative\", \"x negative\", \"Float32\")"]` | 48.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "atan2", "(\"abs(y/x) safe (small)\", \"y negative\", \"x negative\", \"Float64\")"]` | 54.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "atan2", "(\"abs(y/x) safe (small)\", \"y negative\", \"x positive\", \"Float32\")"]` | 47.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "atan2", "(\"abs(y/x) safe (small)\", \"y negative\", \"x positive\", \"Float64\")"]` | 52.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "atan2", "(\"abs(y/x) safe (small)\", \"y positive\", \"x negative\", \"Float32\")"]` | 48.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "atan2", "(\"abs(y/x) safe (small)\", \"y positive\", \"x negative\", \"Float64\")"]` | 54.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "atan2", "(\"abs(y/x) safe (small)\", \"y positive\", \"x positive\", \"Float32\")"]` | 46.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "atan2", "(\"abs(y/x) safe (small)\", \"y positive\", \"x positive\", \"Float64\")"]` | 51.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "atan2", "(\"abs(y/x) small\", \"y positive\", \"x negative\", \"Float32\")"]` | 23.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "atan2", "(\"abs(y/x) small\", \"y positive\", \"x negative\", \"Float64\")"]` | 23.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "atan2", "(\"abs(y/x) small\", \"y positive\", \"x positive\", \"Float32\")"]` | 27.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "atan2", "(\"abs(y/x) small\", \"y positive\", \"x positive\", \"Float64\")"]` | 27.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "atan2", "(\"x one\", \"Float32\")"]` | 42.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "atan2", "(\"x one\", \"Float64\")"]` | 48.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "atan2", "(\"x zero\", \"y negative\", \"Float32\")"]` | 23.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "atan2", "(\"x zero\", \"y negative\", \"Float64\")"]` | 23.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "atan2", "(\"x zero\", \"y positive\", \"Float32\")"]` | 23.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "atan2", "(\"x zero\", \"y positive\", \"Float64\")"]` | 23.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "atan2", "(\"y finite\", \"y negative\", \"x infinite\", \"x negative\", \"Float32\")"]` | 23.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "atan2", "(\"y finite\", \"y negative\", \"x infinite\", \"x negative\", \"Float64\")"]` | 23.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "atan2", "(\"y finite\", \"y negative\", \"x infinite\", \"x positive\", \"Float32\")"]` | 23.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "atan2", "(\"y finite\", \"y negative\", \"x infinite\", \"x positive\", \"Float64\")"]` | 23.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "atan2", "(\"y finite\", \"y positive\", \"x infinite\", \"x negative\", \"Float32\")"]` | 23.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "atan2", "(\"y finite\", \"y positive\", \"x infinite\", \"x negative\", \"Float64\")"]` | 23.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "atan2", "(\"y finite\", \"y positive\", \"x infinite\", \"x positive\", \"Float32\")"]` | 23.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "atan2", "(\"y finite\", \"y positive\", \"x infinite\", \"x positive\", \"Float64\")"]` | 23.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "atan2", "(\"y infinite\", \"y negative\", \"x finite\", \"x negative\", \"Float32\")"]` | 23.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "atan2", "(\"y infinite\", \"y negative\", \"x finite\", \"x negative\", \"Float64\")"]` | 23.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "atan2", "(\"y infinite\", \"y negative\", \"x finite\", \"x positive\", \"Float32\")"]` | 23.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "atan2", "(\"y infinite\", \"y negative\", \"x finite\", \"x positive\", \"Float64\")"]` | 23.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "atan2", "(\"y infinite\", \"y negative\", \"x infinite\", \"x negative\", \"Float32\")"]` | 23.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "atan2", "(\"y infinite\", \"y negative\", \"x infinite\", \"x negative\", \"Float64\")"]` | 23.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "atan2", "(\"y infinite\", \"y negative\", \"x infinite\", \"x positive\", \"Float32\")"]` | 23.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "atan2", "(\"y infinite\", \"y negative\", \"x infinite\", \"x positive\", \"Float64\")"]` | 23.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "atan2", "(\"y infinite\", \"y positive\", \"x finite\", \"x negative\", \"Float32\")"]` | 23.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "atan2", "(\"y infinite\", \"y positive\", \"x finite\", \"x negative\", \"Float64\")"]` | 23.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "atan2", "(\"y infinite\", \"y positive\", \"x finite\", \"x positive\", \"Float32\")"]` | 23.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "atan2", "(\"y infinite\", \"y positive\", \"x finite\", \"x positive\", \"Float64\")"]` | 23.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "atan2", "(\"y infinite\", \"y positive\", \"x infinite\", \"x negative\", \"Float32\")"]` | 23.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "atan2", "(\"y infinite\", \"y positive\", \"x infinite\", \"x negative\", \"Float64\")"]` | 23.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "atan2", "(\"y infinite\", \"y positive\", \"x infinite\", \"x positive\", \"Float32\")"]` | 23.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "atan2", "(\"y infinite\", \"y positive\", \"x infinite\", \"x positive\", \"Float64\")"]` | 23.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "atan2", "(\"y zero\", \"y negative\", \"x negative\", \"Float32\")"]` | 23.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "atan2", "(\"y zero\", \"y negative\", \"x negative\", \"Float64\")"]` | 23.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "atan2", "(\"y zero\", \"y negative\", \"x positive\", \"Float32\")"]` | 23.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "atan2", "(\"y zero\", \"y negative\", \"x positive\", \"Float64\")"]` | 23.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "atan2", "(\"y zero\", \"y positive\", \"x negative\", \"Float32\")"]` | 23.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "atan2", "(\"y zero\", \"y positive\", \"x negative\", \"Float64\")"]` | 23.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "atan2", "(\"y zero\", \"y positive\", \"x positive\", \"Float32\")"]` | 23.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "atan2", "(\"y zero\", \"y positive\", \"x positive\", \"Float64\")"]` | 23.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "atanh", "(\"0.5 <= abs(x) < 1\", \"negative argument\", \"Float32\")"]` | 23.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "atanh", "(\"0.5 <= abs(x) < 1\", \"negative argument\", \"Float64\")"]` | 50.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "atanh", "(\"0.5 <= abs(x) < 1\", \"positive argument\", \"Float32\")"]` | 23.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "atanh", "(\"0.5 <= abs(x) < 1\", \"positive argument\", \"Float64\")"]` | 50.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "atanh", "(\"2^-28 <= abs(x) < 0.5\", \"negative argument\", \"Float32\")"]` | 23.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "atanh", "(\"2^-28 <= abs(x) < 0.5\", \"negative argument\", \"Float64\")"]` | 53.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "atanh", "(\"2^-28 <= abs(x) < 0.5\", \"positive argument\", \"Float32\")"]` | 23.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "atanh", "(\"2^-28 <= abs(x) < 0.5\", \"positive argument\", \"Float64\")"]` | 52.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "atanh", "(\"one\", \"Float32\")"]` | 23.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "atanh", "(\"one\", \"Float64\")"]` | 23.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "atanh", "(\"very small\", \"negative argument\", \"Float32\")"]` | 23.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "atanh", "(\"very small\", \"negative argument\", \"Float64\")"]` | 23.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "atanh", "(\"very small\", \"positive argument\", \"Float32\")"]` | 23.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "atanh", "(\"very small\", \"positive argument\", \"Float64\")"]` | 23.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "atanh", "(\"zero\", \"Float32\")"]` | 23.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "atanh", "(\"zero\", \"Float64\")"]` | 23.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "cbrt", "(\"large\", \"negative argument\", \"Float32\")"]` | 23.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "cbrt", "(\"large\", \"negative argument\", \"Float64\")"]` | 49.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "cbrt", "(\"large\", \"positive argument\", \"Float32\")"]` | 23.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "cbrt", "(\"large\", \"positive argument\", \"Float64\")"]` | 50.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "cbrt", "(\"medium\", \"negative argument\", \"Float32\")"]` | 23.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "cbrt", "(\"medium\", \"negative argument\", \"Float64\")"]` | 50.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "cbrt", "(\"medium\", \"positive argument\", \"Float32\")"]` | 23.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "cbrt", "(\"medium\", \"positive argument\", \"Float64\")"]` | 49.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "cbrt", "(\"one\", \"Float32\")"]` | 23.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "cbrt", "(\"one\", \"Float64\")"]` | 49.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "cbrt", "(\"small\", \"negative argument\", \"Float32\")"]` | 23.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "cbrt", "(\"small\", \"negative argument\", \"Float64\")"]` | 49.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "cbrt", "(\"small\", \"positive argument\", \"Float32\")"]` | 23.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "cbrt", "(\"small\", \"positive argument\", \"Float64\")"]` | 49.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "cbrt", "(\"very small\", \"negative argument\", \"Float32\")"]` | 23.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "cbrt", "(\"very small\", \"negative argument\", \"Float64\")"]` | 178.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "cbrt", "(\"very small\", \"positive argument\", \"Float32\")"]` | 23.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "cbrt", "(\"very small\", \"positive argument\", \"Float64\")"]` | 178.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "cbrt", "(\"zero\", \"Float32\")"]` | 23.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "cbrt", "(\"zero\", \"Float64\")"]` | 23.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "cos", "(\"argument reduction (easy) abs(x) < 2.0^20π/4\", \"negative argument\", \"Float32\", \"cos_kernel\")"]` | 38.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "cos", "(\"argument reduction (easy) abs(x) < 2.0^20π/4\", \"negative argument\", \"Float64\", \"cos_kernel\")"]` | 40.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "cos", "(\"argument reduction (easy) abs(x) < 2.0^20π/4\", \"positive argument\", \"Float32\", \"cos_kernel\")"]` | 38.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "cos", "(\"argument reduction (easy) abs(x) < 2.0^20π/4\", \"positive argument\", \"Float64\", \"cos_kernel\")"]` | 40.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "cos", "(\"argument reduction (easy) abs(x) < 2π/4\", \"negative argument\", \"Float32\", \"sin_kernel\")"]` | 38.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "cos", "(\"argument reduction (easy) abs(x) < 2π/4\", \"negative argument\", \"Float64\", \"sin_kernel\")"]` | 38.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "cos", "(\"argument reduction (easy) abs(x) < 2π/4\", \"positive argument\", \"Float32\", \"sin_kernel\")"]` | 38.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "cos", "(\"argument reduction (easy) abs(x) < 2π/4\", \"positive argument\", \"Float64\", \"sin_kernel\")"]` | 38.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "cos", "(\"argument reduction (easy) abs(x) < 3π/4\", \"negative argument\", \"Float32\", \"sin_kernel\")"]` | 38.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "cos", "(\"argument reduction (easy) abs(x) < 3π/4\", \"negative argument\", \"Float64\", \"sin_kernel\")"]` | 38.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "cos", "(\"argument reduction (easy) abs(x) < 3π/4\", \"positive argument\", \"Float32\", \"sin_kernel\")"]` | 38.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "cos", "(\"argument reduction (easy) abs(x) < 3π/4\", \"positive argument\", \"Float64\", \"sin_kernel\")"]` | 38.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "cos", "(\"argument reduction (easy) abs(x) < 4π/4\", \"negative argument\", \"Float32\", \"cos_kernel\")"]` | 36.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "cos", "(\"argument reduction (easy) abs(x) < 4π/4\", \"negative argument\", \"Float64\", \"cos_kernel\")"]` | 36.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "cos", "(\"argument reduction (easy) abs(x) < 4π/4\", \"positive argument\", \"Float32\", \"cos_kernel\")"]` | 32.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "cos", "(\"argument reduction (easy) abs(x) < 4π/4\", \"positive argument\", \"Float64\", \"cos_kernel\")"]` | 36.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "cos", "(\"argument reduction (easy) abs(x) < 5π/4\", \"negative argument\", \"Float32\", \"cos_kernel\")"]` | 36.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "cos", "(\"argument reduction (easy) abs(x) < 5π/4\", \"negative argument\", \"Float64\", \"cos_kernel\")"]` | 36.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "cos", "(\"argument reduction (easy) abs(x) < 5π/4\", \"positive argument\", \"Float32\", \"cos_kernel\")"]` | 37.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "cos", "(\"argument reduction (easy) abs(x) < 5π/4\", \"positive argument\", \"Float64\", \"cos_kernel\")"]` | 36.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "cos", "(\"argument reduction (easy) abs(x) < 6π/4\", \"negative argument\", \"Float32\", \"sin_kernel\")"]` | 38.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "cos", "(\"argument reduction (easy) abs(x) < 6π/4\", \"negative argument\", \"Float64\", \"sin_kernel\")"]` | 38.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "cos", "(\"argument reduction (easy) abs(x) < 6π/4\", \"positive argument\", \"Float32\", \"sin_kernel\")"]` | 38.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "cos", "(\"argument reduction (easy) abs(x) < 6π/4\", \"positive argument\", \"Float64\", \"sin_kernel\")"]` | 38.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "cos", "(\"argument reduction (easy) abs(x) < 7π/4\", \"negative argument\", \"Float32\", \"cos_kernel\")"]` | 38.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "cos", "(\"argument reduction (easy) abs(x) < 7π/4\", \"negative argument\", \"Float64\", \"cos_kernel\")"]` | 38.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "cos", "(\"argument reduction (easy) abs(x) < 7π/4\", \"positive argument\", \"Float32\", \"cos_kernel\")"]` | 39.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "cos", "(\"argument reduction (easy) abs(x) < 7π/4\", \"positive argument\", \"Float64\", \"cos_kernel\")"]` | 38.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "cos", "(\"argument reduction (easy) abs(x) < 8π/4\", \"negative argument\", \"Float32\", \"cos_kernel\")"]` | 36.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "cos", "(\"argument reduction (easy) abs(x) < 8π/4\", \"negative argument\", \"Float64\", \"cos_kernel\")"]` | 36.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "cos", "(\"argument reduction (easy) abs(x) < 8π/4\", \"positive argument\", \"Float32\", \"cos_kernel\")"]` | 36.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "cos", "(\"argument reduction (easy) abs(x) < 8π/4\", \"positive argument\", \"Float64\", \"cos_kernel\")"]` | 36.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "cos", "(\"argument reduction (easy) abs(x) < 9π/4\", \"negative argument\", \"Float32\", \"cos_kernel\")"]` | 36.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "cos", "(\"argument reduction (easy) abs(x) < 9π/4\", \"negative argument\", \"Float64\", \"cos_kernel\")"]` | 36.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "cos", "(\"argument reduction (easy) abs(x) < 9π/4\", \"positive argument\", \"Float32\", \"cos_kernel\")"]` | 36.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "cos", "(\"argument reduction (easy) abs(x) < 9π/4\", \"positive argument\", \"Float64\", \"cos_kernel\")"]` | 36.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "cos", "(\"argument reduction (hard) abs(x) < 2π/4\", \"negative argument\", \"Float32\", \"sin_kernel\")"]` | 47.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "cos", "(\"argument reduction (hard) abs(x) < 2π/4\", \"negative argument\", \"Float64\", \"sin_kernel\")"]` | 47.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "cos", "(\"argument reduction (hard) abs(x) < 2π/4\", \"positive argument\", \"Float32\", \"sin_kernel\")"]` | 47.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "cos", "(\"argument reduction (hard) abs(x) < 2π/4\", \"positive argument\", \"Float64\", \"sin_kernel\")"]` | 48.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "cos", "(\"argument reduction (hard) abs(x) < 4π/4\", \"negative argument\", \"Float32\", \"cos_kernel\")"]` | 32.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "cos", "(\"argument reduction (hard) abs(x) < 4π/4\", \"negative argument\", \"Float64\", \"cos_kernel\")"]` | 45.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "cos", "(\"argument reduction (hard) abs(x) < 4π/4\", \"positive argument\", \"Float32\", \"cos_kernel\")"]` | 46.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "cos", "(\"argument reduction (hard) abs(x) < 4π/4\", \"positive argument\", \"Float64\", \"cos_kernel\")"]` | 45.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "cos", "(\"argument reduction (hard) abs(x) < 6π/4\", \"negative argument\", \"Float32\", \"sin_kernel\")"]` | 48.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "cos", "(\"argument reduction (hard) abs(x) < 6π/4\", \"negative argument\", \"Float64\", \"sin_kernel\")"]` | 48.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "cos", "(\"argument reduction (hard) abs(x) < 6π/4\", \"positive argument\", \"Float32\", \"sin_kernel\")"]` | 48.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "cos", "(\"argument reduction (hard) abs(x) < 6π/4\", \"positive argument\", \"Float64\", \"sin_kernel\")"]` | 48.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "cos", "(\"argument reduction (hard) abs(x) < 8π/4\", \"negative argument\", \"Float32\", \"cos_kernel\")"]` | 45.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "cos", "(\"argument reduction (hard) abs(x) < 8π/4\", \"negative argument\", \"Float64\", \"cos_kernel\")"]` | 46.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "cos", "(\"argument reduction (hard) abs(x) < 8π/4\", \"positive argument\", \"Float32\", \"cos_kernel\")"]` | 46.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "cos", "(\"argument reduction (hard) abs(x) < 8π/4\", \"positive argument\", \"Float64\", \"cos_kernel\")"]` | 46.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "cos", "(\"argument reduction (paynehanek) abs(x) > 2.0^20*π/2\", \"negative argument\", \"Float32\", \"cos_kernel\")"]` | 62.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "cos", "(\"argument reduction (paynehanek) abs(x) > 2.0^20*π/2\", \"negative argument\", \"Float32\", \"sin_kernel\")"]` | 59.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "cos", "(\"argument reduction (paynehanek) abs(x) > 2.0^20*π/2\", \"negative argument\", \"Float64\", \"cos_kernel\")"]` | 60.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "cos", "(\"argument reduction (paynehanek) abs(x) > 2.0^20*π/2\", \"negative argument\", \"Float64\", \"sin_kernel\")"]` | 65.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "cos", "(\"argument reduction (paynehanek) abs(x) > 2.0^20*π/2\", \"positive argument\", \"Float32\", \"cos_kernel\")"]` | 58.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "cos", "(\"argument reduction (paynehanek) abs(x) > 2.0^20*π/2\", \"positive argument\", \"Float32\", \"sin_kernel\")"]` | 59.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "cos", "(\"argument reduction (paynehanek) abs(x) > 2.0^20*π/2\", \"positive argument\", \"Float64\", \"cos_kernel\")"]` | 59.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "cos", "(\"argument reduction (paynehanek) abs(x) > 2.0^20*π/2\", \"positive argument\", \"Float64\", \"sin_kernel\")"]` | 61.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "cos", "(\"no reduction\", \"negative argument\", \"Float32\", \"cos_kernel\")"]` | 31.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "cos", "(\"no reduction\", \"negative argument\", \"Float64\", \"cos_kernel\")"]` | 31.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "cos", "(\"no reduction\", \"positive argument\", \"Float32\", \"cos_kernel\")"]` | 31.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "cos", "(\"no reduction\", \"positive argument\", \"Float64\", \"cos_kernel\")"]` | 30.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "cos", "(\"no reduction\", \"zero\", \"Float32\")"]` | 25.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "cos", "(\"no reduction\", \"zero\", \"Float64\")"]` | 25.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "cosh", "(\"0 <= abs(x) < 0.00024414062f0\", \"negative argument\", \"Float32\")"]` | 23.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "cosh", "(\"0 <= abs(x) < 0.00024414062f0\", \"positive argument\", \"Float32\")"]` | 23.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "cosh", "(\"0 <= abs(x) < 2.7755602085408512e-17\", \"negative argument\", \"Float64\")"]` | 23.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "cosh", "(\"0 <= abs(x) < 2.7755602085408512e-17\", \"positive argument\", \"Float64\")"]` | 23.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "cosh", "(\"0.00024414062f0 <= abs(x) < 9f0\", \"negative argument\", \"Float32\")"]` | 23.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "cosh", "(\"0.00024414062f0 <= abs(x) < 9f0\", \"positive argument\", \"Float32\")"]` | 23.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "cosh", "(\"2.7755602085408512e-17 <= abs(x) < 22.0\", \"negative argument\", \"Float64\")"]` | 23.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "cosh", "(\"2.7755602085408512e-17 <= abs(x) < 22.0\", \"positive argument\", \"Float64\")"]` | 23.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "cosh", "(\"22.0 <= abs(x) < 709.7822265633563\", \"negative argument\", \"Float64\")"]` | 23.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "cosh", "(\"22.0 <= abs(x) < 709.7822265633563\", \"positive argument\", \"Float64\")"]` | 23.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "cosh", "(\"9f0 <= abs(x) < 88.72283f0\", \"negative argument\", \"Float32\")"]` | 23.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "cosh", "(\"9f0 <= abs(x) < 88.72283f0\", \"positive argument\", \"Float32\")"]` | 23.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "cosh", "(\"very large\", \"negative argument\", \"Float32\")"]` | 23.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "cosh", "(\"very large\", \"negative argument\", \"Float64\")"]` | 23.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "cosh", "(\"very large\", \"positive argument\", \"Float32\")"]` | 23.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "cosh", "(\"very large\", \"positive argument\", \"Float64\")"]` | 23.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "cosh", "(\"very small\", \"negative argument\", \"Float32\")"]` | 23.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "cosh", "(\"very small\", \"negative argument\", \"Float64\")"]` | 23.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "cosh", "(\"very small\", \"positive argument\", \"Float32\")"]` | 23.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "cosh", "(\"very small\", \"positive argument\", \"Float64\")"]` | 23.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "cosh", "(\"zero\", \"Float32\")"]` | 23.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "cosh", "(\"zero\", \"Float64\")"]` | 23.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "exp2", "(\"2pow1023\", \"negative argument\", Float64)"]` | 23.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "exp2", "(\"2pow1023\", \"positive argument\", Float64)"]` | 23.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "exp2", "(\"2pow127\", \"negative argument\", Float32)"]` | 23.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "exp2", "(\"2pow127\", \"positive argument\", Float32)"]` | 23.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "exp2", "(\"2pow35\", \"negative argument\", \"Float32\")"]` | 23.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "exp2", "(\"2pow35\", \"negative argument\", \"Float64\")"]` | 23.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "exp2", "(\"2pow35\", \"positive argument\", \"Float32\")"]` | 23.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "exp2", "(\"2pow35\", \"positive argument\", \"Float64\")"]` | 23.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "exp2", "(\"2pow3\", \"negative argument\", \"Float32\")"]` | 23.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "exp2", "(\"2pow3\", \"negative argument\", \"Float64\")"]` | 23.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "exp2", "(\"2pow3\", \"positive argument\", \"Float32\")"]` | 23.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "exp2", "(\"2pow3\", \"positive argument\", \"Float64\")"]` | 23.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "exp2", "(\"one\", \"Float32\")"]` | 23.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "exp2", "(\"one\", \"Float64\")"]` | 23.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "exp2", "(\"small\", \"negative argument\", \"Float32\")"]` | 23.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "exp2", "(\"small\", \"negative argument\", \"Float64\")"]` | 23.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "exp2", "(\"small\", \"positive argument\", \"Float32\")"]` | 23.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "exp2", "(\"small\", \"positive argument\", \"Float64\")"]` | 23.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "exp2", "(\"very small\", \"negative argument\", \"Float32\")"]` | 23.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "exp2", "(\"very small\", \"negative argument\", \"Float64\")"]` | 23.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "exp2", "(\"very small\", \"positive argument\", \"Float32\")"]` | 23.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "exp2", "(\"very small\", \"positive argument\", \"Float64\")"]` | 23.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "exp2", "(\"zero\", \"Float32\")"]` | 23.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "exp2", "(\"zero\", \"Float64\")"]` | 23.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "expm1", "(\"arg reduction II\", \"negative argument\", \"Float32\")"]` | 48.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "expm1", "(\"arg reduction II\", \"negative argument\", \"Float64\")"]` | 56.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "expm1", "(\"arg reduction II\", \"positive argument\", \"Float32\")"]` | 49.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "expm1", "(\"arg reduction II\", \"positive argument\", \"Float64\")"]` | 56.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "expm1", "(\"arg reduction I\", \"negative argument\", \"Float32\")"]` | 48.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "expm1", "(\"arg reduction I\", \"negative argument\", \"Float64\")"]` | 56.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "expm1", "(\"arg reduction I\", \"positive argument\", \"Float32\")"]` | 49.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "expm1", "(\"arg reduction I\", \"positive argument\", \"Float64\")"]` | 56.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "expm1", "(\"huge\", \"positive argument\", \"Float3\")"]` | 26.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "expm1", "(\"huge\", \"positive argument\", \"Float64\")"]` | 26.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "expm1", "(\"large\", \"negative argument\", \"Float32\")"]` | 26.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "expm1", "(\"large\", \"negative argument\", \"Float64\")"]` | 26.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "expm1", "(\"large\", \"positive argument\", \"Float32\")"]` | 26.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "expm1", "(\"large\", \"positive argument\", \"Float64\")"]` | 26.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "expm1", "(\"medium\", \"negative argument\", \"Float32\")"]` | 26.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "expm1", "(\"medium\", \"negative argument\", \"Float64\")"]` | 26.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "expm1", "(\"medium\", \"positive argument\", \"Float32\")"]` | 26.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "expm1", "(\"medium\", \"positive argument\", \"Float64\")"]` | 65.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "expm1", "(\"one\", \"Float32\")"]` | 48.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "expm1", "(\"one\", \"Float64\")"]` | 57.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "expm1", "(\"small\", \"negative argument\", \"Float32\")"]` | 41.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "expm1", "(\"small\", \"negative argument\", \"Float64\")"]` | 48.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "expm1", "(\"small\", \"positive argument\", \"Float32\")"]` | 40.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "expm1", "(\"small\", \"positive argument\", \"Float64\")"]` | 50.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "expm1", "(\"very small\", \"negative argument\", \"Float32\")"]` | 25.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "expm1", "(\"very small\", \"negative argument\", \"Float64\")"]` | 26.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "expm1", "(\"very small\", \"positive argument\", \"Float32\")"]` | 25.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "expm1", "(\"very small\", \"positive argument\", \"Float64\")"]` | 26.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "expm1", "(\"zero\", \"Float32\")"]` | 25.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "expm1", "(\"zero\", \"Float64\")"]` | 26.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "fastmath", "(\"add\", \"BigFloat\")"]` | 71.000 ns (40%) | 0.000 ns | 112 bytes (1%) | 2 |
| `["scalar", "fastmath", "(\"add\", \"BigInt\")"]` | 56.000 ns (40%) | 0.000 ns | 48 bytes (1%) | 2 |
| `["scalar", "fastmath", "(\"add\", \"ComplexF32\")"]` | 23.000 ns (40%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "fastmath", "(\"add\", \"ComplexF64\")"]` | 23.000 ns (40%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "fastmath", "(\"add\", \"Complex{BigFloat}\")"]` | 99.000 ns (40%) | 0.000 ns | 224 bytes (1%) | 4 |
| `["scalar", "fastmath", "(\"add\", \"Complex{BigInt}\")"]` | 79.000 ns (40%) | 0.000 ns | 88 bytes (1%) | 4 |
| `["scalar", "fastmath", "(\"add\", \"Complex{Int64}\")"]` | 23.000 ns (40%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "fastmath", "(\"add\", \"Complex{UInt64}\")"]` | 23.000 ns (40%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "fastmath", "(\"add\", \"Float32\")"]` | 23.000 ns (40%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "fastmath", "(\"add\", \"Float64\")"]` | 23.000 ns (40%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "fastmath", "(\"add\", \"Int64\")"]` | 23.000 ns (40%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "fastmath", "(\"add\", \"UInt64\")"]` | 23.000 ns (40%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "fastmath", "(\"div\", \"BigFloat\")"]` | 282.000 ns (40%) | 0.000 ns | 112 bytes (1%) | 2 |
| `["scalar", "fastmath", "(\"div\", \"BigInt\")"]` | 395.000 ns (40%) | 0.000 ns | 336 bytes (1%) | 6 |
| `["scalar", "fastmath", "(\"div\", \"ComplexF32\")"]` | 23.000 ns (40%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "fastmath", "(\"div\", \"ComplexF64\")"]` | 23.000 ns (40%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "fastmath", "(\"div\", \"Complex{BigFloat}\")"]` | 573.000 ns (40%) | 0.000 ns | 1.20 KiB (1%) | 22 |
| `["scalar", "fastmath", "(\"div\", \"Complex{BigInt}\")"]` | 690.000 ns (40%) | 0.000 ns | 1.20 KiB (1%) | 22 |
| `["scalar", "fastmath", "(\"div\", \"Complex{Int64}\")"]` | 23.000 ns (40%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "fastmath", "(\"div\", \"Complex{UInt64}\")"]` | 23.000 ns (40%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "fastmath", "(\"div\", \"Float32\")"]` | 23.000 ns (40%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "fastmath", "(\"div\", \"Float64\")"]` | 23.000 ns (40%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "fastmath", "(\"div\", \"Int64\")"]` | 23.000 ns (40%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "fastmath", "(\"div\", \"UInt64\")"]` | 23.000 ns (40%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "fastmath", "(\"mul\", \"BigFloat\")"]` | 101.000 ns (40%) | 0.000 ns | 112 bytes (1%) | 2 |
| `["scalar", "fastmath", "(\"mul\", \"BigInt\")"]` | 82.000 ns (40%) | 0.000 ns | 48 bytes (1%) | 3 |
| `["scalar", "fastmath", "(\"mul\", \"ComplexF32\")"]` | 23.000 ns (40%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "fastmath", "(\"mul\", \"ComplexF64\")"]` | 23.000 ns (40%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "fastmath", "(\"mul\", \"Complex{BigFloat}\")"]` | 243.000 ns (40%) | 0.000 ns | 672 bytes (1%) | 12 |
| `["scalar", "fastmath", "(\"mul\", \"Complex{BigInt}\")"]` | 225.000 ns (40%) | 0.000 ns | 256 bytes (1%) | 13 |
| `["scalar", "fastmath", "(\"mul\", \"Complex{Int64}\")"]` | 23.000 ns (40%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "fastmath", "(\"mul\", \"Complex{UInt64}\")"]` | 23.000 ns (40%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "fastmath", "(\"mul\", \"Float32\")"]` | 23.000 ns (40%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "fastmath", "(\"mul\", \"Float64\")"]` | 23.000 ns (40%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "fastmath", "(\"mul\", \"Int64\")"]` | 23.000 ns (40%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "fastmath", "(\"mul\", \"UInt64\")"]` | 23.000 ns (40%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "fastmath", "(\"sub\", \"BigFloat\")"]` | 56.000 ns (40%) | 0.000 ns | 112 bytes (1%) | 2 |
| `["scalar", "fastmath", "(\"sub\", \"BigInt\")"]` | 57.000 ns (40%) | 0.000 ns | 48 bytes (1%) | 2 |
| `["scalar", "fastmath", "(\"sub\", \"ComplexF32\")"]` | 23.000 ns (40%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "fastmath", "(\"sub\", \"ComplexF64\")"]` | 23.000 ns (40%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "fastmath", "(\"sub\", \"Complex{BigFloat}\")"]` | 84.000 ns (40%) | 0.000 ns | 224 bytes (1%) | 4 |
| `["scalar", "fastmath", "(\"sub\", \"Complex{BigInt}\")"]` | 82.000 ns (40%) | 0.000 ns | 88 bytes (1%) | 4 |
| `["scalar", "fastmath", "(\"sub\", \"Complex{Int64}\")"]` | 23.000 ns (40%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "fastmath", "(\"sub\", \"Complex{UInt64}\")"]` | 23.000 ns (40%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "fastmath", "(\"sub\", \"Float32\")"]` | 23.000 ns (40%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "fastmath", "(\"sub\", \"Float64\")"]` | 23.000 ns (40%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "fastmath", "(\"sub\", \"Int64\")"]` | 23.000 ns (40%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "fastmath", "(\"sub\", \"UInt64\")"]` | 23.000 ns (40%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "fastmath", "13786"]` | 11.949 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "floatexp", "(\"exp10\", \"agument reduction, k = 2\", \"Float32\")"]` | 23.000 ns (40%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "floatexp", "(\"exp10\", \"agument reduction, k = 2\", \"Float64\")"]` | 23.000 ns (40%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "floatexp", "(\"exp10\", \"agument reduction, k = 83\", \"Float32\")"]` | 23.000 ns (40%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "floatexp", "(\"exp10\", \"agument reduction, k = 83\", \"Float64\")"]` | 23.000 ns (40%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "floatexp", "(\"exp10\", \"direct approx, k = 0\", \"Float32\")"]` | 23.000 ns (40%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "floatexp", "(\"exp10\", \"direct approx, k = 0\", \"Float64\")"]` | 23.000 ns (40%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "floatexp", "(\"exp10\", \"no agument reduction, k = 1\", \"Float32\")"]` | 23.000 ns (40%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "floatexp", "(\"exp10\", \"no agument reduction, k = 1\", \"Float64\")"]` | 23.000 ns (40%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "floatexp", "(\"exp10\", \"normal path -> small, k = -1075\", \"Float64\")"]` | 77.000 ns (40%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "floatexp", "(\"exp10\", \"normal path -> small, k = -150\", \"Float32\")"]` | 23.000 ns (40%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "floatexp", "(\"exp10\", \"overflow\", \"Float32\")"]` | 23.000 ns (40%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "floatexp", "(\"exp10\", \"overflow\", \"Float64\")"]` | 23.000 ns (40%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "floatexp", "(\"exp10\", \"taylor expansion\", \"Float32\")"]` | 23.000 ns (40%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "floatexp", "(\"exp10\", \"underflow\", \"Float32\")"]` | 23.000 ns (40%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "floatexp", "(\"exp10\", \"underflow\", \"Float64\")"]` | 23.000 ns (40%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "floatexp", "(\"exp\", \"fast path, k = 1\", \"Float32\")"]` | 23.000 ns (40%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "floatexp", "(\"exp\", \"fast path, k = 1\", \"Float64\")"]` | 23.000 ns (40%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "floatexp", "(\"exp\", \"no agument reduction, k = 9\", \"Float32\")"]` | 23.000 ns (40%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "floatexp", "(\"exp\", \"no agument reduction, k = 9\", \"Float64\")"]` | 23.000 ns (40%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "floatexp", "(\"exp\", \"normal path -> small, k = -1045\", \"Float32\")"]` | 23.000 ns (40%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "floatexp", "(\"exp\", \"normal path -> small, k = -1045\", \"Float64\")"]` | 78.000 ns (40%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "floatexp", "(\"exp\", \"normal path, k = 2\", \"Float32\")"]` | 23.000 ns (40%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "floatexp", "(\"exp\", \"normal path, k = 2\", \"Float64\")"]` | 23.000 ns (40%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "floatexp", "(\"exp\", \"overflow\", \"Float32\")"]` | 23.000 ns (40%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "floatexp", "(\"exp\", \"overflow\", \"Float64\")"]` | 23.000 ns (40%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "floatexp", "(\"exp\", \"small argument path\", \"Float32\")"]` | 23.000 ns (40%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "floatexp", "(\"exp\", \"small argument path\", \"Float64\")"]` | 23.000 ns (40%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "floatexp", "(\"exp\", \"underflow\", \"Float32\")"]` | 23.000 ns (40%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "floatexp", "(\"exp\", \"underflow\", \"Float64\")"]` | 23.000 ns (40%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "floatexp", "(\"exponent\", \"norm\", \"Float32\")"]` | 23.000 ns (40%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "floatexp", "(\"exponent\", \"norm\", \"Float64\")"]` | 23.000 ns (40%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "floatexp", "(\"exponent\", \"subnorm\", \"Float32\")"]` | 23.000 ns (40%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "floatexp", "(\"exponent\", \"subnorm\", \"Float64\")"]` | 23.000 ns (40%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "floatexp", "(\"frexp\", \"inf\", \"Float32\")"]` | 23.000 ns (40%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "floatexp", "(\"frexp\", \"inf\", \"Float64\")"]` | 23.000 ns (40%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "floatexp", "(\"frexp\", \"norm\", \"Float32\")"]` | 23.000 ns (40%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "floatexp", "(\"frexp\", \"norm\", \"Float64\")"]` | 23.000 ns (40%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "floatexp", "(\"frexp\", \"subnorm\", \"Float32\")"]` | 23.000 ns (40%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "floatexp", "(\"frexp\", \"subnorm\", \"Float64\")"]` | 23.000 ns (40%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "floatexp", "(\"ldexp\", \"inf -> inf\", \"Float32\")"]` | 23.000 ns (40%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "floatexp", "(\"ldexp\", \"inf -> inf\", \"Float64\")"]` | 23.000 ns (40%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "floatexp", "(\"ldexp\", \"norm -> inf\", \"Float32\")"]` | 23.000 ns (40%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "floatexp", "(\"ldexp\", \"norm -> inf\", \"Float64\")"]` | 23.000 ns (40%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "floatexp", "(\"ldexp\", \"norm -> norm\", \"Float32\")"]` | 23.000 ns (40%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "floatexp", "(\"ldexp\", \"norm -> norm\", \"Float64\")"]` | 23.000 ns (40%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "floatexp", "(\"ldexp\", \"norm -> subnorm\", \"Float32\")"]` | 70.000 ns (40%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "floatexp", "(\"ldexp\", \"norm -> subnorm\", \"Float64\")"]` | 69.000 ns (40%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "floatexp", "(\"ldexp\", \"subnorm -> norm\", \"Float32\")"]` | 23.000 ns (40%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "floatexp", "(\"ldexp\", \"subnorm -> norm\", \"Float64\")"]` | 23.000 ns (40%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "floatexp", "(\"ldexp\", \"subnorm -> subnorm\", \"Float32\")"]` | 71.000 ns (40%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "floatexp", "(\"ldexp\", \"subnorm -> subnorm\", \"Float64\")"]` | 70.000 ns (40%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "floatexp", "(\"significand\", \"norm\", \"Float32\")"]` | 23.000 ns (40%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "floatexp", "(\"significand\", \"norm\", \"Float64\")"]` | 23.000 ns (40%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "floatexp", "(\"significand\", \"subnorm\", \"Float32\")"]` | 23.000 ns (40%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "floatexp", "(\"significand\", \"subnorm\", \"Float64\")"]` | 23.000 ns (40%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "intfuncs", "(\"#778\", \"BigInt\", \"+\")"]` | 2.067 μs (40%) | 0.000 ns | 1.19 KiB (1%) | 30 |
| `["scalar", "intfuncs", "(\"#778\", \"Int64\", \"+\")"]` | 70.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "intfuncs", "(\"#778\", \"UInt64\", \"+\")"]` | 81.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "intfuncs", "(\"#779\", \"BigInt\", \"+\")"]` | 868.000 ns (40%) | 0.000 ns | 656 bytes (1%) | 18 |
| `["scalar", "intfuncs", "(\"#779\", \"Int64\", \"+\")"]` | 74.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "intfuncs", "(\"#779\", \"UInt64\", \"+\")"]` | 84.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "iteration", "in"]` | 2.377 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "iteration", "indexed"]` | 2.083 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "mod2pi", "(\"argument reduction (easy) abs(x) < 2.0^20π/4\", \"negative argument\", \"Float64\")"]` | 23.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "mod2pi", "(\"argument reduction (easy) abs(x) < 2.0^20π/4\", \"positive argument\", \"Float64\")"]` | 23.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "mod2pi", "(\"argument reduction (easy) abs(x) < 5π/4\", \"negative argument\", \"Float64\")"]` | 23.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "mod2pi", "(\"argument reduction (easy) abs(x) < 5π/4\", \"positive argument\", \"Float64\")"]` | 23.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "mod2pi", "(\"argument reduction (easy) abs(x) < 6π/4\", \"negative argument\", \"Float64\")"]` | 23.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "mod2pi", "(\"argument reduction (easy) abs(x) < 6π/4\", \"positive argument\", \"Float64\")"]` | 23.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "mod2pi", "(\"argument reduction (easy) abs(x) < 7π/4\", \"negative argument\", \"Float64\")"]` | 23.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "mod2pi", "(\"argument reduction (easy) abs(x) < 7π/4\", \"positive argument\", \"Float64\")"]` | 23.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "mod2pi", "(\"argument reduction (easy) abs(x) < 8π/4\", \"negative argument\", \"Float64\")"]` | 23.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "mod2pi", "(\"argument reduction (easy) abs(x) < 8π/4\", \"positive argument\", \"Float64\")"]` | 23.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "mod2pi", "(\"argument reduction (easy) abs(x) < 9π/4\", \"negative argument\", \"Float64\")"]` | 23.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "mod2pi", "(\"argument reduction (easy) abs(x) < 9π/4\", \"positive argument\", \"Float64\")"]` | 23.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "mod2pi", "(\"argument reduction (easy) abs(x) > 2.0^20*π/2\", \"negative argument\", \"Float64\")"]` | 60.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "mod2pi", "(\"argument reduction (easy) abs(x) > 2.0^20*π/2\", \"positive argument\", \"Float64\")"]` | 56.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "mod2pi", "(\"argument reduction (hard) abs(x) < 6π/4\", \"negative argument\", \"Float64\")"]` | 23.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "mod2pi", "(\"argument reduction (hard) abs(x) < 6π/4\", \"positive argument\", \"Float64\")"]` | 23.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "mod2pi", "(\"argument reduction (hard) abs(x) < 8π/4\", \"negative argument\", \"Float64\")"]` | 23.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "mod2pi", "(\"argument reduction (hard) abs(x) < 8π/4\", \"positive argument\", \"Float64\")"]` | 23.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "mod2pi", "(\"no reduction\", \"negative argument\", \"Float64\")"]` | 23.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "mod2pi", "(\"no reduction\", \"positive argument\", \"Float64\")"]` | 23.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "mod2pi", "(\"no reduction\", \"zero\", \"Float64\")"]` | 23.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "predicate", "(\"isequal\", \"BigFloat\")"]` | 49.000 ns (40%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "predicate", "(\"isequal\", \"BigInt\")"]` | 26.000 ns (40%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "predicate", "(\"isequal\", \"ComplexF32\")"]` | 23.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "predicate", "(\"isequal\", \"ComplexF64\")"]` | 23.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "predicate", "(\"isequal\", \"Complex{BigFloat}\")"]` | 61.000 ns (40%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "predicate", "(\"isequal\", \"Complex{BigInt}\")"]` | 29.000 ns (40%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "predicate", "(\"isequal\", \"Complex{Int64}\")"]` | 23.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "predicate", "(\"isequal\", \"Complex{UInt64}\")"]` | 23.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "predicate", "(\"isequal\", \"Float32\")"]` | 23.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "predicate", "(\"isequal\", \"Float64\")"]` | 23.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "predicate", "(\"isequal\", \"Int64\")"]` | 23.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "predicate", "(\"isequal\", \"UInt64\")"]` | 23.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "predicate", "(\"iseven\", \"BigInt\")"]` | 94.000 ns (40%) | 0.000 ns | 80 bytes (1%) | 4 |
| `["scalar", "predicate", "(\"iseven\", \"Int64\")"]` | 23.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "predicate", "(\"iseven\", \"UInt64\")"]` | 23.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "predicate", "(\"isfinite\", \"BigFloat\")"]` | 27.000 ns (40%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "predicate", "(\"isfinite\", \"BigInt\")"]` | 23.000 ns (40%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "predicate", "(\"isfinite\", \"ComplexF32\")"]` | 23.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "predicate", "(\"isfinite\", \"ComplexF64\")"]` | 23.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "predicate", "(\"isfinite\", \"Complex{BigFloat}\")"]` | 32.000 ns (40%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "predicate", "(\"isfinite\", \"Complex{BigInt}\")"]` | 23.000 ns (40%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "predicate", "(\"isfinite\", \"Complex{Int64}\")"]` | 23.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "predicate", "(\"isfinite\", \"Complex{UInt64}\")"]` | 23.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "predicate", "(\"isfinite\", \"Float32\")"]` | 23.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "predicate", "(\"isfinite\", \"Float64\")"]` | 23.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "predicate", "(\"isfinite\", \"Int64\")"]` | 23.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "predicate", "(\"isfinite\", \"UInt64\")"]` | 23.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "predicate", "(\"isinf\", \"BigFloat\")"]` | 24.000 ns (40%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "predicate", "(\"isinf\", \"BigInt\")"]` | 23.000 ns (40%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "predicate", "(\"isinf\", \"ComplexF32\")"]` | 23.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "predicate", "(\"isinf\", \"ComplexF64\")"]` | 23.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "predicate", "(\"isinf\", \"Complex{BigFloat}\")"]` | 26.000 ns (40%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "predicate", "(\"isinf\", \"Complex{BigInt}\")"]` | 23.000 ns (40%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "predicate", "(\"isinf\", \"Complex{Int64}\")"]` | 23.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "predicate", "(\"isinf\", \"Complex{UInt64}\")"]` | 23.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "predicate", "(\"isinf\", \"Float32\")"]` | 23.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "predicate", "(\"isinf\", \"Float64\")"]` | 23.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "predicate", "(\"isinf\", \"Int64\")"]` | 23.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "predicate", "(\"isinf\", \"UInt64\")"]` | 23.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "predicate", "(\"isinteger\", \"BigFloat\")"]` | 28.000 ns (40%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "predicate", "(\"isinteger\", \"BigInt\")"]` | 23.000 ns (40%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "predicate", "(\"isinteger\", \"ComplexF32\")"]` | 23.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "predicate", "(\"isinteger\", \"ComplexF64\")"]` | 23.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "predicate", "(\"isinteger\", \"Complex{BigFloat}\")"]` | 38.000 ns (40%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "predicate", "(\"isinteger\", \"Complex{BigInt}\")"]` | 24.000 ns (40%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "predicate", "(\"isinteger\", \"Complex{Int64}\")"]` | 23.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "predicate", "(\"isinteger\", \"Complex{UInt64}\")"]` | 23.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "predicate", "(\"isinteger\", \"Float32\")"]` | 23.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "predicate", "(\"isinteger\", \"Float64\")"]` | 23.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "predicate", "(\"isinteger\", \"Int64\")"]` | 23.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "predicate", "(\"isinteger\", \"UInt64\")"]` | 23.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "predicate", "(\"isless\", \"BigFloat\")"]` | 44.000 ns (40%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "predicate", "(\"isless\", \"BigInt\")"]` | 26.000 ns (40%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "predicate", "(\"isless\", \"Float32\")"]` | 23.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "predicate", "(\"isless\", \"Float64\")"]` | 23.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "predicate", "(\"isless\", \"Int64\")"]` | 23.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "predicate", "(\"isless\", \"UInt64\")"]` | 23.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "predicate", "(\"isnan\", \"BigFloat\")"]` | 24.000 ns (40%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "predicate", "(\"isnan\", \"BigInt\")"]` | 23.000 ns (40%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "predicate", "(\"isnan\", \"ComplexF32\")"]` | 23.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "predicate", "(\"isnan\", \"ComplexF64\")"]` | 23.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "predicate", "(\"isnan\", \"Complex{BigFloat}\")"]` | 26.000 ns (40%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "predicate", "(\"isnan\", \"Complex{BigInt}\")"]` | 23.000 ns (40%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "predicate", "(\"isnan\", \"Complex{Int64}\")"]` | 23.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "predicate", "(\"isnan\", \"Complex{UInt64}\")"]` | 23.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "predicate", "(\"isnan\", \"Float32\")"]` | 23.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "predicate", "(\"isnan\", \"Float64\")"]` | 23.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "predicate", "(\"isnan\", \"Int64\")"]` | 23.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "predicate", "(\"isnan\", \"UInt64\")"]` | 23.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "predicate", "(\"isodd\", \"BigInt\")"]` | 26.000 ns (40%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "predicate", "(\"isodd\", \"Int64\")"]` | 23.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "predicate", "(\"isodd\", \"UInt64\")"]` | 23.000 ns (25%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "rem_pio2", "(\"argument reduction (easy) abs(x) < 2.0^20π/4\", \"negative argument\", \"Float64\")"]` | 23.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "rem_pio2", "(\"argument reduction (easy) abs(x) < 2.0^20π/4\", \"positive argument\", \"Float64\")"]` | 23.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "rem_pio2", "(\"argument reduction (easy) abs(x) < 2π/4\", \"negative argument\", \"Float64\")"]` | 23.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "rem_pio2", "(\"argument reduction (easy) abs(x) < 2π/4\", \"positive argument\", \"Float64\")"]` | 23.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "rem_pio2", "(\"argument reduction (easy) abs(x) < 3π/4\", \"negative argument\", \"Float64\")"]` | 23.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "rem_pio2", "(\"argument reduction (easy) abs(x) < 3π/4\", \"positive argument\", \"Float64\")"]` | 23.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "rem_pio2", "(\"argument reduction (easy) abs(x) < 4π/4\", \"negative argument\", \"Float64\")"]` | 23.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "rem_pio2", "(\"argument reduction (easy) abs(x) < 4π/4\", \"positive argument\", \"Float64\")"]` | 23.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "rem_pio2", "(\"argument reduction (easy) abs(x) < 5π/4\", \"negative argument\", \"Float64\")"]` | 23.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "rem_pio2", "(\"argument reduction (easy) abs(x) < 5π/4\", \"positive argument\", \"Float64\")"]` | 23.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "rem_pio2", "(\"argument reduction (easy) abs(x) < 6π/4\", \"negative argument\", \"Float64\")"]` | 23.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "rem_pio2", "(\"argument reduction (easy) abs(x) < 6π/4\", \"positive argument\", \"Float64\")"]` | 23.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "rem_pio2", "(\"argument reduction (easy) abs(x) < 7π/4\", \"negative argument\", \"Float64\")"]` | 23.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "rem_pio2", "(\"argument reduction (easy) abs(x) < 7π/4\", \"positive argument\", \"Float64\")"]` | 23.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "rem_pio2", "(\"argument reduction (easy) abs(x) < 8π/4\", \"negative argument\", \"Float64\")"]` | 23.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "rem_pio2", "(\"argument reduction (easy) abs(x) < 8π/4\", \"positive argument\", \"Float64\")"]` | 23.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "rem_pio2", "(\"argument reduction (easy) abs(x) < 9π/4\", \"negative argument\", \"Float64\")"]` | 23.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "rem_pio2", "(\"argument reduction (easy) abs(x) < 9π/4\", \"positive argument\", \"Float64\")"]` | 23.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "rem_pio2", "(\"argument reduction (hard) abs(x) < 2π/4\", \"negative argument\", \"Float64\")"]` | 23.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "rem_pio2", "(\"argument reduction (hard) abs(x) < 2π/4\", \"positive argument\", \"Float64\")"]` | 23.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "rem_pio2", "(\"argument reduction (hard) abs(x) < 4π/4\", \"negative argument\", \"Float64\")"]` | 23.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "rem_pio2", "(\"argument reduction (hard) abs(x) < 4π/4\", \"positive argument\", \"Float64\")"]` | 23.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "rem_pio2", "(\"argument reduction (hard) abs(x) < 6π/4\", \"negative argument\", \"Float64\")"]` | 23.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "rem_pio2", "(\"argument reduction (hard) abs(x) < 6π/4\", \"positive argument\", \"Float64\")"]` | 23.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "rem_pio2", "(\"argument reduction (hard) abs(x) < 8π/4\", \"negative argument\", \"Float64\")"]` | 23.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "rem_pio2", "(\"argument reduction (hard) abs(x) < 8π/4\", \"positive argument\", \"Float64\")"]` | 23.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "rem_pio2", "(\"argument reduction (paynehanek) abs(x) > 2.0^20*π/2\", \"negative argument\", \"Float64\")"]` | 52.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "rem_pio2", "(\"argument reduction (paynehanek) abs(x) > 2.0^20*π/2\", \"positive argument\", \"Float64\")"]` | 52.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "sin", "(\"argument reduction (easy) abs(x) < 2.0^20π/4\", \"negative argument\", \"Float32\", \"sin_kernel\")"]` | 38.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "sin", "(\"argument reduction (easy) abs(x) < 2.0^20π/4\", \"negative argument\", \"Float64\", \"sin_kernel\")"]` | 41.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "sin", "(\"argument reduction (easy) abs(x) < 2.0^20π/4\", \"positive argument\", \"Float32\", \"sin_kernel\")"]` | 38.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "sin", "(\"argument reduction (easy) abs(x) < 2.0^20π/4\", \"positive argument\", \"Float64\", \"sin_kernel\")"]` | 42.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "sin", "(\"argument reduction (easy) abs(x) < 2π/4\", \"negative argument\", \"Float32\", \"cos_kernel\")"]` | 32.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "sin", "(\"argument reduction (easy) abs(x) < 2π/4\", \"negative argument\", \"Float64\", \"cos_kernel\")"]` | 36.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "sin", "(\"argument reduction (easy) abs(x) < 2π/4\", \"positive argument\", \"Float32\", \"cos_kernel\")"]` | 32.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "sin", "(\"argument reduction (easy) abs(x) < 2π/4\", \"positive argument\", \"Float64\", \"cos_kernel\")"]` | 36.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "sin", "(\"argument reduction (easy) abs(x) < 3π/4\", \"negative argument\", \"Float32\", \"cos_kernel\")"]` | 32.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "sin", "(\"argument reduction (easy) abs(x) < 3π/4\", \"negative argument\", \"Float64\", \"cos_kernel\")"]` | 36.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "sin", "(\"argument reduction (easy) abs(x) < 3π/4\", \"positive argument\", \"Float32\", \"cos_kernel\")"]` | 32.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "sin", "(\"argument reduction (easy) abs(x) < 3π/4\", \"positive argument\", \"Float64\", \"cos_kernel\")"]` | 36.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "sin", "(\"argument reduction (easy) abs(x) < 4π/4\", \"negative argument\", \"Float32\", \"sin_kernel\")"]` | 32.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "sin", "(\"argument reduction (easy) abs(x) < 4π/4\", \"negative argument\", \"Float64\", \"sin_kernel\")"]` | 38.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "sin", "(\"argument reduction (easy) abs(x) < 4π/4\", \"positive argument\", \"Float32\", \"sin_kernel\")"]` | 32.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "sin", "(\"argument reduction (easy) abs(x) < 4π/4\", \"positive argument\", \"Float64\", \"sin_kernel\")"]` | 39.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "sin", "(\"argument reduction (easy) abs(x) < 5π/4\", \"negative argument\", \"Float32\", \"sin_kernel\")"]` | 32.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "sin", "(\"argument reduction (easy) abs(x) < 5π/4\", \"negative argument\", \"Float64\", \"sin_kernel\")"]` | 38.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "sin", "(\"argument reduction (easy) abs(x) < 5π/4\", \"positive argument\", \"Float32\", \"sin_kernel\")"]` | 32.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "sin", "(\"argument reduction (easy) abs(x) < 5π/4\", \"positive argument\", \"Float64\", \"sin_kernel\")"]` | 38.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "sin", "(\"argument reduction (easy) abs(x) < 6π/4\", \"negative argument\", \"Float32\", \"cos_kernel\")"]` | 32.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "sin", "(\"argument reduction (easy) abs(x) < 6π/4\", \"negative argument\", \"Float64\", \"cos_kernel\")"]` | 36.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "sin", "(\"argument reduction (easy) abs(x) < 6π/4\", \"positive argument\", \"Float32\", \"cos_kernel\")"]` | 31.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "sin", "(\"argument reduction (easy) abs(x) < 6π/4\", \"positive argument\", \"Float64\", \"cos_kernel\")"]` | 36.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "sin", "(\"argument reduction (easy) abs(x) < 7π/4\", \"negative argument\", \"Float32\", \"sin_kernel\")"]` | 32.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "sin", "(\"argument reduction (easy) abs(x) < 7π/4\", \"negative argument\", \"Float64\", \"sin_kernel\")"]` | 36.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "sin", "(\"argument reduction (easy) abs(x) < 7π/4\", \"positive argument\", \"Float32\", \"sin_kernel\")"]` | 32.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "sin", "(\"argument reduction (easy) abs(x) < 7π/4\", \"positive argument\", \"Float64\", \"sin_kernel\")"]` | 36.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "sin", "(\"argument reduction (easy) abs(x) < 8π/4\", \"negative argument\", \"Float32\", \"sin_kernel\")"]` | 32.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "sin", "(\"argument reduction (easy) abs(x) < 8π/4\", \"negative argument\", \"Float64\", \"sin_kernel\")"]` | 38.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "sin", "(\"argument reduction (easy) abs(x) < 8π/4\", \"positive argument\", \"Float32\", \"sin_kernel\")"]` | 32.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "sin", "(\"argument reduction (easy) abs(x) < 8π/4\", \"positive argument\", \"Float64\", \"sin_kernel\")"]` | 38.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "sin", "(\"argument reduction (easy) abs(x) < 9π/4\", \"negative argument\", \"Float32\", \"sin_kernel\")"]` | 32.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "sin", "(\"argument reduction (easy) abs(x) < 9π/4\", \"negative argument\", \"Float64\", \"sin_kernel\")"]` | 38.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "sin", "(\"argument reduction (easy) abs(x) < 9π/4\", \"positive argument\", \"Float32\", \"sin_kernel\")"]` | 32.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "sin", "(\"argument reduction (easy) abs(x) < 9π/4\", \"positive argument\", \"Float64\", \"sin_kernel\")"]` | 38.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "sin", "(\"argument reduction (hard) abs(x) < 2π/4\", \"negative argument\", \"Float32\", \"cos_kernel\")"]` | 32.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "sin", "(\"argument reduction (hard) abs(x) < 2π/4\", \"negative argument\", \"Float64\", \"cos_kernel\")"]` | 45.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "sin", "(\"argument reduction (hard) abs(x) < 2π/4\", \"positive argument\", \"Float32\", \"cos_kernel\")"]` | 32.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "sin", "(\"argument reduction (hard) abs(x) < 2π/4\", \"positive argument\", \"Float64\", \"cos_kernel\")"]` | 45.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "sin", "(\"argument reduction (hard) abs(x) < 4π/4\", \"negative argument\", \"Float32\", \"sin_kernel\")"]` | 32.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "sin", "(\"argument reduction (hard) abs(x) < 4π/4\", \"negative argument\", \"Float64\", \"sin_kernel\")"]` | 47.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "sin", "(\"argument reduction (hard) abs(x) < 4π/4\", \"positive argument\", \"Float32\", \"sin_kernel\")"]` | 32.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "sin", "(\"argument reduction (hard) abs(x) < 4π/4\", \"positive argument\", \"Float64\", \"sin_kernel\")"]` | 47.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "sin", "(\"argument reduction (hard) abs(x) < 6π/4\", \"negative argument\", \"Float32\", \"cos_kernel\")"]` | 32.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "sin", "(\"argument reduction (hard) abs(x) < 6π/4\", \"negative argument\", \"Float64\", \"cos_kernel\")"]` | 46.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "sin", "(\"argument reduction (hard) abs(x) < 6π/4\", \"positive argument\", \"Float32\", \"cos_kernel\")"]` | 33.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "sin", "(\"argument reduction (hard) abs(x) < 6π/4\", \"positive argument\", \"Float64\", \"cos_kernel\")"]` | 46.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "sin", "(\"argument reduction (hard) abs(x) < 8π/4\", \"negative argument\", \"Float32\", \"sin_kernel\")"]` | 32.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "sin", "(\"argument reduction (hard) abs(x) < 8π/4\", \"negative argument\", \"Float64\", \"sin_kernel\")"]` | 48.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "sin", "(\"argument reduction (hard) abs(x) < 8π/4\", \"positive argument\", \"Float32\", \"sin_kernel\")"]` | 32.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "sin", "(\"argument reduction (hard) abs(x) < 8π/4\", \"positive argument\", \"Float64\", \"sin_kernel\")"]` | 48.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "sin", "(\"argument reduction (paynehanek) abs(x) > 2.0^20*π/2\", \"negative argument\", \"Float32\", \"cos_kernel\")"]` | 65.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "sin", "(\"argument reduction (paynehanek) abs(x) > 2.0^20*π/2\", \"negative argument\", \"Float32\", \"sin_kernel\")"]` | 63.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "sin", "(\"argument reduction (paynehanek) abs(x) > 2.0^20*π/2\", \"negative argument\", \"Float64\", \"cos_kernel\")"]` | 65.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "sin", "(\"argument reduction (paynehanek) abs(x) > 2.0^20*π/2\", \"negative argument\", \"Float64\", \"sin_kernel\")"]` | 63.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "sin", "(\"argument reduction (paynehanek) abs(x) > 2.0^20*π/2\", \"positive argument\", \"Float32\", \"cos_kernel\")"]` | 61.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "sin", "(\"argument reduction (paynehanek) abs(x) > 2.0^20*π/2\", \"positive argument\", \"Float32\", \"sin_kernel\")"]` | 60.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "sin", "(\"argument reduction (paynehanek) abs(x) > 2.0^20*π/2\", \"positive argument\", \"Float64\", \"cos_kernel\")"]` | 59.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "sin", "(\"argument reduction (paynehanek) abs(x) > 2.0^20*π/2\", \"positive argument\", \"Float64\", \"sin_kernel\")"]` | 66.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "sin", "(\"no reduction\", \"negative argument\", \"Float32\", \"sin_kernel\")"]` | 29.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "sin", "(\"no reduction\", \"negative argument\", \"Float64\", \"sin_kernel\")"]` | 31.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "sin", "(\"no reduction\", \"positive argument\", \"Float32\", \"sin_kernel\")"]` | 29.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "sin", "(\"no reduction\", \"positive argument\", \"Float64\", \"sin_kernel\")"]` | 31.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "sin", "(\"no reduction\", \"zero\", \"Float32\")"]` | 25.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "sin", "(\"no reduction\", \"zero\", \"Float64\")"]` | 25.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "sincos", "(\"argument reduction (easy) abs(x) < 2.0^20π/4\", \"negative argument\", \"Float32\")"]` | 40.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "sincos", "(\"argument reduction (easy) abs(x) < 2.0^20π/4\", \"negative argument\", \"Float64\")"]` | 48.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "sincos", "(\"argument reduction (easy) abs(x) < 2.0^20π/4\", \"positive argument\", \"Float32\")"]` | 40.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "sincos", "(\"argument reduction (easy) abs(x) < 2.0^20π/4\", \"positive argument\", \"Float64\")"]` | 48.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "sincos", "(\"argument reduction (easy) abs(x) < 2π/4\", \"negative argument\", \"Float32\")"]` | 45.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "sincos", "(\"argument reduction (easy) abs(x) < 2π/4\", \"negative argument\", \"Float64\")"]` | 45.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "sincos", "(\"argument reduction (easy) abs(x) < 2π/4\", \"positive argument\", \"Float32\")"]` | 44.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "sincos", "(\"argument reduction (easy) abs(x) < 2π/4\", \"positive argument\", \"Float64\")"]` | 44.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "sincos", "(\"argument reduction (easy) abs(x) < 3π/4\", \"negative argument\", \"Float32\")"]` | 45.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "sincos", "(\"argument reduction (easy) abs(x) < 3π/4\", \"negative argument\", \"Float64\")"]` | 45.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "sincos", "(\"argument reduction (easy) abs(x) < 3π/4\", \"positive argument\", \"Float32\")"]` | 46.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "sincos", "(\"argument reduction (easy) abs(x) < 3π/4\", \"positive argument\", \"Float64\")"]` | 44.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "sincos", "(\"argument reduction (easy) abs(x) < 4π/4\", \"negative argument\", \"Float32\")"]` | 40.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "sincos", "(\"argument reduction (easy) abs(x) < 4π/4\", \"negative argument\", \"Float64\")"]` | 41.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "sincos", "(\"argument reduction (easy) abs(x) < 4π/4\", \"positive argument\", \"Float32\")"]` | 34.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "sincos", "(\"argument reduction (easy) abs(x) < 4π/4\", \"positive argument\", \"Float64\")"]` | 40.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "sincos", "(\"argument reduction (easy) abs(x) < 5π/4\", \"negative argument\", \"Float32\")"]` | 40.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "sincos", "(\"argument reduction (easy) abs(x) < 5π/4\", \"negative argument\", \"Float64\")"]` | 40.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "sincos", "(\"argument reduction (easy) abs(x) < 5π/4\", \"positive argument\", \"Float32\")"]` | 40.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "sincos", "(\"argument reduction (easy) abs(x) < 5π/4\", \"positive argument\", \"Float64\")"]` | 40.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "sincos", "(\"argument reduction (easy) abs(x) < 6π/4\", \"negative argument\", \"Float32\")"]` | 44.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "sincos", "(\"argument reduction (easy) abs(x) < 6π/4\", \"negative argument\", \"Float64\")"]` | 44.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "sincos", "(\"argument reduction (easy) abs(x) < 6π/4\", \"positive argument\", \"Float32\")"]` | 45.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "sincos", "(\"argument reduction (easy) abs(x) < 6π/4\", \"positive argument\", \"Float64\")"]` | 45.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "sincos", "(\"argument reduction (easy) abs(x) < 7π/4\", \"negative argument\", \"Float32\")"]` | 44.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "sincos", "(\"argument reduction (easy) abs(x) < 7π/4\", \"negative argument\", \"Float64\")"]` | 45.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "sincos", "(\"argument reduction (easy) abs(x) < 7π/4\", \"positive argument\", \"Float32\")"]` | 46.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "sincos", "(\"argument reduction (easy) abs(x) < 7π/4\", \"positive argument\", \"Float64\")"]` | 45.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "sincos", "(\"argument reduction (easy) abs(x) < 8π/4\", \"negative argument\", \"Float32\")"]` | 45.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "sincos", "(\"argument reduction (easy) abs(x) < 8π/4\", \"negative argument\", \"Float64\")"]` | 45.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "sincos", "(\"argument reduction (easy) abs(x) < 8π/4\", \"positive argument\", \"Float32\")"]` | 44.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "sincos", "(\"argument reduction (easy) abs(x) < 8π/4\", \"positive argument\", \"Float64\")"]` | 45.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "sincos", "(\"argument reduction (easy) abs(x) < 9π/4\", \"negative argument\", \"Float32\")"]` | 45.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "sincos", "(\"argument reduction (easy) abs(x) < 9π/4\", \"negative argument\", \"Float64\")"]` | 45.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "sincos", "(\"argument reduction (easy) abs(x) < 9π/4\", \"positive argument\", \"Float32\")"]` | 45.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "sincos", "(\"argument reduction (easy) abs(x) < 9π/4\", \"positive argument\", \"Float64\")"]` | 45.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "sincos", "(\"argument reduction (hard) abs(x) < 2π/4\", \"negative argument\", \"Float32\")"]` | 54.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "sincos", "(\"argument reduction (hard) abs(x) < 2π/4\", \"negative argument\", \"Float64\")"]` | 54.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "sincos", "(\"argument reduction (hard) abs(x) < 2π/4\", \"positive argument\", \"Float32\")"]` | 54.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "sincos", "(\"argument reduction (hard) abs(x) < 2π/4\", \"positive argument\", \"Float64\")"]` | 54.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "sincos", "(\"argument reduction (hard) abs(x) < 4π/4\", \"negative argument\", \"Float32\")"]` | 34.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "sincos", "(\"argument reduction (hard) abs(x) < 4π/4\", \"negative argument\", \"Float64\")"]` | 50.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "sincos", "(\"argument reduction (hard) abs(x) < 4π/4\", \"positive argument\", \"Float32\")"]` | 34.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "sincos", "(\"argument reduction (hard) abs(x) < 4π/4\", \"positive argument\", \"Float64\")"]` | 50.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "sincos", "(\"argument reduction (hard) abs(x) < 6π/4\", \"negative argument\", \"Float32\")"]` | 54.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "sincos", "(\"argument reduction (hard) abs(x) < 6π/4\", \"negative argument\", \"Float64\")"]` | 54.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "sincos", "(\"argument reduction (hard) abs(x) < 6π/4\", \"positive argument\", \"Float32\")"]` | 54.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "sincos", "(\"argument reduction (hard) abs(x) < 6π/4\", \"positive argument\", \"Float64\")"]` | 55.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "sincos", "(\"argument reduction (hard) abs(x) < 8π/4\", \"negative argument\", \"Float32\")"]` | 54.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "sincos", "(\"argument reduction (hard) abs(x) < 8π/4\", \"negative argument\", \"Float64\")"]` | 54.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "sincos", "(\"argument reduction (hard) abs(x) < 8π/4\", \"positive argument\", \"Float32\")"]` | 54.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "sincos", "(\"argument reduction (hard) abs(x) < 8π/4\", \"positive argument\", \"Float64\")"]` | 54.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "sincos", "(\"argument reduction (paynehanek) abs(x) > 2.0^20*π/2\", \"negative argument\", \"Float32\")"]` | 72.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "sincos", "(\"argument reduction (paynehanek) abs(x) > 2.0^20*π/2\", \"negative argument\", \"Float64\")"]` | 68.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "sincos", "(\"argument reduction (paynehanek) abs(x) > 2.0^20*π/2\", \"positive argument\", \"Float32\")"]` | 67.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "sincos", "(\"argument reduction (paynehanek) abs(x) > 2.0^20*π/2\", \"positive argument\", \"Float64\")"]` | 68.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "sincos", "(\"no reduction\", \"negative argument\", \"Float32\")"]` | 37.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "sincos", "(\"no reduction\", \"negative argument\", \"Float64\")"]` | 37.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "sincos", "(\"no reduction\", \"positive argument\", \"Float32\")"]` | 37.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "sincos", "(\"no reduction\", \"positive argument\", \"Float64\")"]` | 37.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "sincos", "(\"no reduction\", \"zero\", \"Float32\")"]` | 23.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "sincos", "(\"no reduction\", \"zero\", \"Float64\")"]` | 23.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "sinh", "(\"0 <= abs(x) < 2.0^-28\", \"negative argument\", \"Float64\")"]` | 42.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "sinh", "(\"0 <= abs(x) < 2.0^-28\", \"positive argument\", \"Float64\")"]` | 42.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "sinh", "(\"0 <= abs(x) < 2f-12\", \"negative argument\", \"Float32\")"]` | 23.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "sinh", "(\"0 <= abs(x) < 2f-12\", \"positive argument\", \"Float32\")"]` | 23.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "sinh", "(\"2.0^-28 <= abs(x) < 22.0\", \"negative argument\", \"Float64\")"]` | 23.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "sinh", "(\"2.0^-28 <= abs(x) < 22.0\", \"positive argument\", \"Float64\")"]` | 23.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "sinh", "(\"22.0 <= abs(x) < 709.7822265633563\", \"negative argument\", \"Float64\")"]` | 23.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "sinh", "(\"22.0 <= abs(x) < 709.7822265633563\", \"positive argument\", \"Float64\")"]` | 23.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "sinh", "(\"2f-12 <= abs(x) < 9f0\", \"negative argument\", \"Float32\")"]` | 23.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "sinh", "(\"2f-12 <= abs(x) < 9f0\", \"positive argument\", \"Float32\")"]` | 23.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "sinh", "(\"9f0 <= abs(x) < 88.72283f0\", \"negative argument\", \"Float32\")"]` | 23.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "sinh", "(\"9f0 <= abs(x) < 88.72283f0\", \"positive argument\", \"Float32\")"]` | 23.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "sinh", "(\"very large\", \"negative argument\", \"Float32\")"]` | 23.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "sinh", "(\"very large\", \"negative argument\", \"Float64\")"]` | 23.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "sinh", "(\"very large\", \"positive argument\", \"Float32\")"]` | 23.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "sinh", "(\"very large\", \"positive argument\", \"Float64\")"]` | 23.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "sinh", "(\"very small\", \"negative argument\", \"Float32\")"]` | 23.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "sinh", "(\"very small\", \"negative argument\", \"Float64\")"]` | 88.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "sinh", "(\"very small\", \"positive argument\", \"Float32\")"]` | 23.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "sinh", "(\"very small\", \"positive argument\", \"Float64\")"]` | 88.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "sinh", "(\"zero\", \"Float32\")"]` | 23.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "sinh", "(\"zero\", \"Float64\")"]` | 41.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "tan", "(\"large\", \"negative argument\", \"Float32\")"]` | 24.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "tan", "(\"large\", \"negative argument\", \"Float64\")"]` | 24.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "tan", "(\"large\", \"positive argument\", \"Float32\")"]` | 24.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "tan", "(\"large\", \"positive argument\", \"Float64\")"]` | 24.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "tan", "(\"medium\", \"negative argument\", \"Float32\")"]` | 24.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "tan", "(\"medium\", \"negative argument\", \"Float64\")"]` | 40.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "tan", "(\"medium\", \"positive argument\", \"Float32\")"]` | 24.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "tan", "(\"medium\", \"positive argument\", \"Float64\")"]` | 40.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "tan", "(\"small\", \"negative argument\", \"Float32\")"]` | 26.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "tan", "(\"small\", \"negative argument\", \"Float64\")"]` | 26.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "tan", "(\"small\", \"positive argument\", \"Float32\")"]` | 26.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "tan", "(\"small\", \"positive argument\", \"Float64\")"]` | 26.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "tan", "(\"very small\", \"negative argument\", \"Float32\")"]` | 26.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "tan", "(\"very small\", \"negative argument\", \"Float64\")"]` | 26.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "tan", "(\"very small\", \"positive argument\", \"Float32\")"]` | 26.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "tan", "(\"very small\", \"positive argument\", \"Float64\")"]` | 26.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "tan", "(\"zero\", \"Float32\")"]` | 25.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "tan", "(\"zero\", \"Float64\")"]` | 25.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "tanh", "(\"0 <= abs(x) < 2.0^-28\", \"negative argument\", \"Float64\")"]` | 23.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "tanh", "(\"0 <= abs(x) < 2.0^-28\", \"positive argument\", \"Float64\")"]` | 23.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "tanh", "(\"0 <= abs(x) < 2f0^-12\", \"negative argument\", \"Float32\")"]` | 23.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "tanh", "(\"0 <= abs(x) < 2f0^-12\", \"positive argument\", \"Float32\")"]` | 23.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "tanh", "(\"1.0 <= abs(x) < 22.0\", \"negative argument\", \"Float64\")"]` | 23.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "tanh", "(\"1.0 <= abs(x) < 22.0\", \"positive argument\", \"Float64\")"]` | 23.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "tanh", "(\"1f0 <= abs(x) < 9f0\", \"negative argument\", \"Float32\")"]` | 23.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "tanh", "(\"1f0 <= abs(x) < 9f0\", \"positive argument\", \"Float32\")"]` | 23.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "tanh", "(\"2.0^-28 <= abs(x) < 1.0\", \"negative argument\", \"Float64\")"]` | 23.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "tanh", "(\"2.0^-28 <= abs(x) < 1.0\", \"positive argument\", \"Float64\")"]` | 23.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "tanh", "(\"2f0^-12 <= abs(x) < 1f0\", \"negative argument\", \"Float32\")"]` | 23.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "tanh", "(\"2f0^-12 <= abs(x) < 1f0\", \"positive argument\", \"Float32\")"]` | 23.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "tanh", "(\"very large\", \"negative argument\", \"Float32\")"]` | 23.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "tanh", "(\"very large\", \"negative argument\", \"Float64\")"]` | 23.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "tanh", "(\"very large\", \"positive argument\", \"Float32\")"]` | 23.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "tanh", "(\"very large\", \"positive argument\", \"Float64\")"]` | 23.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "tanh", "(\"very small\", \"negative argument\", \"Float32\")"]` | 23.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "tanh", "(\"very small\", \"negative argument\", \"Float64\")"]` | 23.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "tanh", "(\"very small\", \"positive argument\", \"Float32\")"]` | 23.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "tanh", "(\"very small\", \"positive argument\", \"Float64\")"]` | 23.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "tanh", "(\"zero\", \"Float32\")"]` | 23.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["scalar", "tanh", "(\"zero\", \"Float64\")"]` | 23.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["shootout", "binary_trees"]` | 14.909 ms (5%) | 0.000 ns | 13.96 MiB (1%) | 783717 |
| `["shootout", "fannkuch"]` | 172.218 μs (5%) | 0.000 ns | 336 bytes (1%) | 3 |
| `["shootout", "fasta"]` | 12.836 μs (5%) | 0.000 ns | 14.11 KiB (1%) | 806 |
| `["shootout", "k_nucleotide"]` | 24.805 ms (5%) | 0.000 ns | 9.07 MiB (1%) | 254257 |
| `["shootout", "mandelbrot"]` | 3.630 ms (5%) | 0.000 ns | 10.63 KiB (1%) | 14 |
| `["shootout", "meteor_contest"]` | 1.466 s (5%) | 0.000 ns | 765.95 MiB (1%) | 33689040 |
| `["shootout", "nbody"]` | 95.625 μs (5%) | 0.000 ns | 448 bytes (1%) | 6 |
| `["shootout", "nbody_vec"]` | 310.725 μs (5%) | 0.000 ns | 110.86 KiB (1%) | 1017 |
| `["shootout", "pidigits"]` | 15.172 ms (5%) | 0.000 ns | 62.89 MiB (1%) | 89236 |
| `["shootout", "regex_dna"]` | 4.142 ms (5%) | 0.000 ns | 1.69 MiB (1%) | 211 |
| `["shootout", "revcomp"]` | 133.704 μs (25%) | 0.000 ns | 69.45 KiB (1%) | 384 |
| `["shootout", "spectralnorm"]` | 1.071 ms (5%) | 0.000 ns | 2.63 KiB (1%) | 3 |
| `["simd", "(\"auto_axpy!\", \"Float32\", 4095)"]` | 343.000 ns (20%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["simd", "(\"auto_axpy!\", \"Float32\", 4096)"]` | 356.000 ns (20%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["simd", "(\"auto_axpy!\", \"Float64\", 4095)"]` | 839.000 ns (20%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["simd", "(\"auto_axpy!\", \"Float64\", 4096)"]` | 833.000 ns (20%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["simd", "(\"auto_axpy!\", \"Int32\", 4095)"]` | 421.000 ns (20%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["simd", "(\"auto_axpy!\", \"Int32\", 4096)"]` | 351.000 ns (20%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["simd", "(\"auto_axpy!\", \"Int64\", 4095)"]` | 978.000 ns (20%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["simd", "(\"auto_axpy!\", \"Int64\", 4096)"]` | 975.000 ns (20%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["simd", "(\"auto_conditional_loop!\", \"Float32\", 4095)"]` | 989.000 ns (20%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["simd", "(\"auto_conditional_loop!\", \"Float32\", 4096)"]` | 1.001 μs (20%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["simd", "(\"auto_conditional_loop!\", \"Float64\", 4095)"]` | 1.870 μs (20%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["simd", "(\"auto_conditional_loop!\", \"Float64\", 4096)"]` | 1.843 μs (20%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["simd", "(\"auto_conditional_loop!\", \"Int32\", 4095)"]` | 192.000 ns (20%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["simd", "(\"auto_conditional_loop!\", \"Int32\", 4096)"]` | 184.000 ns (20%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["simd", "(\"auto_conditional_loop!\", \"Int64\", 4095)"]` | 503.000 ns (20%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["simd", "(\"auto_conditional_loop!\", \"Int64\", 4096)"]` | 495.000 ns (20%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["simd", "(\"auto_inner\", \"Int32\", 4095)"]` | 366.000 ns (20%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["simd", "(\"auto_inner\", \"Int32\", 4096)"]` | 349.000 ns (20%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["simd", "(\"auto_inner\", \"Int64\", 4095)"]` | 926.000 ns (20%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["simd", "(\"auto_inner\", \"Int64\", 4096)"]` | 918.000 ns (20%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["simd", "(\"auto_local_arrays\", \"Float32\", 4095)"]` | 35.702 μs (20%) | 0.000 ns | 108.12 KiB (1%) | 42 |
| `["simd", "(\"auto_local_arrays\", \"Float32\", 4096)"]` | 35.525 μs (20%) | 0.000 ns | 108.12 KiB (1%) | 42 |
| `["simd", "(\"auto_local_arrays\", \"Float64\", 4095)"]` | 42.217 μs (20%) | 0.000 ns | 156.21 KiB (1%) | 57 |
| `["simd", "(\"auto_local_arrays\", \"Float64\", 4096)"]` | 42.198 μs (20%) | 0.000 ns | 156.21 KiB (1%) | 57 |
| `["simd", "(\"auto_local_arrays\", \"Int32\", 4095)"]` | 36.634 μs (20%) | 0.000 ns | 108.35 KiB (1%) | 54 |
| `["simd", "(\"auto_local_arrays\", \"Int32\", 4096)"]` | 36.806 μs (20%) | 0.000 ns | 108.35 KiB (1%) | 54 |
| `["simd", "(\"auto_local_arrays\", \"Int64\", 4095)"]` | 54.750 μs (20%) | 0.000 ns | 203.46 KiB (1%) | 60 |
| `["simd", "(\"auto_local_arrays\", \"Int64\", 4096)"]` | 44.911 μs (20%) | 0.000 ns | 156.21 KiB (1%) | 57 |
| `["simd", "(\"auto_manual_example!\", \"Int32\", 4095)"]` | 544.000 ns (20%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["simd", "(\"auto_manual_example!\", \"Int32\", 4096)"]` | 548.000 ns (20%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["simd", "(\"auto_manual_example!\", \"Int64\", 4095)"]` | 1.236 μs (20%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["simd", "(\"auto_manual_example!\", \"Int64\", 4096)"]` | 1.232 μs (20%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["simd", "(\"auto_sum_reduce\", \"Int32\", 4095)"]` | 65.000 ns (20%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["simd", "(\"auto_sum_reduce\", \"Int32\", 4096)"]` | 65.000 ns (20%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["simd", "(\"auto_sum_reduce\", \"Int64\", 4095)"]` | 102.000 ns (20%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["simd", "(\"auto_sum_reduce\", \"Int64\", 4096)"]` | 106.000 ns (20%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["simd", "(\"auto_two_reductions\", \"Int32\", 4095)"]` | 5.471 μs (20%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["simd", "(\"auto_two_reductions\", \"Int32\", 4096)"]` | 6.976 μs (20%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["simd", "(\"auto_two_reductions\", \"Int64\", 4095)"]` | 1.154 μs (20%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["simd", "(\"auto_two_reductions\", \"Int64\", 4096)"]` | 1.148 μs (20%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["simd", "(\"axpy!\", \"Float32\", 4095)"]` | 341.000 ns (20%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["simd", "(\"axpy!\", \"Float32\", 4096)"]` | 333.000 ns (20%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["simd", "(\"axpy!\", \"Float64\", 4095)"]` | 835.000 ns (20%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["simd", "(\"axpy!\", \"Float64\", 4096)"]` | 831.000 ns (20%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["simd", "(\"axpy!\", \"Int32\", 4095)"]` | 435.000 ns (20%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["simd", "(\"axpy!\", \"Int32\", 4096)"]` | 356.000 ns (20%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["simd", "(\"axpy!\", \"Int64\", 4095)"]` | 986.000 ns (20%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["simd", "(\"axpy!\", \"Int64\", 4096)"]` | 974.000 ns (20%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["simd", "(\"axpy!_aliased\", \"Float32\", 4095)"]` | 2.438 μs (20%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["simd", "(\"axpy!_aliased\", \"Float32\", 4096)"]` | 2.448 μs (20%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["simd", "(\"axpy!_aliased\", \"Float64\", 4095)"]` | 2.444 μs (20%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["simd", "(\"axpy!_aliased\", \"Float64\", 4096)"]` | 2.444 μs (20%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["simd", "(\"axpy!_aliased\", \"Int32\", 4095)"]` | 2.438 μs (20%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["simd", "(\"axpy!_aliased\", \"Int32\", 4096)"]` | 2.440 μs (20%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["simd", "(\"axpy!_aliased\", \"Int64\", 4095)"]` | 2.445 μs (20%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["simd", "(\"axpy!_aliased\", \"Int64\", 4096)"]` | 2.445 μs (20%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["simd", "(\"conditional_loop!\", \"Float32\", 4095)"]` | 996.000 ns (20%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["simd", "(\"conditional_loop!\", \"Float32\", 4096)"]` | 1.002 μs (20%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["simd", "(\"conditional_loop!\", \"Float64\", 4095)"]` | 1.871 μs (20%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["simd", "(\"conditional_loop!\", \"Float64\", 4096)"]` | 1.850 μs (20%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["simd", "(\"conditional_loop!\", \"Int32\", 4095)"]` | 192.000 ns (20%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["simd", "(\"conditional_loop!\", \"Int32\", 4096)"]` | 191.000 ns (20%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["simd", "(\"conditional_loop!\", \"Int64\", 4095)"]` | 500.000 ns (20%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["simd", "(\"conditional_loop!\", \"Int64\", 4096)"]` | 502.000 ns (20%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["simd", "(\"conditional_loop!_aliased\", \"Float32\", 4095)"]` | 9.680 μs (20%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["simd", "(\"conditional_loop!_aliased\", \"Float32\", 4096)"]` | 9.682 μs (20%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["simd", "(\"conditional_loop!_aliased\", \"Float64\", 4095)"]` | 9.687 μs (20%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["simd", "(\"conditional_loop!_aliased\", \"Float64\", 4096)"]` | 9.690 μs (20%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["simd", "(\"conditional_loop!_aliased\", \"Int32\", 4095)"]` | 193.000 ns (20%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["simd", "(\"conditional_loop!_aliased\", \"Int32\", 4096)"]` | 184.000 ns (20%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["simd", "(\"conditional_loop!_aliased\", \"Int64\", 4095)"]` | 508.000 ns (20%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["simd", "(\"conditional_loop!_aliased\", \"Int64\", 4096)"]` | 499.000 ns (20%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["simd", "(\"inner\", \"Float32\", 4095)"]` | 320.000 ns (20%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["simd", "(\"inner\", \"Float32\", 4096)"]` | 258.000 ns (20%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["simd", "(\"inner\", \"Float64\", 4095)"]` | 746.000 ns (20%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["simd", "(\"inner\", \"Float64\", 4096)"]` | 732.000 ns (20%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["simd", "(\"inner\", \"Int32\", 4095)"]` | 366.000 ns (20%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["simd", "(\"inner\", \"Int32\", 4096)"]` | 347.000 ns (20%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["simd", "(\"inner\", \"Int64\", 4095)"]` | 920.000 ns (20%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["simd", "(\"inner\", \"Int64\", 4096)"]` | 917.000 ns (20%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["simd", "(\"inner_aliased\", \"Float32\", 4095)"]` | 226.000 ns (20%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["simd", "(\"inner_aliased\", \"Float32\", 4096)"]` | 189.000 ns (20%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["simd", "(\"inner_aliased\", \"Float64\", 4095)"]` | 574.000 ns (20%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["simd", "(\"inner_aliased\", \"Float64\", 4096)"]` | 492.000 ns (20%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["simd", "(\"inner_aliased\", \"Int32\", 4095)"]` | 309.000 ns (20%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["simd", "(\"inner_aliased\", \"Int32\", 4096)"]` | 280.000 ns (20%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["simd", "(\"inner_aliased\", \"Int64\", 4095)"]` | 828.000 ns (20%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["simd", "(\"inner_aliased\", \"Int64\", 4096)"]` | 822.000 ns (20%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["simd", "(\"local_arrays\", \"Float32\", 4095)"]` | 36.096 μs (20%) | 0.000 ns | 108.12 KiB (1%) | 42 |
| `["simd", "(\"local_arrays\", \"Float32\", 4096)"]` | 36.037 μs (20%) | 0.000 ns | 108.12 KiB (1%) | 42 |
| `["simd", "(\"local_arrays\", \"Float64\", 4095)"]` | 42.015 μs (20%) | 0.000 ns | 156.21 KiB (1%) | 57 |
| `["simd", "(\"local_arrays\", \"Float64\", 4096)"]` | 42.185 μs (20%) | 0.000 ns | 156.21 KiB (1%) | 57 |
| `["simd", "(\"local_arrays\", \"Int32\", 4095)"]` | 36.778 μs (20%) | 0.000 ns | 108.35 KiB (1%) | 54 |
| `["simd", "(\"local_arrays\", \"Int32\", 4096)"]` | 36.778 μs (20%) | 0.000 ns | 108.35 KiB (1%) | 54 |
| `["simd", "(\"local_arrays\", \"Int64\", 4095)"]` | 55.012 μs (20%) | 0.000 ns | 203.46 KiB (1%) | 60 |
| `["simd", "(\"local_arrays\", \"Int64\", 4096)"]` | 45.018 μs (20%) | 0.000 ns | 156.21 KiB (1%) | 57 |
| `["simd", "(\"loop_fields!\", \"Float32\", \"BaseBenchmarks.SIMDBenchmarks.ImmutableFields\", 4095)"]` | 2.449 μs (20%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["simd", "(\"loop_fields!\", \"Float32\", \"BaseBenchmarks.SIMDBenchmarks.ImmutableFields\", 4096)"]` | 2.449 μs (20%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["simd", "(\"loop_fields!\", \"Float32\", \"BaseBenchmarks.SIMDBenchmarks.MutableFields\", 4095)"]` | 2.448 μs (20%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["simd", "(\"loop_fields!\", \"Float32\", \"BaseBenchmarks.SIMDBenchmarks.MutableFields\", 4096)"]` | 2.450 μs (20%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["simd", "(\"loop_fields!\", \"Float64\", \"BaseBenchmarks.SIMDBenchmarks.ImmutableFields\", 4095)"]` | 1.848 μs (20%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["simd", "(\"loop_fields!\", \"Float64\", \"BaseBenchmarks.SIMDBenchmarks.ImmutableFields\", 4096)"]` | 1.849 μs (20%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["simd", "(\"loop_fields!\", \"Float64\", \"BaseBenchmarks.SIMDBenchmarks.MutableFields\", 4095)"]` | 1.850 μs (20%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["simd", "(\"loop_fields!\", \"Float64\", \"BaseBenchmarks.SIMDBenchmarks.MutableFields\", 4096)"]` | 1.849 μs (20%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["simd", "(\"loop_fields!\", \"Int32\", \"BaseBenchmarks.SIMDBenchmarks.ImmutableFields\", 4095)"]` | 1.840 μs (20%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["simd", "(\"loop_fields!\", \"Int32\", \"BaseBenchmarks.SIMDBenchmarks.ImmutableFields\", 4096)"]` | 1.841 μs (20%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["simd", "(\"loop_fields!\", \"Int32\", \"BaseBenchmarks.SIMDBenchmarks.MutableFields\", 4095)"]` | 1.840 μs (20%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["simd", "(\"loop_fields!\", \"Int32\", \"BaseBenchmarks.SIMDBenchmarks.MutableFields\", 4096)"]` | 1.840 μs (20%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["simd", "(\"loop_fields!\", \"Int64\", \"BaseBenchmarks.SIMDBenchmarks.ImmutableFields\", 4095)"]` | 1.865 μs (20%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["simd", "(\"loop_fields!\", \"Int64\", \"BaseBenchmarks.SIMDBenchmarks.ImmutableFields\", 4096)"]` | 1.869 μs (20%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["simd", "(\"loop_fields!\", \"Int64\", \"BaseBenchmarks.SIMDBenchmarks.MutableFields\", 4095)"]` | 1.866 μs (20%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["simd", "(\"loop_fields!\", \"Int64\", \"BaseBenchmarks.SIMDBenchmarks.MutableFields\", 4096)"]` | 1.867 μs (20%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["simd", "(\"manual_example!\", \"Float32\", 4095)"]` | 510.000 ns (20%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["simd", "(\"manual_example!\", \"Float32\", 4096)"]` | 554.000 ns (20%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["simd", "(\"manual_example!\", \"Float64\", 4095)"]` | 1.195 μs (20%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["simd", "(\"manual_example!\", \"Float64\", 4096)"]` | 1.184 μs (20%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["simd", "(\"manual_example!\", \"Int32\", 4095)"]` | 549.000 ns (20%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["simd", "(\"manual_example!\", \"Int32\", 4096)"]` | 552.000 ns (20%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["simd", "(\"manual_example!\", \"Int64\", 4095)"]` | 1.237 μs (20%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["simd", "(\"manual_example!\", \"Int64\", 4096)"]` | 1.228 μs (20%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["simd", "(\"manual_example!_aliased\", \"Float32\", 4095)"]` | 4.841 μs (20%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["simd", "(\"manual_example!_aliased\", \"Float32\", 4096)"]` | 4.843 μs (20%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["simd", "(\"manual_example!_aliased\", \"Float64\", 4095)"]` | 4.848 μs (20%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["simd", "(\"manual_example!_aliased\", \"Float64\", 4096)"]` | 4.849 μs (20%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["simd", "(\"manual_example!_aliased\", \"Int32\", 4095)"]` | 2.529 μs (20%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["simd", "(\"manual_example!_aliased\", \"Int32\", 4096)"]` | 2.533 μs (20%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["simd", "(\"manual_example!_aliased\", \"Int64\", 4095)"]` | 2.544 μs (20%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["simd", "(\"manual_example!_aliased\", \"Int64\", 4096)"]` | 2.542 μs (20%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["simd", "(\"sum_reduce\", \"Float32\", 4095)"]` | 77.000 ns (20%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["simd", "(\"sum_reduce\", \"Float32\", 4096)"]` | 76.000 ns (20%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["simd", "(\"sum_reduce\", \"Float64\", 4095)"]` | 113.000 ns (20%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["simd", "(\"sum_reduce\", \"Float64\", 4096)"]` | 114.000 ns (20%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["simd", "(\"sum_reduce\", \"Int32\", 4095)"]` | 66.000 ns (20%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["simd", "(\"sum_reduce\", \"Int32\", 4096)"]` | 65.000 ns (20%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["simd", "(\"sum_reduce\", \"Int64\", 4095)"]` | 103.000 ns (20%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["simd", "(\"sum_reduce\", \"Int64\", 4096)"]` | 106.000 ns (20%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["simd", "(\"two_reductions\", \"Float32\", 4095)"]` | 655.000 ns (20%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["simd", "(\"two_reductions\", \"Float32\", 4096)"]` | 586.000 ns (20%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["simd", "(\"two_reductions\", \"Float64\", 4095)"]` | 1.217 μs (20%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["simd", "(\"two_reductions\", \"Float64\", 4096)"]` | 1.172 μs (20%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["simd", "(\"two_reductions\", \"Int32\", 4095)"]` | 7.271 μs (20%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["simd", "(\"two_reductions\", \"Int32\", 4096)"]` | 7.272 μs (20%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["simd", "(\"two_reductions\", \"Int64\", 4095)"]` | 1.151 μs (20%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["simd", "(\"two_reductions\", \"Int64\", 4096)"]` | 1.150 μs (20%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["simd", "(\"two_reductions_aliased\", \"Float32\", 4095)"]` | 418.000 ns (20%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["simd", "(\"two_reductions_aliased\", \"Float32\", 4096)"]` | 344.000 ns (20%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["simd", "(\"two_reductions_aliased\", \"Float64\", 4095)"]` | 763.000 ns (20%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["simd", "(\"two_reductions_aliased\", \"Float64\", 4096)"]` | 736.000 ns (20%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["simd", "(\"two_reductions_aliased\", \"Int32\", 4095)"]` | 7.262 μs (20%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["simd", "(\"two_reductions_aliased\", \"Int32\", 4096)"]` | 7.265 μs (20%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["simd", "(\"two_reductions_aliased\", \"Int64\", 4095)"]` | 717.000 ns (20%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["simd", "(\"two_reductions_aliased\", \"Int64\", 4096)"]` | 744.000 ns (20%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["sort", "insertionsort", "(\"sort forwards\", \"ascending\")"]` | 145.613 μs (30%) | 0.000 ns | 390.70 KiB (1%) | 2 |
| `["sort", "insertionsort", "(\"sort forwards\", \"descending\")"]` | 565.720 ms (30%) | 0.000 ns | 390.70 KiB (1%) | 2 |
| `["sort", "insertionsort", "(\"sort forwards\", \"ones\")"]` | 180.119 μs (30%) | 0.000 ns | 390.70 KiB (1%) | 2 |
| `["sort", "insertionsort", "(\"sort forwards\", \"random\")"]` | 246.223 ms (30%) | 0.000 ns | 390.70 KiB (1%) | 2 |
| `["sort", "insertionsort", "(\"sort reverse\", \"ascending\")"]` | 491.451 ms (30%) | 0.000 ns | 390.70 KiB (1%) | 2 |
| `["sort", "insertionsort", "(\"sort reverse\", \"descending\")"]` | 145.478 μs (30%) | 0.000 ns | 390.70 KiB (1%) | 2 |
| `["sort", "insertionsort", "(\"sort reverse\", \"ones\")"]` | 202.773 μs (30%) | 0.000 ns | 390.70 KiB (1%) | 2 |
| `["sort", "insertionsort", "(\"sort reverse\", \"random\")"]` | 243.757 ms (30%) | 0.000 ns | 390.70 KiB (1%) | 2 |
| `["sort", "insertionsort", "(\"sort! forwards\", \"ascending\")"]` | 85.335 μs (30%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["sort", "insertionsort", "(\"sort! forwards\", \"descending\")"]` | 565.623 ms (30%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["sort", "insertionsort", "(\"sort! forwards\", \"ones\")"]` | 123.894 μs (30%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["sort", "insertionsort", "(\"sort! forwards\", \"random\")"]` | 246.041 ms (30%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["sort", "insertionsort", "(\"sort! reverse\", \"ascending\")"]` | 491.323 ms (30%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["sort", "insertionsort", "(\"sort! reverse\", \"descending\")"]` | 86.900 μs (30%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["sort", "insertionsort", "(\"sort! reverse\", \"ones\")"]` | 146.225 μs (30%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["sort", "insertionsort", "(\"sort! reverse\", \"random\")"]` | 243.622 ms (30%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["sort", "insertionsort", "(\"sortperm forwards\", \"ascending\")"]` | 167.233 μs (30%) | 0.000 ns | 390.72 KiB (1%) | 3 |
| `["sort", "insertionsort", "(\"sortperm forwards\", \"descending\")"]` | 1.071 s (30%) | 0.000 ns | 390.72 KiB (1%) | 3 |
| `["sort", "insertionsort", "(\"sortperm forwards\", \"ones\")"]` | 205.048 μs (30%) | 0.000 ns | 390.72 KiB (1%) | 3 |
| `["sort", "insertionsort", "(\"sortperm forwards\", \"random\")"]` | 632.635 ms (30%) | 0.000 ns | 390.72 KiB (1%) | 3 |
| `["sort", "insertionsort", "(\"sortperm reverse\", \"ascending\")"]` | 1.076 s (30%) | 0.000 ns | 390.72 KiB (1%) | 3 |
| `["sort", "insertionsort", "(\"sortperm reverse\", \"descending\")"]` | 123.298 μs (30%) | 0.000 ns | 390.72 KiB (1%) | 3 |
| `["sort", "insertionsort", "(\"sortperm reverse\", \"ones\")"]` | 286.086 μs (30%) | 0.000 ns | 390.72 KiB (1%) | 3 |
| `["sort", "insertionsort", "(\"sortperm reverse\", \"random\")"]` | 632.119 ms (30%) | 0.000 ns | 390.72 KiB (1%) | 3 |
| `["sort", "insertionsort", "(\"sortperm! forwards\", \"ascending\")"]` | 133.338 μs (30%) | 0.000 ns | 16 bytes (1%) | 1 |
| `["sort", "insertionsort", "(\"sortperm! forwards\", \"descending\")"]` | 1.071 s (30%) | 0.000 ns | 16 bytes (1%) | 1 |
| `["sort", "insertionsort", "(\"sortperm! forwards\", \"ones\")"]` | 177.817 μs (30%) | 0.000 ns | 16 bytes (1%) | 1 |
| `["sort", "insertionsort", "(\"sortperm! forwards\", \"random\")"]` | 633.039 ms (30%) | 0.000 ns | 16 bytes (1%) | 1 |
| `["sort", "insertionsort", "(\"sortperm! reverse\", \"ascending\")"]` | 1.076 s (30%) | 0.000 ns | 16 bytes (1%) | 1 |
| `["sort", "insertionsort", "(\"sortperm! reverse\", \"descending\")"]` | 97.124 μs (30%) | 0.000 ns | 16 bytes (1%) | 1 |
| `["sort", "insertionsort", "(\"sortperm! reverse\", \"ones\")"]` | 258.390 μs (30%) | 0.000 ns | 16 bytes (1%) | 1 |
| `["sort", "insertionsort", "(\"sortperm! reverse\", \"random\")"]` | 632.289 ms (30%) | 0.000 ns | 16 bytes (1%) | 1 |
| `["sort", "issorted", "(\"forwards\", \"ascending\")"]` | 29.465 μs (30%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["sort", "issorted", "(\"forwards\", \"descending\")"]` | 24.000 ns (30%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["sort", "issorted", "(\"forwards\", \"ones\")"]` | 134.733 μs (30%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["sort", "issorted", "(\"forwards\", \"random\")"]` | 28.000 ns (30%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["sort", "issorted", "(\"reverse\", \"ascending\")"]` | 126.000 ns (30%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["sort", "issorted", "(\"reverse\", \"descending\")"]` | 29.611 μs (30%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["sort", "issorted", "(\"reverse\", \"ones\")"]` | 137.082 μs (30%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["sort", "issorted", "(\"reverse\", \"random\")"]` | 126.000 ns (30%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["sort", "mergesort", "(\"sort forwards\", \"ascending\")"]` | 567.045 μs (30%) | 0.000 ns | 586.16 KiB (1%) | 4 |
| `["sort", "mergesort", "(\"sort forwards\", \"descending\")"]` | 737.102 μs (30%) | 0.000 ns | 586.16 KiB (1%) | 4 |
| `["sort", "mergesort", "(\"sort forwards\", \"ones\")"]` | 600.035 μs (30%) | 0.000 ns | 586.23 KiB (1%) | 5 |
| `["sort", "mergesort", "(\"sort forwards\", \"random\")"]` | 3.343 ms (30%) | 0.000 ns | 586.23 KiB (1%) | 5 |
| `["sort", "mergesort", "(\"sort reverse\", \"ascending\")"]` | 735.981 μs (30%) | 0.000 ns | 586.16 KiB (1%) | 4 |
| `["sort", "mergesort", "(\"sort reverse\", \"descending\")"]` | 568.015 μs (30%) | 0.000 ns | 586.16 KiB (1%) | 4 |
| `["sort", "mergesort", "(\"sort reverse\", \"ones\")"]` | 748.363 μs (30%) | 0.000 ns | 586.23 KiB (1%) | 5 |
| `["sort", "mergesort", "(\"sort reverse\", \"random\")"]` | 3.701 ms (30%) | 0.000 ns | 586.23 KiB (1%) | 5 |
| `["sort", "mergesort", "(\"sort! forwards\", \"ascending\")"]` | 508.438 μs (30%) | 0.000 ns | 195.45 KiB (1%) | 2 |
| `["sort", "mergesort", "(\"sort! forwards\", \"descending\")"]` | 679.044 μs (30%) | 0.000 ns | 195.45 KiB (1%) | 2 |
| `["sort", "mergesort", "(\"sort! forwards\", \"ones\")"]` | 541.962 μs (30%) | 0.000 ns | 195.53 KiB (1%) | 3 |
| `["sort", "mergesort", "(\"sort! forwards\", \"random\")"]` | 3.284 ms (30%) | 0.000 ns | 195.53 KiB (1%) | 3 |
| `["sort", "mergesort", "(\"sort! reverse\", \"ascending\")"]` | 676.990 μs (30%) | 0.000 ns | 195.45 KiB (1%) | 2 |
| `["sort", "mergesort", "(\"sort! reverse\", \"descending\")"]` | 510.318 μs (30%) | 0.000 ns | 195.45 KiB (1%) | 2 |
| `["sort", "mergesort", "(\"sort! reverse\", \"ones\")"]` | 688.636 μs (30%) | 0.000 ns | 195.53 KiB (1%) | 3 |
| `["sort", "mergesort", "(\"sort! reverse\", \"random\")"]` | 3.649 ms (30%) | 0.000 ns | 195.53 KiB (1%) | 3 |
| `["sort", "mergesort", "(\"sortperm forwards\", \"ascending\")"]` | 811.416 μs (30%) | 0.000 ns | 586.17 KiB (1%) | 5 |
| `["sort", "mergesort", "(\"sortperm forwards\", \"descending\")"]` | 1.049 ms (30%) | 0.000 ns | 586.17 KiB (1%) | 5 |
| `["sort", "mergesort", "(\"sortperm forwards\", \"ones\")"]` | 857.289 μs (30%) | 0.000 ns | 586.25 KiB (1%) | 6 |
| `["sort", "mergesort", "(\"sortperm forwards\", \"random\")"]` | 4.557 ms (30%) | 0.000 ns | 586.25 KiB (1%) | 6 |
| `["sort", "mergesort", "(\"sortperm reverse\", \"ascending\")"]` | 1.033 ms (30%) | 0.000 ns | 586.17 KiB (1%) | 5 |
| `["sort", "mergesort", "(\"sortperm reverse\", \"descending\")"]` | 768.200 μs (30%) | 0.000 ns | 586.17 KiB (1%) | 5 |
| `["sort", "mergesort", "(\"sortperm reverse\", \"ones\")"]` | 924.053 μs (30%) | 0.000 ns | 586.25 KiB (1%) | 6 |
| `["sort", "mergesort", "(\"sortperm reverse\", \"random\")"]` | 4.644 ms (30%) | 0.000 ns | 586.25 KiB (1%) | 6 |
| `["sort", "mergesort", "(\"sortperm! forwards\", \"ascending\")"]` | 769.274 μs (30%) | 0.000 ns | 195.47 KiB (1%) | 3 |
| `["sort", "mergesort", "(\"sortperm! forwards\", \"descending\")"]` | 1.009 ms (30%) | 0.000 ns | 195.47 KiB (1%) | 3 |
| `["sort", "mergesort", "(\"sortperm! forwards\", \"ones\")"]` | 823.413 μs (30%) | 0.000 ns | 195.55 KiB (1%) | 4 |
| `["sort", "mergesort", "(\"sortperm! forwards\", \"random\")"]` | 4.521 ms (30%) | 0.000 ns | 195.55 KiB (1%) | 4 |
| `["sort", "mergesort", "(\"sortperm! reverse\", \"ascending\")"]` | 1.014 ms (30%) | 0.000 ns | 195.47 KiB (1%) | 3 |
| `["sort", "mergesort", "(\"sortperm! reverse\", \"descending\")"]` | 734.001 μs (30%) | 0.000 ns | 195.47 KiB (1%) | 3 |
| `["sort", "mergesort", "(\"sortperm! reverse\", \"ones\")"]` | 896.154 μs (30%) | 0.000 ns | 195.55 KiB (1%) | 4 |
| `["sort", "mergesort", "(\"sortperm! reverse\", \"random\")"]` | 4.621 ms (30%) | 0.000 ns | 195.55 KiB (1%) | 4 |
| `["sort", "quicksort", "(\"sort forwards\", \"ascending\")"]` | 371.948 μs (30%) | 0.000 ns | 390.70 KiB (1%) | 2 |
| `["sort", "quicksort", "(\"sort forwards\", \"descending\")"]` | 393.566 μs (30%) | 0.000 ns | 390.70 KiB (1%) | 2 |
| `["sort", "quicksort", "(\"sort forwards\", \"ones\")"]` | 562.122 μs (30%) | 0.000 ns | 390.70 KiB (1%) | 2 |
| `["sort", "quicksort", "(\"sort forwards\", \"random\")"]` | 2.752 ms (30%) | 0.000 ns | 390.70 KiB (1%) | 2 |
| `["sort", "quicksort", "(\"sort reverse\", \"ascending\")"]` | 380.992 μs (30%) | 0.000 ns | 390.70 KiB (1%) | 2 |
| `["sort", "quicksort", "(\"sort reverse\", \"descending\")"]` | 366.872 μs (30%) | 0.000 ns | 390.70 KiB (1%) | 2 |
| `["sort", "quicksort", "(\"sort reverse\", \"ones\")"]` | 583.988 μs (30%) | 0.000 ns | 390.70 KiB (1%) | 2 |
| `["sort", "quicksort", "(\"sort reverse\", \"random\")"]` | 2.774 ms (30%) | 0.000 ns | 390.70 KiB (1%) | 2 |
| `["sort", "quicksort", "(\"sort! forwards\", \"ascending\")"]` | 314.558 μs (30%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["sort", "quicksort", "(\"sort! forwards\", \"descending\")"]` | 334.688 μs (30%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["sort", "quicksort", "(\"sort! forwards\", \"ones\")"]` | 505.452 μs (30%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["sort", "quicksort", "(\"sort! forwards\", \"random\")"]` | 2.693 ms (30%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["sort", "quicksort", "(\"sort! reverse\", \"ascending\")"]` | 323.617 μs (30%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["sort", "quicksort", "(\"sort! reverse\", \"descending\")"]` | 308.973 μs (30%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["sort", "quicksort", "(\"sort! reverse\", \"ones\")"]` | 527.046 μs (30%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["sort", "quicksort", "(\"sort! reverse\", \"random\")"]` | 2.716 ms (30%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["sort", "quicksort", "(\"sortperm forwards\", \"ascending\")"]` | 796.522 μs (30%) | 0.000 ns | 390.72 KiB (1%) | 3 |
| `["sort", "quicksort", "(\"sortperm forwards\", \"descending\")"]` | 834.332 μs (30%) | 0.000 ns | 390.72 KiB (1%) | 3 |
| `["sort", "quicksort", "(\"sortperm forwards\", \"ones\")"]` | 973.366 μs (30%) | 0.000 ns | 390.72 KiB (1%) | 3 |
| `["sort", "quicksort", "(\"sortperm forwards\", \"random\")"]` | 4.085 ms (30%) | 0.000 ns | 390.72 KiB (1%) | 3 |
| `["sort", "quicksort", "(\"sortperm reverse\", \"ascending\")"]` | 788.955 μs (30%) | 0.000 ns | 390.72 KiB (1%) | 3 |
| `["sort", "quicksort", "(\"sortperm reverse\", \"descending\")"]` | 756.558 μs (30%) | 0.000 ns | 390.72 KiB (1%) | 3 |
| `["sort", "quicksort", "(\"sortperm reverse\", \"ones\")"]` | 859.563 μs (30%) | 0.000 ns | 390.72 KiB (1%) | 3 |
| `["sort", "quicksort", "(\"sortperm reverse\", \"random\")"]` | 4.073 ms (30%) | 0.000 ns | 390.72 KiB (1%) | 3 |
| `["sort", "quicksort", "(\"sortperm! forwards\", \"ascending\")"]` | 758.222 μs (30%) | 0.000 ns | 16 bytes (1%) | 1 |
| `["sort", "quicksort", "(\"sortperm! forwards\", \"descending\")"]` | 796.826 μs (30%) | 0.000 ns | 16 bytes (1%) | 1 |
| `["sort", "quicksort", "(\"sortperm! forwards\", \"ones\")"]` | 944.267 μs (30%) | 0.000 ns | 16 bytes (1%) | 1 |
| `["sort", "quicksort", "(\"sortperm! forwards\", \"random\")"]` | 4.050 ms (30%) | 0.000 ns | 16 bytes (1%) | 1 |
| `["sort", "quicksort", "(\"sortperm! reverse\", \"ascending\")"]` | 759.590 μs (30%) | 0.000 ns | 16 bytes (1%) | 1 |
| `["sort", "quicksort", "(\"sortperm! reverse\", \"descending\")"]` | 726.035 μs (30%) | 0.000 ns | 16 bytes (1%) | 1 |
| `["sort", "quicksort", "(\"sortperm! reverse\", \"ones\")"]` | 830.988 μs (30%) | 0.000 ns | 16 bytes (1%) | 1 |
| `["sort", "quicksort", "(\"sortperm! reverse\", \"random\")"]` | 4.040 ms (30%) | 0.000 ns | 16 bytes (1%) | 1 |
| `["sparse", "arithmetic", "(\"unary minus\", (20000, 20000))"]` | 11.073 ms (30%) | 0.000 ns | 61.18 MiB (1%) | 6 |
| `["sparse", "arithmetic", "(\"unary minus\", (600, 600))"]` | 8.451 μs (30%) | 0.000 ns | 60.28 KiB (1%) | 5 |
| `["sparse", "constructors", "(\"Bidiagonal\", 10)"]` | 150.000 ns (5%) | 0.000 ns | 656 bytes (1%) | 3 |
| `["sparse", "constructors", "(\"Bidiagonal\", 100)"]` | 330.000 ns (5%) | 0.000 ns | 4.41 KiB (1%) | 3 |
| `["sparse", "constructors", "(\"Bidiagonal\", 1000)"]` | 4.824 μs (5%) | 0.000 ns | 39.50 KiB (1%) | 3 |
| `["sparse", "constructors", "(\"Diagonal\", 10)"]` | 145.000 ns (5%) | 0.000 ns | 496 bytes (1%) | 3 |
| `["sparse", "constructors", "(\"Diagonal\", 100)"]` | 284.000 ns (5%) | 0.000 ns | 2.63 KiB (1%) | 3 |
| `["sparse", "constructors", "(\"Diagonal\", 1000)"]` | 4.040 μs (5%) | 0.000 ns | 23.88 KiB (1%) | 3 |
| `["sparse", "constructors", "(\"IJV\", 10)"]` | 128.000 ns (5%) | 0.000 ns | 256 bytes (1%) | 3 |
| `["sparse", "constructors", "(\"IJV\", 100)"]` | 640.000 ns (5%) | 0.000 ns | 2.31 KiB (1%) | 10 |
| `["sparse", "constructors", "(\"IJV\", 1000)"]` | 7.935 μs (5%) | 0.000 ns | 27.02 KiB (1%) | 12 |
| `["sparse", "constructors", "(\"IV\", 10)"]` | 125.000 ns (5%) | 0.000 ns | 192 bytes (1%) | 3 |
| `["sparse", "constructors", "(\"IV\", 100)"]` | 366.000 ns (5%) | 0.000 ns | 560 bytes (1%) | 8 |
| `["sparse", "constructors", "(\"IV\", 1000)"]` | 2.264 μs (5%) | 0.000 ns | 4.44 KiB (1%) | 8 |
| `["sparse", "constructors", "(\"SymTridiagonal\", 10)"]` | 149.000 ns (5%) | 0.000 ns | 784 bytes (1%) | 3 |
| `["sparse", "constructors", "(\"SymTridiagonal\", 100)"]` | 909.000 ns (5%) | 0.000 ns | 5.88 KiB (1%) | 3 |
| `["sparse", "constructors", "(\"SymTridiagonal\", 1000)"]` | 6.912 μs (5%) | 0.000 ns | 55.03 KiB (1%) | 5 |
| `["sparse", "constructors", "(\"Tridiagonal\", 10)"]` | 150.000 ns (5%) | 0.000 ns | 784 bytes (1%) | 3 |
| `["sparse", "constructors", "(\"Tridiagonal\", 100)"]` | 926.000 ns (5%) | 0.000 ns | 5.88 KiB (1%) | 3 |
| `["sparse", "constructors", "(\"Tridiagonal\", 1000)"]` | 6.779 μs (5%) | 0.000 ns | 55.03 KiB (1%) | 5 |
| `["sparse", "index", "(\"spmat\", \"OneTo\", 10)"]` | 186.000 ns (30%) | 0.000 ns | 912 bytes (1%) | 3 |
| `["sparse", "index", "(\"spmat\", \"OneTo\", 100)"]` | 2.369 μs (30%) | 0.000 ns | 17.38 KiB (1%) | 3 |
| `["sparse", "index", "(\"spmat\", \"OneTo\", 1000)"]` | 59.277 μs (30%) | 0.000 ns | 501.16 KiB (1%) | 5 |
| `["sparse", "index", "(\"spmat\", \"array\", 10)"]` | 1.166 μs (30%) | 0.000 ns | 1.84 KiB (1%) | 10 |
| `["sparse", "index", "(\"spmat\", \"array\", 100)"]` | 38.403 μs (30%) | 0.000 ns | 22.02 KiB (1%) | 10 |
| `["sparse", "index", "(\"spmat\", \"array\", 1000)"]` | 1.186 ms (30%) | 0.000 ns | 544.55 KiB (1%) | 12 |
| `["sparse", "index", "(\"spmat\", \"col\", \"OneTo\", 10)"]` | 102.000 ns (30%) | 0.000 ns | 224 bytes (1%) | 2 |
| `["sparse", "index", "(\"spmat\", \"col\", \"OneTo\", 100)"]` | 114.000 ns (30%) | 0.000 ns | 352 bytes (1%) | 2 |
| `["sparse", "index", "(\"spmat\", \"col\", \"OneTo\", 1000)"]` | 138.000 ns (30%) | 0.000 ns | 800 bytes (1%) | 2 |
| `["sparse", "index", "(\"spmat\", \"col\", \"array\", 10)"]` | 595.000 ns (30%) | 0.000 ns | 1.22 KiB (1%) | 11 |
| `["sparse", "index", "(\"spmat\", \"col\", \"array\", 100)"]` | 1.785 μs (30%) | 0.000 ns | 3.61 KiB (1%) | 11 |
| `["sparse", "index", "(\"spmat\", \"col\", \"array\", 1000)"]` | 29.292 μs (30%) | 0.000 ns | 25.81 KiB (1%) | 11 |
| `["sparse", "index", "(\"spmat\", \"col\", \"logical\", 10)"]` | 261.000 ns (30%) | 0.000 ns | 672 bytes (1%) | 6 |
| `["sparse", "index", "(\"spmat\", \"col\", \"logical\", 100)"]` | 473.000 ns (30%) | 0.000 ns | 1.88 KiB (1%) | 6 |
| `["sparse", "index", "(\"spmat\", \"col\", \"logical\", 1000)"]` | 3.537 μs (30%) | 0.000 ns | 12.53 KiB (1%) | 6 |
| `["sparse", "index", "(\"spmat\", \"col\", \"range\", 10)"]` | 105.000 ns (30%) | 0.000 ns | 224 bytes (1%) | 2 |
| `["sparse", "index", "(\"spmat\", \"col\", \"range\", 100)"]` | 118.000 ns (30%) | 0.000 ns | 352 bytes (1%) | 2 |
| `["sparse", "index", "(\"spmat\", \"col\", \"range\", 1000)"]` | 143.000 ns (30%) | 0.000 ns | 800 bytes (1%) | 2 |
| `["sparse", "index", "(\"spmat\", \"integer\", 10)"]` | 28.000 ns (30%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["sparse", "index", "(\"spmat\", \"integer\", 100)"]` | 29.000 ns (30%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["sparse", "index", "(\"spmat\", \"integer\", 1000)"]` | 30.000 ns (30%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["sparse", "index", "(\"spmat\", \"logical\", 10)"]` | 341.000 ns (30%) | 0.000 ns | 832 bytes (1%) | 6 |
| `["sparse", "index", "(\"spmat\", \"logical\", 100)"]` | 6.844 μs (30%) | 0.000 ns | 7.47 KiB (1%) | 6 |
| `["sparse", "index", "(\"spmat\", \"logical\", 1000)"]` | 136.870 μs (30%) | 0.000 ns | 140.59 KiB (1%) | 8 |
| `["sparse", "index", "(\"spmat\", \"range\", 10)"]` | 187.000 ns (30%) | 0.000 ns | 912 bytes (1%) | 3 |
| `["sparse", "index", "(\"spmat\", \"range\", 100)"]` | 2.420 μs (30%) | 0.000 ns | 17.38 KiB (1%) | 3 |
| `["sparse", "index", "(\"spmat\", \"range\", 1000)"]` | 57.964 μs (30%) | 0.000 ns | 501.16 KiB (1%) | 5 |
| `["sparse", "index", "(\"spmat\", \"row\", \"OneTo\", 10)"]` | 246.000 ns (30%) | 0.000 ns | 416 bytes (1%) | 6 |
| `["sparse", "index", "(\"spmat\", \"row\", \"OneTo\", 100)"]` | 791.000 ns (30%) | 0.000 ns | 704 bytes (1%) | 8 |
| `["sparse", "index", "(\"spmat\", \"row\", \"OneTo\", 1000)"]` | 13.494 μs (30%) | 0.000 ns | 1.22 KiB (1%) | 10 |
| `["sparse", "index", "(\"spmat\", \"row\", \"array\", 10)"]` | 262.000 ns (30%) | 0.000 ns | 416 bytes (1%) | 6 |
| `["sparse", "index", "(\"spmat\", \"row\", \"array\", 100)"]` | 807.000 ns (30%) | 0.000 ns | 416 bytes (1%) | 6 |
| `["sparse", "index", "(\"spmat\", \"row\", \"array\", 1000)"]` | 16.461 μs (30%) | 0.000 ns | 1.22 KiB (1%) | 10 |
| `["sparse", "index", "(\"spmat\", \"row\", \"logical\", 10)"]` | 221.000 ns (30%) | 0.000 ns | 384 bytes (1%) | 5 |
| `["sparse", "index", "(\"spmat\", \"row\", \"logical\", 100)"]` | 679.000 ns (30%) | 0.000 ns | 960 bytes (1%) | 7 |
| `["sparse", "index", "(\"spmat\", \"row\", \"logical\", 1000)"]` | 5.601 μs (30%) | 0.000 ns | 4.69 KiB (1%) | 9 |
| `["sparse", "index", "(\"spmat\", \"row\", \"range\", 10)"]` | 251.000 ns (30%) | 0.000 ns | 416 bytes (1%) | 6 |
| `["sparse", "index", "(\"spmat\", \"row\", \"range\", 100)"]` | 860.000 ns (30%) | 0.000 ns | 704 bytes (1%) | 8 |
| `["sparse", "index", "(\"spmat\", \"row\", \"range\", 1000)"]` | 12.774 μs (30%) | 0.000 ns | 1.22 KiB (1%) | 10 |
| `["sparse", "index", "(\"spmat\", \"splogical\", 10)"]` | 354.000 ns (30%) | 0.000 ns | 160 bytes (1%) | 2 |
| `["sparse", "index", "(\"spmat\", \"splogical\", 100)"]` | 24.504 μs (30%) | 0.000 ns | 160 bytes (1%) | 2 |
| `["sparse", "index", "(\"spmat\", \"splogical\", 1000)"]` | 4.030 ms (30%) | 0.000 ns | 320 bytes (1%) | 2 |
| `["sparse", "index", "(\"spvec\", \"array\", 1000)"]` | 29.600 μs (30%) | 0.000 ns | 26.30 KiB (1%) | 12 |
| `["sparse", "index", "(\"spvec\", \"array\", 10000)"]` | 725.318 μs (30%) | 0.000 ns | 239.83 KiB (1%) | 15 |
| `["sparse", "index", "(\"spvec\", \"array\", 100000)"]` | 9.544 ms (30%) | 0.000 ns | 2.30 MiB (1%) | 15 |
| `["sparse", "index", "(\"spvec\", \"integer\", 1000)"]` | 30.000 ns (30%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["sparse", "index", "(\"spvec\", \"integer\", 10000)"]` | 32.000 ns (30%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["sparse", "index", "(\"spvec\", \"integer\", 100000)"]` | 32.000 ns (30%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["sparse", "index", "(\"spvec\", \"logical\", 1000)"]` | 2.851 μs (30%) | 0.000 ns | 4.81 KiB (1%) | 6 |
| `["sparse", "index", "(\"spvec\", \"logical\", 10000)"]` | 63.077 μs (30%) | 0.000 ns | 40.86 KiB (1%) | 7 |
| `["sparse", "index", "(\"spvec\", \"logical\", 100000)"]` | 609.460 μs (30%) | 0.000 ns | 393.08 KiB (1%) | 7 |
| `["sparse", "index", "(\"spvec\", \"range\", 1000)"]` | 146.000 ns (30%) | 0.000 ns | 800 bytes (1%) | 2 |
| `["sparse", "index", "(\"spvec\", \"range\", 10000)"]` | 254.000 ns (30%) | 0.000 ns | 1.97 KiB (1%) | 2 |
| `["sparse", "index", "(\"spvec\", \"range\", 100000)"]` | 1.003 μs (30%) | 0.000 ns | 5.13 KiB (1%) | 2 |
| `["sparse", "matmul", "(\"A_mul_B!\", \"dense 4000x40, sparse 40x40 -> dense 4000x40\")"]` | 545.436 μs (30%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["sparse", "matmul", "(\"A_mul_B!\", \"dense 400x40, sparse 40x400 -> dense 400x400\")"]` | 348.503 μs (30%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["sparse", "matmul", "(\"A_mul_B!\", \"dense 400x400, sparse 400x40 -> dense 400x40\")"]` | 39.519 μs (30%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["sparse", "matmul", "(\"A_mul_B!\", \"dense 400x400, sparse 400x400 -> dense 400x400\")"]` | 465.203 μs (30%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["sparse", "matmul", "(\"A_mul_B!\", \"dense 40x40, sparse 40x4000 -> dense 40x4000\")"]` | 570.459 μs (30%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["sparse", "matmul", "(\"A_mul_B!\", \"dense 40x400, sparse 400x4000 -> dense 40x4000\")"]` | 607.698 μs (30%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["sparse", "matmul", "(\"A_mul_B!\", \"dense 40x4000, sparse 4000x400 -> dense 40x400\")"]` | 82.754 μs (30%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["sparse", "matmul", "(\"A_mul_B!\", \"dense 40x4000, sparse 4000x4000 -> dense 40x4000\")"]` | 911.783 μs (30%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["sparse", "matmul", "(\"A_mul_B!\", \"sparse 4000x40, dense 40x40 -> dense 4000x40\")"]` | 150.740 μs (30%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["sparse", "matmul", "(\"A_mul_B!\", \"sparse 4000x400, dense 400x40 -> dense 4000x40\")"]` | 453.598 μs (30%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["sparse", "matmul", "(\"A_mul_B!\", \"sparse 4000x4000, dense 4000x40 -> dense 4000x40\")"]` | 3.763 ms (30%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["sparse", "matmul", "(\"A_mul_B!\", \"sparse 400x40, dense 40x400 -> dense 400x400\")"]` | 383.811 μs (30%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["sparse", "matmul", "(\"A_mul_B!\", \"sparse 400x400, dense 400x400 -> dense 400x400\")"]` | 3.204 ms (30%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["sparse", "matmul", "(\"A_mul_B!\", \"sparse 400x4000, dense 4000x40 -> dense 400x40\")"]` | 3.567 ms (30%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["sparse", "matmul", "(\"A_mul_B!\", \"sparse 40x40, dense 40x4000 -> dense 40x4000\")"]` | 2.366 ms (30%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["sparse", "matmul", "(\"A_mul_B!\", \"sparse 40x400, dense 400x400 -> dense 40x400\")"]` | 3.067 ms (30%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["sparse", "matmul", "(\"A_mul_B\", \"dense 500x5, sparse 5x5 -> dense 500x5\")"]` | 3.167 μs (30%) | 0.000 ns | 19.64 KiB (1%) | 2 |
| `["sparse", "matmul", "(\"A_mul_B\", \"dense 50x5, sparse 5x50 -> dense 50x50\")"]` | 3.747 μs (30%) | 0.000 ns | 19.64 KiB (1%) | 2 |
| `["sparse", "matmul", "(\"A_mul_B\", \"dense 50x50, sparse 50x5 -> dense 50x5\")"]` | 564.000 ns (30%) | 0.000 ns | 2.13 KiB (1%) | 1 |
| `["sparse", "matmul", "(\"A_mul_B\", \"dense 50x50, sparse 50x50 -> dense 50x50\")"]` | 4.145 μs (30%) | 0.000 ns | 19.64 KiB (1%) | 2 |
| `["sparse", "matmul", "(\"A_mul_B\", \"dense 5x5, sparse 5x500 -> dense 5x500\")"]` | 13.392 μs (30%) | 0.000 ns | 19.64 KiB (1%) | 2 |
| `["sparse", "matmul", "(\"A_mul_B\", \"dense 5x50, sparse 50x500 -> dense 5x500\")"]` | 14.608 μs (30%) | 0.000 ns | 19.64 KiB (1%) | 2 |
| `["sparse", "matmul", "(\"A_mul_B\", \"dense 5x500, sparse 500x50 -> dense 5x50\")"]` | 1.474 μs (30%) | 0.000 ns | 2.13 KiB (1%) | 1 |
| `["sparse", "matmul", "(\"A_mul_B\", \"dense 5x500, sparse 500x500 -> dense 5x500\")"]` | 14.474 μs (30%) | 0.000 ns | 19.64 KiB (1%) | 2 |
| `["sparse", "matmul", "(\"A_mul_B\", \"sparse 500x5, dense 5x5 -> dense 500x5\")"]` | 3.328 μs (30%) | 0.000 ns | 39.14 KiB (1%) | 2 |
| `["sparse", "matmul", "(\"A_mul_B\", \"sparse 500x50, dense 50x5 -> dense 500x5\")"]` | 4.799 μs (30%) | 0.000 ns | 39.14 KiB (1%) | 2 |
| `["sparse", "matmul", "(\"A_mul_B\", \"sparse 500x500, dense 500x5 -> dense 500x5\")"]` | 17.972 μs (30%) | 0.000 ns | 39.14 KiB (1%) | 2 |
| `["sparse", "matmul", "(\"A_mul_B\", \"sparse 50x5, dense 5x50 -> dense 50x50\")"]` | 4.918 μs (30%) | 0.000 ns | 39.14 KiB (1%) | 2 |
| `["sparse", "matmul", "(\"A_mul_B\", \"sparse 50x50, dense 50x50 -> dense 50x50\")"]` | 18.603 μs (30%) | 0.000 ns | 39.14 KiB (1%) | 2 |
| `["sparse", "matmul", "(\"A_mul_B\", \"sparse 50x500, dense 500x5 -> dense 50x5\")"]` | 15.640 μs (30%) | 0.000 ns | 4.06 KiB (1%) | 1 |
| `["sparse", "matmul", "(\"A_mul_B\", \"sparse 5x5, dense 5x500 -> dense 5x500\")"]` | 19.251 μs (30%) | 0.000 ns | 39.14 KiB (1%) | 2 |
| `["sparse", "matmul", "(\"A_mul_B\", \"sparse 5x50, dense 50x50 -> dense 5x50\")"]` | 15.446 μs (30%) | 0.000 ns | 4.06 KiB (1%) | 1 |
| `["sparse", "matmul", "(\"A_mul_Bc!\", \"dense 2000x20, sparse 20x20 -> dense 2000x20\")"]` | 340.860 μs (30%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["sparse", "matmul", "(\"A_mul_Bc!\", \"dense 200x20, sparse 200x20 -> dense 200x200\")"]` | 321.581 μs (30%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["sparse", "matmul", "(\"A_mul_Bc!\", \"dense 200x200, sparse 200x200 -> dense 200x200\")"]` | 330.721 μs (30%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["sparse", "matmul", "(\"A_mul_Bc!\", \"dense 200x200, sparse 20x200 -> dense 200x20\")"]` | 37.832 μs (30%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["sparse", "matmul", "(\"A_mul_Bc!\", \"dense 20x20, sparse 2000x20 -> dense 20x2000\")"]` | 368.300 μs (30%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["sparse", "matmul", "(\"A_mul_Bc!\", \"dense 20x200, sparse 2000x200 -> dense 20x2000\")"]` | 381.815 μs (30%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["sparse", "matmul", "(\"A_mul_Bc!\", \"dense 20x2000, sparse 2000x2000 -> dense 20x2000\")"]` | 413.291 μs (30%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["sparse", "matmul", "(\"A_mul_Bc!\", \"dense 20x2000, sparse 200x2000 -> dense 20x200\")"]` | 50.116 μs (30%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["sparse", "matmul", "(\"A_mul_Bc!\", \"sparse 2000x20, dense 20x20 -> dense 2000x20\")"]` | 20.533 μs (30%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["sparse", "matmul", "(\"A_mul_Bc!\", \"sparse 2000x200, dense 20x200 -> dense 2000x20\")"]` | 70.287 μs (30%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["sparse", "matmul", "(\"A_mul_Bc!\", \"sparse 2000x2000, dense 20x2000 -> dense 2000x20\")"]` | 834.870 μs (30%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["sparse", "matmul", "(\"A_mul_Bc!\", \"sparse 200x20, dense 200x20 -> dense 200x200\")"]` | 74.105 μs (30%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["sparse", "matmul", "(\"A_mul_Bc!\", \"sparse 200x200, dense 200x200 -> dense 200x200\")"]` | 763.348 μs (30%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["sparse", "matmul", "(\"A_mul_Bc!\", \"sparse 200x2000, dense 20x2000 -> dense 200x20\")"]` | 778.718 μs (30%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["sparse", "matmul", "(\"A_mul_Bc!\", \"sparse 20x20, dense 2000x20 -> dense 20x2000\")"]` | 572.693 μs (30%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["sparse", "matmul", "(\"A_mul_Bc!\", \"sparse 20x200, dense 200x200 -> dense 20x200\")"]` | 660.374 μs (30%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["sparse", "matmul", "(\"A_mul_Bc\", \"dense 500x5, sparse 5x5 -> dense 500x5\")"]` | 12.997 μs (30%) | 0.000 ns | 39.14 KiB (1%) | 2 |
| `["sparse", "matmul", "(\"A_mul_Bc\", \"dense 50x5, sparse 50x5 -> dense 50x50\")"]` | 13.481 μs (30%) | 0.000 ns | 39.14 KiB (1%) | 2 |
| `["sparse", "matmul", "(\"A_mul_Bc\", \"dense 50x50, sparse 50x50 -> dense 50x50\")"]` | 14.599 μs (30%) | 0.000 ns | 39.14 KiB (1%) | 2 |
| `["sparse", "matmul", "(\"A_mul_Bc\", \"dense 50x50, sparse 5x50 -> dense 50x5\")"]` | 1.705 μs (30%) | 0.000 ns | 4.06 KiB (1%) | 1 |
| `["sparse", "matmul", "(\"A_mul_Bc\", \"dense 5x5, sparse 500x5 -> dense 5x500\")"]` | 18.851 μs (30%) | 0.000 ns | 39.14 KiB (1%) | 2 |
| `["sparse", "matmul", "(\"A_mul_Bc\", \"dense 5x50, sparse 500x50 -> dense 5x500\")"]` | 18.936 μs (30%) | 0.000 ns | 39.14 KiB (1%) | 2 |
| `["sparse", "matmul", "(\"A_mul_Bc\", \"dense 5x500, sparse 500x500 -> dense 5x500\")"]` | 22.240 μs (30%) | 0.000 ns | 39.14 KiB (1%) | 2 |
| `["sparse", "matmul", "(\"A_mul_Bc\", \"dense 5x500, sparse 50x500 -> dense 5x50\")"]` | 3.516 μs (30%) | 0.000 ns | 4.06 KiB (1%) | 1 |
| `["sparse", "matmul", "(\"A_mul_Bc\", \"sparse 500x5, dense 5x5 -> dense 500x5\")"]` | 3.372 μs (30%) | 0.000 ns | 39.14 KiB (1%) | 2 |
| `["sparse", "matmul", "(\"A_mul_Bc\", \"sparse 500x50, dense 5x50 -> dense 500x5\")"]` | 5.195 μs (30%) | 0.000 ns | 39.14 KiB (1%) | 2 |
| `["sparse", "matmul", "(\"A_mul_Bc\", \"sparse 500x500, dense 5x500 -> dense 500x5\")"]` | 23.086 μs (30%) | 0.000 ns | 39.14 KiB (1%) | 2 |
| `["sparse", "matmul", "(\"A_mul_Bc\", \"sparse 50x5, dense 50x5 -> dense 50x50\")"]` | 5.402 μs (30%) | 0.000 ns | 39.14 KiB (1%) | 2 |
| `["sparse", "matmul", "(\"A_mul_Bc\", \"sparse 50x50, dense 50x50 -> dense 50x50\")"]` | 23.315 μs (30%) | 0.000 ns | 39.14 KiB (1%) | 2 |
| `["sparse", "matmul", "(\"A_mul_Bc\", \"sparse 50x500, dense 5x500 -> dense 50x5\")"]` | 20.289 μs (30%) | 0.000 ns | 4.06 KiB (1%) | 1 |
| `["sparse", "matmul", "(\"A_mul_Bc\", \"sparse 5x5, dense 500x5 -> dense 5x500\")"]` | 24.908 μs (30%) | 0.000 ns | 39.14 KiB (1%) | 2 |
| `["sparse", "matmul", "(\"A_mul_Bc\", \"sparse 5x50, dense 50x50 -> dense 5x50\")"]` | 20.396 μs (30%) | 0.000 ns | 4.06 KiB (1%) | 1 |
| `["sparse", "matmul", "(\"A_mul_Bt!\", \"dense 4000x40, sparse 40x40 -> dense 4000x40\")"]` | 518.056 μs (30%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["sparse", "matmul", "(\"A_mul_Bt!\", \"dense 400x40, sparse 400x40 -> dense 400x400\")"]` | 419.703 μs (30%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["sparse", "matmul", "(\"A_mul_Bt!\", \"dense 400x400, sparse 400x400 -> dense 400x400\")"]` | 470.464 μs (30%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["sparse", "matmul", "(\"A_mul_Bt!\", \"dense 400x400, sparse 40x400 -> dense 400x40\")"]` | 44.667 μs (30%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["sparse", "matmul", "(\"A_mul_Bt!\", \"dense 40x40, sparse 4000x40 -> dense 40x4000\")"]` | 784.236 μs (30%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["sparse", "matmul", "(\"A_mul_Bt!\", \"dense 40x400, sparse 4000x400 -> dense 40x4000\")"]` | 830.854 μs (30%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["sparse", "matmul", "(\"A_mul_Bt!\", \"dense 40x4000, sparse 4000x4000 -> dense 40x4000\")"]` | 882.223 μs (30%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["sparse", "matmul", "(\"A_mul_Bt!\", \"dense 40x4000, sparse 400x4000 -> dense 40x400\")"]` | 94.858 μs (30%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["sparse", "matmul", "(\"A_mul_Bt!\", \"sparse 4000x40, dense 40x40 -> dense 4000x40\")"]` | 150.465 μs (30%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["sparse", "matmul", "(\"A_mul_Bt!\", \"sparse 4000x400, dense 40x400 -> dense 4000x40\")"]` | 443.826 μs (30%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["sparse", "matmul", "(\"A_mul_Bt!\", \"sparse 4000x4000, dense 40x4000 -> dense 4000x40\")"]` | 4.564 ms (30%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["sparse", "matmul", "(\"A_mul_Bt!\", \"sparse 400x40, dense 400x40 -> dense 400x400\")"]` | 399.898 μs (30%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["sparse", "matmul", "(\"A_mul_Bt!\", \"sparse 400x400, dense 400x400 -> dense 400x400\")"]` | 3.725 ms (30%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["sparse", "matmul", "(\"A_mul_Bt!\", \"sparse 400x4000, dense 40x4000 -> dense 400x40\")"]` | 4.312 ms (30%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["sparse", "matmul", "(\"A_mul_Bt!\", \"sparse 40x40, dense 4000x40 -> dense 40x4000\")"]` | 2.642 ms (30%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["sparse", "matmul", "(\"A_mul_Bt!\", \"sparse 40x400, dense 400x400 -> dense 40x400\")"]` | 3.564 ms (30%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["sparse", "matmul", "(\"A_mul_Bt\", \"dense 500x5, sparse 5x5 -> dense 500x5\")"]` | 3.186 μs (30%) | 0.000 ns | 19.64 KiB (1%) | 2 |
| `["sparse", "matmul", "(\"A_mul_Bt\", \"dense 50x5, sparse 50x5 -> dense 50x50\")"]` | 3.508 μs (30%) | 0.000 ns | 19.64 KiB (1%) | 2 |
| `["sparse", "matmul", "(\"A_mul_Bt\", \"dense 50x50, sparse 50x50 -> dense 50x50\")"]` | 4.048 μs (30%) | 0.000 ns | 19.64 KiB (1%) | 2 |
| `["sparse", "matmul", "(\"A_mul_Bt\", \"dense 50x50, sparse 5x50 -> dense 50x5\")"]` | 699.000 ns (30%) | 0.000 ns | 2.13 KiB (1%) | 1 |
| `["sparse", "matmul", "(\"A_mul_Bt\", \"dense 5x5, sparse 500x5 -> dense 5x500\")"]` | 10.143 μs (30%) | 0.000 ns | 19.64 KiB (1%) | 2 |
| `["sparse", "matmul", "(\"A_mul_Bt\", \"dense 5x50, sparse 500x50 -> dense 5x500\")"]` | 10.595 μs (30%) | 0.000 ns | 19.64 KiB (1%) | 2 |
| `["sparse", "matmul", "(\"A_mul_Bt\", \"dense 5x500, sparse 500x500 -> dense 5x500\")"]` | 14.811 μs (30%) | 0.000 ns | 19.64 KiB (1%) | 2 |
| `["sparse", "matmul", "(\"A_mul_Bt\", \"dense 5x500, sparse 50x500 -> dense 5x50\")"]` | 2.462 μs (30%) | 0.000 ns | 2.13 KiB (1%) | 1 |
| `["sparse", "matmul", "(\"A_mul_Bt\", \"sparse 500x5, dense 5x5 -> dense 500x5\")"]` | 3.308 μs (30%) | 0.000 ns | 39.14 KiB (1%) | 2 |
| `["sparse", "matmul", "(\"A_mul_Bt\", \"sparse 500x50, dense 5x50 -> dense 500x5\")"]` | 4.820 μs (30%) | 0.000 ns | 39.14 KiB (1%) | 2 |
| `["sparse", "matmul", "(\"A_mul_Bt\", \"sparse 500x500, dense 5x500 -> dense 500x5\")"]` | 19.054 μs (30%) | 0.000 ns | 39.14 KiB (1%) | 2 |
| `["sparse", "matmul", "(\"A_mul_Bt\", \"sparse 50x5, dense 50x5 -> dense 50x50\")"]` | 4.957 μs (30%) | 0.000 ns | 39.14 KiB (1%) | 2 |
| `["sparse", "matmul", "(\"A_mul_Bt\", \"sparse 50x50, dense 50x50 -> dense 50x50\")"]` | 18.876 μs (30%) | 0.000 ns | 39.14 KiB (1%) | 2 |
| `["sparse", "matmul", "(\"A_mul_Bt\", \"sparse 50x500, dense 5x500 -> dense 50x5\")"]` | 16.302 μs (30%) | 0.000 ns | 4.06 KiB (1%) | 1 |
| `["sparse", "matmul", "(\"A_mul_Bt\", \"sparse 5x5, dense 500x5 -> dense 5x500\")"]` | 20.292 μs (30%) | 0.000 ns | 39.14 KiB (1%) | 2 |
| `["sparse", "matmul", "(\"A_mul_Bt\", \"sparse 5x50, dense 50x50 -> dense 5x50\")"]` | 15.697 μs (30%) | 0.000 ns | 4.06 KiB (1%) | 1 |
| `["sparse", "matmul", "(\"Ac_mul_B!\", \"dense 2000x20, sparse 2000x200 -> dense 20x200\")"]` | 59.410 μs (30%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["sparse", "matmul", "(\"Ac_mul_B!\", \"dense 2000x20, sparse 2000x2000 -> dense 20x2000\")"]` | 802.842 μs (30%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["sparse", "matmul", "(\"Ac_mul_B!\", \"dense 200x20, sparse 200x2000 -> dense 20x2000\")"]` | 776.396 μs (30%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["sparse", "matmul", "(\"Ac_mul_B!\", \"dense 200x200, sparse 200x20 -> dense 200x20\")"]` | 62.827 μs (30%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["sparse", "matmul", "(\"Ac_mul_B!\", \"dense 200x200, sparse 200x200 -> dense 200x200\")"]` | 568.782 μs (30%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["sparse", "matmul", "(\"Ac_mul_B!\", \"dense 20x20, sparse 20x2000 -> dense 20x2000\")"]` | 764.163 μs (30%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["sparse", "matmul", "(\"Ac_mul_B!\", \"dense 20x200, sparse 20x200 -> dense 200x200\")"]` | 540.286 μs (30%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["sparse", "matmul", "(\"Ac_mul_B!\", \"dense 20x2000, sparse 20x20 -> dense 2000x20\")"]` | 526.807 μs (30%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["sparse", "matmul", "(\"Ac_mul_B!\", \"sparse 2000x200, dense 2000x20 -> dense 200x20\")"]` | 450.304 μs (30%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["sparse", "matmul", "(\"Ac_mul_B!\", \"sparse 2000x2000, dense 2000x20 -> dense 2000x20\")"]` | 774.674 μs (30%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["sparse", "matmul", "(\"Ac_mul_B!\", \"sparse 200x20, dense 200x200 -> dense 20x200\")"]` | 417.697 μs (30%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["sparse", "matmul", "(\"Ac_mul_B!\", \"sparse 200x200, dense 200x200 -> dense 200x200\")"]` | 696.692 μs (30%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["sparse", "matmul", "(\"Ac_mul_B!\", \"sparse 200x2000, dense 200x20 -> dense 2000x20\")"]` | 140.275 μs (30%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["sparse", "matmul", "(\"Ac_mul_B!\", \"sparse 20x20, dense 20x2000 -> dense 20x2000\")"]` | 498.913 μs (30%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["sparse", "matmul", "(\"Ac_mul_B!\", \"sparse 20x200, dense 20x200 -> dense 200x200\")"]` | 143.675 μs (30%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["sparse", "matmul", "(\"Ac_mul_B!\", \"sparse 20x2000, dense 20x20 -> dense 2000x20\")"]` | 103.654 μs (30%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["sparse", "matmul", "(\"Ac_mul_B\", \"dense 500x5, sparse 500x50 -> dense 5x50\")"]` | 2.512 μs (30%) | 0.000 ns | 4.06 KiB (1%) | 1 |
| `["sparse", "matmul", "(\"Ac_mul_B\", \"dense 500x5, sparse 500x500 -> dense 5x500\")"]` | 21.781 μs (30%) | 0.000 ns | 39.14 KiB (1%) | 2 |
| `["sparse", "matmul", "(\"Ac_mul_B\", \"dense 50x5, sparse 50x500 -> dense 5x500\")"]` | 21.599 μs (30%) | 0.000 ns | 39.14 KiB (1%) | 2 |
| `["sparse", "matmul", "(\"Ac_mul_B\", \"dense 50x50, sparse 50x5 -> dense 50x5\")"]` | 2.726 μs (30%) | 0.000 ns | 4.06 KiB (1%) | 1 |
| `["sparse", "matmul", "(\"Ac_mul_B\", \"dense 50x50, sparse 50x50 -> dense 50x50\")"]` | 22.205 μs (30%) | 0.000 ns | 39.14 KiB (1%) | 2 |
| `["sparse", "matmul", "(\"Ac_mul_B\", \"dense 5x5, sparse 5x500 -> dense 5x500\")"]` | 21.377 μs (30%) | 0.000 ns | 39.14 KiB (1%) | 2 |
| `["sparse", "matmul", "(\"Ac_mul_B\", \"dense 5x50, sparse 5x50 -> dense 50x50\")"]` | 21.138 μs (30%) | 0.000 ns | 39.14 KiB (1%) | 2 |
| `["sparse", "matmul", "(\"Ac_mul_B\", \"dense 5x500, sparse 5x5 -> dense 500x5\")"]` | 22.489 μs (30%) | 0.000 ns | 39.14 KiB (1%) | 2 |
| `["sparse", "matmul", "(\"Ac_mul_B\", \"sparse 500x50, dense 500x5 -> dense 50x5\")"]` | 14.728 μs (30%) | 0.000 ns | 4.06 KiB (1%) | 1 |
| `["sparse", "matmul", "(\"Ac_mul_B\", \"sparse 500x500, dense 500x5 -> dense 500x5\")"]` | 29.409 μs (30%) | 0.000 ns | 39.14 KiB (1%) | 2 |
| `["sparse", "matmul", "(\"Ac_mul_B\", \"sparse 50x5, dense 50x50 -> dense 5x50\")"]` | 14.539 μs (30%) | 0.000 ns | 4.06 KiB (1%) | 1 |
| `["sparse", "matmul", "(\"Ac_mul_B\", \"sparse 50x50, dense 50x50 -> dense 50x50\")"]` | 21.186 μs (30%) | 0.000 ns | 39.14 KiB (1%) | 2 |
| `["sparse", "matmul", "(\"Ac_mul_B\", \"sparse 50x500, dense 50x5 -> dense 500x5\")"]` | 9.733 μs (30%) | 0.000 ns | 39.14 KiB (1%) | 2 |
| `["sparse", "matmul", "(\"Ac_mul_B\", \"sparse 5x5, dense 5x500 -> dense 5x500\")"]` | 21.460 μs (30%) | 0.000 ns | 39.14 KiB (1%) | 2 |
| `["sparse", "matmul", "(\"Ac_mul_B\", \"sparse 5x50, dense 5x50 -> dense 50x50\")"]` | 9.946 μs (30%) | 0.000 ns | 39.14 KiB (1%) | 2 |
| `["sparse", "matmul", "(\"Ac_mul_B\", \"sparse 5x500, dense 5x5 -> dense 500x5\")"]` | 8.582 μs (30%) | 0.000 ns | 39.14 KiB (1%) | 2 |
| `["sparse", "matmul", "(\"Ac_mul_Bc!\", \"dense 2000x20, sparse 2000x2000 -> dense 20x2000\")"]` | 601.536 μs (30%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["sparse", "matmul", "(\"Ac_mul_Bc!\", \"dense 2000x20, sparse 200x2000 -> dense 20x200\")"]` | 70.819 μs (30%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["sparse", "matmul", "(\"Ac_mul_Bc!\", \"dense 200x20, sparse 2000x200 -> dense 20x2000\")"]` | 562.206 μs (30%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["sparse", "matmul", "(\"Ac_mul_Bc!\", \"dense 200x200, sparse 200x200 -> dense 200x200\")"]` | 587.913 μs (30%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["sparse", "matmul", "(\"Ac_mul_Bc!\", \"dense 200x200, sparse 20x200 -> dense 200x20\")"]` | 68.420 μs (30%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["sparse", "matmul", "(\"Ac_mul_Bc!\", \"dense 20x20, sparse 2000x20 -> dense 20x2000\")"]` | 554.561 μs (30%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["sparse", "matmul", "(\"Ac_mul_Bc!\", \"dense 20x200, sparse 200x20 -> dense 200x200\")"]` | 499.309 μs (30%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["sparse", "matmul", "(\"Ac_mul_Bc!\", \"dense 20x2000, sparse 20x20 -> dense 2000x20\")"]` | 571.927 μs (30%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["sparse", "matmul", "(\"Ac_mul_Bc!\", \"sparse 2000x200, dense 20x2000 -> dense 200x20\")"]` | 706.746 μs (30%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["sparse", "matmul", "(\"Ac_mul_Bc!\", \"sparse 2000x2000, dense 20x2000 -> dense 2000x20\")"]` | 968.448 μs (30%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["sparse", "matmul", "(\"Ac_mul_Bc!\", \"sparse 200x20, dense 200x200 -> dense 20x200\")"]` | 663.271 μs (30%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["sparse", "matmul", "(\"Ac_mul_Bc!\", \"sparse 200x200, dense 200x200 -> dense 200x200\")"]` | 941.855 μs (30%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["sparse", "matmul", "(\"Ac_mul_Bc!\", \"sparse 200x2000, dense 20x200 -> dense 2000x20\")"]` | 157.296 μs (30%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["sparse", "matmul", "(\"Ac_mul_Bc!\", \"sparse 20x20, dense 2000x20 -> dense 20x2000\")"]` | 819.719 μs (30%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["sparse", "matmul", "(\"Ac_mul_Bc!\", \"sparse 20x200, dense 200x20 -> dense 200x200\")"]` | 161.324 μs (30%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["sparse", "matmul", "(\"Ac_mul_Bc!\", \"sparse 20x2000, dense 20x20 -> dense 2000x20\")"]` | 108.638 μs (30%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["sparse", "matmul", "(\"Ac_mul_Bc\", \"dense 500x5, sparse 500x500 -> dense 5x500\")"]` | 32.766 μs (30%) | 0.000 ns | 39.14 KiB (1%) | 2 |
| `["sparse", "matmul", "(\"Ac_mul_Bc\", \"dense 500x5, sparse 50x500 -> dense 5x50\")"]` | 4.980 μs (30%) | 0.000 ns | 4.06 KiB (1%) | 1 |
| `["sparse", "matmul", "(\"Ac_mul_Bc\", \"dense 50x5, sparse 500x50 -> dense 5x500\")"]` | 29.225 μs (30%) | 0.000 ns | 39.14 KiB (1%) | 2 |
| `["sparse", "matmul", "(\"Ac_mul_Bc\", \"dense 50x50, sparse 50x50 -> dense 50x50\")"]` | 20.507 μs (30%) | 0.000 ns | 39.14 KiB (1%) | 2 |
| `["sparse", "matmul", "(\"Ac_mul_Bc\", \"dense 50x50, sparse 5x50 -> dense 50x5\")"]` | 2.493 μs (30%) | 0.000 ns | 4.06 KiB (1%) | 1 |
| `["sparse", "matmul", "(\"Ac_mul_Bc\", \"dense 5x5, sparse 500x5 -> dense 5x500\")"]` | 28.716 μs (30%) | 0.000 ns | 39.14 KiB (1%) | 2 |
| `["sparse", "matmul", "(\"Ac_mul_Bc\", \"dense 5x50, sparse 50x5 -> dense 50x50\")"]` | 18.950 μs (30%) | 0.000 ns | 39.14 KiB (1%) | 2 |
| `["sparse", "matmul", "(\"Ac_mul_Bc\", \"dense 5x500, sparse 5x5 -> dense 500x5\")"]` | 19.099 μs (30%) | 0.000 ns | 39.14 KiB (1%) | 2 |
| `["sparse", "matmul", "(\"Ac_mul_Bc\", \"sparse 500x50, dense 5x500 -> dense 50x5\")"]` | 19.887 μs (30%) | 0.000 ns | 4.06 KiB (1%) | 1 |
| `["sparse", "matmul", "(\"Ac_mul_Bc\", \"sparse 500x500, dense 5x500 -> dense 500x5\")"]` | 41.373 μs (30%) | 0.000 ns | 39.14 KiB (1%) | 2 |
| `["sparse", "matmul", "(\"Ac_mul_Bc\", \"sparse 50x5, dense 50x50 -> dense 5x50\")"]` | 18.154 μs (30%) | 0.000 ns | 4.06 KiB (1%) | 1 |
| `["sparse", "matmul", "(\"Ac_mul_Bc\", \"sparse 50x50, dense 50x50 -> dense 50x50\")"]` | 32.323 μs (30%) | 0.000 ns | 39.14 KiB (1%) | 2 |
| `["sparse", "matmul", "(\"Ac_mul_Bc\", \"sparse 50x500, dense 5x50 -> dense 500x5\")"]` | 10.284 μs (30%) | 0.000 ns | 39.14 KiB (1%) | 2 |
| `["sparse", "matmul", "(\"Ac_mul_Bc\", \"sparse 5x5, dense 500x5 -> dense 5x500\")"]` | 25.816 μs (30%) | 0.000 ns | 39.14 KiB (1%) | 2 |
| `["sparse", "matmul", "(\"Ac_mul_Bc\", \"sparse 5x50, dense 50x5 -> dense 50x50\")"]` | 10.581 μs (30%) | 0.000 ns | 39.14 KiB (1%) | 2 |
| `["sparse", "matmul", "(\"Ac_mul_Bc\", \"sparse 5x500, dense 5x5 -> dense 500x5\")"]` | 8.721 μs (30%) | 0.000 ns | 39.14 KiB (1%) | 2 |
| `["sparse", "matmul", "(\"At_mul_B!\", \"dense 4000x40, sparse 4000x400 -> dense 40x400\")"]` | 293.790 μs (30%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["sparse", "matmul", "(\"At_mul_B!\", \"dense 4000x40, sparse 4000x4000 -> dense 40x4000\")"]` | 3.018 ms (30%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["sparse", "matmul", "(\"At_mul_B!\", \"dense 400x40, sparse 400x4000 -> dense 40x4000\")"]` | 2.990 ms (30%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["sparse", "matmul", "(\"At_mul_B!\", \"dense 400x400, sparse 400x40 -> dense 400x40\")"]` | 223.279 μs (30%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["sparse", "matmul", "(\"At_mul_B!\", \"dense 400x400, sparse 400x400 -> dense 400x400\")"]` | 2.895 ms (30%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["sparse", "matmul", "(\"At_mul_B!\", \"dense 40x40, sparse 40x4000 -> dense 40x4000\")"]` | 2.967 ms (30%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["sparse", "matmul", "(\"At_mul_B!\", \"dense 40x400, sparse 40x400 -> dense 400x400\")"]` | 2.881 ms (30%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["sparse", "matmul", "(\"At_mul_B!\", \"dense 40x4000, sparse 40x40 -> dense 4000x40\")"]` | 1.975 ms (30%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["sparse", "matmul", "(\"At_mul_B!\", \"sparse 4000x400, dense 4000x40 -> dense 400x40\")"]` | 2.604 ms (30%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["sparse", "matmul", "(\"At_mul_B!\", \"sparse 4000x4000, dense 4000x40 -> dense 4000x40\")"]` | 3.845 ms (30%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["sparse", "matmul", "(\"At_mul_B!\", \"sparse 400x40, dense 400x400 -> dense 40x400\")"]` | 2.392 ms (30%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["sparse", "matmul", "(\"At_mul_B!\", \"sparse 400x400, dense 400x400 -> dense 400x400\")"]` | 2.908 ms (30%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["sparse", "matmul", "(\"At_mul_B!\", \"sparse 400x4000, dense 400x40 -> dense 4000x40\")"]` | 1.121 ms (30%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["sparse", "matmul", "(\"At_mul_B!\", \"sparse 40x40, dense 40x4000 -> dense 40x4000\")"]` | 2.495 ms (30%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["sparse", "matmul", "(\"At_mul_B!\", \"sparse 40x400, dense 40x400 -> dense 400x400\")"]` | 614.427 μs (30%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["sparse", "matmul", "(\"At_mul_B!\", \"sparse 40x4000, dense 40x40 -> dense 4000x40\")"]` | 417.149 μs (30%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["sparse", "matmul", "(\"At_mul_B\", \"dense 500x5, sparse 500x50 -> dense 5x50\")"]` | 1.643 μs (30%) | 0.000 ns | 2.13 KiB (1%) | 1 |
| `["sparse", "matmul", "(\"At_mul_B\", \"dense 500x5, sparse 500x500 -> dense 5x500\")"]` | 23.026 μs (30%) | 0.000 ns | 19.64 KiB (1%) | 2 |
| `["sparse", "matmul", "(\"At_mul_B\", \"dense 50x5, sparse 50x500 -> dense 5x500\")"]` | 23.404 μs (30%) | 0.000 ns | 19.64 KiB (1%) | 2 |
| `["sparse", "matmul", "(\"At_mul_B\", \"dense 50x50, sparse 50x5 -> dense 50x5\")"]` | 1.720 μs (30%) | 0.000 ns | 2.13 KiB (1%) | 1 |
| `["sparse", "matmul", "(\"At_mul_B\", \"dense 50x50, sparse 50x50 -> dense 50x50\")"]` | 14.396 μs (30%) | 0.000 ns | 19.64 KiB (1%) | 2 |
| `["sparse", "matmul", "(\"At_mul_B\", \"dense 5x5, sparse 5x500 -> dense 5x500\")"]` | 22.146 μs (30%) | 0.000 ns | 19.64 KiB (1%) | 2 |
| `["sparse", "matmul", "(\"At_mul_B\", \"dense 5x50, sparse 5x50 -> dense 50x50\")"]` | 13.585 μs (30%) | 0.000 ns | 19.64 KiB (1%) | 2 |
| `["sparse", "matmul", "(\"At_mul_B\", \"dense 5x500, sparse 5x5 -> dense 500x5\")"]` | 14.774 μs (30%) | 0.000 ns | 19.64 KiB (1%) | 2 |
| `["sparse", "matmul", "(\"At_mul_B\", \"sparse 500x50, dense 500x5 -> dense 50x5\")"]` | 13.216 μs (30%) | 0.000 ns | 4.06 KiB (1%) | 1 |
| `["sparse", "matmul", "(\"At_mul_B\", \"sparse 500x500, dense 500x5 -> dense 500x5\")"]` | 18.922 μs (30%) | 0.000 ns | 39.14 KiB (1%) | 2 |
| `["sparse", "matmul", "(\"At_mul_B\", \"sparse 50x5, dense 50x50 -> dense 5x50\")"]` | 12.305 μs (30%) | 0.000 ns | 4.06 KiB (1%) | 1 |
| `["sparse", "matmul", "(\"At_mul_B\", \"sparse 50x50, dense 50x50 -> dense 50x50\")"]` | 19.417 μs (30%) | 0.000 ns | 39.14 KiB (1%) | 2 |
| `["sparse", "matmul", "(\"At_mul_B\", \"sparse 50x500, dense 50x5 -> dense 500x5\")"]` | 8.984 μs (30%) | 0.000 ns | 39.14 KiB (1%) | 2 |
| `["sparse", "matmul", "(\"At_mul_B\", \"sparse 5x5, dense 5x500 -> dense 5x500\")"]` | 19.946 μs (30%) | 0.000 ns | 39.14 KiB (1%) | 2 |
| `["sparse", "matmul", "(\"At_mul_B\", \"sparse 5x50, dense 5x50 -> dense 50x50\")"]` | 9.245 μs (30%) | 0.000 ns | 39.14 KiB (1%) | 2 |
| `["sparse", "matmul", "(\"At_mul_B\", \"sparse 5x500, dense 5x5 -> dense 500x5\")"]` | 7.844 μs (30%) | 0.000 ns | 39.14 KiB (1%) | 2 |
| `["sparse", "matmul", "(\"At_mul_Bt!\", \"dense 4000x40, sparse 4000x4000 -> dense 40x4000\")"]` | 1.659 ms (30%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["sparse", "matmul", "(\"At_mul_Bt!\", \"dense 4000x40, sparse 400x4000 -> dense 40x400\")"]` | 180.942 μs (30%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["sparse", "matmul", "(\"At_mul_Bt!\", \"dense 400x40, sparse 4000x400 -> dense 40x4000\")"]` | 1.513 ms (30%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["sparse", "matmul", "(\"At_mul_Bt!\", \"dense 400x400, sparse 400x400 -> dense 400x400\")"]` | 1.869 ms (30%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["sparse", "matmul", "(\"At_mul_Bt!\", \"dense 400x400, sparse 40x400 -> dense 400x40\")"]` | 217.991 μs (30%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["sparse", "matmul", "(\"At_mul_Bt!\", \"dense 40x40, sparse 4000x40 -> dense 40x4000\")"]` | 1.393 ms (30%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["sparse", "matmul", "(\"At_mul_Bt!\", \"dense 40x400, sparse 400x40 -> dense 400x400\")"]` | 1.236 ms (30%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["sparse", "matmul", "(\"At_mul_Bt!\", \"dense 40x4000, sparse 40x40 -> dense 4000x40\")"]` | 1.578 ms (30%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["sparse", "matmul", "(\"At_mul_Bt!\", \"sparse 4000x400, dense 40x4000 -> dense 400x40\")"]` | 3.781 ms (30%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["sparse", "matmul", "(\"At_mul_Bt!\", \"sparse 4000x4000, dense 40x4000 -> dense 4000x40\")"]` | 5.000 ms (30%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["sparse", "matmul", "(\"At_mul_Bt!\", \"sparse 400x40, dense 400x400 -> dense 40x400\")"]` | 3.508 ms (30%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["sparse", "matmul", "(\"At_mul_Bt!\", \"sparse 400x400, dense 400x400 -> dense 400x400\")"]` | 4.413 ms (30%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["sparse", "matmul", "(\"At_mul_Bt!\", \"sparse 400x4000, dense 40x400 -> dense 4000x40\")"]` | 1.671 ms (30%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["sparse", "matmul", "(\"At_mul_Bt!\", \"sparse 40x40, dense 4000x40 -> dense 40x4000\")"]` | 3.243 ms (30%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["sparse", "matmul", "(\"At_mul_Bt!\", \"sparse 40x400, dense 400x40 -> dense 400x400\")"]` | 783.884 μs (30%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["sparse", "matmul", "(\"At_mul_Bt!\", \"sparse 40x4000, dense 40x40 -> dense 4000x40\")"]` | 629.600 μs (30%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["sparse", "matmul", "(\"At_mul_Bt\", \"dense 500x5, sparse 500x500 -> dense 5x500\")"]` | 16.019 μs (30%) | 0.000 ns | 19.64 KiB (1%) | 2 |
| `["sparse", "matmul", "(\"At_mul_Bt\", \"dense 500x5, sparse 50x500 -> dense 5x50\")"]` | 2.438 μs (30%) | 0.000 ns | 2.13 KiB (1%) | 1 |
| `["sparse", "matmul", "(\"At_mul_Bt\", \"dense 50x5, sparse 500x50 -> dense 5x500\")"]` | 11.432 μs (30%) | 0.000 ns | 19.64 KiB (1%) | 2 |
| `["sparse", "matmul", "(\"At_mul_Bt\", \"dense 50x50, sparse 50x50 -> dense 50x50\")"]` | 8.885 μs (30%) | 0.000 ns | 19.64 KiB (1%) | 2 |
| `["sparse", "matmul", "(\"At_mul_Bt\", \"dense 50x50, sparse 5x50 -> dense 50x5\")"]` | 1.335 μs (30%) | 0.000 ns | 2.13 KiB (1%) | 1 |
| `["sparse", "matmul", "(\"At_mul_Bt\", \"dense 5x5, sparse 500x5 -> dense 5x500\")"]` | 11.185 μs (30%) | 0.000 ns | 19.64 KiB (1%) | 2 |
| `["sparse", "matmul", "(\"At_mul_Bt\", \"dense 5x50, sparse 50x5 -> dense 50x50\")"]` | 8.067 μs (30%) | 0.000 ns | 19.64 KiB (1%) | 2 |
| `["sparse", "matmul", "(\"At_mul_Bt\", \"dense 5x500, sparse 5x5 -> dense 500x5\")"]` | 8.099 μs (30%) | 0.000 ns | 19.64 KiB (1%) | 2 |
| `["sparse", "matmul", "(\"At_mul_Bt\", \"sparse 500x50, dense 5x500 -> dense 50x5\")"]` | 16.051 μs (30%) | 0.000 ns | 4.06 KiB (1%) | 1 |
| `["sparse", "matmul", "(\"At_mul_Bt\", \"sparse 500x500, dense 5x500 -> dense 500x5\")"]` | 35.492 μs (30%) | 0.000 ns | 39.14 KiB (1%) | 2 |
| `["sparse", "matmul", "(\"At_mul_Bt\", \"sparse 50x5, dense 50x50 -> dense 5x50\")"]` | 14.279 μs (30%) | 0.000 ns | 4.06 KiB (1%) | 1 |
| `["sparse", "matmul", "(\"At_mul_Bt\", \"sparse 50x50, dense 50x50 -> dense 50x50\")"]` | 22.174 μs (30%) | 0.000 ns | 39.14 KiB (1%) | 2 |
| `["sparse", "matmul", "(\"At_mul_Bt\", \"sparse 50x500, dense 5x50 -> dense 500x5\")"]` | 11.722 μs (30%) | 0.000 ns | 39.14 KiB (1%) | 2 |
| `["sparse", "matmul", "(\"At_mul_Bt\", \"sparse 5x5, dense 500x5 -> dense 5x500\")"]` | 22.811 μs (30%) | 0.000 ns | 39.14 KiB (1%) | 2 |
| `["sparse", "matmul", "(\"At_mul_Bt\", \"sparse 5x50, dense 50x5 -> dense 50x50\")"]` | 10.854 μs (30%) | 0.000 ns | 39.14 KiB (1%) | 2 |
| `["sparse", "matmul", "(\"At_mul_Bt\", \"sparse 5x500, dense 5x5 -> dense 500x5\")"]` | 9.597 μs (30%) | 0.000 ns | 39.14 KiB (1%) | 2 |
| `["sparse", "sparse matvec", "adjoint"]` | 154.259 ms (5%) | 0.000 ns | 76.29 MiB (1%) | 3 |
| `["sparse", "sparse matvec", "non-adjoint"]` | 146.816 ms (5%) | 0.000 ns | 76.29 MiB (1%) | 2 |
| `["sparse", "sparse solves", "least squares (default), matrix rhs"]` | 46.071 ms (5%) | 0.000 ns | 52.83 MiB (1%) | 144 |
| `["sparse", "sparse solves", "least squares (default), vector rhs"]` | 42.947 ms (5%) | 0.000 ns | 52.68 MiB (1%) | 148 |
| `["sparse", "sparse solves", "least squares (qr), matrix rhs"]` | 46.180 ms (5%) | 0.000 ns | 52.83 MiB (1%) | 144 |
| `["sparse", "sparse solves", "least squares (qr), vector rhs"]` | 43.284 ms (5%) | 0.000 ns | 52.68 MiB (1%) | 148 |
| `["sparse", "sparse solves", "square system (default), matrix rhs"]` | 34.546 ms (5%) | 0.000 ns | 20.69 MiB (1%) | 69 |
| `["sparse", "sparse solves", "square system (default), vector rhs"]` | 34.315 ms (5%) | 0.000 ns | 20.49 MiB (1%) | 69 |
| `["sparse", "sparse solves", "square system (ldlt), matrix rhs"]` | 38.868 ms (5%) | 0.000 ns | 25.65 MiB (1%) | 53 |
| `["sparse", "sparse solves", "square system (ldlt), vector rhs"]` | 42.009 ms (5%) | 0.000 ns | 25.44 MiB (1%) | 53 |
| `["sparse", "sparse solves", "square system (lu), matrix rhs"]` | 42.046 ms (5%) | 0.000 ns | 23.12 MiB (1%) | 74 |
| `["sparse", "sparse solves", "square system (lu), vector rhs"]` | 39.310 ms (5%) | 0.000 ns | 22.57 MiB (1%) | 72 |
| `["sparse", "transpose", "(\"adjoint!\", (20000, 10000))"]` | 59.368 ms (30%) | 0.000 ns | 128 bytes (1%) | 3 |
| `["sparse", "transpose", "(\"adjoint!\", (20000, 20000))"]` | 140.705 ms (30%) | 0.000 ns | 128 bytes (1%) | 3 |
| `["sparse", "transpose", "(\"adjoint!\", (600, 400))"]` | 9.532 μs (30%) | 0.000 ns | 128 bytes (1%) | 3 |
| `["sparse", "transpose", "(\"adjoint!\", (600, 600))"]` | 14.631 μs (30%) | 0.000 ns | 128 bytes (1%) | 3 |
| `["sparse", "transpose", "(\"adjoint\", (20000, 10000))"]` | 24.000 ns (30%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["sparse", "transpose", "(\"adjoint\", (20000, 20000))"]` | 24.000 ns (30%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["sparse", "transpose", "(\"adjoint\", (600, 400))"]` | 24.000 ns (30%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["sparse", "transpose", "(\"adjoint\", (600, 600))"]` | 24.000 ns (30%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["sparse", "transpose", "(\"transpose!\", (20000, 10000))"]` | 53.592 ms (30%) | 0.000 ns | 128 bytes (1%) | 3 |
| `["sparse", "transpose", "(\"transpose!\", (20000, 20000))"]` | 95.813 ms (30%) | 0.000 ns | 128 bytes (1%) | 3 |
| `["sparse", "transpose", "(\"transpose!\", (600, 400))"]` | 8.414 μs (30%) | 0.000 ns | 128 bytes (1%) | 3 |
| `["sparse", "transpose", "(\"transpose!\", (600, 600))"]` | 12.852 μs (30%) | 0.000 ns | 128 bytes (1%) | 3 |
| `["sparse", "transpose", "(\"transpose\", (20000, 10000))"]` | 24.000 ns (30%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["sparse", "transpose", "(\"transpose\", (20000, 20000))"]` | 24.000 ns (30%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["sparse", "transpose", "(\"transpose\", (600, 400))"]` | 24.000 ns (30%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["sparse", "transpose", "(\"transpose\", (600, 600))"]` | 24.000 ns (30%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["string", "==(::AbstractString, ::AbstractString)", "different length"]` | 11.500 μs (5%) | 0.000 ns | 64 bytes (1%) | 1 |
| `["string", "==(::AbstractString, ::AbstractString)", "different"]` | 17.047 ns (5%) | 0.000 ns | 64 bytes (1%) | 1 |
| `["string", "==(::AbstractString, ::AbstractString)", "equal"]` | 11.500 μs (5%) | 0.000 ns | 64 bytes (1%) | 1 |
| `["string", "==(::AbstractString, ::AbstractString)", "identical"]` | 44.449 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["string", "==(::SubString, ::String)", "different length"]` | 0.023 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["string", "==(::SubString, ::String)", "different"]` | 3.564 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["string", "==(::SubString, ::String)", "equal"]` | 44.474 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["string", "findfirst", "Char"]` | 15.644 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["string", "findfirst", "String"]` | 24.172 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["string", "join"]` | 98.284 ms (40%) | 0.000 ns | 156.27 MiB (1%) | 20 |
| `["string", "readuntil", "backtracking"]` | 662.244 μs (5%) | 0.000 ns | 105.69 KiB (1%) | 18 |
| `["string", "readuntil", "barbarian backtrack"]` | 656.477 μs (5%) | 0.000 ns | 73.67 KiB (1%) | 17 |
| `["string", "readuntil", "no backtracking"]` | 447.509 μs (5%) | 0.000 ns | 66.48 KiB (1%) | 16 |
| `["string", "readuntil", "target length 1"]` | 44.374 ns (5%) | 0.000 ns | 160 bytes (1%) | 2 |
| `["string", "readuntil", "target length 1000"]` | 2.986 μs (5%) | 0.000 ns | 64 bytes (1%) | 1 |
| `["string", "readuntil", "target length 2"]` | 32.228 ns (5%) | 0.000 ns | 64 bytes (1%) | 1 |
| `["string", "readuntil", "target length 50000"]` | 147.153 μs (5%) | 0.000 ns | 64 bytes (1%) | 1 |
| `["string", "repeat", "repeat char 1"]` | 65.093 ns (5%) | 0.000 ns | 544 bytes (1%) | 1 |
| `["string", "repeat", "repeat char 2"]` | 124.606 ns (5%) | 0.000 ns | 1.06 KiB (1%) | 1 |
| `["string", "repeat", "repeat str len 1"]` | 70.181 ns (5%) | 0.000 ns | 544 bytes (1%) | 1 |
| `["string", "repeat", "repeat str len 16"]` | 1.640 μs (5%) | 0.000 ns | 7.94 KiB (1%) | 1 |
| `["string", "replace"]` | 126.271 μs (5%) | 0.000 ns | 12.00 KiB (1%) | 4 |
| `["tuple", "index", "(\"sumelt\", \"NTuple\", 3, Float32)"]` | 24.000 ns (40%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["tuple", "index", "(\"sumelt\", \"NTuple\", 3, Float64)"]` | 24.000 ns (40%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["tuple", "index", "(\"sumelt\", \"NTuple\", 30, Float32)"]` | 54.000 ns (40%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["tuple", "index", "(\"sumelt\", \"NTuple\", 30, Float64)"]` | 54.000 ns (40%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["tuple", "index", "(\"sumelt\", \"NTuple\", 60, Float32)"]` | 90.000 ns (40%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["tuple", "index", "(\"sumelt\", \"NTuple\", 60, Float64)"]` | 90.000 ns (40%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["tuple", "index", "(\"sumelt\", \"NTuple\", 8, Float32)"]` | 28.000 ns (40%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["tuple", "index", "(\"sumelt\", \"NTuple\", 8, Float64)"]` | 28.000 ns (40%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["tuple", "index", "(\"sumelt\", \"TupleWrapper\", 3, Float32)"]` | 24.000 ns (40%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["tuple", "index", "(\"sumelt\", \"TupleWrapper\", 3, Float64)"]` | 24.000 ns (40%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["tuple", "index", "(\"sumelt\", \"TupleWrapper\", 30, Float32)"]` | 54.000 ns (40%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["tuple", "index", "(\"sumelt\", \"TupleWrapper\", 30, Float64)"]` | 54.000 ns (40%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["tuple", "index", "(\"sumelt\", \"TupleWrapper\", 60, Float32)"]` | 90.000 ns (40%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["tuple", "index", "(\"sumelt\", \"TupleWrapper\", 60, Float64)"]` | 90.000 ns (40%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["tuple", "index", "(\"sumelt\", \"TupleWrapper\", 8, Float32)"]` | 28.000 ns (40%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["tuple", "index", "(\"sumelt\", \"TupleWrapper\", 8, Float64)"]` | 28.000 ns (40%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["tuple", "linear algebra", "(\"matmat\", (16, 16), (16, 16))"]` | 1.561 μs (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["tuple", "linear algebra", "(\"matmat\", (2, 2), (2, 2))"]` | 23.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["tuple", "linear algebra", "(\"matmat\", (4, 4), (4, 4))"]` | 23.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["tuple", "linear algebra", "(\"matmat\", (8, 8), (8, 8))"]` | 82.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["tuple", "linear algebra", "(\"matvec\", (16, 16), (16,))"]` | 23.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["tuple", "linear algebra", "(\"matvec\", (2, 2), (2,))"]` | 23.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["tuple", "linear algebra", "(\"matvec\", (4, 4), (4,))"]` | 23.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["tuple", "linear algebra", "(\"matvec\", (8, 8), (8,))"]` | 23.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["tuple", "misc", "11899"]` | 0.023 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["tuple", "misc", "longtuple"]` | 5.325 μs (5%) | 0.000 ns | 4.89 KiB (1%) | 152 |
| `["tuple", "reduction", "(\"minimum\", (16, 16))"]` | 882.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["tuple", "reduction", "(\"minimum\", (16,))"]` | 69.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["tuple", "reduction", "(\"minimum\", (2, 2))"]` | 29.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["tuple", "reduction", "(\"minimum\", (2,))"]` | 23.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["tuple", "reduction", "(\"minimum\", (4, 4))"]` | 68.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["tuple", "reduction", "(\"minimum\", (4,))"]` | 30.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["tuple", "reduction", "(\"minimum\", (8, 8))"]` | 230.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["tuple", "reduction", "(\"minimum\", (8,))"]` | 43.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["tuple", "reduction", "(\"sum\", (16, 16))"]` | 47.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["tuple", "reduction", "(\"sum\", (16,))"]` | 30.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["tuple", "reduction", "(\"sum\", (2, 2))"]` | 24.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["tuple", "reduction", "(\"sum\", (2,))"]` | 24.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["tuple", "reduction", "(\"sum\", (4, 4))"]` | 28.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["tuple", "reduction", "(\"sum\", (4,))"]` | 24.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["tuple", "reduction", "(\"sum\", (8, 8))"]` | 43.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["tuple", "reduction", "(\"sum\", (8,))"]` | 27.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["tuple", "reduction", "(\"sumabs\", (16, 16))"]` | 322.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["tuple", "reduction", "(\"sumabs\", (16,))"]` | 39.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["tuple", "reduction", "(\"sumabs\", (2, 2))"]` | 25.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["tuple", "reduction", "(\"sumabs\", (2,))"]` | 23.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["tuple", "reduction", "(\"sumabs\", (4, 4))"]` | 39.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["tuple", "reduction", "(\"sumabs\", (4,))"]` | 25.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["tuple", "reduction", "(\"sumabs\", (8, 8))"]` | 95.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["tuple", "reduction", "(\"sumabs\", (8,))"]` | 30.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["union", "array", "(\"broadcast\", *, BigFloat, (false, false))"]` | 915.853 μs (5%) | 0.000 ns | 1.14 MiB (1%) | 20008 |
| `["union", "array", "(\"broadcast\", *, BigFloat, (false, true))"]` | 844.971 μs (5%) | 0.000 ns | 1.11 MiB (1%) | 17847 |
| `["union", "array", "(\"broadcast\", *, BigFloat, (true, true))"]` | 836.414 μs (5%) | 0.000 ns | 1.11 MiB (1%) | 17847 |
| `["union", "array", "(\"broadcast\", *, BigInt, (false, false))"]` | 892.097 μs (5%) | 0.000 ns | 703.48 KiB (1%) | 30008 |
| `["union", "array", "(\"broadcast\", *, BigInt, (false, true))"]` | 809.340 μs (5%) | 0.000 ns | 714.13 KiB (1%) | 26764 |
| `["union", "array", "(\"broadcast\", *, BigInt, (true, true))"]` | 774.745 μs (5%) | 0.000 ns | 714.13 KiB (1%) | 26764 |
| `["union", "array", "(\"broadcast\", *, Bool, (false, false))"]` | 39.350 μs (5%) | 0.000 ns | 1.64 KiB (1%) | 8 |
| `["union", "array", "(\"broadcast\", *, Bool, (false, true))"]` | 40.748 μs (5%) | 0.000 ns | 21.41 KiB (1%) | 13 |
| `["union", "array", "(\"broadcast\", *, Bool, (true, true))"]` | 40.371 μs (5%) | 0.000 ns | 21.41 KiB (1%) | 13 |
| `["union", "array", "(\"broadcast\", *, ComplexF64, (false, false))"]` | 42.900 μs (5%) | 0.000 ns | 156.61 KiB (1%) | 8 |
| `["union", "array", "(\"broadcast\", *, ComplexF64, (false, true))"]` | 84.043 μs (5%) | 0.000 ns | 322.88 KiB (1%) | 13 |
| `["union", "array", "(\"broadcast\", *, ComplexF64, (true, true))"]` | 82.849 μs (5%) | 0.000 ns | 322.88 KiB (1%) | 13 |
| `["union", "array", "(\"broadcast\", *, Float32, (false, false))"]` | 24.908 μs (5%) | 0.000 ns | 39.42 KiB (1%) | 8 |
| `["union", "array", "(\"broadcast\", *, Float32, (false, true))"]` | 34.902 μs (5%) | 0.000 ns | 88.50 KiB (1%) | 13 |
| `["union", "array", "(\"broadcast\", *, Float32, (true, true))"]` | 34.444 μs (5%) | 0.000 ns | 88.50 KiB (1%) | 13 |
| `["union", "array", "(\"broadcast\", *, Float64, (false, false))"]` | 24.990 μs (5%) | 0.000 ns | 78.48 KiB (1%) | 8 |
| `["union", "array", "(\"broadcast\", *, Float64, (false, true))"]` | 41.276 μs (5%) | 0.000 ns | 166.63 KiB (1%) | 13 |
| `["union", "array", "(\"broadcast\", *, Float64, (true, true))"]` | 40.160 μs (5%) | 0.000 ns | 166.63 KiB (1%) | 13 |
| `["union", "array", "(\"broadcast\", *, Int64, (false, false))"]` | 25.094 μs (5%) | 0.000 ns | 78.48 KiB (1%) | 8 |
| `["union", "array", "(\"broadcast\", *, Int64, (false, true))"]` | 44.708 μs (5%) | 0.000 ns | 166.63 KiB (1%) | 13 |
| `["union", "array", "(\"broadcast\", *, Int64, (true, true))"]` | 43.850 μs (5%) | 0.000 ns | 166.63 KiB (1%) | 13 |
| `["union", "array", "(\"broadcast\", *, Int8, (false, false))"]` | 27.847 μs (5%) | 0.000 ns | 10.22 KiB (1%) | 7 |
| `["union", "array", "(\"broadcast\", *, Int8, (false, true))"]` | 34.684 μs (5%) | 0.000 ns | 29.98 KiB (1%) | 12 |
| `["union", "array", "(\"broadcast\", *, Int8, (true, true))"]` | 33.950 μs (5%) | 0.000 ns | 29.98 KiB (1%) | 12 |
| `["union", "array", "(\"broadcast\", abs, BigFloat, false)"]` | 353.239 μs (5%) | 0.000 ns | 1.14 MiB (1%) | 20008 |
| `["union", "array", "(\"broadcast\", abs, BigFloat, true)"]` | 349.501 μs (5%) | 0.000 ns | 1.11 MiB (1%) | 17847 |
| `["union", "array", "(\"broadcast\", abs, BigInt, false)"]` | 473.469 μs (5%) | 0.000 ns | 312.30 KiB (1%) | 14972 |
| `["union", "array", "(\"broadcast\", abs, BigInt, true)"]` | 433.443 μs (5%) | 0.000 ns | 364.42 KiB (1%) | 13300 |
| `["union", "array", "(\"broadcast\", abs, Bool, false)"]` | 19.315 μs (5%) | 0.000 ns | 1.64 KiB (1%) | 8 |
| `["union", "array", "(\"broadcast\", abs, Bool, true)"]` | 17.485 μs (5%) | 0.000 ns | 21.41 KiB (1%) | 13 |
| `["union", "array", "(\"broadcast\", abs, ComplexF64, false)"]` | 146.185 μs (5%) | 0.000 ns | 78.48 KiB (1%) | 8 |
| `["union", "array", "(\"broadcast\", abs, ComplexF64, true)"]` | 145.987 μs (5%) | 0.000 ns | 166.63 KiB (1%) | 13 |
| `["union", "array", "(\"broadcast\", abs, Float32, false)"]` | 13.225 μs (5%) | 0.000 ns | 39.42 KiB (1%) | 8 |
| `["union", "array", "(\"broadcast\", abs, Float32, true)"]` | 22.431 μs (5%) | 0.000 ns | 88.50 KiB (1%) | 13 |
| `["union", "array", "(\"broadcast\", abs, Float64, false)"]` | 10.816 μs (5%) | 0.000 ns | 78.48 KiB (1%) | 8 |
| `["union", "array", "(\"broadcast\", abs, Float64, true)"]` | 27.231 μs (5%) | 0.000 ns | 166.63 KiB (1%) | 13 |
| `["union", "array", "(\"broadcast\", abs, Int64, false)"]` | 11.769 μs (5%) | 0.000 ns | 78.48 KiB (1%) | 8 |
| `["union", "array", "(\"broadcast\", abs, Int64, true)"]` | 32.855 μs (5%) | 0.000 ns | 166.63 KiB (1%) | 13 |
| `["union", "array", "(\"broadcast\", abs, Int8, false)"]` | 14.589 μs (5%) | 0.000 ns | 10.22 KiB (1%) | 7 |
| `["union", "array", "(\"broadcast\", abs, Int8, true)"]` | 24.726 μs (5%) | 0.000 ns | 29.98 KiB (1%) | 12 |
| `["union", "array", "(\"broadcast\", identity, BigFloat, false)"]` | 30.218 μs (5%) | 0.000 ns | 78.48 KiB (1%) | 8 |
| `["union", "array", "(\"broadcast\", identity, BigFloat, true)"]` | 45.584 μs (5%) | 0.000 ns | 156.81 KiB (1%) | 13 |
| `["union", "array", "(\"broadcast\", identity, BigInt, false)"]` | 29.847 μs (5%) | 0.000 ns | 78.48 KiB (1%) | 8 |
| `["union", "array", "(\"broadcast\", identity, BigInt, true)"]` | 45.357 μs (5%) | 0.000 ns | 156.81 KiB (1%) | 13 |
| `["union", "array", "(\"broadcast\", identity, Bool, false)"]` | 19.326 μs (5%) | 0.000 ns | 1.64 KiB (1%) | 8 |
| `["union", "array", "(\"broadcast\", identity, Bool, true)"]` | 17.468 μs (5%) | 0.000 ns | 21.41 KiB (1%) | 13 |
| `["union", "array", "(\"broadcast\", identity, ComplexF64, false)"]` | 13.975 μs (5%) | 0.000 ns | 156.61 KiB (1%) | 8 |
| `["union", "array", "(\"broadcast\", identity, ComplexF64, true)"]` | 55.761 μs (5%) | 0.000 ns | 322.88 KiB (1%) | 13 |
| `["union", "array", "(\"broadcast\", identity, Float32, false)"]` | 8.408 μs (5%) | 0.000 ns | 39.42 KiB (1%) | 8 |
| `["union", "array", "(\"broadcast\", identity, Float32, true)"]` | 22.322 μs (5%) | 0.000 ns | 88.50 KiB (1%) | 13 |
| `["union", "array", "(\"broadcast\", identity, Float64, false)"]` | 9.227 μs (5%) | 0.000 ns | 78.48 KiB (1%) | 8 |
| `["union", "array", "(\"broadcast\", identity, Float64, true)"]` | 28.051 μs (5%) | 0.000 ns | 166.63 KiB (1%) | 13 |
| `["union", "array", "(\"broadcast\", identity, Int64, false)"]` | 9.256 μs (5%) | 0.000 ns | 78.48 KiB (1%) | 8 |
| `["union", "array", "(\"broadcast\", identity, Int64, true)"]` | 29.980 μs (5%) | 0.000 ns | 166.63 KiB (1%) | 13 |
| `["union", "array", "(\"broadcast\", identity, Int8, false)"]` | 13.067 μs (5%) | 0.000 ns | 10.22 KiB (1%) | 7 |
| `["union", "array", "(\"broadcast\", identity, Int8, true)"]` | 17.664 μs (5%) | 0.000 ns | 29.98 KiB (1%) | 12 |
| `["union", "array", "(\"collect\", \"all\", BigFloat, false)"]` | 29.002 μs (5%) | 0.000 ns | 78.20 KiB (1%) | 2 |
| `["union", "array", "(\"collect\", \"all\", BigFloat, true)"]` | 50.035 μs (5%) | 0.000 ns | 156.41 KiB (1%) | 4 |
| `["union", "array", "(\"collect\", \"all\", BigInt, false)"]` | 23.517 μs (5%) | 0.000 ns | 78.20 KiB (1%) | 2 |
| `["union", "array", "(\"collect\", \"all\", BigInt, true)"]` | 48.286 μs (5%) | 0.000 ns | 156.41 KiB (1%) | 4 |
| `["union", "array", "(\"collect\", \"all\", Bool, false)"]` | 7.763 μs (5%) | 0.000 ns | 9.94 KiB (1%) | 1 |
| `["union", "array", "(\"collect\", \"all\", Bool, true)"]` | 14.299 μs (5%) | 0.000 ns | 29.58 KiB (1%) | 3 |
| `["union", "array", "(\"collect\", \"all\", ComplexF64, false)"]` | 13.007 μs (5%) | 0.000 ns | 156.33 KiB (1%) | 2 |
| `["union", "array", "(\"collect\", \"all\", ComplexF64, true)"]` | 49.228 μs (5%) | 0.000 ns | 322.47 KiB (1%) | 4 |
| `["union", "array", "(\"collect\", \"all\", Float32, false)"]` | 9.418 μs (5%) | 0.000 ns | 39.14 KiB (1%) | 2 |
| `["union", "array", "(\"collect\", \"all\", Float32, true)"]` | 23.821 μs (5%) | 0.000 ns | 88.09 KiB (1%) | 4 |
| `["union", "array", "(\"collect\", \"all\", Float64, false)"]` | 9.914 μs (5%) | 0.000 ns | 78.20 KiB (1%) | 2 |
| `["union", "array", "(\"collect\", \"all\", Float64, true)"]` | 25.360 μs (5%) | 0.000 ns | 166.22 KiB (1%) | 4 |
| `["union", "array", "(\"collect\", \"all\", Int64, false)"]` | 9.974 μs (5%) | 0.000 ns | 78.20 KiB (1%) | 2 |
| `["union", "array", "(\"collect\", \"all\", Int64, true)"]` | 25.117 μs (5%) | 0.000 ns | 166.22 KiB (1%) | 4 |
| `["union", "array", "(\"collect\", \"all\", Int8, false)"]` | 7.739 μs (5%) | 0.000 ns | 9.94 KiB (1%) | 1 |
| `["union", "array", "(\"collect\", \"all\", Int8, true)"]` | 14.986 μs (5%) | 0.000 ns | 29.58 KiB (1%) | 3 |
| `["union", "array", "(\"collect\", \"filter\", BigFloat, false)"]` | 110.997 μs (5%) | 0.000 ns | 256.72 KiB (1%) | 15 |
| `["union", "array", "(\"collect\", \"filter\", BigFloat, true)"]` | 114.370 μs (5%) | 0.000 ns | 192.89 KiB (1%) | 17 |
| `["union", "array", "(\"collect\", \"filter\", BigInt, false)"]` | 107.529 μs (5%) | 0.000 ns | 256.72 KiB (1%) | 15 |
| `["union", "array", "(\"collect\", \"filter\", BigInt, true)"]` | 109.082 μs (5%) | 0.000 ns | 192.89 KiB (1%) | 17 |
| `["union", "array", "(\"collect\", \"filter\", Bool, false)"]` | 70.601 μs (5%) | 0.000 ns | 32.88 KiB (1%) | 15 |
| `["union", "array", "(\"collect\", \"filter\", Bool, true)"]` | 122.303 μs (5%) | 0.000 ns | 48.77 KiB (1%) | 17 |
| `["union", "array", "(\"collect\", \"filter\", ComplexF64, false)"]` | 117.880 μs (5%) | 0.000 ns | 512.73 KiB (1%) | 15 |
| `["union", "array", "(\"collect\", \"filter\", ComplexF64, true)"]` | 158.555 μs (5%) | 0.000 ns | 409.11 KiB (1%) | 17 |
| `["union", "array", "(\"collect\", \"filter\", Float32, false)"]` | 80.489 μs (5%) | 0.000 ns | 128.69 KiB (1%) | 15 |
| `["union", "array", "(\"collect\", \"filter\", Float32, true)"]` | 127.753 μs (5%) | 0.000 ns | 120.83 KiB (1%) | 17 |
| `["union", "array", "(\"collect\", \"filter\", Float64, false)"]` | 107.095 μs (5%) | 0.000 ns | 256.72 KiB (1%) | 15 |
| `["union", "array", "(\"collect\", \"filter\", Float64, true)"]` | 152.037 μs (5%) | 0.000 ns | 216.84 KiB (1%) | 17 |
| `["union", "array", "(\"collect\", \"filter\", Int64, false)"]` | 93.031 μs (5%) | 0.000 ns | 256.72 KiB (1%) | 15 |
| `["union", "array", "(\"collect\", \"filter\", Int64, true)"]` | 141.246 μs (5%) | 0.000 ns | 216.84 KiB (1%) | 17 |
| `["union", "array", "(\"collect\", \"filter\", Int8, false)"]` | 75.491 μs (5%) | 0.000 ns | 32.88 KiB (1%) | 15 |
| `["union", "array", "(\"collect\", \"filter\", Int8, true)"]` | 123.712 μs (5%) | 0.000 ns | 48.77 KiB (1%) | 17 |
| `["union", "array", "(\"map\", *, BigFloat, (false, false))"]` | 899.040 μs (5%) | 0.000 ns | 1.14 MiB (1%) | 20002 |
| `["union", "array", "(\"map\", *, BigFloat, (false, true))"]` | 835.772 μs (5%) | 0.000 ns | 1.11 MiB (1%) | 17838 |
| `["union", "array", "(\"map\", *, BigFloat, (true, true))"]` | 832.507 μs (5%) | 0.000 ns | 1.11 MiB (1%) | 17838 |
| `["union", "array", "(\"map\", *, BigInt, (false, false))"]` | 873.831 μs (5%) | 0.000 ns | 703.20 KiB (1%) | 30002 |
| `["union", "array", "(\"map\", *, BigInt, (false, true))"]` | 790.424 μs (5%) | 0.000 ns | 713.72 KiB (1%) | 26755 |
| `["union", "array", "(\"map\", *, BigInt, (true, true))"]` | 781.186 μs (5%) | 0.000 ns | 713.72 KiB (1%) | 26755 |
| `["union", "array", "(\"map\", *, Bool, (false, false))"]` | 23.806 μs (5%) | 0.000 ns | 9.94 KiB (1%) | 1 |
| `["union", "array", "(\"map\", *, Bool, (false, true))"]` | 38.977 μs (5%) | 0.000 ns | 29.58 KiB (1%) | 3 |
| `["union", "array", "(\"map\", *, Bool, (true, true))"]` | 37.777 μs (5%) | 0.000 ns | 29.58 KiB (1%) | 3 |
| `["union", "array", "(\"map\", *, ComplexF64, (false, false))"]` | 36.072 μs (5%) | 0.000 ns | 156.33 KiB (1%) | 2 |
| `["union", "array", "(\"map\", *, ComplexF64, (false, true))"]` | 81.510 μs (5%) | 0.000 ns | 322.47 KiB (1%) | 4 |
| `["union", "array", "(\"map\", *, ComplexF64, (true, true))"]` | 79.686 μs (5%) | 0.000 ns | 322.47 KiB (1%) | 4 |
| `["union", "array", "(\"map\", *, Float32, (false, false))"]` | 24.038 μs (5%) | 0.000 ns | 39.14 KiB (1%) | 2 |
| `["union", "array", "(\"map\", *, Float32, (false, true))"]` | 42.189 μs (5%) | 0.000 ns | 88.09 KiB (1%) | 4 |
| `["union", "array", "(\"map\", *, Float32, (true, true))"]` | 42.355 μs (5%) | 0.000 ns | 88.09 KiB (1%) | 4 |
| `["union", "array", "(\"map\", *, Float64, (false, false))"]` | 24.036 μs (5%) | 0.000 ns | 78.20 KiB (1%) | 2 |
| `["union", "array", "(\"map\", *, Float64, (false, true))"]` | 47.510 μs (5%) | 0.000 ns | 166.22 KiB (1%) | 4 |
| `["union", "array", "(\"map\", *, Float64, (true, true))"]` | 47.618 μs (5%) | 0.000 ns | 166.22 KiB (1%) | 4 |
| `["union", "array", "(\"map\", *, Int64, (false, false))"]` | 29.873 μs (5%) | 0.000 ns | 78.20 KiB (1%) | 2 |
| `["union", "array", "(\"map\", *, Int64, (false, true))"]` | 47.083 μs (5%) | 0.000 ns | 166.22 KiB (1%) | 4 |
| `["union", "array", "(\"map\", *, Int64, (true, true))"]` | 46.367 μs (5%) | 0.000 ns | 166.22 KiB (1%) | 4 |
| `["union", "array", "(\"map\", *, Int8, (false, false))"]` | 32.720 μs (5%) | 0.000 ns | 9.94 KiB (1%) | 1 |
| `["union", "array", "(\"map\", *, Int8, (false, true))"]` | 48.670 μs (5%) | 0.000 ns | 29.58 KiB (1%) | 3 |
| `["union", "array", "(\"map\", *, Int8, (true, true))"]` | 51.811 μs (5%) | 0.000 ns | 29.58 KiB (1%) | 3 |
| `["union", "array", "(\"map\", abs, BigFloat, false)"]` | 354.659 μs (5%) | 0.000 ns | 1.14 MiB (1%) | 20002 |
| `["union", "array", "(\"map\", abs, BigFloat, true)"]` | 340.738 μs (5%) | 0.000 ns | 1.11 MiB (1%) | 17838 |
| `["union", "array", "(\"map\", abs, BigInt, false)"]` | 479.253 μs (5%) | 0.000 ns | 312.02 KiB (1%) | 14966 |
| `["union", "array", "(\"map\", abs, BigInt, true)"]` | 433.517 μs (5%) | 0.000 ns | 364.02 KiB (1%) | 13291 |
| `["union", "array", "(\"map\", abs, Bool, false)"]` | 12.074 μs (5%) | 0.000 ns | 9.94 KiB (1%) | 1 |
| `["union", "array", "(\"map\", abs, Bool, true)"]` | 15.499 μs (5%) | 0.000 ns | 29.58 KiB (1%) | 3 |
| `["union", "array", "(\"map\", abs, ComplexF64, false)"]` | 149.690 μs (5%) | 0.000 ns | 78.20 KiB (1%) | 2 |
| `["union", "array", "(\"map\", abs, ComplexF64, true)"]` | 147.650 μs (5%) | 0.000 ns | 166.22 KiB (1%) | 4 |
| `["union", "array", "(\"map\", abs, Float32, false)"]` | 9.362 μs (5%) | 0.000 ns | 39.14 KiB (1%) | 2 |
| `["union", "array", "(\"map\", abs, Float32, true)"]` | 21.814 μs (5%) | 0.000 ns | 88.09 KiB (1%) | 4 |
| `["union", "array", "(\"map\", abs, Float64, false)"]` | 9.982 μs (5%) | 0.000 ns | 78.20 KiB (1%) | 2 |
| `["union", "array", "(\"map\", abs, Float64, true)"]` | 27.140 μs (5%) | 0.000 ns | 166.22 KiB (1%) | 4 |
| `["union", "array", "(\"map\", abs, Int64, false)"]` | 10.851 μs (5%) | 0.000 ns | 78.20 KiB (1%) | 2 |
| `["union", "array", "(\"map\", abs, Int64, true)"]` | 26.410 μs (5%) | 0.000 ns | 166.22 KiB (1%) | 4 |
| `["union", "array", "(\"map\", abs, Int8, false)"]` | 10.639 μs (5%) | 0.000 ns | 9.94 KiB (1%) | 1 |
| `["union", "array", "(\"map\", abs, Int8, true)"]` | 17.408 μs (5%) | 0.000 ns | 29.58 KiB (1%) | 3 |
| `["union", "array", "(\"map\", identity, BigFloat, false)"]` | 28.988 μs (5%) | 0.000 ns | 78.20 KiB (1%) | 2 |
| `["union", "array", "(\"map\", identity, BigFloat, true)"]` | 49.997 μs (5%) | 0.000 ns | 156.41 KiB (1%) | 4 |
| `["union", "array", "(\"map\", identity, BigInt, false)"]` | 23.651 μs (5%) | 0.000 ns | 78.20 KiB (1%) | 2 |
| `["union", "array", "(\"map\", identity, BigInt, true)"]` | 48.277 μs (5%) | 0.000 ns | 156.41 KiB (1%) | 4 |
| `["union", "array", "(\"map\", identity, Bool, false)"]` | 7.714 μs (5%) | 0.000 ns | 9.94 KiB (1%) | 1 |
| `["union", "array", "(\"map\", identity, Bool, true)"]` | 14.241 μs (5%) | 0.000 ns | 29.58 KiB (1%) | 3 |
| `["union", "array", "(\"map\", identity, ComplexF64, false)"]` | 13.290 μs (5%) | 0.000 ns | 156.33 KiB (1%) | 2 |
| `["union", "array", "(\"map\", identity, ComplexF64, true)"]` | 49.179 μs (5%) | 0.000 ns | 322.47 KiB (1%) | 4 |
| `["union", "array", "(\"map\", identity, Float32, false)"]` | 9.421 μs (5%) | 0.000 ns | 39.14 KiB (1%) | 2 |
| `["union", "array", "(\"map\", identity, Float32, true)"]` | 23.497 μs (5%) | 0.000 ns | 88.09 KiB (1%) | 4 |
| `["union", "array", "(\"map\", identity, Float64, false)"]` | 9.899 μs (5%) | 0.000 ns | 78.20 KiB (1%) | 2 |
| `["union", "array", "(\"map\", identity, Float64, true)"]` | 25.290 μs (5%) | 0.000 ns | 166.22 KiB (1%) | 4 |
| `["union", "array", "(\"map\", identity, Int64, false)"]` | 9.987 μs (5%) | 0.000 ns | 78.20 KiB (1%) | 2 |
| `["union", "array", "(\"map\", identity, Int64, true)"]` | 25.092 μs (5%) | 0.000 ns | 166.22 KiB (1%) | 4 |
| `["union", "array", "(\"map\", identity, Int8, false)"]` | 7.772 μs (5%) | 0.000 ns | 9.94 KiB (1%) | 1 |
| `["union", "array", "(\"map\", identity, Int8, true)"]` | 15.015 μs (5%) | 0.000 ns | 29.58 KiB (1%) | 3 |
| `["union", "array", "(\"perf_binaryop\", *, BigFloat, (false, false))"]` | 889.023 μs (5%) | 0.000 ns | 1.14 MiB (1%) | 20008 |
| `["union", "array", "(\"perf_binaryop\", *, BigFloat, (false, true))"]` | 824.389 μs (5%) | 0.000 ns | 1.03 MiB (1%) | 17842 |
| `["union", "array", "(\"perf_binaryop\", *, BigFloat, (true, true))"]` | 815.761 μs (5%) | 0.000 ns | 1.03 MiB (1%) | 17842 |
| `["union", "array", "(\"perf_binaryop\", *, BigInt, (false, false))"]` | 869.095 μs (5%) | 0.000 ns | 703.32 KiB (1%) | 30008 |
| `["union", "array", "(\"perf_binaryop\", *, BigInt, (false, true))"]` | 767.407 μs (5%) | 0.000 ns | 635.63 KiB (1%) | 26759 |
| `["union", "array", "(\"perf_binaryop\", *, BigInt, (true, true))"]` | 749.961 μs (5%) | 0.000 ns | 635.63 KiB (1%) | 26759 |
| `["union", "array", "(\"perf_binaryop\", *, Bool, (false, false))"]` | 26.788 μs (5%) | 0.000 ns | 19.64 KiB (1%) | 2 |
| `["union", "array", "(\"perf_binaryop\", *, Bool, (false, true))"]` | 32.736 μs (5%) | 0.000 ns | 19.64 KiB (1%) | 2 |
| `["union", "array", "(\"perf_binaryop\", *, Bool, (true, true))"]` | 32.275 μs (5%) | 0.000 ns | 19.64 KiB (1%) | 2 |
| `["union", "array", "(\"perf_binaryop\", *, ComplexF64, (false, false))"]` | 73.070 μs (5%) | 0.000 ns | 166.14 KiB (1%) | 2 |
| `["union", "array", "(\"perf_binaryop\", *, ComplexF64, (false, true))"]` | 81.293 μs (5%) | 0.000 ns | 166.14 KiB (1%) | 2 |
| `["union", "array", "(\"perf_binaryop\", *, ComplexF64, (true, true))"]` | 80.549 μs (5%) | 0.000 ns | 166.14 KiB (1%) | 2 |
| `["union", "array", "(\"perf_binaryop\", *, Float32, (false, false))"]` | 33.818 μs (5%) | 0.000 ns | 48.95 KiB (1%) | 2 |
| `["union", "array", "(\"perf_binaryop\", *, Float32, (false, true))"]` | 40.377 μs (5%) | 0.000 ns | 48.95 KiB (1%) | 2 |
| `["union", "array", "(\"perf_binaryop\", *, Float32, (true, true))"]` | 40.599 μs (5%) | 0.000 ns | 48.95 KiB (1%) | 2 |
| `["union", "array", "(\"perf_binaryop\", *, Float64, (false, false))"]` | 35.970 μs (5%) | 0.000 ns | 88.02 KiB (1%) | 2 |
| `["union", "array", "(\"perf_binaryop\", *, Float64, (false, true))"]` | 44.368 μs (5%) | 0.000 ns | 88.02 KiB (1%) | 2 |
| `["union", "array", "(\"perf_binaryop\", *, Float64, (true, true))"]` | 44.754 μs (5%) | 0.000 ns | 88.02 KiB (1%) | 2 |
| `["union", "array", "(\"perf_binaryop\", *, Int64, (false, false))"]` | 38.875 μs (5%) | 0.000 ns | 88.02 KiB (1%) | 2 |
| `["union", "array", "(\"perf_binaryop\", *, Int64, (false, true))"]` | 46.723 μs (5%) | 0.000 ns | 88.02 KiB (1%) | 2 |
| `["union", "array", "(\"perf_binaryop\", *, Int64, (true, true))"]` | 46.432 μs (5%) | 0.000 ns | 88.02 KiB (1%) | 2 |
| `["union", "array", "(\"perf_binaryop\", *, Int8, (false, false))"]` | 26.736 μs (5%) | 0.000 ns | 19.64 KiB (1%) | 2 |
| `["union", "array", "(\"perf_binaryop\", *, Int8, (false, true))"]` | 32.929 μs (5%) | 0.000 ns | 19.64 KiB (1%) | 2 |
| `["union", "array", "(\"perf_binaryop\", *, Int8, (true, true))"]` | 32.352 μs (5%) | 0.000 ns | 19.64 KiB (1%) | 2 |
| `["union", "array", "(\"perf_countequals\", \"BigFloat\")"]` | 210.680 μs (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["union", "array", "(\"perf_countequals\", \"BigInt\")"]` | 75.600 μs (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["union", "array", "(\"perf_countequals\", \"Bool\")"]` | 31.112 μs (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["union", "array", "(\"perf_countequals\", \"ComplexF64\")"]` | 47.129 μs (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["union", "array", "(\"perf_countequals\", \"Float32\")"]` | 41.902 μs (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["union", "array", "(\"perf_countequals\", \"Float64\")"]` | 31.802 μs (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["union", "array", "(\"perf_countequals\", \"Int64\")"]` | 30.948 μs (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["union", "array", "(\"perf_countequals\", \"Int8\")"]` | 30.599 μs (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["union", "array", "(\"perf_countnothing\", BigFloat, false)"]` | 5.935 μs (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["union", "array", "(\"perf_countnothing\", BigFloat, true)"]` | 5.933 μs (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["union", "array", "(\"perf_countnothing\", BigInt, false)"]` | 5.932 μs (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["union", "array", "(\"perf_countnothing\", BigInt, true)"]` | 5.932 μs (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["union", "array", "(\"perf_countnothing\", Bool, false)"]` | 1.499 μs (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["union", "array", "(\"perf_countnothing\", Bool, true)"]` | 868.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["union", "array", "(\"perf_countnothing\", ComplexF64, false)"]` | 868.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["union", "array", "(\"perf_countnothing\", ComplexF64, true)"]` | 1.319 μs (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["union", "array", "(\"perf_countnothing\", Float32, false)"]` | 871.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["union", "array", "(\"perf_countnothing\", Float32, true)"]` | 1.319 μs (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["union", "array", "(\"perf_countnothing\", Float64, false)"]` | 1.504 μs (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["union", "array", "(\"perf_countnothing\", Float64, true)"]` | 1.320 μs (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["union", "array", "(\"perf_countnothing\", Int64, false)"]` | 869.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["union", "array", "(\"perf_countnothing\", Int64, true)"]` | 1.320 μs (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["union", "array", "(\"perf_countnothing\", Int8, false)"]` | 867.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["union", "array", "(\"perf_countnothing\", Int8, true)"]` | 868.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["union", "array", "(\"perf_simplecopy\", BigFloat, false)"]` | 28.928 μs (5%) | 0.000 ns | 78.20 KiB (1%) | 2 |
| `["union", "array", "(\"perf_simplecopy\", BigFloat, true)"]` | 35.140 μs (5%) | 0.000 ns | 78.20 KiB (1%) | 2 |
| `["union", "array", "(\"perf_simplecopy\", BigInt, false)"]` | 31.352 μs (5%) | 0.000 ns | 78.20 KiB (1%) | 2 |
| `["union", "array", "(\"perf_simplecopy\", BigInt, true)"]` | 36.385 μs (5%) | 0.000 ns | 78.20 KiB (1%) | 2 |
| `["union", "array", "(\"perf_simplecopy\", Bool, false)"]` | 4.047 μs (5%) | 0.000 ns | 19.64 KiB (1%) | 2 |
| `["union", "array", "(\"perf_simplecopy\", Bool, true)"]` | 4.283 μs (5%) | 0.000 ns | 19.64 KiB (1%) | 2 |
| `["union", "array", "(\"perf_simplecopy\", ComplexF64, false)"]` | 38.837 μs (5%) | 0.000 ns | 166.14 KiB (1%) | 2 |
| `["union", "array", "(\"perf_simplecopy\", ComplexF64, true)"]` | 38.887 μs (5%) | 0.000 ns | 166.14 KiB (1%) | 2 |
| `["union", "array", "(\"perf_simplecopy\", Float32, false)"]` | 10.451 μs (5%) | 0.000 ns | 48.95 KiB (1%) | 2 |
| `["union", "array", "(\"perf_simplecopy\", Float32, true)"]` | 10.561 μs (5%) | 0.000 ns | 48.95 KiB (1%) | 2 |
| `["union", "array", "(\"perf_simplecopy\", Float64, false)"]` | 21.533 μs (5%) | 0.000 ns | 88.02 KiB (1%) | 2 |
| `["union", "array", "(\"perf_simplecopy\", Float64, true)"]` | 29.196 μs (5%) | 0.000 ns | 88.02 KiB (1%) | 2 |
| `["union", "array", "(\"perf_simplecopy\", Int64, false)"]` | 21.523 μs (5%) | 0.000 ns | 88.02 KiB (1%) | 2 |
| `["union", "array", "(\"perf_simplecopy\", Int64, true)"]` | 28.121 μs (5%) | 0.000 ns | 88.02 KiB (1%) | 2 |
| `["union", "array", "(\"perf_simplecopy\", Int8, false)"]` | 4.023 μs (5%) | 0.000 ns | 19.64 KiB (1%) | 2 |
| `["union", "array", "(\"perf_simplecopy\", Int8, true)"]` | 4.144 μs (5%) | 0.000 ns | 19.64 KiB (1%) | 2 |
| `["union", "array", "(\"perf_sum2\", BigFloat, false)"]` | 515.192 μs (5%) | 0.000 ns | 1.07 MiB (1%) | 20006 |
| `["union", "array", "(\"perf_sum2\", BigFloat, true)"]` | 473.123 μs (5%) | 0.000 ns | 975.63 KiB (1%) | 17840 |
| `["union", "array", "(\"perf_sum2\", BigInt, false)"]` | 634.410 μs (5%) | 0.000 ns | 616.76 KiB (1%) | 20006 |
| `["union", "array", "(\"perf_sum2\", BigInt, true)"]` | 562.187 μs (5%) | 0.000 ns | 546.33 KiB (1%) | 17840 |
| `["union", "array", "(\"perf_sum2\", Bool, false)"]` | 1.501 μs (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["union", "array", "(\"perf_sum2\", Bool, true)"]` | 1.502 μs (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["union", "array", "(\"perf_sum2\", ComplexF64, false)"]` | 19.152 μs (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["union", "array", "(\"perf_sum2\", ComplexF64, true)"]` | 19.150 μs (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["union", "array", "(\"perf_sum2\", Float32, false)"]` | 14.732 μs (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["union", "array", "(\"perf_sum2\", Float32, true)"]` | 14.733 μs (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["union", "array", "(\"perf_sum2\", Float64, false)"]` | 14.733 μs (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["union", "array", "(\"perf_sum2\", Float64, true)"]` | 14.732 μs (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["union", "array", "(\"perf_sum2\", Int64, false)"]` | 1.244 μs (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["union", "array", "(\"perf_sum2\", Int64, true)"]` | 1.242 μs (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["union", "array", "(\"perf_sum2\", Int8, false)"]` | 176.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["union", "array", "(\"perf_sum2\", Int8, true)"]` | 176.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["union", "array", "(\"perf_sum3\", BigFloat, false)"]` | 518.735 μs (5%) | 0.000 ns | 1.07 MiB (1%) | 20006 |
| `["union", "array", "(\"perf_sum3\", BigFloat, true)"]` | 481.984 μs (5%) | 0.000 ns | 975.63 KiB (1%) | 17840 |
| `["union", "array", "(\"perf_sum3\", BigInt, false)"]` | 632.870 μs (5%) | 0.000 ns | 616.76 KiB (1%) | 20006 |
| `["union", "array", "(\"perf_sum3\", BigInt, true)"]` | 562.627 μs (5%) | 0.000 ns | 546.33 KiB (1%) | 17840 |
| `["union", "array", "(\"perf_sum3\", Bool, false)"]` | 8.861 μs (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["union", "array", "(\"perf_sum3\", Bool, true)"]` | 11.766 μs (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["union", "array", "(\"perf_sum3\", ComplexF64, false)"]` | 19.050 μs (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["union", "array", "(\"perf_sum3\", ComplexF64, true)"]` | 19.592 μs (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["union", "array", "(\"perf_sum3\", Float32, false)"]` | 14.752 μs (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["union", "array", "(\"perf_sum3\", Float32, true)"]` | 17.713 μs (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["union", "array", "(\"perf_sum3\", Float64, false)"]` | 14.750 μs (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["union", "array", "(\"perf_sum3\", Float64, true)"]` | 16.805 μs (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["union", "array", "(\"perf_sum3\", Int64, false)"]` | 8.135 μs (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["union", "array", "(\"perf_sum3\", Int64, true)"]` | 11.224 μs (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["union", "array", "(\"perf_sum3\", Int8, false)"]` | 8.126 μs (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["union", "array", "(\"perf_sum3\", Int8, true)"]` | 15.315 μs (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["union", "array", "(\"perf_sum4\", BigFloat, false)"]` | 780.085 μs (5%) | 0.000 ns | 2.14 MiB (1%) | 40006 |
| `["union", "array", "(\"perf_sum4\", BigFloat, true)"]` | 772.499 μs (5%) | 0.000 ns | 2.14 MiB (1%) | 40006 |
| `["union", "array", "(\"perf_sum4\", BigInt, false)"]` | 1.153 ms (5%) | 0.000 ns | 1007.38 KiB (1%) | 40006 |
| `["union", "array", "(\"perf_sum4\", BigInt, true)"]` | 1.116 ms (5%) | 0.000 ns | 1003.42 KiB (1%) | 40006 |
| `["union", "array", "(\"perf_sum4\", Bool, false)"]` | 1.684 μs (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["union", "array", "(\"perf_sum4\", Bool, true)"]` | 1.685 μs (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["union", "array", "(\"perf_sum4\", ComplexF64, false)"]` | 11.815 μs (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["union", "array", "(\"perf_sum4\", ComplexF64, true)"]` | 11.812 μs (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["union", "array", "(\"perf_sum4\", Float32, false)"]` | 704.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["union", "array", "(\"perf_sum4\", Float32, true)"]` | 705.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["union", "array", "(\"perf_sum4\", Float64, false)"]` | 1.283 μs (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["union", "array", "(\"perf_sum4\", Float64, true)"]` | 1.275 μs (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["union", "array", "(\"perf_sum4\", Int64, false)"]` | 1.244 μs (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["union", "array", "(\"perf_sum4\", Int64, true)"]` | 1.239 μs (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["union", "array", "(\"perf_sum4\", Int8, false)"]` | 175.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["union", "array", "(\"perf_sum4\", Int8, true)"]` | 174.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["union", "array", "(\"perf_sum\", BigFloat, false)"]` | 513.025 μs (5%) | 0.000 ns | 1.07 MiB (1%) | 20006 |
| `["union", "array", "(\"perf_sum\", BigFloat, true)"]` | 469.922 μs (5%) | 0.000 ns | 975.63 KiB (1%) | 17840 |
| `["union", "array", "(\"perf_sum\", BigInt, false)"]` | 638.931 μs (5%) | 0.000 ns | 616.76 KiB (1%) | 20006 |
| `["union", "array", "(\"perf_sum\", BigInt, true)"]` | 556.532 μs (5%) | 0.000 ns | 546.33 KiB (1%) | 17840 |
| `["union", "array", "(\"perf_sum\", Bool, false)"]` | 1.684 μs (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["union", "array", "(\"perf_sum\", Bool, true)"]` | 1.500 μs (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["union", "array", "(\"perf_sum\", ComplexF64, false)"]` | 11.798 μs (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["union", "array", "(\"perf_sum\", ComplexF64, true)"]` | 14.200 μs (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["union", "array", "(\"perf_sum\", Float32, false)"]` | 14.732 μs (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["union", "array", "(\"perf_sum\", Float32, true)"]` | 14.731 μs (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["union", "array", "(\"perf_sum\", Float64, false)"]` | 14.730 μs (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["union", "array", "(\"perf_sum\", Float64, true)"]` | 14.732 μs (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["union", "array", "(\"perf_sum\", Int64, false)"]` | 1.241 μs (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["union", "array", "(\"perf_sum\", Int64, true)"]` | 1.236 μs (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["union", "array", "(\"perf_sum\", Int8, false)"]` | 175.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["union", "array", "(\"perf_sum\", Int8, true)"]` | 174.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["union", "array", "(\"skipmissing\", collect, BigFloat, false)"]` | 95.535 μs (5%) | 0.000 ns | 256.64 KiB (1%) | 14 |
| `["union", "array", "(\"skipmissing\", collect, BigInt, false)"]` | 101.079 μs (5%) | 0.000 ns | 256.64 KiB (1%) | 14 |
| `["union", "array", "(\"skipmissing\", collect, Bool, false)"]` | 67.455 μs (5%) | 0.000 ns | 32.80 KiB (1%) | 14 |
| `["union", "array", "(\"skipmissing\", collect, ComplexF64, false)"]` | 108.310 μs (5%) | 0.000 ns | 512.66 KiB (1%) | 14 |
| `["union", "array", "(\"skipmissing\", collect, Float32, false)"]` | 73.588 μs (5%) | 0.000 ns | 128.61 KiB (1%) | 14 |
| `["union", "array", "(\"skipmissing\", collect, Float64, false)"]` | 86.943 μs (5%) | 0.000 ns | 256.64 KiB (1%) | 14 |
| `["union", "array", "(\"skipmissing\", collect, Int64, false)"]` | 86.469 μs (5%) | 0.000 ns | 256.64 KiB (1%) | 14 |
| `["union", "array", "(\"skipmissing\", collect, Int8, false)"]` | 65.070 μs (5%) | 0.000 ns | 32.80 KiB (1%) | 14 |
| `["union", "array", "(\"skipmissing\", collect, Union{Missing, BigFloat}, true)"]` | 106.656 μs (5%) | 0.000 ns | 256.64 KiB (1%) | 14 |
| `["union", "array", "(\"skipmissing\", collect, Union{Missing, BigInt}, true)"]` | 106.679 μs (5%) | 0.000 ns | 256.64 KiB (1%) | 14 |
| `["union", "array", "(\"skipmissing\", collect, Union{Missing, Bool}, true)"]` | 82.192 μs (5%) | 0.000 ns | 32.80 KiB (1%) | 14 |
| `["union", "array", "(\"skipmissing\", collect, Union{Missing, ComplexF64}, true)"]` | 124.259 μs (5%) | 0.000 ns | 512.66 KiB (1%) | 14 |
| `["union", "array", "(\"skipmissing\", collect, Union{Missing, Float32}, true)"]` | 88.233 μs (5%) | 0.000 ns | 128.61 KiB (1%) | 14 |
| `["union", "array", "(\"skipmissing\", collect, Union{Missing, Float64}, true)"]` | 100.609 μs (5%) | 0.000 ns | 256.64 KiB (1%) | 14 |
| `["union", "array", "(\"skipmissing\", collect, Union{Missing, Int64}, true)"]` | 100.471 μs (5%) | 0.000 ns | 256.64 KiB (1%) | 14 |
| `["union", "array", "(\"skipmissing\", collect, Union{Missing, Int8}, true)"]` | 81.537 μs (5%) | 0.000 ns | 32.80 KiB (1%) | 14 |
| `["union", "array", "(\"skipmissing\", collect, Union{Nothing, BigFloat}, false)"]` | 104.863 μs (5%) | 0.000 ns | 256.64 KiB (1%) | 14 |
| `["union", "array", "(\"skipmissing\", collect, Union{Nothing, BigInt}, false)"]` | 104.575 μs (5%) | 0.000 ns | 256.64 KiB (1%) | 14 |
| `["union", "array", "(\"skipmissing\", collect, Union{Nothing, Bool}, false)"]` | 110.166 μs (5%) | 0.000 ns | 64.56 KiB (1%) | 14 |
| `["union", "array", "(\"skipmissing\", collect, Union{Nothing, ComplexF64}, false)"]` | 158.910 μs (5%) | 0.000 ns | 544.66 KiB (1%) | 14 |
| `["union", "array", "(\"skipmissing\", collect, Union{Nothing, Float32}, false)"]` | 128.124 μs (5%) | 0.000 ns | 160.61 KiB (1%) | 14 |
| `["union", "array", "(\"skipmissing\", collect, Union{Nothing, Float64}, false)"]` | 128.985 μs (5%) | 0.000 ns | 288.59 KiB (1%) | 14 |
| `["union", "array", "(\"skipmissing\", collect, Union{Nothing, Int64}, false)"]` | 134.336 μs (5%) | 0.000 ns | 288.59 KiB (1%) | 14 |
| `["union", "array", "(\"skipmissing\", collect, Union{Nothing, Int8}, false)"]` | 114.794 μs (5%) | 0.000 ns | 64.56 KiB (1%) | 14 |
| `["union", "array", "(\"skipmissing\", sum, BigFloat, false)"]` | 514.242 μs (5%) | 0.000 ns | 1.07 MiB (1%) | 19998 |
| `["union", "array", "(\"skipmissing\", sum, BigInt, false)"]` | 647.547 μs (5%) | 0.000 ns | 609.67 KiB (1%) | 19998 |
| `["union", "array", "(\"skipmissing\", sum, Bool, false)"]` | 1.654 μs (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["union", "array", "(\"skipmissing\", sum, ComplexF64, false)"]` | 3.333 μs (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["union", "array", "(\"skipmissing\", sum, Float32, false)"]` | 875.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["union", "array", "(\"skipmissing\", sum, Float64, false)"]` | 1.228 μs (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["union", "array", "(\"skipmissing\", sum, Int64, false)"]` | 946.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["union", "array", "(\"skipmissing\", sum, Int8, false)"]` | 930.000 ns (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["union", "array", "(\"skipmissing\", sum, Union{Missing, BigFloat}, true)"]` | 474.945 μs (5%) | 0.000 ns | 975.73 KiB (1%) | 17867 |
| `["union", "array", "(\"skipmissing\", sum, Union{Missing, BigInt}, true)"]` | 570.853 μs (5%) | 0.000 ns | 542.34 KiB (1%) | 17867 |
| `["union", "array", "(\"skipmissing\", sum, Union{Missing, Bool}, true)"]` | 2.194 μs (5%) | 0.000 ns | 96 bytes (1%) | 6 |
| `["union", "array", "(\"skipmissing\", sum, Union{Missing, ComplexF64}, true)"]` | 14.856 μs (5%) | 0.000 ns | 128 bytes (1%) | 6 |
| `["union", "array", "(\"skipmissing\", sum, Union{Missing, Float32}, true)"]` | 14.957 μs (5%) | 0.000 ns | 96 bytes (1%) | 6 |
| `["union", "array", "(\"skipmissing\", sum, Union{Missing, Float64}, true)"]` | 14.936 μs (5%) | 0.000 ns | 96 bytes (1%) | 6 |
| `["union", "array", "(\"skipmissing\", sum, Union{Missing, Int64}, true)"]` | 1.888 μs (5%) | 0.000 ns | 96 bytes (1%) | 6 |
| `["union", "array", "(\"skipmissing\", sum, Union{Missing, Int8}, true)"]` | 2.135 μs (5%) | 0.000 ns | 96 bytes (1%) | 6 |
| `["union", "array", "(\"skipmissing\", sum, Union{Nothing, BigFloat}, false)"]` | 524.331 μs (5%) | 0.000 ns | 1.07 MiB (1%) | 19998 |
| `["union", "array", "(\"skipmissing\", sum, Union{Nothing, BigInt}, false)"]` | 636.077 μs (5%) | 0.000 ns | 609.67 KiB (1%) | 19998 |
| `["union", "array", "(\"skipmissing\", sum, Union{Nothing, Bool}, false)"]` | 12.130 μs (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["union", "array", "(\"skipmissing\", sum, Union{Nothing, ComplexF64}, false)"]` | 13.564 μs (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["union", "array", "(\"skipmissing\", sum, Union{Nothing, Float32}, false)"]` | 13.074 μs (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["union", "array", "(\"skipmissing\", sum, Union{Nothing, Float64}, false)"]` | 13.067 μs (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["union", "array", "(\"skipmissing\", sum, Union{Nothing, Int64}, false)"]` | 12.100 μs (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["union", "array", "(\"skipmissing\", sum, Union{Nothing, Int8}, false)"]` | 12.155 μs (5%) | 0.000 ns | 0 bytes (1%) | 0 |
| `["union", "array", "(\"sort\", BigFloat, false)"]` | 3.241 ms (5%) | 0.000 ns | 78.20 KiB (1%) | 2 |
| `["union", "array", "(\"sort\", BigInt, false)"]` | 1.605 ms (5%) | 0.000 ns | 78.35 KiB (1%) | 8 |
| `["union", "array", "(\"sort\", Bool, false)"]` | 21.584 μs (5%) | 0.000 ns | 10.03 KiB (1%) | 2 |
| `["union", "array", "(\"sort\", Float32, false)"]` | 462.819 μs (5%) | 0.000 ns | 39.14 KiB (1%) | 2 |
| `["union", "array", "(\"sort\", Float64, false)"]` | 464.971 μs (5%) | 0.000 ns | 78.20 KiB (1%) | 2 |
| `["union", "array", "(\"sort\", Int64, false)"]` | 492.633 μs (5%) | 0.000 ns | 78.20 KiB (1%) | 2 |
| `["union", "array", "(\"sort\", Int8, false)"]` | 355.777 μs (5%) | 0.000 ns | 9.94 KiB (1%) | 1 |
| `["union", "array", "(\"sort\", Union{Missing, BigFloat}, true)"]` | 3.134 ms (5%) | 0.000 ns | 78.20 KiB (1%) | 2 |
| `["union", "array", "(\"sort\", Union{Missing, BigInt}, true)"]` | 1.518 ms (5%) | 0.000 ns | 78.20 KiB (1%) | 2 |
| `["union", "array", "(\"sort\", Union{Missing, Bool}, true)"]` | 461.764 μs (5%) | 0.000 ns | 19.64 KiB (1%) | 2 |
| `["union", "array", "(\"sort\", Union{Missing, Float32}, true)"]` | 1.157 ms (5%) | 0.000 ns | 48.95 KiB (1%) | 2 |
| `["union", "array", "(\"sort\", Union{Missing, Float64}, true)"]` | 1.177 ms (5%) | 0.000 ns | 88.02 KiB (1%) | 2 |
| `["union", "array", "(\"sort\", Union{Missing, Int64}, true)"]` | 820.875 μs (5%) | 0.000 ns | 88.02 KiB (1%) | 2 |
| `["union", "array", "(\"sort\", Union{Missing, Int8}, true)"]` | 692.262 μs (5%) | 0.000 ns | 19.64 KiB (1%) | 2 |
| `["union", "array", "(\"sort\", Union{Nothing, BigFloat}, false)"]` | 3.664 ms (5%) | 0.000 ns | 117.41 KiB (1%) | 4 |
| `["union", "array", "(\"sort\", Union{Nothing, BigInt}, false)"]` | 2.084 ms (5%) | 0.000 ns | 117.41 KiB (1%) | 4 |
| `["union", "array", "(\"sort\", Union{Nothing, Bool}, false)"]` | 600.511 μs (5%) | 0.000 ns | 29.59 KiB (1%) | 4 |
| `["union", "array", "(\"sort\", Union{Nothing, Float32}, false)"]` | 1.483 ms (5%) | 0.000 ns | 73.53 KiB (1%) | 4 |
| `["union", "array", "(\"sort\", Union{Nothing, Float64}, false)"]` | 1.537 ms (5%) | 0.000 ns | 132.16 KiB (1%) | 4 |
| `["union", "array", "(\"sort\", Union{Nothing, Int64}, false)"]` | 1.206 ms (5%) | 0.000 ns | 132.16 KiB (1%) | 4 |
| `["union", "array", "(\"sort\", Union{Nothing, Int8}, false)"]` | 1.101 ms (5%) | 0.000 ns | 29.59 KiB (1%) | 4 |

## Benchmark Group List

Here's a list of all the benchmark groups executed by this job:

- `["array", "accumulate"]`
- `["array", "any/all"]`
- `["array", "bool"]`
- `["array", "cat"]`
- `["array", "comprehension"]`
- `["array", "convert"]`
- `["array", "equality"]`
- `["array", "growth"]`
- `["array", "index"]`
- `["array", "reductions"]`
- `["array", "reverse"]`
- `["array", "setindex!"]`
- `["array", "subarray"]`
- `["broadcast"]`
- `["broadcast", "dotop"]`
- `["broadcast", "fusion"]`
- `["broadcast", "mix_scalar_tuple"]`
- `["broadcast", "sparse"]`
- `["broadcast", "typeargs"]`
- `["collection", "deletion"]`
- `["collection", "initialization"]`
- `["collection", "iteration"]`
- `["collection", "optimizations"]`
- `["collection", "queries & updates"]`
- `["collection", "set operations"]`
- `["dates", "accessor"]`
- `["dates", "arithmetic"]`
- `["dates", "construction"]`
- `["dates", "conversion"]`
- `["dates", "parse"]`
- `["dates", "query"]`
- `["dates", "string"]`
- `["find", "findall"]`
- `["find", "findnext"]`
- `["find", "findprev"]`
- `["io", "array_limit"]`
- `["io", "read"]`
- `["io", "serialization"]`
- `["io"]`
- `["linalg", "arithmetic"]`
- `["linalg", "blas"]`
- `["linalg", "factorization"]`
- `["linalg"]`
- `["micro"]`
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
- `["parallel", "remotecall"]`
- `["problem", "chaosgame"]`
- `["problem", "fem"]`
- `["problem", "go"]`
- `["problem", "grigoriadis khachiyan"]`
- `["problem", "imdb"]`
- `["problem", "json"]`
- `["problem", "laplacian"]`
- `["problem", "monte carlo"]`
- `["problem", "raytrace"]`
- `["problem", "seismic"]`
- `["problem", "simplex"]`
- `["problem", "spellcheck"]`
- `["problem", "stockcorr"]`
- `["problem", "ziggurat"]`
- `["random", "collections"]`
- `["random", "randstring"]`
- `["random", "ranges"]`
- `["random", "sequences"]`
- `["random", "types"]`
- `["scalar", "acos"]`
- `["scalar", "acosh"]`
- `["scalar", "arithmetic"]`
- `["scalar", "asin"]`
- `["scalar", "asinh"]`
- `["scalar", "atan"]`
- `["scalar", "atan2"]`
- `["scalar", "atanh"]`
- `["scalar", "cbrt"]`
- `["scalar", "cos"]`
- `["scalar", "cosh"]`
- `["scalar", "exp2"]`
- `["scalar", "expm1"]`
- `["scalar", "fastmath"]`
- `["scalar", "floatexp"]`
- `["scalar", "intfuncs"]`
- `["scalar", "iteration"]`
- `["scalar", "mod2pi"]`
- `["scalar", "predicate"]`
- `["scalar", "rem_pio2"]`
- `["scalar", "sin"]`
- `["scalar", "sincos"]`
- `["scalar", "sinh"]`
- `["scalar", "tan"]`
- `["scalar", "tanh"]`
- `["shootout"]`
- `["simd"]`
- `["sort", "insertionsort"]`
- `["sort", "issorted"]`
- `["sort", "mergesort"]`
- `["sort", "quicksort"]`
- `["sparse", "arithmetic"]`
- `["sparse", "constructors"]`
- `["sparse", "index"]`
- `["sparse", "matmul"]`
- `["sparse", "sparse matvec"]`
- `["sparse", "sparse solves"]`
- `["sparse", "transpose"]`
- `["string", "==(::AbstractString, ::AbstractString)"]`
- `["string", "==(::SubString, ::String)"]`
- `["string", "findfirst"]`
- `["string"]`
- `["string", "readuntil"]`
- `["string", "repeat"]`
- `["tuple", "index"]`
- `["tuple", "linear algebra"]`
- `["tuple", "misc"]`
- `["tuple", "reduction"]`
- `["union", "array"]`

## Version Info

#### Primary Build

```
Julia Version 1.7.0-DEV.594
Commit d753a0b6a7 (2021-02-22 16:57 UTC)
Platform Info:
  OS: Linux (x86_64-linux-gnu)
      Ubuntu 20.04.2 LTS
  uname: Linux 5.4.0-1037-aws #39-Ubuntu SMP Thu Jan 14 02:56:06 UTC 2021 x86_64 x86_64
  CPU: Intel(R) Xeon(R) Platinum 8124M CPU @ 3.00GHz: 
              speed         user         nice          sys         idle          irq
       #1  3399 MHz      46894 s        354 s       4144 s     748250 s          0 s
       #2  3400 MHz     194187 s          2 s       4029 s     601694 s          0 s
       #3  3399 MHz       4376 s         11 s        378 s     795158 s          0 s
       #4  3399 MHz       5847 s          6 s        370 s     793372 s          0 s
       #5  3399 MHz       2562 s         13 s        363 s     770056 s          0 s
       #6  3399 MHz       5646 s         12 s        415 s     793775 s          0 s
       #7  3399 MHz       2534 s          5 s        317 s     797076 s          0 s
       #8  3399 MHz       4047 s         22 s        307 s     795161 s          0 s
       
  Memory: 30.362831115722656 GB (10723.98046875 MB free)
  Uptime: 79997.0 sec
  Load Avg:  1.0  1.0  1.0
  WORD_SIZE: 64
  LIBM: libopenlibm
  LLVM: libLLVM-11.0.1 (ORCJIT, skylake-avx512)

```
