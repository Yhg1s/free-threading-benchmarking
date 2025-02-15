# Results

- fork: DinoV/local_type_cache
- version: 3.14.0a5+
- config: NOGIL
- commit hash: [627b63e](https://github.com/DinoV/cpython/commit/627b63e)
- commit date: 2025-02-14T14:10:42-08:00
- commit merge base: [303043f5062c1e7ffb7907abde61dbf13c98f8e9](https://github.com/python/cpython/commit/303043f5062c1e7ffb7907abde61dbf13c98f8e9)
- ref: local_type_cache

## linux x86_64 (vultr)

- [GitHub Action run](https://github.com/facebookexperimental/free-threading-benchmarking/actions/runs/13336978262)
- cpu model: Intel(R) Xeon(R) E-2286G CPU @ 4.00GHz
- platform: Linux-6.8.0-51-generic-x86_64-with-glibc2.39
- [raw results](bm-20250214-vultr-x86_64-DinoV-local_type_cache-3.14.0a5%2B-627b63e.json)

### vs. 3.12.6

- Geometric mean: 1.053x slower (HPT: reliability of 99.99%, 1.04x slower at 99th %ile)
- Memory usage: 1.37x
- missing benchmarks: aiohttp, asyncio_tcp, asyncio_tcp_ssl, chameleon, dask, flaskblogging, gunicorn, mypy2, pickle, pickle_dict, pickle_list, tornado_http, unpack_sequence, unpickle, unpickle_list
- new benchmarks: connected_components, k_core, many_optionals, shortest_path, sphinx, subparsers
- [📄table](bm-20250214-vultr-x86_64-DinoV-local_type_cache-3.14.0a5%2B-627b63e-vs-3.12.6.md)
- [📈time plot](bm-20250214-vultr-x86_64-DinoV-local_type_cache-3.14.0a5%2B-627b63e-vs-3.12.6.svg)

### vs. 3.13.0rc2

- Geometric mean: 1.084x slower (HPT: reliability of 99.99%, 1.05x slower at 99th %ile)
- Memory usage: 1.35x
- missing benchmarks: aiohttp, asyncio_tcp, asyncio_tcp_ssl, chameleon, dask, flaskblogging, gunicorn, pickle, pickle_dict, pickle_list, tornado_http, unpack_sequence, unpickle, unpickle_list
- new benchmarks: connected_components, k_core, many_optionals, shortest_path, sphinx, sqlalchemy_declarative, sqlalchemy_imperative, subparsers
- [📄table](bm-20250214-vultr-x86_64-DinoV-local_type_cache-3.14.0a5%2B-627b63e-vs-3.13.0rc2.md)
- [📈time plot](bm-20250214-vultr-x86_64-DinoV-local_type_cache-3.14.0a5%2B-627b63e-vs-3.13.0rc2.svg)

### vs. base

- Geometric mean: 1.006x slower (HPT: reliability of 99.97%, 1.00x slower at 99th %ile)
- Memory usage: 1.01x
- [🧠memory plot](bm-20250214-vultr-x86_64-DinoV-local_type_cache-3.14.0a5%2B-627b63e-vs-base-mem.svg)
- [📄table](bm-20250214-vultr-x86_64-DinoV-local_type_cache-3.14.0a5%2B-627b63e-vs-base.md)
- [📈time plot](bm-20250214-vultr-x86_64-DinoV-local_type_cache-3.14.0a5%2B-627b63e-vs-base.svg)

