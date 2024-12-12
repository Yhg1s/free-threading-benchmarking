# Faster CPython Benchmark Infrastructure

🔒 [▶️ START A BENCHMARK RUN](../../actions/workflows/benchmark.yml)

## Results

Here are some recent and important revisions. 👉 [Complete list of results](RESULTS.md).

<!-- START table -->
[Most recent pystats on main (79b7cab)](results/bm-20241207-3.14.0a2%2B-79b7cab-PYTHON_UOPS/bm-20241207-vultr-x86_64-python-79b7cab50a3292a1c014-3.14.0a2%2B-79b7cab-pystats.md)

## linux x86_64 (linux)
| date | fork/ref | hash/flags | vs. 3.12.6: | vs. 3.13.0rc2: | vs. base: |
| --- | --- | --- | ---: | ---: | ---: |
| [2024-12-11](results/bm-20241211-3.14.0a2%2B-12b4f1a-NOGIL) | python/12b4f1a5a175d4dcec27 | 12b4f1a (NOGIL) | 1.162x ↓<br>[📄](results/bm-20241211-3.14.0a2%2B-12b4f1a-NOGIL/bm-20241211-linux-x86_64-python-12b4f1a5a175d4dcec27-3.14.0a2%2B-12b4f1a-vs-3.12.6.md)[📈](results/bm-20241211-3.14.0a2%2B-12b4f1a-NOGIL/bm-20241211-linux-x86_64-python-12b4f1a5a175d4dcec27-3.14.0a2%2B-12b4f1a-vs-3.12.6.svg) | 1.191x ↓<br>[📄](results/bm-20241211-3.14.0a2%2B-12b4f1a-NOGIL/bm-20241211-linux-x86_64-python-12b4f1a5a175d4dcec27-3.14.0a2%2B-12b4f1a-vs-3.13.0rc2.md)[📈](results/bm-20241211-3.14.0a2%2B-12b4f1a-NOGIL/bm-20241211-linux-x86_64-python-12b4f1a5a175d4dcec27-3.14.0a2%2B-12b4f1a-vs-3.13.0rc2.svg) | 1.240x ↓<br>[📄](results/bm-20241211-3.14.0a2%2B-12b4f1a-NOGIL/bm-20241211-linux-x86_64-python-12b4f1a5a175d4dcec27-3.14.0a2%2B-12b4f1a-vs-base.md)[📈](results/bm-20241211-3.14.0a2%2B-12b4f1a-NOGIL/bm-20241211-linux-x86_64-python-12b4f1a5a175d4dcec27-3.14.0a2%2B-12b4f1a-vs-base.svg)[🧠](results/bm-20241211-3.14.0a2%2B-12b4f1a-NOGIL/bm-20241211-linux-x86_64-python-12b4f1a5a175d4dcec27-3.14.0a2%2B-12b4f1a-vs-base-mem.svg) |
| [2024-12-11](results/bm-20241211-3.14.0a2%2B-12b4f1a) | python/12b4f1a5a175d4dcec27 | 12b4f1a | 1.113x ↑<br>[📄](results/bm-20241211-3.14.0a2%2B-12b4f1a/bm-20241211-linux-x86_64-python-12b4f1a5a175d4dcec27-3.14.0a2%2B-12b4f1a-vs-3.12.6.md)[📈](results/bm-20241211-3.14.0a2%2B-12b4f1a/bm-20241211-linux-x86_64-python-12b4f1a5a175d4dcec27-3.14.0a2%2B-12b4f1a-vs-3.12.6.svg) | 1.068x ↑<br>[📄](results/bm-20241211-3.14.0a2%2B-12b4f1a/bm-20241211-linux-x86_64-python-12b4f1a5a175d4dcec27-3.14.0a2%2B-12b4f1a-vs-3.13.0rc2.md)[📈](results/bm-20241211-3.14.0a2%2B-12b4f1a/bm-20241211-linux-x86_64-python-12b4f1a5a175d4dcec27-3.14.0a2%2B-12b4f1a-vs-3.13.0rc2.svg) |  |
| [2024-12-09](results/bm-20241209-3.14.0a2%2B-5c89adf-NOGIL) | python/5c89adf385aaaca97c2e | 5c89adf (NOGIL) | 1.164x ↓<br>[📄](results/bm-20241209-3.14.0a2%2B-5c89adf-NOGIL/bm-20241209-linux-x86_64-python-5c89adf385aaaca97c2e-3.14.0a2%2B-5c89adf-vs-3.12.6.md)[📈](results/bm-20241209-3.14.0a2%2B-5c89adf-NOGIL/bm-20241209-linux-x86_64-python-5c89adf385aaaca97c2e-3.14.0a2%2B-5c89adf-vs-3.12.6.svg) | 1.194x ↓<br>[📄](results/bm-20241209-3.14.0a2%2B-5c89adf-NOGIL/bm-20241209-linux-x86_64-python-5c89adf385aaaca97c2e-3.14.0a2%2B-5c89adf-vs-3.13.0rc2.md)[📈](results/bm-20241209-3.14.0a2%2B-5c89adf-NOGIL/bm-20241209-linux-x86_64-python-5c89adf385aaaca97c2e-3.14.0a2%2B-5c89adf-vs-3.13.0rc2.svg) | 1.247x ↓<br>[📄](results/bm-20241209-3.14.0a2%2B-5c89adf-NOGIL/bm-20241209-linux-x86_64-python-5c89adf385aaaca97c2e-3.14.0a2%2B-5c89adf-vs-base.md)[📈](results/bm-20241209-3.14.0a2%2B-5c89adf-NOGIL/bm-20241209-linux-x86_64-python-5c89adf385aaaca97c2e-3.14.0a2%2B-5c89adf-vs-base.svg)[🧠](results/bm-20241209-3.14.0a2%2B-5c89adf-NOGIL/bm-20241209-linux-x86_64-python-5c89adf385aaaca97c2e-3.14.0a2%2B-5c89adf-vs-base-mem.svg) |
| [2024-12-09](results/bm-20241209-3.14.0a2%2B-5c89adf) | python/5c89adf385aaaca97c2e | 5c89adf | 1.119x ↑<br>[📄](results/bm-20241209-3.14.0a2%2B-5c89adf/bm-20241209-linux-x86_64-python-5c89adf385aaaca97c2e-3.14.0a2%2B-5c89adf-vs-3.12.6.md)[📈](results/bm-20241209-3.14.0a2%2B-5c89adf/bm-20241209-linux-x86_64-python-5c89adf385aaaca97c2e-3.14.0a2%2B-5c89adf-vs-3.12.6.svg) | 1.075x ↑<br>[📄](results/bm-20241209-3.14.0a2%2B-5c89adf/bm-20241209-linux-x86_64-python-5c89adf385aaaca97c2e-3.14.0a2%2B-5c89adf-vs-3.13.0rc2.md)[📈](results/bm-20241209-3.14.0a2%2B-5c89adf/bm-20241209-linux-x86_64-python-5c89adf385aaaca97c2e-3.14.0a2%2B-5c89adf-vs-3.13.0rc2.svg) |  |
| [2024-12-08](results/bm-20241208-3.14.0a2%2B-a03efb5-NOGIL) | python/a03efb533a58fd13fb0c | a03efb5 (NOGIL) | 1.156x ↓<br>[📄](results/bm-20241208-3.14.0a2%2B-a03efb5-NOGIL/bm-20241208-linux-x86_64-python-a03efb533a58fd13fb0c-3.14.0a2%2B-a03efb5-vs-3.12.6.md)[📈](results/bm-20241208-3.14.0a2%2B-a03efb5-NOGIL/bm-20241208-linux-x86_64-python-a03efb533a58fd13fb0c-3.14.0a2%2B-a03efb5-vs-3.12.6.svg) | 1.185x ↓<br>[📄](results/bm-20241208-3.14.0a2%2B-a03efb5-NOGIL/bm-20241208-linux-x86_64-python-a03efb533a58fd13fb0c-3.14.0a2%2B-a03efb5-vs-3.13.0rc2.md)[📈](results/bm-20241208-3.14.0a2%2B-a03efb5-NOGIL/bm-20241208-linux-x86_64-python-a03efb533a58fd13fb0c-3.14.0a2%2B-a03efb5-vs-3.13.0rc2.svg) | 1.248x ↓<br>[📄](results/bm-20241208-3.14.0a2%2B-a03efb5-NOGIL/bm-20241208-linux-x86_64-python-a03efb533a58fd13fb0c-3.14.0a2%2B-a03efb5-vs-base.md)[📈](results/bm-20241208-3.14.0a2%2B-a03efb5-NOGIL/bm-20241208-linux-x86_64-python-a03efb533a58fd13fb0c-3.14.0a2%2B-a03efb5-vs-base.svg)[🧠](results/bm-20241208-3.14.0a2%2B-a03efb5-NOGIL/bm-20241208-linux-x86_64-python-a03efb533a58fd13fb0c-3.14.0a2%2B-a03efb5-vs-base-mem.svg) |
| [2024-12-08](results/bm-20241208-3.14.0a2%2B-a03efb5) | python/a03efb533a58fd13fb0c | a03efb5 | 1.132x ↑<br>[📄](results/bm-20241208-3.14.0a2%2B-a03efb5/bm-20241208-linux-x86_64-python-a03efb533a58fd13fb0c-3.14.0a2%2B-a03efb5-vs-3.12.6.md)[📈](results/bm-20241208-3.14.0a2%2B-a03efb5/bm-20241208-linux-x86_64-python-a03efb533a58fd13fb0c-3.14.0a2%2B-a03efb5-vs-3.12.6.svg) | 1.089x ↑<br>[📄](results/bm-20241208-3.14.0a2%2B-a03efb5/bm-20241208-linux-x86_64-python-a03efb533a58fd13fb0c-3.14.0a2%2B-a03efb5-vs-3.13.0rc2.md)[📈](results/bm-20241208-3.14.0a2%2B-a03efb5/bm-20241208-linux-x86_64-python-a03efb533a58fd13fb0c-3.14.0a2%2B-a03efb5-vs-3.13.0rc2.svg) |  |

