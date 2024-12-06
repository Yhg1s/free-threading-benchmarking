# Faster CPython Benchmark Infrastructure

🔒 [▶️ START A BENCHMARK RUN](../../actions/workflows/benchmark.yml)

## Results

Here are some recent and important revisions. 👉 [Complete list of results](RESULTS.md).

<!-- START table -->
[Most recent pystats on main (dbd2379)](results/bm-20241123-3.14.0a2%2B-dbd2379-PYTHON_UOPS/bm-20241123-vultr-x86_64-python-dbd23790dbd662169905-3.14.0a2%2B-dbd2379-pystats.md)

## linux x86_64 (linux)
| date | fork/ref | hash/flags | vs. 3.12.6: | vs. 3.13.0rc2: | vs. base: |
| --- | --- | --- | ---: | ---: | ---: |
| [2024-12-05](results/bm-20241205-3.14.0a2%2B-8b3cccf) | python/8b3cccf3f9508572d85b | 8b3cccf | 1.082x ↑<br>[📄](results/bm-20241205-3.14.0a2%2B-8b3cccf/bm-20241205-linux-x86_64-python-8b3cccf3f9508572d85b-3.14.0a2%2B-8b3cccf-vs-3.12.6.md)[📈](results/bm-20241205-3.14.0a2%2B-8b3cccf/bm-20241205-linux-x86_64-python-8b3cccf3f9508572d85b-3.14.0a2%2B-8b3cccf-vs-3.12.6.svg) | 1.038x ↑<br>[📄](results/bm-20241205-3.14.0a2%2B-8b3cccf/bm-20241205-linux-x86_64-python-8b3cccf3f9508572d85b-3.14.0a2%2B-8b3cccf-vs-3.13.0rc2.md)[📈](results/bm-20241205-3.14.0a2%2B-8b3cccf/bm-20241205-linux-x86_64-python-8b3cccf3f9508572d85b-3.14.0a2%2B-8b3cccf-vs-3.13.0rc2.svg) |  |
| [2024-12-05](results/bm-20241205-3.14.0a2%2B-2f1cee8) | python/2f1cee8477e22bfc36a7 | 2f1cee8 | 1.115x ↑<br>[📄](results/bm-20241205-3.14.0a2%2B-2f1cee8/bm-20241205-linux-x86_64-python-2f1cee8477e22bfc36a7-3.14.0a2%2B-2f1cee8-vs-3.12.6.md)[📈](results/bm-20241205-3.14.0a2%2B-2f1cee8/bm-20241205-linux-x86_64-python-2f1cee8477e22bfc36a7-3.14.0a2%2B-2f1cee8-vs-3.12.6.svg) | 1.067x ↑<br>[📄](results/bm-20241205-3.14.0a2%2B-2f1cee8/bm-20241205-linux-x86_64-python-2f1cee8477e22bfc36a7-3.14.0a2%2B-2f1cee8-vs-3.13.0rc2.md)[📈](results/bm-20241205-3.14.0a2%2B-2f1cee8/bm-20241205-linux-x86_64-python-2f1cee8477e22bfc36a7-3.14.0a2%2B-2f1cee8-vs-3.13.0rc2.svg) |  |
| [2024-12-05](results/bm-20241205-3.14.0a2%2B-2f1cee8-NOGIL) | python/2f1cee8477e22bfc36a7 | 2f1cee8 (NOGIL) | 1.171x ↓<br>[📄](results/bm-20241205-3.14.0a2%2B-2f1cee8-NOGIL/bm-20241205-linux-x86_64-python-2f1cee8477e22bfc36a7-3.14.0a2%2B-2f1cee8-vs-3.12.6.md)[📈](results/bm-20241205-3.14.0a2%2B-2f1cee8-NOGIL/bm-20241205-linux-x86_64-python-2f1cee8477e22bfc36a7-3.14.0a2%2B-2f1cee8-vs-3.12.6.svg) | 1.201x ↓<br>[📄](results/bm-20241205-3.14.0a2%2B-2f1cee8-NOGIL/bm-20241205-linux-x86_64-python-2f1cee8477e22bfc36a7-3.14.0a2%2B-2f1cee8-vs-3.13.0rc2.md)[📈](results/bm-20241205-3.14.0a2%2B-2f1cee8-NOGIL/bm-20241205-linux-x86_64-python-2f1cee8477e22bfc36a7-3.14.0a2%2B-2f1cee8-vs-3.13.0rc2.svg) | 1.249x ↓<br>[📄](results/bm-20241205-3.14.0a2%2B-2f1cee8-NOGIL/bm-20241205-linux-x86_64-python-2f1cee8477e22bfc36a7-3.14.0a2%2B-2f1cee8-vs-base.md)[📈](results/bm-20241205-3.14.0a2%2B-2f1cee8-NOGIL/bm-20241205-linux-x86_64-python-2f1cee8477e22bfc36a7-3.14.0a2%2B-2f1cee8-vs-base.svg)[🧠](results/bm-20241205-3.14.0a2%2B-2f1cee8-NOGIL/bm-20241205-linux-x86_64-python-2f1cee8477e22bfc36a7-3.14.0a2%2B-2f1cee8-vs-base-mem.svg) |
| [2024-12-03](results/bm-20241203-3.14.0a2%2B-7f882c8) | python/7f882c88cfda48694797 | 7f882c8 | 1.118x ↑<br>[📄](results/bm-20241203-3.14.0a2%2B-7f882c8/bm-20241203-linux-x86_64-python-7f882c88cfda48694797-3.14.0a2%2B-7f882c8-vs-3.12.6.md)[📈](results/bm-20241203-3.14.0a2%2B-7f882c8/bm-20241203-linux-x86_64-python-7f882c88cfda48694797-3.14.0a2%2B-7f882c8-vs-3.12.6.svg) | 1.075x ↑<br>[📄](results/bm-20241203-3.14.0a2%2B-7f882c8/bm-20241203-linux-x86_64-python-7f882c88cfda48694797-3.14.0a2%2B-7f882c8-vs-3.13.0rc2.md)[📈](results/bm-20241203-3.14.0a2%2B-7f882c8/bm-20241203-linux-x86_64-python-7f882c88cfda48694797-3.14.0a2%2B-7f882c8-vs-3.13.0rc2.svg) |  |
| [2024-12-03](results/bm-20241203-3.14.0a2%2B-7f882c8-NOGIL) | python/7f882c88cfda48694797 | 7f882c8 (NOGIL) | 1.166x ↓<br>[📄](results/bm-20241203-3.14.0a2%2B-7f882c8-NOGIL/bm-20241203-linux-x86_64-python-7f882c88cfda48694797-3.14.0a2%2B-7f882c8-vs-3.12.6.md)[📈](results/bm-20241203-3.14.0a2%2B-7f882c8-NOGIL/bm-20241203-linux-x86_64-python-7f882c88cfda48694797-3.14.0a2%2B-7f882c8-vs-3.12.6.svg) | 1.195x ↓<br>[📄](results/bm-20241203-3.14.0a2%2B-7f882c8-NOGIL/bm-20241203-linux-x86_64-python-7f882c88cfda48694797-3.14.0a2%2B-7f882c8-vs-3.13.0rc2.md)[📈](results/bm-20241203-3.14.0a2%2B-7f882c8-NOGIL/bm-20241203-linux-x86_64-python-7f882c88cfda48694797-3.14.0a2%2B-7f882c8-vs-3.13.0rc2.svg) | 1.249x ↓<br>[📄](results/bm-20241203-3.14.0a2%2B-7f882c8-NOGIL/bm-20241203-linux-x86_64-python-7f882c88cfda48694797-3.14.0a2%2B-7f882c8-vs-base.md)[📈](results/bm-20241203-3.14.0a2%2B-7f882c8-NOGIL/bm-20241203-linux-x86_64-python-7f882c88cfda48694797-3.14.0a2%2B-7f882c8-vs-base.svg)[🧠](results/bm-20241203-3.14.0a2%2B-7f882c8-NOGIL/bm-20241203-linux-x86_64-python-7f882c88cfda48694797-3.14.0a2%2B-7f882c8-vs-base-mem.svg) |
| [2024-12-03](results/bm-20241203-3.14.0a2%2B-bfb0788) | python/bfb0788bfcaab7474c1b | bfb0788 | 1.116x ↑<br>[📄](results/bm-20241203-3.14.0a2%2B-bfb0788/bm-20241203-linux-x86_64-python-bfb0788bfcaab7474c1b-3.14.0a2%2B-bfb0788-vs-3.12.6.md)[📈](results/bm-20241203-3.14.0a2%2B-bfb0788/bm-20241203-linux-x86_64-python-bfb0788bfcaab7474c1b-3.14.0a2%2B-bfb0788-vs-3.12.6.svg) | 1.070x ↑<br>[📄](results/bm-20241203-3.14.0a2%2B-bfb0788/bm-20241203-linux-x86_64-python-bfb0788bfcaab7474c1b-3.14.0a2%2B-bfb0788-vs-3.13.0rc2.md)[📈](results/bm-20241203-3.14.0a2%2B-bfb0788/bm-20241203-linux-x86_64-python-bfb0788bfcaab7474c1b-3.14.0a2%2B-bfb0788-vs-3.13.0rc2.svg) |  |
| [2024-12-03](results/bm-20241203-3.14.0a2%2B-bfb0788-NOGIL) | python/bfb0788bfcaab7474c1b | bfb0788 (NOGIL) | 1.204x ↓<br>[📄](results/bm-20241203-3.14.0a2%2B-bfb0788-NOGIL/bm-20241203-linux-x86_64-python-bfb0788bfcaab7474c1b-3.14.0a2%2B-bfb0788-vs-3.12.6.md)[📈](results/bm-20241203-3.14.0a2%2B-bfb0788-NOGIL/bm-20241203-linux-x86_64-python-bfb0788bfcaab7474c1b-3.14.0a2%2B-bfb0788-vs-3.12.6.svg) | 1.231x ↓<br>[📄](results/bm-20241203-3.14.0a2%2B-bfb0788-NOGIL/bm-20241203-linux-x86_64-python-bfb0788bfcaab7474c1b-3.14.0a2%2B-bfb0788-vs-3.13.0rc2.md)[📈](results/bm-20241203-3.14.0a2%2B-bfb0788-NOGIL/bm-20241203-linux-x86_64-python-bfb0788bfcaab7474c1b-3.14.0a2%2B-bfb0788-vs-3.13.0rc2.svg) | 1.277x ↓<br>[📄](results/bm-20241203-3.14.0a2%2B-bfb0788-NOGIL/bm-20241203-linux-x86_64-python-bfb0788bfcaab7474c1b-3.14.0a2%2B-bfb0788-vs-base.md)[📈](results/bm-20241203-3.14.0a2%2B-bfb0788-NOGIL/bm-20241203-linux-x86_64-python-bfb0788bfcaab7474c1b-3.14.0a2%2B-bfb0788-vs-base.svg)[🧠](results/bm-20241203-3.14.0a2%2B-bfb0788-NOGIL/bm-20241203-linux-x86_64-python-bfb0788bfcaab7474c1b-3.14.0a2%2B-bfb0788-vs-base-mem.svg) |

