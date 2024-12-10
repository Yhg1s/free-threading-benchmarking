# Faster CPython Benchmark Infrastructure

🔒 [▶️ START A BENCHMARK RUN](../../actions/workflows/benchmark.yml)

## Results

Here are some recent and important revisions. 👉 [Complete list of results](RESULTS.md).

<!-- START table -->
[Most recent pystats on main (79b7cab)](results/bm-20241207-3.14.0a2%2B-79b7cab-PYTHON_UOPS/bm-20241207-vultr-x86_64-python-79b7cab50a3292a1c014-3.14.0a2%2B-79b7cab-pystats.md)

## linux x86_64 (linux)
| date | fork/ref | hash/flags | vs. 3.12.6: | vs. 3.13.0rc2: | vs. base: |
| --- | --- | --- | ---: | ---: | ---: |
| [2024-12-08](results/bm-20241208-3.14.0a2%2B-a03efb5-NOGIL) | python/a03efb533a58fd13fb0c | a03efb5 (NOGIL) | 1.156x ↓<br>[📄](results/bm-20241208-3.14.0a2%2B-a03efb5-NOGIL/bm-20241208-linux-x86_64-python-a03efb533a58fd13fb0c-3.14.0a2%2B-a03efb5-vs-3.12.6.md)[📈](results/bm-20241208-3.14.0a2%2B-a03efb5-NOGIL/bm-20241208-linux-x86_64-python-a03efb533a58fd13fb0c-3.14.0a2%2B-a03efb5-vs-3.12.6.svg) | 1.185x ↓<br>[📄](results/bm-20241208-3.14.0a2%2B-a03efb5-NOGIL/bm-20241208-linux-x86_64-python-a03efb533a58fd13fb0c-3.14.0a2%2B-a03efb5-vs-3.13.0rc2.md)[📈](results/bm-20241208-3.14.0a2%2B-a03efb5-NOGIL/bm-20241208-linux-x86_64-python-a03efb533a58fd13fb0c-3.14.0a2%2B-a03efb5-vs-3.13.0rc2.svg) | 1.248x ↓<br>[📄](results/bm-20241208-3.14.0a2%2B-a03efb5-NOGIL/bm-20241208-linux-x86_64-python-a03efb533a58fd13fb0c-3.14.0a2%2B-a03efb5-vs-base.md)[📈](results/bm-20241208-3.14.0a2%2B-a03efb5-NOGIL/bm-20241208-linux-x86_64-python-a03efb533a58fd13fb0c-3.14.0a2%2B-a03efb5-vs-base.svg)[🧠](results/bm-20241208-3.14.0a2%2B-a03efb5-NOGIL/bm-20241208-linux-x86_64-python-a03efb533a58fd13fb0c-3.14.0a2%2B-a03efb5-vs-base-mem.svg) |
| [2024-12-08](results/bm-20241208-3.14.0a2%2B-a03efb5) | python/a03efb533a58fd13fb0c | a03efb5 | 1.132x ↑<br>[📄](results/bm-20241208-3.14.0a2%2B-a03efb5/bm-20241208-linux-x86_64-python-a03efb533a58fd13fb0c-3.14.0a2%2B-a03efb5-vs-3.12.6.md)[📈](results/bm-20241208-3.14.0a2%2B-a03efb5/bm-20241208-linux-x86_64-python-a03efb533a58fd13fb0c-3.14.0a2%2B-a03efb5-vs-3.12.6.svg) | 1.089x ↑<br>[📄](results/bm-20241208-3.14.0a2%2B-a03efb5/bm-20241208-linux-x86_64-python-a03efb533a58fd13fb0c-3.14.0a2%2B-a03efb5-vs-3.13.0rc2.md)[📈](results/bm-20241208-3.14.0a2%2B-a03efb5/bm-20241208-linux-x86_64-python-a03efb533a58fd13fb0c-3.14.0a2%2B-a03efb5-vs-3.13.0rc2.svg) |  |
| [2024-12-07](results/bm-20241207-3.14.0a2%2B-79b7cab) | python/79b7cab50a3292a1c014 | 79b7cab | 1.119x ↑<br>[📄](results/bm-20241207-3.14.0a2%2B-79b7cab/bm-20241207-linux-x86_64-python-79b7cab50a3292a1c014-3.14.0a2%2B-79b7cab-vs-3.12.6.md)[📈](results/bm-20241207-3.14.0a2%2B-79b7cab/bm-20241207-linux-x86_64-python-79b7cab50a3292a1c014-3.14.0a2%2B-79b7cab-vs-3.12.6.svg) | 1.076x ↑<br>[📄](results/bm-20241207-3.14.0a2%2B-79b7cab/bm-20241207-linux-x86_64-python-79b7cab50a3292a1c014-3.14.0a2%2B-79b7cab-vs-3.13.0rc2.md)[📈](results/bm-20241207-3.14.0a2%2B-79b7cab/bm-20241207-linux-x86_64-python-79b7cab50a3292a1c014-3.14.0a2%2B-79b7cab-vs-3.13.0rc2.svg) |  |
| [2024-12-07](results/bm-20241207-3.14.0a2%2B-79b7cab-NOGIL) | python/79b7cab50a3292a1c014 | 79b7cab (NOGIL) | 1.160x ↓<br>[📄](results/bm-20241207-3.14.0a2%2B-79b7cab-NOGIL/bm-20241207-linux-x86_64-python-79b7cab50a3292a1c014-3.14.0a2%2B-79b7cab-vs-3.12.6.md)[📈](results/bm-20241207-3.14.0a2%2B-79b7cab-NOGIL/bm-20241207-linux-x86_64-python-79b7cab50a3292a1c014-3.14.0a2%2B-79b7cab-vs-3.12.6.svg) | 1.188x ↓<br>[📄](results/bm-20241207-3.14.0a2%2B-79b7cab-NOGIL/bm-20241207-linux-x86_64-python-79b7cab50a3292a1c014-3.14.0a2%2B-79b7cab-vs-3.13.0rc2.md)[📈](results/bm-20241207-3.14.0a2%2B-79b7cab-NOGIL/bm-20241207-linux-x86_64-python-79b7cab50a3292a1c014-3.14.0a2%2B-79b7cab-vs-3.13.0rc2.svg) | 1.244x ↓<br>[📄](results/bm-20241207-3.14.0a2%2B-79b7cab-NOGIL/bm-20241207-linux-x86_64-python-79b7cab50a3292a1c014-3.14.0a2%2B-79b7cab-vs-base.md)[📈](results/bm-20241207-3.14.0a2%2B-79b7cab-NOGIL/bm-20241207-linux-x86_64-python-79b7cab50a3292a1c014-3.14.0a2%2B-79b7cab-vs-base.svg)[🧠](results/bm-20241207-3.14.0a2%2B-79b7cab-NOGIL/bm-20241207-linux-x86_64-python-79b7cab50a3292a1c014-3.14.0a2%2B-79b7cab-vs-base-mem.svg) |
| [2024-12-06](results/bm-20241206-3.14.0a2%2B-31c9f3c) | python/31c9f3ced293492b38e7 | 31c9f3c | 1.119x ↑<br>[📄](results/bm-20241206-3.14.0a2%2B-31c9f3c/bm-20241206-linux-x86_64-python-31c9f3ced293492b38e7-3.14.0a2%2B-31c9f3c-vs-3.12.6.md)[📈](results/bm-20241206-3.14.0a2%2B-31c9f3c/bm-20241206-linux-x86_64-python-31c9f3ced293492b38e7-3.14.0a2%2B-31c9f3c-vs-3.12.6.svg) | 1.075x ↑<br>[📄](results/bm-20241206-3.14.0a2%2B-31c9f3c/bm-20241206-linux-x86_64-python-31c9f3ced293492b38e7-3.14.0a2%2B-31c9f3c-vs-3.13.0rc2.md)[📈](results/bm-20241206-3.14.0a2%2B-31c9f3c/bm-20241206-linux-x86_64-python-31c9f3ced293492b38e7-3.14.0a2%2B-31c9f3c-vs-3.13.0rc2.svg) |  |
| [2024-12-06](results/bm-20241206-3.14.0a2%2B-31c9f3c-NOGIL) | python/31c9f3ced293492b38e7 | 31c9f3c (NOGIL) | 1.165x ↓<br>[📄](results/bm-20241206-3.14.0a2%2B-31c9f3c-NOGIL/bm-20241206-linux-x86_64-python-31c9f3ced293492b38e7-3.14.0a2%2B-31c9f3c-vs-3.12.6.md)[📈](results/bm-20241206-3.14.0a2%2B-31c9f3c-NOGIL/bm-20241206-linux-x86_64-python-31c9f3ced293492b38e7-3.14.0a2%2B-31c9f3c-vs-3.12.6.svg) | 1.194x ↓<br>[📄](results/bm-20241206-3.14.0a2%2B-31c9f3c-NOGIL/bm-20241206-linux-x86_64-python-31c9f3ced293492b38e7-3.14.0a2%2B-31c9f3c-vs-3.13.0rc2.md)[📈](results/bm-20241206-3.14.0a2%2B-31c9f3c-NOGIL/bm-20241206-linux-x86_64-python-31c9f3ced293492b38e7-3.14.0a2%2B-31c9f3c-vs-3.13.0rc2.svg) | 1.248x ↓<br>[📄](results/bm-20241206-3.14.0a2%2B-31c9f3c-NOGIL/bm-20241206-linux-x86_64-python-31c9f3ced293492b38e7-3.14.0a2%2B-31c9f3c-vs-base.md)[📈](results/bm-20241206-3.14.0a2%2B-31c9f3c-NOGIL/bm-20241206-linux-x86_64-python-31c9f3ced293492b38e7-3.14.0a2%2B-31c9f3c-vs-base.svg)[🧠](results/bm-20241206-3.14.0a2%2B-31c9f3c-NOGIL/bm-20241206-linux-x86_64-python-31c9f3ced293492b38e7-3.14.0a2%2B-31c9f3c-vs-base-mem.svg) |

