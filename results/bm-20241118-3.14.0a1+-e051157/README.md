# Results

- fork: mpage
- version: 3.14.0a1+
- config: 
- commit hash: [e051157](https://github.com/mpage/cpython/commit/e051157)
- commit date: 2024-11-18T17:33:09-08:00
- commit merge base: [9d6366b60d01305fc5e45100e0cd13e358aa397d](https://github.com/mpage/cpython/commit/9d6366b60d01305fc5e45100e0cd13e358aa397d)
- ref: gh_115999_tlbc_call_

## linux x86_64 (vultr)

- [GitHub Action run](https://github.com/facebookexperimental/free-threading-benchmarking/actions/runs/11917864398)
- cpu model: Intel(R) Xeon(R) E-2286G CPU @ 4.00GHz
- platform: Linux-6.8.0-45-generic-x86_64-with-glibc2.39
- [raw results](bm-20241118-vultr-x86_64-mpage-gh_115999_tlbc_call_-3.14.0a1%2B-e051157.json)

### vs. 3.12.6

- Geometric mean: 1.00x slower (HPT: reliability of 98.44%, 1.00x faster at 99th %ile)
- Memory usage: 1.02x
- missing benchmarks: aiohttp, async_tree_cpu_io_mixed, async_tree_cpu_io_mixed_tg, async_tree_io, async_tree_io_tg, async_tree_memoization, async_tree_memoization_tg, async_tree_none, async_tree_none_tg, chameleon, dask, flaskblogging, gunicorn, mypy2, sqlalchemy_declarative, sqlalchemy_imperative, tornado_http
- [📄table](bm-20241118-vultr-x86_64-mpage-gh_115999_tlbc_call_-3.14.0a1%2B-e051157-vs-3.12.6.md)
- [📈time plot](bm-20241118-vultr-x86_64-mpage-gh_115999_tlbc_call_-3.14.0a1%2B-e051157-vs-3.12.6.svg)

### vs. 3.13.0rc2

- Geometric mean: 1.02x slower (HPT: reliability of 96.25%, 1.00x slower at 99th %ile)
- Memory usage: 1.00x
- missing benchmarks: aiohttp, async_tree_cpu_io_mixed, async_tree_cpu_io_mixed_tg, async_tree_io, async_tree_io_tg, async_tree_memoization, async_tree_memoization_tg, async_tree_none, async_tree_none_tg, chameleon, dask, flaskblogging, gunicorn, tornado_http
- [📄table](bm-20241118-vultr-x86_64-mpage-gh_115999_tlbc_call_-3.14.0a1%2B-e051157-vs-3.13.0rc2.md)
- [📈time plot](bm-20241118-vultr-x86_64-mpage-gh_115999_tlbc_call_-3.14.0a1%2B-e051157-vs-3.13.0rc2.svg)

### vs. base

- Geometric mean: 1.00x slower (HPT: reliability of 98.86%, 1.00x slower at 99th %ile)
- Memory usage: 1.00x
- [🧠memory plot](bm-20241118-vultr-x86_64-mpage-gh_115999_tlbc_call_-3.14.0a1%2B-e051157-vs-base-mem.svg)
- [📄table](bm-20241118-vultr-x86_64-mpage-gh_115999_tlbc_call_-3.14.0a1%2B-e051157-vs-base.md)
- [📈time plot](bm-20241118-vultr-x86_64-mpage-gh_115999_tlbc_call_-3.14.0a1%2B-e051157-vs-base.svg)