## linux x86_64 (vultr)
| date | fork/ref | hash/flags | vs. 3.12.6: | vs. 3.13.0rc2: | vs. base: |
| --- | --- | --- | ---: | ---: | ---: |
| [2024-12-05](results/bm-20241205-3.14.0a2%2B-2f1cee8) | python/2f1cee8477e22bfc36a7 | 2f1cee8 | 1.068x ↑<br>[📄](results/bm-20241205-3.14.0a2%2B-2f1cee8/bm-20241205-vultr-x86_64-python-2f1cee8477e22bfc36a7-3.14.0a2%2B-2f1cee8-vs-3.12.6.md)[📈](results/bm-20241205-3.14.0a2%2B-2f1cee8/bm-20241205-vultr-x86_64-python-2f1cee8477e22bfc36a7-3.14.0a2%2B-2f1cee8-vs-3.12.6.svg) | 1.030x ↑<br>[📄](results/bm-20241205-3.14.0a2%2B-2f1cee8/bm-20241205-vultr-x86_64-python-2f1cee8477e22bfc36a7-3.14.0a2%2B-2f1cee8-vs-3.13.0rc2.md)[📈](results/bm-20241205-3.14.0a2%2B-2f1cee8/bm-20241205-vultr-x86_64-python-2f1cee8477e22bfc36a7-3.14.0a2%2B-2f1cee8-vs-3.13.0rc2.svg) |  |
| [2024-12-05](results/bm-20241205-3.14.0a2%2B-2f1cee8-NOGIL) | python/2f1cee8477e22bfc36a7 | 2f1cee8 (NOGIL) | 1.231x ↓<br>[📄](results/bm-20241205-3.14.0a2%2B-2f1cee8-NOGIL/bm-20241205-vultr-x86_64-python-2f1cee8477e22bfc36a7-3.14.0a2%2B-2f1cee8-vs-3.12.6.md)[📈](results/bm-20241205-3.14.0a2%2B-2f1cee8-NOGIL/bm-20241205-vultr-x86_64-python-2f1cee8477e22bfc36a7-3.14.0a2%2B-2f1cee8-vs-3.12.6.svg) | 1.255x ↓<br>[📄](results/bm-20241205-3.14.0a2%2B-2f1cee8-NOGIL/bm-20241205-vultr-x86_64-python-2f1cee8477e22bfc36a7-3.14.0a2%2B-2f1cee8-vs-3.13.0rc2.md)[📈](results/bm-20241205-3.14.0a2%2B-2f1cee8-NOGIL/bm-20241205-vultr-x86_64-python-2f1cee8477e22bfc36a7-3.14.0a2%2B-2f1cee8-vs-3.13.0rc2.svg) | 1.274x ↓<br>[📄](results/bm-20241205-3.14.0a2%2B-2f1cee8-NOGIL/bm-20241205-vultr-x86_64-python-2f1cee8477e22bfc36a7-3.14.0a2%2B-2f1cee8-vs-base.md)[📈](results/bm-20241205-3.14.0a2%2B-2f1cee8-NOGIL/bm-20241205-vultr-x86_64-python-2f1cee8477e22bfc36a7-3.14.0a2%2B-2f1cee8-vs-base.svg)[🧠](results/bm-20241205-3.14.0a2%2B-2f1cee8-NOGIL/bm-20241205-vultr-x86_64-python-2f1cee8477e22bfc36a7-3.14.0a2%2B-2f1cee8-vs-base-mem.svg) |
| [2024-12-04](results/bm-20241204-3.14.0a2%2B-a7b41c8-NOGIL) | colesbury/gh_127582_resurrecti | a7b41c8 (NOGIL) | 1.225x ↓<br>[📄](results/bm-20241204-3.14.0a2%2B-a7b41c8-NOGIL/bm-20241204-vultr-x86_64-colesbury-gh_127582_resurrecti-3.14.0a2%2B-a7b41c8-vs-3.12.6.md)[📈](results/bm-20241204-3.14.0a2%2B-a7b41c8-NOGIL/bm-20241204-vultr-x86_64-colesbury-gh_127582_resurrecti-3.14.0a2%2B-a7b41c8-vs-3.12.6.svg) | 1.249x ↓<br>[📄](results/bm-20241204-3.14.0a2%2B-a7b41c8-NOGIL/bm-20241204-vultr-x86_64-colesbury-gh_127582_resurrecti-3.14.0a2%2B-a7b41c8-vs-3.13.0rc2.md)[📈](results/bm-20241204-3.14.0a2%2B-a7b41c8-NOGIL/bm-20241204-vultr-x86_64-colesbury-gh_127582_resurrecti-3.14.0a2%2B-a7b41c8-vs-3.13.0rc2.svg) | 1.000x ↓<br>[📄](results/bm-20241204-3.14.0a2%2B-a7b41c8-NOGIL/bm-20241204-vultr-x86_64-colesbury-gh_127582_resurrecti-3.14.0a2%2B-a7b41c8-vs-base.md)[📈](results/bm-20241204-3.14.0a2%2B-a7b41c8-NOGIL/bm-20241204-vultr-x86_64-colesbury-gh_127582_resurrecti-3.14.0a2%2B-a7b41c8-vs-base.svg)[🧠](results/bm-20241204-3.14.0a2%2B-a7b41c8-NOGIL/bm-20241204-vultr-x86_64-colesbury-gh_127582_resurrecti-3.14.0a2%2B-a7b41c8-vs-base-mem.svg) |
| [2024-12-04](results/bm-20241204-3.14.0a2%2B-de73a27-NOGIL) | mpage/gh_115999_load_attr_ | de73a27 (NOGIL) | 1.219x ↓<br>[📄](results/bm-20241204-3.14.0a2%2B-de73a27-NOGIL/bm-20241204-vultr-x86_64-mpage-gh_115999_load_attr_-3.14.0a2%2B-de73a27-vs-3.12.6.md)[📈](results/bm-20241204-3.14.0a2%2B-de73a27-NOGIL/bm-20241204-vultr-x86_64-mpage-gh_115999_load_attr_-3.14.0a2%2B-de73a27-vs-3.12.6.svg) | 1.244x ↓<br>[📄](results/bm-20241204-3.14.0a2%2B-de73a27-NOGIL/bm-20241204-vultr-x86_64-mpage-gh_115999_load_attr_-3.14.0a2%2B-de73a27-vs-3.13.0rc2.md)[📈](results/bm-20241204-3.14.0a2%2B-de73a27-NOGIL/bm-20241204-vultr-x86_64-mpage-gh_115999_load_attr_-3.14.0a2%2B-de73a27-vs-3.13.0rc2.svg) | 1.017x ↑<br>[📄](results/bm-20241204-3.14.0a2%2B-de73a27-NOGIL/bm-20241204-vultr-x86_64-mpage-gh_115999_load_attr_-3.14.0a2%2B-de73a27-vs-base.md)[📈](results/bm-20241204-3.14.0a2%2B-de73a27-NOGIL/bm-20241204-vultr-x86_64-mpage-gh_115999_load_attr_-3.14.0a2%2B-de73a27-vs-base.svg)[🧠](results/bm-20241204-3.14.0a2%2B-de73a27-NOGIL/bm-20241204-vultr-x86_64-mpage-gh_115999_load_attr_-3.14.0a2%2B-de73a27-vs-base-mem.svg) |
| [2024-12-04](results/bm-20241204-3.14.0a2%2B-6bc3e83-NOGIL) | python/6bc3e830a518112a4e24 | 6bc3e83 (NOGIL) | 1.224x ↓<br>[📄](results/bm-20241204-3.14.0a2%2B-6bc3e83-NOGIL/bm-20241204-vultr-x86_64-python-6bc3e830a518112a4e24-3.14.0a2%2B-6bc3e83-vs-3.12.6.md)[📈](results/bm-20241204-3.14.0a2%2B-6bc3e83-NOGIL/bm-20241204-vultr-x86_64-python-6bc3e830a518112a4e24-3.14.0a2%2B-6bc3e83-vs-3.12.6.svg) | 1.249x ↓<br>[📄](results/bm-20241204-3.14.0a2%2B-6bc3e83-NOGIL/bm-20241204-vultr-x86_64-python-6bc3e830a518112a4e24-3.14.0a2%2B-6bc3e83-vs-3.13.0rc2.md)[📈](results/bm-20241204-3.14.0a2%2B-6bc3e83-NOGIL/bm-20241204-vultr-x86_64-python-6bc3e830a518112a4e24-3.14.0a2%2B-6bc3e83-vs-3.13.0rc2.svg) |  |
| [2024-12-04](results/bm-20241204-3.14.0a2%2B-c0d3c19-NOGIL) | mpage/gh_115999_tlbc_call_ | c0d3c19 (NOGIL) | 1.224x ↓<br>[📄](results/bm-20241204-3.14.0a2%2B-c0d3c19-NOGIL/bm-20241204-vultr-x86_64-mpage-gh_115999_tlbc_call_-3.14.0a2%2B-c0d3c19-vs-3.12.6.md)[📈](results/bm-20241204-3.14.0a2%2B-c0d3c19-NOGIL/bm-20241204-vultr-x86_64-mpage-gh_115999_tlbc_call_-3.14.0a2%2B-c0d3c19-vs-3.12.6.svg) | 1.249x ↓<br>[📄](results/bm-20241204-3.14.0a2%2B-c0d3c19-NOGIL/bm-20241204-vultr-x86_64-mpage-gh_115999_tlbc_call_-3.14.0a2%2B-c0d3c19-vs-3.13.0rc2.md)[📈](results/bm-20241204-3.14.0a2%2B-c0d3c19-NOGIL/bm-20241204-vultr-x86_64-mpage-gh_115999_tlbc_call_-3.14.0a2%2B-c0d3c19-vs-3.13.0rc2.svg) | 1.010x ↑<br>[📄](results/bm-20241204-3.14.0a2%2B-c0d3c19-NOGIL/bm-20241204-vultr-x86_64-mpage-gh_115999_tlbc_call_-3.14.0a2%2B-c0d3c19-vs-base.md)[📈](results/bm-20241204-3.14.0a2%2B-c0d3c19-NOGIL/bm-20241204-vultr-x86_64-mpage-gh_115999_tlbc_call_-3.14.0a2%2B-c0d3c19-vs-base.svg)[🧠](results/bm-20241204-3.14.0a2%2B-c0d3c19-NOGIL/bm-20241204-vultr-x86_64-mpage-gh_115999_tlbc_call_-3.14.0a2%2B-c0d3c19-vs-base-mem.svg) |
| [2024-12-04](results/bm-20241204-3.14.0a2%2B-c0d3c19) | mpage/gh_115999_tlbc_call_ | c0d3c19 | 1.071x ↑<br>[📄](results/bm-20241204-3.14.0a2%2B-c0d3c19/bm-20241204-vultr-x86_64-mpage-gh_115999_tlbc_call_-3.14.0a2%2B-c0d3c19-vs-3.12.6.md)[📈](results/bm-20241204-3.14.0a2%2B-c0d3c19/bm-20241204-vultr-x86_64-mpage-gh_115999_tlbc_call_-3.14.0a2%2B-c0d3c19-vs-3.12.6.svg) | 1.033x ↑<br>[📄](results/bm-20241204-3.14.0a2%2B-c0d3c19/bm-20241204-vultr-x86_64-mpage-gh_115999_tlbc_call_-3.14.0a2%2B-c0d3c19-vs-3.13.0rc2.md)[📈](results/bm-20241204-3.14.0a2%2B-c0d3c19/bm-20241204-vultr-x86_64-mpage-gh_115999_tlbc_call_-3.14.0a2%2B-c0d3c19-vs-3.13.0rc2.svg) | 1.002x ↑<br>[📄](results/bm-20241204-3.14.0a2%2B-c0d3c19/bm-20241204-vultr-x86_64-mpage-gh_115999_tlbc_call_-3.14.0a2%2B-c0d3c19-vs-base.md)[📈](results/bm-20241204-3.14.0a2%2B-c0d3c19/bm-20241204-vultr-x86_64-mpage-gh_115999_tlbc_call_-3.14.0a2%2B-c0d3c19-vs-base.svg)[🧠](results/bm-20241204-3.14.0a2%2B-c0d3c19/bm-20241204-vultr-x86_64-mpage-gh_115999_tlbc_call_-3.14.0a2%2B-c0d3c19-vs-base-mem.svg) |
| [2024-12-04](results/bm-20241204-3.14.0a2%2B-51cfa56-NOGIL) | python/51cfa569e379f84b3418 | 51cfa56 (NOGIL) | 1.232x ↓<br>[📄](results/bm-20241204-3.14.0a2%2B-51cfa56-NOGIL/bm-20241204-vultr-x86_64-python-51cfa569e379f84b3418-3.14.0a2%2B-51cfa56-vs-3.12.6.md)[📈](results/bm-20241204-3.14.0a2%2B-51cfa56-NOGIL/bm-20241204-vultr-x86_64-python-51cfa569e379f84b3418-3.14.0a2%2B-51cfa56-vs-3.12.6.svg) | 1.257x ↓<br>[📄](results/bm-20241204-3.14.0a2%2B-51cfa56-NOGIL/bm-20241204-vultr-x86_64-python-51cfa569e379f84b3418-3.14.0a2%2B-51cfa56-vs-3.13.0rc2.md)[📈](results/bm-20241204-3.14.0a2%2B-51cfa56-NOGIL/bm-20241204-vultr-x86_64-python-51cfa569e379f84b3418-3.14.0a2%2B-51cfa56-vs-3.13.0rc2.svg) | 1.009x ↓<br>[📄](results/bm-20241204-3.14.0a2%2B-51cfa56-NOGIL/bm-20241204-vultr-x86_64-python-51cfa569e379f84b3418-3.14.0a2%2B-51cfa56-vs-base.md)[📈](results/bm-20241204-3.14.0a2%2B-51cfa56-NOGIL/bm-20241204-vultr-x86_64-python-51cfa569e379f84b3418-3.14.0a2%2B-51cfa56-vs-base.svg)[🧠](results/bm-20241204-3.14.0a2%2B-51cfa56-NOGIL/bm-20241204-vultr-x86_64-python-51cfa569e379f84b3418-3.14.0a2%2B-51cfa56-vs-base-mem.svg) |
| [2024-12-04](results/bm-20241204-3.14.0a2%2B-51cfa56) | python/51cfa569e379f84b3418 | 51cfa56 | 1.069x ↑<br>[📄](results/bm-20241204-3.14.0a2%2B-51cfa56/bm-20241204-vultr-x86_64-python-51cfa569e379f84b3418-3.14.0a2%2B-51cfa56-vs-3.12.6.md)[📈](results/bm-20241204-3.14.0a2%2B-51cfa56/bm-20241204-vultr-x86_64-python-51cfa569e379f84b3418-3.14.0a2%2B-51cfa56-vs-3.12.6.svg) | 1.031x ↑<br>[📄](results/bm-20241204-3.14.0a2%2B-51cfa56/bm-20241204-vultr-x86_64-python-51cfa569e379f84b3418-3.14.0a2%2B-51cfa56-vs-3.13.0rc2.md)[📈](results/bm-20241204-3.14.0a2%2B-51cfa56/bm-20241204-vultr-x86_64-python-51cfa569e379f84b3418-3.14.0a2%2B-51cfa56-vs-3.13.0rc2.svg) |  |
| [2024-12-04](results/bm-20241204-3.14.0a2%2B-0f5d11c) | mpage/measure_gc_changes | 0f5d11c | 1.040x ↑<br>[📄](results/bm-20241204-3.14.0a2%2B-0f5d11c/bm-20241204-vultr-x86_64-mpage-measure_gc_changes-3.14.0a2%2B-0f5d11c-vs-3.12.6.md)[📈](results/bm-20241204-3.14.0a2%2B-0f5d11c/bm-20241204-vultr-x86_64-mpage-measure_gc_changes-3.14.0a2%2B-0f5d11c-vs-3.12.6.svg) | 1.002x ↑<br>[📄](results/bm-20241204-3.14.0a2%2B-0f5d11c/bm-20241204-vultr-x86_64-mpage-measure_gc_changes-3.14.0a2%2B-0f5d11c-vs-3.13.0rc2.md)[📈](results/bm-20241204-3.14.0a2%2B-0f5d11c/bm-20241204-vultr-x86_64-mpage-measure_gc_changes-3.14.0a2%2B-0f5d11c-vs-3.13.0rc2.svg) | 1.019x ↓<br>[📄](results/bm-20241204-3.14.0a2%2B-0f5d11c/bm-20241204-vultr-x86_64-mpage-measure_gc_changes-3.14.0a2%2B-0f5d11c-vs-base.md)[📈](results/bm-20241204-3.14.0a2%2B-0f5d11c/bm-20241204-vultr-x86_64-mpage-measure_gc_changes-3.14.0a2%2B-0f5d11c-vs-base.svg)[🧠](results/bm-20241204-3.14.0a2%2B-0f5d11c/bm-20241204-vultr-x86_64-mpage-measure_gc_changes-3.14.0a2%2B-0f5d11c-vs-base-mem.svg) |
| [2024-12-04](results/bm-20241204-3.14.0a2%2B-0f5d11c-NOGIL) | mpage/measure_gc_changes | 0f5d11c (NOGIL) | 1.255x ↓<br>[📄](results/bm-20241204-3.14.0a2%2B-0f5d11c-NOGIL/bm-20241204-vultr-x86_64-mpage-measure_gc_changes-3.14.0a2%2B-0f5d11c-vs-3.12.6.md)[📈](results/bm-20241204-3.14.0a2%2B-0f5d11c-NOGIL/bm-20241204-vultr-x86_64-mpage-measure_gc_changes-3.14.0a2%2B-0f5d11c-vs-3.12.6.svg) | 1.279x ↓<br>[📄](results/bm-20241204-3.14.0a2%2B-0f5d11c-NOGIL/bm-20241204-vultr-x86_64-mpage-measure_gc_changes-3.14.0a2%2B-0f5d11c-vs-3.13.0rc2.md)[📈](results/bm-20241204-3.14.0a2%2B-0f5d11c-NOGIL/bm-20241204-vultr-x86_64-mpage-measure_gc_changes-3.14.0a2%2B-0f5d11c-vs-3.13.0rc2.svg) | 1.006x ↑<br>[📄](results/bm-20241204-3.14.0a2%2B-0f5d11c-NOGIL/bm-20241204-vultr-x86_64-mpage-measure_gc_changes-3.14.0a2%2B-0f5d11c-vs-base.md)[📈](results/bm-20241204-3.14.0a2%2B-0f5d11c-NOGIL/bm-20241204-vultr-x86_64-mpage-measure_gc_changes-3.14.0a2%2B-0f5d11c-vs-base.svg)[🧠](results/bm-20241204-3.14.0a2%2B-0f5d11c-NOGIL/bm-20241204-vultr-x86_64-mpage-measure_gc_changes-3.14.0a2%2B-0f5d11c-vs-base-mem.svg) |
| [2024-12-03](results/bm-20241203-3.14.0a2%2B-7f882c8) | python/7f882c88cfda48694797 | 7f882c8 | 1.058x ↑<br>[📄](results/bm-20241203-3.14.0a2%2B-7f882c8/bm-20241203-vultr-x86_64-python-7f882c88cfda48694797-3.14.0a2%2B-7f882c8-vs-3.12.6.md)[📈](results/bm-20241203-3.14.0a2%2B-7f882c8/bm-20241203-vultr-x86_64-python-7f882c88cfda48694797-3.14.0a2%2B-7f882c8-vs-3.12.6.svg) | 1.020x ↑<br>[📄](results/bm-20241203-3.14.0a2%2B-7f882c8/bm-20241203-vultr-x86_64-python-7f882c88cfda48694797-3.14.0a2%2B-7f882c8-vs-3.13.0rc2.md)[📈](results/bm-20241203-3.14.0a2%2B-7f882c8/bm-20241203-vultr-x86_64-python-7f882c88cfda48694797-3.14.0a2%2B-7f882c8-vs-3.13.0rc2.svg) |  |
| [2024-12-03](results/bm-20241203-3.14.0a2%2B-7f882c8-NOGIL) | python/7f882c88cfda48694797 | 7f882c8 (NOGIL) | 1.232x ↓<br>[📄](results/bm-20241203-3.14.0a2%2B-7f882c8-NOGIL/bm-20241203-vultr-x86_64-python-7f882c88cfda48694797-3.14.0a2%2B-7f882c8-vs-3.12.6.md)[📈](results/bm-20241203-3.14.0a2%2B-7f882c8-NOGIL/bm-20241203-vultr-x86_64-python-7f882c88cfda48694797-3.14.0a2%2B-7f882c8-vs-3.12.6.svg) | 1.256x ↓<br>[📄](results/bm-20241203-3.14.0a2%2B-7f882c8-NOGIL/bm-20241203-vultr-x86_64-python-7f882c88cfda48694797-3.14.0a2%2B-7f882c8-vs-3.13.0rc2.md)[📈](results/bm-20241203-3.14.0a2%2B-7f882c8-NOGIL/bm-20241203-vultr-x86_64-python-7f882c88cfda48694797-3.14.0a2%2B-7f882c8-vs-3.13.0rc2.svg) | 1.268x ↓<br>[📄](results/bm-20241203-3.14.0a2%2B-7f882c8-NOGIL/bm-20241203-vultr-x86_64-python-7f882c88cfda48694797-3.14.0a2%2B-7f882c8-vs-base.md)[📈](results/bm-20241203-3.14.0a2%2B-7f882c8-NOGIL/bm-20241203-vultr-x86_64-python-7f882c88cfda48694797-3.14.0a2%2B-7f882c8-vs-base.svg)[🧠](results/bm-20241203-3.14.0a2%2B-7f882c8-NOGIL/bm-20241203-vultr-x86_64-python-7f882c88cfda48694797-3.14.0a2%2B-7f882c8-vs-base-mem.svg) |
| [2024-12-03](results/bm-20241203-3.14.0a2%2B-8ba9f5b) | mpage/8ba9f5bca9c0ce6130e1 | 8ba9f5b | 1.063x ↑<br>[📄](results/bm-20241203-3.14.0a2%2B-8ba9f5b/bm-20241203-vultr-x86_64-mpage-8ba9f5bca9c0ce6130e1-3.14.0a2%2B-8ba9f5b-vs-3.12.6.md)[📈](results/bm-20241203-3.14.0a2%2B-8ba9f5b/bm-20241203-vultr-x86_64-mpage-8ba9f5bca9c0ce6130e1-3.14.0a2%2B-8ba9f5b-vs-3.12.6.svg) | 1.025x ↑<br>[📄](results/bm-20241203-3.14.0a2%2B-8ba9f5b/bm-20241203-vultr-x86_64-mpage-8ba9f5bca9c0ce6130e1-3.14.0a2%2B-8ba9f5b-vs-3.13.0rc2.md)[📈](results/bm-20241203-3.14.0a2%2B-8ba9f5b/bm-20241203-vultr-x86_64-mpage-8ba9f5bca9c0ce6130e1-3.14.0a2%2B-8ba9f5b-vs-3.13.0rc2.svg) |  |
| [2024-12-03](results/bm-20241203-3.14.0a2%2B-8ba9f5b-NOGIL) | python/8ba9f5bca9c0ce6130e1 | 8ba9f5b (NOGIL) | 1.257x ↓<br>[📄](results/bm-20241203-3.14.0a2%2B-8ba9f5b-NOGIL/bm-20241203-vultr-x86_64-python-8ba9f5bca9c0ce6130e1-3.14.0a2%2B-8ba9f5b-vs-3.12.6.md)[📈](results/bm-20241203-3.14.0a2%2B-8ba9f5b-NOGIL/bm-20241203-vultr-x86_64-python-8ba9f5bca9c0ce6130e1-3.14.0a2%2B-8ba9f5b-vs-3.12.6.svg) | 1.282x ↓<br>[📄](results/bm-20241203-3.14.0a2%2B-8ba9f5b-NOGIL/bm-20241203-vultr-x86_64-python-8ba9f5bca9c0ce6130e1-3.14.0a2%2B-8ba9f5b-vs-3.13.0rc2.md)[📈](results/bm-20241203-3.14.0a2%2B-8ba9f5b-NOGIL/bm-20241203-vultr-x86_64-python-8ba9f5bca9c0ce6130e1-3.14.0a2%2B-8ba9f5b-vs-3.13.0rc2.svg) |  |
| [2024-12-03](results/bm-20241203-3.14.0a2%2B-4049072-NOGIL) | mpage/reapply_gc_changes | 4049072 (NOGIL) | 1.255x ↓<br>[📄](results/bm-20241203-3.14.0a2%2B-4049072-NOGIL/bm-20241203-vultr-x86_64-mpage-reapply_gc_changes-3.14.0a2%2B-4049072-vs-3.12.6.md)[📈](results/bm-20241203-3.14.0a2%2B-4049072-NOGIL/bm-20241203-vultr-x86_64-mpage-reapply_gc_changes-3.14.0a2%2B-4049072-vs-3.12.6.svg) | 1.279x ↓<br>[📄](results/bm-20241203-3.14.0a2%2B-4049072-NOGIL/bm-20241203-vultr-x86_64-mpage-reapply_gc_changes-3.14.0a2%2B-4049072-vs-3.13.0rc2.md)[📈](results/bm-20241203-3.14.0a2%2B-4049072-NOGIL/bm-20241203-vultr-x86_64-mpage-reapply_gc_changes-3.14.0a2%2B-4049072-vs-3.13.0rc2.svg) | 1.004x ↑<br>[📄](results/bm-20241203-3.14.0a2%2B-4049072-NOGIL/bm-20241203-vultr-x86_64-mpage-reapply_gc_changes-3.14.0a2%2B-4049072-vs-base.md)[📈](results/bm-20241203-3.14.0a2%2B-4049072-NOGIL/bm-20241203-vultr-x86_64-mpage-reapply_gc_changes-3.14.0a2%2B-4049072-vs-base.svg)[🧠](results/bm-20241203-3.14.0a2%2B-4049072-NOGIL/bm-20241203-vultr-x86_64-mpage-reapply_gc_changes-3.14.0a2%2B-4049072-vs-base-mem.svg) |
| [2024-12-03](results/bm-20241203-3.14.0a2%2B-3bfbf91-NOGIL) | mpage/gh_115999_load_attr | 3bfbf91 (NOGIL) | 1.219x ↓<br>[📄](results/bm-20241203-3.14.0a2%2B-3bfbf91-NOGIL/bm-20241203-vultr-x86_64-mpage-gh_115999_load_attr-3.14.0a2%2B-3bfbf91-vs-3.12.6.md)[📈](results/bm-20241203-3.14.0a2%2B-3bfbf91-NOGIL/bm-20241203-vultr-x86_64-mpage-gh_115999_load_attr-3.14.0a2%2B-3bfbf91-vs-3.12.6.svg) | 1.244x ↓<br>[📄](results/bm-20241203-3.14.0a2%2B-3bfbf91-NOGIL/bm-20241203-vultr-x86_64-mpage-gh_115999_load_attr-3.14.0a2%2B-3bfbf91-vs-3.13.0rc2.md)[📈](results/bm-20241203-3.14.0a2%2B-3bfbf91-NOGIL/bm-20241203-vultr-x86_64-mpage-gh_115999_load_attr-3.14.0a2%2B-3bfbf91-vs-3.13.0rc2.svg) | 1.015x ↑<br>[📄](results/bm-20241203-3.14.0a2%2B-3bfbf91-NOGIL/bm-20241203-vultr-x86_64-mpage-gh_115999_load_attr-3.14.0a2%2B-3bfbf91-vs-base.md)[📈](results/bm-20241203-3.14.0a2%2B-3bfbf91-NOGIL/bm-20241203-vultr-x86_64-mpage-gh_115999_load_attr-3.14.0a2%2B-3bfbf91-vs-base.svg)[🧠](results/bm-20241203-3.14.0a2%2B-3bfbf91-NOGIL/bm-20241203-vultr-x86_64-mpage-gh_115999_load_attr-3.14.0a2%2B-3bfbf91-vs-base-mem.svg) |
| [2024-12-03](results/bm-20241203-3.14.0a2%2B-dabcecf-NOGIL) | python/dabcecfd6dadb9430733 | dabcecf (NOGIL) | 1.231x ↓<br>[📄](results/bm-20241203-3.14.0a2%2B-dabcecf-NOGIL/bm-20241203-vultr-x86_64-python-dabcecfd6dadb9430733-3.14.0a2%2B-dabcecf-vs-3.12.6.md)[📈](results/bm-20241203-3.14.0a2%2B-dabcecf-NOGIL/bm-20241203-vultr-x86_64-python-dabcecfd6dadb9430733-3.14.0a2%2B-dabcecf-vs-3.12.6.svg) | 1.256x ↓<br>[📄](results/bm-20241203-3.14.0a2%2B-dabcecf-NOGIL/bm-20241203-vultr-x86_64-python-dabcecfd6dadb9430733-3.14.0a2%2B-dabcecf-vs-3.13.0rc2.md)[📈](results/bm-20241203-3.14.0a2%2B-dabcecf-NOGIL/bm-20241203-vultr-x86_64-python-dabcecfd6dadb9430733-3.14.0a2%2B-dabcecf-vs-3.13.0rc2.svg) |  |
| [2024-12-03](results/bm-20241203-3.14.0a2%2B-2923163-NOGIL) | mpage/revert_gc_changes | 2923163 (NOGIL) | 1.255x ↓<br>[📄](results/bm-20241203-3.14.0a2%2B-2923163-NOGIL/bm-20241203-vultr-x86_64-mpage-revert_gc_changes-3.14.0a2%2B-2923163-vs-3.12.6.md)[📈](results/bm-20241203-3.14.0a2%2B-2923163-NOGIL/bm-20241203-vultr-x86_64-mpage-revert_gc_changes-3.14.0a2%2B-2923163-vs-3.12.6.svg) | 1.279x ↓<br>[📄](results/bm-20241203-3.14.0a2%2B-2923163-NOGIL/bm-20241203-vultr-x86_64-mpage-revert_gc_changes-3.14.0a2%2B-2923163-vs-3.13.0rc2.md)[📈](results/bm-20241203-3.14.0a2%2B-2923163-NOGIL/bm-20241203-vultr-x86_64-mpage-revert_gc_changes-3.14.0a2%2B-2923163-vs-3.13.0rc2.svg) | 1.003x ↑<br>[📄](results/bm-20241203-3.14.0a2%2B-2923163-NOGIL/bm-20241203-vultr-x86_64-mpage-revert_gc_changes-3.14.0a2%2B-2923163-vs-base.md)[📈](results/bm-20241203-3.14.0a2%2B-2923163-NOGIL/bm-20241203-vultr-x86_64-mpage-revert_gc_changes-3.14.0a2%2B-2923163-vs-base.svg)[🧠](results/bm-20241203-3.14.0a2%2B-2923163-NOGIL/bm-20241203-vultr-x86_64-mpage-revert_gc_changes-3.14.0a2%2B-2923163-vs-base-mem.svg) |
| [2024-12-03](results/bm-20241203-3.14.0a2%2B-bfb0788) | python/bfb0788bfcaab7474c1b | bfb0788 | 1.059x ↑<br>[📄](results/bm-20241203-3.14.0a2%2B-bfb0788/bm-20241203-vultr-x86_64-python-bfb0788bfcaab7474c1b-3.14.0a2%2B-bfb0788-vs-3.12.6.md)[📈](results/bm-20241203-3.14.0a2%2B-bfb0788/bm-20241203-vultr-x86_64-python-bfb0788bfcaab7474c1b-3.14.0a2%2B-bfb0788-vs-3.12.6.svg) | 1.021x ↑<br>[📄](results/bm-20241203-3.14.0a2%2B-bfb0788/bm-20241203-vultr-x86_64-python-bfb0788bfcaab7474c1b-3.14.0a2%2B-bfb0788-vs-3.13.0rc2.md)[📈](results/bm-20241203-3.14.0a2%2B-bfb0788/bm-20241203-vultr-x86_64-python-bfb0788bfcaab7474c1b-3.14.0a2%2B-bfb0788-vs-3.13.0rc2.svg) |  |
| [2024-12-03](results/bm-20241203-3.14.0a2%2B-bfb0788-NOGIL) | python/bfb0788bfcaab7474c1b | bfb0788 (NOGIL) | 1.259x ↓<br>[📄](results/bm-20241203-3.14.0a2%2B-bfb0788-NOGIL/bm-20241203-vultr-x86_64-python-bfb0788bfcaab7474c1b-3.14.0a2%2B-bfb0788-vs-3.12.6.md)[📈](results/bm-20241203-3.14.0a2%2B-bfb0788-NOGIL/bm-20241203-vultr-x86_64-python-bfb0788bfcaab7474c1b-3.14.0a2%2B-bfb0788-vs-3.12.6.svg) | 1.283x ↓<br>[📄](results/bm-20241203-3.14.0a2%2B-bfb0788-NOGIL/bm-20241203-vultr-x86_64-python-bfb0788bfcaab7474c1b-3.14.0a2%2B-bfb0788-vs-3.13.0rc2.md)[📈](results/bm-20241203-3.14.0a2%2B-bfb0788-NOGIL/bm-20241203-vultr-x86_64-python-bfb0788bfcaab7474c1b-3.14.0a2%2B-bfb0788-vs-3.13.0rc2.svg) | 1.295x ↓<br>[📄](results/bm-20241203-3.14.0a2%2B-bfb0788-NOGIL/bm-20241203-vultr-x86_64-python-bfb0788bfcaab7474c1b-3.14.0a2%2B-bfb0788-vs-base.md)[📈](results/bm-20241203-3.14.0a2%2B-bfb0788-NOGIL/bm-20241203-vultr-x86_64-python-bfb0788bfcaab7474c1b-3.14.0a2%2B-bfb0788-vs-base.svg)[🧠](results/bm-20241203-3.14.0a2%2B-bfb0788-NOGIL/bm-20241203-vultr-x86_64-python-bfb0788bfcaab7474c1b-3.14.0a2%2B-bfb0788-vs-base-mem.svg) |
| [2024-12-03](results/bm-20241203-3.14.0a2%2B-6c5cec5-NOGIL) | dpdani/gh_117657_tsan_pymem | 6c5cec5 (NOGIL) | 1.253x ↓<br>[📄](results/bm-20241203-3.14.0a2%2B-6c5cec5-NOGIL/bm-20241203-vultr-x86_64-dpdani-gh_117657_tsan_pymem-3.14.0a2%2B-6c5cec5-vs-3.12.6.md)[📈](results/bm-20241203-3.14.0a2%2B-6c5cec5-NOGIL/bm-20241203-vultr-x86_64-dpdani-gh_117657_tsan_pymem-3.14.0a2%2B-6c5cec5-vs-3.12.6.svg) | 1.278x ↓<br>[📄](results/bm-20241203-3.14.0a2%2B-6c5cec5-NOGIL/bm-20241203-vultr-x86_64-dpdani-gh_117657_tsan_pymem-3.14.0a2%2B-6c5cec5-vs-3.13.0rc2.md)[📈](results/bm-20241203-3.14.0a2%2B-6c5cec5-NOGIL/bm-20241203-vultr-x86_64-dpdani-gh_117657_tsan_pymem-3.14.0a2%2B-6c5cec5-vs-3.13.0rc2.svg) | 1.007x ↑<br>[📄](results/bm-20241203-3.14.0a2%2B-6c5cec5-NOGIL/bm-20241203-vultr-x86_64-dpdani-gh_117657_tsan_pymem-3.14.0a2%2B-6c5cec5-vs-base.md)[📈](results/bm-20241203-3.14.0a2%2B-6c5cec5-NOGIL/bm-20241203-vultr-x86_64-dpdani-gh_117657_tsan_pymem-3.14.0a2%2B-6c5cec5-vs-base.svg)[🧠](results/bm-20241203-3.14.0a2%2B-6c5cec5-NOGIL/bm-20241203-vultr-x86_64-dpdani-gh_117657_tsan_pymem-3.14.0a2%2B-6c5cec5-vs-base-mem.svg) |
| [2024-12-02](results/bm-20241202-3.14.0a2%2B-e517ccb-NOGIL) | nascheme/gh_115999_specialize | e517ccb (NOGIL) | 1.265x ↓<br>[📄](results/bm-20241202-3.14.0a2%2B-e517ccb-NOGIL/bm-20241202-vultr-x86_64-nascheme-gh_115999_specialize-3.14.0a2%2B-e517ccb-vs-3.12.6.md)[📈](results/bm-20241202-3.14.0a2%2B-e517ccb-NOGIL/bm-20241202-vultr-x86_64-nascheme-gh_115999_specialize-3.14.0a2%2B-e517ccb-vs-3.12.6.svg) | 1.290x ↓<br>[📄](results/bm-20241202-3.14.0a2%2B-e517ccb-NOGIL/bm-20241202-vultr-x86_64-nascheme-gh_115999_specialize-3.14.0a2%2B-e517ccb-vs-3.13.0rc2.md)[📈](results/bm-20241202-3.14.0a2%2B-e517ccb-NOGIL/bm-20241202-vultr-x86_64-nascheme-gh_115999_specialize-3.14.0a2%2B-e517ccb-vs-3.13.0rc2.svg) | 1.007x ↓<br>[📄](results/bm-20241202-3.14.0a2%2B-e517ccb-NOGIL/bm-20241202-vultr-x86_64-nascheme-gh_115999_specialize-3.14.0a2%2B-e517ccb-vs-base.md)[📈](results/bm-20241202-3.14.0a2%2B-e517ccb-NOGIL/bm-20241202-vultr-x86_64-nascheme-gh_115999_specialize-3.14.0a2%2B-e517ccb-vs-base.svg)[🧠](results/bm-20241202-3.14.0a2%2B-e517ccb-NOGIL/bm-20241202-vultr-x86_64-nascheme-gh_115999_specialize-3.14.0a2%2B-e517ccb-vs-base-mem.svg) |
| [2024-11-29](results/bm-20241129-3.14.0a2%2B-15d6506) | python/15d6506d175780bb29e5 | 15d6506 | 1.031x ↑<br>[📄](results/bm-20241129-3.14.0a2%2B-15d6506/bm-20241129-vultr-x86_64-python-15d6506d175780bb29e5-3.14.0a2%2B-15d6506-vs-3.12.6.md)[📈](results/bm-20241129-3.14.0a2%2B-15d6506/bm-20241129-vultr-x86_64-python-15d6506d175780bb29e5-3.14.0a2%2B-15d6506-vs-3.12.6.svg) | 1.007x ↓<br>[📄](results/bm-20241129-3.14.0a2%2B-15d6506/bm-20241129-vultr-x86_64-python-15d6506d175780bb29e5-3.14.0a2%2B-15d6506-vs-3.13.0rc2.md)[📈](results/bm-20241129-3.14.0a2%2B-15d6506/bm-20241129-vultr-x86_64-python-15d6506d175780bb29e5-3.14.0a2%2B-15d6506-vs-3.13.0rc2.svg) |  |
| [2024-11-29](results/bm-20241129-3.14.0a2%2B-15d6506-NOGIL) | python/15d6506d175780bb29e5 | 15d6506 (NOGIL) | 1.259x ↓<br>[📄](results/bm-20241129-3.14.0a2%2B-15d6506-NOGIL/bm-20241129-vultr-x86_64-python-15d6506d175780bb29e5-3.14.0a2%2B-15d6506-vs-3.12.6.md)[📈](results/bm-20241129-3.14.0a2%2B-15d6506-NOGIL/bm-20241129-vultr-x86_64-python-15d6506d175780bb29e5-3.14.0a2%2B-15d6506-vs-3.12.6.svg) | 1.284x ↓<br>[📄](results/bm-20241129-3.14.0a2%2B-15d6506-NOGIL/bm-20241129-vultr-x86_64-python-15d6506d175780bb29e5-3.14.0a2%2B-15d6506-vs-3.13.0rc2.md)[📈](results/bm-20241129-3.14.0a2%2B-15d6506-NOGIL/bm-20241129-vultr-x86_64-python-15d6506d175780bb29e5-3.14.0a2%2B-15d6506-vs-3.13.0rc2.svg) | 1.273x ↓<br>[📄](results/bm-20241129-3.14.0a2%2B-15d6506-NOGIL/bm-20241129-vultr-x86_64-python-15d6506d175780bb29e5-3.14.0a2%2B-15d6506-vs-base.md)[📈](results/bm-20241129-3.14.0a2%2B-15d6506-NOGIL/bm-20241129-vultr-x86_64-python-15d6506d175780bb29e5-3.14.0a2%2B-15d6506-vs-base.svg)[🧠](results/bm-20241129-3.14.0a2%2B-15d6506-NOGIL/bm-20241129-vultr-x86_64-python-15d6506d175780bb29e5-3.14.0a2%2B-15d6506-vs-base-mem.svg) |
| [2024-11-27](results/bm-20241127-3.14.0a2%2B-b09c4cf) | nascheme/gh_127271_cell_get_s | b09c4cf | 1.036x ↑<br>[📄](results/bm-20241127-3.14.0a2%2B-b09c4cf/bm-20241127-vultr-x86_64-nascheme-gh_127271_cell_get_s-3.14.0a2%2B-b09c4cf-vs-3.12.6.md)[📈](results/bm-20241127-3.14.0a2%2B-b09c4cf/bm-20241127-vultr-x86_64-nascheme-gh_127271_cell_get_s-3.14.0a2%2B-b09c4cf-vs-3.12.6.svg) | 1.002x ↓<br>[📄](results/bm-20241127-3.14.0a2%2B-b09c4cf/bm-20241127-vultr-x86_64-nascheme-gh_127271_cell_get_s-3.14.0a2%2B-b09c4cf-vs-3.13.0rc2.md)[📈](results/bm-20241127-3.14.0a2%2B-b09c4cf/bm-20241127-vultr-x86_64-nascheme-gh_127271_cell_get_s-3.14.0a2%2B-b09c4cf-vs-3.13.0rc2.svg) | 1.004x ↓<br>[📄](results/bm-20241127-3.14.0a2%2B-b09c4cf/bm-20241127-vultr-x86_64-nascheme-gh_127271_cell_get_s-3.14.0a2%2B-b09c4cf-vs-base.md)[📈](results/bm-20241127-3.14.0a2%2B-b09c4cf/bm-20241127-vultr-x86_64-nascheme-gh_127271_cell_get_s-3.14.0a2%2B-b09c4cf-vs-base.svg)[🧠](results/bm-20241127-3.14.0a2%2B-b09c4cf/bm-20241127-vultr-x86_64-nascheme-gh_127271_cell_get_s-3.14.0a2%2B-b09c4cf-vs-base-mem.svg) |
| [2024-11-26](results/bm-20241126-3.14.0a2%2B-6da9d25) | python/6da9d252ac39d5334245 | 6da9d25 | 1.040x ↑<br>[📄](results/bm-20241126-3.14.0a2%2B-6da9d25/bm-20241126-vultr-x86_64-python-6da9d252ac39d5334245-3.14.0a2%2B-6da9d25-vs-3.12.6.md)[📈](results/bm-20241126-3.14.0a2%2B-6da9d25/bm-20241126-vultr-x86_64-python-6da9d252ac39d5334245-3.14.0a2%2B-6da9d25-vs-3.12.6.svg) | 1.002x ↑<br>[📄](results/bm-20241126-3.14.0a2%2B-6da9d25/bm-20241126-vultr-x86_64-python-6da9d252ac39d5334245-3.14.0a2%2B-6da9d25-vs-3.13.0rc2.md)[📈](results/bm-20241126-3.14.0a2%2B-6da9d25/bm-20241126-vultr-x86_64-python-6da9d252ac39d5334245-3.14.0a2%2B-6da9d25-vs-3.13.0rc2.svg) |  |


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
