# Faster CPython Benchmark Infrastructure

🔒 [▶️ START A BENCHMARK RUN](../../actions/workflows/benchmark.yml)

## Results

Here are some recent and important revisions. 👉 [Complete list of results](RESULTS.md).

<!-- START table -->
[Most recent pystats on main (2a66dd3)](results/bm-20241220-3.14.0a3%2B-2a66dd3-PYTHON_UOPS/bm-20241220-vultr-x86_64-python-2a66dd33dfc0b845042d-3.14.0a3%2B-2a66dd3-pystats.md)

## linux x86_64 (linux)
| date | fork/ref | hash/flags | vs. 3.12.6: | vs. 3.13.0rc2: | vs. base: |
| --- | --- | --- | ---: | ---: | ---: |
| [2024-12-20](results/bm-20241220-3.14.0a3%2B-2a66dd3) | python/2a66dd33dfc0b845042d | 2a66dd3 | 1.106x ↑<br>[📄](results/bm-20241220-3.14.0a3%2B-2a66dd3/bm-20241220-linux-x86_64-python-2a66dd33dfc0b845042d-3.14.0a3%2B-2a66dd3-vs-3.12.6.md)[📈](results/bm-20241220-3.14.0a3%2B-2a66dd3/bm-20241220-linux-x86_64-python-2a66dd33dfc0b845042d-3.14.0a3%2B-2a66dd3-vs-3.12.6.svg) | 1.059x ↑<br>[📄](results/bm-20241220-3.14.0a3%2B-2a66dd3/bm-20241220-linux-x86_64-python-2a66dd33dfc0b845042d-3.14.0a3%2B-2a66dd3-vs-3.13.0rc2.md)[📈](results/bm-20241220-3.14.0a3%2B-2a66dd3/bm-20241220-linux-x86_64-python-2a66dd33dfc0b845042d-3.14.0a3%2B-2a66dd3-vs-3.13.0rc2.svg) |  |
| [2024-12-20](results/bm-20241220-3.14.0a3%2B-2a66dd3-NOGIL) | python/2a66dd33dfc0b845042d | 2a66dd3 (NOGIL) | 1.147x ↓<br>[📄](results/bm-20241220-3.14.0a3%2B-2a66dd3-NOGIL/bm-20241220-linux-x86_64-python-2a66dd33dfc0b845042d-3.14.0a3%2B-2a66dd3-vs-3.12.6.md)[📈](results/bm-20241220-3.14.0a3%2B-2a66dd3-NOGIL/bm-20241220-linux-x86_64-python-2a66dd33dfc0b845042d-3.14.0a3%2B-2a66dd3-vs-3.12.6.svg) | 1.175x ↓<br>[📄](results/bm-20241220-3.14.0a3%2B-2a66dd3-NOGIL/bm-20241220-linux-x86_64-python-2a66dd33dfc0b845042d-3.14.0a3%2B-2a66dd3-vs-3.13.0rc2.md)[📈](results/bm-20241220-3.14.0a3%2B-2a66dd3-NOGIL/bm-20241220-linux-x86_64-python-2a66dd33dfc0b845042d-3.14.0a3%2B-2a66dd3-vs-3.13.0rc2.svg) | 1.215x ↓<br>[📄](results/bm-20241220-3.14.0a3%2B-2a66dd3-NOGIL/bm-20241220-linux-x86_64-python-2a66dd33dfc0b845042d-3.14.0a3%2B-2a66dd3-vs-base.md)[📈](results/bm-20241220-3.14.0a3%2B-2a66dd3-NOGIL/bm-20241220-linux-x86_64-python-2a66dd33dfc0b845042d-3.14.0a3%2B-2a66dd3-vs-base.svg)[🧠](results/bm-20241220-3.14.0a3%2B-2a66dd3-NOGIL/bm-20241220-linux-x86_64-python-2a66dd33dfc0b845042d-3.14.0a3%2B-2a66dd3-vs-base-mem.svg) |
| [2024-12-19](results/bm-20241219-3.14.0a3%2B-39e69a7) | python/39e69a7cd54d44c9061d | 39e69a7 | 1.102x ↑<br>[📄](results/bm-20241219-3.14.0a3%2B-39e69a7/bm-20241219-linux-x86_64-python-39e69a7cd54d44c9061d-3.14.0a3%2B-39e69a7-vs-3.12.6.md)[📈](results/bm-20241219-3.14.0a3%2B-39e69a7/bm-20241219-linux-x86_64-python-39e69a7cd54d44c9061d-3.14.0a3%2B-39e69a7-vs-3.12.6.svg) | 1.058x ↑<br>[📄](results/bm-20241219-3.14.0a3%2B-39e69a7/bm-20241219-linux-x86_64-python-39e69a7cd54d44c9061d-3.14.0a3%2B-39e69a7-vs-3.13.0rc2.md)[📈](results/bm-20241219-3.14.0a3%2B-39e69a7/bm-20241219-linux-x86_64-python-39e69a7cd54d44c9061d-3.14.0a3%2B-39e69a7-vs-3.13.0rc2.svg) |  |
| [2024-12-19](results/bm-20241219-3.14.0a3%2B-39e69a7-NOGIL) | python/39e69a7cd54d44c9061d | 39e69a7 (NOGIL) | 1.143x ↓<br>[📄](results/bm-20241219-3.14.0a3%2B-39e69a7-NOGIL/bm-20241219-linux-x86_64-python-39e69a7cd54d44c9061d-3.14.0a3%2B-39e69a7-vs-3.12.6.md)[📈](results/bm-20241219-3.14.0a3%2B-39e69a7-NOGIL/bm-20241219-linux-x86_64-python-39e69a7cd54d44c9061d-3.14.0a3%2B-39e69a7-vs-3.12.6.svg) | 1.172x ↓<br>[📄](results/bm-20241219-3.14.0a3%2B-39e69a7-NOGIL/bm-20241219-linux-x86_64-python-39e69a7cd54d44c9061d-3.14.0a3%2B-39e69a7-vs-3.13.0rc2.md)[📈](results/bm-20241219-3.14.0a3%2B-39e69a7-NOGIL/bm-20241219-linux-x86_64-python-39e69a7cd54d44c9061d-3.14.0a3%2B-39e69a7-vs-3.13.0rc2.svg) | 1.216x ↓<br>[📄](results/bm-20241219-3.14.0a3%2B-39e69a7-NOGIL/bm-20241219-linux-x86_64-python-39e69a7cd54d44c9061d-3.14.0a3%2B-39e69a7-vs-base.md)[📈](results/bm-20241219-3.14.0a3%2B-39e69a7-NOGIL/bm-20241219-linux-x86_64-python-39e69a7cd54d44c9061d-3.14.0a3%2B-39e69a7-vs-base.svg)[🧠](results/bm-20241219-3.14.0a3%2B-39e69a7-NOGIL/bm-20241219-linux-x86_64-python-39e69a7cd54d44c9061d-3.14.0a3%2B-39e69a7-vs-base-mem.svg) |
| [2024-12-18](results/bm-20241218-3.14.0a3%2B-f802c8b-NOGIL) | python/f802c8bf872ab882d305 | f802c8b (NOGIL) | 1.181x ↓<br>[📄](results/bm-20241218-3.14.0a3%2B-f802c8b-NOGIL/bm-20241218-linux-x86_64-python-f802c8bf872ab882d305-3.14.0a3%2B-f802c8b-vs-3.12.6.md)[📈](results/bm-20241218-3.14.0a3%2B-f802c8b-NOGIL/bm-20241218-linux-x86_64-python-f802c8bf872ab882d305-3.14.0a3%2B-f802c8b-vs-3.12.6.svg) | 1.208x ↓<br>[📄](results/bm-20241218-3.14.0a3%2B-f802c8b-NOGIL/bm-20241218-linux-x86_64-python-f802c8bf872ab882d305-3.14.0a3%2B-f802c8b-vs-3.13.0rc2.md)[📈](results/bm-20241218-3.14.0a3%2B-f802c8b-NOGIL/bm-20241218-linux-x86_64-python-f802c8bf872ab882d305-3.14.0a3%2B-f802c8b-vs-3.13.0rc2.svg) | 1.251x ↓<br>[📄](results/bm-20241218-3.14.0a3%2B-f802c8b-NOGIL/bm-20241218-linux-x86_64-python-f802c8bf872ab882d305-3.14.0a3%2B-f802c8b-vs-base.md)[📈](results/bm-20241218-3.14.0a3%2B-f802c8b-NOGIL/bm-20241218-linux-x86_64-python-f802c8bf872ab882d305-3.14.0a3%2B-f802c8b-vs-base.svg)[🧠](results/bm-20241218-3.14.0a3%2B-f802c8b-NOGIL/bm-20241218-linux-x86_64-python-f802c8bf872ab882d305-3.14.0a3%2B-f802c8b-vs-base-mem.svg) |
| [2024-12-18](results/bm-20241218-3.14.0a3%2B-f802c8b) | python/f802c8bf872ab882d305 | f802c8b | 1.107x ↑<br>[📄](results/bm-20241218-3.14.0a3%2B-f802c8b/bm-20241218-linux-x86_64-python-f802c8bf872ab882d305-3.14.0a3%2B-f802c8b-vs-3.12.6.md)[📈](results/bm-20241218-3.14.0a3%2B-f802c8b/bm-20241218-linux-x86_64-python-f802c8bf872ab882d305-3.14.0a3%2B-f802c8b-vs-3.12.6.svg) | 1.064x ↑<br>[📄](results/bm-20241218-3.14.0a3%2B-f802c8b/bm-20241218-linux-x86_64-python-f802c8bf872ab882d305-3.14.0a3%2B-f802c8b-vs-3.13.0rc2.md)[📈](results/bm-20241218-3.14.0a3%2B-f802c8b/bm-20241218-linux-x86_64-python-f802c8bf872ab882d305-3.14.0a3%2B-f802c8b-vs-3.13.0rc2.svg) |  |

