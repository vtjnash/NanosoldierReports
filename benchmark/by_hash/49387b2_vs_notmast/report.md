# Benchmark Report

## Job Properties

*Commit(s):* [vtjnash/julia@49387b2bc67f90650e5c2a982d8fb31e7e6d90b7](https://github.com/vtjnash/julia/commit/49387b2bc67f90650e5c2a982d8fb31e7e6d90b7) vs [vtjnash/julia@notmaster^](https://github.com/vtjnash/julia/commit/notmaster^)

*Triggered By:* [link](https://github.com/vtjnash/julia/commit/49387b2bc67f90650e5c2a982d8fb31e7e6d90b7#commitcomment-47821652)

*Tag Predicate:* `"io"`

## Error

The build could not finish due to an error:

```
NanosoldierError: failed to run benchmarks against primary commit: failed process: Process(`git reset --hard origin/master`, ProcessExited(128)) [128]

Stacktrace:
 [1] pipeline_error at ./process.jl:525 [inlined]
 [2] run(::Cmd; wait::Bool) at ./process.jl:440
 [3] run at ./process.jl:438 [inlined]
 [4] gitreset! at /data/vtjnash/nanosoldierbot/Nanosoldier.jl/src/Nanosoldier.jl:30 [inlined]
 [5] cd(::typeof(Nanosoldier.gitreset!), ::String) at ./file.jl:104
 [6] gitreset! at /data/vtjnash/nanosoldierbot/Nanosoldier.jl/src/Nanosoldier.jl:31 [inlined]
 [7] build_julia!(::Nanosoldier.Config, ::Nanosoldier.BuildRef, ::String, ::Nothing) at /data/vtjnash/nanosoldierbot/Nanosoldier.jl/src/build.jl:28
 [8] build_julia! at /data/vtjnash/nanosoldierbot/Nanosoldier.jl/src/build.jl:25 [inlined]
 [9] execute_benchmarks!(::Nanosoldier.BenchmarkJob, ::Symbol) at /data/vtjnash/nanosoldierbot/Nanosoldier.jl/src/jobs/BenchmarkJob.jl:267
 [10] run(::Nanosoldier.BenchmarkJob) at /data/vtjnash/nanosoldierbot/Nanosoldier.jl/src/jobs/BenchmarkJob.jl:202
 [11] (::Distributed.var"#106#108"{Distributed.CallMsg{:call_fetch}})() at /buildworker/worker/package_linux64/build/usr/share/julia/stdlib/v1.5/Distributed/src/process_messages.jl:294
 [12] run_work_thunk(::Distributed.var"#106#108"{Distributed.CallMsg{:call_fetch}}, ::Bool) at /buildworker/worker/package_linux64/build/usr/share/julia/stdlib/v1.5/Distributed/src/process_messages.jl:79
 [13] macro expansion at /buildworker/worker/package_linux64/build/usr/share/julia/stdlib/v1.5/Distributed/src/process_messages.jl:294 [inlined]
 [14] (::Distributed.var"#105#107"{Distributed.CallMsg{:call_fetch},Distributed.MsgHeader,Sockets.TCPSocket})() at ./task.jl:356
```

Check the logs folder in this directory for more detailed output.

