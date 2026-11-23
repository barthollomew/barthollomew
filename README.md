- Most Java services don't need another framework
- A fast 503 is better than a slow 200
- Most outages come from boring mistakes
- Measure wall time and CPU before you guess why something is slow.
- If you have to restart a frozen server to see why it is frozen then that is bad design

I also send bug fixes upstream to tools I use ([jackson-core](https://github.com/FasterXML/jackson-core/pull/1834) / [wiremock](https://github.com/wiremock/wiremock/pull/3695) / [pmd](https://github.com/pmd/pmd/pull/7382) / [pitest](https://github.com/hcoles/pitest/pull/1513) / [awaitility](https://github.com/awaitility/awaitility/pull/343) / [nvim-lspconfig](https://github.com/neovim/nvim-lspconfig/pull/4581) / [obsidian.nvim](https://github.com/obsidian-nvim/obsidian.nvim/pull/1032))
