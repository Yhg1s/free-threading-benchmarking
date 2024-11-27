# Faster CPython Benchmark Infrastructure

🔒 [▶️ START A BENCHMARK RUN](../../actions/workflows/benchmark.yml)

## Results

Here are some recent and important revisions. 👉 [Complete list of results](RESULTS.md).

<!-- START table -->
[Most recent pystats on main (dbd2379)](results/bm-20241123-3.14.0a2%2B-dbd2379-PYTHON_UOPS/bm-20241123-vultr-x86_64-python-dbd23790dbd662169905-3.14.0a2%2B-dbd2379-pystats.md)

## linux x86_64 (linux)
| date | fork/ref | hash/flags | vs. 3.12.6: | vs. 3.13.0rc2: | vs. base: |
| --- | --- | --- | ---: | ---: | ---: |
| [2024-11-26](results/bm-20241126-3.14.0a2%2B-71ede11) | python/71ede1142ddad2d31cc9 | 71ede11 | 1.064x ↑<br>[📄](results/bm-20241126-3.14.0a2%2B-71ede11/bm-20241126-linux-x86_64-python-71ede1142ddad2d31cc9-3.14.0a2%2B-71ede11-vs-3.12.6.md)[📈](results/bm-20241126-3.14.0a2%2B-71ede11/bm-20241126-linux-x86_64-python-71ede1142ddad2d31cc9-3.14.0a2%2B-71ede11-vs-3.12.6.svg) | 1.022x ↑<br>[📄](results/bm-20241126-3.14.0a2%2B-71ede11/bm-20241126-linux-x86_64-python-71ede1142ddad2d31cc9-3.14.0a2%2B-71ede11-vs-3.13.0rc2.md)[📈](results/bm-20241126-3.14.0a2%2B-71ede11/bm-20241126-linux-x86_64-python-71ede1142ddad2d31cc9-3.14.0a2%2B-71ede11-vs-3.13.0rc2.svg) |  |
| [2024-11-26](results/bm-20241126-3.14.0a2%2B-71ede11-NOGIL) | python/71ede1142ddad2d31cc9 | 71ede11 (NOGIL) | 1.231x ↓<br>[📄](results/bm-20241126-3.14.0a2%2B-71ede11-NOGIL/bm-20241126-linux-x86_64-python-71ede1142ddad2d31cc9-3.14.0a2%2B-71ede11-vs-3.12.6.md)[📈](results/bm-20241126-3.14.0a2%2B-71ede11-NOGIL/bm-20241126-linux-x86_64-python-71ede1142ddad2d31cc9-3.14.0a2%2B-71ede11-vs-3.12.6.svg) | 1.261x ↓<br>[📄](results/bm-20241126-3.14.0a2%2B-71ede11-NOGIL/bm-20241126-linux-x86_64-python-71ede1142ddad2d31cc9-3.14.0a2%2B-71ede11-vs-3.13.0rc2.md)[📈](results/bm-20241126-3.14.0a2%2B-71ede11-NOGIL/bm-20241126-linux-x86_64-python-71ede1142ddad2d31cc9-3.14.0a2%2B-71ede11-vs-3.13.0rc2.svg) | 1.267x ↓<br>[📄](results/bm-20241126-3.14.0a2%2B-71ede11-NOGIL/bm-20241126-linux-x86_64-python-71ede1142ddad2d31cc9-3.14.0a2%2B-71ede11-vs-base.md)[📈](results/bm-20241126-3.14.0a2%2B-71ede11-NOGIL/bm-20241126-linux-x86_64-python-71ede1142ddad2d31cc9-3.14.0a2%2B-71ede11-vs-base.svg)[🧠](results/bm-20241126-3.14.0a2%2B-71ede11-NOGIL/bm-20241126-linux-x86_64-python-71ede1142ddad2d31cc9-3.14.0a2%2B-71ede11-vs-base-mem.svg) |
| [2024-11-25](results/bm-20241125-3.14.0a2%2B-26ff32b) | python/26ff32b30553e1f7b0cc | 26ff32b | 1.083x ↑<br>[📄](results/bm-20241125-3.14.0a2%2B-26ff32b/bm-20241125-linux-x86_64-python-26ff32b30553e1f7b0cc-3.14.0a2%2B-26ff32b-vs-3.12.6.md)[📈](results/bm-20241125-3.14.0a2%2B-26ff32b/bm-20241125-linux-x86_64-python-26ff32b30553e1f7b0cc-3.14.0a2%2B-26ff32b-vs-3.12.6.svg) | 1.039x ↑<br>[📄](results/bm-20241125-3.14.0a2%2B-26ff32b/bm-20241125-linux-x86_64-python-26ff32b30553e1f7b0cc-3.14.0a2%2B-26ff32b-vs-3.13.0rc2.md)[📈](results/bm-20241125-3.14.0a2%2B-26ff32b/bm-20241125-linux-x86_64-python-26ff32b30553e1f7b0cc-3.14.0a2%2B-26ff32b-vs-3.13.0rc2.svg) |  |
| [2024-11-25](results/bm-20241125-3.14.0a2%2B-26ff32b-NOGIL) | python/26ff32b30553e1f7b0cc | 26ff32b (NOGIL) | 1.196x ↓<br>[📄](results/bm-20241125-3.14.0a2%2B-26ff32b-NOGIL/bm-20241125-linux-x86_64-python-26ff32b30553e1f7b0cc-3.14.0a2%2B-26ff32b-vs-3.12.6.md)[📈](results/bm-20241125-3.14.0a2%2B-26ff32b-NOGIL/bm-20241125-linux-x86_64-python-26ff32b30553e1f7b0cc-3.14.0a2%2B-26ff32b-vs-3.12.6.svg) | 1.226x ↓<br>[📄](results/bm-20241125-3.14.0a2%2B-26ff32b-NOGIL/bm-20241125-linux-x86_64-python-26ff32b30553e1f7b0cc-3.14.0a2%2B-26ff32b-vs-3.13.0rc2.md)[📈](results/bm-20241125-3.14.0a2%2B-26ff32b-NOGIL/bm-20241125-linux-x86_64-python-26ff32b30553e1f7b0cc-3.14.0a2%2B-26ff32b-vs-3.13.0rc2.svg) | 1.248x ↓<br>[📄](results/bm-20241125-3.14.0a2%2B-26ff32b-NOGIL/bm-20241125-linux-x86_64-python-26ff32b30553e1f7b0cc-3.14.0a2%2B-26ff32b-vs-base.md)[📈](results/bm-20241125-3.14.0a2%2B-26ff32b-NOGIL/bm-20241125-linux-x86_64-python-26ff32b30553e1f7b0cc-3.14.0a2%2B-26ff32b-vs-base.svg)[🧠](results/bm-20241125-3.14.0a2%2B-26ff32b-NOGIL/bm-20241125-linux-x86_64-python-26ff32b30553e1f7b0cc-3.14.0a2%2B-26ff32b-vs-base-mem.svg) |
| [2024-11-24](results/bm-20241124-3.14.0a2%2B-17c16ae) | python/17c16aea66b606d66f71 | 17c16ae | not sig<br>[📄](results/bm-20241124-3.14.0a2%2B-17c16ae/bm-20241124-linux-x86_64-python-17c16aea66b606d66f71-3.14.0a2%2B-17c16ae-vs-3.12.6.md)[📈](results/bm-20241124-3.14.0a2%2B-17c16ae/bm-20241124-linux-x86_64-python-17c16aea66b606d66f71-3.14.0a2%2B-17c16ae-vs-3.12.6.svg) | not sig<br>[📄](results/bm-20241124-3.14.0a2%2B-17c16ae/bm-20241124-linux-x86_64-python-17c16aea66b606d66f71-3.14.0a2%2B-17c16ae-vs-3.13.0rc2.md)[📈](results/bm-20241124-3.14.0a2%2B-17c16ae/bm-20241124-linux-x86_64-python-17c16aea66b606d66f71-3.14.0a2%2B-17c16ae-vs-3.13.0rc2.svg) |  |
| [2024-11-24](results/bm-20241124-3.14.0a2%2B-17c16ae-NOGIL) | python/17c16aea66b606d66f71 | 17c16ae (NOGIL) | not sig<br>[📄](results/bm-20241124-3.14.0a2%2B-17c16ae-NOGIL/bm-20241124-linux-x86_64-python-17c16aea66b606d66f71-3.14.0a2%2B-17c16ae-vs-3.12.6.md)[📈](results/bm-20241124-3.14.0a2%2B-17c16ae-NOGIL/bm-20241124-linux-x86_64-python-17c16aea66b606d66f71-3.14.0a2%2B-17c16ae-vs-3.12.6.svg) | not sig<br>[📄](results/bm-20241124-3.14.0a2%2B-17c16ae-NOGIL/bm-20241124-linux-x86_64-python-17c16aea66b606d66f71-3.14.0a2%2B-17c16ae-vs-3.13.0rc2.md)[📈](results/bm-20241124-3.14.0a2%2B-17c16ae-NOGIL/bm-20241124-linux-x86_64-python-17c16aea66b606d66f71-3.14.0a2%2B-17c16ae-vs-3.13.0rc2.svg) | not sig<br>[📄](results/bm-20241124-3.14.0a2%2B-17c16ae-NOGIL/bm-20241124-linux-x86_64-python-17c16aea66b606d66f71-3.14.0a2%2B-17c16ae-vs-base.md)[📈](results/bm-20241124-3.14.0a2%2B-17c16ae-NOGIL/bm-20241124-linux-x86_64-python-17c16aea66b606d66f71-3.14.0a2%2B-17c16ae-vs-base.svg)[🧠](results/bm-20241124-3.14.0a2%2B-17c16ae-NOGIL/bm-20241124-linux-x86_64-python-17c16aea66b606d66f71-3.14.0a2%2B-17c16ae-vs-base-mem.svg) |
| [2024-11-23](results/bm-20241123-3.14.0a2%2B-dbd2379-NOGIL) | python/dbd23790dbd662169905 | dbd2379 (NOGIL) | not sig<br>[📄](results/bm-20241123-3.14.0a2%2B-dbd2379-NOGIL/bm-20241123-linux-x86_64-python-dbd23790dbd662169905-3.14.0a2%2B-dbd2379-vs-3.12.6.md)[📈](results/bm-20241123-3.14.0a2%2B-dbd2379-NOGIL/bm-20241123-linux-x86_64-python-dbd23790dbd662169905-3.14.0a2%2B-dbd2379-vs-3.12.6.svg) | not sig<br>[📄](results/bm-20241123-3.14.0a2%2B-dbd2379-NOGIL/bm-20241123-linux-x86_64-python-dbd23790dbd662169905-3.14.0a2%2B-dbd2379-vs-3.13.0rc2.md)[📈](results/bm-20241123-3.14.0a2%2B-dbd2379-NOGIL/bm-20241123-linux-x86_64-python-dbd23790dbd662169905-3.14.0a2%2B-dbd2379-vs-3.13.0rc2.svg) | not sig<br>[📄](results/bm-20241123-3.14.0a2%2B-dbd2379-NOGIL/bm-20241123-linux-x86_64-python-dbd23790dbd662169905-3.14.0a2%2B-dbd2379-vs-base.md)[📈](results/bm-20241123-3.14.0a2%2B-dbd2379-NOGIL/bm-20241123-linux-x86_64-python-dbd23790dbd662169905-3.14.0a2%2B-dbd2379-vs-base.svg)[🧠](results/bm-20241123-3.14.0a2%2B-dbd2379-NOGIL/bm-20241123-linux-x86_64-python-dbd23790dbd662169905-3.14.0a2%2B-dbd2379-vs-base-mem.svg) |
| [2024-11-23](results/bm-20241123-3.14.0a2%2B-dbd2379) | python/dbd23790dbd662169905 | dbd2379 | not sig<br>[📄](results/bm-20241123-3.14.0a2%2B-dbd2379/bm-20241123-linux-x86_64-python-dbd23790dbd662169905-3.14.0a2%2B-dbd2379-vs-3.12.6.md)[📈](results/bm-20241123-3.14.0a2%2B-dbd2379/bm-20241123-linux-x86_64-python-dbd23790dbd662169905-3.14.0a2%2B-dbd2379-vs-3.12.6.svg) | not sig<br>[📄](results/bm-20241123-3.14.0a2%2B-dbd2379/bm-20241123-linux-x86_64-python-dbd23790dbd662169905-3.14.0a2%2B-dbd2379-vs-3.13.0rc2.md)[📈](results/bm-20241123-3.14.0a2%2B-dbd2379/bm-20241123-linux-x86_64-python-dbd23790dbd662169905-3.14.0a2%2B-dbd2379-vs-3.13.0rc2.svg) |  |

