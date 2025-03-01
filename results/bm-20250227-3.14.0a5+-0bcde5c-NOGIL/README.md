# Results

- fork: tom-pytel/fix_issue_128942
- version: 3.14.0a5+
- config: NOGIL
- commit hash: [0bcde5c](https://github.com/tom%2dpytel/cpython/commit/0bcde5c)
- commit date: 2025-02-27T13:36:49+00:00
- commit merge base: [45a24f54af4a65c14cc15fc13d3258726e2fe73b](https://github.com/python/cpython/commit/45a24f54af4a65c14cc15fc13d3258726e2fe73b)
- ref: fix_issue_128942

## linux x86_64 (vultr)

- [GitHub Action run](https://github.com/facebookexperimental/free-threading-benchmarking/actions/runs/13595814277)
- cpu model: Intel(R) Xeon(R) E-2286G CPU @ 4.00GHz
- platform: Linux-6.8.0-51-generic-x86_64-with-glibc2.39
- [raw results](bm-20250227-vultr-x86_64-tom%252dpytel-fix_issue_128942-3.14.0a5%2B-0bcde5c.json)

### vs. 3.12.6

- Geometric mean: 1.058x slower (HPT: reliability of 100.00%, 1.04x slower at 99th %ile)
- Memory usage: 1.36x
- missing benchmarks: aiohttp, asyncio_tcp, asyncio_tcp_ssl, chameleon, dask, flaskblogging, gunicorn, mypy2, pickle, pickle_dict, pickle_list, tornado_http, unpack_sequence, unpickle, unpickle_list
- new benchmarks: connected_components, k_core, many_optionals, shortest_path, sphinx, subparsers
- [📄table](bm-20250227-vultr-x86_64-tom%252dpytel-fix_issue_128942-3.14.0a5%2B-0bcde5c-vs-3.12.6.md)
- [📈time plot](bm-20250227-vultr-x86_64-tom%252dpytel-fix_issue_128942-3.14.0a5%2B-0bcde5c-vs-3.12.6.svg)

### vs. 3.13.0rc2

- Geometric mean: 1.090x slower (HPT: reliability of 100.00%, 1.06x slower at 99th %ile)
- Memory usage: 1.34x
- missing benchmarks: aiohttp, asyncio_tcp, asyncio_tcp_ssl, chameleon, dask, flaskblogging, gunicorn, pickle, pickle_dict, pickle_list, tornado_http, unpack_sequence, unpickle, unpickle_list
- new benchmarks: connected_components, k_core, many_optionals, shortest_path, sphinx, sqlalchemy_declarative, sqlalchemy_imperative, subparsers
- [📄table](bm-20250227-vultr-x86_64-tom%252dpytel-fix_issue_128942-3.14.0a5%2B-0bcde5c-vs-3.13.0rc2.md)
- [📈time plot](bm-20250227-vultr-x86_64-tom%252dpytel-fix_issue_128942-3.14.0a5%2B-0bcde5c-vs-3.13.0rc2.svg)

### vs. base

- Geometric mean: 1.015x slower (HPT: reliability of 100.00%, 1.00x slower at 99th %ile)
- Memory usage: 1.01x
- [🧠memory plot](bm-20250227-vultr-x86_64-tom%252dpytel-fix_issue_128942-3.14.0a5%2B-0bcde5c-vs-base-mem.svg)
- [📄table](bm-20250227-vultr-x86_64-tom%252dpytel-fix_issue_128942-3.14.0a5%2B-0bcde5c-vs-base.md)
- [📈time plot](bm-20250227-vultr-x86_64-tom%252dpytel-fix_issue_128942-3.14.0a5%2B-0bcde5c-vs-base.svg)

