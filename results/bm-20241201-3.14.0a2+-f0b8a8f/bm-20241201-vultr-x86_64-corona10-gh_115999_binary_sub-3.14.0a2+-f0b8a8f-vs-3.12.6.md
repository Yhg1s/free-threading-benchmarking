# Results vs. 3.12.6

- fork: corona10
- ref: gh_115999_binary_sub
- machine: linux-x86_64
- commit hash: f0b8a8f
- commit date: 2024-12-01
- overall geometric mean: 1.036x faster
- HPT reliability: 99.92%
- HPT 99th percentile: 1.00x faster
- Memory change: 1.11x

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20240906-vultr-x86_64-python-v3.12.6-3.12.6-a4a2d2b | bm-20241201-vultr-x86_64-corona10-gh_115999_binary_sub-3.14.0a2+-f0b8a8f |
|----------------|:------------------------------------------------------:|:------------------------------------------------------------------------:|
| 2to3           | 264 ms                                                 | 258 ms: 1.02x faster                                                     |
| docutils       | 2.64 sec                                               | 2.63 sec: 1.00x faster                                                   |
| Geometric mean | (ref)                                                  | 1.01x faster                                                             |

Benchmarks with tag 'asyncio':
==============================

| Benchmark                  | bm-20240906-vultr-x86_64-python-v3.12.6-3.12.6-a4a2d2b | bm-20241201-vultr-x86_64-corona10-gh_115999_binary_sub-3.14.0a2+-f0b8a8f |
|----------------------------|:------------------------------------------------------:|:------------------------------------------------------------------------:|
| async_tree_memoization_tg  | 560 ms                                                 | 387 ms: 1.45x faster                                                     |
| async_tree_none            | 464 ms                                                 | 331 ms: 1.40x faster                                                     |
| async_tree_memoization     | 555 ms                                                 | 406 ms: 1.37x faster                                                     |
| async_tree_none_tg         | 446 ms                                                 | 345 ms: 1.29x faster                                                     |
| async_tree_io              | 1.08 sec                                               | 839 ms: 1.29x faster                                                     |
| async_tree_cpu_io_mixed_tg | 723 ms                                                 | 567 ms: 1.27x faster                                                     |
| async_tree_io_tg           | 1.11 sec                                               | 877 ms: 1.26x faster                                                     |
| async_tree_cpu_io_mixed    | 715 ms                                                 | 569 ms: 1.26x faster                                                     |
| async_generators           | 384 ms                                                 | 373 ms: 1.03x faster                                                     |
| coroutines                 | 23.9 ms                                                | 23.2 ms: 1.03x faster                                                    |
| asyncio_websockets         | 517 ms                                                 | 522 ms: 1.01x slower                                                     |
| Geometric mean             | (ref)                                                  | 1.23x faster                                                             |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20240906-vultr-x86_64-python-v3.12.6-3.12.6-a4a2d2b | bm-20241201-vultr-x86_64-corona10-gh_115999_binary_sub-3.14.0a2+-f0b8a8f |
|----------------|:------------------------------------------------------:|:------------------------------------------------------------------------:|
| pidigits       | 184 ms                                                 | 187 ms: 1.01x slower                                                     |
| nbody          | 89.3 ms                                                | 96.1 ms: 1.08x slower                                                    |
| Geometric mean | (ref)                                                  | 1.03x slower                                                             |

Benchmark hidden because not significant (1): float

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20240906-vultr-x86_64-python-v3.12.6-3.12.6-a4a2d2b | bm-20241201-vultr-x86_64-corona10-gh_115999_binary_sub-3.14.0a2+-f0b8a8f |
|----------------|:------------------------------------------------------:|:------------------------------------------------------------------------:|
| regex_effbot   | 3.17 ms                                                | 2.69 ms: 1.18x faster                                                    |
| regex_compile  | 142 ms                                                 | 137 ms: 1.04x faster                                                     |
| regex_dna      | 168 ms                                                 | 174 ms: 1.04x slower                                                     |
| regex_v8       | 20.6 ms                                                | 23.0 ms: 1.12x slower                                                    |
| Geometric mean | (ref)                                                  | 1.02x faster                                                             |

Benchmarks with tag 'serialize':
================================