## linux x86_64 (vultr)
| date | fork/ref | hash/flags | vs. 3.12.6: | vs. 3.13.0rc2: | vs. base: |
| --- | --- | --- | ---: | ---: | ---: |
| [2024-11-28](results/bm-20241128-3.14.0a2%2B-6e2f5fe) | corona10/gh_115999_binary_sub | 6e2f5fe | 1.036x ↑<br>[📄](results/bm-20241128-3.14.0a2%2B-6e2f5fe/bm-20241128-vultr-x86_64-corona10-gh_115999_binary_sub-3.14.0a2%2B-6e2f5fe-vs-3.12.6.md)[📈](results/bm-20241128-3.14.0a2%2B-6e2f5fe/bm-20241128-vultr-x86_64-corona10-gh_115999_binary_sub-3.14.0a2%2B-6e2f5fe-vs-3.12.6.svg) | 1.001x ↓<br>[📄](results/bm-20241128-3.14.0a2%2B-6e2f5fe/bm-20241128-vultr-x86_64-corona10-gh_115999_binary_sub-3.14.0a2%2B-6e2f5fe-vs-3.13.0rc2.md)[📈](results/bm-20241128-3.14.0a2%2B-6e2f5fe/bm-20241128-vultr-x86_64-corona10-gh_115999_binary_sub-3.14.0a2%2B-6e2f5fe-vs-3.13.0rc2.svg) | 1.003x ↑<br>[📄](results/bm-20241128-3.14.0a2%2B-6e2f5fe/bm-20241128-vultr-x86_64-corona10-gh_115999_binary_sub-3.14.0a2%2B-6e2f5fe-vs-base.md)[📈](results/bm-20241128-3.14.0a2%2B-6e2f5fe/bm-20241128-vultr-x86_64-corona10-gh_115999_binary_sub-3.14.0a2%2B-6e2f5fe-vs-base.svg)[🧠](results/bm-20241128-3.14.0a2%2B-6e2f5fe/bm-20241128-vultr-x86_64-corona10-gh_115999_binary_sub-3.14.0a2%2B-6e2f5fe-vs-base-mem.svg) |
| [2024-11-27](results/bm-20241127-3.14.0a2%2B-58e334e) | python/58e334e1431b2ed6b70e | 58e334e | 1.034x ↑<br>[📄](results/bm-20241127-3.14.0a2%2B-58e334e/bm-20241127-vultr-x86_64-python-58e334e1431b2ed6b70e-3.14.0a2%2B-58e334e-vs-3.12.6.md)[📈](results/bm-20241127-3.14.0a2%2B-58e334e/bm-20241127-vultr-x86_64-python-58e334e1431b2ed6b70e-3.14.0a2%2B-58e334e-vs-3.12.6.svg) | 1.004x ↓<br>[📄](results/bm-20241127-3.14.0a2%2B-58e334e/bm-20241127-vultr-x86_64-python-58e334e1431b2ed6b70e-3.14.0a2%2B-58e334e-vs-3.13.0rc2.md)[📈](results/bm-20241127-3.14.0a2%2B-58e334e/bm-20241127-vultr-x86_64-python-58e334e1431b2ed6b70e-3.14.0a2%2B-58e334e-vs-3.13.0rc2.svg) |  |
| [2024-11-26](results/bm-20241126-3.14.0a2%2B-71ede11) | python/71ede1142ddad2d31cc9 | 71ede11 | 1.031x ↑<br>[📄](results/bm-20241126-3.14.0a2%2B-71ede11/bm-20241126-vultr-x86_64-python-71ede1142ddad2d31cc9-3.14.0a2%2B-71ede11-vs-3.12.6.md)[📈](results/bm-20241126-3.14.0a2%2B-71ede11/bm-20241126-vultr-x86_64-python-71ede1142ddad2d31cc9-3.14.0a2%2B-71ede11-vs-3.12.6.svg) | 1.006x ↓<br>[📄](results/bm-20241126-3.14.0a2%2B-71ede11/bm-20241126-vultr-x86_64-python-71ede1142ddad2d31cc9-3.14.0a2%2B-71ede11-vs-3.13.0rc2.md)[📈](results/bm-20241126-3.14.0a2%2B-71ede11/bm-20241126-vultr-x86_64-python-71ede1142ddad2d31cc9-3.14.0a2%2B-71ede11-vs-3.13.0rc2.svg) |  |
| [2024-11-26](results/bm-20241126-3.14.0a2%2B-71ede11-NOGIL) | python/71ede1142ddad2d31cc9 | 71ede11 (NOGIL) | 1.262x ↓<br>[📄](results/bm-20241126-3.14.0a2%2B-71ede11-NOGIL/bm-20241126-vultr-x86_64-python-71ede1142ddad2d31cc9-3.14.0a2%2B-71ede11-vs-3.12.6.md)[📈](results/bm-20241126-3.14.0a2%2B-71ede11-NOGIL/bm-20241126-vultr-x86_64-python-71ede1142ddad2d31cc9-3.14.0a2%2B-71ede11-vs-3.12.6.svg) | 1.287x ↓<br>[📄](results/bm-20241126-3.14.0a2%2B-71ede11-NOGIL/bm-20241126-vultr-x86_64-python-71ede1142ddad2d31cc9-3.14.0a2%2B-71ede11-vs-3.13.0rc2.md)[📈](results/bm-20241126-3.14.0a2%2B-71ede11-NOGIL/bm-20241126-vultr-x86_64-python-71ede1142ddad2d31cc9-3.14.0a2%2B-71ede11-vs-3.13.0rc2.svg) | 1.277x ↓<br>[📄](results/bm-20241126-3.14.0a2%2B-71ede11-NOGIL/bm-20241126-vultr-x86_64-python-71ede1142ddad2d31cc9-3.14.0a2%2B-71ede11-vs-base.md)[📈](results/bm-20241126-3.14.0a2%2B-71ede11-NOGIL/bm-20241126-vultr-x86_64-python-71ede1142ddad2d31cc9-3.14.0a2%2B-71ede11-vs-base.svg)[🧠](results/bm-20241126-3.14.0a2%2B-71ede11-NOGIL/bm-20241126-vultr-x86_64-python-71ede1142ddad2d31cc9-3.14.0a2%2B-71ede11-vs-base-mem.svg) |
| [2024-11-26](results/bm-20241126-3.14.0a2%2B-ab3af14-NOGIL) | nascheme/gh_115999_load_super | ab3af14 (NOGIL) | 1.289x ↓<br>[📄](results/bm-20241126-3.14.0a2%2B-ab3af14-NOGIL/bm-20241126-vultr-x86_64-nascheme-gh_115999_load_super-3.14.0a2%2B-ab3af14-vs-3.12.6.md)[📈](results/bm-20241126-3.14.0a2%2B-ab3af14-NOGIL/bm-20241126-vultr-x86_64-nascheme-gh_115999_load_super-3.14.0a2%2B-ab3af14-vs-3.12.6.svg) | 1.313x ↓<br>[📄](results/bm-20241126-3.14.0a2%2B-ab3af14-NOGIL/bm-20241126-vultr-x86_64-nascheme-gh_115999_load_super-3.14.0a2%2B-ab3af14-vs-3.13.0rc2.md)[📈](results/bm-20241126-3.14.0a2%2B-ab3af14-NOGIL/bm-20241126-vultr-x86_64-nascheme-gh_115999_load_super-3.14.0a2%2B-ab3af14-vs-3.13.0rc2.svg) | 1.004x ↑<br>[📄](results/bm-20241126-3.14.0a2%2B-ab3af14-NOGIL/bm-20241126-vultr-x86_64-nascheme-gh_115999_load_super-3.14.0a2%2B-ab3af14-vs-base.md)[📈](results/bm-20241126-3.14.0a2%2B-ab3af14-NOGIL/bm-20241126-vultr-x86_64-nascheme-gh_115999_load_super-3.14.0a2%2B-ab3af14-vs-base.svg)[🧠](results/bm-20241126-3.14.0a2%2B-ab3af14-NOGIL/bm-20241126-vultr-x86_64-nascheme-gh_115999_load_super-3.14.0a2%2B-ab3af14-vs-base-mem.svg) |
| [2024-11-25](results/bm-20241125-3.14.0a2%2B-26ff32b) | python/26ff32b30553e1f7b0cc | 26ff32b | 1.037x ↑<br>[📄](results/bm-20241125-3.14.0a2%2B-26ff32b/bm-20241125-vultr-x86_64-python-26ff32b30553e1f7b0cc-3.14.0a2%2B-26ff32b-vs-3.12.6.md)[📈](results/bm-20241125-3.14.0a2%2B-26ff32b/bm-20241125-vultr-x86_64-python-26ff32b30553e1f7b0cc-3.14.0a2%2B-26ff32b-vs-3.12.6.svg) | 1.000x ↓<br>[📄](results/bm-20241125-3.14.0a2%2B-26ff32b/bm-20241125-vultr-x86_64-python-26ff32b30553e1f7b0cc-3.14.0a2%2B-26ff32b-vs-3.13.0rc2.md)[📈](results/bm-20241125-3.14.0a2%2B-26ff32b/bm-20241125-vultr-x86_64-python-26ff32b30553e1f7b0cc-3.14.0a2%2B-26ff32b-vs-3.13.0rc2.svg) |  |
| [2024-11-25](results/bm-20241125-3.14.0a2%2B-26ff32b-NOGIL) | python/26ff32b30553e1f7b0cc | 26ff32b (NOGIL) | 1.259x ↓<br>[📄](results/bm-20241125-3.14.0a2%2B-26ff32b-NOGIL/bm-20241125-vultr-x86_64-python-26ff32b30553e1f7b0cc-3.14.0a2%2B-26ff32b-vs-3.12.6.md)[📈](results/bm-20241125-3.14.0a2%2B-26ff32b-NOGIL/bm-20241125-vultr-x86_64-python-26ff32b30553e1f7b0cc-3.14.0a2%2B-26ff32b-vs-3.12.6.svg) | 1.284x ↓<br>[📄](results/bm-20241125-3.14.0a2%2B-26ff32b-NOGIL/bm-20241125-vultr-x86_64-python-26ff32b30553e1f7b0cc-3.14.0a2%2B-26ff32b-vs-3.13.0rc2.md)[📈](results/bm-20241125-3.14.0a2%2B-26ff32b-NOGIL/bm-20241125-vultr-x86_64-python-26ff32b30553e1f7b0cc-3.14.0a2%2B-26ff32b-vs-3.13.0rc2.svg) | 1.277x ↓<br>[📄](results/bm-20241125-3.14.0a2%2B-26ff32b-NOGIL/bm-20241125-vultr-x86_64-python-26ff32b30553e1f7b0cc-3.14.0a2%2B-26ff32b-vs-base.md)[📈](results/bm-20241125-3.14.0a2%2B-26ff32b-NOGIL/bm-20241125-vultr-x86_64-python-26ff32b30553e1f7b0cc-3.14.0a2%2B-26ff32b-vs-base.svg)[🧠](results/bm-20241125-3.14.0a2%2B-26ff32b-NOGIL/bm-20241125-vultr-x86_64-python-26ff32b30553e1f7b0cc-3.14.0a2%2B-26ff32b-vs-base-mem.svg) |
| [2024-11-25](results/bm-20241125-3.14.0a2%2B-a515a0d-NOGIL) | nascheme/gh_115999_load_super | a515a0d (NOGIL) | 1.411x ↓<br>[📄](results/bm-20241125-3.14.0a2%2B-a515a0d-NOGIL/bm-20241125-vultr-x86_64-nascheme-gh_115999_load_super-3.14.0a2%2B-a515a0d-vs-3.12.6.md)[📈](results/bm-20241125-3.14.0a2%2B-a515a0d-NOGIL/bm-20241125-vultr-x86_64-nascheme-gh_115999_load_super-3.14.0a2%2B-a515a0d-vs-3.12.6.svg) | 1.431x ↓<br>[📄](results/bm-20241125-3.14.0a2%2B-a515a0d-NOGIL/bm-20241125-vultr-x86_64-nascheme-gh_115999_load_super-3.14.0a2%2B-a515a0d-vs-3.13.0rc2.md)[📈](results/bm-20241125-3.14.0a2%2B-a515a0d-NOGIL/bm-20241125-vultr-x86_64-nascheme-gh_115999_load_super-3.14.0a2%2B-a515a0d-vs-3.13.0rc2.svg) | 1.175x ↓<br>[📄](results/bm-20241125-3.14.0a2%2B-a515a0d-NOGIL/bm-20241125-vultr-x86_64-nascheme-gh_115999_load_super-3.14.0a2%2B-a515a0d-vs-base.md)[📈](results/bm-20241125-3.14.0a2%2B-a515a0d-NOGIL/bm-20241125-vultr-x86_64-nascheme-gh_115999_load_super-3.14.0a2%2B-a515a0d-vs-base.svg)[🧠](results/bm-20241125-3.14.0a2%2B-a515a0d-NOGIL/bm-20241125-vultr-x86_64-nascheme-gh_115999_load_super-3.14.0a2%2B-a515a0d-vs-base-mem.svg) |
| [2024-11-25](results/bm-20241125-3.14.0a2%2B-a515a0d) | nascheme/gh_115999_load_super | a515a0d | 1.039x ↑<br>[📄](results/bm-20241125-3.14.0a2%2B-a515a0d/bm-20241125-vultr-x86_64-nascheme-gh_115999_load_super-3.14.0a2%2B-a515a0d-vs-3.12.6.md)[📈](results/bm-20241125-3.14.0a2%2B-a515a0d/bm-20241125-vultr-x86_64-nascheme-gh_115999_load_super-3.14.0a2%2B-a515a0d-vs-3.12.6.svg) | 1.001x ↑<br>[📄](results/bm-20241125-3.14.0a2%2B-a515a0d/bm-20241125-vultr-x86_64-nascheme-gh_115999_load_super-3.14.0a2%2B-a515a0d-vs-3.13.0rc2.md)[📈](results/bm-20241125-3.14.0a2%2B-a515a0d/bm-20241125-vultr-x86_64-nascheme-gh_115999_load_super-3.14.0a2%2B-a515a0d-vs-3.13.0rc2.svg) | 1.002x ↑<br>[📄](results/bm-20241125-3.14.0a2%2B-a515a0d/bm-20241125-vultr-x86_64-nascheme-gh_115999_load_super-3.14.0a2%2B-a515a0d-vs-base.md)[📈](results/bm-20241125-3.14.0a2%2B-a515a0d/bm-20241125-vultr-x86_64-nascheme-gh_115999_load_super-3.14.0a2%2B-a515a0d-vs-base.svg)[🧠](results/bm-20241125-3.14.0a2%2B-a515a0d/bm-20241125-vultr-x86_64-nascheme-gh_115999_load_super-3.14.0a2%2B-a515a0d-vs-base-mem.svg) |
| [2024-11-24](results/bm-20241124-3.14.0a2%2B-17c16ae) | python/17c16aea66b606d66f71 | 17c16ae | not sig<br>[📄](results/bm-20241124-3.14.0a2%2B-17c16ae/bm-20241124-vultr-x86_64-python-17c16aea66b606d66f71-3.14.0a2%2B-17c16ae-vs-3.12.6.md)[📈](results/bm-20241124-3.14.0a2%2B-17c16ae/bm-20241124-vultr-x86_64-python-17c16aea66b606d66f71-3.14.0a2%2B-17c16ae-vs-3.12.6.svg) | not sig<br>[📄](results/bm-20241124-3.14.0a2%2B-17c16ae/bm-20241124-vultr-x86_64-python-17c16aea66b606d66f71-3.14.0a2%2B-17c16ae-vs-3.13.0rc2.md)[📈](results/bm-20241124-3.14.0a2%2B-17c16ae/bm-20241124-vultr-x86_64-python-17c16aea66b606d66f71-3.14.0a2%2B-17c16ae-vs-3.13.0rc2.svg) |  |
| [2024-11-24](results/bm-20241124-3.14.0a2%2B-17c16ae-NOGIL) | python/17c16aea66b606d66f71 | 17c16ae (NOGIL) | not sig<br>[📄](results/bm-20241124-3.14.0a2%2B-17c16ae-NOGIL/bm-20241124-vultr-x86_64-python-17c16aea66b606d66f71-3.14.0a2%2B-17c16ae-vs-3.12.6.md)[📈](results/bm-20241124-3.14.0a2%2B-17c16ae-NOGIL/bm-20241124-vultr-x86_64-python-17c16aea66b606d66f71-3.14.0a2%2B-17c16ae-vs-3.12.6.svg) | not sig<br>[📄](results/bm-20241124-3.14.0a2%2B-17c16ae-NOGIL/bm-20241124-vultr-x86_64-python-17c16aea66b606d66f71-3.14.0a2%2B-17c16ae-vs-3.13.0rc2.md)[📈](results/bm-20241124-3.14.0a2%2B-17c16ae-NOGIL/bm-20241124-vultr-x86_64-python-17c16aea66b606d66f71-3.14.0a2%2B-17c16ae-vs-3.13.0rc2.svg) | not sig<br>[📄](results/bm-20241124-3.14.0a2%2B-17c16ae-NOGIL/bm-20241124-vultr-x86_64-python-17c16aea66b606d66f71-3.14.0a2%2B-17c16ae-vs-base.md)[📈](results/bm-20241124-3.14.0a2%2B-17c16ae-NOGIL/bm-20241124-vultr-x86_64-python-17c16aea66b606d66f71-3.14.0a2%2B-17c16ae-vs-base.svg)[🧠](results/bm-20241124-3.14.0a2%2B-17c16ae-NOGIL/bm-20241124-vultr-x86_64-python-17c16aea66b606d66f71-3.14.0a2%2B-17c16ae-vs-base-mem.svg) |
| [2024-11-23](results/bm-20241123-3.14.0a2%2B-dbd2379-NOGIL) | python/dbd23790dbd662169905 | dbd2379 (NOGIL) | not sig<br>[📄](results/bm-20241123-3.14.0a2%2B-dbd2379-NOGIL/bm-20241123-vultr-x86_64-python-dbd23790dbd662169905-3.14.0a2%2B-dbd2379-vs-3.12.6.md)[📈](results/bm-20241123-3.14.0a2%2B-dbd2379-NOGIL/bm-20241123-vultr-x86_64-python-dbd23790dbd662169905-3.14.0a2%2B-dbd2379-vs-3.12.6.svg) | not sig<br>[📄](results/bm-20241123-3.14.0a2%2B-dbd2379-NOGIL/bm-20241123-vultr-x86_64-python-dbd23790dbd662169905-3.14.0a2%2B-dbd2379-vs-3.13.0rc2.md)[📈](results/bm-20241123-3.14.0a2%2B-dbd2379-NOGIL/bm-20241123-vultr-x86_64-python-dbd23790dbd662169905-3.14.0a2%2B-dbd2379-vs-3.13.0rc2.svg) | not sig<br>[📄](results/bm-20241123-3.14.0a2%2B-dbd2379-NOGIL/bm-20241123-vultr-x86_64-python-dbd23790dbd662169905-3.14.0a2%2B-dbd2379-vs-base.md)[📈](results/bm-20241123-3.14.0a2%2B-dbd2379-NOGIL/bm-20241123-vultr-x86_64-python-dbd23790dbd662169905-3.14.0a2%2B-dbd2379-vs-base.svg)[🧠](results/bm-20241123-3.14.0a2%2B-dbd2379-NOGIL/bm-20241123-vultr-x86_64-python-dbd23790dbd662169905-3.14.0a2%2B-dbd2379-vs-base-mem.svg) |
| [2024-11-23](results/bm-20241123-3.14.0a2%2B-dbd2379) | python/dbd23790dbd662169905 | dbd2379 | not sig<br>[📄](results/bm-20241123-3.14.0a2%2B-dbd2379/bm-20241123-vultr-x86_64-python-dbd23790dbd662169905-3.14.0a2%2B-dbd2379-vs-3.12.6.md)[📈](results/bm-20241123-3.14.0a2%2B-dbd2379/bm-20241123-vultr-x86_64-python-dbd23790dbd662169905-3.14.0a2%2B-dbd2379-vs-3.12.6.svg) | not sig<br>[📄](results/bm-20241123-3.14.0a2%2B-dbd2379/bm-20241123-vultr-x86_64-python-dbd23790dbd662169905-3.14.0a2%2B-dbd2379-vs-3.13.0rc2.md)[📈](results/bm-20241123-3.14.0a2%2B-dbd2379/bm-20241123-vultr-x86_64-python-dbd23790dbd662169905-3.14.0a2%2B-dbd2379-vs-3.13.0rc2.svg) |  |
| [2024-11-21](results/bm-20241121-3.14.0a2%2B-09c240f-NOGIL) | python/09c240f20c47db126ad7 | 09c240f (NOGIL) | 1.292x ↓<br>[📄](results/bm-20241121-3.14.0a2%2B-09c240f-NOGIL/bm-20241121-vultr-x86_64-python-09c240f20c47db126ad7-3.14.0a2%2B-09c240f-vs-3.12.6.md)[📈](results/bm-20241121-3.14.0a2%2B-09c240f-NOGIL/bm-20241121-vultr-x86_64-python-09c240f20c47db126ad7-3.14.0a2%2B-09c240f-vs-3.12.6.svg) | 1.316x ↓<br>[📄](results/bm-20241121-3.14.0a2%2B-09c240f-NOGIL/bm-20241121-vultr-x86_64-python-09c240f20c47db126ad7-3.14.0a2%2B-09c240f-vs-3.13.0rc2.md)[📈](results/bm-20241121-3.14.0a2%2B-09c240f-NOGIL/bm-20241121-vultr-x86_64-python-09c240f20c47db126ad7-3.14.0a2%2B-09c240f-vs-3.13.0rc2.svg) | 1.309x ↓<br>[📄](results/bm-20241121-3.14.0a2%2B-09c240f-NOGIL/bm-20241121-vultr-x86_64-python-09c240f20c47db126ad7-3.14.0a2%2B-09c240f-vs-base.md)[📈](results/bm-20241121-3.14.0a2%2B-09c240f-NOGIL/bm-20241121-vultr-x86_64-python-09c240f20c47db126ad7-3.14.0a2%2B-09c240f-vs-base.svg)[🧠](results/bm-20241121-3.14.0a2%2B-09c240f-NOGIL/bm-20241121-vultr-x86_64-python-09c240f20c47db126ad7-3.14.0a2%2B-09c240f-vs-base-mem.svg) |
| [2024-11-21](results/bm-20241121-3.14.0a2%2B-09c240f) | python/09c240f20c47db126ad7 | 09c240f | 1.038x ↑<br>[📄](results/bm-20241121-3.14.0a2%2B-09c240f/bm-20241121-vultr-x86_64-python-09c240f20c47db126ad7-3.14.0a2%2B-09c240f-vs-3.12.6.md)[📈](results/bm-20241121-3.14.0a2%2B-09c240f/bm-20241121-vultr-x86_64-python-09c240f20c47db126ad7-3.14.0a2%2B-09c240f-vs-3.12.6.svg) | 1.000x ↓<br>[📄](results/bm-20241121-3.14.0a2%2B-09c240f/bm-20241121-vultr-x86_64-python-09c240f20c47db126ad7-3.14.0a2%2B-09c240f-vs-3.13.0rc2.md)[📈](results/bm-20241121-3.14.0a2%2B-09c240f/bm-20241121-vultr-x86_64-python-09c240f20c47db126ad7-3.14.0a2%2B-09c240f-vs-3.13.0rc2.svg) |  |


