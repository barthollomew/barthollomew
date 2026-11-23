# Nathan

Backend engineer building in Java and Go. I like fast systems, simple tools, and keeping production servers alive.

## Projects

- **[WATTOM](https://github.com/barthollomew/WATTOM)**: Attach to a frozen Java app by PID and see why it is stuck (CPU, memory allocation rate, deadlocks, pinned Java 21 virtual threads, and live method latency) without restarting it.
- **[NOPE](https://github.com/barthollomew/NOPE)**: Drop background requests first during traffic spikes so login and checkout stay fast. Uses CoDel queue wait times and three priority tiers in Java 21.
- **[SLOPWALL](https://github.com/barthollomew/SLOPWALL)**: Put per-user token limits, automatic provider failover, and a local SQLite cache in front of OpenAI and Anthropic calls in Java 21.
- **[HL2DEM](https://github.com/barthollomew/HL2DEM)**: Turn Counter-Strike 2 match replay files (`.dem`) into tick-by-tick player JSON or CSV using Java 21 `MemorySegment` zero-copy reads and Snappy frame unpacking.
- **[check-this.nvim](https://github.com/barthollomew/check-this.nvim)**: Neovim plugin and Go Tree-sitter analyzer that flags missing network timeouts, infinite retries, and swallowed errors while you edit.
- **[why-is-this-slow](https://github.com/barthollomew/why-is-this-slow)**: Run any slow terminal command and see whether it is waiting on disk/network or burning CPU, then compare runs over time.

## Open Source Contributions

### JVM Ecosystem
- **[FasterXML/jackson-core#1834](https://github.com/FasterXML/jackson-core/pull/1834)**: Preserve textual flag in redacted `ContentReference`.
- **[wiremock/wiremock#3695](https://github.com/wiremock/wiremock/pull/3695)**: Do not match present empty array against `absent()` in `matchingJsonPath`.
- **[pmd/pmd#7382](https://github.com/pmd/pmd/pull/7382)**: Do not count calls on other objects as recursion in `CognitiveComplexity`.
- **[hcoles/pitest#1513](https://github.com/hcoles/pitest/pull/1513)**: Support `fullMutationMatrix` XML fields in `pitest-aggregator`.
- **[awaitility/awaitility#343](https://github.com/awaitility/awaitility/pull/343)**: Add poll delay getters to `StartEvaluationEvent`.
- **[jk1/Gradle-License-Report#433](https://github.com/jk1/Gradle-License-Report/pull/433)**: Narrow BSD-3-Clause rules and map related licenses.

### Neovim & Lua Ecosystem
- **[neovim/nvim-lspconfig#4581](https://github.com/neovim/nvim-lspconfig/pull/4581)**: Set default diagnostic source for `termux_language_server`.
- **[obsidian-nvim/obsidian.nvim#1032](https://github.com/obsidian-nvim/obsidian.nvim/pull/1032)**: Keep first line in visual line mode (merged).
- **[lunarmodules/Penlight#539](https://github.com/lunarmodules/Penlight/pull/539)**: Document `types.is_type` subclass behavior (merged).
- **[nvimtools/none-ls.nvim#354](https://github.com/nvimtools/none-ls.nvim/pull/354)**: Keep `codespell` diagnostics when `--count` is used.
- **[hedyhli/outline.nvim#178](https://github.com/hedyhli/outline.nvim/pull/178)**: Refresh highlight defaults on colorscheme change.