| Benchmark           | bm-20240906-vultr-x86_64-python-v3.12.6-3.12.6-a4a2d2b | bm-20241201-vultr-x86_64-corona10-gh_115999_binary_sub-3.14.0a2+-f0b8a8f |
|---------------------|:------------------------------------------------------:|:------------------------------------------------------------------------:|
| json_loads          | 26.5 us                                                | 25.3 us: 1.05x faster                                                    |
| xml_etree_parse     | 139 ms                                                 | 138 ms: 1.01x faster                                                     |
| tomli_loads         | 2.11 sec                                               | 2.12 sec: 1.01x slower                                                   |
| xml_etree_iterparse | 96.7 ms                                                | 98.6 ms: 1.02x slower                                                    |
| xml_etree_generate  | 85.2 ms                                                | 86.9 ms: 1.02x slower                                                    |
| xml_etree_process   | 59.0 ms                                                | 61.0 ms: 1.03x slower                                                    |
| pickle_pure_python  | 308 us                                                 | 320 us: 1.04x slower                                                     |
| json_dumps          | 10.4 ms                                                | 11.5 ms: 1.11x slower                                                    |
| Geometric mean      | (ref)                                                  | 1.02x slower                                                             |

Benchmark hidden because not significant (1): unpickle_pure_python

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20240906-vultr-x86_64-python-v3.12.6-3.12.6-a4a2d2b | bm-20241201-vultr-x86_64-corona10-gh_115999_binary_sub-3.14.0a2+-f0b8a8f |
|------------------------|:------------------------------------------------------:|:------------------------------------------------------------------------:|
| python_startup_no_site | 7.16 ms                                                | 7.40 ms: 1.03x slower                                                    |
| python_startup         | 9.93 ms                                                | 14.6 ms: 1.47x slower                                                    |
| Geometric mean         | (ref)                                                  | 1.23x slower                                                             |

Benchmarks with tag 'template':
===============================

| Benchmark       | bm-20240906-vultr-x86_64-python-v3.12.6-3.12.6-a4a2d2b | bm-20241201-vultr-x86_64-corona10-gh_115999_binary_sub-3.14.0a2+-f0b8a8f |
|-----------------|:------------------------------------------------------:|:------------------------------------------------------------------------:|
| genshi_text     | 22.8 ms                                                | 22.3 ms: 1.02x faster                                                    |
| django_template | 34.7 ms                                                | 35.6 ms: 1.03x slower                                                    |
| mako            | 11.0 ms                                                | 12.0 ms: 1.09x slower                                                    |
| Geometric mean  | (ref)                                                  | 1.02x slower                                                             |

Benchmark hidden because not significant (1): genshi_xml

All benchmarks:
===============