## linux x86_64 (vultr)
| date | fork/ref | hash/flags | vs. 3.12.6: | vs. 3.13.0rc2: | vs. base: |
| --- | --- | --- | ---: | ---: | ---: |
| [2024-12-11](results/bm-20241211-3.14.0a2%2B-bc262de-NOGIL) | python/bc262de06b10a2d119c2 | bc262de (NOGIL) | 1.224x ↓<br>[📄](results/bm-20241211-3.14.0a2%2B-bc262de-NOGIL/bm-20241211-vultr-x86_64-python-bc262de06b10a2d119c2-3.14.0a2%2B-bc262de-vs-3.12.6.md)[📈](results/bm-20241211-3.14.0a2%2B-bc262de-NOGIL/bm-20241211-vultr-x86_64-python-bc262de06b10a2d119c2-3.14.0a2%2B-bc262de-vs-3.12.6.svg) | 1.248x ↓<br>[📄](results/bm-20241211-3.14.0a2%2B-bc262de-NOGIL/bm-20241211-vultr-x86_64-python-bc262de06b10a2d119c2-3.14.0a2%2B-bc262de-vs-3.13.0rc2.md)[📈](results/bm-20241211-3.14.0a2%2B-bc262de-NOGIL/bm-20241211-vultr-x86_64-python-bc262de06b10a2d119c2-3.14.0a2%2B-bc262de-vs-3.13.0rc2.svg) |  |
| [2024-12-11](results/bm-20241211-3.14.0a2%2B-7e3de44-NOGIL) | nascheme/gh_115999_specialize | 7e3de44 (NOGIL) | 1.217x ↓<br>[📄](results/bm-20241211-3.14.0a2%2B-7e3de44-NOGIL/bm-20241211-vultr-x86_64-nascheme-gh_115999_specialize-3.14.0a2%2B-7e3de44-vs-3.12.6.md)[📈](results/bm-20241211-3.14.0a2%2B-7e3de44-NOGIL/bm-20241211-vultr-x86_64-nascheme-gh_115999_specialize-3.14.0a2%2B-7e3de44-vs-3.12.6.svg) | 1.242x ↓<br>[📄](results/bm-20241211-3.14.0a2%2B-7e3de44-NOGIL/bm-20241211-vultr-x86_64-nascheme-gh_115999_specialize-3.14.0a2%2B-7e3de44-vs-3.13.0rc2.md)[📈](results/bm-20241211-3.14.0a2%2B-7e3de44-NOGIL/bm-20241211-vultr-x86_64-nascheme-gh_115999_specialize-3.14.0a2%2B-7e3de44-vs-3.13.0rc2.svg) | 1.008x ↑<br>[📄](results/bm-20241211-3.14.0a2%2B-7e3de44-NOGIL/bm-20241211-vultr-x86_64-nascheme-gh_115999_specialize-3.14.0a2%2B-7e3de44-vs-base.md)[📈](results/bm-20241211-3.14.0a2%2B-7e3de44-NOGIL/bm-20241211-vultr-x86_64-nascheme-gh_115999_specialize-3.14.0a2%2B-7e3de44-vs-base.svg)[🧠](results/bm-20241211-3.14.0a2%2B-7e3de44-NOGIL/bm-20241211-vultr-x86_64-nascheme-gh_115999_specialize-3.14.0a2%2B-7e3de44-vs-base-mem.svg) |
| [2024-12-11](results/bm-20241211-3.14.0a2%2B-7e3de44) | nascheme/gh_115999_specialize | 7e3de44 | 1.059x ↑<br>[📄](results/bm-20241211-3.14.0a2%2B-7e3de44/bm-20241211-vultr-x86_64-nascheme-gh_115999_specialize-3.14.0a2%2B-7e3de44-vs-3.12.6.md)[📈](results/bm-20241211-3.14.0a2%2B-7e3de44/bm-20241211-vultr-x86_64-nascheme-gh_115999_specialize-3.14.0a2%2B-7e3de44-vs-3.12.6.svg) | 1.021x ↑<br>[📄](results/bm-20241211-3.14.0a2%2B-7e3de44/bm-20241211-vultr-x86_64-nascheme-gh_115999_specialize-3.14.0a2%2B-7e3de44-vs-3.13.0rc2.md)[📈](results/bm-20241211-3.14.0a2%2B-7e3de44/bm-20241211-vultr-x86_64-nascheme-gh_115999_specialize-3.14.0a2%2B-7e3de44-vs-3.13.0rc2.svg) |  |
| [2024-12-11](results/bm-20241211-3.14.0a2%2B-12b4f1a-NOGIL) | python/12b4f1a5a175d4dcec27 | 12b4f1a (NOGIL) | 1.225x ↓<br>[📄](results/bm-20241211-3.14.0a2%2B-12b4f1a-NOGIL/bm-20241211-vultr-x86_64-python-12b4f1a5a175d4dcec27-3.14.0a2%2B-12b4f1a-vs-3.12.6.md)[📈](results/bm-20241211-3.14.0a2%2B-12b4f1a-NOGIL/bm-20241211-vultr-x86_64-python-12b4f1a5a175d4dcec27-3.14.0a2%2B-12b4f1a-vs-3.12.6.svg) | 1.249x ↓<br>[📄](results/bm-20241211-3.14.0a2%2B-12b4f1a-NOGIL/bm-20241211-vultr-x86_64-python-12b4f1a5a175d4dcec27-3.14.0a2%2B-12b4f1a-vs-3.13.0rc2.md)[📈](results/bm-20241211-3.14.0a2%2B-12b4f1a-NOGIL/bm-20241211-vultr-x86_64-python-12b4f1a5a175d4dcec27-3.14.0a2%2B-12b4f1a-vs-3.13.0rc2.svg) | 1.277x ↓<br>[📄](results/bm-20241211-3.14.0a2%2B-12b4f1a-NOGIL/bm-20241211-vultr-x86_64-python-12b4f1a5a175d4dcec27-3.14.0a2%2B-12b4f1a-vs-base.md)[📈](results/bm-20241211-3.14.0a2%2B-12b4f1a-NOGIL/bm-20241211-vultr-x86_64-python-12b4f1a5a175d4dcec27-3.14.0a2%2B-12b4f1a-vs-base.svg)[🧠](results/bm-20241211-3.14.0a2%2B-12b4f1a-NOGIL/bm-20241211-vultr-x86_64-python-12b4f1a5a175d4dcec27-3.14.0a2%2B-12b4f1a-vs-base-mem.svg) |
| [2024-12-11](results/bm-20241211-3.14.0a2%2B-12b4f1a) | python/12b4f1a5a175d4dcec27 | 12b4f1a | 1.081x ↑<br>[📄](results/bm-20241211-3.14.0a2%2B-12b4f1a/bm-20241211-vultr-x86_64-python-12b4f1a5a175d4dcec27-3.14.0a2%2B-12b4f1a-vs-3.12.6.md)[📈](results/bm-20241211-3.14.0a2%2B-12b4f1a/bm-20241211-vultr-x86_64-python-12b4f1a5a175d4dcec27-3.14.0a2%2B-12b4f1a-vs-3.12.6.svg) | 1.042x ↑<br>[📄](results/bm-20241211-3.14.0a2%2B-12b4f1a/bm-20241211-vultr-x86_64-python-12b4f1a5a175d4dcec27-3.14.0a2%2B-12b4f1a-vs-3.13.0rc2.md)[📈](results/bm-20241211-3.14.0a2%2B-12b4f1a/bm-20241211-vultr-x86_64-python-12b4f1a5a175d4dcec27-3.14.0a2%2B-12b4f1a-vs-3.13.0rc2.svg) |  |
| [2024-12-09](results/bm-20241209-3.14.0a2%2B-bba99b4-NOGIL) | colesbury/stackpointer | bba99b4 (NOGIL) | 1.234x ↓<br>[📄](results/bm-20241209-3.14.0a2%2B-bba99b4-NOGIL/bm-20241209-vultr-x86_64-colesbury-stackpointer-3.14.0a2%2B-bba99b4-vs-3.12.6.md)[📈](results/bm-20241209-3.14.0a2%2B-bba99b4-NOGIL/bm-20241209-vultr-x86_64-colesbury-stackpointer-3.14.0a2%2B-bba99b4-vs-3.12.6.svg) | 1.259x ↓<br>[📄](results/bm-20241209-3.14.0a2%2B-bba99b4-NOGIL/bm-20241209-vultr-x86_64-colesbury-stackpointer-3.14.0a2%2B-bba99b4-vs-3.13.0rc2.md)[📈](results/bm-20241209-3.14.0a2%2B-bba99b4-NOGIL/bm-20241209-vultr-x86_64-colesbury-stackpointer-3.14.0a2%2B-bba99b4-vs-3.13.0rc2.svg) | 1.008x ↓<br>[📄](results/bm-20241209-3.14.0a2%2B-bba99b4-NOGIL/bm-20241209-vultr-x86_64-colesbury-stackpointer-3.14.0a2%2B-bba99b4-vs-base.md)[📈](results/bm-20241209-3.14.0a2%2B-bba99b4-NOGIL/bm-20241209-vultr-x86_64-colesbury-stackpointer-3.14.0a2%2B-bba99b4-vs-base.svg)[🧠](results/bm-20241209-3.14.0a2%2B-bba99b4-NOGIL/bm-20241209-vultr-x86_64-colesbury-stackpointer-3.14.0a2%2B-bba99b4-vs-base-mem.svg) |
| [2024-12-09](results/bm-20241209-3.14.0a2%2B-7f50611) | colesbury/mro | 7f50611 | 1.058x ↑<br>[📄](results/bm-20241209-3.14.0a2%2B-7f50611/bm-20241209-vultr-x86_64-colesbury-mro-3.14.0a2%2B-7f50611-vs-3.12.6.md)[📈](results/bm-20241209-3.14.0a2%2B-7f50611/bm-20241209-vultr-x86_64-colesbury-mro-3.14.0a2%2B-7f50611-vs-3.12.6.svg) | 1.019x ↑<br>[📄](results/bm-20241209-3.14.0a2%2B-7f50611/bm-20241209-vultr-x86_64-colesbury-mro-3.14.0a2%2B-7f50611-vs-3.13.0rc2.md)[📈](results/bm-20241209-3.14.0a2%2B-7f50611/bm-20241209-vultr-x86_64-colesbury-mro-3.14.0a2%2B-7f50611-vs-3.13.0rc2.svg) | 1.009x ↓<br>[📄](results/bm-20241209-3.14.0a2%2B-7f50611/bm-20241209-vultr-x86_64-colesbury-mro-3.14.0a2%2B-7f50611-vs-base.md)[📈](results/bm-20241209-3.14.0a2%2B-7f50611/bm-20241209-vultr-x86_64-colesbury-mro-3.14.0a2%2B-7f50611-vs-base.svg)[🧠](results/bm-20241209-3.14.0a2%2B-7f50611/bm-20241209-vultr-x86_64-colesbury-mro-3.14.0a2%2B-7f50611-vs-base-mem.svg) |
| [2024-12-09](results/bm-20241209-3.14.0a2%2B-5c89adf-NOGIL) | python/5c89adf385aaaca97c2e | 5c89adf (NOGIL) | 1.227x ↓<br>[📄](results/bm-20241209-3.14.0a2%2B-5c89adf-NOGIL/bm-20241209-vultr-x86_64-python-5c89adf385aaaca97c2e-3.14.0a2%2B-5c89adf-vs-3.12.6.md)[📈](results/bm-20241209-3.14.0a2%2B-5c89adf-NOGIL/bm-20241209-vultr-x86_64-python-5c89adf385aaaca97c2e-3.14.0a2%2B-5c89adf-vs-3.12.6.svg) | 1.252x ↓<br>[📄](results/bm-20241209-3.14.0a2%2B-5c89adf-NOGIL/bm-20241209-vultr-x86_64-python-5c89adf385aaaca97c2e-3.14.0a2%2B-5c89adf-vs-3.13.0rc2.md)[📈](results/bm-20241209-3.14.0a2%2B-5c89adf-NOGIL/bm-20241209-vultr-x86_64-python-5c89adf385aaaca97c2e-3.14.0a2%2B-5c89adf-vs-3.13.0rc2.svg) | 1.265x ↓<br>[📄](results/bm-20241209-3.14.0a2%2B-5c89adf-NOGIL/bm-20241209-vultr-x86_64-python-5c89adf385aaaca97c2e-3.14.0a2%2B-5c89adf-vs-base.md)[📈](results/bm-20241209-3.14.0a2%2B-5c89adf-NOGIL/bm-20241209-vultr-x86_64-python-5c89adf385aaaca97c2e-3.14.0a2%2B-5c89adf-vs-base.svg)[🧠](results/bm-20241209-3.14.0a2%2B-5c89adf-NOGIL/bm-20241209-vultr-x86_64-python-5c89adf385aaaca97c2e-3.14.0a2%2B-5c89adf-vs-base-mem.svg) |
| [2024-12-09](results/bm-20241209-3.14.0a2%2B-5c89adf) | python/5c89adf385aaaca97c2e | 5c89adf | 1.060x ↑<br>[📄](results/bm-20241209-3.14.0a2%2B-5c89adf/bm-20241209-vultr-x86_64-python-5c89adf385aaaca97c2e-3.14.0a2%2B-5c89adf-vs-3.12.6.md)[📈](results/bm-20241209-3.14.0a2%2B-5c89adf/bm-20241209-vultr-x86_64-python-5c89adf385aaaca97c2e-3.14.0a2%2B-5c89adf-vs-3.12.6.svg) | 1.022x ↑<br>[📄](results/bm-20241209-3.14.0a2%2B-5c89adf/bm-20241209-vultr-x86_64-python-5c89adf385aaaca97c2e-3.14.0a2%2B-5c89adf-vs-3.13.0rc2.md)[📈](results/bm-20241209-3.14.0a2%2B-5c89adf/bm-20241209-vultr-x86_64-python-5c89adf385aaaca97c2e-3.14.0a2%2B-5c89adf-vs-3.13.0rc2.svg) |  |
| [2024-12-08](results/bm-20241208-3.14.0a2%2B-a03efb5-NOGIL) | python/a03efb533a58fd13fb0c | a03efb5 (NOGIL) | 1.229x ↓<br>[📄](results/bm-20241208-3.14.0a2%2B-a03efb5-NOGIL/bm-20241208-vultr-x86_64-python-a03efb533a58fd13fb0c-3.14.0a2%2B-a03efb5-vs-3.12.6.md)[📈](results/bm-20241208-3.14.0a2%2B-a03efb5-NOGIL/bm-20241208-vultr-x86_64-python-a03efb533a58fd13fb0c-3.14.0a2%2B-a03efb5-vs-3.12.6.svg) | 1.254x ↓<br>[📄](results/bm-20241208-3.14.0a2%2B-a03efb5-NOGIL/bm-20241208-vultr-x86_64-python-a03efb533a58fd13fb0c-3.14.0a2%2B-a03efb5-vs-3.13.0rc2.md)[📈](results/bm-20241208-3.14.0a2%2B-a03efb5-NOGIL/bm-20241208-vultr-x86_64-python-a03efb533a58fd13fb0c-3.14.0a2%2B-a03efb5-vs-3.13.0rc2.svg) | 1.273x ↓<br>[📄](results/bm-20241208-3.14.0a2%2B-a03efb5-NOGIL/bm-20241208-vultr-x86_64-python-a03efb533a58fd13fb0c-3.14.0a2%2B-a03efb5-vs-base.md)[📈](results/bm-20241208-3.14.0a2%2B-a03efb5-NOGIL/bm-20241208-vultr-x86_64-python-a03efb533a58fd13fb0c-3.14.0a2%2B-a03efb5-vs-base.svg)[🧠](results/bm-20241208-3.14.0a2%2B-a03efb5-NOGIL/bm-20241208-vultr-x86_64-python-a03efb533a58fd13fb0c-3.14.0a2%2B-a03efb5-vs-base-mem.svg) |
| [2024-12-08](results/bm-20241208-3.14.0a2%2B-a03efb5) | python/a03efb533a58fd13fb0c | a03efb5 | 1.069x ↑<br>[📄](results/bm-20241208-3.14.0a2%2B-a03efb5/bm-20241208-vultr-x86_64-python-a03efb533a58fd13fb0c-3.14.0a2%2B-a03efb5-vs-3.12.6.md)[📈](results/bm-20241208-3.14.0a2%2B-a03efb5/bm-20241208-vultr-x86_64-python-a03efb533a58fd13fb0c-3.14.0a2%2B-a03efb5-vs-3.12.6.svg) | 1.030x ↑<br>[📄](results/bm-20241208-3.14.0a2%2B-a03efb5/bm-20241208-vultr-x86_64-python-a03efb533a58fd13fb0c-3.14.0a2%2B-a03efb5-vs-3.13.0rc2.md)[📈](results/bm-20241208-3.14.0a2%2B-a03efb5/bm-20241208-vultr-x86_64-python-a03efb533a58fd13fb0c-3.14.0a2%2B-a03efb5-vs-3.13.0rc2.svg) |  |
| [2024-12-06](results/bm-20241206-3.14.0a2%2B-5b6635f) | python/5b6635f772d187d6049a | 5b6635f | 1.067x ↑<br>[📄](results/bm-20241206-3.14.0a2%2B-5b6635f/bm-20241206-vultr-x86_64-python-5b6635f772d187d6049a-3.14.0a2%2B-5b6635f-vs-3.12.6.md)[📈](results/bm-20241206-3.14.0a2%2B-5b6635f/bm-20241206-vultr-x86_64-python-5b6635f772d187d6049a-3.14.0a2%2B-5b6635f-vs-3.12.6.svg) | 1.029x ↑<br>[📄](results/bm-20241206-3.14.0a2%2B-5b6635f/bm-20241206-vultr-x86_64-python-5b6635f772d187d6049a-3.14.0a2%2B-5b6635f-vs-3.13.0rc2.md)[📈](results/bm-20241206-3.14.0a2%2B-5b6635f/bm-20241206-vultr-x86_64-python-5b6635f772d187d6049a-3.14.0a2%2B-5b6635f-vs-3.13.0rc2.svg) |  |


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
