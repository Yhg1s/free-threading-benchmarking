# Results

- fork: nascheme/gh_128384_warnings_c
- version: 3.14.0a5+
- config: NOGIL
- commit hash: [dba89e0](https://github.com/nascheme/cpython/commit/dba89e0)
- commit date: 2025-02-19T09:50:46-08:00
- commit merge base: [a7427f2db937adb4c787754deb4c337f1894fe86](https://github.com/python/cpython/commit/a7427f2db937adb4c787754deb4c337f1894fe86)
- ref: gh_128384_warnings_c

## linux x86_64 (vultr)

- [GitHub Action run](https://github.com/facebookexperimental/free-threading-benchmarking/actions/runs/13442186326)
- cpu model: Intel(R) Xeon(R) E-2286G CPU @ 4.00GHz
- platform: Linux-6.8.0-51-generic-x86_64-with-glibc2.39
- [raw results](bm-20250219-vultr-x86_64-nascheme-gh_128384_warnings_c-3.14.0a5%2B-dba89e0.json)

### vs. 3.12.6

- Geometric mean: 1.049x slower (HPT: reliability of 99.98%, 1.03x slower at 99th %ile)
- Memory usage: 1.36x
- missing benchmarks: aiohttp, asyncio_tcp, asyncio_tcp_ssl, chameleon, dask, flaskblogging, gunicorn, mypy2, pickle, pickle_dict, pickle_list, tornado_http, unpack_sequence, unpickle, unpickle_list
- new benchmarks: connected_components, k_core, many_optionals, shortest_path, sphinx, subparsers
- [📄table](bm-20250219-vultr-x86_64-nascheme-gh_128384_warnings_c-3.14.0a5%2B-dba89e0-vs-3.12.6.md)
- [📈time plot](bm-20250219-vultr-x86_64-nascheme-gh_128384_warnings_c-3.14.0a5%2B-dba89e0-vs-3.12.6.svg)

### vs. 3.13.0rc2

- Geometric mean: 1.081x slower (HPT: reliability of 99.99%, 1.05x slower at 99th %ile)
- Memory usage: 1.34x
- missing benchmarks: aiohttp, asyncio_tcp, asyncio_tcp_ssl, chameleon, dask, flaskblogging, gunicorn, pickle, pickle_dict, pickle_list, tornado_http, unpack_sequence, unpickle, unpickle_list
- new benchmarks: connected_components, k_core, many_optionals, shortest_path, sphinx, sqlalchemy_declarative, sqlalchemy_imperative, subparsers
- [📄table](bm-20250219-vultr-x86_64-nascheme-gh_128384_warnings_c-3.14.0a5%2B-dba89e0-vs-3.13.0rc2.md)
- [📈time plot](bm-20250219-vultr-x86_64-nascheme-gh_128384_warnings_c-3.14.0a5%2B-dba89e0-vs-3.13.0rc2.svg)

### vs. base

- Geometric mean: 1.002x slower (HPT: reliability of 94.57%, 1.00x slower at 99th %ile)
- Memory usage: 1.00x
- [🧠memory plot](bm-20250219-vultr-x86_64-nascheme-gh_128384_warnings_c-3.14.0a5%2B-dba89e0-vs-base-mem.svg)
- [📄table](bm-20250219-vultr-x86_64-nascheme-gh_128384_warnings_c-3.14.0a5%2B-dba89e0-vs-base.md)
- [📈time plot](bm-20250219-vultr-x86_64-nascheme-gh_128384_warnings_c-3.14.0a5%2B-dba89e0-vs-base.svg)

