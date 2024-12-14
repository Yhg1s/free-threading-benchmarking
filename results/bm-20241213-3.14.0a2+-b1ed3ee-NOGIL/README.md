# Results

- fork: mpage/gh_115999_load_attr_
- version: 3.14.0a2+
- config: NOGIL
- commit hash: [b1ed3ee](https://github.com/mpage/cpython/commit/b1ed3ee)
- commit date: 2024-12-13T21:07:57-08:00
- commit merge base: [5dd775bed086909722ec7014a7c4f77a35f74a80](https://github.com/python/cpython/commit/5dd775bed086909722ec7014a7c4f77a35f74a80)
- ref: gh_115999_load_attr_

## linux x86_64 (vultr)

- [GitHub Action run](https://github.com/facebookexperimental/free-threading-benchmarking/actions/runs/12327128480)
- cpu model: Intel(R) Xeon(R) E-2286G CPU @ 4.00GHz
- platform: Linux-6.8.0-45-generic-x86_64-with-glibc2.39
- [raw results](bm-20241213-vultr-x86_64-mpage-gh_115999_load_attr_-3.14.0a2%2B-b1ed3ee.json)

### vs. 3.12.6

- Geometric mean: 1.115x slower (HPT: reliability of 100.00%, 1.09x slower at 99th %ile)
- Memory usage: 1.35x
- missing benchmarks: aiohttp, asyncio_tcp, asyncio_tcp_ssl, chameleon, dask, flaskblogging, gunicorn, mypy2, pickle, pickle_dict, pickle_list, tornado_http, unpack_sequence, unpickle, unpickle_list
- new benchmarks: connected_components, k_core, many_optionals, shortest_path, sphinx, subparsers
- [📄table](bm-20241213-vultr-x86_64-mpage-gh_115999_load_attr_-3.14.0a2%2B-b1ed3ee-vs-3.12.6.md)
- [📈time plot](bm-20241213-vultr-x86_64-mpage-gh_115999_load_attr_-3.14.0a2%2B-b1ed3ee-vs-3.12.6.svg)

### vs. 3.13.0rc2

- Geometric mean: 1.144x slower (HPT: reliability of 100.00%, 1.10x slower at 99th %ile)
- Memory usage: 1.33x
- missing benchmarks: aiohttp, asyncio_tcp, asyncio_tcp_ssl, chameleon, dask, flaskblogging, gunicorn, pickle, pickle_dict, pickle_list, tornado_http, unpack_sequence, unpickle, unpickle_list
- new benchmarks: connected_components, k_core, many_optionals, shortest_path, sphinx, sqlalchemy_declarative, sqlalchemy_imperative, subparsers
- [📄table](bm-20241213-vultr-x86_64-mpage-gh_115999_load_attr_-3.14.0a2%2B-b1ed3ee-vs-3.13.0rc2.md)
- [📈time plot](bm-20241213-vultr-x86_64-mpage-gh_115999_load_attr_-3.14.0a2%2B-b1ed3ee-vs-3.13.0rc2.svg)

### vs. base

- Geometric mean: 1.127x faster (HPT: reliability of 100.00%, 1.05x faster at 99th %ile)
- Memory usage: 1.01x
- [🧠memory plot](bm-20241213-vultr-x86_64-mpage-gh_115999_load_attr_-3.14.0a2%2B-b1ed3ee-vs-base-mem.svg)
- [📄table](bm-20241213-vultr-x86_64-mpage-gh_115999_load_attr_-3.14.0a2%2B-b1ed3ee-vs-base.md)
- [📈time plot](bm-20241213-vultr-x86_64-mpage-gh_115999_load_attr_-3.14.0a2%2B-b1ed3ee-vs-base.svg)

### vs. default_base_vs_NOGIL

- Geometric mean: 1.181x slower (HPT: reliability of 100.00%, 1.14x slower at 99th %ile)
- Memory usage: 1.20x
- new benchmarks: html5lib
- [📄table](bm-20241213-vultr-x86_64-mpage-gh_115999_load_attr_-3.14.0a2%2B-b1ed3ee-vs-default_base_vs_NOGIL.md)
- [📈time plot](bm-20241213-vultr-x86_64-mpage-gh_115999_load_attr_-3.14.0a2%2B-b1ed3ee-vs-default_base_vs_NOGIL.svg)

