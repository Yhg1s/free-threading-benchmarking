# Results

- fork: mpage/load_fast_borrow
- version: 3.14.0a4+
- config: NOGIL
- commit hash: [b0fcd85](https://github.com/mpage/cpython/commit/b0fcd85)
- commit date: 2025-02-06T16:44:50-08:00
- commit merge base: [e41ec8e18b078024b02a742272e675ae39778536](https://github.com/python/cpython/commit/e41ec8e18b078024b02a742272e675ae39778536)
- ref: load_fast_borrow

## linux x86_64 (vultr)

- [GitHub Action run](https://github.com/facebookexperimental/free-threading-benchmarking/actions/runs/13190788783)
- cpu model: Intel(R) Xeon(R) E-2286G CPU @ 4.00GHz
- platform: Linux-6.8.0-51-generic-x86_64-with-glibc2.39
- [raw results](bm-20250206-vultr-x86_64-mpage-load_fast_borrow-3.14.0a4%2B-b0fcd85.json)

### vs. 3.12.6

- Geometric mean: 1.038x slower (HPT: reliability of 99.95%, 1.02x slower at 99th %ile)
- Memory usage: 1.35x
- missing benchmarks: aiohttp, asyncio_tcp, asyncio_tcp_ssl, chameleon, dask, flaskblogging, gunicorn, mypy2, pickle, pickle_dict, pickle_list, tornado_http, unpack_sequence, unpickle, unpickle_list
- new benchmarks: connected_components, k_core, many_optionals, shortest_path, sphinx, subparsers
- [📄table](bm-20250206-vultr-x86_64-mpage-load_fast_borrow-3.14.0a4%2B-b0fcd85-vs-3.12.6.md)
- [📈time plot](bm-20250206-vultr-x86_64-mpage-load_fast_borrow-3.14.0a4%2B-b0fcd85-vs-3.12.6.svg)

### vs. 3.13.0rc2

- Geometric mean: 1.069x slower (HPT: reliability of 99.97%, 1.04x slower at 99th %ile)
- Memory usage: 1.34x
- missing benchmarks: aiohttp, asyncio_tcp, asyncio_tcp_ssl, chameleon, dask, flaskblogging, gunicorn, pickle, pickle_dict, pickle_list, tornado_http, unpack_sequence, unpickle, unpickle_list
- new benchmarks: connected_components, k_core, many_optionals, shortest_path, sphinx, sqlalchemy_declarative, sqlalchemy_imperative, subparsers
- [📄table](bm-20250206-vultr-x86_64-mpage-load_fast_borrow-3.14.0a4%2B-b0fcd85-vs-3.13.0rc2.md)
- [📈time plot](bm-20250206-vultr-x86_64-mpage-load_fast_borrow-3.14.0a4%2B-b0fcd85-vs-3.13.0rc2.svg)

### vs. base

- Geometric mean: 1.012x faster (HPT: reliability of 100.00%, 1.00x faster at 99th %ile)
- Memory usage: 1.01x
- [🧠memory plot](bm-20250206-vultr-x86_64-mpage-load_fast_borrow-3.14.0a4%2B-b0fcd85-vs-base-mem.svg)
- [📄table](bm-20250206-vultr-x86_64-mpage-load_fast_borrow-3.14.0a4%2B-b0fcd85-vs-base.md)
- [📈time plot](bm-20250206-vultr-x86_64-mpage-load_fast_borrow-3.14.0a4%2B-b0fcd85-vs-base.svg)

### vs. default_base_vs_NOGIL

- Geometric mean: 1.121x slower (HPT: reliability of 100.00%, 1.11x slower at 99th %ile)
- Memory usage: 1.20x
- new benchmarks: html5lib
- [📄table](bm-20250206-vultr-x86_64-mpage-load_fast_borrow-3.14.0a4%2B-b0fcd85-vs-default_base_vs_NOGIL.md)
- [📈time plot](bm-20250206-vultr-x86_64-mpage-load_fast_borrow-3.14.0a4%2B-b0fcd85-vs-default_base_vs_NOGIL.svg)

