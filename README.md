# Faster CPython Benchmark Infrastructure

🔒 [▶️ START A BENCHMARK RUN](../../actions/workflows/benchmark.yml)

## Results

Here are some recent and important revisions. 👉 [Complete list of results](RESULTS.md).

<!-- START table -->
[Most recent pystats on main (359c7dd)](results/bm-20250216-3.14.0a5%2B-359c7dd-PYTHON_UOPS/bm-20250216-linux-x86_64-python-359c7dde3bb074e02968-3.14.0a5%2B-359c7dd-pystats.md)

## linux x86_64 (linux)
| date | fork/ref | hash/flags | vs. 3.12.6: | vs. 3.13.0rc2: | vs. base: |
| --- | --- | --- | ---: | ---: | ---: |
| [2025-02-19](results/bm-20250219-3.14.0a5%2B-6c982ae) | python/6c982aeb547528174f8b | 6c982ae | 1.110x ↑<br>[📄](results/bm-20250219-3.14.0a5%2B-6c982ae/bm-20250219-linux-x86_64-python-6c982aeb547528174f8b-3.14.0a5%2B-6c982ae-vs-3.12.6.md)[📈](results/bm-20250219-3.14.0a5%2B-6c982ae/bm-20250219-linux-x86_64-python-6c982aeb547528174f8b-3.14.0a5%2B-6c982ae-vs-3.12.6.svg) | 1.067x ↑<br>[📄](results/bm-20250219-3.14.0a5%2B-6c982ae/bm-20250219-linux-x86_64-python-6c982aeb547528174f8b-3.14.0a5%2B-6c982ae-vs-3.13.0rc2.md)[📈](results/bm-20250219-3.14.0a5%2B-6c982ae/bm-20250219-linux-x86_64-python-6c982aeb547528174f8b-3.14.0a5%2B-6c982ae-vs-3.13.0rc2.svg) |  |
| [2025-02-19](results/bm-20250219-3.14.0a5%2B-6c982ae-NOGIL) | python/6c982aeb547528174f8b | 6c982ae (NOGIL) | 1.024x ↓<br>[📄](results/bm-20250219-3.14.0a5%2B-6c982ae-NOGIL/bm-20250219-linux-x86_64-python-6c982aeb547528174f8b-3.14.0a5%2B-6c982ae-vs-3.12.6.md)[📈](results/bm-20250219-3.14.0a5%2B-6c982ae-NOGIL/bm-20250219-linux-x86_64-python-6c982aeb547528174f8b-3.14.0a5%2B-6c982ae-vs-3.12.6.svg) | 1.060x ↓<br>[📄](results/bm-20250219-3.14.0a5%2B-6c982ae-NOGIL/bm-20250219-linux-x86_64-python-6c982aeb547528174f8b-3.14.0a5%2B-6c982ae-vs-3.13.0rc2.md)[📈](results/bm-20250219-3.14.0a5%2B-6c982ae-NOGIL/bm-20250219-linux-x86_64-python-6c982aeb547528174f8b-3.14.0a5%2B-6c982ae-vs-3.13.0rc2.svg) | 1.118x ↓<br>[📄](results/bm-20250219-3.14.0a5%2B-6c982ae-NOGIL/bm-20250219-linux-x86_64-python-6c982aeb547528174f8b-3.14.0a5%2B-6c982ae-vs-base.md)[📈](results/bm-20250219-3.14.0a5%2B-6c982ae-NOGIL/bm-20250219-linux-x86_64-python-6c982aeb547528174f8b-3.14.0a5%2B-6c982ae-vs-base.svg)[🧠](results/bm-20250219-3.14.0a5%2B-6c982ae-NOGIL/bm-20250219-linux-x86_64-python-6c982aeb547528174f8b-3.14.0a5%2B-6c982ae-vs-base-mem.svg) |
| [2025-02-18](results/bm-20250218-3.14.0a5%2B-736ad66) | python/736ad664e0c3be05fad7 | 736ad66 | 1.110x ↑<br>[📄](results/bm-20250218-3.14.0a5%2B-736ad66/bm-20250218-linux-x86_64-python-736ad664e0c3be05fad7-3.14.0a5%2B-736ad66-vs-3.12.6.md)[📈](results/bm-20250218-3.14.0a5%2B-736ad66/bm-20250218-linux-x86_64-python-736ad664e0c3be05fad7-3.14.0a5%2B-736ad66-vs-3.12.6.svg) | 1.067x ↑<br>[📄](results/bm-20250218-3.14.0a5%2B-736ad66/bm-20250218-linux-x86_64-python-736ad664e0c3be05fad7-3.14.0a5%2B-736ad66-vs-3.13.0rc2.md)[📈](results/bm-20250218-3.14.0a5%2B-736ad66/bm-20250218-linux-x86_64-python-736ad664e0c3be05fad7-3.14.0a5%2B-736ad66-vs-3.13.0rc2.svg) |  |
| [2025-02-18](results/bm-20250218-3.14.0a5%2B-736ad66-NOGIL) | python/736ad664e0c3be05fad7 | 736ad66 (NOGIL) | 1.011x ↓<br>[📄](results/bm-20250218-3.14.0a5%2B-736ad66-NOGIL/bm-20250218-linux-x86_64-python-736ad664e0c3be05fad7-3.14.0a5%2B-736ad66-vs-3.12.6.md)[📈](results/bm-20250218-3.14.0a5%2B-736ad66-NOGIL/bm-20250218-linux-x86_64-python-736ad664e0c3be05fad7-3.14.0a5%2B-736ad66-vs-3.12.6.svg) | 1.048x ↓<br>[📄](results/bm-20250218-3.14.0a5%2B-736ad66-NOGIL/bm-20250218-linux-x86_64-python-736ad664e0c3be05fad7-3.14.0a5%2B-736ad66-vs-3.13.0rc2.md)[📈](results/bm-20250218-3.14.0a5%2B-736ad66-NOGIL/bm-20250218-linux-x86_64-python-736ad664e0c3be05fad7-3.14.0a5%2B-736ad66-vs-3.13.0rc2.svg) | 1.110x ↓<br>[📄](results/bm-20250218-3.14.0a5%2B-736ad66-NOGIL/bm-20250218-linux-x86_64-python-736ad664e0c3be05fad7-3.14.0a5%2B-736ad66-vs-base.md)[📈](results/bm-20250218-3.14.0a5%2B-736ad66-NOGIL/bm-20250218-linux-x86_64-python-736ad664e0c3be05fad7-3.14.0a5%2B-736ad66-vs-base.svg)[🧠](results/bm-20250218-3.14.0a5%2B-736ad66-NOGIL/bm-20250218-linux-x86_64-python-736ad664e0c3be05fad7-3.14.0a5%2B-736ad66-vs-base-mem.svg) |
| [2025-02-17](results/bm-20250217-3.14.0a5%2B-99d9656-NOGIL) | python/99d965635ae2ac4bffdc | 99d9656 (NOGIL) | 1.014x ↓<br>[📄](results/bm-20250217-3.14.0a5%2B-99d9656-NOGIL/bm-20250217-linux-x86_64-python-99d965635ae2ac4bffdc-3.14.0a5%2B-99d9656-vs-3.12.6.md)[📈](results/bm-20250217-3.14.0a5%2B-99d9656-NOGIL/bm-20250217-linux-x86_64-python-99d965635ae2ac4bffdc-3.14.0a5%2B-99d9656-vs-3.12.6.svg) | 1.051x ↓<br>[📄](results/bm-20250217-3.14.0a5%2B-99d9656-NOGIL/bm-20250217-linux-x86_64-python-99d965635ae2ac4bffdc-3.14.0a5%2B-99d9656-vs-3.13.0rc2.md)[📈](results/bm-20250217-3.14.0a5%2B-99d9656-NOGIL/bm-20250217-linux-x86_64-python-99d965635ae2ac4bffdc-3.14.0a5%2B-99d9656-vs-3.13.0rc2.svg) | 1.109x ↓<br>[📄](results/bm-20250217-3.14.0a5%2B-99d9656-NOGIL/bm-20250217-linux-x86_64-python-99d965635ae2ac4bffdc-3.14.0a5%2B-99d9656-vs-base.md)[📈](results/bm-20250217-3.14.0a5%2B-99d9656-NOGIL/bm-20250217-linux-x86_64-python-99d965635ae2ac4bffdc-3.14.0a5%2B-99d9656-vs-base.svg)[🧠](results/bm-20250217-3.14.0a5%2B-99d9656-NOGIL/bm-20250217-linux-x86_64-python-99d965635ae2ac4bffdc-3.14.0a5%2B-99d9656-vs-base-mem.svg) |
| [2025-02-17](results/bm-20250217-3.14.0a5%2B-99d9656) | python/99d965635ae2ac4bffdc | 99d9656 | 1.104x ↑<br>[📄](results/bm-20250217-3.14.0a5%2B-99d9656/bm-20250217-linux-x86_64-python-99d965635ae2ac4bffdc-3.14.0a5%2B-99d9656-vs-3.12.6.md)[📈](results/bm-20250217-3.14.0a5%2B-99d9656/bm-20250217-linux-x86_64-python-99d965635ae2ac4bffdc-3.14.0a5%2B-99d9656-vs-3.12.6.svg) | 1.062x ↑<br>[📄](results/bm-20250217-3.14.0a5%2B-99d9656/bm-20250217-linux-x86_64-python-99d965635ae2ac4bffdc-3.14.0a5%2B-99d9656-vs-3.13.0rc2.md)[📈](results/bm-20250217-3.14.0a5%2B-99d9656/bm-20250217-linux-x86_64-python-99d965635ae2ac4bffdc-3.14.0a5%2B-99d9656-vs-3.13.0rc2.svg) |  |
| [2025-02-17](results/bm-20250217-3.14.0a5%2B-cfe4103) | python/cfe41037eb5293a05184 | cfe4103 | 1.138x ↑<br>[📄](results/bm-20250217-3.14.0a5%2B-cfe4103/bm-20250217-linux-x86_64-python-cfe41037eb5293a05184-3.14.0a5%2B-cfe4103-vs-3.12.6.md)[📈](results/bm-20250217-3.14.0a5%2B-cfe4103/bm-20250217-linux-x86_64-python-cfe41037eb5293a05184-3.14.0a5%2B-cfe4103-vs-3.12.6.svg) | 1.093x ↑<br>[📄](results/bm-20250217-3.14.0a5%2B-cfe4103/bm-20250217-linux-x86_64-python-cfe41037eb5293a05184-3.14.0a5%2B-cfe4103-vs-3.13.0rc2.md)[📈](results/bm-20250217-3.14.0a5%2B-cfe4103/bm-20250217-linux-x86_64-python-cfe41037eb5293a05184-3.14.0a5%2B-cfe4103-vs-3.13.0rc2.svg) |  |
| [2025-02-17](results/bm-20250217-3.14.0a5%2B-cfe4103-NOGIL) | python/cfe41037eb5293a05184 | cfe4103 (NOGIL) | 1.021x ↓<br>[📄](results/bm-20250217-3.14.0a5%2B-cfe4103-NOGIL/bm-20250217-linux-x86_64-python-cfe41037eb5293a05184-3.14.0a5%2B-cfe4103-vs-3.12.6.md)[📈](results/bm-20250217-3.14.0a5%2B-cfe4103-NOGIL/bm-20250217-linux-x86_64-python-cfe41037eb5293a05184-3.14.0a5%2B-cfe4103-vs-3.12.6.svg) | 1.058x ↓<br>[📄](results/bm-20250217-3.14.0a5%2B-cfe4103-NOGIL/bm-20250217-linux-x86_64-python-cfe41037eb5293a05184-3.14.0a5%2B-cfe4103-vs-3.13.0rc2.md)[📈](results/bm-20250217-3.14.0a5%2B-cfe4103-NOGIL/bm-20250217-linux-x86_64-python-cfe41037eb5293a05184-3.14.0a5%2B-cfe4103-vs-3.13.0rc2.svg) | 1.137x ↓<br>[📄](results/bm-20250217-3.14.0a5%2B-cfe4103-NOGIL/bm-20250217-linux-x86_64-python-cfe41037eb5293a05184-3.14.0a5%2B-cfe4103-vs-base.md)[📈](results/bm-20250217-3.14.0a5%2B-cfe4103-NOGIL/bm-20250217-linux-x86_64-python-cfe41037eb5293a05184-3.14.0a5%2B-cfe4103-vs-base.svg)[🧠](results/bm-20250217-3.14.0a5%2B-cfe4103-NOGIL/bm-20250217-linux-x86_64-python-cfe41037eb5293a05184-3.14.0a5%2B-cfe4103-vs-base-mem.svg) |

