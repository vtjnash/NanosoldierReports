# Benchmark Report

## Job Properties

*Commit(s):* [vtjnash/julia@d753a0b6a78d94d08c17b2c227916700e3359e4a](https://github.com/vtjnash/julia/commit/d753a0b6a78d94d08c17b2c227916700e3359e4a) vs [vtjnash/julia@76106100559e6dc61769cdbd3d53836e22ffa5e9](https://github.com/vtjnash/julia/commit/76106100559e6dc61769cdbd3d53836e22ffa5e9)

*Triggered By:* [link](https://github.com/vtjnash/julia/commit/d753a0b6a78d94d08c17b2c227916700e3359e4a#commitcomment-47436870)

*Tag Predicate:* `"micro"`

## Error

The build could not finish due to an error:

```
NanosoldierError: failed to run benchmarks against primary commit: failed process: Process(`git clone git@github.com:vtjnash/julia.git /home/ubuntu/test_workdir/jl_OboE7t`, ProcessExited(128)) [128]

Stacktrace:
 [1] pipeline_error at ./process.jl:525 [inlined]
 [2] run(::Cmd; wait::Bool) at ./process.jl:440
 [3] run at ./process.jl:438 [inlined]
 [4] gitclone! at /home/ubuntu/Nanosoldier.jl/src/Nanosoldier.jl:25 [inlined]
 [5] gitclone! at /home/ubuntu/Nanosoldier.jl/src/Nanosoldier.jl:20 [inlined]
 [6] build_julia!(::Nanosoldier.Config, ::Nanosoldier.BuildRef, ::String, ::Nothing) at /home/ubuntu/Nanosoldier.jl/src/build.jl:43
 [7] build_julia! at /home/ubuntu/Nanosoldier.jl/src/build.jl:25 [inlined]
 [8] execute_benchmarks!(::Nanosoldier.BenchmarkJob, ::Symbol) at /home/ubuntu/Nanosoldier.jl/src/jobs/BenchmarkJob.jl:263
 [9] run(::Nanosoldier.BenchmarkJob) at /home/ubuntu/Nanosoldier.jl/src/jobs/BenchmarkJob.jl:202
 [10] (::Distributed.var"#106#108"{Distributed.CallMsg{:call_fetch}})() at /buildworker/worker/package_linux64/build/usr/share/julia/stdlib/v1.5/Distributed/src/process_messages.jl:294
 [11] run_work_thunk(::Distributed.var"#106#108"{Distributed.CallMsg{:call_fetch}}, ::Bool) at /buildworker/worker/package_linux64/build/usr/share/julia/stdlib/v1.5/Distributed/src/process_messages.jl:79
 [12] macro expansion at /buildworker/worker/package_linux64/build/usr/share/julia/stdlib/v1.5/Distributed/src/process_messages.jl:294 [inlined]
 [13] (::Distributed.var"#105#107"{Distributed.CallMsg{:call_fetch},Distributed.MsgHeader,Sockets.TCPSocket})() at ./task.jl:356
```

Check the logs folder in this directory for more detailed output.