<!-- END table -->

`*` indicates that the exact same versions of pyperformance was not used.

![Longitudinal speed improvement](/longitudinal.svg)

Improvement of the geometric mean of key merged benchmarks, computed with `pyperf compare`.
The results have a resolution of 0.01 (1%).

![Configuration speed improvement](/configs.svg)

## Documentation

### Running benchmarks from the GitHub web UI

Visit the 🔒 [benchmark action](../../actions/workflows/benchmark.yml) and click the "Run Workflow" button.

The available parameters are:

- `fork`: The fork of CPython to benchmark.
  If benchmarking a pull request, this would normally be your GitHub username.
- `ref`: The branch, tag or commit SHA to benchmark.
  If a SHA, it must be the full SHA, since finding it by a prefix is not supported.
- `machine`: The machine to run on.
  One of `linux-amd64` (default), `windows-amd64`, `darwin-arm64` or `all`.
- `benchmark_base`: If checked, the base of the selected branch will also be benchmarked.
  The base is determined by running `git merge-base upstream/main $ref`.
- `pystats`: If checked, collect the pystats from running the benchmarks.

To watch the progress of the benchmark, select it from the 🔒 [benchmark action page](../../actions/workflows/benchmark.yml).
It may be canceled from there as well.
To show only your benchmark workflows, select your GitHub ID from the "Actor" dropdown.

When the benchmarking is complete, the results are published to this repository and will appear in the [complete table](RESULTS.md).
Each set of benchmarks will have:

- The raw `.json` results from pyperformance.
- Comparisons against important reference releases, as well as the merge base of the branch if `benchmark_base` was selected. These include
  - A markdown table produced by `pyperf compare_to`.
  - A set of "violin" plots showing the distribution of results for each benchmark.

The most convenient way to get results locally is to clone this repo and `git pull` from it.

### Running benchmarks from the GitHub CLI

To automate benchmarking runs, it may be more convenient to use the [GitHub CLI](https://cli.github.com/).
Once you have `gh` installed and configured, you can run benchmarks by cloning this repository and then from inside it:

```bash session
gh workflow run benchmark.yml -f fork=me -f ref=my_branch
```

Any of the parameters described above are available at the commandline using the `-f key=value` syntax.

### Collecting Linux perf profiling data

To collect Linux perf sampling profile data for a benchmarking run, run the `_benchmark` action and check the `perf` checkbox.
Follow this by a run of the `_generate` action to regenerate the plots.

## License

This repo is licensed under the BSD 3-Clause License, as found in the LICENSE file.
