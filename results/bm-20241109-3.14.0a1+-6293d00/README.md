# Results

- fork: python
- version: 3.14.0a1+
- config: 
- commit hash: [6293d00](https://github.com/python/cpython/commit/6293d00)
- commit date: 2024-11-09T11:35:33+08:00
- commit merge base: [f8276bf5f37ef12aa0033634151fa33a6f7bd4f2](https://github.com/python/cpython/commit/f8276bf5f37ef12aa0033634151fa33a6f7bd4f2)
- ref: 6293d00e7201f3f28b1f

## linux x86_64 (vultr)

- [GitHub Action run](https://github.com/facebookexperimental/free-threading-benchmarking/actions/runs/11803760194)
- cpu model: Intel(R) Xeon(R) E-2286G CPU @ 4.00GHz
- platform: Linux-6.8.0-45-generic-x86_64-with-glibc2.39
- [raw results](bm-20241109-vultr-x86_64-python-6293d00e7201f3f28b1f-3.14.0a1%2B-6293d00.json)

### vs. 3.12.6

- Geometric mean: 1.017x faster (HPT: reliability of 99.11%, 1.00x faster at 99th %ile)
- Memory usage: 1.02x
- missing benchmarks: aiohttp, async_tree_cpu_io_mixed, async_tree_cpu_io_mixed_tg, async_tree_io, async_tree_io_tg, async_tree_memoization, async_tree_memoization_tg, async_tree_none, async_tree_none_tg, chameleon, dask, flaskblogging, gunicorn, mypy2, sqlalchemy_declarative, sqlalchemy_imperative, tornado_http
- [📄table](bm-20241109-vultr-x86_64-python-6293d00e7201f3f28b1f-3.14.0a1%2B-6293d00-vs-3.12.6.md)
- [📈time plot](bm-20241109-vultr-x86_64-python-6293d00e7201f3f28b1f-3.14.0a1%2B-6293d00-vs-3.12.6.svg)

### vs. 3.13.0rc2

- Geometric mean: 1.001x faster (HPT: reliability of 89.10%, 1.00x slower at 99th %ile)
- Memory usage: 1.00x
- missing benchmarks: aiohttp, async_tree_cpu_io_mixed, async_tree_cpu_io_mixed_tg, async_tree_io, async_tree_io_tg, async_tree_memoization, async_tree_memoization_tg, async_tree_none, async_tree_none_tg, chameleon, dask, flaskblogging, gunicorn, tornado_http
- [📄table](bm-20241109-vultr-x86_64-python-6293d00e7201f3f28b1f-3.14.0a1%2B-6293d00-vs-3.13.0rc2.md)
- [📈time plot](bm-20241109-vultr-x86_64-python-6293d00e7201f3f28b1f-3.14.0a1%2B-6293d00-vs-3.13.0rc2.svg)

