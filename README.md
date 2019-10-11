# java-microbenchmark
A simple project to demonstrate the use of MH (Java Microbenchmark Harness) framework

# Results
```

# JMH version: 1.21
# VM version: JDK 11.0.4, Java HotSpot(TM) 64-Bit Server VM, 11.0.4+10-LTS
# VM invoker: /Library/Java/JavaVirtualMachines/jdk-11.0.4.jdk/Contents/Home/bin/java
# VM options: -Xms2G -Xmx2G
# Warmup: 3 iterations, 10 s each
# Measurement: 10 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 1 thread, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.kds.benchmark.BenchMarkRegExEvaluation.patternMacher

# Run progress: 0.00% complete, ETA 00:08:40
# Fork: 1 of 2
# Warmup Iteration   1: ≈ 10⁻⁴ ms/op
# Warmup Iteration   2: ≈ 10⁻⁴ ms/op
# Warmup Iteration   3: ≈ 10⁻⁴ ms/op
Iteration   1: ≈ 10⁻⁴ ms/op
Iteration   2: ≈ 10⁻⁴ ms/op
Iteration   3: ≈ 10⁻⁴ ms/op
Iteration   4: ≈ 10⁻⁴ ms/op
Iteration   5: ≈ 10⁻⁴ ms/op
Iteration   6: ≈ 10⁻⁴ ms/op
Iteration   7: ≈ 10⁻⁴ ms/op
Iteration   8: ≈ 10⁻⁴ ms/op
Iteration   9: ≈ 10⁻⁴ ms/op
Iteration  10: ≈ 10⁻⁴ ms/op

# Run progress: 25.00% complete, ETA 00:06:32
# Fork: 2 of 2
# Warmup Iteration   1: ≈ 10⁻⁴ ms/op
# Warmup Iteration   2: ≈ 10⁻⁴ ms/op
# Warmup Iteration   3: ≈ 10⁻⁴ ms/op
Iteration   1: ≈ 10⁻⁴ ms/op
Iteration   2: ≈ 10⁻⁴ ms/op
Iteration   3: ≈ 10⁻⁴ ms/op
Iteration   4: ≈ 10⁻⁴ ms/op
Iteration   5: ≈ 10⁻⁴ ms/op
Iteration   6: ≈ 10⁻⁴ ms/op
Iteration   7: ≈ 10⁻⁴ ms/op
Iteration   8: ≈ 10⁻⁴ ms/op
Iteration   9: ≈ 10⁻⁴ ms/op
Iteration  10: ≈ 10⁻⁴ ms/op


Result "org.kds.benchmark.BenchMarkRegExEvaluation.patternMacher": ≈ 10⁻⁴ ms/op


# JMH version: 1.21
# VM version: JDK 11.0.4, Java HotSpot(TM) 64-Bit Server VM, 11.0.4+10-LTS
# VM invoker: /Library/Java/JavaVirtualMachines/jdk-11.0.4.jdk/Contents/Home/bin/java
# VM options: -Xms2G -Xmx2G
# Warmup: 3 iterations, 10 s each
# Measurement: 10 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 1 thread, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.kds.benchmark.BenchMarkRegExEvaluation.stringMacher

# Run progress: 50.00% complete, ETA 00:04:21
# Fork: 1 of 2
# Warmup Iteration   1: 0.006 ms/op
# Warmup Iteration   2: 0.005 ms/op
# Warmup Iteration   3: 0.005 ms/op
Iteration   1: 0.005 ms/op
Iteration   2: 0.005 ms/op
Iteration   3: 0.005 ms/op
Iteration   4: 0.005 ms/op
Iteration   5: 0.005 ms/op
Iteration   6: 0.005 ms/op
Iteration   7: 0.005 ms/op
Iteration   8: 0.005 ms/op
Iteration   9: 0.005 ms/op
Iteration  10: 0.005 ms/op

# Run progress: 75.00% complete, ETA 00:02:10
# Fork: 2 of 2
# Warmup Iteration   1: 0.006 ms/op
# Warmup Iteration   2: 0.005 ms/op
# Warmup Iteration   3: 0.005 ms/op
Iteration   1: 0.005 ms/op
Iteration   2: 0.005 ms/op
Iteration   3: 0.005 ms/op
Iteration   4: 0.005 ms/op
Iteration   5: 0.005 ms/op
Iteration   6: 0.005 ms/op
Iteration   7: 0.005 ms/op
Iteration   8: 0.005 ms/op
Iteration   9: 0.005 ms/op
Iteration  10: 0.005 ms/op


Result "org.kds.benchmark.BenchMarkRegExEvaluation.stringMacher":
  0.005 ±(99.9%) 0.001 ms/op [Average]
  (min, avg, max) = (0.005, 0.005, 0.005), stdev = 0.001
  CI (99.9%): [0.005, 0.005] (assumes normal distribution)


# Run complete. Total time: 00:08:43

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode  Cnt   Score    Error  Units
BenchMarkRegExEvaluation.patternMacher  avgt   20  ≈ 10⁻⁴           ms/op
BenchMarkRegExEvaluation.stringMacher   avgt   20   0.005 ±  0.001  ms/op

```
