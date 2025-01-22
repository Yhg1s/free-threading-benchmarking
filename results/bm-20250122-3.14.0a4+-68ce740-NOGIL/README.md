# Results

- fork: colesbury/revert_gh_128914
- version: 3.14.0a4+
- config: NOGIL
- commit hash: [68ce740](https://github.com/colesbury/cpython/commit/68ce740)
- commit date: 2025-01-22T09:24:48-05:00
- commit merge base: [2ed5ee9a50454b3fce87b26be5838ca7127b2ff9](https://github.com/python/cpython/commit/2ed5ee9a50454b3fce87b26be5838ca7127b2ff9)
- ref: revert_gh_128914

## linux x86_64 (vultr)

- [GitHub Action run](https://github.com/facebookexperimental/free-threading-benchmarking/actions/runs/12910324097)
- cpu model: Intel(R) Xeon(R) E-2286G CPU @ 4.00GHz
- platform: Linux-6.8.0-51-generic-x86_64-with-glibc2.39
- [raw results](bm-20250122-vultr-x86_64-colesbury-revert_gh_128914-3.14.0a4%2B-68ce740.json)

### vs. 3.12.6

- Geometric mean: 1.056x slower (HPT: reliability of 99.98%, 1.03x slower at 99th %ile)
- Memory usage: 1.34x
- missing benchmarks: aiohttp, asyncio_tcp, asyncio_tcp_ssl, chameleon, dask, flaskblogging, gunicorn, mypy2, pickle, pickle_dict, pickle_list, tornado_http, unpack_sequence, unpickle, unpickle_list
- new benchmarks: connected_components, k_core, many_optionals, shortest_path, sphinx, subparsers
- [📄table](bm-20250122-vultr-x86_64-colesbury-revert_gh_128914-3.14.0a4%2B-68ce740-vs-3.12.6.md)
- [📈time plot](bm-20250122-vultr-x86_64-colesbury-revert_gh_128914-3.14.0a4%2B-68ce740-vs-3.12.6.svg)

### vs. 3.13.0rc2

- Geometric mean: 1.086x slower (HPT: reliability of 99.99%, 1.06x slower at 99th %ile)
- Memory usage: 1.33x
- missing benchmarks: aiohttp, asyncio_tcp, asyncio_tcp_ssl, chameleon, dask, flaskblogging, gunicorn, pickle, pickle_dict, pickle_list, tornado_http, unpack_sequence, unpickle, unpickle_list
- new benchmarks: connected_components, k_core, many_optionals, shortest_path, sphinx, sqlalchemy_declarative, sqlalchemy_imperative, subparsers
- [📄table](bm-20250122-vultr-x86_64-colesbury-revert_gh_128914-3.14.0a4%2B-68ce740-vs-3.13.0rc2.md)
- [📈time plot](bm-20250122-vultr-x86_64-colesbury-revert_gh_128914-3.14.0a4%2B-68ce740-vs-3.13.0rc2.svg)

### vs. base

- Geometric mean: 1.025x faster (HPT: reliability of 100.00%, 1.01x faster at 99th %ile)
- Memory usage: 0.99x
- [🧠memory plot](bm-20250122-vultr-x86_64-colesbury-revert_gh_128914-3.14.0a4%2B-68ce740-vs-base-mem.svg)
- [📄table](bm-20250122-vultr-x86_64-colesbury-revert_gh_128914-3.14.0a4%2B-68ce740-vs-base.md)
- [📈time plot](bm-20250122-vultr-x86_64-colesbury-revert_gh_128914-3.14.0a4%2B-68ce740-vs-base.svg)

