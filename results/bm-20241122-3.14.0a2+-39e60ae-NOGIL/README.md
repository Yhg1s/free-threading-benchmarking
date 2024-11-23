# Results

- fork: python
- version: 3.14.0a2+
- config: NOGIL
- commit hash: [39e60ae](https://github.com/python/cpython/commit/39e60ae)
- commit date: 2024-11-22T16:02:51-08:00
- commit merge base: [d24a22e9b6377797c3b602945347096fbe065670](https://github.com/python/cpython/commit/d24a22e9b6377797c3b602945347096fbe065670)
- ref: 39e60aeb3837f1f23d8b

## linux x86_64 (linux)

- [GitHub Action run](https://github.com/facebookexperimental/free-threading-benchmarking/actions/runs/11982244918)
- cpu model: Intel(R) Xeon(R) Platinum 8259CL CPU @ 2.50GHz
- platform: Linux-5.15.0-1071-aws-x86_64-with-glibc2.31
- [raw results](bm-20241122-linux-x86_64-python-39e60aeb3837f1f23d8b-3.14.0a2%2B-39e60ae.json)

### vs. 3.12.6

- Geometric mean: 1.27x slower (HPT: reliability of 100.00%, 1.14x slower at 99th %ile)
- Memory usage: 1.34x
- missing benchmarks: aiohttp, asyncio_tcp, asyncio_tcp_ssl, chameleon, dask, flaskblogging, gunicorn, mypy2, pickle, pickle_dict, pickle_list, sqlalchemy_declarative, sqlalchemy_imperative, tornado_http, unpack_sequence, unpickle, unpickle_list
- new benchmarks: connected_components, k_core, many_optionals, shortest_path, sphinx, subparsers
- [📄table](bm-20241122-linux-x86_64-python-39e60aeb3837f1f23d8b-3.14.0a2%2B-39e60ae-vs-3.12.6.md)
- [📈time plot](bm-20241122-linux-x86_64-python-39e60aeb3837f1f23d8b-3.14.0a2%2B-39e60ae-vs-3.12.6.svg)

### vs. 3.13.0rc2

- Geometric mean: 1.32x slower (HPT: reliability of 100.00%, 1.19x slower at 99th %ile)
- Memory usage: 1.33x
- missing benchmarks: aiohttp, asyncio_tcp, asyncio_tcp_ssl, chameleon, dask, flaskblogging, gunicorn, pickle, pickle_dict, pickle_list, tornado_http, unpack_sequence, unpickle, unpickle_list
- new benchmarks: connected_components, k_core, many_optionals, shortest_path, sphinx, subparsers
- [📄table](bm-20241122-linux-x86_64-python-39e60aeb3837f1f23d8b-3.14.0a2%2B-39e60ae-vs-3.13.0rc2.md)
- [📈time plot](bm-20241122-linux-x86_64-python-39e60aeb3837f1f23d8b-3.14.0a2%2B-39e60ae-vs-3.13.0rc2.svg)

### vs. base

- Geometric mean: 1.36x slower (HPT: reliability of 100.00%, 1.22x slower at 99th %ile)
- Memory usage: 1.18x
- missing benchmarks: 🔴 sqlalchemy_declarative, sqlalchemy_imperative
- [🧠memory plot](bm-20241122-linux-x86_64-python-39e60aeb3837f1f23d8b-3.14.0a2%2B-39e60ae-vs-base-mem.svg)
- [📄table](bm-20241122-linux-x86_64-python-39e60aeb3837f1f23d8b-3.14.0a2%2B-39e60ae-vs-base.md)
- [📈time plot](bm-20241122-linux-x86_64-python-39e60aeb3837f1f23d8b-3.14.0a2%2B-39e60ae-vs-base.svg)

