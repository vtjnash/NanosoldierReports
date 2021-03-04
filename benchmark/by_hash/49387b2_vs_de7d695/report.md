# Benchmark Report

## Job Properties

*Commit(s):* [vtjnash/julia@49387b2bc67f90650e5c2a982d8fb31e7e6d90b7](https://github.com/vtjnash/julia/commit/49387b2bc67f90650e5c2a982d8fb31e7e6d90b7) vs [vtjnash/julia@de7d695](https://github.com/vtjnash/julia/commit/de7d695)

*Triggered By:* [link](https://github.com/vtjnash/julia/commit/49387b2bc67f90650e5c2a982d8fb31e7e6d90b7#commitcomment-47851900)

*Tag Predicate:* `"io"`

## Error

The build could not finish due to an error:

```
NanosoldierError: failed to run benchmarks against primary commit: IOError: chmod: no such file or directory (ENOENT)
Stacktrace:
 [1] uv_error at ./libuv.jl:97 [inlined]
 [2] chmod(::String, ::UInt16; recursive::Bool) at ./file.jl:1024
 [3] chmod at ./file.jl:1023 [inlined]
 [4] sync_srcs!(::String, ::String, ::Bool) at /data/vtjnash/nanosoldierbot/Nanosoldier.jl/src/build.jl:33
 [5] build_julia!(::Nanosoldier.Config, ::Nanosoldier.BuildRef, ::String, ::Nothing) at /data/vtjnash/nanosoldierbot/Nanosoldier.jl/src/build.jl:88
 [6] build_julia! at /data/vtjnash/nanosoldierbot/Nanosoldier.jl/src/build.jl:44 [inlined]
 [7] execute_benchmarks!(::Nanosoldier.BenchmarkJob, ::Symbol) at /data/vtjnash/nanosoldierbot/Nanosoldier.jl/src/jobs/BenchmarkJob.jl:267
 [8] run(::Nanosoldier.BenchmarkJob) at /data/vtjnash/nanosoldierbot/Nanosoldier.jl/src/jobs/BenchmarkJob.jl:202
 [9] (::Distributed.var"#106#108"{Distributed.CallMsg{:call_fetch}})() at /buildworker/worker/package_linux64/build/usr/share/julia/stdlib/v1.5/Distributed/src/process_messages.jl:294
 [10] run_work_thunk(::Distributed.var"#106#108"{Distributed.CallMsg{:call_fetch}}, ::Bool) at /buildworker/worker/package_linux64/build/usr/share/julia/stdlib/v1.5/Distributed/src/process_messages.jl:79
 [11] macro expansion at /buildworker/worker/package_linux64/build/usr/share/julia/stdlib/v1.5/Distributed/src/process_messages.jl:294 [inlined]
 [12] (::Distributed.var"#105#107"{Distributed.CallMsg{:call_fetch},Distributed.MsgHeader,Sockets.TCPSocket})() at ./task.jl:356
```

Check the logs folder in this directory for more detailed output.

