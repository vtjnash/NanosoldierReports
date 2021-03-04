# Benchmark Report

## Job Properties

*Commit(s):* [vtjnash/julia@49387b2bc67f90650e5c2a982d8fb31e7e6d90b7](https://github.com/vtjnash/julia/commit/49387b2bc67f90650e5c2a982d8fb31e7e6d90b7) vs [vtjnash/julia@de7d695](https://github.com/vtjnash/julia/commit/de7d695)

*Triggered By:* [link](https://github.com/vtjnash/julia/commit/49387b2bc67f90650e5c2a982d8fb31e7e6d90b7#commitcomment-47852751)

*Tag Predicate:* `"io"`

## Error

The build could not finish due to an error:

```
NanosoldierError: failed to run benchmarks against primary commit: ArgumentError: '/home/vtjnash/test_workdir/srccache/CompilerSupportLibraries.v0.4.0+0.x86_64-linux-gnu-libgfortran5.tar.gz.tmp' exists. `force=true` is required to remove '/home/vtjnash/test_workdir/srccache/CompilerSupportLibraries.v0.4.0+0.x86_64-linux-gnu-libgfortran5.tar.gz.tmp' before copying.
Stacktrace:
 [1] checkfor_mv_cp_cptree(::String, ::String, ::String; force::Bool) at ./file.jl:308
 [2] cp(::String, ::String; force::Bool, follow_symlinks::Bool) at ./file.jl:345
 [3] cp at ./file.jl:345 [inlined]
 [4] sync_srcs!(::String, ::String, ::Bool) at /data/vtjnash/nanosoldierbot/Nanosoldier.jl/src/build.jl:33
 [5] build_julia!(::Nanosoldier.Config, ::Nanosoldier.BuildRef, ::String, ::Nothing) at /data/vtjnash/nanosoldierbot/Nanosoldier.jl/src/build.jl:89
 [6] build_julia! at /data/vtjnash/nanosoldierbot/Nanosoldier.jl/src/build.jl:45 [inlined]
 [7] execute_benchmarks!(::Nanosoldier.BenchmarkJob, ::Symbol) at /data/vtjnash/nanosoldierbot/Nanosoldier.jl/src/jobs/BenchmarkJob.jl:267
 [8] run(::Nanosoldier.BenchmarkJob) at /data/vtjnash/nanosoldierbot/Nanosoldier.jl/src/jobs/BenchmarkJob.jl:202
 [9] (::Distributed.var"#106#108"{Distributed.CallMsg{:call_fetch}})() at /buildworker/worker/package_linux64/build/usr/share/julia/stdlib/v1.5/Distributed/src/process_messages.jl:294
 [10] run_work_thunk(::Distributed.var"#106#108"{Distributed.CallMsg{:call_fetch}}, ::Bool) at /buildworker/worker/package_linux64/build/usr/share/julia/stdlib/v1.5/Distributed/src/process_messages.jl:79
 [11] macro expansion at /buildworker/worker/package_linux64/build/usr/share/julia/stdlib/v1.5/Distributed/src/process_messages.jl:294 [inlined]
 [12] (::Distributed.var"#105#107"{Distributed.CallMsg{:call_fetch},Distributed.MsgHeader,Sockets.TCPSocket})() at ./task.jl:356
```

Check the logs folder in this directory for more detailed output.

