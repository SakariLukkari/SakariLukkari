## Hi, I'm Sakari 👋

Network and security specialist from Finland. In my own time I fuzz and harden the open-source software that home and small-office networks run on: routers, DHCP clients and servers, port mapping, and time sync.

### What I work on
- **Fuzzing network daemons.** I write in-process libFuzzer/AFL++ harnesses with ASan/UBSan that drive the real request parsers, plus logic oracles for bugs that do not crash.
- **Fixing what I find.** Every report I send comes with a reproducer and a patch, and goes to the maintainers privately first.
- **Coverage-guided triage.** I use llvm-cov to find code the fuzzers do not reach yet, minimise crashes and confirm them in an isolated lab.

### Contributions
| Project | What | Status |
|---|---|---|
| [miniupnpd](https://github.com/miniupnp/miniupnp) | Fuzz targets for HTTP/SOAP and PCP/NAT-PMP request handling ([#974](https://github.com/miniupnp/miniupnp/pull/974)) | Under review |

More will be listed here once fixes are public.

### Tools I use
`AFL++` · `libFuzzer` · `ASan/UBSan` · `llvm-cov` · `Docker` · `C` · `Python` · `Linux networking`

*I work with AI assistance (Claude Code). I run and check every result myself before it goes to a maintainer.*
