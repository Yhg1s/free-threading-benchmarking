# Results

- fork: nascheme/pgo_benchmark_task
- version: 3.14.0a5+
- config: NOGIL
- commit hash: [8dd8862](https://github.com/nascheme/cpython/commit/8dd8862)
- commit date: 2025-02-28T10:31:26-08:00
- commit merge base: [9e474a98af4184615540467dea16da05f4d284d8](https://github.com/python/cpython/commit/9e474a98af4184615540467dea16da05f4d284d8)
- ref: pgo_benchmark_task

## linux x86_64 (vultr)

- [GitHub Action run](https://github.com/facebookexperimental/free-threading-benchmarking/actions/runs/13594409843)
- cpu model: Intel(R) Xeon(R) E-2286G CPU @ 4.00GHz
- platform: Linux-6.8.0-51-generic-x86_64-with-glibc2.39
- [raw results](bm-20250228-vultr-x86_64-nascheme-pgo_benchmark_task-3.14.0a5%2B-8dd8862.json)

### vs. 3.12.6

- Geometric mean: 1.039x slower (HPT: reliability of 99.95%, 1.03x slower at 99th %ile)
- Memory usage: 1.35x
- missing benchmarks: aiohttp, asyncio_tcp, asyncio_tcp_ssl, chameleon, dask, flaskblogging, gunicorn, mypy2, pickle, pickle_dict, pickle_list, tornado_http, unpack_sequence, unpickle, unpickle_list
- new benchmarks: connected_components, k_core, many_optionals, shortest_path, sphinx, subparsers
- [📄table](bm-20250228-vultr-x86_64-nascheme-pgo_benchmark_task-3.14.0a5%2B-8dd8862-vs-3.12.6.md)
- [📈time plot](bm-20250228-vultr-x86_64-nascheme-pgo_benchmark_task-3.14.0a5%2B-8dd8862-vs-3.12.6.svg)

### vs. 3.13.0rc2

- Geometric mean: 1.071x slower (HPT: reliability of 99.97%, 1.03x slower at 99th %ile)
- Memory usage: 1.34x
- missing benchmarks: aiohttp, asyncio_tcp, asyncio_tcp_ssl, chameleon, dask, flaskblogging, gunicorn, pickle, pickle_dict, pickle_list, tornado_http, unpack_sequence, unpickle, unpickle_list
- new benchmarks: connected_components, k_core, many_optionals, shortest_path, sphinx, sqlalchemy_declarative, sqlalchemy_imperative, subparsers
- [📄table](bm-20250228-vultr-x86_64-nascheme-pgo_benchmark_task-3.14.0a5%2B-8dd8862-vs-3.13.0rc2.md)
- [📈time plot](bm-20250228-vultr-x86_64-nascheme-pgo_benchmark_task-3.14.0a5%2B-8dd8862-vs-3.13.0rc2.svg)

### vs. base

- Geometric mean: 1.008x faster (HPT: reliability of 74.60%, 1.00x slower at 99th %ile)
- Memory usage: 0.99x
- [🧠memory plot](bm-20250228-vultr-x86_64-nascheme-pgo_benchmark_task-3.14.0a5%2B-8dd8862-vs-base-mem.svg)
- [📄table](bm-20250228-vultr-x86_64-nascheme-pgo_benchmark_task-3.14.0a5%2B-8dd8862-vs-base.md)
- [📈time plot](bm-20250228-vultr-x86_64-nascheme-pgo_benchmark_task-3.14.0a5%2B-8dd8862-vs-base.svg)

### vs. default_base_vs_NOGIL

- Geometric mean: 1.124x slower (HPT: reliability of 100.00%, 1.12x slower at 99th %ile)
- Memory usage: 1.20x
- new benchmarks: html5lib
- [📄table](bm-20250228-vultr-x86_64-nascheme-pgo_benchmark_task-3.14.0a5%2B-8dd8862-vs-default_base_vs_NOGIL.md)
- [📈time plot](bm-20250228-vultr-x86_64-nascheme-pgo_benchmark_task-3.14.0a5%2B-8dd8862-vs-default_base_vs_NOGIL.svg)