| Benchmark                  | bm-20240906-vultr-x86_64-python-v3.12.6-3.12.6-a4a2d2b | bm-20241201-vultr-x86_64-corona10-gh_115999_binary_sub-3.14.0a2+-f0b8a8f |
|----------------------------|:------------------------------------------------------:|:------------------------------------------------------------------------:|
| async_tree_memoization_tg  | 560 ms                                                 | 387 ms: 1.45x faster                                                     |
| async_tree_none            | 464 ms                                                 | 331 ms: 1.40x faster                                                     |
| async_tree_memoization     | 555 ms                                                 | 406 ms: 1.37x faster                                                     |
| deepcopy                   | 352 us                                                 | 260 us: 1.35x faster                                                     |
| deepcopy_memo              | 40.3 us                                                | 30.6 us: 1.32x faster                                                    |
| async_tree_none_tg         | 446 ms                                                 | 345 ms: 1.29x faster                                                     |
| async_tree_io              | 1.08 sec                                               | 839 ms: 1.29x faster                                                     |
| async_tree_cpu_io_mixed_tg | 723 ms                                                 | 567 ms: 1.27x faster                                                     |
| async_tree_io_tg           | 1.11 sec                                               | 877 ms: 1.26x faster                                                     |
| async_tree_cpu_io_mixed    | 715 ms                                                 | 569 ms: 1.26x faster                                                     |
| pylint                     | 319 ms                                                 | 270 ms: 1.18x faster                                                     |
| deepcopy_reduce            | 3.08 us                                                | 2.61 us: 1.18x faster                                                    |
| regex_effbot               | 3.17 ms                                                | 2.69 ms: 1.18x faster                                                    |
| pathlib                    | 21.5 ms                                                | 18.6 ms: 1.16x faster                                                    |
| comprehensions             | 19.8 us                                                | 17.5 us: 1.14x faster                                                    |
| sqlalchemy_declarative     | 143 ms                                                 | 127 ms: 1.13x faster                                                     |
| crypto_pyaes               | 76.6 ms                                                | 68.2 ms: 1.12x faster                                                    |
| go                         | 139 ms                                                 | 124 ms: 1.12x faster                                                     |
| sqlalchemy_imperative      | 21.8 ms                                                | 19.6 ms: 1.11x faster                                                    |
| raytrace                   | 299 ms                                                 | 271 ms: 1.11x faster                                                     |
| json                       | 5.02 ms                                                | 4.56 ms: 1.10x faster                                                    |
| sympy_sum                  | 166 ms                                                 | 153 ms: 1.08x faster                                                     |
| bpe_tokeniser              | 4.74 sec                                               | 4.43 sec: 1.07x faster                                                   |
| sympy_str                  | 292 ms                                                 | 273 ms: 1.07x faster                                                     |
| thrift                     | 791 us                                                 | 743 us: 1.07x faster                                                     |
| logging_simple             | 6.63 us                                                | 6.29 us: 1.05x faster                                                    |
| chaos                      | 62.8 ms                                                | 59.8 ms: 1.05x faster                                                    |
| json_loads                 | 26.5 us                                                | 25.3 us: 1.05x faster                                                    |
| regex_compile              | 142 ms                                                 | 137 ms: 1.04x faster                                                     |
| generators                 | 32.2 ms                                                | 31.0 ms: 1.04x faster                                                    |
| logging_format             | 7.35 us                                                | 7.07 us: 1.04x faster                                                    |
| pycparser                  | 1.17 sec                                               | 1.13 sec: 1.04x faster                                                   |
| sqlglot_transpile          | 1.67 ms                                                | 1.61 ms: 1.04x faster                                                    |
| dulwich_log                | 78.9 ms                                                | 76.2 ms: 1.03x faster                                                    |
| async_generators           | 384 ms                                                 | 373 ms: 1.03x faster                                                     |
| coroutines                 | 23.9 ms                                                | 23.2 ms: 1.03x faster                                                    |
| sqlglot_parse              | 1.36 ms                                                | 1.32 ms: 1.03x faster                                                    |
| sympy_integrate            | 20.5 ms                                                | 20.0 ms: 1.03x faster                                                    |
| scimark_monte_carlo        | 68.4 ms                                                | 66.6 ms: 1.03x faster                                                    |
| pprint_safe_repr           | 743 ms                                                 | 724 ms: 1.03x faster                                                     |
| meteor_contest             | 104 ms                                                 | 101 ms: 1.03x faster                                                     |
| pprint_pformat             | 1.52 sec                                               | 1.48 sec: 1.03x faster                                                   |
| typing_runtime_protocols   | 163 us                                                 | 159 us: 1.03x faster                                                     |
| mdp                        | 2.42 sec                                               | 2.36 sec: 1.02x faster                                                   |
| 2to3                       | 264 ms                                                 | 258 ms: 1.02x faster                                                     |
| genshi_text                | 22.8 ms                                                | 22.3 ms: 1.02x faster                                                    |
| sympy_expand               | 468 ms                                                 | 462 ms: 1.01x faster                                                     |
| scimark_fft                | 342 ms                                                 | 338 ms: 1.01x faster                                                     |
| deltablue                  | 3.45 ms                                                | 3.42 ms: 1.01x faster                                                    |
| xml_etree_parse            | 139 ms                                                 | 138 ms: 1.01x faster                                                     |
| nqueens                    | 80.1 ms                                                | 79.6 ms: 1.01x faster                                                    |
| hexiom                     | 6.17 ms                                                | 6.14 ms: 1.01x faster                                                    |
| docutils                   | 2.64 sec                                               | 2.63 sec: 1.00x faster                                                   |
| tomli_loads                | 2.11 sec                                               | 2.12 sec: 1.01x slower                                                   |
| sqlglot_normalize          | 107 ms                                                 | 108 ms: 1.01x slower                                                     |
| asyncio_websockets         | 517 ms                                                 | 522 ms: 1.01x slower                                                     |
| scimark_lu                 | 114 ms                                                 | 116 ms: 1.01x slower                                                     |
| pidigits                   | 184 ms                                                 | 187 ms: 1.01x slower                                                     |
| sqlglot_optimize           | 53.3 ms                                                | 54.0 ms: 1.01x slower                                                    |
| logging_silent             | 109 ns                                                 | 111 ns: 1.01x slower                                                     |
| xml_etree_iterparse        | 96.7 ms                                                | 98.6 ms: 1.02x slower                                                    |
| xml_etree_generate         | 85.2 ms                                                | 86.9 ms: 1.02x slower                                                    |
| sqlite_synth               | 2.20 us                                                | 2.25 us: 1.02x slower                                                    |
| django_template            | 34.7 ms                                                | 35.6 ms: 1.03x slower                                                    |
| spectral_norm              | 110 ms                                                 | 113 ms: 1.03x slower                                                     |
| python_startup_no_site     | 7.16 ms                                                | 7.40 ms: 1.03x slower                                                    |
| xml_etree_process          | 59.0 ms                                                | 61.0 ms: 1.03x slower                                                    |
| regex_dna                  | 168 ms                                                 | 174 ms: 1.04x slower                                                     |
| richards                   | 45.9 ms                                                | 47.8 ms: 1.04x slower                                                    |
| pickle_pure_python         | 308 us                                                 | 320 us: 1.04x slower                                                     |
| scimark_sor                | 130 ms                                                 | 135 ms: 1.04x slower                                                     |
| scimark_sparse_mat_mult    | 4.39 ms                                                | 4.61 ms: 1.05x slower                                                    |
| richards_super             | 51.9 ms                                                | 54.5 ms: 1.05x slower                                                    |
| nbody                      | 89.3 ms                                                | 96.1 ms: 1.08x slower                                                    |
| bench_thread_pool          | 941 us                                                 | 1.02 ms: 1.09x slower                                                    |
| mako                       | 11.0 ms                                                | 12.0 ms: 1.09x slower                                                    |
| json_dumps                 | 10.4 ms                                                | 11.5 ms: 1.11x slower                                                    |
| regex_v8                   | 20.6 ms                                                | 23.0 ms: 1.12x slower                                                    |
| telco                      | 6.53 ms                                                | 7.33 ms: 1.12x slower                                                    |
| coverage                   | 71.4 ms                                                | 80.5 ms: 1.13x slower                                                    |
| gc_traversal               | 3.46 ms                                                | 4.01 ms: 1.16x slower                                                    |
| python_startup             | 9.93 ms                                                | 14.6 ms: 1.47x slower                                                    |
| create_gc_cycles           | 1.09 ms                                                | 1.94 ms: 1.78x slower                                                    |
| bench_mp_pool              | 10.8 ms                                                | 86.3 ms: 8.00x slower                                                    |
| Geometric mean             | (ref)                                                  | 1.01x faster                                                             |

Benchmark hidden because not significant (5): genshi_xml, pyflate, unpickle_pure_python, float, fannkuch
Ignored benchmarks (16) of results/bm-20240906-3.12.6-a4a2d2b/bm-20240906-vultr-x86_64-python-v3.12.6-3.12.6-a4a2d2b.json: aiohttp, asyncio_tcp, asyncio_tcp_ssl, chameleon, dask, flaskblogging, gunicorn, html5lib, mypy2, pickle, pickle_dict, pickle_list, tornado_http, unpack_sequence, unpickle, unpickle_list
Ignored benchmarks (6) of results/bm-20241201-3.14.0a2+-f0b8a8f/bm-20241201-vultr-x86_64-corona10-gh_115999_binary_sub-3.14.0a2+-f0b8a8f.json: connected_components, k_core, many_optionals, shortest_path, sphinx, subparsers

- Geometric mean (including insignificant results): 1.036x faster

# HPT report

- Reliability score: 99.92% likely to be faster
- 90% likely to have a speedup of 1.01x
- 95% likely to have a speedup of 1.01x
- 99% likely to have a speedup of 1.00x

# Memory
- memory change: 1.11x