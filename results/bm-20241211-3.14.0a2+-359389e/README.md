# Results

- fork: python/359389ed51aecc107681
- version: 3.14.0a2+
- config: 
- commit hash: [359389e](https://github.com/python/cpython/commit/359389e)
- commit date: 2024-12-11T13:28:19+00:00
- commit merge base: [b2ad7e0a2c1518539d9b0ef83c9f7a09d10fd303](https://github.com/python/cpython/commit/b2ad7e0a2c1518539d9b0ef83c9f7a09d10fd303)
- ref: 359389ed51aecc107681

## linux x86_64 (vultr)

- [GitHub Action run](https://github.com/facebookexperimental/free-threading-benchmarking/actions/runs/12289007658)
- cpu model: Intel(R) Xeon(R) E-2286G CPU @ 4.00GHz
- platform: Linux-6.8.0-45-generic-x86_64-with-glibc2.39
- [raw results](bm-20241211-vultr-x86_64-python-359389ed51aecc107681-3.14.0a2%2B-359389e.json)

### vs. 3.12.6

- Geometric mean: 1.082x faster (HPT: reliability of 100.00%, 1.03x faster at 99th %ile)
- Memory usage: 1.11x
- missing benchmarks: aiohttp, asyncio_tcp, asyncio_tcp_ssl, chameleon, dask, flaskblogging, gunicorn, html5lib, mypy2, pickle, pickle_dict, pickle_list, tornado_http, unpack_sequence, unpickle, unpickle_list
- new benchmarks: connected_components, k_core, many_optionals, shortest_path, sphinx, subparsers
- [📄table](bm-20241211-vultr-x86_64-python-359389ed51aecc107681-3.14.0a2%2B-359389e-vs-3.12.6.md)
- [📈time plot](bm-20241211-vultr-x86_64-python-359389ed51aecc107681-3.14.0a2%2B-359389e-vs-3.12.6.svg)

### vs. 3.13.0rc2

- Geometric mean: 1.043x faster (HPT: reliability of 100.00%, 1.00x faster at 99th %ile)
- Memory usage: 1.10x
- missing benchmarks: aiohttp, asyncio_tcp, asyncio_tcp_ssl, chameleon, dask, flaskblogging, gunicorn, html5lib, pickle, pickle_dict, pickle_list, tornado_http, unpack_sequence, unpickle, unpickle_list
- new benchmarks: connected_components, k_core, many_optionals, shortest_path, sphinx, sqlalchemy_declarative, sqlalchemy_imperative, subparsers
- [📄table](bm-20241211-vultr-x86_64-python-359389ed51aecc107681-3.14.0a2%2B-359389e-vs-3.13.0rc2.md)
- [📈time plot](bm-20241211-vultr-x86_64-python-359389ed51aecc107681-3.14.0a2%2B-359389e-vs-3.13.0rc2.svg)

