# Benchmark Report

## Job Properties

*Commits:* [vtjnash/julia@d7da2a4a327b47f4969b40a9feadef3b2b825eda](https://github.com/vtjnash/julia/commit/d7da2a4a327b47f4969b40a9feadef3b2b825eda) vs [vtjnash/julia@notmaster](https://github.com/vtjnash/julia/commit/notmaster)

*Comparison Diff:* [link](https://github.com/vtjnash/julia/compare/notmaster..d7da2a4a327b47f4969b40a9feadef3b2b825eda)

*Triggered By:* [link](https://github.com/vtjnash/julia/commit/d7da2a4a327b47f4969b40a9feadef3b2b825eda#commitcomment-48322287)

*Tag Predicate:* `ALL`

## Error

The build could not finish due to an error:

```
NanosoldierError: failed to run benchmarks against primary commit: failed process: Process(`sudo /data/vtjnash/nanosoldierbot/cset/bin/cset shield -e su vtjnash -- -c /home/vtjnash/test_workdir/jl_YXVWhv/benchscript.sh`, ProcessExited(1)) [1]

Stacktrace:
 [1] pipeline_error at ./process.jl:525 [inlined]
 [2] run(::Cmd; wait::Bool) at ./process.jl:440
 [3] run at ./process.jl:438 [inlined]
 [4] execute_benchmarks!(::Nanosoldier.BenchmarkJob, ::String, ::Symbol) at /data/vtjnash/nanosoldierbot/Nanosoldier.jl/src/jobs/BenchmarkJob.jl:468
 [5] run(::Nanosoldier.BenchmarkJob) at /data/vtjnash/nanosoldierbot/Nanosoldier.jl/src/jobs/BenchmarkJob.jl:228
 [6] (::Distributed.var"#106#108"{Distributed.CallMsg{:call_fetch}})() at /buildworker/worker/package_linux64/build/usr/share/julia/stdlib/v1.5/Distributed/src/process_messages.jl:294
 [7] run_work_thunk(::Distributed.var"#106#108"{Distributed.CallMsg{:call_fetch}}, ::Bool) at /buildworker/worker/package_linux64/build/usr/share/julia/stdlib/v1.5/Distributed/src/process_messages.jl:79
 [8] macro expansion at /buildworker/worker/package_linux64/build/usr/share/julia/stdlib/v1.5/Distributed/src/process_messages.jl:294 [inlined]
 [9] (::Distributed.var"#105#107"{Distributed.CallMsg{:call_fetch},Distributed.MsgHeader,Sockets.TCPSocket})() at ./task.jl:356
```

Check the logs folder in this directory for more detailed output.

