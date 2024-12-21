# Faster CPython Benchmark Infrastructure

🔒 [▶️ START A BENCHMARK RUN](../../actions/workflows/benchmark.yml)

## Results

Here are some recent and important revisions. 👉 [Complete list of results](RESULTS.md).

<!-- START table -->
[Most recent pystats on main (0ac40ac)](results/bm-20241214-3.14.0a2%2B-0ac40ac-PYTHON_UOPS/bm-20241214-vultr-x86_64-python-0ac40acec045c4ce780c-3.14.0a2%2B-0ac40ac-pystats.md)

## linux x86_64 (linux)
| date | fork/ref | hash/flags | vs. 3.12.6: | vs. 3.13.0rc2: | vs. base: |
| --- | --- | --- | ---: | ---: | ---: |
| [2024-12-19](results/bm-20241219-3.14.0a3%2B-39e69a7) | python/39e69a7cd54d44c9061d | 39e69a7 | 1.102x ↑<br>[📄](results/bm-20241219-3.14.0a3%2B-39e69a7/bm-20241219-linux-x86_64-python-39e69a7cd54d44c9061d-3.14.0a3%2B-39e69a7-vs-3.12.6.md)[📈](results/bm-20241219-3.14.0a3%2B-39e69a7/bm-20241219-linux-x86_64-python-39e69a7cd54d44c9061d-3.14.0a3%2B-39e69a7-vs-3.12.6.svg) | 1.058x ↑<br>[📄](results/bm-20241219-3.14.0a3%2B-39e69a7/bm-20241219-linux-x86_64-python-39e69a7cd54d44c9061d-3.14.0a3%2B-39e69a7-vs-3.13.0rc2.md)[📈](results/bm-20241219-3.14.0a3%2B-39e69a7/bm-20241219-linux-x86_64-python-39e69a7cd54d44c9061d-3.14.0a3%2B-39e69a7-vs-3.13.0rc2.svg) |  |
| [2024-12-19](results/bm-20241219-3.14.0a3%2B-39e69a7-NOGIL) | python/39e69a7cd54d44c9061d | 39e69a7 (NOGIL) | 1.143x ↓<br>[📄](results/bm-20241219-3.14.0a3%2B-39e69a7-NOGIL/bm-20241219-linux-x86_64-python-39e69a7cd54d44c9061d-3.14.0a3%2B-39e69a7-vs-3.12.6.md)[📈](results/bm-20241219-3.14.0a3%2B-39e69a7-NOGIL/bm-20241219-linux-x86_64-python-39e69a7cd54d44c9061d-3.14.0a3%2B-39e69a7-vs-3.12.6.svg) | 1.172x ↓<br>[📄](results/bm-20241219-3.14.0a3%2B-39e69a7-NOGIL/bm-20241219-linux-x86_64-python-39e69a7cd54d44c9061d-3.14.0a3%2B-39e69a7-vs-3.13.0rc2.md)[📈](results/bm-20241219-3.14.0a3%2B-39e69a7-NOGIL/bm-20241219-linux-x86_64-python-39e69a7cd54d44c9061d-3.14.0a3%2B-39e69a7-vs-3.13.0rc2.svg) | 1.216x ↓<br>[📄](results/bm-20241219-3.14.0a3%2B-39e69a7-NOGIL/bm-20241219-linux-x86_64-python-39e69a7cd54d44c9061d-3.14.0a3%2B-39e69a7-vs-base.md)[📈](results/bm-20241219-3.14.0a3%2B-39e69a7-NOGIL/bm-20241219-linux-x86_64-python-39e69a7cd54d44c9061d-3.14.0a3%2B-39e69a7-vs-base.svg)[🧠](results/bm-20241219-3.14.0a3%2B-39e69a7-NOGIL/bm-20241219-linux-x86_64-python-39e69a7cd54d44c9061d-3.14.0a3%2B-39e69a7-vs-base-mem.svg) |
| [2024-12-18](results/bm-20241218-3.14.0a3%2B-f802c8b-NOGIL) | python/f802c8bf872ab882d305 | f802c8b (NOGIL) | 1.181x ↓<br>[📄](results/bm-20241218-3.14.0a3%2B-f802c8b-NOGIL/bm-20241218-linux-x86_64-python-f802c8bf872ab882d305-3.14.0a3%2B-f802c8b-vs-3.12.6.md)[📈](results/bm-20241218-3.14.0a3%2B-f802c8b-NOGIL/bm-20241218-linux-x86_64-python-f802c8bf872ab882d305-3.14.0a3%2B-f802c8b-vs-3.12.6.svg) | 1.208x ↓<br>[📄](results/bm-20241218-3.14.0a3%2B-f802c8b-NOGIL/bm-20241218-linux-x86_64-python-f802c8bf872ab882d305-3.14.0a3%2B-f802c8b-vs-3.13.0rc2.md)[📈](results/bm-20241218-3.14.0a3%2B-f802c8b-NOGIL/bm-20241218-linux-x86_64-python-f802c8bf872ab882d305-3.14.0a3%2B-f802c8b-vs-3.13.0rc2.svg) | 1.251x ↓<br>[📄](results/bm-20241218-3.14.0a3%2B-f802c8b-NOGIL/bm-20241218-linux-x86_64-python-f802c8bf872ab882d305-3.14.0a3%2B-f802c8b-vs-base.md)[📈](results/bm-20241218-3.14.0a3%2B-f802c8b-NOGIL/bm-20241218-linux-x86_64-python-f802c8bf872ab882d305-3.14.0a3%2B-f802c8b-vs-base.svg)[🧠](results/bm-20241218-3.14.0a3%2B-f802c8b-NOGIL/bm-20241218-linux-x86_64-python-f802c8bf872ab882d305-3.14.0a3%2B-f802c8b-vs-base-mem.svg) |
| [2024-12-18](results/bm-20241218-3.14.0a3%2B-f802c8b) | python/f802c8bf872ab882d305 | f802c8b | 1.107x ↑<br>[📄](results/bm-20241218-3.14.0a3%2B-f802c8b/bm-20241218-linux-x86_64-python-f802c8bf872ab882d305-3.14.0a3%2B-f802c8b-vs-3.12.6.md)[📈](results/bm-20241218-3.14.0a3%2B-f802c8b/bm-20241218-linux-x86_64-python-f802c8bf872ab882d305-3.14.0a3%2B-f802c8b-vs-3.12.6.svg) | 1.064x ↑<br>[📄](results/bm-20241218-3.14.0a3%2B-f802c8b/bm-20241218-linux-x86_64-python-f802c8bf872ab882d305-3.14.0a3%2B-f802c8b-vs-3.13.0rc2.md)[📈](results/bm-20241218-3.14.0a3%2B-f802c8b/bm-20241218-linux-x86_64-python-f802c8bf872ab882d305-3.14.0a3%2B-f802c8b-vs-3.13.0rc2.svg) |  |
| [2024-12-18](results/bm-20241218-3.14.0a3%2B-b92f101-NOGIL) | python/b92f101d0f19a1df3205 | b92f101 (NOGIL) | 1.163x ↓<br>[📄](results/bm-20241218-3.14.0a3%2B-b92f101-NOGIL/bm-20241218-linux-x86_64-python-b92f101d0f19a1df3205-3.14.0a3%2B-b92f101-vs-3.12.6.md)[📈](results/bm-20241218-3.14.0a3%2B-b92f101-NOGIL/bm-20241218-linux-x86_64-python-b92f101d0f19a1df3205-3.14.0a3%2B-b92f101-vs-3.12.6.svg) | 1.192x ↓<br>[📄](results/bm-20241218-3.14.0a3%2B-b92f101-NOGIL/bm-20241218-linux-x86_64-python-b92f101d0f19a1df3205-3.14.0a3%2B-b92f101-vs-3.13.0rc2.md)[📈](results/bm-20241218-3.14.0a3%2B-b92f101-NOGIL/bm-20241218-linux-x86_64-python-b92f101d0f19a1df3205-3.14.0a3%2B-b92f101-vs-3.13.0rc2.svg) | 1.236x ↓<br>[📄](results/bm-20241218-3.14.0a3%2B-b92f101-NOGIL/bm-20241218-linux-x86_64-python-b92f101d0f19a1df3205-3.14.0a3%2B-b92f101-vs-base.md)[📈](results/bm-20241218-3.14.0a3%2B-b92f101-NOGIL/bm-20241218-linux-x86_64-python-b92f101d0f19a1df3205-3.14.0a3%2B-b92f101-vs-base.svg)[🧠](results/bm-20241218-3.14.0a3%2B-b92f101-NOGIL/bm-20241218-linux-x86_64-python-b92f101d0f19a1df3205-3.14.0a3%2B-b92f101-vs-base-mem.svg) |
| [2024-12-18](results/bm-20241218-3.14.0a3%2B-b92f101) | python/b92f101d0f19a1df3205 | b92f101 | 1.105x ↑<br>[📄](results/bm-20241218-3.14.0a3%2B-b92f101/bm-20241218-linux-x86_64-python-b92f101d0f19a1df3205-3.14.0a3%2B-b92f101-vs-3.12.6.md)[📈](results/bm-20241218-3.14.0a3%2B-b92f101/bm-20241218-linux-x86_64-python-b92f101d0f19a1df3205-3.14.0a3%2B-b92f101-vs-3.12.6.svg) | 1.064x ↑<br>[📄](results/bm-20241218-3.14.0a3%2B-b92f101/bm-20241218-linux-x86_64-python-b92f101d0f19a1df3205-3.14.0a3%2B-b92f101-vs-3.13.0rc2.md)[📈](results/bm-20241218-3.14.0a3%2B-b92f101/bm-20241218-linux-x86_64-python-b92f101d0f19a1df3205-3.14.0a3%2B-b92f101-vs-3.13.0rc2.svg) |  |

