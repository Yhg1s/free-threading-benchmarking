# Results vs. 3.13.0rc2

- fork: python
- ref: cdcacec79f7a216c3c98
- machine: linux-x86_64
- commit hash: cdcacec
- commit date: 2025-02-05
- overall geometric mean: 1.073x slower
- HPT reliability: 99.98%
- HPT 99th percentile: 1.04x slower
- Memory change: 1.34x

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20240906-vultr-x86_64-python-v3.13.0rc2-3.13.0rc2-ec61006 | bm-20250205-vultr-x86_64-python-cdcacec79f7a216c3c98-3.14.0a4+-cdcacec |
|----------------|:------------------------------------------------------------:|:----------------------------------------------------------------------:|
| 2to3           | 260 ms                                                       | 302 ms: 1.16x slower                                                   |
| docutils       | 2.62 sec                                                     | 2.82 sec: 1.08x slower                                                 |
| html5lib       | 67.0 ms                                                      | 71.9 ms: 1.07x slower                                                  |
| Geometric mean | (ref)                                                        | 1.10x slower                                                           |

Benchmarks with tag 'asyncio':
==============================

| Benchmark                  | bm-20240906-vultr-x86_64-python-v3.13.0rc2-3.13.0rc2-ec61006 | bm-20250205-vultr-x86_64-python-cdcacec79f7a216c3c98-3.14.0a4+-cdcacec |
|----------------------------|:------------------------------------------------------------:|:----------------------------------------------------------------------:|
| async_tree_io_tg           | 913 ms                                                       | 564 ms: 1.62x faster                                                   |
| async_tree_io              | 876 ms                                                       | 596 ms: 1.47x faster                                                   |
| async_tree_none_tg         | 336 ms                                                       | 243 ms: 1.38x faster                                                   |
| async_tree_memoization     | 461 ms                                                       | 347 ms: 1.33x faster                                                   |
| async_tree_memoization_tg  | 414 ms                                                       | 312 ms: 1.33x faster                                                   |
| async_tree_cpu_io_mixed_tg | 638 ms                                                       | 501 ms: 1.27x faster                                                   |
| async_tree_none            | 354 ms                                                       | 283 ms: 1.25x faster                                                   |
| async_tree_cpu_io_mixed    | 666 ms                                                       | 534 ms: 1.25x faster                                                   |
| async_generators           | 377 ms                                                       | 372 ms: 1.01x faster                                                   |
| asyncio_websockets         | 520 ms                                                       | 516 ms: 1.01x faster                                                   |
| coroutines                 | 23.6 ms                                                      | 23.4 ms: 1.01x faster                                                  |
| Geometric mean             | (ref)                                                        | 1.25x faster                                                           |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20240906-vultr-x86_64-python-v3.13.0rc2-3.13.0rc2-ec61006 | bm-20250205-vultr-x86_64-python-cdcacec79f7a216c3c98-3.14.0a4+-cdcacec |
|----------------|:------------------------------------------------------------:|:----------------------------------------------------------------------:|
| pidigits       | 217 ms                                                       | 196 ms: 1.11x faster                                                   |
| float          | 77.5 ms                                                      | 76.5 ms: 1.01x faster                                                  |
| nbody          | 85.1 ms                                                      | 130 ms: 1.53x slower                                                   |
| Geometric mean | (ref)                                                        | 1.11x slower                                                           |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20240906-vultr-x86_64-python-v3.13.0rc2-3.13.0rc2-ec61006 | bm-20250205-vultr-x86_64-python-cdcacec79f7a216c3c98-3.14.0a4+-cdcacec |
|----------------|:------------------------------------------------------------:|:----------------------------------------------------------------------:|
| regex_effbot   | 3.08 ms                                                      | 2.85 ms: 1.08x faster                                                  |
| regex_dna      | 180 ms                                                       | 187 ms: 1.04x slower                                                   |
| regex_v8       | 22.7 ms                                                      | 24.4 ms: 1.08x slower                                                  |
| regex_compile  | 132 ms                                                       | 151 ms: 1.14x slower                                                   |
| Geometric mean | (ref)                                                        | 1.04x slower                                                           |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20240906-vultr-x86_64-python-v3.13.0rc2-3.13.0rc2-ec61006 | bm-20250205-vultr-x86_64-python-cdcacec79f7a216c3c98-3.14.0a4+-cdcacec |
|----------------------|:------------------------------------------------------------:|:----------------------------------------------------------------------:|
| xml_etree_iterparse  | 94.9 ms                                                      | 87.4 ms: 1.09x faster                                                  |
| xml_etree_parse      | 136 ms                                                       | 129 ms: 1.06x faster                                                   |
| xml_etree_generate   | 85.4 ms                                                      | 96.1 ms: 1.12x slower                                                  |
| xml_etree_process    | 59.3 ms                                                      | 68.3 ms: 1.15x slower                                                  |
| json_loads           | 27.0 us                                                      | 31.1 us: 1.15x slower                                                  |
| unpickle_pure_python | 210 us                                                       | 244 us: 1.16x slower                                                   |
| tomli_loads          | 2.01 sec                                                     | 2.35 sec: 1.17x slower                                                 |
| json_dumps           | 10.5 ms                                                      | 12.8 ms: 1.22x slower                                                  |
| pickle_pure_python   | 294 us                                                       | 367 us: 1.25x slower                                                   |
| Geometric mean       | (ref)                                                        | 1.12x slower                                                           |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20240906-vultr-x86_64-python-v3.13.0rc2-3.13.0rc2-ec61006 | bm-20250205-vultr-x86_64-python-cdcacec79f7a216c3c98-3.14.0a4+-cdcacec |
|------------------------|:------------------------------------------------------------:|:----------------------------------------------------------------------:|
| python_startup_no_site | 7.39 ms                                                      | 9.62 ms: 1.30x slower                                                  |
| python_startup         | 11.0 ms                                                      | 15.3 ms: 1.40x slower                                                  |
| Geometric mean         | (ref)                                                        | 1.35x slower                                                           |

