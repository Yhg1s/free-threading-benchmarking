# Faster CPython Benchmark Infrastructure

🔒 [▶️ START A BENCHMARK RUN](../../actions/workflows/benchmark.yml)

## Results

Here are some recent and important revisions. 👉 [Complete list of results](RESULTS.md).

<!-- START table -->
[Most recent pystats on main (7d7d56d)](results/bm-20241102-3.14.0a1%2B-7d7d56d-PYTHON_UOPS/bm-20241102-vultr-x86_64-python-7d7d56d8b1147a6b85e1-3.14.0a1%2B-7d7d56d-pystats.md)

## linux x86_64 (linux)
| date | fork/ref | hash/flags | vs. 3.12.6: | vs. 3.13.0rc2: | vs. base: |
| --- | --- | --- | ---: | ---: | ---: |
| [2024-11-22](results/bm-20241122-3.14.0a2%2B-39e60ae-NOGIL) | python/39e60aeb3837f1f23d8b | 39e60ae (NOGIL) | 1.27x ↓<br>[📄](results/bm-20241122-3.14.0a2%2B-39e60ae-NOGIL/bm-20241122-linux-x86_64-python-39e60aeb3837f1f23d8b-3.14.0a2%2B-39e60ae-vs-3.12.6.md)[📈](results/bm-20241122-3.14.0a2%2B-39e60ae-NOGIL/bm-20241122-linux-x86_64-python-39e60aeb3837f1f23d8b-3.14.0a2%2B-39e60ae-vs-3.12.6.svg) | 1.32x ↓<br>[📄](results/bm-20241122-3.14.0a2%2B-39e60ae-NOGIL/bm-20241122-linux-x86_64-python-39e60aeb3837f1f23d8b-3.14.0a2%2B-39e60ae-vs-3.13.0rc2.md)[📈](results/bm-20241122-3.14.0a2%2B-39e60ae-NOGIL/bm-20241122-linux-x86_64-python-39e60aeb3837f1f23d8b-3.14.0a2%2B-39e60ae-vs-3.13.0rc2.svg) | 1.36x ↓<br>[📄](results/bm-20241122-3.14.0a2%2B-39e60ae-NOGIL/bm-20241122-linux-x86_64-python-39e60aeb3837f1f23d8b-3.14.0a2%2B-39e60ae-vs-base.md)[📈](results/bm-20241122-3.14.0a2%2B-39e60ae-NOGIL/bm-20241122-linux-x86_64-python-39e60aeb3837f1f23d8b-3.14.0a2%2B-39e60ae-vs-base.svg)[🧠](results/bm-20241122-3.14.0a2%2B-39e60ae-NOGIL/bm-20241122-linux-x86_64-python-39e60aeb3837f1f23d8b-3.14.0a2%2B-39e60ae-vs-base-mem.svg) |
| [2024-11-22](results/bm-20241122-3.14.0a2%2B-39e60ae) | python/39e60aeb3837f1f23d8b | 39e60ae | 1.08x ↑<br>[📄](results/bm-20241122-3.14.0a2%2B-39e60ae/bm-20241122-linux-x86_64-python-39e60aeb3837f1f23d8b-3.14.0a2%2B-39e60ae-vs-3.12.6.md)[📈](results/bm-20241122-3.14.0a2%2B-39e60ae/bm-20241122-linux-x86_64-python-39e60aeb3837f1f23d8b-3.14.0a2%2B-39e60ae-vs-3.12.6.svg) | 1.04x ↑<br>[📄](results/bm-20241122-3.14.0a2%2B-39e60ae/bm-20241122-linux-x86_64-python-39e60aeb3837f1f23d8b-3.14.0a2%2B-39e60ae-vs-3.13.0rc2.md)[📈](results/bm-20241122-3.14.0a2%2B-39e60ae/bm-20241122-linux-x86_64-python-39e60aeb3837f1f23d8b-3.14.0a2%2B-39e60ae-vs-3.13.0rc2.svg) |  |
| [2024-11-21](results/bm-20241121-3.14.0a2%2B-fcfdb55-NOGIL) | python/fcfdb55465636afc256b | fcfdb55 (NOGIL) | 1.33x ↓<br>[📄](results/bm-20241121-3.14.0a2%2B-fcfdb55-NOGIL/bm-20241121-linux-x86_64-python-fcfdb55465636afc256b-3.14.0a2%2B-fcfdb55-vs-3.12.6.md)[📈](results/bm-20241121-3.14.0a2%2B-fcfdb55-NOGIL/bm-20241121-linux-x86_64-python-fcfdb55465636afc256b-3.14.0a2%2B-fcfdb55-vs-3.12.6.svg) | 1.38x ↓<br>[📄](results/bm-20241121-3.14.0a2%2B-fcfdb55-NOGIL/bm-20241121-linux-x86_64-python-fcfdb55465636afc256b-3.14.0a2%2B-fcfdb55-vs-3.13.0rc2.md)[📈](results/bm-20241121-3.14.0a2%2B-fcfdb55-NOGIL/bm-20241121-linux-x86_64-python-fcfdb55465636afc256b-3.14.0a2%2B-fcfdb55-vs-3.13.0rc2.svg) | 1.39x ↓<br>[📄](results/bm-20241121-3.14.0a2%2B-fcfdb55-NOGIL/bm-20241121-linux-x86_64-python-fcfdb55465636afc256b-3.14.0a2%2B-fcfdb55-vs-base.md)[📈](results/bm-20241121-3.14.0a2%2B-fcfdb55-NOGIL/bm-20241121-linux-x86_64-python-fcfdb55465636afc256b-3.14.0a2%2B-fcfdb55-vs-base.svg)[🧠](results/bm-20241121-3.14.0a2%2B-fcfdb55-NOGIL/bm-20241121-linux-x86_64-python-fcfdb55465636afc256b-3.14.0a2%2B-fcfdb55-vs-base-mem.svg) |
| [2024-11-21](results/bm-20241121-3.14.0a2%2B-fcfdb55) | python/fcfdb55465636afc256b | fcfdb55 | 1.06x ↑<br>[📄](results/bm-20241121-3.14.0a2%2B-fcfdb55/bm-20241121-linux-x86_64-python-fcfdb55465636afc256b-3.14.0a2%2B-fcfdb55-vs-3.12.6.md)[📈](results/bm-20241121-3.14.0a2%2B-fcfdb55/bm-20241121-linux-x86_64-python-fcfdb55465636afc256b-3.14.0a2%2B-fcfdb55-vs-3.12.6.svg) | 1.02x ↑<br>[📄](results/bm-20241121-3.14.0a2%2B-fcfdb55/bm-20241121-linux-x86_64-python-fcfdb55465636afc256b-3.14.0a2%2B-fcfdb55-vs-3.13.0rc2.md)[📈](results/bm-20241121-3.14.0a2%2B-fcfdb55/bm-20241121-linux-x86_64-python-fcfdb55465636afc256b-3.14.0a2%2B-fcfdb55-vs-3.13.0rc2.svg) |  |
| [2024-11-20](results/bm-20241120-3.14.0a2%2B-32428cf-NOGIL) | python/32428cf9ea03bce6d64c | 32428cf (NOGIL) | 1.42x ↓<br>[📄](results/bm-20241120-3.14.0a2%2B-32428cf-NOGIL/bm-20241120-linux-x86_64-python-32428cf9ea03bce6d64c-3.14.0a2%2B-32428cf-vs-3.12.6.md)[📈](results/bm-20241120-3.14.0a2%2B-32428cf-NOGIL/bm-20241120-linux-x86_64-python-32428cf9ea03bce6d64c-3.14.0a2%2B-32428cf-vs-3.12.6.svg) | 1.44x ↓<br>[📄](results/bm-20241120-3.14.0a2%2B-32428cf-NOGIL/bm-20241120-linux-x86_64-python-32428cf9ea03bce6d64c-3.14.0a2%2B-32428cf-vs-3.13.0rc2.md)[📈](results/bm-20241120-3.14.0a2%2B-32428cf-NOGIL/bm-20241120-linux-x86_64-python-32428cf9ea03bce6d64c-3.14.0a2%2B-32428cf-vs-3.13.0rc2.svg) | 1.45x ↓<br>[📄](results/bm-20241120-3.14.0a2%2B-32428cf-NOGIL/bm-20241120-linux-x86_64-python-32428cf9ea03bce6d64c-3.14.0a2%2B-32428cf-vs-base.md)[📈](results/bm-20241120-3.14.0a2%2B-32428cf-NOGIL/bm-20241120-linux-x86_64-python-32428cf9ea03bce6d64c-3.14.0a2%2B-32428cf-vs-base.svg)[🧠](results/bm-20241120-3.14.0a2%2B-32428cf-NOGIL/bm-20241120-linux-x86_64-python-32428cf9ea03bce6d64c-3.14.0a2%2B-32428cf-vs-base-mem.svg) |
| [2024-11-20](results/bm-20241120-3.14.0a2%2B-32428cf) | python/32428cf9ea03bce6d64c | 32428cf | 1.03x ↑<br>[📄](results/bm-20241120-3.14.0a2%2B-32428cf/bm-20241120-linux-x86_64-python-32428cf9ea03bce6d64c-3.14.0a2%2B-32428cf-vs-3.12.6.md)[📈](results/bm-20241120-3.14.0a2%2B-32428cf/bm-20241120-linux-x86_64-python-32428cf9ea03bce6d64c-3.14.0a2%2B-32428cf-vs-3.12.6.svg) | 1.01x ↑<br>[📄](results/bm-20241120-3.14.0a2%2B-32428cf/bm-20241120-linux-x86_64-python-32428cf9ea03bce6d64c-3.14.0a2%2B-32428cf-vs-3.13.0rc2.md)[📈](results/bm-20241120-3.14.0a2%2B-32428cf/bm-20241120-linux-x86_64-python-32428cf9ea03bce6d64c-3.14.0a2%2B-32428cf-vs-3.13.0rc2.svg) |  |
| [2024-11-19](results/bm-20241119-3.14.0a2%2B-c9b399f) | python/c9b399fbdb01584dcfff | c9b399f | 1.01x ↑<br>[📄](results/bm-20241119-3.14.0a2%2B-c9b399f/bm-20241119-linux-x86_64-python-c9b399fbdb01584dcfff-3.14.0a2%2B-c9b399f-vs-3.12.6.md)[📈](results/bm-20241119-3.14.0a2%2B-c9b399f/bm-20241119-linux-x86_64-python-c9b399fbdb01584dcfff-3.14.0a2%2B-c9b399f-vs-3.12.6.svg) | 1.00x ↓<br>[📄](results/bm-20241119-3.14.0a2%2B-c9b399f/bm-20241119-linux-x86_64-python-c9b399fbdb01584dcfff-3.14.0a2%2B-c9b399f-vs-3.13.0rc2.md)[📈](results/bm-20241119-3.14.0a2%2B-c9b399f/bm-20241119-linux-x86_64-python-c9b399fbdb01584dcfff-3.14.0a2%2B-c9b399f-vs-3.13.0rc2.svg) |  |
| [2024-11-19](results/bm-20241119-3.14.0a2%2B-c9b399f-NOGIL) | python/c9b399fbdb01584dcfff | c9b399f (NOGIL) | 1.41x ↓<br>[📄](results/bm-20241119-3.14.0a2%2B-c9b399f-NOGIL/bm-20241119-linux-x86_64-python-c9b399fbdb01584dcfff-3.14.0a2%2B-c9b399f-vs-3.12.6.md)[📈](results/bm-20241119-3.14.0a2%2B-c9b399f-NOGIL/bm-20241119-linux-x86_64-python-c9b399fbdb01584dcfff-3.14.0a2%2B-c9b399f-vs-3.12.6.svg) | 1.43x ↓<br>[📄](results/bm-20241119-3.14.0a2%2B-c9b399f-NOGIL/bm-20241119-linux-x86_64-python-c9b399fbdb01584dcfff-3.14.0a2%2B-c9b399f-vs-3.13.0rc2.md)[📈](results/bm-20241119-3.14.0a2%2B-c9b399f-NOGIL/bm-20241119-linux-x86_64-python-c9b399fbdb01584dcfff-3.14.0a2%2B-c9b399f-vs-3.13.0rc2.svg) | 1.43x ↓<br>[📄](results/bm-20241119-3.14.0a2%2B-c9b399f-NOGIL/bm-20241119-linux-x86_64-python-c9b399fbdb01584dcfff-3.14.0a2%2B-c9b399f-vs-base.md)[📈](results/bm-20241119-3.14.0a2%2B-c9b399f-NOGIL/bm-20241119-linux-x86_64-python-c9b399fbdb01584dcfff-3.14.0a2%2B-c9b399f-vs-base.svg)[🧠](results/bm-20241119-3.14.0a2%2B-c9b399f-NOGIL/bm-20241119-linux-x86_64-python-c9b399fbdb01584dcfff-3.14.0a2%2B-c9b399f-vs-base-mem.svg) |

