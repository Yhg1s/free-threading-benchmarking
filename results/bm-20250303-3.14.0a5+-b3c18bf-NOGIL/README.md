# Results

- fork: python/b3c18bfd828ba90b9c71
- version: 3.14.0a5+
- config: NOGIL
- commit hash: [b3c18bf](https://github.com/python/cpython/commit/b3c18bf)
- commit date: 2025-03-03T15:08:05+01:00
- commit merge base: [4f14b7e30c0243e81407a34968495301e829a033](https://github.com/python/cpython/commit/4f14b7e30c0243e81407a34968495301e829a033)
- ref: b3c18bfd828ba90b9c71

## linux x86_64 (vultr)

- [GitHub Action run](https://github.com/facebookexperimental/free-threading-benchmarking/actions/runs/13637467049)
- cpu model: Intel(R) Xeon(R) E-2286G CPU @ 4.00GHz
- platform: Linux-6.8.0-51-generic-x86_64-with-glibc2.39
- [raw results](bm-20250303-vultr-x86_64-python-b3c18bfd828ba90b9c71-3.14.0a5%2B-b3c18bf.json)

### vs. 3.12.6

- Geometric mean: 1.043x slower (HPT: reliability of 99.99%, 1.02x slower at 99th %ile)
- Memory usage: 1.35x
- missing benchmarks: aiohttp, asyncio_tcp, asyncio_tcp_ssl, chameleon, dask, flaskblogging, gunicorn, mypy2, pickle, pickle_dict, pickle_list, tornado_http, unpack_sequence, unpickle, unpickle_list
- new benchmarks: connected_components, k_core, many_optionals, shortest_path, sphinx, subparsers
- [📄table](bm-20250303-vultr-x86_64-python-b3c18bfd828ba90b9c71-3.14.0a5%2B-b3c18bf-vs-3.12.6.md)
- [📈time plot](bm-20250303-vultr-x86_64-python-b3c18bfd828ba90b9c71-3.14.0a5%2B-b3c18bf-vs-3.12.6.svg)

### vs. 3.13.0rc2

- Geometric mean: 1.075x slower (HPT: reliability of 100.00%, 1.05x slower at 99th %ile)
- Memory usage: 1.34x
- missing benchmarks: aiohttp, asyncio_tcp, asyncio_tcp_ssl, chameleon, dask, flaskblogging, gunicorn, pickle, pickle_dict, pickle_list, tornado_http, unpack_sequence, unpickle, unpickle_list
- new benchmarks: connected_components, k_core, many_optionals, shortest_path, sphinx, sqlalchemy_declarative, sqlalchemy_imperative, subparsers
- [📄table](bm-20250303-vultr-x86_64-python-b3c18bfd828ba90b9c71-3.14.0a5%2B-b3c18bf-vs-3.13.0rc2.md)
- [📈time plot](bm-20250303-vultr-x86_64-python-b3c18bfd828ba90b9c71-3.14.0a5%2B-b3c18bf-vs-3.13.0rc2.svg)