## linux x86_64 (vultr)
| date | fork/ref | hash/flags | vs. 3.12.6: | vs. 3.13.0rc2: | vs. base: |
| --- | --- | --- | ---: | ---: | ---: |
| [2024-12-22](results/bm-20241222-3.14.0a3%2B-f420bdd-NOGIL) | python/f420bdd29fbc1a97ad20 | f420bdd (NOGIL) | 1.187x ↓<br>[📄](results/bm-20241222-3.14.0a3%2B-f420bdd-NOGIL/bm-20241222-vultr-x86_64-python-f420bdd29fbc1a97ad20-3.14.0a3%2B-f420bdd-vs-3.12.6.md)[📈](results/bm-20241222-3.14.0a3%2B-f420bdd-NOGIL/bm-20241222-vultr-x86_64-python-f420bdd29fbc1a97ad20-3.14.0a3%2B-f420bdd-vs-3.12.6.svg) | 1.213x ↓<br>[📄](results/bm-20241222-3.14.0a3%2B-f420bdd-NOGIL/bm-20241222-vultr-x86_64-python-f420bdd29fbc1a97ad20-3.14.0a3%2B-f420bdd-vs-3.13.0rc2.md)[📈](results/bm-20241222-3.14.0a3%2B-f420bdd-NOGIL/bm-20241222-vultr-x86_64-python-f420bdd29fbc1a97ad20-3.14.0a3%2B-f420bdd-vs-3.13.0rc2.svg) |  |
| [2024-12-22](results/bm-20241222-3.14.0a3%2B-83781d1-NOGIL) | colesbury/align_32 | 83781d1 (NOGIL) | 1.177x ↓<br>[📄](results/bm-20241222-3.14.0a3%2B-83781d1-NOGIL/bm-20241222-vultr-x86_64-colesbury-align_32-3.14.0a3%2B-83781d1-vs-3.12.6.md)[📈](results/bm-20241222-3.14.0a3%2B-83781d1-NOGIL/bm-20241222-vultr-x86_64-colesbury-align_32-3.14.0a3%2B-83781d1-vs-3.12.6.svg) | 1.203x ↓<br>[📄](results/bm-20241222-3.14.0a3%2B-83781d1-NOGIL/bm-20241222-vultr-x86_64-colesbury-align_32-3.14.0a3%2B-83781d1-vs-3.13.0rc2.md)[📈](results/bm-20241222-3.14.0a3%2B-83781d1-NOGIL/bm-20241222-vultr-x86_64-colesbury-align_32-3.14.0a3%2B-83781d1-vs-3.13.0rc2.svg) | 1.012x ↑<br>[📄](results/bm-20241222-3.14.0a3%2B-83781d1-NOGIL/bm-20241222-vultr-x86_64-colesbury-align_32-3.14.0a3%2B-83781d1-vs-base.md)[📈](results/bm-20241222-3.14.0a3%2B-83781d1-NOGIL/bm-20241222-vultr-x86_64-colesbury-align_32-3.14.0a3%2B-83781d1-vs-base.svg)[🧠](results/bm-20241222-3.14.0a3%2B-83781d1-NOGIL/bm-20241222-vultr-x86_64-colesbury-align_32-3.14.0a3%2B-83781d1-vs-base-mem.svg) |
| [2024-12-20](results/bm-20241220-3.14.0a3%2B-b28153d-NOGIL) | Yhg1s/optimise_recursive_c | b28153d (NOGIL) | 1.168x ↓<br>[📄](results/bm-20241220-3.14.0a3%2B-b28153d-NOGIL/bm-20241220-vultr-x86_64-Yhg1s-optimise_recursive_c-3.14.0a3%2B-b28153d-vs-3.12.6.md)[📈](results/bm-20241220-3.14.0a3%2B-b28153d-NOGIL/bm-20241220-vultr-x86_64-Yhg1s-optimise_recursive_c-3.14.0a3%2B-b28153d-vs-3.12.6.svg) | 1.195x ↓<br>[📄](results/bm-20241220-3.14.0a3%2B-b28153d-NOGIL/bm-20241220-vultr-x86_64-Yhg1s-optimise_recursive_c-3.14.0a3%2B-b28153d-vs-3.13.0rc2.md)[📈](results/bm-20241220-3.14.0a3%2B-b28153d-NOGIL/bm-20241220-vultr-x86_64-Yhg1s-optimise_recursive_c-3.14.0a3%2B-b28153d-vs-3.13.0rc2.svg) | 1.024x ↑<br>[📄](results/bm-20241220-3.14.0a3%2B-b28153d-NOGIL/bm-20241220-vultr-x86_64-Yhg1s-optimise_recursive_c-3.14.0a3%2B-b28153d-vs-base.md)[📈](results/bm-20241220-3.14.0a3%2B-b28153d-NOGIL/bm-20241220-vultr-x86_64-Yhg1s-optimise_recursive_c-3.14.0a3%2B-b28153d-vs-base.svg)[🧠](results/bm-20241220-3.14.0a3%2B-b28153d-NOGIL/bm-20241220-vultr-x86_64-Yhg1s-optimise_recursive_c-3.14.0a3%2B-b28153d-vs-base-mem.svg) |
| [2024-12-20](results/bm-20241220-3.14.0a3%2B-4fc4237) | mpage/4fc4237a1ea09f6a31e9 | 4fc4237 | 1.091x ↑<br>[📄](results/bm-20241220-3.14.0a3%2B-4fc4237/bm-20241220-vultr-x86_64-mpage-4fc4237a1ea09f6a31e9-3.14.0a3%2B-4fc4237-vs-3.12.6.md)[📈](results/bm-20241220-3.14.0a3%2B-4fc4237/bm-20241220-vultr-x86_64-mpage-4fc4237a1ea09f6a31e9-3.14.0a3%2B-4fc4237-vs-3.12.6.svg) | 1.052x ↑<br>[📄](results/bm-20241220-3.14.0a3%2B-4fc4237/bm-20241220-vultr-x86_64-mpage-4fc4237a1ea09f6a31e9-3.14.0a3%2B-4fc4237-vs-3.13.0rc2.md)[📈](results/bm-20241220-3.14.0a3%2B-4fc4237/bm-20241220-vultr-x86_64-mpage-4fc4237a1ea09f6a31e9-3.14.0a3%2B-4fc4237-vs-3.13.0rc2.svg) | 1.002x ↑<br>[📄](results/bm-20241220-3.14.0a3%2B-4fc4237/bm-20241220-vultr-x86_64-mpage-4fc4237a1ea09f6a31e9-3.14.0a3%2B-4fc4237-vs-base.md)[📈](results/bm-20241220-3.14.0a3%2B-4fc4237/bm-20241220-vultr-x86_64-mpage-4fc4237a1ea09f6a31e9-3.14.0a3%2B-4fc4237-vs-base.svg)[🧠](results/bm-20241220-3.14.0a3%2B-4fc4237/bm-20241220-vultr-x86_64-mpage-4fc4237a1ea09f6a31e9-3.14.0a3%2B-4fc4237-vs-base-mem.svg) |
| [2024-12-20](results/bm-20241220-3.14.0a3%2B-63a53fd) | mpage/63a53fd736f57fcf80df | 63a53fd | 1.085x ↑<br>[📄](results/bm-20241220-3.14.0a3%2B-63a53fd/bm-20241220-vultr-x86_64-mpage-63a53fd736f57fcf80df-3.14.0a3%2B-63a53fd-vs-3.12.6.md)[📈](results/bm-20241220-3.14.0a3%2B-63a53fd/bm-20241220-vultr-x86_64-mpage-63a53fd736f57fcf80df-3.14.0a3%2B-63a53fd-vs-3.12.6.svg) | 1.046x ↑<br>[📄](results/bm-20241220-3.14.0a3%2B-63a53fd/bm-20241220-vultr-x86_64-mpage-63a53fd736f57fcf80df-3.14.0a3%2B-63a53fd-vs-3.13.0rc2.md)[📈](results/bm-20241220-3.14.0a3%2B-63a53fd/bm-20241220-vultr-x86_64-mpage-63a53fd736f57fcf80df-3.14.0a3%2B-63a53fd-vs-3.13.0rc2.svg) | 1.002x ↓<br>[📄](results/bm-20241220-3.14.0a3%2B-63a53fd/bm-20241220-vultr-x86_64-mpage-63a53fd736f57fcf80df-3.14.0a3%2B-63a53fd-vs-base.md)[📈](results/bm-20241220-3.14.0a3%2B-63a53fd/bm-20241220-vultr-x86_64-mpage-63a53fd736f57fcf80df-3.14.0a3%2B-63a53fd-vs-base.svg)[🧠](results/bm-20241220-3.14.0a3%2B-63a53fd/bm-20241220-vultr-x86_64-mpage-63a53fd736f57fcf80df-3.14.0a3%2B-63a53fd-vs-base-mem.svg) |
| [2024-12-20](results/bm-20241220-3.14.0a3%2B-9364aaa) | mpage/9364aaa5b628ce0b5ffb | 9364aaa | 1.090x ↑<br>[📄](results/bm-20241220-3.14.0a3%2B-9364aaa/bm-20241220-vultr-x86_64-mpage-9364aaa5b628ce0b5ffb-3.14.0a3%2B-9364aaa-vs-3.12.6.md)[📈](results/bm-20241220-3.14.0a3%2B-9364aaa/bm-20241220-vultr-x86_64-mpage-9364aaa5b628ce0b5ffb-3.14.0a3%2B-9364aaa-vs-3.12.6.svg) | 1.051x ↑<br>[📄](results/bm-20241220-3.14.0a3%2B-9364aaa/bm-20241220-vultr-x86_64-mpage-9364aaa5b628ce0b5ffb-3.14.0a3%2B-9364aaa-vs-3.13.0rc2.md)[📈](results/bm-20241220-3.14.0a3%2B-9364aaa/bm-20241220-vultr-x86_64-mpage-9364aaa5b628ce0b5ffb-3.14.0a3%2B-9364aaa-vs-3.13.0rc2.svg) | 1.001x ↑<br>[📄](results/bm-20241220-3.14.0a3%2B-9364aaa/bm-20241220-vultr-x86_64-mpage-9364aaa5b628ce0b5ffb-3.14.0a3%2B-9364aaa-vs-base.md)[📈](results/bm-20241220-3.14.0a3%2B-9364aaa/bm-20241220-vultr-x86_64-mpage-9364aaa5b628ce0b5ffb-3.14.0a3%2B-9364aaa-vs-base.svg)[🧠](results/bm-20241220-3.14.0a3%2B-9364aaa/bm-20241220-vultr-x86_64-mpage-9364aaa5b628ce0b5ffb-3.14.0a3%2B-9364aaa-vs-base-mem.svg) |
| [2024-12-20](results/bm-20241220-3.14.0a3%2B-d6d4c73-NOGIL) | mpage/gh_115999_load_attr_ | d6d4c73 (NOGIL) | 1.087x ↓<br>[📄](results/bm-20241220-3.14.0a3%2B-d6d4c73-NOGIL/bm-20241220-vultr-x86_64-mpage-gh_115999_load_attr_-3.14.0a3%2B-d6d4c73-vs-3.12.6.md)[📈](results/bm-20241220-3.14.0a3%2B-d6d4c73-NOGIL/bm-20241220-vultr-x86_64-mpage-gh_115999_load_attr_-3.14.0a3%2B-d6d4c73-vs-3.12.6.svg) | 1.116x ↓<br>[📄](results/bm-20241220-3.14.0a3%2B-d6d4c73-NOGIL/bm-20241220-vultr-x86_64-mpage-gh_115999_load_attr_-3.14.0a3%2B-d6d4c73-vs-3.13.0rc2.md)[📈](results/bm-20241220-3.14.0a3%2B-d6d4c73-NOGIL/bm-20241220-vultr-x86_64-mpage-gh_115999_load_attr_-3.14.0a3%2B-d6d4c73-vs-3.13.0rc2.svg) | 1.120x ↑<br>[📄](results/bm-20241220-3.14.0a3%2B-d6d4c73-NOGIL/bm-20241220-vultr-x86_64-mpage-gh_115999_load_attr_-3.14.0a3%2B-d6d4c73-vs-base.md)[📈](results/bm-20241220-3.14.0a3%2B-d6d4c73-NOGIL/bm-20241220-vultr-x86_64-mpage-gh_115999_load_attr_-3.14.0a3%2B-d6d4c73-vs-base.svg)[🧠](results/bm-20241220-3.14.0a3%2B-d6d4c73-NOGIL/bm-20241220-vultr-x86_64-mpage-gh_115999_load_attr_-3.14.0a3%2B-d6d4c73-vs-base-mem.svg) |
| [2024-12-20](results/bm-20241220-3.14.0a3%2B-d6d4c73) | mpage/gh_115999_load_attr_ | d6d4c73 | 1.087x ↑<br>[📄](results/bm-20241220-3.14.0a3%2B-d6d4c73/bm-20241220-vultr-x86_64-mpage-gh_115999_load_attr_-3.14.0a3%2B-d6d4c73-vs-3.12.6.md)[📈](results/bm-20241220-3.14.0a3%2B-d6d4c73/bm-20241220-vultr-x86_64-mpage-gh_115999_load_attr_-3.14.0a3%2B-d6d4c73-vs-3.12.6.svg) | 1.048x ↑<br>[📄](results/bm-20241220-3.14.0a3%2B-d6d4c73/bm-20241220-vultr-x86_64-mpage-gh_115999_load_attr_-3.14.0a3%2B-d6d4c73-vs-3.13.0rc2.md)[📈](results/bm-20241220-3.14.0a3%2B-d6d4c73/bm-20241220-vultr-x86_64-mpage-gh_115999_load_attr_-3.14.0a3%2B-d6d4c73-vs-3.13.0rc2.svg) | 1.002x ↑<br>[📄](results/bm-20241220-3.14.0a3%2B-d6d4c73/bm-20241220-vultr-x86_64-mpage-gh_115999_load_attr_-3.14.0a3%2B-d6d4c73-vs-base.md)[📈](results/bm-20241220-3.14.0a3%2B-d6d4c73/bm-20241220-vultr-x86_64-mpage-gh_115999_load_attr_-3.14.0a3%2B-d6d4c73-vs-base.svg)[🧠](results/bm-20241220-3.14.0a3%2B-d6d4c73/bm-20241220-vultr-x86_64-mpage-gh_115999_load_attr_-3.14.0a3%2B-d6d4c73-vs-base-mem.svg) |
| [2024-12-20](results/bm-20241220-3.14.0a3%2B-ddb794a-NOGIL) | Yhg1s/optimise_recursive_c | ddb794a (NOGIL) | 1.185x ↓<br>[📄](results/bm-20241220-3.14.0a3%2B-ddb794a-NOGIL/bm-20241220-vultr-x86_64-Yhg1s-optimise_recursive_c-3.14.0a3%2B-ddb794a-vs-3.12.6.md)[📈](results/bm-20241220-3.14.0a3%2B-ddb794a-NOGIL/bm-20241220-vultr-x86_64-Yhg1s-optimise_recursive_c-3.14.0a3%2B-ddb794a-vs-3.12.6.svg) | 1.212x ↓<br>[📄](results/bm-20241220-3.14.0a3%2B-ddb794a-NOGIL/bm-20241220-vultr-x86_64-Yhg1s-optimise_recursive_c-3.14.0a3%2B-ddb794a-vs-3.13.0rc2.md)[📈](results/bm-20241220-3.14.0a3%2B-ddb794a-NOGIL/bm-20241220-vultr-x86_64-Yhg1s-optimise_recursive_c-3.14.0a3%2B-ddb794a-vs-3.13.0rc2.svg) | 1.003x ↑<br>[📄](results/bm-20241220-3.14.0a3%2B-ddb794a-NOGIL/bm-20241220-vultr-x86_64-Yhg1s-optimise_recursive_c-3.14.0a3%2B-ddb794a-vs-base.md)[📈](results/bm-20241220-3.14.0a3%2B-ddb794a-NOGIL/bm-20241220-vultr-x86_64-Yhg1s-optimise_recursive_c-3.14.0a3%2B-ddb794a-vs-base.svg)[🧠](results/bm-20241220-3.14.0a3%2B-ddb794a-NOGIL/bm-20241220-vultr-x86_64-Yhg1s-optimise_recursive_c-3.14.0a3%2B-ddb794a-vs-base-mem.svg) |
| [2024-12-20](results/bm-20241220-3.14.0a3%2B-78ffba4-NOGIL) | python/78ffba4221dcb2e39fd5 | 78ffba4 (NOGIL) | 1.188x ↓<br>[📄](results/bm-20241220-3.14.0a3%2B-78ffba4-NOGIL/bm-20241220-vultr-x86_64-python-78ffba4221dcb2e39fd5-3.14.0a3%2B-78ffba4-vs-3.12.6.md)[📈](results/bm-20241220-3.14.0a3%2B-78ffba4-NOGIL/bm-20241220-vultr-x86_64-python-78ffba4221dcb2e39fd5-3.14.0a3%2B-78ffba4-vs-3.12.6.svg) | 1.215x ↓<br>[📄](results/bm-20241220-3.14.0a3%2B-78ffba4-NOGIL/bm-20241220-vultr-x86_64-python-78ffba4221dcb2e39fd5-3.14.0a3%2B-78ffba4-vs-3.13.0rc2.md)[📈](results/bm-20241220-3.14.0a3%2B-78ffba4-NOGIL/bm-20241220-vultr-x86_64-python-78ffba4221dcb2e39fd5-3.14.0a3%2B-78ffba4-vs-3.13.0rc2.svg) |  |
| [2024-12-20](results/bm-20241220-3.14.0a3%2B-b868363) | mpage/gh_115999_load_attr_ | b868363 | 1.094x ↑<br>[📄](results/bm-20241220-3.14.0a3%2B-b868363/bm-20241220-vultr-x86_64-mpage-gh_115999_load_attr_-3.14.0a3%2B-b868363-vs-3.12.6.md)[📈](results/bm-20241220-3.14.0a3%2B-b868363/bm-20241220-vultr-x86_64-mpage-gh_115999_load_attr_-3.14.0a3%2B-b868363-vs-3.12.6.svg) | 1.055x ↑<br>[📄](results/bm-20241220-3.14.0a3%2B-b868363/bm-20241220-vultr-x86_64-mpage-gh_115999_load_attr_-3.14.0a3%2B-b868363-vs-3.13.0rc2.md)[📈](results/bm-20241220-3.14.0a3%2B-b868363/bm-20241220-vultr-x86_64-mpage-gh_115999_load_attr_-3.14.0a3%2B-b868363-vs-3.13.0rc2.svg) | 1.008x ↑<br>[📄](results/bm-20241220-3.14.0a3%2B-b868363/bm-20241220-vultr-x86_64-mpage-gh_115999_load_attr_-3.14.0a3%2B-b868363-vs-base.md)[📈](results/bm-20241220-3.14.0a3%2B-b868363/bm-20241220-vultr-x86_64-mpage-gh_115999_load_attr_-3.14.0a3%2B-b868363-vs-base.svg)[🧠](results/bm-20241220-3.14.0a3%2B-b868363/bm-20241220-vultr-x86_64-mpage-gh_115999_load_attr_-3.14.0a3%2B-b868363-vs-base-mem.svg) |
| [2024-12-20](results/bm-20241220-3.14.0a3%2B-2a66dd3) | python/2a66dd33dfc0b845042d | 2a66dd3 | 1.088x ↑<br>[📄](results/bm-20241220-3.14.0a3%2B-2a66dd3/bm-20241220-vultr-x86_64-python-2a66dd33dfc0b845042d-3.14.0a3%2B-2a66dd3-vs-3.12.6.md)[📈](results/bm-20241220-3.14.0a3%2B-2a66dd3/bm-20241220-vultr-x86_64-python-2a66dd33dfc0b845042d-3.14.0a3%2B-2a66dd3-vs-3.12.6.svg) | 1.050x ↑<br>[📄](results/bm-20241220-3.14.0a3%2B-2a66dd3/bm-20241220-vultr-x86_64-python-2a66dd33dfc0b845042d-3.14.0a3%2B-2a66dd3-vs-3.13.0rc2.md)[📈](results/bm-20241220-3.14.0a3%2B-2a66dd3/bm-20241220-vultr-x86_64-python-2a66dd33dfc0b845042d-3.14.0a3%2B-2a66dd3-vs-3.13.0rc2.svg) |  |
| [2024-12-20](results/bm-20241220-3.14.0a3%2B-2a66dd3-NOGIL) | python/2a66dd33dfc0b845042d | 2a66dd3 (NOGIL) | 1.193x ↓<br>[📄](results/bm-20241220-3.14.0a3%2B-2a66dd3-NOGIL/bm-20241220-vultr-x86_64-python-2a66dd33dfc0b845042d-3.14.0a3%2B-2a66dd3-vs-3.12.6.md)[📈](results/bm-20241220-3.14.0a3%2B-2a66dd3-NOGIL/bm-20241220-vultr-x86_64-python-2a66dd33dfc0b845042d-3.14.0a3%2B-2a66dd3-vs-3.12.6.svg) | 1.219x ↓<br>[📄](results/bm-20241220-3.14.0a3%2B-2a66dd3-NOGIL/bm-20241220-vultr-x86_64-python-2a66dd33dfc0b845042d-3.14.0a3%2B-2a66dd3-vs-3.13.0rc2.md)[📈](results/bm-20241220-3.14.0a3%2B-2a66dd3-NOGIL/bm-20241220-vultr-x86_64-python-2a66dd33dfc0b845042d-3.14.0a3%2B-2a66dd3-vs-3.13.0rc2.svg) | 1.252x ↓<br>[📄](results/bm-20241220-3.14.0a3%2B-2a66dd3-NOGIL/bm-20241220-vultr-x86_64-python-2a66dd33dfc0b845042d-3.14.0a3%2B-2a66dd3-vs-base.md)[📈](results/bm-20241220-3.14.0a3%2B-2a66dd3-NOGIL/bm-20241220-vultr-x86_64-python-2a66dd33dfc0b845042d-3.14.0a3%2B-2a66dd3-vs-base.svg)[🧠](results/bm-20241220-3.14.0a3%2B-2a66dd3-NOGIL/bm-20241220-vultr-x86_64-python-2a66dd33dfc0b845042d-3.14.0a3%2B-2a66dd3-vs-base-mem.svg) |
| [2024-12-20](results/bm-20241220-3.14.0a3%2B-1b787b3-NOGIL) | mpage/gh_115999_load_attr_ | 1b787b3 (NOGIL) | 1.086x ↓<br>[📄](results/bm-20241220-3.14.0a3%2B-1b787b3-NOGIL/bm-20241220-vultr-x86_64-mpage-gh_115999_load_attr_-3.14.0a3%2B-1b787b3-vs-3.12.6.md)[📈](results/bm-20241220-3.14.0a3%2B-1b787b3-NOGIL/bm-20241220-vultr-x86_64-mpage-gh_115999_load_attr_-3.14.0a3%2B-1b787b3-vs-3.12.6.svg) | 1.115x ↓<br>[📄](results/bm-20241220-3.14.0a3%2B-1b787b3-NOGIL/bm-20241220-vultr-x86_64-mpage-gh_115999_load_attr_-3.14.0a3%2B-1b787b3-vs-3.13.0rc2.md)[📈](results/bm-20241220-3.14.0a3%2B-1b787b3-NOGIL/bm-20241220-vultr-x86_64-mpage-gh_115999_load_attr_-3.14.0a3%2B-1b787b3-vs-3.13.0rc2.svg) | 1.122x ↑<br>[📄](results/bm-20241220-3.14.0a3%2B-1b787b3-NOGIL/bm-20241220-vultr-x86_64-mpage-gh_115999_load_attr_-3.14.0a3%2B-1b787b3-vs-base.md)[📈](results/bm-20241220-3.14.0a3%2B-1b787b3-NOGIL/bm-20241220-vultr-x86_64-mpage-gh_115999_load_attr_-3.14.0a3%2B-1b787b3-vs-base.svg)[🧠](results/bm-20241220-3.14.0a3%2B-1b787b3-NOGIL/bm-20241220-vultr-x86_64-mpage-gh_115999_load_attr_-3.14.0a3%2B-1b787b3-vs-base-mem.svg) |
| [2024-12-19](results/bm-20241219-3.14.0a3%2B-3876bc7-NOGIL) | mpage/gh_115999_load_attr_ | 3876bc7 (NOGIL) | 1.091x ↓<br>[📄](results/bm-20241219-3.14.0a3%2B-3876bc7-NOGIL/bm-20241219-vultr-x86_64-mpage-gh_115999_load_attr_-3.14.0a3%2B-3876bc7-vs-3.12.6.md)[📈](results/bm-20241219-3.14.0a3%2B-3876bc7-NOGIL/bm-20241219-vultr-x86_64-mpage-gh_115999_load_attr_-3.14.0a3%2B-3876bc7-vs-3.12.6.svg) | 1.120x ↓<br>[📄](results/bm-20241219-3.14.0a3%2B-3876bc7-NOGIL/bm-20241219-vultr-x86_64-mpage-gh_115999_load_attr_-3.14.0a3%2B-3876bc7-vs-3.13.0rc2.md)[📈](results/bm-20241219-3.14.0a3%2B-3876bc7-NOGIL/bm-20241219-vultr-x86_64-mpage-gh_115999_load_attr_-3.14.0a3%2B-3876bc7-vs-3.13.0rc2.svg) | 1.116x ↑<br>[📄](results/bm-20241219-3.14.0a3%2B-3876bc7-NOGIL/bm-20241219-vultr-x86_64-mpage-gh_115999_load_attr_-3.14.0a3%2B-3876bc7-vs-base.md)[📈](results/bm-20241219-3.14.0a3%2B-3876bc7-NOGIL/bm-20241219-vultr-x86_64-mpage-gh_115999_load_attr_-3.14.0a3%2B-3876bc7-vs-base.svg)[🧠](results/bm-20241219-3.14.0a3%2B-3876bc7-NOGIL/bm-20241219-vultr-x86_64-mpage-gh_115999_load_attr_-3.14.0a3%2B-3876bc7-vs-base-mem.svg) |
| [2024-12-19](results/bm-20241219-3.14.0a3%2B-3876bc7) | mpage/gh_115999_load_attr_ | 3876bc7 | 1.094x ↑<br>[📄](results/bm-20241219-3.14.0a3%2B-3876bc7/bm-20241219-vultr-x86_64-mpage-gh_115999_load_attr_-3.14.0a3%2B-3876bc7-vs-3.12.6.md)[📈](results/bm-20241219-3.14.0a3%2B-3876bc7/bm-20241219-vultr-x86_64-mpage-gh_115999_load_attr_-3.14.0a3%2B-3876bc7-vs-3.12.6.svg) | 1.055x ↑<br>[📄](results/bm-20241219-3.14.0a3%2B-3876bc7/bm-20241219-vultr-x86_64-mpage-gh_115999_load_attr_-3.14.0a3%2B-3876bc7-vs-3.13.0rc2.md)[📈](results/bm-20241219-3.14.0a3%2B-3876bc7/bm-20241219-vultr-x86_64-mpage-gh_115999_load_attr_-3.14.0a3%2B-3876bc7-vs-3.13.0rc2.svg) | 1.008x ↑<br>[📄](results/bm-20241219-3.14.0a3%2B-3876bc7/bm-20241219-vultr-x86_64-mpage-gh_115999_load_attr_-3.14.0a3%2B-3876bc7-vs-base.md)[📈](results/bm-20241219-3.14.0a3%2B-3876bc7/bm-20241219-vultr-x86_64-mpage-gh_115999_load_attr_-3.14.0a3%2B-3876bc7-vs-base.svg)[🧠](results/bm-20241219-3.14.0a3%2B-3876bc7/bm-20241219-vultr-x86_64-mpage-gh_115999_load_attr_-3.14.0a3%2B-3876bc7-vs-base-mem.svg) |
| [2024-12-19](results/bm-20241219-3.14.0a3%2B-39e69a7) | python/39e69a7cd54d44c9061d | 39e69a7 | 1.084x ↑<br>[📄](results/bm-20241219-3.14.0a3%2B-39e69a7/bm-20241219-vultr-x86_64-python-39e69a7cd54d44c9061d-3.14.0a3%2B-39e69a7-vs-3.12.6.md)[📈](results/bm-20241219-3.14.0a3%2B-39e69a7/bm-20241219-vultr-x86_64-python-39e69a7cd54d44c9061d-3.14.0a3%2B-39e69a7-vs-3.12.6.svg) | 1.046x ↑<br>[📄](results/bm-20241219-3.14.0a3%2B-39e69a7/bm-20241219-vultr-x86_64-python-39e69a7cd54d44c9061d-3.14.0a3%2B-39e69a7-vs-3.13.0rc2.md)[📈](results/bm-20241219-3.14.0a3%2B-39e69a7/bm-20241219-vultr-x86_64-python-39e69a7cd54d44c9061d-3.14.0a3%2B-39e69a7-vs-3.13.0rc2.svg) |  |
| [2024-12-19](results/bm-20241219-3.14.0a3%2B-39e69a7) | mpage/39e69a7cd54d44c9061d | 39e69a7 | 1.089x ↑<br>[📄](results/bm-20241219-3.14.0a3%2B-39e69a7/bm-20241219-vultr-x86_64-mpage-39e69a7cd54d44c9061d-3.14.0a3%2B-39e69a7-vs-3.12.6.md)[📈](results/bm-20241219-3.14.0a3%2B-39e69a7/bm-20241219-vultr-x86_64-mpage-39e69a7cd54d44c9061d-3.14.0a3%2B-39e69a7-vs-3.12.6.svg) | 1.051x ↑<br>[📄](results/bm-20241219-3.14.0a3%2B-39e69a7/bm-20241219-vultr-x86_64-mpage-39e69a7cd54d44c9061d-3.14.0a3%2B-39e69a7-vs-3.13.0rc2.md)[📈](results/bm-20241219-3.14.0a3%2B-39e69a7/bm-20241219-vultr-x86_64-mpage-39e69a7cd54d44c9061d-3.14.0a3%2B-39e69a7-vs-3.13.0rc2.svg) |  |
| [2024-12-19](results/bm-20241219-3.14.0a3%2B-39e69a7-NOGIL) | python/39e69a7cd54d44c9061d | 39e69a7 (NOGIL) | 1.189x ↓<br>[📄](results/bm-20241219-3.14.0a3%2B-39e69a7-NOGIL/bm-20241219-vultr-x86_64-python-39e69a7cd54d44c9061d-3.14.0a3%2B-39e69a7-vs-3.12.6.md)[📈](results/bm-20241219-3.14.0a3%2B-39e69a7-NOGIL/bm-20241219-vultr-x86_64-python-39e69a7cd54d44c9061d-3.14.0a3%2B-39e69a7-vs-3.12.6.svg) | 1.215x ↓<br>[📄](results/bm-20241219-3.14.0a3%2B-39e69a7-NOGIL/bm-20241219-vultr-x86_64-python-39e69a7cd54d44c9061d-3.14.0a3%2B-39e69a7-vs-3.13.0rc2.md)[📈](results/bm-20241219-3.14.0a3%2B-39e69a7-NOGIL/bm-20241219-vultr-x86_64-python-39e69a7cd54d44c9061d-3.14.0a3%2B-39e69a7-vs-3.13.0rc2.svg) | 1.246x ↓<br>[📄](results/bm-20241219-3.14.0a3%2B-39e69a7-NOGIL/bm-20241219-vultr-x86_64-python-39e69a7cd54d44c9061d-3.14.0a3%2B-39e69a7-vs-base.md)[📈](results/bm-20241219-3.14.0a3%2B-39e69a7-NOGIL/bm-20241219-vultr-x86_64-python-39e69a7cd54d44c9061d-3.14.0a3%2B-39e69a7-vs-base.svg)[🧠](results/bm-20241219-3.14.0a3%2B-39e69a7-NOGIL/bm-20241219-vultr-x86_64-python-39e69a7cd54d44c9061d-3.14.0a3%2B-39e69a7-vs-base-mem.svg) |
| [2024-12-18](results/bm-20241218-3.14.0a3%2B-f802c8b-NOGIL) | python/f802c8bf872ab882d305 | f802c8b (NOGIL) | 1.218x ↓<br>[📄](results/bm-20241218-3.14.0a3%2B-f802c8b-NOGIL/bm-20241218-vultr-x86_64-python-f802c8bf872ab882d305-3.14.0a3%2B-f802c8b-vs-3.12.6.md)[📈](results/bm-20241218-3.14.0a3%2B-f802c8b-NOGIL/bm-20241218-vultr-x86_64-python-f802c8bf872ab882d305-3.14.0a3%2B-f802c8b-vs-3.12.6.svg) | 1.243x ↓<br>[📄](results/bm-20241218-3.14.0a3%2B-f802c8b-NOGIL/bm-20241218-vultr-x86_64-python-f802c8bf872ab882d305-3.14.0a3%2B-f802c8b-vs-3.13.0rc2.md)[📈](results/bm-20241218-3.14.0a3%2B-f802c8b-NOGIL/bm-20241218-vultr-x86_64-python-f802c8bf872ab882d305-3.14.0a3%2B-f802c8b-vs-3.13.0rc2.svg) | 1.266x ↓<br>[📄](results/bm-20241218-3.14.0a3%2B-f802c8b-NOGIL/bm-20241218-vultr-x86_64-python-f802c8bf872ab882d305-3.14.0a3%2B-f802c8b-vs-base.md)[📈](results/bm-20241218-3.14.0a3%2B-f802c8b-NOGIL/bm-20241218-vultr-x86_64-python-f802c8bf872ab882d305-3.14.0a3%2B-f802c8b-vs-base.svg)[🧠](results/bm-20241218-3.14.0a3%2B-f802c8b-NOGIL/bm-20241218-vultr-x86_64-python-f802c8bf872ab882d305-3.14.0a3%2B-f802c8b-vs-base-mem.svg) |
| [2024-12-18](results/bm-20241218-3.14.0a3%2B-f802c8b) | python/f802c8bf872ab882d305 | f802c8b | 1.076x ↑<br>[📄](results/bm-20241218-3.14.0a3%2B-f802c8b/bm-20241218-vultr-x86_64-python-f802c8bf872ab882d305-3.14.0a3%2B-f802c8b-vs-3.12.6.md)[📈](results/bm-20241218-3.14.0a3%2B-f802c8b/bm-20241218-vultr-x86_64-python-f802c8bf872ab882d305-3.14.0a3%2B-f802c8b-vs-3.12.6.svg) | 1.037x ↑<br>[📄](results/bm-20241218-3.14.0a3%2B-f802c8b/bm-20241218-vultr-x86_64-python-f802c8bf872ab882d305-3.14.0a3%2B-f802c8b-vs-3.13.0rc2.md)[📈](results/bm-20241218-3.14.0a3%2B-f802c8b/bm-20241218-vultr-x86_64-python-f802c8bf872ab882d305-3.14.0a3%2B-f802c8b-vs-3.13.0rc2.svg) |  |
| [2024-12-17](results/bm-20241217-3.14.0a3%2B-3291656) | python/329165639f9ac00ba64f | 3291656 | 1.082x ↑<br>[📄](results/bm-20241217-3.14.0a3%2B-3291656/bm-20241217-vultr-x86_64-python-329165639f9ac00ba64f-3.14.0a3%2B-3291656-vs-3.12.6.md)[📈](results/bm-20241217-3.14.0a3%2B-3291656/bm-20241217-vultr-x86_64-python-329165639f9ac00ba64f-3.14.0a3%2B-3291656-vs-3.12.6.svg) | 1.043x ↑<br>[📄](results/bm-20241217-3.14.0a3%2B-3291656/bm-20241217-vultr-x86_64-python-329165639f9ac00ba64f-3.14.0a3%2B-3291656-vs-3.13.0rc2.md)[📈](results/bm-20241217-3.14.0a3%2B-3291656/bm-20241217-vultr-x86_64-python-329165639f9ac00ba64f-3.14.0a3%2B-3291656-vs-3.13.0rc2.svg) |  |


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