## linux x86_64 (vultr)
| date | fork/ref | hash/flags | vs. 3.12.6: | vs. 3.13.0rc2: | vs. base: |
| --- | --- | --- | ---: | ---: | ---: |
| [2024-11-22](results/bm-20241122-3.14.0a2%2B-2b63929-NOGIL) | colesbury/gh_115999_store_subs | 2b63929 (NOGIL) | 1.40x ↓<br>[📄](results/bm-20241122-3.14.0a2%2B-2b63929-NOGIL/bm-20241122-vultr-x86_64-colesbury-gh_115999_store_subs-3.14.0a2%2B-2b63929-vs-3.12.6.md)[📈](results/bm-20241122-3.14.0a2%2B-2b63929-NOGIL/bm-20241122-vultr-x86_64-colesbury-gh_115999_store_subs-3.14.0a2%2B-2b63929-vs-3.12.6.svg) | 1.44x ↓<br>[📄](results/bm-20241122-3.14.0a2%2B-2b63929-NOGIL/bm-20241122-vultr-x86_64-colesbury-gh_115999_store_subs-3.14.0a2%2B-2b63929-vs-3.13.0rc2.md)[📈](results/bm-20241122-3.14.0a2%2B-2b63929-NOGIL/bm-20241122-vultr-x86_64-colesbury-gh_115999_store_subs-3.14.0a2%2B-2b63929-vs-3.13.0rc2.svg) |  |
| [2024-11-22](results/bm-20241122-3.14.0a2%2B-9e69bca-NOGIL) | colesbury/gh_127022_py_eval_fr | 9e69bca (NOGIL) | 1.41x ↓<br>[📄](results/bm-20241122-3.14.0a2%2B-9e69bca-NOGIL/bm-20241122-vultr-x86_64-colesbury-gh_127022_py_eval_fr-3.14.0a2%2B-9e69bca-vs-3.12.6.md)[📈](results/bm-20241122-3.14.0a2%2B-9e69bca-NOGIL/bm-20241122-vultr-x86_64-colesbury-gh_127022_py_eval_fr-3.14.0a2%2B-9e69bca-vs-3.12.6.svg) | 1.45x ↓<br>[📄](results/bm-20241122-3.14.0a2%2B-9e69bca-NOGIL/bm-20241122-vultr-x86_64-colesbury-gh_127022_py_eval_fr-3.14.0a2%2B-9e69bca-vs-3.13.0rc2.md)[📈](results/bm-20241122-3.14.0a2%2B-9e69bca-NOGIL/bm-20241122-vultr-x86_64-colesbury-gh_127022_py_eval_fr-3.14.0a2%2B-9e69bca-vs-3.13.0rc2.svg) | 1.01x ↓<br>[📄](results/bm-20241122-3.14.0a2%2B-9e69bca-NOGIL/bm-20241122-vultr-x86_64-colesbury-gh_127022_py_eval_fr-3.14.0a2%2B-9e69bca-vs-base.md)[📈](results/bm-20241122-3.14.0a2%2B-9e69bca-NOGIL/bm-20241122-vultr-x86_64-colesbury-gh_127022_py_eval_fr-3.14.0a2%2B-9e69bca-vs-base.svg)[🧠](results/bm-20241122-3.14.0a2%2B-9e69bca-NOGIL/bm-20241122-vultr-x86_64-colesbury-gh_127022_py_eval_fr-3.14.0a2%2B-9e69bca-vs-base-mem.svg) |
| [2024-11-22](results/bm-20241122-3.14.0a2%2B-4759ba6-NOGIL) | python/4759ba6eec9f0b36b24b | 4759ba6 (NOGIL) | 1.39x ↓<br>[📄](results/bm-20241122-3.14.0a2%2B-4759ba6-NOGIL/bm-20241122-vultr-x86_64-python-4759ba6eec9f0b36b24b-3.14.0a2%2B-4759ba6-vs-3.12.6.md)[📈](results/bm-20241122-3.14.0a2%2B-4759ba6-NOGIL/bm-20241122-vultr-x86_64-python-4759ba6eec9f0b36b24b-3.14.0a2%2B-4759ba6-vs-3.12.6.svg) | 1.44x ↓<br>[📄](results/bm-20241122-3.14.0a2%2B-4759ba6-NOGIL/bm-20241122-vultr-x86_64-python-4759ba6eec9f0b36b24b-3.14.0a2%2B-4759ba6-vs-3.13.0rc2.md)[📈](results/bm-20241122-3.14.0a2%2B-4759ba6-NOGIL/bm-20241122-vultr-x86_64-python-4759ba6eec9f0b36b24b-3.14.0a2%2B-4759ba6-vs-3.13.0rc2.svg) |  |
| [2024-11-21](results/bm-20241121-3.14.0a2%2B-4c7837f-NOGIL) | mpage/gh_115999_tlbc_call | 4c7837f (NOGIL) | 1.49x ↓<br>[📄](results/bm-20241121-3.14.0a2%2B-4c7837f-NOGIL/bm-20241121-vultr-x86_64-mpage-gh_115999_tlbc_call-3.14.0a2%2B-4c7837f-vs-3.12.6.md)[📈](results/bm-20241121-3.14.0a2%2B-4c7837f-NOGIL/bm-20241121-vultr-x86_64-mpage-gh_115999_tlbc_call-3.14.0a2%2B-4c7837f-vs-3.12.6.svg) | 1.54x ↓<br>[📄](results/bm-20241121-3.14.0a2%2B-4c7837f-NOGIL/bm-20241121-vultr-x86_64-mpage-gh_115999_tlbc_call-3.14.0a2%2B-4c7837f-vs-3.13.0rc2.md)[📈](results/bm-20241121-3.14.0a2%2B-4c7837f-NOGIL/bm-20241121-vultr-x86_64-mpage-gh_115999_tlbc_call-3.14.0a2%2B-4c7837f-vs-3.13.0rc2.svg) | 1.03x ↑<br>[📄](results/bm-20241121-3.14.0a2%2B-4c7837f-NOGIL/bm-20241121-vultr-x86_64-mpage-gh_115999_tlbc_call-3.14.0a2%2B-4c7837f-vs-base.md)[📈](results/bm-20241121-3.14.0a2%2B-4c7837f-NOGIL/bm-20241121-vultr-x86_64-mpage-gh_115999_tlbc_call-3.14.0a2%2B-4c7837f-vs-base.svg)[🧠](results/bm-20241121-3.14.0a2%2B-4c7837f-NOGIL/bm-20241121-vultr-x86_64-mpage-gh_115999_tlbc_call-3.14.0a2%2B-4c7837f-vs-base-mem.svg) |
| [2024-11-21](results/bm-20241121-3.14.0a2%2B-fcfdb55-NOGIL) | python/fcfdb55465636afc256b | fcfdb55 (NOGIL) | 1.46x ↓<br>[📄](results/bm-20241121-3.14.0a2%2B-fcfdb55-NOGIL/bm-20241121-vultr-x86_64-python-fcfdb55465636afc256b-3.14.0a2%2B-fcfdb55-vs-3.12.6.md)[📈](results/bm-20241121-3.14.0a2%2B-fcfdb55-NOGIL/bm-20241121-vultr-x86_64-python-fcfdb55465636afc256b-3.14.0a2%2B-fcfdb55-vs-3.12.6.svg) | 1.51x ↓<br>[📄](results/bm-20241121-3.14.0a2%2B-fcfdb55-NOGIL/bm-20241121-vultr-x86_64-python-fcfdb55465636afc256b-3.14.0a2%2B-fcfdb55-vs-3.13.0rc2.md)[📈](results/bm-20241121-3.14.0a2%2B-fcfdb55-NOGIL/bm-20241121-vultr-x86_64-python-fcfdb55465636afc256b-3.14.0a2%2B-fcfdb55-vs-3.13.0rc2.svg) | 1.47x ↓<br>[📄](results/bm-20241121-3.14.0a2%2B-fcfdb55-NOGIL/bm-20241121-vultr-x86_64-python-fcfdb55465636afc256b-3.14.0a2%2B-fcfdb55-vs-base.md)[📈](results/bm-20241121-3.14.0a2%2B-fcfdb55-NOGIL/bm-20241121-vultr-x86_64-python-fcfdb55465636afc256b-3.14.0a2%2B-fcfdb55-vs-base.svg)[🧠](results/bm-20241121-3.14.0a2%2B-fcfdb55-NOGIL/bm-20241121-vultr-x86_64-python-fcfdb55465636afc256b-3.14.0a2%2B-fcfdb55-vs-base-mem.svg) |
| [2024-11-21](results/bm-20241121-3.14.0a2%2B-fcfdb55) | python/fcfdb55465636afc256b | fcfdb55 | 1.02x ↑<br>[📄](results/bm-20241121-3.14.0a2%2B-fcfdb55/bm-20241121-vultr-x86_64-python-fcfdb55465636afc256b-3.14.0a2%2B-fcfdb55-vs-3.12.6.md)[📈](results/bm-20241121-3.14.0a2%2B-fcfdb55/bm-20241121-vultr-x86_64-python-fcfdb55465636afc256b-3.14.0a2%2B-fcfdb55-vs-3.12.6.svg) | 1.02x ↓<br>[📄](results/bm-20241121-3.14.0a2%2B-fcfdb55/bm-20241121-vultr-x86_64-python-fcfdb55465636afc256b-3.14.0a2%2B-fcfdb55-vs-3.13.0rc2.md)[📈](results/bm-20241121-3.14.0a2%2B-fcfdb55/bm-20241121-vultr-x86_64-python-fcfdb55465636afc256b-3.14.0a2%2B-fcfdb55-vs-3.13.0rc2.svg) |  |
| [2024-11-20](results/bm-20241120-3.14.0a2%2B-8ebd73d) | mpage/gh_115999_tlbc_call | 8ebd73d | 1.00x ↓<br>[📄](results/bm-20241120-3.14.0a2%2B-8ebd73d/bm-20241120-vultr-x86_64-mpage-gh_115999_tlbc_call-3.14.0a2%2B-8ebd73d-vs-3.12.6.md)[📈](results/bm-20241120-3.14.0a2%2B-8ebd73d/bm-20241120-vultr-x86_64-mpage-gh_115999_tlbc_call-3.14.0a2%2B-8ebd73d-vs-3.12.6.svg) | 1.02x ↓<br>[📄](results/bm-20241120-3.14.0a2%2B-8ebd73d/bm-20241120-vultr-x86_64-mpage-gh_115999_tlbc_call-3.14.0a2%2B-8ebd73d-vs-3.13.0rc2.md)[📈](results/bm-20241120-3.14.0a2%2B-8ebd73d/bm-20241120-vultr-x86_64-mpage-gh_115999_tlbc_call-3.14.0a2%2B-8ebd73d-vs-3.13.0rc2.svg) | 1.00x ↑<br>[📄](results/bm-20241120-3.14.0a2%2B-8ebd73d/bm-20241120-vultr-x86_64-mpage-gh_115999_tlbc_call-3.14.0a2%2B-8ebd73d-vs-base.md)[📈](results/bm-20241120-3.14.0a2%2B-8ebd73d/bm-20241120-vultr-x86_64-mpage-gh_115999_tlbc_call-3.14.0a2%2B-8ebd73d-vs-base.svg)[🧠](results/bm-20241120-3.14.0a2%2B-8ebd73d/bm-20241120-vultr-x86_64-mpage-gh_115999_tlbc_call-3.14.0a2%2B-8ebd73d-vs-base-mem.svg) |
| [2024-11-20](results/bm-20241120-3.14.0a2%2B-8ebd73d-NOGIL) | mpage/gh_115999_tlbc_call | 8ebd73d (NOGIL) | 1.50x ↓<br>[📄](results/bm-20241120-3.14.0a2%2B-8ebd73d-NOGIL/bm-20241120-vultr-x86_64-mpage-gh_115999_tlbc_call-3.14.0a2%2B-8ebd73d-vs-3.12.6.md)[📈](results/bm-20241120-3.14.0a2%2B-8ebd73d-NOGIL/bm-20241120-vultr-x86_64-mpage-gh_115999_tlbc_call-3.14.0a2%2B-8ebd73d-vs-3.12.6.svg) | 1.52x ↓<br>[📄](results/bm-20241120-3.14.0a2%2B-8ebd73d-NOGIL/bm-20241120-vultr-x86_64-mpage-gh_115999_tlbc_call-3.14.0a2%2B-8ebd73d-vs-3.13.0rc2.md)[📈](results/bm-20241120-3.14.0a2%2B-8ebd73d-NOGIL/bm-20241120-vultr-x86_64-mpage-gh_115999_tlbc_call-3.14.0a2%2B-8ebd73d-vs-3.13.0rc2.svg) | 1.03x ↑<br>[📄](results/bm-20241120-3.14.0a2%2B-8ebd73d-NOGIL/bm-20241120-vultr-x86_64-mpage-gh_115999_tlbc_call-3.14.0a2%2B-8ebd73d-vs-base.md)[📈](results/bm-20241120-3.14.0a2%2B-8ebd73d-NOGIL/bm-20241120-vultr-x86_64-mpage-gh_115999_tlbc_call-3.14.0a2%2B-8ebd73d-vs-base.svg)[🧠](results/bm-20241120-3.14.0a2%2B-8ebd73d-NOGIL/bm-20241120-vultr-x86_64-mpage-gh_115999_tlbc_call-3.14.0a2%2B-8ebd73d-vs-base-mem.svg) |
| [2024-11-20](results/bm-20241120-3.14.0a2%2B-32428cf-NOGIL) | python/32428cf9ea03bce6d64c | 32428cf (NOGIL) | 1.54x ↓<br>[📄](results/bm-20241120-3.14.0a2%2B-32428cf-NOGIL/bm-20241120-vultr-x86_64-python-32428cf9ea03bce6d64c-3.14.0a2%2B-32428cf-vs-3.12.6.md)[📈](results/bm-20241120-3.14.0a2%2B-32428cf-NOGIL/bm-20241120-vultr-x86_64-python-32428cf9ea03bce6d64c-3.14.0a2%2B-32428cf-vs-3.12.6.svg) | 1.56x ↓<br>[📄](results/bm-20241120-3.14.0a2%2B-32428cf-NOGIL/bm-20241120-vultr-x86_64-python-32428cf9ea03bce6d64c-3.14.0a2%2B-32428cf-vs-3.13.0rc2.md)[📈](results/bm-20241120-3.14.0a2%2B-32428cf-NOGIL/bm-20241120-vultr-x86_64-python-32428cf9ea03bce6d64c-3.14.0a2%2B-32428cf-vs-3.13.0rc2.svg) | 1.53x ↓<br>[📄](results/bm-20241120-3.14.0a2%2B-32428cf-NOGIL/bm-20241120-vultr-x86_64-python-32428cf9ea03bce6d64c-3.14.0a2%2B-32428cf-vs-base.md)[📈](results/bm-20241120-3.14.0a2%2B-32428cf-NOGIL/bm-20241120-vultr-x86_64-python-32428cf9ea03bce6d64c-3.14.0a2%2B-32428cf-vs-base.svg)[🧠](results/bm-20241120-3.14.0a2%2B-32428cf-NOGIL/bm-20241120-vultr-x86_64-python-32428cf9ea03bce6d64c-3.14.0a2%2B-32428cf-vs-base-mem.svg) |
| [2024-11-20](results/bm-20241120-3.14.0a2%2B-32428cf) | python/32428cf9ea03bce6d64c | 32428cf | 1.00x ↓<br>[📄](results/bm-20241120-3.14.0a2%2B-32428cf/bm-20241120-vultr-x86_64-python-32428cf9ea03bce6d64c-3.14.0a2%2B-32428cf-vs-3.12.6.md)[📈](results/bm-20241120-3.14.0a2%2B-32428cf/bm-20241120-vultr-x86_64-python-32428cf9ea03bce6d64c-3.14.0a2%2B-32428cf-vs-3.12.6.svg) | 1.02x ↓<br>[📄](results/bm-20241120-3.14.0a2%2B-32428cf/bm-20241120-vultr-x86_64-python-32428cf9ea03bce6d64c-3.14.0a2%2B-32428cf-vs-3.13.0rc2.md)[📈](results/bm-20241120-3.14.0a2%2B-32428cf/bm-20241120-vultr-x86_64-python-32428cf9ea03bce6d64c-3.14.0a2%2B-32428cf-vs-3.13.0rc2.svg) |  |
| [2024-11-19](results/bm-20241119-3.14.0a2%2B-c9b399f) | python/c9b399fbdb01584dcfff | c9b399f | 1.01x ↓<br>[📄](results/bm-20241119-3.14.0a2%2B-c9b399f/bm-20241119-vultr-x86_64-python-c9b399fbdb01584dcfff-3.14.0a2%2B-c9b399f-vs-3.12.6.md)[📈](results/bm-20241119-3.14.0a2%2B-c9b399f/bm-20241119-vultr-x86_64-python-c9b399fbdb01584dcfff-3.14.0a2%2B-c9b399f-vs-3.12.6.svg) | 1.02x ↓<br>[📄](results/bm-20241119-3.14.0a2%2B-c9b399f/bm-20241119-vultr-x86_64-python-c9b399fbdb01584dcfff-3.14.0a2%2B-c9b399f-vs-3.13.0rc2.md)[📈](results/bm-20241119-3.14.0a2%2B-c9b399f/bm-20241119-vultr-x86_64-python-c9b399fbdb01584dcfff-3.14.0a2%2B-c9b399f-vs-3.13.0rc2.svg) |  |
| [2024-11-19](results/bm-20241119-3.14.0a2%2B-c9b399f-NOGIL) | python/c9b399fbdb01584dcfff | c9b399f (NOGIL) | 1.54x ↓<br>[📄](results/bm-20241119-3.14.0a2%2B-c9b399f-NOGIL/bm-20241119-vultr-x86_64-python-c9b399fbdb01584dcfff-3.14.0a2%2B-c9b399f-vs-3.12.6.md)[📈](results/bm-20241119-3.14.0a2%2B-c9b399f-NOGIL/bm-20241119-vultr-x86_64-python-c9b399fbdb01584dcfff-3.14.0a2%2B-c9b399f-vs-3.12.6.svg) | 1.56x ↓<br>[📄](results/bm-20241119-3.14.0a2%2B-c9b399f-NOGIL/bm-20241119-vultr-x86_64-python-c9b399fbdb01584dcfff-3.14.0a2%2B-c9b399f-vs-3.13.0rc2.md)[📈](results/bm-20241119-3.14.0a2%2B-c9b399f-NOGIL/bm-20241119-vultr-x86_64-python-c9b399fbdb01584dcfff-3.14.0a2%2B-c9b399f-vs-3.13.0rc2.svg) | 1.53x ↓<br>[📄](results/bm-20241119-3.14.0a2%2B-c9b399f-NOGIL/bm-20241119-vultr-x86_64-python-c9b399fbdb01584dcfff-3.14.0a2%2B-c9b399f-vs-base.md)[📈](results/bm-20241119-3.14.0a2%2B-c9b399f-NOGIL/bm-20241119-vultr-x86_64-python-c9b399fbdb01584dcfff-3.14.0a2%2B-c9b399f-vs-base.svg)[🧠](results/bm-20241119-3.14.0a2%2B-c9b399f-NOGIL/bm-20241119-vultr-x86_64-python-c9b399fbdb01584dcfff-3.14.0a2%2B-c9b399f-vs-base-mem.svg) |
| [2024-11-22](results/bm-20241122-3.14.0a1%2B-a9e4872-NOGIL) | colesbury/gh_127022_cheaper_st | a9e4872 (NOGIL) | 1.49x ↓<br>[📄](results/bm-20241122-3.14.0a1%2B-a9e4872-NOGIL/bm-20241122-vultr-x86_64-colesbury-gh_127022_cheaper_st-3.14.0a1%2B-a9e4872-vs-3.12.6.md)[📈](results/bm-20241122-3.14.0a1%2B-a9e4872-NOGIL/bm-20241122-vultr-x86_64-colesbury-gh_127022_cheaper_st-3.14.0a1%2B-a9e4872-vs-3.12.6.svg) | 1.54x ↓<br>[📄](results/bm-20241122-3.14.0a1%2B-a9e4872-NOGIL/bm-20241122-vultr-x86_64-colesbury-gh_127022_cheaper_st-3.14.0a1%2B-a9e4872-vs-3.13.0rc2.md)[📈](results/bm-20241122-3.14.0a1%2B-a9e4872-NOGIL/bm-20241122-vultr-x86_64-colesbury-gh_127022_cheaper_st-3.14.0a1%2B-a9e4872-vs-3.13.0rc2.svg) | 1.03x ↑<br>[📄](results/bm-20241122-3.14.0a1%2B-a9e4872-NOGIL/bm-20241122-vultr-x86_64-colesbury-gh_127022_cheaper_st-3.14.0a1%2B-a9e4872-vs-base.md)[📈](results/bm-20241122-3.14.0a1%2B-a9e4872-NOGIL/bm-20241122-vultr-x86_64-colesbury-gh_127022_cheaper_st-3.14.0a1%2B-a9e4872-vs-base.svg)[🧠](results/bm-20241122-3.14.0a1%2B-a9e4872-NOGIL/bm-20241122-vultr-x86_64-colesbury-gh_127022_cheaper_st-3.14.0a1%2B-a9e4872-vs-base-mem.svg) |
| [2024-11-19](results/bm-20241119-3.14.0a1%2B-29cbcbd-NOGIL) | python/29cbcbd73bbfd8c953c0 | 29cbcbd (NOGIL) | 1.55x ↓<br>[📄](results/bm-20241119-3.14.0a1%2B-29cbcbd-NOGIL/bm-20241119-vultr-x86_64-python-29cbcbd73bbfd8c953c0-3.14.0a1%2B-29cbcbd-vs-3.12.6.md)[📈](results/bm-20241119-3.14.0a1%2B-29cbcbd-NOGIL/bm-20241119-vultr-x86_64-python-29cbcbd73bbfd8c953c0-3.14.0a1%2B-29cbcbd-vs-3.12.6.svg) | 1.58x ↓<br>[📄](results/bm-20241119-3.14.0a1%2B-29cbcbd-NOGIL/bm-20241119-vultr-x86_64-python-29cbcbd73bbfd8c953c0-3.14.0a1%2B-29cbcbd-vs-3.13.0rc2.md)[📈](results/bm-20241119-3.14.0a1%2B-29cbcbd-NOGIL/bm-20241119-vultr-x86_64-python-29cbcbd73bbfd8c953c0-3.14.0a1%2B-29cbcbd-vs-3.13.0rc2.svg) |  |
| [2024-11-18](results/bm-20241118-3.14.0a1%2B-e051157-NOGIL) | mpage/gh_115999_tlbc_call_ | e051157 (NOGIL) | 1.55x ↓<br>[📄](results/bm-20241118-3.14.0a1%2B-e051157-NOGIL/bm-20241118-vultr-x86_64-mpage-gh_115999_tlbc_call_-3.14.0a1%2B-e051157-vs-3.12.6.md)[📈](results/bm-20241118-3.14.0a1%2B-e051157-NOGIL/bm-20241118-vultr-x86_64-mpage-gh_115999_tlbc_call_-3.14.0a1%2B-e051157-vs-3.12.6.svg) | 1.57x ↓<br>[📄](results/bm-20241118-3.14.0a1%2B-e051157-NOGIL/bm-20241118-vultr-x86_64-mpage-gh_115999_tlbc_call_-3.14.0a1%2B-e051157-vs-3.13.0rc2.md)[📈](results/bm-20241118-3.14.0a1%2B-e051157-NOGIL/bm-20241118-vultr-x86_64-mpage-gh_115999_tlbc_call_-3.14.0a1%2B-e051157-vs-3.13.0rc2.svg) | 1.00x ↑<br>[📄](results/bm-20241118-3.14.0a1%2B-e051157-NOGIL/bm-20241118-vultr-x86_64-mpage-gh_115999_tlbc_call_-3.14.0a1%2B-e051157-vs-base.md)[📈](results/bm-20241118-3.14.0a1%2B-e051157-NOGIL/bm-20241118-vultr-x86_64-mpage-gh_115999_tlbc_call_-3.14.0a1%2B-e051157-vs-base.svg)[🧠](results/bm-20241118-3.14.0a1%2B-e051157-NOGIL/bm-20241118-vultr-x86_64-mpage-gh_115999_tlbc_call_-3.14.0a1%2B-e051157-vs-base-mem.svg) |
| [2024-11-17](results/bm-20241117-3.14.0a1%2B-9d6366b-NOGIL) | python/9d6366b60d01305fc5e4 | 9d6366b (NOGIL) | 1.55x ↓<br>[📄](results/bm-20241117-3.14.0a1%2B-9d6366b-NOGIL/bm-20241117-vultr-x86_64-python-9d6366b60d01305fc5e4-3.14.0a1%2B-9d6366b-vs-3.12.6.md)[📈](results/bm-20241117-3.14.0a1%2B-9d6366b-NOGIL/bm-20241117-vultr-x86_64-python-9d6366b60d01305fc5e4-3.14.0a1%2B-9d6366b-vs-3.12.6.svg) | 1.57x ↓<br>[📄](results/bm-20241117-3.14.0a1%2B-9d6366b-NOGIL/bm-20241117-vultr-x86_64-python-9d6366b60d01305fc5e4-3.14.0a1%2B-9d6366b-vs-3.13.0rc2.md)[📈](results/bm-20241117-3.14.0a1%2B-9d6366b-NOGIL/bm-20241117-vultr-x86_64-python-9d6366b60d01305fc5e4-3.14.0a1%2B-9d6366b-vs-3.13.0rc2.svg) | 1.01x ↑<br>[📄](results/bm-20241117-3.14.0a1%2B-9d6366b-NOGIL/bm-20241117-vultr-x86_64-python-9d6366b60d01305fc5e4-3.14.0a1%2B-9d6366b-vs-base.md)[📈](results/bm-20241117-3.14.0a1%2B-9d6366b-NOGIL/bm-20241117-vultr-x86_64-python-9d6366b60d01305fc5e4-3.14.0a1%2B-9d6366b-vs-base.svg)[🧠](results/bm-20241117-3.14.0a1%2B-9d6366b-NOGIL/bm-20241117-vultr-x86_64-python-9d6366b60d01305fc5e4-3.14.0a1%2B-9d6366b-vs-base-mem.svg) |


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
