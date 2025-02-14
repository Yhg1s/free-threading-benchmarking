# Results

- fork: mpage/load_fast_borrow_abs
- version: 3.14.0a5+
- config: NOGIL
- commit hash: [dcbd5da](https://github.com/mpage/cpython/commit/dcbd5da)
- commit date: 2025-02-13T13:55:39-08:00
- commit merge base: [07f5e33f2eed50984d7a60b48bb3136d93a59dd6](https://github.com/python/cpython/commit/07f5e33f2eed50984d7a60b48bb3136d93a59dd6)
- ref: load_fast_borrow_abs

## linux x86_64 (vultr)

- [GitHub Action run](https://github.com/facebookexperimental/free-threading-benchmarking/actions/runs/13317961904)
- cpu model: Intel(R) Xeon(R) E-2286G CPU @ 4.00GHz
- platform: Linux-6.8.0-51-generic-x86_64-with-glibc2.39
- [raw results](bm-20250213-vultr-x86_64-mpage-load_fast_borrow_abs-3.14.0a5%2B-dcbd5da.json)

### vs. 3.12.6

- Geometric mean: 1.005x faster (HPT: reliability of 92.57%, 1.00x slower at 99th %ile)
- Memory usage: 1.36x
- missing benchmarks: aiohttp, asyncio_tcp, asyncio_tcp_ssl, chameleon, dask, flaskblogging, gunicorn, mypy2, pickle, pickle_dict, pickle_list, tornado_http, unpack_sequence, unpickle, unpickle_list
- new benchmarks: connected_components, k_core, many_optionals, shortest_path, sphinx, subparsers
- [📄table](bm-20250213-vultr-x86_64-mpage-load_fast_borrow_abs-3.14.0a5%2B-dcbd5da-vs-3.12.6.md)
- [📈time plot](bm-20250213-vultr-x86_64-mpage-load_fast_borrow_abs-3.14.0a5%2B-dcbd5da-vs-3.12.6.svg)

### vs. 3.13.0rc2

- Geometric mean: 1.028x slower (HPT: reliability of 98.20%, 1.00x slower at 99th %ile)
- Memory usage: 1.34x
- missing benchmarks: aiohttp, asyncio_tcp, asyncio_tcp_ssl, chameleon, dask, flaskblogging, gunicorn, pickle, pickle_dict, pickle_list, tornado_http, unpack_sequence, unpickle, unpickle_list
- new benchmarks: connected_components, k_core, many_optionals, shortest_path, sphinx, sqlalchemy_declarative, sqlalchemy_imperative, subparsers
- [📄table](bm-20250213-vultr-x86_64-mpage-load_fast_borrow_abs-3.14.0a5%2B-dcbd5da-vs-3.13.0rc2.md)
- [📈time plot](bm-20250213-vultr-x86_64-mpage-load_fast_borrow_abs-3.14.0a5%2B-dcbd5da-vs-3.13.0rc2.svg)

### vs. base

- Geometric mean: 1.054x faster (HPT: reliability of 100.00%, 1.03x faster at 99th %ile)
- Memory usage: 1.00x
- [🧠memory plot](bm-20250213-vultr-x86_64-mpage-load_fast_borrow_abs-3.14.0a5%2B-dcbd5da-vs-base-mem.svg)
- [📄table](bm-20250213-vultr-x86_64-mpage-load_fast_borrow_abs-3.14.0a5%2B-dcbd5da-vs-base.md)
- [📈time plot](bm-20250213-vultr-x86_64-mpage-load_fast_borrow_abs-3.14.0a5%2B-dcbd5da-vs-base.svg)

### vs. default_base_vs_NOGIL

- Geometric mean: 1.081x slower (HPT: reliability of 100.00%, 1.07x slower at 99th %ile)
- Memory usage: 1.20x
- new benchmarks: html5lib
- [📄table](bm-20250213-vultr-x86_64-mpage-load_fast_borrow_abs-3.14.0a5%2B-dcbd5da-vs-default_base_vs_NOGIL.md)
- [📈time plot](bm-20250213-vultr-x86_64-mpage-load_fast_borrow_abs-3.14.0a5%2B-dcbd5da-vs-default_base_vs_NOGIL.svg)

