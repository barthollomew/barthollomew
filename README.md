Most Java services do not need another framework. The JDK already gives you virtual threads and Flight Recorder and raw memory access. Every giant dependency you add is another thing to debug at 3am.

A few things I believe after writing Java and Go:

- A fast 503 is better than a slow 200. If your server is drowning drop the batch jobs first so real users can still log in.
- If you have to restart a frozen server to see why it is frozen you already lost the bug.
- Most outages come from boring mistakes like a missing HTTP timeout or a `while True` retry loop or an empty `catch` block.
- Measure wall time and CPU before you guess why something is slow.

My repos are pinned below. I also send bug fixes upstream to tools I use ([jackson-core](https://github.com/FasterXML/jackson-core/pull/1834) / [wiremock](https://github.com/wiremock/wiremock/pull/3695) / [pmd](https://github.com/pmd/pmd/pull/7382) / [pitest](https://github.com/hcoles/pitest/pull/1513) / [awaitility](https://github.com/awaitility/awaitility/pull/343) / [nvim-lspconfig](https://github.com/neovim/nvim-lspconfig/pull/4581) / [obsidian.nvim](https://github.com/obsidian-nvim/obsidian.nvim/pull/1032)).
