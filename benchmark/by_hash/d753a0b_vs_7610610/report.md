# Benchmark Report

## Job Properties

*Commit(s):* [vtjnash/julia@d753a0b6a78d94d08c17b2c227916700e3359e4a](https://github.com/vtjnash/julia/commit/d753a0b6a78d94d08c17b2c227916700e3359e4a) vs [vtjnash/julia@76106100559e6dc61769cdbd3d53836e22ffa5e9](https://github.com/vtjnash/julia/commit/76106100559e6dc61769cdbd3d53836e22ffa5e9)

*Triggered By:* [link](https://github.com/vtjnash/julia/commit/d753a0b6a78d94d08c17b2c227916700e3359e4a#commitcomment-47438264)

*Tag Predicate:* `"micro"`

## Error

The build could not finish due to an error:

```
NanosoldierError: failed to run benchmarks against primary commit: UndefVarError: juliaenv not defined
Stacktrace:
 [1] execute_benchmarks!(::Nanosoldier.BenchmarkJob, ::Symbol) at /home/ubuntu/Nanosoldier.jl/src/jobs/BenchmarkJob.jl:281
 [2] run(::Nanosoldier.BenchmarkJob) at /home/ubuntu/Nanosoldier.jl/src/jobs/BenchmarkJob.jl:202
 [3] (::Distributed.var"#106#108"{Distributed.CallMsg{:call_fetch}})() at /buildworker/worker/package_linux64/build/usr/share/julia/stdlib/v1.5/Distributed/src/process_messages.jl:294
 [4] run_work_thunk(::Distributed.var"#106#108"{Distributed.CallMsg{:call_fetch}}, ::Bool) at /buildworker/worker/package_linux64/build/usr/share/julia/stdlib/v1.5/Distributed/src/process_messages.jl:79
 [5] macro expansion at /buildworker/worker/package_linux64/build/usr/share/julia/stdlib/v1.5/Distributed/src/process_messages.jl:294 [inlined]
 [6] (::Distributed.var"#105#107"{Distributed.CallMsg{:call_fetch},Distributed.MsgHeader,Sockets.TCPSocket})() at ./task.jl:356
```

Check the logs folder in this directory for more detailed output.