Benchmarks with tag 'template':
===============================

| Benchmark       | bm-20240906-vultr-x86_64-python-v3.13.0rc2-3.13.0rc2-ec61006 | bm-20250205-vultr-x86_64-python-cdcacec79f7a216c3c98-3.14.0a4+-cdcacec |
|-----------------|:------------------------------------------------------------:|:----------------------------------------------------------------------:|
| genshi_xml      | 48.8 ms                                                      | 58.0 ms: 1.19x slower                                                  |
| django_template | 34.1 ms                                                      | 41.3 ms: 1.21x slower                                                  |
| genshi_text     | 21.5 ms                                                      | 27.5 ms: 1.28x slower                                                  |
| mako            | 11.3 ms                                                      | 16.0 ms: 1.41x slower                                                  |
| Geometric mean  | (ref)                                                        | 1.27x slower                                                           |

All benchmarks:
===============

| Benchmark                  | bm-20240906-vultr-x86_64-python-v3.13.0rc2-3.13.0rc2-ec61006 | bm-20250205-vultr-x86_64-python-cdcacec79f7a216c3c98-3.14.0a4+-cdcacec |
|----------------------------|:------------------------------------------------------------:|:----------------------------------------------------------------------:|
| gc_traversal               | 3.14 ms                                                      | 1.75 ms: 1.79x faster                                                  |
| async_tree_io_tg           | 913 ms                                                       | 564 ms: 1.62x faster                                                   |
| async_tree_io              | 876 ms                                                       | 596 ms: 1.47x faster                                                   |
| async_tree_none_tg         | 336 ms                                                       | 243 ms: 1.38x faster                                                   |
| async_tree_memoization     | 461 ms                                                       | 347 ms: 1.33x faster                                                   |
| async_tree_memoization_tg  | 414 ms                                                       | 312 ms: 1.33x faster                                                   |
| async_tree_cpu_io_mixed_tg | 638 ms                                                       | 501 ms: 1.27x faster                                                   |
| async_tree_none            | 354 ms                                                       | 283 ms: 1.25x faster                                                   |
| async_tree_cpu_io_mixed    | 666 ms                                                       | 534 ms: 1.25x faster                                                   |
| deepcopy                   | 355 us                                                       | 306 us: 1.16x faster                                                   |
| pidigits                   | 217 ms                                                       | 196 ms: 1.11x faster                                                   |
| sqlite_synth               | 2.21 us                                                      | 2.02 us: 1.10x faster                                                  |
| xml_etree_iterparse        | 94.9 ms                                                      | 87.4 ms: 1.09x faster                                                  |
| regex_effbot               | 3.08 ms                                                      | 2.85 ms: 1.08x faster                                                  |
| xml_etree_parse            | 136 ms                                                       | 129 ms: 1.06x faster                                                   |
| deepcopy_memo              | 39.1 us                                                      | 37.7 us: 1.04x faster                                                  |
| scimark_sor                | 134 ms                                                       | 130 ms: 1.03x faster                                                   |
| go                         | 141 ms                                                       | 138 ms: 1.02x faster                                                   |
| pathlib                    | 19.2 ms                                                      | 18.8 ms: 1.02x faster                                                  |
| spectral_norm              | 111 ms                                                       | 109 ms: 1.02x faster                                                   |
| async_generators           | 377 ms                                                       | 372 ms: 1.01x faster                                                   |
| float                      | 77.5 ms                                                      | 76.5 ms: 1.01x faster                                                  |
| asyncio_websockets         | 520 ms                                                       | 516 ms: 1.01x faster                                                   |
| coroutines                 | 23.6 ms                                                      | 23.4 ms: 1.01x faster                                                  |
| deepcopy_reduce            | 3.11 us                                                      | 3.14 us: 1.01x slower                                                  |
| regex_dna                  | 180 ms                                                       | 187 ms: 1.04x slower                                                   |
| bpe_tokeniser              | 4.45 sec                                                     | 4.64 sec: 1.04x slower                                                 |
| create_gc_cycles           | 1.34 ms                                                      | 1.40 ms: 1.05x slower                                                  |
| pycparser                  | 1.12 sec                                                     | 1.18 sec: 1.06x slower                                                 |
| html5lib                   | 67.0 ms                                                      | 71.9 ms: 1.07x slower                                                  |
| docutils                   | 2.62 sec                                                     | 2.82 sec: 1.08x slower                                                 |
| regex_v8                   | 22.7 ms                                                      | 24.4 ms: 1.08x slower                                                  |
| telco                      | 7.82 ms                                                      | 8.42 ms: 1.08x slower                                                  |
| pyflate                    | 449 ms                                                       | 489 ms: 1.09x slower                                                   |
| json                       | 4.93 ms                                                      | 5.38 ms: 1.09x slower                                                  |
| pprint_safe_repr           | 738 ms                                                       | 805 ms: 1.09x slower                                                   |
| logging_silent             | 103 ns                                                       | 113 ns: 1.10x slower                                                   |
| scimark_fft                | 349 ms                                                       | 385 ms: 1.10x slower                                                   |
| dulwich_log                | 74.8 ms                                                      | 82.5 ms: 1.10x slower                                                  |
| generators                 | 28.8 ms                                                      | 32.0 ms: 1.11x slower                                                  |
| pprint_pformat             | 1.50 sec                                                     | 1.67 sec: 1.12x slower                                                 |
| xml_etree_generate         | 85.4 ms                                                      | 96.1 ms: 1.12x slower                                                  |
| sqlglot_normalize          | 106 ms                                                       | 119 ms: 1.13x slower                                                   |
| mdp                        | 2.36 sec                                                     | 2.68 sec: 1.14x slower                                                 |
| regex_compile              | 132 ms                                                       | 151 ms: 1.14x slower                                                   |
| thrift                     | 778 us                                                       | 893 us: 1.15x slower                                                   |
| xml_etree_process          | 59.3 ms                                                      | 68.3 ms: 1.15x slower                                                  |
| sqlglot_optimize           | 52.7 ms                                                      | 60.7 ms: 1.15x slower                                                  |
| json_loads                 | 27.0 us                                                      | 31.1 us: 1.15x slower                                                  |
| unpickle_pure_python       | 210 us                                                       | 244 us: 1.16x slower                                                   |
| coverage                   | 83.0 ms                                                      | 96.5 ms: 1.16x slower                                                  |
| 2to3                       | 260 ms                                                       | 302 ms: 1.16x slower                                                   |
| logging_simple             | 6.16 us                                                      | 7.19 us: 1.17x slower                                                  |
| tomli_loads                | 2.01 sec                                                     | 2.35 sec: 1.17x slower                                                 |
| scimark_sparse_mat_mult    | 4.71 ms                                                      | 5.54 ms: 1.18x slower                                                  |
| sympy_sum                  | 156 ms                                                       | 185 ms: 1.19x slower                                                   |
| chaos                      | 57.3 ms                                                      | 68.1 ms: 1.19x slower                                                  |
| genshi_xml                 | 48.8 ms                                                      | 58.0 ms: 1.19x slower                                                  |
| comprehensions             | 16.5 us                                                      | 19.7 us: 1.20x slower                                                  |
| sympy_expand               | 457 ms                                                       | 549 ms: 1.20x slower                                                   |
| sympy_integrate            | 19.8 ms                                                      | 23.9 ms: 1.21x slower                                                  |
| django_template            | 34.1 ms                                                      | 41.3 ms: 1.21x slower                                                  |
| scimark_lu                 | 113 ms                                                       | 136 ms: 1.21x slower                                                   |
| logging_format             | 6.84 us                                                      | 8.28 us: 1.21x slower                                                  |
| json_dumps                 | 10.5 ms                                                      | 12.8 ms: 1.22x slower                                                  |
| nqueens                    | 78.6 ms                                                      | 95.6 ms: 1.22x slower                                                  |
| sqlglot_transpile          | 1.56 ms                                                      | 1.90 ms: 1.22x slower                                                  |
| sympy_str                  | 275 ms                                                       | 334 ms: 1.22x slower                                                   |
| richards                   | 45.2 ms                                                      | 55.5 ms: 1.23x slower                                                  |
| hexiom                     | 5.99 ms                                                      | 7.40 ms: 1.24x slower                                                  |
| richards_super             | 51.6 ms                                                      | 64.2 ms: 1.24x slower                                                  |
| pickle_pure_python         | 294 us                                                       | 367 us: 1.25x slower                                                   |
| scimark_monte_carlo        | 65.4 ms                                                      | 81.6 ms: 1.25x slower                                                  |
| sqlglot_parse              | 1.25 ms                                                      | 1.57 ms: 1.26x slower                                                  |
| raytrace                   | 253 ms                                                       | 322 ms: 1.28x slower                                                   |
| genshi_text                | 21.5 ms                                                      | 27.5 ms: 1.28x slower                                                  |
| meteor_contest             | 102 ms                                                       | 131 ms: 1.28x slower                                                   |
| typing_runtime_protocols   | 155 us                                                       | 199 us: 1.29x slower                                                   |
| crypto_pyaes               | 67.9 ms                                                      | 88.2 ms: 1.30x slower                                                  |
| python_startup_no_site     | 7.39 ms                                                      | 9.62 ms: 1.30x slower                                                  |
| fannkuch                   | 370 ms                                                       | 484 ms: 1.31x slower                                                   |
| python_startup             | 11.0 ms                                                      | 15.3 ms: 1.40x slower                                                  |
| mako                       | 11.3 ms                                                      | 16.0 ms: 1.41x slower                                                  |
| deltablue                  | 3.12 ms                                                      | 4.63 ms: 1.48x slower                                                  |
| nbody                      | 85.1 ms                                                      | 130 ms: 1.53x slower                                                   |
| bench_thread_pool          | 919 us                                                       | 3.31 ms: 3.60x slower                                                  |
| bench_mp_pool              | 11.0 ms                                                      | 94.8 ms: 8.62x slower                                                  |
| Geometric mean             | (ref)                                                        | 1.12x slower                                                           |

Benchmark hidden because not significant (1): pylint
Ignored benchmarks (14) of results/bm-20240906-3.13.0rc2-ec61006/bm-20240906-vultr-x86_64-python-v3.13.0rc2-3.13.0rc2-ec61006.json: aiohttp, asyncio_tcp, asyncio_tcp_ssl, chameleon, dask, flaskblogging, gunicorn, pickle, pickle_dict, pickle_list, tornado_http, unpack_sequence, unpickle, unpickle_list
Ignored benchmarks (8) of results/bm-20250205-3.14.0a4+-cdcacec-NOGIL/bm-20250205-vultr-x86_64-python-cdcacec79f7a216c3c98-3.14.0a4+-cdcacec.json: connected_components, k_core, many_optionals, shortest_path, sphinx, sqlalchemy_declarative, sqlalchemy_imperative, subparsers

- Geometric mean (including insignificant results): 1.073x slower

# HPT report

- Reliability score: 99.98% likely to be slow
- 90% likely to have a slowdown of 1.07x
- 95% likely to have a slowdown of 1.06x
- 99% likely to have a slowdown of 1.04x

# Memory
- memory change: 1.34x