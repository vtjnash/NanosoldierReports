# Benchmark Report

## Job Properties

*Commit(s):* [vtjnash/julia@d753a0b6a78d94d08c17b2c227916700e3359e4a](https://github.com/vtjnash/julia/commit/d753a0b6a78d94d08c17b2c227916700e3359e4a) vs [vtjnash/julia@76106100559e6dc61769cdbd3d53836e22ffa5e9](https://github.com/vtjnash/julia/commit/76106100559e6dc61769cdbd3d53836e22ffa5e9)

*Triggered By:* [link](https://github.com/vtjnash/julia/commit/d753a0b6a78d94d08c17b2c227916700e3359e4a#commitcomment-47439177)

*Tag Predicate:* `"ALL"`

## Error

The build could not finish due to an error:

```
NanosoldierError: failed to run benchmarks against primary commit: IOError: could not spawn `make -j7 USECCACHE=1 USE_BINARYBUILDER_LLVM=0`: no such file or directory (ENOENT)
Stacktrace:
 [1] _spawn_primitive(::String, ::Cmd, ::Array{Any,1}) at ./process.jl:99
 [2] #585 at ./process.jl:112 [inlined]
 [3] setup_stdios(::Base.var"#585#586"{Cmd}, ::Array{Any,1}) at ./process.jl:196
 [4] _spawn at ./process.jl:111 [inlined]
 [5] _spawn(::Base.CmdRedirect, ::Array{Any,1}) at ./process.jl:139 (repeats 2 times)
 [6] run(::Base.CmdRedirect; wait::Bool) at ./process.jl:439
 [7] run at ./process.jl:438 [inlined]
 [8] build_julia!(::Nanosoldier.Config, ::Nanosoldier.BuildRef, ::String, ::Nothing) at /home/ubuntu/Nanosoldier.jl/src/build.jl:55
 [9] build_julia! at /home/ubuntu/Nanosoldier.jl/src/build.jl:25 [inlined]
 [10] execute_benchmarks!(::Nanosoldier.BenchmarkJob, ::Symbol) at /home/ubuntu/Nanosoldier.jl/src/jobs/BenchmarkJob.jl:263
 [11] run(::Nanosoldier.BenchmarkJob) at /home/ubuntu/Nanosoldier.jl/src/jobs/BenchmarkJob.jl:202
 [12] (::Distributed.var"#106#108"{Distributed.CallMsg{:call_fetch}})() at /buildworker/worker/package_linux64/build/usr/share/julia/stdlib/v1.5/Distributed/src/process_messages.jl:294
 [13] run_work_thunk(::Distributed.var"#106#108"{Distributed.CallMsg{:call_fetch}}, ::Bool) at /buildworker/worker/package_linux64/build/usr/share/julia/stdlib/v1.5/Distributed/src/process_messages.jl:79
 [14] macro expansion at /buildworker/worker/package_linux64/build/usr/share/julia/stdlib/v1.5/Distributed/src/process_messages.jl:294 [inlined]
 [15] (::Distributed.var"#105#107"{Distributed.CallMsg{:call_fetch},Distributed.MsgHeader,Sockets.TCPSocket})() at ./task.jl:356
```

Check the logs folder in this directory for more detailed output.

