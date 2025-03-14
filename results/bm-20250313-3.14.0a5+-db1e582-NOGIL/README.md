# Results

- fork: python/db1e5827c45ad737bf83
- version: 3.14.0a5+
- config: NOGIL
- commit hash: [db1e582](https://github.com/python/cpython/commit/db1e582)
- commit date: 2025-03-13T08:28:15+08:00
- commit merge base: [3618240624d98de2a68a79dc174d49efb96cc2e6](https://github.com/python/cpython/commit/3618240624d98de2a68a79dc174d49efb96cc2e6)
- ref: db1e5827c45ad737bf83

## linux x86_64 (vultr)

- [GitHub Action run](https://github.com/facebookexperimental/free-threading-benchmarking/actions/runs/13847246221)
- cpu model: Intel(R) Xeon(R) E-2286G CPU @ 4.00GHz
- platform: Linux-6.8.0-51-generic-x86_64-with-glibc2.39
- [raw results](bm-20250313-vultr-x86_64-python-db1e5827c45ad737bf83-3.14.0a5%2B-db1e582.json)

### vs. 3.12.6

- Geometric mean: 1.052x slower (HPT: reliability of 100.00%, 1.03x slower at 99th %ile)
- Memory usage: 1.36x
- missing benchmarks: aiohttp, asyncio_tcp, asyncio_tcp_ssl, chameleon, dask, flaskblogging, gunicorn, mypy2, pickle, pickle_dict, pickle_list, tornado_http, unpack_sequence, unpickle, unpickle_list
- new benchmarks: connected_components, k_core, many_optionals, shortest_path, sphinx, subparsers
- [📄table](bm-20250313-vultr-x86_64-python-db1e5827c45ad737bf83-3.14.0a5%2B-db1e582-vs-3.12.6.md)
- [📈time plot](bm-20250313-vultr-x86_64-python-db1e5827c45ad737bf83-3.14.0a5%2B-db1e582-vs-3.12.6.svg)

### vs. 3.13.0rc2

- Geometric mean: 1.084x slower (HPT: reliability of 100.00%, 1.05x slower at 99th %ile)
- Memory usage: 1.35x
- missing benchmarks: aiohttp, asyncio_tcp, asyncio_tcp_ssl, chameleon, dask, flaskblogging, gunicorn, pickle, pickle_dict, pickle_list, tornado_http, unpack_sequence, unpickle, unpickle_list
- new benchmarks: connected_components, k_core, many_optionals, shortest_path, sphinx, sqlalchemy_declarative, sqlalchemy_imperative, subparsers
- [📄table](bm-20250313-vultr-x86_64-python-db1e5827c45ad737bf83-3.14.0a5%2B-db1e582-vs-3.13.0rc2.md)
- [📈time plot](bm-20250313-vultr-x86_64-python-db1e5827c45ad737bf83-3.14.0a5%2B-db1e582-vs-3.13.0rc2.svg)

### vs. base

- Geometric mean: 1.005x slower (HPT: reliability of 99.94%, 1.00x slower at 99th %ile)
- Memory usage: 0.98x
- [🧠memory plot](bm-20250313-vultr-x86_64-python-db1e5827c45ad737bf83-3.14.0a5%2B-db1e582-vs-base-mem.svg)
- [📄table](bm-20250313-vultr-x86_64-python-db1e5827c45ad737bf83-3.14.0a5%2B-db1e582-vs-base.md)
- [📈time plot](bm-20250313-vultr-x86_64-python-db1e5827c45ad737bf83-3.14.0a5%2B-db1e582-vs-base.svg)

### vs. default_base_vs_NOGIL

- Geometric mean: 1.105x slower (HPT: reliability of 100.00%, 1.09x slower at 99th %ile)
- Memory usage: 1.21x
- new benchmarks: html5lib
- [📄table](bm-20250313-vultr-x86_64-python-db1e5827c45ad737bf83-3.14.0a5%2B-db1e582-vs-default_base_vs_NOGIL.md)
- [📈time plot](bm-20250313-vultr-x86_64-python-db1e5827c45ad737bf83-3.14.0a5%2B-db1e582-vs-default_base_vs_NOGIL.svg)

