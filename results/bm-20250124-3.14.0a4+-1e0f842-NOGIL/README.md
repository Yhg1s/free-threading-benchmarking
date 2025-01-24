# Results

- fork: faster-cpython/remove_most_conditio
- version: 3.14.0a4+
- config: NOGIL
- commit hash: [1e0f842](https://github.com/faster%2dcpython/cpython/commit/1e0f842)
- commit date: 2025-01-24T11:21:33+00:00
- commit merge base: [a10f99375e7912df863cf101a38e9703cfcd72f1](https://github.com/python/cpython/commit/a10f99375e7912df863cf101a38e9703cfcd72f1)
- ref: remove_most_conditio

## linux x86_64 (vultr)

- [GitHub Action run](https://github.com/facebookexperimental/free-threading-benchmarking/actions/runs/12954921020)
- cpu model: Intel(R) Xeon(R) E-2286G CPU @ 4.00GHz
- platform: Linux-6.8.0-51-generic-x86_64-with-glibc2.39
- [raw results](bm-20250124-vultr-x86_64-faster%252dcpython-remove_most_conditio-3.14.0a4%2B-1e0f842.json)

### vs. 3.12.6

- Geometric mean: 1.053x slower (HPT: reliability of 99.95%, 1.03x slower at 99th %ile)
- Memory usage: 1.35x
- missing benchmarks: aiohttp, asyncio_tcp, asyncio_tcp_ssl, chameleon, dask, flaskblogging, gunicorn, mypy2, pickle, pickle_dict, pickle_list, tornado_http, unpack_sequence, unpickle, unpickle_list
- new benchmarks: connected_components, k_core, many_optionals, shortest_path, sphinx, subparsers
- [📄table](bm-20250124-vultr-x86_64-faster%252dcpython-remove_most_conditio-3.14.0a4%2B-1e0f842-vs-3.12.6.md)
- [📈time plot](bm-20250124-vultr-x86_64-faster%252dcpython-remove_most_conditio-3.14.0a4%2B-1e0f842-vs-3.12.6.svg)

### vs. 3.13.0rc2

- Geometric mean: 1.083x slower (HPT: reliability of 99.98%, 1.04x slower at 99th %ile)
- Memory usage: 1.33x
- missing benchmarks: aiohttp, asyncio_tcp, asyncio_tcp_ssl, chameleon, dask, flaskblogging, gunicorn, pickle, pickle_dict, pickle_list, tornado_http, unpack_sequence, unpickle, unpickle_list
- new benchmarks: connected_components, k_core, many_optionals, shortest_path, sphinx, sqlalchemy_declarative, sqlalchemy_imperative, subparsers
- [📄table](bm-20250124-vultr-x86_64-faster%252dcpython-remove_most_conditio-3.14.0a4%2B-1e0f842-vs-3.13.0rc2.md)
- [📈time plot](bm-20250124-vultr-x86_64-faster%252dcpython-remove_most_conditio-3.14.0a4%2B-1e0f842-vs-3.13.0rc2.svg)

### vs. base

- Geometric mean: 1.010x faster (HPT: reliability of 100.00%, 1.00x faster at 99th %ile)
- Memory usage: 1.00x
- [🧠memory plot](bm-20250124-vultr-x86_64-faster%252dcpython-remove_most_conditio-3.14.0a4%2B-1e0f842-vs-base-mem.svg)
- [📄table](bm-20250124-vultr-x86_64-faster%252dcpython-remove_most_conditio-3.14.0a4%2B-1e0f842-vs-base.md)
- [📈time plot](bm-20250124-vultr-x86_64-faster%252dcpython-remove_most_conditio-3.14.0a4%2B-1e0f842-vs-base.svg)