## linux x86_64 (vultr)
| date | fork/ref | hash/flags | vs. 3.12.6: | vs. 3.13.0rc2: | vs. base: |
| --- | --- | --- | ---: | ---: | ---: |
| [2024-12-09](results/bm-20241209-3.14.0a2%2B-bba99b4-NOGIL) | colesbury/stackpointer | bba99b4 (NOGIL) | 1.234x ↓<br>[📄](results/bm-20241209-3.14.0a2%2B-bba99b4-NOGIL/bm-20241209-vultr-x86_64-colesbury-stackpointer-3.14.0a2%2B-bba99b4-vs-3.12.6.md)[📈](results/bm-20241209-3.14.0a2%2B-bba99b4-NOGIL/bm-20241209-vultr-x86_64-colesbury-stackpointer-3.14.0a2%2B-bba99b4-vs-3.12.6.svg) | 1.259x ↓<br>[📄](results/bm-20241209-3.14.0a2%2B-bba99b4-NOGIL/bm-20241209-vultr-x86_64-colesbury-stackpointer-3.14.0a2%2B-bba99b4-vs-3.13.0rc2.md)[📈](results/bm-20241209-3.14.0a2%2B-bba99b4-NOGIL/bm-20241209-vultr-x86_64-colesbury-stackpointer-3.14.0a2%2B-bba99b4-vs-3.13.0rc2.svg) | 1.008x ↓<br>[📄](results/bm-20241209-3.14.0a2%2B-bba99b4-NOGIL/bm-20241209-vultr-x86_64-colesbury-stackpointer-3.14.0a2%2B-bba99b4-vs-base.md)[📈](results/bm-20241209-3.14.0a2%2B-bba99b4-NOGIL/bm-20241209-vultr-x86_64-colesbury-stackpointer-3.14.0a2%2B-bba99b4-vs-base.svg)[🧠](results/bm-20241209-3.14.0a2%2B-bba99b4-NOGIL/bm-20241209-vultr-x86_64-colesbury-stackpointer-3.14.0a2%2B-bba99b4-vs-base-mem.svg) |
| [2024-12-09](results/bm-20241209-3.14.0a2%2B-7f50611) | colesbury/mro | 7f50611 | 1.058x ↑<br>[📄](results/bm-20241209-3.14.0a2%2B-7f50611/bm-20241209-vultr-x86_64-colesbury-mro-3.14.0a2%2B-7f50611-vs-3.12.6.md)[📈](results/bm-20241209-3.14.0a2%2B-7f50611/bm-20241209-vultr-x86_64-colesbury-mro-3.14.0a2%2B-7f50611-vs-3.12.6.svg) | 1.019x ↑<br>[📄](results/bm-20241209-3.14.0a2%2B-7f50611/bm-20241209-vultr-x86_64-colesbury-mro-3.14.0a2%2B-7f50611-vs-3.13.0rc2.md)[📈](results/bm-20241209-3.14.0a2%2B-7f50611/bm-20241209-vultr-x86_64-colesbury-mro-3.14.0a2%2B-7f50611-vs-3.13.0rc2.svg) | 1.009x ↓<br>[📄](results/bm-20241209-3.14.0a2%2B-7f50611/bm-20241209-vultr-x86_64-colesbury-mro-3.14.0a2%2B-7f50611-vs-base.md)[📈](results/bm-20241209-3.14.0a2%2B-7f50611/bm-20241209-vultr-x86_64-colesbury-mro-3.14.0a2%2B-7f50611-vs-base.svg)[🧠](results/bm-20241209-3.14.0a2%2B-7f50611/bm-20241209-vultr-x86_64-colesbury-mro-3.14.0a2%2B-7f50611-vs-base-mem.svg) |
| [2024-12-09](results/bm-20241209-3.14.0a2%2B-5c89adf-NOGIL) | python/5c89adf385aaaca97c2e | 5c89adf (NOGIL) | 1.227x ↓<br>[📄](results/bm-20241209-3.14.0a2%2B-5c89adf-NOGIL/bm-20241209-vultr-x86_64-python-5c89adf385aaaca97c2e-3.14.0a2%2B-5c89adf-vs-3.12.6.md)[📈](results/bm-20241209-3.14.0a2%2B-5c89adf-NOGIL/bm-20241209-vultr-x86_64-python-5c89adf385aaaca97c2e-3.14.0a2%2B-5c89adf-vs-3.12.6.svg) | 1.252x ↓<br>[📄](results/bm-20241209-3.14.0a2%2B-5c89adf-NOGIL/bm-20241209-vultr-x86_64-python-5c89adf385aaaca97c2e-3.14.0a2%2B-5c89adf-vs-3.13.0rc2.md)[📈](results/bm-20241209-3.14.0a2%2B-5c89adf-NOGIL/bm-20241209-vultr-x86_64-python-5c89adf385aaaca97c2e-3.14.0a2%2B-5c89adf-vs-3.13.0rc2.svg) |  |
| [2024-12-08](results/bm-20241208-3.14.0a2%2B-a03efb5-NOGIL) | python/a03efb533a58fd13fb0c | a03efb5 (NOGIL) | 1.229x ↓<br>[📄](results/bm-20241208-3.14.0a2%2B-a03efb5-NOGIL/bm-20241208-vultr-x86_64-python-a03efb533a58fd13fb0c-3.14.0a2%2B-a03efb5-vs-3.12.6.md)[📈](results/bm-20241208-3.14.0a2%2B-a03efb5-NOGIL/bm-20241208-vultr-x86_64-python-a03efb533a58fd13fb0c-3.14.0a2%2B-a03efb5-vs-3.12.6.svg) | 1.254x ↓<br>[📄](results/bm-20241208-3.14.0a2%2B-a03efb5-NOGIL/bm-20241208-vultr-x86_64-python-a03efb533a58fd13fb0c-3.14.0a2%2B-a03efb5-vs-3.13.0rc2.md)[📈](results/bm-20241208-3.14.0a2%2B-a03efb5-NOGIL/bm-20241208-vultr-x86_64-python-a03efb533a58fd13fb0c-3.14.0a2%2B-a03efb5-vs-3.13.0rc2.svg) | 1.273x ↓<br>[📄](results/bm-20241208-3.14.0a2%2B-a03efb5-NOGIL/bm-20241208-vultr-x86_64-python-a03efb533a58fd13fb0c-3.14.0a2%2B-a03efb5-vs-base.md)[📈](results/bm-20241208-3.14.0a2%2B-a03efb5-NOGIL/bm-20241208-vultr-x86_64-python-a03efb533a58fd13fb0c-3.14.0a2%2B-a03efb5-vs-base.svg)[🧠](results/bm-20241208-3.14.0a2%2B-a03efb5-NOGIL/bm-20241208-vultr-x86_64-python-a03efb533a58fd13fb0c-3.14.0a2%2B-a03efb5-vs-base-mem.svg) |
| [2024-12-08](results/bm-20241208-3.14.0a2%2B-a03efb5) | python/a03efb533a58fd13fb0c | a03efb5 | 1.069x ↑<br>[📄](results/bm-20241208-3.14.0a2%2B-a03efb5/bm-20241208-vultr-x86_64-python-a03efb533a58fd13fb0c-3.14.0a2%2B-a03efb5-vs-3.12.6.md)[📈](results/bm-20241208-3.14.0a2%2B-a03efb5/bm-20241208-vultr-x86_64-python-a03efb533a58fd13fb0c-3.14.0a2%2B-a03efb5-vs-3.12.6.svg) | 1.030x ↑<br>[📄](results/bm-20241208-3.14.0a2%2B-a03efb5/bm-20241208-vultr-x86_64-python-a03efb533a58fd13fb0c-3.14.0a2%2B-a03efb5-vs-3.13.0rc2.md)[📈](results/bm-20241208-3.14.0a2%2B-a03efb5/bm-20241208-vultr-x86_64-python-a03efb533a58fd13fb0c-3.14.0a2%2B-a03efb5-vs-3.13.0rc2.svg) |  |
| [2024-12-07](results/bm-20241207-3.14.0a2%2B-79b7cab) | python/79b7cab50a3292a1c014 | 79b7cab | 1.062x ↑<br>[📄](results/bm-20241207-3.14.0a2%2B-79b7cab/bm-20241207-vultr-x86_64-python-79b7cab50a3292a1c014-3.14.0a2%2B-79b7cab-vs-3.12.6.md)[📈](results/bm-20241207-3.14.0a2%2B-79b7cab/bm-20241207-vultr-x86_64-python-79b7cab50a3292a1c014-3.14.0a2%2B-79b7cab-vs-3.12.6.svg) | 1.023x ↑<br>[📄](results/bm-20241207-3.14.0a2%2B-79b7cab/bm-20241207-vultr-x86_64-python-79b7cab50a3292a1c014-3.14.0a2%2B-79b7cab-vs-3.13.0rc2.md)[📈](results/bm-20241207-3.14.0a2%2B-79b7cab/bm-20241207-vultr-x86_64-python-79b7cab50a3292a1c014-3.14.0a2%2B-79b7cab-vs-3.13.0rc2.svg) |  |
| [2024-12-07](results/bm-20241207-3.14.0a2%2B-79b7cab-NOGIL) | python/79b7cab50a3292a1c014 | 79b7cab (NOGIL) | 1.227x ↓<br>[📄](results/bm-20241207-3.14.0a2%2B-79b7cab-NOGIL/bm-20241207-vultr-x86_64-python-79b7cab50a3292a1c014-3.14.0a2%2B-79b7cab-vs-3.12.6.md)[📈](results/bm-20241207-3.14.0a2%2B-79b7cab-NOGIL/bm-20241207-vultr-x86_64-python-79b7cab50a3292a1c014-3.14.0a2%2B-79b7cab-vs-3.12.6.svg) | 1.252x ↓<br>[📄](results/bm-20241207-3.14.0a2%2B-79b7cab-NOGIL/bm-20241207-vultr-x86_64-python-79b7cab50a3292a1c014-3.14.0a2%2B-79b7cab-vs-3.13.0rc2.md)[📈](results/bm-20241207-3.14.0a2%2B-79b7cab-NOGIL/bm-20241207-vultr-x86_64-python-79b7cab50a3292a1c014-3.14.0a2%2B-79b7cab-vs-3.13.0rc2.svg) | 1.266x ↓<br>[📄](results/bm-20241207-3.14.0a2%2B-79b7cab-NOGIL/bm-20241207-vultr-x86_64-python-79b7cab50a3292a1c014-3.14.0a2%2B-79b7cab-vs-base.md)[📈](results/bm-20241207-3.14.0a2%2B-79b7cab-NOGIL/bm-20241207-vultr-x86_64-python-79b7cab50a3292a1c014-3.14.0a2%2B-79b7cab-vs-base.svg)[🧠](results/bm-20241207-3.14.0a2%2B-79b7cab-NOGIL/bm-20241207-vultr-x86_64-python-79b7cab50a3292a1c014-3.14.0a2%2B-79b7cab-vs-base-mem.svg) |
| [2024-12-06](results/bm-20241206-3.14.0a2%2B-31c9f3c) | python/31c9f3ced293492b38e7 | 31c9f3c | 1.062x ↑<br>[📄](results/bm-20241206-3.14.0a2%2B-31c9f3c/bm-20241206-vultr-x86_64-python-31c9f3ced293492b38e7-3.14.0a2%2B-31c9f3c-vs-3.12.6.md)[📈](results/bm-20241206-3.14.0a2%2B-31c9f3c/bm-20241206-vultr-x86_64-python-31c9f3ced293492b38e7-3.14.0a2%2B-31c9f3c-vs-3.12.6.svg) | 1.023x ↑<br>[📄](results/bm-20241206-3.14.0a2%2B-31c9f3c/bm-20241206-vultr-x86_64-python-31c9f3ced293492b38e7-3.14.0a2%2B-31c9f3c-vs-3.13.0rc2.md)[📈](results/bm-20241206-3.14.0a2%2B-31c9f3c/bm-20241206-vultr-x86_64-python-31c9f3ced293492b38e7-3.14.0a2%2B-31c9f3c-vs-3.13.0rc2.svg) |  |
| [2024-12-06](results/bm-20241206-3.14.0a2%2B-31c9f3c-NOGIL) | python/31c9f3ced293492b38e7 | 31c9f3c (NOGIL) | 1.225x ↓<br>[📄](results/bm-20241206-3.14.0a2%2B-31c9f3c-NOGIL/bm-20241206-vultr-x86_64-python-31c9f3ced293492b38e7-3.14.0a2%2B-31c9f3c-vs-3.12.6.md)[📈](results/bm-20241206-3.14.0a2%2B-31c9f3c-NOGIL/bm-20241206-vultr-x86_64-python-31c9f3ced293492b38e7-3.14.0a2%2B-31c9f3c-vs-3.12.6.svg) | 1.250x ↓<br>[📄](results/bm-20241206-3.14.0a2%2B-31c9f3c-NOGIL/bm-20241206-vultr-x86_64-python-31c9f3ced293492b38e7-3.14.0a2%2B-31c9f3c-vs-3.13.0rc2.md)[📈](results/bm-20241206-3.14.0a2%2B-31c9f3c-NOGIL/bm-20241206-vultr-x86_64-python-31c9f3ced293492b38e7-3.14.0a2%2B-31c9f3c-vs-3.13.0rc2.svg) | 1.264x ↓<br>[📄](results/bm-20241206-3.14.0a2%2B-31c9f3c-NOGIL/bm-20241206-vultr-x86_64-python-31c9f3ced293492b38e7-3.14.0a2%2B-31c9f3c-vs-base.md)[📈](results/bm-20241206-3.14.0a2%2B-31c9f3c-NOGIL/bm-20241206-vultr-x86_64-python-31c9f3ced293492b38e7-3.14.0a2%2B-31c9f3c-vs-base.svg)[🧠](results/bm-20241206-3.14.0a2%2B-31c9f3c-NOGIL/bm-20241206-vultr-x86_64-python-31c9f3ced293492b38e7-3.14.0a2%2B-31c9f3c-vs-base-mem.svg) |
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
