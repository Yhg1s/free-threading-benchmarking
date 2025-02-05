# Results

- fork: DinoV/hash_type
- version: 3.14.0a4+
- config: NOGIL
- commit hash: [cbd6459](https://github.com/DinoV/cpython/commit/cbd6459)
- commit date: 2025-02-05T09:00:32-08:00
- commit merge base: [49f24650e4541456872490ec2b59d6d186204891](https://github.com/python/cpython/commit/49f24650e4541456872490ec2b59d6d186204891)
- ref: hash_type

## linux x86_64 (vultr)

- [GitHub Action run](https://github.com/facebookexperimental/free-threading-benchmarking/actions/runs/13162638117)
- cpu model: Intel(R) Xeon(R) E-2286G CPU @ 4.00GHz
- platform: Linux-6.8.0-51-generic-x86_64-with-glibc2.39
- [raw results](bm-20250205-vultr-x86_64-DinoV-hash_type-3.14.0a4%2B-cbd6459.json)

### vs. 3.12.6

- Geometric mean: 1.050x slower (HPT: reliability of 99.99%, 1.03x slower at 99th %ile)
- Memory usage: 1.36x
- missing benchmarks: aiohttp, asyncio_tcp, asyncio_tcp_ssl, chameleon, dask, flaskblogging, gunicorn, mypy2, pickle, pickle_dict, pickle_list, tornado_http, unpack_sequence, unpickle, unpickle_list
- new benchmarks: connected_components, k_core, many_optionals, shortest_path, sphinx, subparsers
- [📄table](bm-20250205-vultr-x86_64-DinoV-hash_type-3.14.0a4%2B-cbd6459-vs-3.12.6.md)
- [📈time plot](bm-20250205-vultr-x86_64-DinoV-hash_type-3.14.0a4%2B-cbd6459-vs-3.12.6.svg)

### vs. 3.13.0rc2

- Geometric mean: 1.080x slower (HPT: reliability of 99.99%, 1.04x slower at 99th %ile)
- Memory usage: 1.34x
- missing benchmarks: aiohttp, asyncio_tcp, asyncio_tcp_ssl, chameleon, dask, flaskblogging, gunicorn, pickle, pickle_dict, pickle_list, tornado_http, unpack_sequence, unpickle, unpickle_list
- new benchmarks: connected_components, k_core, many_optionals, shortest_path, sphinx, sqlalchemy_declarative, sqlalchemy_imperative, subparsers
- [📄table](bm-20250205-vultr-x86_64-DinoV-hash_type-3.14.0a4%2B-cbd6459-vs-3.13.0rc2.md)
- [📈time plot](bm-20250205-vultr-x86_64-DinoV-hash_type-3.14.0a4%2B-cbd6459-vs-3.13.0rc2.svg)