## linux x86_64 (vultr)
| date | fork/ref | hash/flags | vs. 3.12.6: | vs. 3.13.0rc2: | vs. base: |
| --- | --- | --- | ---: | ---: | ---: |
| [2025-02-20](results/bm-20250220-3.14.0a5%2B-aa60561-NOGIL) | DinoV/local_type_cache | aa60561 (NOGIL) | 1.046x ↓<br>[📄](results/bm-20250220-3.14.0a5%2B-aa60561-NOGIL/bm-20250220-vultr-x86_64-DinoV-local_type_cache-3.14.0a5%2B-aa60561-vs-3.12.6.md)[📈](results/bm-20250220-3.14.0a5%2B-aa60561-NOGIL/bm-20250220-vultr-x86_64-DinoV-local_type_cache-3.14.0a5%2B-aa60561-vs-3.12.6.svg) | 1.078x ↓<br>[📄](results/bm-20250220-3.14.0a5%2B-aa60561-NOGIL/bm-20250220-vultr-x86_64-DinoV-local_type_cache-3.14.0a5%2B-aa60561-vs-3.13.0rc2.md)[📈](results/bm-20250220-3.14.0a5%2B-aa60561-NOGIL/bm-20250220-vultr-x86_64-DinoV-local_type_cache-3.14.0a5%2B-aa60561-vs-3.13.0rc2.svg) | 1.005x ↓<br>[📄](results/bm-20250220-3.14.0a5%2B-aa60561-NOGIL/bm-20250220-vultr-x86_64-DinoV-local_type_cache-3.14.0a5%2B-aa60561-vs-base.md)[📈](results/bm-20250220-3.14.0a5%2B-aa60561-NOGIL/bm-20250220-vultr-x86_64-DinoV-local_type_cache-3.14.0a5%2B-aa60561-vs-base.svg)[🧠](results/bm-20250220-3.14.0a5%2B-aa60561-NOGIL/bm-20250220-vultr-x86_64-DinoV-local_type_cache-3.14.0a5%2B-aa60561-vs-base-mem.svg) |
| [2025-02-19](results/bm-20250219-3.14.0a5%2B-6c982ae) | python/6c982aeb547528174f8b | 6c982ae | 1.091x ↑<br>[📄](results/bm-20250219-3.14.0a5%2B-6c982ae/bm-20250219-vultr-x86_64-python-6c982aeb547528174f8b-3.14.0a5%2B-6c982ae-vs-3.12.6.md)[📈](results/bm-20250219-3.14.0a5%2B-6c982ae/bm-20250219-vultr-x86_64-python-6c982aeb547528174f8b-3.14.0a5%2B-6c982ae-vs-3.12.6.svg) | 1.051x ↑<br>[📄](results/bm-20250219-3.14.0a5%2B-6c982ae/bm-20250219-vultr-x86_64-python-6c982aeb547528174f8b-3.14.0a5%2B-6c982ae-vs-3.13.0rc2.md)[📈](results/bm-20250219-3.14.0a5%2B-6c982ae/bm-20250219-vultr-x86_64-python-6c982aeb547528174f8b-3.14.0a5%2B-6c982ae-vs-3.13.0rc2.svg) |  |
| [2025-02-19](results/bm-20250219-3.14.0a5%2B-6c982ae-NOGIL) | python/6c982aeb547528174f8b | 6c982ae (NOGIL) | 1.040x ↓<br>[📄](results/bm-20250219-3.14.0a5%2B-6c982ae-NOGIL/bm-20250219-vultr-x86_64-python-6c982aeb547528174f8b-3.14.0a5%2B-6c982ae-vs-3.12.6.md)[📈](results/bm-20250219-3.14.0a5%2B-6c982ae-NOGIL/bm-20250219-vultr-x86_64-python-6c982aeb547528174f8b-3.14.0a5%2B-6c982ae-vs-3.12.6.svg) | 1.072x ↓<br>[📄](results/bm-20250219-3.14.0a5%2B-6c982ae-NOGIL/bm-20250219-vultr-x86_64-python-6c982aeb547528174f8b-3.14.0a5%2B-6c982ae-vs-3.13.0rc2.md)[📈](results/bm-20250219-3.14.0a5%2B-6c982ae-NOGIL/bm-20250219-vultr-x86_64-python-6c982aeb547528174f8b-3.14.0a5%2B-6c982ae-vs-3.13.0rc2.svg) | 1.001x ↑<br>[📄](results/bm-20250219-3.14.0a5%2B-6c982ae-NOGIL/bm-20250219-vultr-x86_64-python-6c982aeb547528174f8b-3.14.0a5%2B-6c982ae-vs-base.md)[📈](results/bm-20250219-3.14.0a5%2B-6c982ae-NOGIL/bm-20250219-vultr-x86_64-python-6c982aeb547528174f8b-3.14.0a5%2B-6c982ae-vs-base.svg)[🧠](results/bm-20250219-3.14.0a5%2B-6c982ae-NOGIL/bm-20250219-vultr-x86_64-python-6c982aeb547528174f8b-3.14.0a5%2B-6c982ae-vs-base-mem.svg) |
| [2025-02-19](results/bm-20250219-3.14.0a5%2B-7380186-NOGIL) | python/73801864d866c76ae26a | 7380186 (NOGIL) | 1.041x ↓<br>[📄](results/bm-20250219-3.14.0a5%2B-7380186-NOGIL/bm-20250219-vultr-x86_64-python-73801864d866c76ae26a-3.14.0a5%2B-7380186-vs-3.12.6.md)[📈](results/bm-20250219-3.14.0a5%2B-7380186-NOGIL/bm-20250219-vultr-x86_64-python-73801864d866c76ae26a-3.14.0a5%2B-7380186-vs-3.12.6.svg) | 1.074x ↓<br>[📄](results/bm-20250219-3.14.0a5%2B-7380186-NOGIL/bm-20250219-vultr-x86_64-python-73801864d866c76ae26a-3.14.0a5%2B-7380186-vs-3.13.0rc2.md)[📈](results/bm-20250219-3.14.0a5%2B-7380186-NOGIL/bm-20250219-vultr-x86_64-python-73801864d866c76ae26a-3.14.0a5%2B-7380186-vs-3.13.0rc2.svg) | 1.002x ↑<br>[📄](results/bm-20250219-3.14.0a5%2B-7380186-NOGIL/bm-20250219-vultr-x86_64-python-73801864d866c76ae26a-3.14.0a5%2B-7380186-vs-base.md)[📈](results/bm-20250219-3.14.0a5%2B-7380186-NOGIL/bm-20250219-vultr-x86_64-python-73801864d866c76ae26a-3.14.0a5%2B-7380186-vs-base.svg)[🧠](results/bm-20250219-3.14.0a5%2B-7380186-NOGIL/bm-20250219-vultr-x86_64-python-73801864d866c76ae26a-3.14.0a5%2B-7380186-vs-base-mem.svg) |
| [2025-02-19](results/bm-20250219-3.14.0a5%2B-08402c0-NOGIL) | mpage/load_fast_borrow_abs | 08402c0 (NOGIL) | 1.010x ↑<br>[📄](results/bm-20250219-3.14.0a5%2B-08402c0-NOGIL/bm-20250219-vultr-x86_64-mpage-load_fast_borrow_abs-3.14.0a5%2B-08402c0-vs-3.12.6.md)[📈](results/bm-20250219-3.14.0a5%2B-08402c0-NOGIL/bm-20250219-vultr-x86_64-mpage-load_fast_borrow_abs-3.14.0a5%2B-08402c0-vs-3.12.6.svg) | 1.024x ↓<br>[📄](results/bm-20250219-3.14.0a5%2B-08402c0-NOGIL/bm-20250219-vultr-x86_64-mpage-load_fast_borrow_abs-3.14.0a5%2B-08402c0-vs-3.13.0rc2.md)[📈](results/bm-20250219-3.14.0a5%2B-08402c0-NOGIL/bm-20250219-vultr-x86_64-mpage-load_fast_borrow_abs-3.14.0a5%2B-08402c0-vs-3.13.0rc2.svg) | 1.051x ↑<br>[📄](results/bm-20250219-3.14.0a5%2B-08402c0-NOGIL/bm-20250219-vultr-x86_64-mpage-load_fast_borrow_abs-3.14.0a5%2B-08402c0-vs-base.md)[📈](results/bm-20250219-3.14.0a5%2B-08402c0-NOGIL/bm-20250219-vultr-x86_64-mpage-load_fast_borrow_abs-3.14.0a5%2B-08402c0-vs-base.svg)[🧠](results/bm-20250219-3.14.0a5%2B-08402c0-NOGIL/bm-20250219-vultr-x86_64-mpage-load_fast_borrow_abs-3.14.0a5%2B-08402c0-vs-base-mem.svg) |
| [2025-02-19](results/bm-20250219-3.14.0a5%2B-32a747e-NOGIL) | DinoV/local_type_cache | 32a747e (NOGIL) | 1.043x ↓<br>[📄](results/bm-20250219-3.14.0a5%2B-32a747e-NOGIL/bm-20250219-vultr-x86_64-DinoV-local_type_cache-3.14.0a5%2B-32a747e-vs-3.12.6.md)[📈](results/bm-20250219-3.14.0a5%2B-32a747e-NOGIL/bm-20250219-vultr-x86_64-DinoV-local_type_cache-3.14.0a5%2B-32a747e-vs-3.12.6.svg) | 1.075x ↓<br>[📄](results/bm-20250219-3.14.0a5%2B-32a747e-NOGIL/bm-20250219-vultr-x86_64-DinoV-local_type_cache-3.14.0a5%2B-32a747e-vs-3.13.0rc2.md)[📈](results/bm-20250219-3.14.0a5%2B-32a747e-NOGIL/bm-20250219-vultr-x86_64-DinoV-local_type_cache-3.14.0a5%2B-32a747e-vs-3.13.0rc2.svg) | 1.001x ↓<br>[📄](results/bm-20250219-3.14.0a5%2B-32a747e-NOGIL/bm-20250219-vultr-x86_64-DinoV-local_type_cache-3.14.0a5%2B-32a747e-vs-base.md)[📈](results/bm-20250219-3.14.0a5%2B-32a747e-NOGIL/bm-20250219-vultr-x86_64-DinoV-local_type_cache-3.14.0a5%2B-32a747e-vs-base.svg)[🧠](results/bm-20250219-3.14.0a5%2B-32a747e-NOGIL/bm-20250219-vultr-x86_64-DinoV-local_type_cache-3.14.0a5%2B-32a747e-vs-base-mem.svg) |
| [2025-02-19](results/bm-20250219-3.14.0a5%2B-ccf1732-NOGIL) | python/ccf17323c218a2fdcf7f | ccf1732 (NOGIL) | 1.044x ↓<br>[📄](results/bm-20250219-3.14.0a5%2B-ccf1732-NOGIL/bm-20250219-vultr-x86_64-python-ccf17323c218a2fdcf7f-3.14.0a5%2B-ccf1732-vs-3.12.6.md)[📈](results/bm-20250219-3.14.0a5%2B-ccf1732-NOGIL/bm-20250219-vultr-x86_64-python-ccf17323c218a2fdcf7f-3.14.0a5%2B-ccf1732-vs-3.12.6.svg) | 1.076x ↓<br>[📄](results/bm-20250219-3.14.0a5%2B-ccf1732-NOGIL/bm-20250219-vultr-x86_64-python-ccf17323c218a2fdcf7f-3.14.0a5%2B-ccf1732-vs-3.13.0rc2.md)[📈](results/bm-20250219-3.14.0a5%2B-ccf1732-NOGIL/bm-20250219-vultr-x86_64-python-ccf17323c218a2fdcf7f-3.14.0a5%2B-ccf1732-vs-3.13.0rc2.svg) |  |
| [2025-02-19](results/bm-20250219-3.14.0a5%2B-6a1fe7e-NOGIL) | DinoV/nolock_loadattr_with | 6a1fe7e (NOGIL) | 1.039x ↓<br>[📄](results/bm-20250219-3.14.0a5%2B-6a1fe7e-NOGIL/bm-20250219-vultr-x86_64-DinoV-nolock_loadattr_with-3.14.0a5%2B-6a1fe7e-vs-3.12.6.md)[📈](results/bm-20250219-3.14.0a5%2B-6a1fe7e-NOGIL/bm-20250219-vultr-x86_64-DinoV-nolock_loadattr_with-3.14.0a5%2B-6a1fe7e-vs-3.12.6.svg) | 1.071x ↓<br>[📄](results/bm-20250219-3.14.0a5%2B-6a1fe7e-NOGIL/bm-20250219-vultr-x86_64-DinoV-nolock_loadattr_with-3.14.0a5%2B-6a1fe7e-vs-3.13.0rc2.md)[📈](results/bm-20250219-3.14.0a5%2B-6a1fe7e-NOGIL/bm-20250219-vultr-x86_64-DinoV-nolock_loadattr_with-3.14.0a5%2B-6a1fe7e-vs-3.13.0rc2.svg) | 1.004x ↑<br>[📄](results/bm-20250219-3.14.0a5%2B-6a1fe7e-NOGIL/bm-20250219-vultr-x86_64-DinoV-nolock_loadattr_with-3.14.0a5%2B-6a1fe7e-vs-base.md)[📈](results/bm-20250219-3.14.0a5%2B-6a1fe7e-NOGIL/bm-20250219-vultr-x86_64-DinoV-nolock_loadattr_with-3.14.0a5%2B-6a1fe7e-vs-base.svg)[🧠](results/bm-20250219-3.14.0a5%2B-6a1fe7e-NOGIL/bm-20250219-vultr-x86_64-DinoV-nolock_loadattr_with-3.14.0a5%2B-6a1fe7e-vs-base-mem.svg) |
| [2025-02-19](results/bm-20250219-3.14.0a5%2B-427c122-NOGIL) | DinoV/nolock_map | 427c122 (NOGIL) | 1.042x ↓<br>[📄](results/bm-20250219-3.14.0a5%2B-427c122-NOGIL/bm-20250219-vultr-x86_64-DinoV-nolock_map-3.14.0a5%2B-427c122-vs-3.12.6.md)[📈](results/bm-20250219-3.14.0a5%2B-427c122-NOGIL/bm-20250219-vultr-x86_64-DinoV-nolock_map-3.14.0a5%2B-427c122-vs-3.12.6.svg) | 1.074x ↓<br>[📄](results/bm-20250219-3.14.0a5%2B-427c122-NOGIL/bm-20250219-vultr-x86_64-DinoV-nolock_map-3.14.0a5%2B-427c122-vs-3.13.0rc2.md)[📈](results/bm-20250219-3.14.0a5%2B-427c122-NOGIL/bm-20250219-vultr-x86_64-DinoV-nolock_map-3.14.0a5%2B-427c122-vs-3.13.0rc2.svg) | 1.001x ↑<br>[📄](results/bm-20250219-3.14.0a5%2B-427c122-NOGIL/bm-20250219-vultr-x86_64-DinoV-nolock_map-3.14.0a5%2B-427c122-vs-base.md)[📈](results/bm-20250219-3.14.0a5%2B-427c122-NOGIL/bm-20250219-vultr-x86_64-DinoV-nolock_map-3.14.0a5%2B-427c122-vs-base.svg)[🧠](results/bm-20250219-3.14.0a5%2B-427c122-NOGIL/bm-20250219-vultr-x86_64-DinoV-nolock_map-3.14.0a5%2B-427c122-vs-base-mem.svg) |
| [2025-02-19](results/bm-20250219-3.14.0a5%2B-dba89e0-NOGIL) | nascheme/gh_128384_warnings_c | dba89e0 (NOGIL) | 1.049x ↓<br>[📄](results/bm-20250219-3.14.0a5%2B-dba89e0-NOGIL/bm-20250219-vultr-x86_64-nascheme-gh_128384_warnings_c-3.14.0a5%2B-dba89e0-vs-3.12.6.md)[📈](results/bm-20250219-3.14.0a5%2B-dba89e0-NOGIL/bm-20250219-vultr-x86_64-nascheme-gh_128384_warnings_c-3.14.0a5%2B-dba89e0-vs-3.12.6.svg) | 1.081x ↓<br>[📄](results/bm-20250219-3.14.0a5%2B-dba89e0-NOGIL/bm-20250219-vultr-x86_64-nascheme-gh_128384_warnings_c-3.14.0a5%2B-dba89e0-vs-3.13.0rc2.md)[📈](results/bm-20250219-3.14.0a5%2B-dba89e0-NOGIL/bm-20250219-vultr-x86_64-nascheme-gh_128384_warnings_c-3.14.0a5%2B-dba89e0-vs-3.13.0rc2.svg) | 1.002x ↓<br>[📄](results/bm-20250219-3.14.0a5%2B-dba89e0-NOGIL/bm-20250219-vultr-x86_64-nascheme-gh_128384_warnings_c-3.14.0a5%2B-dba89e0-vs-base.md)[📈](results/bm-20250219-3.14.0a5%2B-dba89e0-NOGIL/bm-20250219-vultr-x86_64-nascheme-gh_128384_warnings_c-3.14.0a5%2B-dba89e0-vs-base.svg)[🧠](results/bm-20250219-3.14.0a5%2B-dba89e0-NOGIL/bm-20250219-vultr-x86_64-nascheme-gh_128384_warnings_c-3.14.0a5%2B-dba89e0-vs-base-mem.svg) |
| [2025-02-19](results/bm-20250219-3.14.0a5%2B-e7db011-NOGIL) | DinoV/local_type_cache | e7db011 (NOGIL) | 1.049x ↓<br>[📄](results/bm-20250219-3.14.0a5%2B-e7db011-NOGIL/bm-20250219-vultr-x86_64-DinoV-local_type_cache-3.14.0a5%2B-e7db011-vs-3.12.6.md)[📈](results/bm-20250219-3.14.0a5%2B-e7db011-NOGIL/bm-20250219-vultr-x86_64-DinoV-local_type_cache-3.14.0a5%2B-e7db011-vs-3.12.6.svg) | 1.081x ↓<br>[📄](results/bm-20250219-3.14.0a5%2B-e7db011-NOGIL/bm-20250219-vultr-x86_64-DinoV-local_type_cache-3.14.0a5%2B-e7db011-vs-3.13.0rc2.md)[📈](results/bm-20250219-3.14.0a5%2B-e7db011-NOGIL/bm-20250219-vultr-x86_64-DinoV-local_type_cache-3.14.0a5%2B-e7db011-vs-3.13.0rc2.svg) | 1.003x ↓<br>[📄](results/bm-20250219-3.14.0a5%2B-e7db011-NOGIL/bm-20250219-vultr-x86_64-DinoV-local_type_cache-3.14.0a5%2B-e7db011-vs-base.md)[📈](results/bm-20250219-3.14.0a5%2B-e7db011-NOGIL/bm-20250219-vultr-x86_64-DinoV-local_type_cache-3.14.0a5%2B-e7db011-vs-base.svg)[🧠](results/bm-20250219-3.14.0a5%2B-e7db011-NOGIL/bm-20250219-vultr-x86_64-DinoV-local_type_cache-3.14.0a5%2B-e7db011-vs-base-mem.svg) |
| [2025-02-18](results/bm-20250218-3.14.0a5%2B-736ad66) | python/736ad664e0c3be05fad7 | 736ad66 | 1.082x ↑<br>[📄](results/bm-20250218-3.14.0a5%2B-736ad66/bm-20250218-vultr-x86_64-python-736ad664e0c3be05fad7-3.14.0a5%2B-736ad66-vs-3.12.6.md)[📈](results/bm-20250218-3.14.0a5%2B-736ad66/bm-20250218-vultr-x86_64-python-736ad664e0c3be05fad7-3.14.0a5%2B-736ad66-vs-3.12.6.svg) | 1.042x ↑<br>[📄](results/bm-20250218-3.14.0a5%2B-736ad66/bm-20250218-vultr-x86_64-python-736ad664e0c3be05fad7-3.14.0a5%2B-736ad66-vs-3.13.0rc2.md)[📈](results/bm-20250218-3.14.0a5%2B-736ad66/bm-20250218-vultr-x86_64-python-736ad664e0c3be05fad7-3.14.0a5%2B-736ad66-vs-3.13.0rc2.svg) |  |
| [2025-02-18](results/bm-20250218-3.14.0a5%2B-736ad66-NOGIL) | python/736ad664e0c3be05fad7 | 736ad66 (NOGIL) | 1.046x ↓<br>[📄](results/bm-20250218-3.14.0a5%2B-736ad66-NOGIL/bm-20250218-vultr-x86_64-python-736ad664e0c3be05fad7-3.14.0a5%2B-736ad66-vs-3.12.6.md)[📈](results/bm-20250218-3.14.0a5%2B-736ad66-NOGIL/bm-20250218-vultr-x86_64-python-736ad664e0c3be05fad7-3.14.0a5%2B-736ad66-vs-3.12.6.svg) | 1.078x ↓<br>[📄](results/bm-20250218-3.14.0a5%2B-736ad66-NOGIL/bm-20250218-vultr-x86_64-python-736ad664e0c3be05fad7-3.14.0a5%2B-736ad66-vs-3.13.0rc2.md)[📈](results/bm-20250218-3.14.0a5%2B-736ad66-NOGIL/bm-20250218-vultr-x86_64-python-736ad664e0c3be05fad7-3.14.0a5%2B-736ad66-vs-3.13.0rc2.svg) | 1.119x ↓<br>[📄](results/bm-20250218-3.14.0a5%2B-736ad66-NOGIL/bm-20250218-vultr-x86_64-python-736ad664e0c3be05fad7-3.14.0a5%2B-736ad66-vs-base.md)[📈](results/bm-20250218-3.14.0a5%2B-736ad66-NOGIL/bm-20250218-vultr-x86_64-python-736ad664e0c3be05fad7-3.14.0a5%2B-736ad66-vs-base.svg)[🧠](results/bm-20250218-3.14.0a5%2B-736ad66-NOGIL/bm-20250218-vultr-x86_64-python-736ad664e0c3be05fad7-3.14.0a5%2B-736ad66-vs-base-mem.svg) |
| [2025-02-18](results/bm-20250218-3.14.0a5%2B-bcc9a5d-NOGIL) | python/bcc9a5dddb777c8195b5 | bcc9a5d (NOGIL) | 1.046x ↓<br>[📄](results/bm-20250218-3.14.0a5%2B-bcc9a5d-NOGIL/bm-20250218-vultr-x86_64-python-bcc9a5dddb777c8195b5-3.14.0a5%2B-bcc9a5d-vs-3.12.6.md)[📈](results/bm-20250218-3.14.0a5%2B-bcc9a5d-NOGIL/bm-20250218-vultr-x86_64-python-bcc9a5dddb777c8195b5-3.14.0a5%2B-bcc9a5d-vs-3.12.6.svg) | 1.078x ↓<br>[📄](results/bm-20250218-3.14.0a5%2B-bcc9a5d-NOGIL/bm-20250218-vultr-x86_64-python-bcc9a5dddb777c8195b5-3.14.0a5%2B-bcc9a5d-vs-3.13.0rc2.md)[📈](results/bm-20250218-3.14.0a5%2B-bcc9a5d-NOGIL/bm-20250218-vultr-x86_64-python-bcc9a5dddb777c8195b5-3.14.0a5%2B-bcc9a5d-vs-3.13.0rc2.svg) |  |
| [2025-02-18](results/bm-20250218-3.14.0a5%2B-d72f499-NOGIL) | DinoV/local_type_cache | d72f499 (NOGIL) | 1.055x ↓<br>[📄](results/bm-20250218-3.14.0a5%2B-d72f499-NOGIL/bm-20250218-vultr-x86_64-DinoV-local_type_cache-3.14.0a5%2B-d72f499-vs-3.12.6.md)[📈](results/bm-20250218-3.14.0a5%2B-d72f499-NOGIL/bm-20250218-vultr-x86_64-DinoV-local_type_cache-3.14.0a5%2B-d72f499-vs-3.12.6.svg) | 1.086x ↓<br>[📄](results/bm-20250218-3.14.0a5%2B-d72f499-NOGIL/bm-20250218-vultr-x86_64-DinoV-local_type_cache-3.14.0a5%2B-d72f499-vs-3.13.0rc2.md)[📈](results/bm-20250218-3.14.0a5%2B-d72f499-NOGIL/bm-20250218-vultr-x86_64-DinoV-local_type_cache-3.14.0a5%2B-d72f499-vs-3.13.0rc2.svg) | 1.009x ↓<br>[📄](results/bm-20250218-3.14.0a5%2B-d72f499-NOGIL/bm-20250218-vultr-x86_64-DinoV-local_type_cache-3.14.0a5%2B-d72f499-vs-base.md)[📈](results/bm-20250218-3.14.0a5%2B-d72f499-NOGIL/bm-20250218-vultr-x86_64-DinoV-local_type_cache-3.14.0a5%2B-d72f499-vs-base.svg)[🧠](results/bm-20250218-3.14.0a5%2B-d72f499-NOGIL/bm-20250218-vultr-x86_64-DinoV-local_type_cache-3.14.0a5%2B-d72f499-vs-base-mem.svg) |
| [2025-02-18](results/bm-20250218-3.14.0a5%2B-ab974f8-NOGIL) | DinoV/local_type_cache | ab974f8 (NOGIL) | 1.053x ↓<br>[📄](results/bm-20250218-3.14.0a5%2B-ab974f8-NOGIL/bm-20250218-vultr-x86_64-DinoV-local_type_cache-3.14.0a5%2B-ab974f8-vs-3.12.6.md)[📈](results/bm-20250218-3.14.0a5%2B-ab974f8-NOGIL/bm-20250218-vultr-x86_64-DinoV-local_type_cache-3.14.0a5%2B-ab974f8-vs-3.12.6.svg) | 1.084x ↓<br>[📄](results/bm-20250218-3.14.0a5%2B-ab974f8-NOGIL/bm-20250218-vultr-x86_64-DinoV-local_type_cache-3.14.0a5%2B-ab974f8-vs-3.13.0rc2.md)[📈](results/bm-20250218-3.14.0a5%2B-ab974f8-NOGIL/bm-20250218-vultr-x86_64-DinoV-local_type_cache-3.14.0a5%2B-ab974f8-vs-3.13.0rc2.svg) | 1.006x ↓<br>[📄](results/bm-20250218-3.14.0a5%2B-ab974f8-NOGIL/bm-20250218-vultr-x86_64-DinoV-local_type_cache-3.14.0a5%2B-ab974f8-vs-base.md)[📈](results/bm-20250218-3.14.0a5%2B-ab974f8-NOGIL/bm-20250218-vultr-x86_64-DinoV-local_type_cache-3.14.0a5%2B-ab974f8-vs-base.svg)[🧠](results/bm-20250218-3.14.0a5%2B-ab974f8-NOGIL/bm-20250218-vultr-x86_64-DinoV-local_type_cache-3.14.0a5%2B-ab974f8-vs-base-mem.svg) |
| [2025-02-17](results/bm-20250217-3.14.0a5%2B-99d9656-NOGIL) | python/99d965635ae2ac4bffdc | 99d9656 (NOGIL) | 1.048x ↓<br>[📄](results/bm-20250217-3.14.0a5%2B-99d9656-NOGIL/bm-20250217-vultr-x86_64-python-99d965635ae2ac4bffdc-3.14.0a5%2B-99d9656-vs-3.12.6.md)[📈](results/bm-20250217-3.14.0a5%2B-99d9656-NOGIL/bm-20250217-vultr-x86_64-python-99d965635ae2ac4bffdc-3.14.0a5%2B-99d9656-vs-3.12.6.svg) | 1.080x ↓<br>[📄](results/bm-20250217-3.14.0a5%2B-99d9656-NOGIL/bm-20250217-vultr-x86_64-python-99d965635ae2ac4bffdc-3.14.0a5%2B-99d9656-vs-3.13.0rc2.md)[📈](results/bm-20250217-3.14.0a5%2B-99d9656-NOGIL/bm-20250217-vultr-x86_64-python-99d965635ae2ac4bffdc-3.14.0a5%2B-99d9656-vs-3.13.0rc2.svg) | 1.126x ↓<br>[📄](results/bm-20250217-3.14.0a5%2B-99d9656-NOGIL/bm-20250217-vultr-x86_64-python-99d965635ae2ac4bffdc-3.14.0a5%2B-99d9656-vs-base.md)[📈](results/bm-20250217-3.14.0a5%2B-99d9656-NOGIL/bm-20250217-vultr-x86_64-python-99d965635ae2ac4bffdc-3.14.0a5%2B-99d9656-vs-base.svg)[🧠](results/bm-20250217-3.14.0a5%2B-99d9656-NOGIL/bm-20250217-vultr-x86_64-python-99d965635ae2ac4bffdc-3.14.0a5%2B-99d9656-vs-base-mem.svg) |
| [2025-02-17](results/bm-20250217-3.14.0a5%2B-99d9656) | python/99d965635ae2ac4bffdc | 99d9656 | 1.088x ↑<br>[📄](results/bm-20250217-3.14.0a5%2B-99d9656/bm-20250217-vultr-x86_64-python-99d965635ae2ac4bffdc-3.14.0a5%2B-99d9656-vs-3.12.6.md)[📈](results/bm-20250217-3.14.0a5%2B-99d9656/bm-20250217-vultr-x86_64-python-99d965635ae2ac4bffdc-3.14.0a5%2B-99d9656-vs-3.12.6.svg) | 1.048x ↑<br>[📄](results/bm-20250217-3.14.0a5%2B-99d9656/bm-20250217-vultr-x86_64-python-99d965635ae2ac4bffdc-3.14.0a5%2B-99d9656-vs-3.13.0rc2.md)[📈](results/bm-20250217-3.14.0a5%2B-99d9656/bm-20250217-vultr-x86_64-python-99d965635ae2ac4bffdc-3.14.0a5%2B-99d9656-vs-3.13.0rc2.svg) |  |
| [2025-02-17](results/bm-20250217-3.14.0a5%2B-c3669ca-NOGIL) | DinoV/local_type_cache | c3669ca (NOGIL) | 1.061x ↓<br>[📄](results/bm-20250217-3.14.0a5%2B-c3669ca-NOGIL/bm-20250217-vultr-x86_64-DinoV-local_type_cache-3.14.0a5%2B-c3669ca-vs-3.12.6.md)[📈](results/bm-20250217-3.14.0a5%2B-c3669ca-NOGIL/bm-20250217-vultr-x86_64-DinoV-local_type_cache-3.14.0a5%2B-c3669ca-vs-3.12.6.svg) | 1.093x ↓<br>[📄](results/bm-20250217-3.14.0a5%2B-c3669ca-NOGIL/bm-20250217-vultr-x86_64-DinoV-local_type_cache-3.14.0a5%2B-c3669ca-vs-3.13.0rc2.md)[📈](results/bm-20250217-3.14.0a5%2B-c3669ca-NOGIL/bm-20250217-vultr-x86_64-DinoV-local_type_cache-3.14.0a5%2B-c3669ca-vs-3.13.0rc2.svg) | 1.014x ↓<br>[📄](results/bm-20250217-3.14.0a5%2B-c3669ca-NOGIL/bm-20250217-vultr-x86_64-DinoV-local_type_cache-3.14.0a5%2B-c3669ca-vs-base.md)[📈](results/bm-20250217-3.14.0a5%2B-c3669ca-NOGIL/bm-20250217-vultr-x86_64-DinoV-local_type_cache-3.14.0a5%2B-c3669ca-vs-base.svg)[🧠](results/bm-20250217-3.14.0a5%2B-c3669ca-NOGIL/bm-20250217-vultr-x86_64-DinoV-local_type_cache-3.14.0a5%2B-c3669ca-vs-base-mem.svg) |
| [2025-02-17](results/bm-20250217-3.14.0a5%2B-cfe4103) | python/cfe41037eb5293a05184 | cfe4103 | 1.092x ↑<br>[📄](results/bm-20250217-3.14.0a5%2B-cfe4103/bm-20250217-vultr-x86_64-python-cfe41037eb5293a05184-3.14.0a5%2B-cfe4103-vs-3.12.6.md)[📈](results/bm-20250217-3.14.0a5%2B-cfe4103/bm-20250217-vultr-x86_64-python-cfe41037eb5293a05184-3.14.0a5%2B-cfe4103-vs-3.12.6.svg) | 1.052x ↑<br>[📄](results/bm-20250217-3.14.0a5%2B-cfe4103/bm-20250217-vultr-x86_64-python-cfe41037eb5293a05184-3.14.0a5%2B-cfe4103-vs-3.13.0rc2.md)[📈](results/bm-20250217-3.14.0a5%2B-cfe4103/bm-20250217-vultr-x86_64-python-cfe41037eb5293a05184-3.14.0a5%2B-cfe4103-vs-3.13.0rc2.svg) |  |
| [2025-02-17](results/bm-20250217-3.14.0a5%2B-cfe4103-NOGIL) | python/cfe41037eb5293a05184 | cfe4103 (NOGIL) | 1.047x ↓<br>[📄](results/bm-20250217-3.14.0a5%2B-cfe4103-NOGIL/bm-20250217-vultr-x86_64-python-cfe41037eb5293a05184-3.14.0a5%2B-cfe4103-vs-3.12.6.md)[📈](results/bm-20250217-3.14.0a5%2B-cfe4103-NOGIL/bm-20250217-vultr-x86_64-python-cfe41037eb5293a05184-3.14.0a5%2B-cfe4103-vs-3.12.6.svg) | 1.079x ↓<br>[📄](results/bm-20250217-3.14.0a5%2B-cfe4103-NOGIL/bm-20250217-vultr-x86_64-python-cfe41037eb5293a05184-3.14.0a5%2B-cfe4103-vs-3.13.0rc2.md)[📈](results/bm-20250217-3.14.0a5%2B-cfe4103-NOGIL/bm-20250217-vultr-x86_64-python-cfe41037eb5293a05184-3.14.0a5%2B-cfe4103-vs-3.13.0rc2.svg) | 1.128x ↓<br>[📄](results/bm-20250217-3.14.0a5%2B-cfe4103-NOGIL/bm-20250217-vultr-x86_64-python-cfe41037eb5293a05184-3.14.0a5%2B-cfe4103-vs-base.md)[📈](results/bm-20250217-3.14.0a5%2B-cfe4103-NOGIL/bm-20250217-vultr-x86_64-python-cfe41037eb5293a05184-3.14.0a5%2B-cfe4103-vs-base.svg)[🧠](results/bm-20250217-3.14.0a5%2B-cfe4103-NOGIL/bm-20250217-vultr-x86_64-python-cfe41037eb5293a05184-3.14.0a5%2B-cfe4103-vs-base-mem.svg) |
| [2025-02-11](results/bm-20250211-3.14.0a5%2B-a7427f2-NOGIL) | python/a7427f2db937adb4c787 | a7427f2 (NOGIL) | 1.047x ↓<br>[📄](results/bm-20250211-3.14.0a5%2B-a7427f2-NOGIL/bm-20250211-vultr-x86_64-python-a7427f2db937adb4c787-3.14.0a5%2B-a7427f2-vs-3.12.6.md)[📈](results/bm-20250211-3.14.0a5%2B-a7427f2-NOGIL/bm-20250211-vultr-x86_64-python-a7427f2db937adb4c787-3.14.0a5%2B-a7427f2-vs-3.12.6.svg) | 1.079x ↓<br>[📄](results/bm-20250211-3.14.0a5%2B-a7427f2-NOGIL/bm-20250211-vultr-x86_64-python-a7427f2db937adb4c787-3.14.0a5%2B-a7427f2-vs-3.13.0rc2.md)[📈](results/bm-20250211-3.14.0a5%2B-a7427f2-NOGIL/bm-20250211-vultr-x86_64-python-a7427f2db937adb4c787-3.14.0a5%2B-a7427f2-vs-3.13.0rc2.svg) |  |


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
