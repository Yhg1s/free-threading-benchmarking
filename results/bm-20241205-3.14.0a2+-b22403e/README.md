# Results

- fork: mpage/gh_115999_tlbc_call_
- version: 3.14.0a2+
- config: 
- commit hash: [b22403e](https://github.com/mpage/cpython/commit/b22403e)
- commit date: 2024-12-05T22:12:53-08:00
- commit merge base: [e991ac8f2037d78140e417cc9a9486223eb3e786](https://github.com/python/cpython/commit/e991ac8f2037d78140e417cc9a9486223eb3e786)
- ref: gh_115999_tlbc_call_

## linux x86_64 (vultr)

- [GitHub Action run](https://github.com/facebookexperimental/free-threading-benchmarking/actions/runs/12193968772)
- cpu model: Intel(R) Xeon(R) E-2286G CPU @ 4.00GHz
- platform: Linux-6.8.0-45-generic-x86_64-with-glibc2.39
- [raw results](bm-20241205-vultr-x86_64-mpage-gh_115999_tlbc_call_-3.14.0a2%2B-b22403e.json)

### vs. 3.12.6

- Geometric mean: 1.065x faster (HPT: reliability of 99.95%, 1.01x faster at 99th %ile)
- Memory usage: 1.11x
- missing benchmarks: aiohttp, asyncio_tcp, asyncio_tcp_ssl, chameleon, dask, flaskblogging, gunicorn, html5lib, mypy2, pickle, pickle_dict, pickle_list, tornado_http, unpack_sequence, unpickle, unpickle_list
- new benchmarks: connected_components, k_core, many_optionals, shortest_path, sphinx, subparsers
- [📄table](bm-20241205-vultr-x86_64-mpage-gh_115999_tlbc_call_-3.14.0a2%2B-b22403e-vs-3.12.6.md)
- [📈time plot](bm-20241205-vultr-x86_64-mpage-gh_115999_tlbc_call_-3.14.0a2%2B-b22403e-vs-3.12.6.svg)

### vs. 3.13.0rc2

- Geometric mean: 1.027x faster (HPT: reliability of 83.21%, 1.00x faster at 99th %ile)
- Memory usage: 1.09x
- missing benchmarks: aiohttp, asyncio_tcp, asyncio_tcp_ssl, chameleon, dask, flaskblogging, gunicorn, html5lib, pickle, pickle_dict, pickle_list, tornado_http, unpack_sequence, unpickle, unpickle_list
- new benchmarks: connected_components, k_core, many_optionals, shortest_path, sphinx, sqlalchemy_declarative, sqlalchemy_imperative, subparsers
- [📄table](bm-20241205-vultr-x86_64-mpage-gh_115999_tlbc_call_-3.14.0a2%2B-b22403e-vs-3.13.0rc2.md)
- [📈time plot](bm-20241205-vultr-x86_64-mpage-gh_115999_tlbc_call_-3.14.0a2%2B-b22403e-vs-3.13.0rc2.svg)

### vs. base

- Geometric mean: 1.004x faster (HPT: reliability of 86.70%, 1.00x slower at 99th %ile)
- Memory usage: 1.00x
- [🧠memory plot](bm-20241205-vultr-x86_64-mpage-gh_115999_tlbc_call_-3.14.0a2%2B-b22403e-vs-base-mem.svg)
- [📄table](bm-20241205-vultr-x86_64-mpage-gh_115999_tlbc_call_-3.14.0a2%2B-b22403e-vs-base.md)
- [📈time plot](bm-20241205-vultr-x86_64-mpage-gh_115999_tlbc_call_-3.14.0a2%2B-b22403e-vs-base.svg)

