# Nathan

Backend and distributed systems engineer working with Java 21, Go, and Neovim tooling.

I focus on low-latency concurrency, production JVM diagnostics, resilient service gateways, and fast developer tools.

## Featured Projects

- **[WATTOM](https://github.com/barthollomew/WATTOM)**: Hot-attach Java 21 diagnostic agent that streams JFR events, detects virtual thread pinning and carrier starvation, tracks TLAB allocation rates, and instruments method p99 latency in live JVMs without a restart.
- **[NOPE](https://github.com/barthollomew/NOPE)**: Adaptive Java 21 load-shedding library that combines RFC 8289 CoDel sojourn tracking, Little's Law concurrency limits, VarHandle semaphores, and three-tier priority queues with sub-microsecond hot-path latency.
- **[SLOPWALL](https://github.com/barthollomew/SLOPWALL)**: Java 21 LLM gateway library featuring lock-free token bucket budgets, sliding-window circuit breakers, structured concurrency failover, and WAL-mode SQLite semantic caching.
- **[HL2DEM](https://github.com/barthollomew/HL2DEM)**: Counter-Strike 2 Source 2 demo parser built on Java 21 `MemorySegment` zero-copy reads, Snappy frame unpacking, custom Huffman field-path decoding, and virtual-thread streaming export.
- **[check-this.nvim](https://github.com/barthollomew/check-this.nvim)**: Neovim plugin and CGO Tree-sitter Go AST analyzer that flags production reliability risks (unbounded retries, missing network timeouts, swallowed errors, and mutable global state) inline as you type.
- **[why-is-this-slow](https://github.com/barthollomew/why-is-this-slow)**: Go CLI that measures command wall time, `rusage` CPU time, and max RSS across repeat runs to classify workloads as I/O wait, CPU bound, or parallel CPU and compare runs for regressions.

## Core Focus

- **JVM & Concurrency**: Java 21, Virtual Threads, Structured Concurrency, JDK Flight Recorder (JFR), ByteBuddy bytecode instrumentation, `MemorySegment` (FFM API), `VarHandle` lock-free primitives, and JMH microbenchmarking.
- **Systems & Developer Tooling**: Go, Tree-sitter AST analysis, Unix process telemetry (`rusage`), Neovim Lua plugins, and SQLite embedded storage.
