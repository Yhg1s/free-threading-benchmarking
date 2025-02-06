# Results

- fork: python/cdcacec79f7a216c3c98
- version: 3.14.0a4+
- config: NOGIL
- commit hash: [cdcacec](https://github.com/python/cpython/commit/cdcacec)
- commit date: 2025-02-05T11:38:30-08:00
- commit merge base: [5fb019fc29a90e722aff20a9522bf588351358cd](https://github.com/python/cpython/commit/5fb019fc29a90e722aff20a9522bf588351358cd)
- ref: cdcacec79f7a216c3c98

## linux x86_64 (linux)

- [GitHub Action run](https://github.com/facebookexperimental/free-threading-benchmarking/actions/runs/13169156243)
- cpu model: Intel(R) Xeon(R) Platinum 8259CL CPU @ 2.50GHz
- platform: Linux-5.15.0-1071-aws-x86_64-with-glibc2.31
- [raw results](bm-20250205-linux-x86_64-python-cdcacec79f7a216c3c98-3.14.0a4%2B-cdcacec.json)

### vs. 3.12.6

- Geometric mean: 1.034x slower (HPT: reliability of 99.92%, 1.01x slower at 99th %ile)
- Memory usage: 1.35x
- missing benchmarks: aiohttp, asyncio_tcp, asyncio_tcp_ssl, chameleon, dask, flaskblogging, gunicorn, mypy2, pickle, pickle_dict, pickle_list, tornado_http, unpack_sequence, unpickle, unpickle_list
- new benchmarks: connected_components, k_core, many_optionals, shortest_path, sphinx, subparsers
- [📄table](bm-20250205-linux-x86_64-python-cdcacec79f7a216c3c98-3.14.0a4%2B-cdcacec-vs-3.12.6.md)
- [📈time plot](bm-20250205-linux-x86_64-python-cdcacec79f7a216c3c98-3.14.0a4%2B-cdcacec-vs-3.12.6.svg)

### vs. 3.13.0rc2

- Geometric mean: 1.069x slower (HPT: reliability of 99.99%, 1.03x slower at 99th %ile)
- Memory usage: 1.34x
- missing benchmarks: aiohttp, asyncio_tcp, asyncio_tcp_ssl, chameleon, dask, flaskblogging, gunicorn, pickle, pickle_dict, pickle_list, tornado_http, unpack_sequence, unpickle, unpickle_list
- new benchmarks: connected_components, k_core, many_optionals, shortest_path, sphinx, sqlalchemy_declarative, sqlalchemy_imperative, subparsers
- [📄table](bm-20250205-linux-x86_64-python-cdcacec79f7a216c3c98-3.14.0a4%2B-cdcacec-vs-3.13.0rc2.md)
- [📈time plot](bm-20250205-linux-x86_64-python-cdcacec79f7a216c3c98-3.14.0a4%2B-cdcacec-vs-3.13.0rc2.svg)