## linux x86_64 (vultr)
| date | fork/ref | hash/flags | vs. 3.12.6: | vs. 3.13.0rc2: | vs. base: |
| --- | --- | --- | ---: | ---: | ---: |
| [2024-12-20](results/bm-20241220-3.14.0a3%2B-d6d4c73-NOGIL) | mpage/gh_115999_load_attr_ | d6d4c73 (NOGIL) | 1.087x ↓<br>[📄](results/bm-20241220-3.14.0a3%2B-d6d4c73-NOGIL/bm-20241220-vultr-x86_64-mpage-gh_115999_load_attr_-3.14.0a3%2B-d6d4c73-vs-3.12.6.md)[📈](results/bm-20241220-3.14.0a3%2B-d6d4c73-NOGIL/bm-20241220-vultr-x86_64-mpage-gh_115999_load_attr_-3.14.0a3%2B-d6d4c73-vs-3.12.6.svg) | 1.116x ↓<br>[📄](results/bm-20241220-3.14.0a3%2B-d6d4c73-NOGIL/bm-20241220-vultr-x86_64-mpage-gh_115999_load_attr_-3.14.0a3%2B-d6d4c73-vs-3.13.0rc2.md)[📈](results/bm-20241220-3.14.0a3%2B-d6d4c73-NOGIL/bm-20241220-vultr-x86_64-mpage-gh_115999_load_attr_-3.14.0a3%2B-d6d4c73-vs-3.13.0rc2.svg) | 1.120x ↑<br>[📄](results/bm-20241220-3.14.0a3%2B-d6d4c73-NOGIL/bm-20241220-vultr-x86_64-mpage-gh_115999_load_attr_-3.14.0a3%2B-d6d4c73-vs-base.md)[📈](results/bm-20241220-3.14.0a3%2B-d6d4c73-NOGIL/bm-20241220-vultr-x86_64-mpage-gh_115999_load_attr_-3.14.0a3%2B-d6d4c73-vs-base.svg)[🧠](results/bm-20241220-3.14.0a3%2B-d6d4c73-NOGIL/bm-20241220-vultr-x86_64-mpage-gh_115999_load_attr_-3.14.0a3%2B-d6d4c73-vs-base-mem.svg) |
| [2024-12-20](results/bm-20241220-3.14.0a3%2B-ddb794a-NOGIL) | Yhg1s/optimise_recursive_c | ddb794a (NOGIL) | 1.185x ↓<br>[📄](results/bm-20241220-3.14.0a3%2B-ddb794a-NOGIL/bm-20241220-vultr-x86_64-Yhg1s-optimise_recursive_c-3.14.0a3%2B-ddb794a-vs-3.12.6.md)[📈](results/bm-20241220-3.14.0a3%2B-ddb794a-NOGIL/bm-20241220-vultr-x86_64-Yhg1s-optimise_recursive_c-3.14.0a3%2B-ddb794a-vs-3.12.6.svg) | 1.212x ↓<br>[📄](results/bm-20241220-3.14.0a3%2B-ddb794a-NOGIL/bm-20241220-vultr-x86_64-Yhg1s-optimise_recursive_c-3.14.0a3%2B-ddb794a-vs-3.13.0rc2.md)[📈](results/bm-20241220-3.14.0a3%2B-ddb794a-NOGIL/bm-20241220-vultr-x86_64-Yhg1s-optimise_recursive_c-3.14.0a3%2B-ddb794a-vs-3.13.0rc2.svg) | 1.003x ↑<br>[📄](results/bm-20241220-3.14.0a3%2B-ddb794a-NOGIL/bm-20241220-vultr-x86_64-Yhg1s-optimise_recursive_c-3.14.0a3%2B-ddb794a-vs-base.md)[📈](results/bm-20241220-3.14.0a3%2B-ddb794a-NOGIL/bm-20241220-vultr-x86_64-Yhg1s-optimise_recursive_c-3.14.0a3%2B-ddb794a-vs-base.svg)[🧠](results/bm-20241220-3.14.0a3%2B-ddb794a-NOGIL/bm-20241220-vultr-x86_64-Yhg1s-optimise_recursive_c-3.14.0a3%2B-ddb794a-vs-base-mem.svg) |
| [2024-12-20](results/bm-20241220-3.14.0a3%2B-78ffba4-NOGIL) | python/78ffba4221dcb2e39fd5 | 78ffba4 (NOGIL) | 1.188x ↓<br>[📄](results/bm-20241220-3.14.0a3%2B-78ffba4-NOGIL/bm-20241220-vultr-x86_64-python-78ffba4221dcb2e39fd5-3.14.0a3%2B-78ffba4-vs-3.12.6.md)[📈](results/bm-20241220-3.14.0a3%2B-78ffba4-NOGIL/bm-20241220-vultr-x86_64-python-78ffba4221dcb2e39fd5-3.14.0a3%2B-78ffba4-vs-3.12.6.svg) | 1.215x ↓<br>[📄](results/bm-20241220-3.14.0a3%2B-78ffba4-NOGIL/bm-20241220-vultr-x86_64-python-78ffba4221dcb2e39fd5-3.14.0a3%2B-78ffba4-vs-3.13.0rc2.md)[📈](results/bm-20241220-3.14.0a3%2B-78ffba4-NOGIL/bm-20241220-vultr-x86_64-python-78ffba4221dcb2e39fd5-3.14.0a3%2B-78ffba4-vs-3.13.0rc2.svg) |  |
| [2024-12-20](results/bm-20241220-3.14.0a3%2B-b868363) | mpage/gh_115999_load_attr_ | b868363 | 1.094x ↑<br>[📄](results/bm-20241220-3.14.0a3%2B-b868363/bm-20241220-vultr-x86_64-mpage-gh_115999_load_attr_-3.14.0a3%2B-b868363-vs-3.12.6.md)[📈](results/bm-20241220-3.14.0a3%2B-b868363/bm-20241220-vultr-x86_64-mpage-gh_115999_load_attr_-3.14.0a3%2B-b868363-vs-3.12.6.svg) | 1.055x ↑<br>[📄](results/bm-20241220-3.14.0a3%2B-b868363/bm-20241220-vultr-x86_64-mpage-gh_115999_load_attr_-3.14.0a3%2B-b868363-vs-3.13.0rc2.md)[📈](results/bm-20241220-3.14.0a3%2B-b868363/bm-20241220-vultr-x86_64-mpage-gh_115999_load_attr_-3.14.0a3%2B-b868363-vs-3.13.0rc2.svg) | 1.008x ↑<br>[📄](results/bm-20241220-3.14.0a3%2B-b868363/bm-20241220-vultr-x86_64-mpage-gh_115999_load_attr_-3.14.0a3%2B-b868363-vs-base.md)[📈](results/bm-20241220-3.14.0a3%2B-b868363/bm-20241220-vultr-x86_64-mpage-gh_115999_load_attr_-3.14.0a3%2B-b868363-vs-base.svg)[🧠](results/bm-20241220-3.14.0a3%2B-b868363/bm-20241220-vultr-x86_64-mpage-gh_115999_load_attr_-3.14.0a3%2B-b868363-vs-base-mem.svg) |
| [2024-12-20](results/bm-20241220-3.14.0a3%2B-1b787b3-NOGIL) | mpage/gh_115999_load_attr_ | 1b787b3 (NOGIL) | 1.086x ↓<br>[📄](results/bm-20241220-3.14.0a3%2B-1b787b3-NOGIL/bm-20241220-vultr-x86_64-mpage-gh_115999_load_attr_-3.14.0a3%2B-1b787b3-vs-3.12.6.md)[📈](results/bm-20241220-3.14.0a3%2B-1b787b3-NOGIL/bm-20241220-vultr-x86_64-mpage-gh_115999_load_attr_-3.14.0a3%2B-1b787b3-vs-3.12.6.svg) | 1.115x ↓<br>[📄](results/bm-20241220-3.14.0a3%2B-1b787b3-NOGIL/bm-20241220-vultr-x86_64-mpage-gh_115999_load_attr_-3.14.0a3%2B-1b787b3-vs-3.13.0rc2.md)[📈](results/bm-20241220-3.14.0a3%2B-1b787b3-NOGIL/bm-20241220-vultr-x86_64-mpage-gh_115999_load_attr_-3.14.0a3%2B-1b787b3-vs-3.13.0rc2.svg) | 1.122x ↑<br>[📄](results/bm-20241220-3.14.0a3%2B-1b787b3-NOGIL/bm-20241220-vultr-x86_64-mpage-gh_115999_load_attr_-3.14.0a3%2B-1b787b3-vs-base.md)[📈](results/bm-20241220-3.14.0a3%2B-1b787b3-NOGIL/bm-20241220-vultr-x86_64-mpage-gh_115999_load_attr_-3.14.0a3%2B-1b787b3-vs-base.svg)[🧠](results/bm-20241220-3.14.0a3%2B-1b787b3-NOGIL/bm-20241220-vultr-x86_64-mpage-gh_115999_load_attr_-3.14.0a3%2B-1b787b3-vs-base-mem.svg) |
| [2024-12-19](results/bm-20241219-3.14.0a3%2B-3876bc7-NOGIL) | mpage/gh_115999_load_attr_ | 3876bc7 (NOGIL) | 1.091x ↓<br>[📄](results/bm-20241219-3.14.0a3%2B-3876bc7-NOGIL/bm-20241219-vultr-x86_64-mpage-gh_115999_load_attr_-3.14.0a3%2B-3876bc7-vs-3.12.6.md)[📈](results/bm-20241219-3.14.0a3%2B-3876bc7-NOGIL/bm-20241219-vultr-x86_64-mpage-gh_115999_load_attr_-3.14.0a3%2B-3876bc7-vs-3.12.6.svg) | 1.120x ↓<br>[📄](results/bm-20241219-3.14.0a3%2B-3876bc7-NOGIL/bm-20241219-vultr-x86_64-mpage-gh_115999_load_attr_-3.14.0a3%2B-3876bc7-vs-3.13.0rc2.md)[📈](results/bm-20241219-3.14.0a3%2B-3876bc7-NOGIL/bm-20241219-vultr-x86_64-mpage-gh_115999_load_attr_-3.14.0a3%2B-3876bc7-vs-3.13.0rc2.svg) | 1.116x ↑<br>[📄](results/bm-20241219-3.14.0a3%2B-3876bc7-NOGIL/bm-20241219-vultr-x86_64-mpage-gh_115999_load_attr_-3.14.0a3%2B-3876bc7-vs-base.md)[📈](results/bm-20241219-3.14.0a3%2B-3876bc7-NOGIL/bm-20241219-vultr-x86_64-mpage-gh_115999_load_attr_-3.14.0a3%2B-3876bc7-vs-base.svg)[🧠](results/bm-20241219-3.14.0a3%2B-3876bc7-NOGIL/bm-20241219-vultr-x86_64-mpage-gh_115999_load_attr_-3.14.0a3%2B-3876bc7-vs-base-mem.svg) |
| [2024-12-19](results/bm-20241219-3.14.0a3%2B-3876bc7) | mpage/gh_115999_load_attr_ | 3876bc7 | 1.094x ↑<br>[📄](results/bm-20241219-3.14.0a3%2B-3876bc7/bm-20241219-vultr-x86_64-mpage-gh_115999_load_attr_-3.14.0a3%2B-3876bc7-vs-3.12.6.md)[📈](results/bm-20241219-3.14.0a3%2B-3876bc7/bm-20241219-vultr-x86_64-mpage-gh_115999_load_attr_-3.14.0a3%2B-3876bc7-vs-3.12.6.svg) | 1.055x ↑<br>[📄](results/bm-20241219-3.14.0a3%2B-3876bc7/bm-20241219-vultr-x86_64-mpage-gh_115999_load_attr_-3.14.0a3%2B-3876bc7-vs-3.13.0rc2.md)[📈](results/bm-20241219-3.14.0a3%2B-3876bc7/bm-20241219-vultr-x86_64-mpage-gh_115999_load_attr_-3.14.0a3%2B-3876bc7-vs-3.13.0rc2.svg) | 1.008x ↑<br>[📄](results/bm-20241219-3.14.0a3%2B-3876bc7/bm-20241219-vultr-x86_64-mpage-gh_115999_load_attr_-3.14.0a3%2B-3876bc7-vs-base.md)[📈](results/bm-20241219-3.14.0a3%2B-3876bc7/bm-20241219-vultr-x86_64-mpage-gh_115999_load_attr_-3.14.0a3%2B-3876bc7-vs-base.svg)[🧠](results/bm-20241219-3.14.0a3%2B-3876bc7/bm-20241219-vultr-x86_64-mpage-gh_115999_load_attr_-3.14.0a3%2B-3876bc7-vs-base-mem.svg) |
| [2024-12-19](results/bm-20241219-3.14.0a3%2B-39e69a7) | python/39e69a7cd54d44c9061d | 39e69a7 | 1.084x ↑<br>[📄](results/bm-20241219-3.14.0a3%2B-39e69a7/bm-20241219-vultr-x86_64-python-39e69a7cd54d44c9061d-3.14.0a3%2B-39e69a7-vs-3.12.6.md)[📈](results/bm-20241219-3.14.0a3%2B-39e69a7/bm-20241219-vultr-x86_64-python-39e69a7cd54d44c9061d-3.14.0a3%2B-39e69a7-vs-3.12.6.svg) | 1.046x ↑<br>[📄](results/bm-20241219-3.14.0a3%2B-39e69a7/bm-20241219-vultr-x86_64-python-39e69a7cd54d44c9061d-3.14.0a3%2B-39e69a7-vs-3.13.0rc2.md)[📈](results/bm-20241219-3.14.0a3%2B-39e69a7/bm-20241219-vultr-x86_64-python-39e69a7cd54d44c9061d-3.14.0a3%2B-39e69a7-vs-3.13.0rc2.svg) |  |
| [2024-12-19](results/bm-20241219-3.14.0a3%2B-39e69a7-NOGIL) | python/39e69a7cd54d44c9061d | 39e69a7 (NOGIL) | 1.189x ↓<br>[📄](results/bm-20241219-3.14.0a3%2B-39e69a7-NOGIL/bm-20241219-vultr-x86_64-python-39e69a7cd54d44c9061d-3.14.0a3%2B-39e69a7-vs-3.12.6.md)[📈](results/bm-20241219-3.14.0a3%2B-39e69a7-NOGIL/bm-20241219-vultr-x86_64-python-39e69a7cd54d44c9061d-3.14.0a3%2B-39e69a7-vs-3.12.6.svg) | 1.215x ↓<br>[📄](results/bm-20241219-3.14.0a3%2B-39e69a7-NOGIL/bm-20241219-vultr-x86_64-python-39e69a7cd54d44c9061d-3.14.0a3%2B-39e69a7-vs-3.13.0rc2.md)[📈](results/bm-20241219-3.14.0a3%2B-39e69a7-NOGIL/bm-20241219-vultr-x86_64-python-39e69a7cd54d44c9061d-3.14.0a3%2B-39e69a7-vs-3.13.0rc2.svg) | 1.246x ↓<br>[📄](results/bm-20241219-3.14.0a3%2B-39e69a7-NOGIL/bm-20241219-vultr-x86_64-python-39e69a7cd54d44c9061d-3.14.0a3%2B-39e69a7-vs-base.md)[📈](results/bm-20241219-3.14.0a3%2B-39e69a7-NOGIL/bm-20241219-vultr-x86_64-python-39e69a7cd54d44c9061d-3.14.0a3%2B-39e69a7-vs-base.svg)[🧠](results/bm-20241219-3.14.0a3%2B-39e69a7-NOGIL/bm-20241219-vultr-x86_64-python-39e69a7cd54d44c9061d-3.14.0a3%2B-39e69a7-vs-base-mem.svg) |
| [2024-12-18](results/bm-20241218-3.14.0a3%2B-f802c8b-NOGIL) | python/f802c8bf872ab882d305 | f802c8b (NOGIL) | 1.218x ↓<br>[📄](results/bm-20241218-3.14.0a3%2B-f802c8b-NOGIL/bm-20241218-vultr-x86_64-python-f802c8bf872ab882d305-3.14.0a3%2B-f802c8b-vs-3.12.6.md)[📈](results/bm-20241218-3.14.0a3%2B-f802c8b-NOGIL/bm-20241218-vultr-x86_64-python-f802c8bf872ab882d305-3.14.0a3%2B-f802c8b-vs-3.12.6.svg) | 1.243x ↓<br>[📄](results/bm-20241218-3.14.0a3%2B-f802c8b-NOGIL/bm-20241218-vultr-x86_64-python-f802c8bf872ab882d305-3.14.0a3%2B-f802c8b-vs-3.13.0rc2.md)[📈](results/bm-20241218-3.14.0a3%2B-f802c8b-NOGIL/bm-20241218-vultr-x86_64-python-f802c8bf872ab882d305-3.14.0a3%2B-f802c8b-vs-3.13.0rc2.svg) | 1.266x ↓<br>[📄](results/bm-20241218-3.14.0a3%2B-f802c8b-NOGIL/bm-20241218-vultr-x86_64-python-f802c8bf872ab882d305-3.14.0a3%2B-f802c8b-vs-base.md)[📈](results/bm-20241218-3.14.0a3%2B-f802c8b-NOGIL/bm-20241218-vultr-x86_64-python-f802c8bf872ab882d305-3.14.0a3%2B-f802c8b-vs-base.svg)[🧠](results/bm-20241218-3.14.0a3%2B-f802c8b-NOGIL/bm-20241218-vultr-x86_64-python-f802c8bf872ab882d305-3.14.0a3%2B-f802c8b-vs-base-mem.svg) |
| [2024-12-18](results/bm-20241218-3.14.0a3%2B-f802c8b) | python/f802c8bf872ab882d305 | f802c8b | 1.076x ↑<br>[📄](results/bm-20241218-3.14.0a3%2B-f802c8b/bm-20241218-vultr-x86_64-python-f802c8bf872ab882d305-3.14.0a3%2B-f802c8b-vs-3.12.6.md)[📈](results/bm-20241218-3.14.0a3%2B-f802c8b/bm-20241218-vultr-x86_64-python-f802c8bf872ab882d305-3.14.0a3%2B-f802c8b-vs-3.12.6.svg) | 1.037x ↑<br>[📄](results/bm-20241218-3.14.0a3%2B-f802c8b/bm-20241218-vultr-x86_64-python-f802c8bf872ab882d305-3.14.0a3%2B-f802c8b-vs-3.13.0rc2.md)[📈](results/bm-20241218-3.14.0a3%2B-f802c8b/bm-20241218-vultr-x86_64-python-f802c8bf872ab882d305-3.14.0a3%2B-f802c8b-vs-3.13.0rc2.svg) |  |
| [2024-12-18](results/bm-20241218-3.14.0a3%2B-9015a3f) | nascheme/gh_115999_specialize | 9015a3f | 1.082x ↑<br>[📄](results/bm-20241218-3.14.0a3%2B-9015a3f/bm-20241218-vultr-x86_64-nascheme-gh_115999_specialize-3.14.0a3%2B-9015a3f-vs-3.12.6.md)[📈](results/bm-20241218-3.14.0a3%2B-9015a3f/bm-20241218-vultr-x86_64-nascheme-gh_115999_specialize-3.14.0a3%2B-9015a3f-vs-3.12.6.svg) | 1.043x ↑<br>[📄](results/bm-20241218-3.14.0a3%2B-9015a3f/bm-20241218-vultr-x86_64-nascheme-gh_115999_specialize-3.14.0a3%2B-9015a3f-vs-3.13.0rc2.md)[📈](results/bm-20241218-3.14.0a3%2B-9015a3f/bm-20241218-vultr-x86_64-nascheme-gh_115999_specialize-3.14.0a3%2B-9015a3f-vs-3.13.0rc2.svg) | 1.000x ↓<br>[📄](results/bm-20241218-3.14.0a3%2B-9015a3f/bm-20241218-vultr-x86_64-nascheme-gh_115999_specialize-3.14.0a3%2B-9015a3f-vs-base.md)[📈](results/bm-20241218-3.14.0a3%2B-9015a3f/bm-20241218-vultr-x86_64-nascheme-gh_115999_specialize-3.14.0a3%2B-9015a3f-vs-base.svg)[🧠](results/bm-20241218-3.14.0a3%2B-9015a3f/bm-20241218-vultr-x86_64-nascheme-gh_115999_specialize-3.14.0a3%2B-9015a3f-vs-base-mem.svg) |
| [2024-12-18](results/bm-20241218-3.14.0a3%2B-9015a3f-NOGIL) | nascheme/gh_115999_specialize | 9015a3f (NOGIL) | 1.192x ↓<br>[📄](results/bm-20241218-3.14.0a3%2B-9015a3f-NOGIL/bm-20241218-vultr-x86_64-nascheme-gh_115999_specialize-3.14.0a3%2B-9015a3f-vs-3.12.6.md)[📈](results/bm-20241218-3.14.0a3%2B-9015a3f-NOGIL/bm-20241218-vultr-x86_64-nascheme-gh_115999_specialize-3.14.0a3%2B-9015a3f-vs-3.12.6.svg) | 1.218x ↓<br>[📄](results/bm-20241218-3.14.0a3%2B-9015a3f-NOGIL/bm-20241218-vultr-x86_64-nascheme-gh_115999_specialize-3.14.0a3%2B-9015a3f-vs-3.13.0rc2.md)[📈](results/bm-20241218-3.14.0a3%2B-9015a3f-NOGIL/bm-20241218-vultr-x86_64-nascheme-gh_115999_specialize-3.14.0a3%2B-9015a3f-vs-3.13.0rc2.svg) | 1.023x ↑<br>[📄](results/bm-20241218-3.14.0a3%2B-9015a3f-NOGIL/bm-20241218-vultr-x86_64-nascheme-gh_115999_specialize-3.14.0a3%2B-9015a3f-vs-base.md)[📈](results/bm-20241218-3.14.0a3%2B-9015a3f-NOGIL/bm-20241218-vultr-x86_64-nascheme-gh_115999_specialize-3.14.0a3%2B-9015a3f-vs-base.svg)[🧠](results/bm-20241218-3.14.0a3%2B-9015a3f-NOGIL/bm-20241218-vultr-x86_64-nascheme-gh_115999_specialize-3.14.0a3%2B-9015a3f-vs-base-mem.svg) |
| [2024-12-18](results/bm-20241218-3.14.0a3%2B-b92f101-NOGIL) | python/b92f101d0f19a1df3205 | b92f101 (NOGIL) | 1.214x ↓<br>[📄](results/bm-20241218-3.14.0a3%2B-b92f101-NOGIL/bm-20241218-vultr-x86_64-python-b92f101d0f19a1df3205-3.14.0a3%2B-b92f101-vs-3.12.6.md)[📈](results/bm-20241218-3.14.0a3%2B-b92f101-NOGIL/bm-20241218-vultr-x86_64-python-b92f101d0f19a1df3205-3.14.0a3%2B-b92f101-vs-3.12.6.svg) | 1.240x ↓<br>[📄](results/bm-20241218-3.14.0a3%2B-b92f101-NOGIL/bm-20241218-vultr-x86_64-python-b92f101d0f19a1df3205-3.14.0a3%2B-b92f101-vs-3.13.0rc2.md)[📈](results/bm-20241218-3.14.0a3%2B-b92f101-NOGIL/bm-20241218-vultr-x86_64-python-b92f101d0f19a1df3205-3.14.0a3%2B-b92f101-vs-3.13.0rc2.svg) | 1.269x ↓<br>[📄](results/bm-20241218-3.14.0a3%2B-b92f101-NOGIL/bm-20241218-vultr-x86_64-python-b92f101d0f19a1df3205-3.14.0a3%2B-b92f101-vs-base.md)[📈](results/bm-20241218-3.14.0a3%2B-b92f101-NOGIL/bm-20241218-vultr-x86_64-python-b92f101d0f19a1df3205-3.14.0a3%2B-b92f101-vs-base.svg)[🧠](results/bm-20241218-3.14.0a3%2B-b92f101-NOGIL/bm-20241218-vultr-x86_64-python-b92f101d0f19a1df3205-3.14.0a3%2B-b92f101-vs-base-mem.svg) |
| [2024-12-18](results/bm-20241218-3.14.0a3%2B-b92f101) | python/b92f101d0f19a1df3205 | b92f101 | 1.085x ↑<br>[📄](results/bm-20241218-3.14.0a3%2B-b92f101/bm-20241218-vultr-x86_64-python-b92f101d0f19a1df3205-3.14.0a3%2B-b92f101-vs-3.12.6.md)[📈](results/bm-20241218-3.14.0a3%2B-b92f101/bm-20241218-vultr-x86_64-python-b92f101d0f19a1df3205-3.14.0a3%2B-b92f101-vs-3.12.6.svg) | 1.046x ↑<br>[📄](results/bm-20241218-3.14.0a3%2B-b92f101/bm-20241218-vultr-x86_64-python-b92f101d0f19a1df3205-3.14.0a3%2B-b92f101-vs-3.13.0rc2.md)[📈](results/bm-20241218-3.14.0a3%2B-b92f101/bm-20241218-vultr-x86_64-python-b92f101d0f19a1df3205-3.14.0a3%2B-b92f101-vs-3.13.0rc2.svg) |  |
| [2024-12-17](results/bm-20241217-3.14.0a3%2B-40f5577-NOGIL) | mpage/gh_115999_specialize | 40f5577 (NOGIL) | 1.189x ↓<br>[📄](results/bm-20241217-3.14.0a3%2B-40f5577-NOGIL/bm-20241217-vultr-x86_64-mpage-gh_115999_specialize-3.14.0a3%2B-40f5577-vs-3.12.6.md)[📈](results/bm-20241217-3.14.0a3%2B-40f5577-NOGIL/bm-20241217-vultr-x86_64-mpage-gh_115999_specialize-3.14.0a3%2B-40f5577-vs-3.12.6.svg) | 1.215x ↓<br>[📄](results/bm-20241217-3.14.0a3%2B-40f5577-NOGIL/bm-20241217-vultr-x86_64-mpage-gh_115999_specialize-3.14.0a3%2B-40f5577-vs-3.13.0rc2.md)[📈](results/bm-20241217-3.14.0a3%2B-40f5577-NOGIL/bm-20241217-vultr-x86_64-mpage-gh_115999_specialize-3.14.0a3%2B-40f5577-vs-3.13.0rc2.svg) | 1.027x ↑<br>[📄](results/bm-20241217-3.14.0a3%2B-40f5577-NOGIL/bm-20241217-vultr-x86_64-mpage-gh_115999_specialize-3.14.0a3%2B-40f5577-vs-base.md)[📈](results/bm-20241217-3.14.0a3%2B-40f5577-NOGIL/bm-20241217-vultr-x86_64-mpage-gh_115999_specialize-3.14.0a3%2B-40f5577-vs-base.svg)[🧠](results/bm-20241217-3.14.0a3%2B-40f5577-NOGIL/bm-20241217-vultr-x86_64-mpage-gh_115999_specialize-3.14.0a3%2B-40f5577-vs-base-mem.svg) |
| [2024-12-17](results/bm-20241217-3.14.0a3%2B-3291656-NOGIL) | python/329165639f9ac00ba64f | 3291656 (NOGIL) | 1.211x ↓<br>[📄](results/bm-20241217-3.14.0a3%2B-3291656-NOGIL/bm-20241217-vultr-x86_64-python-329165639f9ac00ba64f-3.14.0a3%2B-3291656-vs-3.12.6.md)[📈](results/bm-20241217-3.14.0a3%2B-3291656-NOGIL/bm-20241217-vultr-x86_64-python-329165639f9ac00ba64f-3.14.0a3%2B-3291656-vs-3.12.6.svg) | 1.236x ↓<br>[📄](results/bm-20241217-3.14.0a3%2B-3291656-NOGIL/bm-20241217-vultr-x86_64-python-329165639f9ac00ba64f-3.14.0a3%2B-3291656-vs-3.13.0rc2.md)[📈](results/bm-20241217-3.14.0a3%2B-3291656-NOGIL/bm-20241217-vultr-x86_64-python-329165639f9ac00ba64f-3.14.0a3%2B-3291656-vs-3.13.0rc2.svg) | 1.265x ↓<br>[📄](results/bm-20241217-3.14.0a3%2B-3291656-NOGIL/bm-20241217-vultr-x86_64-python-329165639f9ac00ba64f-3.14.0a3%2B-3291656-vs-base.md)[📈](results/bm-20241217-3.14.0a3%2B-3291656-NOGIL/bm-20241217-vultr-x86_64-python-329165639f9ac00ba64f-3.14.0a3%2B-3291656-vs-base.svg)[🧠](results/bm-20241217-3.14.0a3%2B-3291656-NOGIL/bm-20241217-vultr-x86_64-python-329165639f9ac00ba64f-3.14.0a3%2B-3291656-vs-base-mem.svg) |
| [2024-12-17](results/bm-20241217-3.14.0a3%2B-3291656) | python/329165639f9ac00ba64f | 3291656 | 1.082x ↑<br>[📄](results/bm-20241217-3.14.0a3%2B-3291656/bm-20241217-vultr-x86_64-python-329165639f9ac00ba64f-3.14.0a3%2B-3291656-vs-3.12.6.md)[📈](results/bm-20241217-3.14.0a3%2B-3291656/bm-20241217-vultr-x86_64-python-329165639f9ac00ba64f-3.14.0a3%2B-3291656-vs-3.12.6.svg) | 1.043x ↑<br>[📄](results/bm-20241217-3.14.0a3%2B-3291656/bm-20241217-vultr-x86_64-python-329165639f9ac00ba64f-3.14.0a3%2B-3291656-vs-3.13.0rc2.md)[📈](results/bm-20241217-3.14.0a3%2B-3291656/bm-20241217-vultr-x86_64-python-329165639f9ac00ba64f-3.14.0a3%2B-3291656-vs-3.13.0rc2.svg) |  |
| [2024-12-19](results/bm-20241219-3.14.0a2%2B-47b80b4-NOGIL) | corona10/gh_115999_BINARY_SUB | 47b80b4 (NOGIL) | 1.221x ↓<br>[📄](results/bm-20241219-3.14.0a2%2B-47b80b4-NOGIL/bm-20241219-vultr-x86_64-corona10-gh_115999_BINARY_SUB-3.14.0a2%2B-47b80b4-vs-3.12.6.md)[📈](results/bm-20241219-3.14.0a2%2B-47b80b4-NOGIL/bm-20241219-vultr-x86_64-corona10-gh_115999_BINARY_SUB-3.14.0a2%2B-47b80b4-vs-3.12.6.svg) | 1.246x ↓<br>[📄](results/bm-20241219-3.14.0a2%2B-47b80b4-NOGIL/bm-20241219-vultr-x86_64-corona10-gh_115999_BINARY_SUB-3.14.0a2%2B-47b80b4-vs-3.13.0rc2.md)[📈](results/bm-20241219-3.14.0a2%2B-47b80b4-NOGIL/bm-20241219-vultr-x86_64-corona10-gh_115999_BINARY_SUB-3.14.0a2%2B-47b80b4-vs-3.13.0rc2.svg) | 1.012x ↑<br>[📄](results/bm-20241219-3.14.0a2%2B-47b80b4-NOGIL/bm-20241219-vultr-x86_64-corona10-gh_115999_BINARY_SUB-3.14.0a2%2B-47b80b4-vs-base.md)[📈](results/bm-20241219-3.14.0a2%2B-47b80b4-NOGIL/bm-20241219-vultr-x86_64-corona10-gh_115999_BINARY_SUB-3.14.0a2%2B-47b80b4-vs-base.svg)[🧠](results/bm-20241219-3.14.0a2%2B-47b80b4-NOGIL/bm-20241219-vultr-x86_64-corona10-gh_115999_BINARY_SUB-3.14.0a2%2B-47b80b4-vs-base-mem.svg) |
| [2024-12-19](results/bm-20241219-3.14.0a2%2B-47b80b4) | corona10/gh_115999_BINARY_SUB | 47b80b4 | 1.062x ↑<br>[📄](results/bm-20241219-3.14.0a2%2B-47b80b4/bm-20241219-vultr-x86_64-corona10-gh_115999_BINARY_SUB-3.14.0a2%2B-47b80b4-vs-3.12.6.md)[📈](results/bm-20241219-3.14.0a2%2B-47b80b4/bm-20241219-vultr-x86_64-corona10-gh_115999_BINARY_SUB-3.14.0a2%2B-47b80b4-vs-3.12.6.svg) | 1.024x ↑<br>[📄](results/bm-20241219-3.14.0a2%2B-47b80b4/bm-20241219-vultr-x86_64-corona10-gh_115999_BINARY_SUB-3.14.0a2%2B-47b80b4-vs-3.13.0rc2.md)[📈](results/bm-20241219-3.14.0a2%2B-47b80b4/bm-20241219-vultr-x86_64-corona10-gh_115999_BINARY_SUB-3.14.0a2%2B-47b80b4-vs-3.13.0rc2.svg) | 1.003x ↓<br>[📄](results/bm-20241219-3.14.0a2%2B-47b80b4/bm-20241219-vultr-x86_64-corona10-gh_115999_BINARY_SUB-3.14.0a2%2B-47b80b4-vs-base.md)[📈](results/bm-20241219-3.14.0a2%2B-47b80b4/bm-20241219-vultr-x86_64-corona10-gh_115999_BINARY_SUB-3.14.0a2%2B-47b80b4-vs-base.svg)[🧠](results/bm-20241219-3.14.0a2%2B-47b80b4/bm-20241219-vultr-x86_64-corona10-gh_115999_BINARY_SUB-3.14.0a2%2B-47b80b4-vs-base-mem.svg) |
| [2024-12-18](results/bm-20241218-3.14.0a2%2B-6ef74ac) | corona10/gh_115999_BINARY_SUB | 6ef74ac | 1.060x ↑<br>[📄](results/bm-20241218-3.14.0a2%2B-6ef74ac/bm-20241218-vultr-x86_64-corona10-gh_115999_BINARY_SUB-3.14.0a2%2B-6ef74ac-vs-3.12.6.md)[📈](results/bm-20241218-3.14.0a2%2B-6ef74ac/bm-20241218-vultr-x86_64-corona10-gh_115999_BINARY_SUB-3.14.0a2%2B-6ef74ac-vs-3.12.6.svg) | 1.022x ↑<br>[📄](results/bm-20241218-3.14.0a2%2B-6ef74ac/bm-20241218-vultr-x86_64-corona10-gh_115999_BINARY_SUB-3.14.0a2%2B-6ef74ac-vs-3.13.0rc2.md)[📈](results/bm-20241218-3.14.0a2%2B-6ef74ac/bm-20241218-vultr-x86_64-corona10-gh_115999_BINARY_SUB-3.14.0a2%2B-6ef74ac-vs-3.13.0rc2.svg) | 1.005x ↓<br>[📄](results/bm-20241218-3.14.0a2%2B-6ef74ac/bm-20241218-vultr-x86_64-corona10-gh_115999_BINARY_SUB-3.14.0a2%2B-6ef74ac-vs-base.md)[📈](results/bm-20241218-3.14.0a2%2B-6ef74ac/bm-20241218-vultr-x86_64-corona10-gh_115999_BINARY_SUB-3.14.0a2%2B-6ef74ac-vs-base.svg)[🧠](results/bm-20241218-3.14.0a2%2B-6ef74ac/bm-20241218-vultr-x86_64-corona10-gh_115999_BINARY_SUB-3.14.0a2%2B-6ef74ac-vs-base-mem.svg) |
| [2024-12-18](results/bm-20241218-3.14.0a2%2B-6ef74ac-NOGIL) | corona10/gh_115999_BINARY_SUB | 6ef74ac (NOGIL) | 1.222x ↓<br>[📄](results/bm-20241218-3.14.0a2%2B-6ef74ac-NOGIL/bm-20241218-vultr-x86_64-corona10-gh_115999_BINARY_SUB-3.14.0a2%2B-6ef74ac-vs-3.12.6.md)[📈](results/bm-20241218-3.14.0a2%2B-6ef74ac-NOGIL/bm-20241218-vultr-x86_64-corona10-gh_115999_BINARY_SUB-3.14.0a2%2B-6ef74ac-vs-3.12.6.svg) | 1.247x ↓<br>[📄](results/bm-20241218-3.14.0a2%2B-6ef74ac-NOGIL/bm-20241218-vultr-x86_64-corona10-gh_115999_BINARY_SUB-3.14.0a2%2B-6ef74ac-vs-3.13.0rc2.md)[📈](results/bm-20241218-3.14.0a2%2B-6ef74ac-NOGIL/bm-20241218-vultr-x86_64-corona10-gh_115999_BINARY_SUB-3.14.0a2%2B-6ef74ac-vs-3.13.0rc2.svg) | 1.011x ↑<br>[📄](results/bm-20241218-3.14.0a2%2B-6ef74ac-NOGIL/bm-20241218-vultr-x86_64-corona10-gh_115999_BINARY_SUB-3.14.0a2%2B-6ef74ac-vs-base.md)[📈](results/bm-20241218-3.14.0a2%2B-6ef74ac-NOGIL/bm-20241218-vultr-x86_64-corona10-gh_115999_BINARY_SUB-3.14.0a2%2B-6ef74ac-vs-base.svg)[🧠](results/bm-20241218-3.14.0a2%2B-6ef74ac-NOGIL/bm-20241218-vultr-x86_64-corona10-gh_115999_BINARY_SUB-3.14.0a2%2B-6ef74ac-vs-base-mem.svg) |
| [2024-12-17](results/bm-20241217-3.14.0a2%2B-699f4e9) | nascheme/gh_115999_specialize | 699f4e9 | 1.079x ↑<br>[📄](results/bm-20241217-3.14.0a2%2B-699f4e9/bm-20241217-vultr-x86_64-nascheme-gh_115999_specialize-3.14.0a2%2B-699f4e9-vs-3.12.6.md)[📈](results/bm-20241217-3.14.0a2%2B-699f4e9/bm-20241217-vultr-x86_64-nascheme-gh_115999_specialize-3.14.0a2%2B-699f4e9-vs-3.12.6.svg) | 1.040x ↑<br>[📄](results/bm-20241217-3.14.0a2%2B-699f4e9/bm-20241217-vultr-x86_64-nascheme-gh_115999_specialize-3.14.0a2%2B-699f4e9-vs-3.13.0rc2.md)[📈](results/bm-20241217-3.14.0a2%2B-699f4e9/bm-20241217-vultr-x86_64-nascheme-gh_115999_specialize-3.14.0a2%2B-699f4e9-vs-3.13.0rc2.svg) | 1.005x ↓<br>[📄](results/bm-20241217-3.14.0a2%2B-699f4e9/bm-20241217-vultr-x86_64-nascheme-gh_115999_specialize-3.14.0a2%2B-699f4e9-vs-base.md)[📈](results/bm-20241217-3.14.0a2%2B-699f4e9/bm-20241217-vultr-x86_64-nascheme-gh_115999_specialize-3.14.0a2%2B-699f4e9-vs-base.svg)[🧠](results/bm-20241217-3.14.0a2%2B-699f4e9/bm-20241217-vultr-x86_64-nascheme-gh_115999_specialize-3.14.0a2%2B-699f4e9-vs-base-mem.svg) |
| [2024-12-17](results/bm-20241217-3.14.0a2%2B-699f4e9-NOGIL) | nascheme/gh_115999_specialize | 699f4e9 (NOGIL) | 1.201x ↓<br>[📄](results/bm-20241217-3.14.0a2%2B-699f4e9-NOGIL/bm-20241217-vultr-x86_64-nascheme-gh_115999_specialize-3.14.0a2%2B-699f4e9-vs-3.12.6.md)[📈](results/bm-20241217-3.14.0a2%2B-699f4e9-NOGIL/bm-20241217-vultr-x86_64-nascheme-gh_115999_specialize-3.14.0a2%2B-699f4e9-vs-3.12.6.svg) | 1.227x ↓<br>[📄](results/bm-20241217-3.14.0a2%2B-699f4e9-NOGIL/bm-20241217-vultr-x86_64-nascheme-gh_115999_specialize-3.14.0a2%2B-699f4e9-vs-3.13.0rc2.md)[📈](results/bm-20241217-3.14.0a2%2B-699f4e9-NOGIL/bm-20241217-vultr-x86_64-nascheme-gh_115999_specialize-3.14.0a2%2B-699f4e9-vs-3.13.0rc2.svg) | 1.017x ↑<br>[📄](results/bm-20241217-3.14.0a2%2B-699f4e9-NOGIL/bm-20241217-vultr-x86_64-nascheme-gh_115999_specialize-3.14.0a2%2B-699f4e9-vs-base.md)[📈](results/bm-20241217-3.14.0a2%2B-699f4e9-NOGIL/bm-20241217-vultr-x86_64-nascheme-gh_115999_specialize-3.14.0a2%2B-699f4e9-vs-base.svg)[🧠](results/bm-20241217-3.14.0a2%2B-699f4e9-NOGIL/bm-20241217-vultr-x86_64-nascheme-gh_115999_specialize-3.14.0a2%2B-699f4e9-vs-base-mem.svg) |


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
