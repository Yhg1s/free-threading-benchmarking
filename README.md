# Faster CPython Benchmark Infrastructure

🔒 [▶️ START A BENCHMARK RUN](../../actions/workflows/benchmark.yml)

## Results

Here are some recent and important revisions. 👉 [Complete list of results](RESULTS.md).

<!-- START table -->
[Most recent pystats on main (c9932a9)](results/bm-20250301-3.14.0a5%2B-c9932a9-PYTHON_UOPS/bm-20250301-linux-x86_64-python-c9932a9ec8a3077933a8-3.14.0a5%2B-c9932a9-pystats.md)

## linux x86_64 (linux)
| date | fork/ref | hash/flags | vs. 3.12.6: | vs. 3.13.0rc2: | vs. base: |
| --- | --- | --- | ---: | ---: | ---: |
| [2025-03-09](results/bm-20250309-3.14.0a5%2B-98fa4a4) | python/98fa4a49fecbac3c990a | 98fa4a4 | 1.110x ↑<br>[📄](results/bm-20250309-3.14.0a5%2B-98fa4a4/bm-20250309-linux-x86_64-python-98fa4a49fecbac3c990a-3.14.0a5%2B-98fa4a4-vs-3.12.6.md)[📈](results/bm-20250309-3.14.0a5%2B-98fa4a4/bm-20250309-linux-x86_64-python-98fa4a49fecbac3c990a-3.14.0a5%2B-98fa4a4-vs-3.12.6.svg) | 1.065x ↑<br>[📄](results/bm-20250309-3.14.0a5%2B-98fa4a4/bm-20250309-linux-x86_64-python-98fa4a49fecbac3c990a-3.14.0a5%2B-98fa4a4-vs-3.13.0rc2.md)[📈](results/bm-20250309-3.14.0a5%2B-98fa4a4/bm-20250309-linux-x86_64-python-98fa4a49fecbac3c990a-3.14.0a5%2B-98fa4a4-vs-3.13.0rc2.svg) |  |
| [2025-03-09](results/bm-20250309-3.14.0a5%2B-98fa4a4-NOGIL) | python/98fa4a49fecbac3c990a | 98fa4a4 (NOGIL) | 1.023x ↓<br>[📄](results/bm-20250309-3.14.0a5%2B-98fa4a4-NOGIL/bm-20250309-linux-x86_64-python-98fa4a49fecbac3c990a-3.14.0a5%2B-98fa4a4-vs-3.12.6.md)[📈](results/bm-20250309-3.14.0a5%2B-98fa4a4-NOGIL/bm-20250309-linux-x86_64-python-98fa4a49fecbac3c990a-3.14.0a5%2B-98fa4a4-vs-3.12.6.svg) | 1.058x ↓<br>[📄](results/bm-20250309-3.14.0a5%2B-98fa4a4-NOGIL/bm-20250309-linux-x86_64-python-98fa4a49fecbac3c990a-3.14.0a5%2B-98fa4a4-vs-3.13.0rc2.md)[📈](results/bm-20250309-3.14.0a5%2B-98fa4a4-NOGIL/bm-20250309-linux-x86_64-python-98fa4a49fecbac3c990a-3.14.0a5%2B-98fa4a4-vs-3.13.0rc2.svg) | 1.117x ↓<br>[📄](results/bm-20250309-3.14.0a5%2B-98fa4a4-NOGIL/bm-20250309-linux-x86_64-python-98fa4a49fecbac3c990a-3.14.0a5%2B-98fa4a4-vs-base.md)[📈](results/bm-20250309-3.14.0a5%2B-98fa4a4-NOGIL/bm-20250309-linux-x86_64-python-98fa4a49fecbac3c990a-3.14.0a5%2B-98fa4a4-vs-base.svg)[🧠](results/bm-20250309-3.14.0a5%2B-98fa4a4-NOGIL/bm-20250309-linux-x86_64-python-98fa4a49fecbac3c990a-3.14.0a5%2B-98fa4a4-vs-base-mem.svg) |
| [2025-03-08](results/bm-20250308-3.14.0a5%2B-a3990df) | python/a3990df6121880e8c678 | a3990df | 1.107x ↑<br>[📄](results/bm-20250308-3.14.0a5%2B-a3990df/bm-20250308-linux-x86_64-python-a3990df6121880e8c678-3.14.0a5%2B-a3990df-vs-3.12.6.md)[📈](results/bm-20250308-3.14.0a5%2B-a3990df/bm-20250308-linux-x86_64-python-a3990df6121880e8c678-3.14.0a5%2B-a3990df-vs-3.12.6.svg) | 1.066x ↑<br>[📄](results/bm-20250308-3.14.0a5%2B-a3990df/bm-20250308-linux-x86_64-python-a3990df6121880e8c678-3.14.0a5%2B-a3990df-vs-3.13.0rc2.md)[📈](results/bm-20250308-3.14.0a5%2B-a3990df/bm-20250308-linux-x86_64-python-a3990df6121880e8c678-3.14.0a5%2B-a3990df-vs-3.13.0rc2.svg) |  |
| [2025-03-08](results/bm-20250308-3.14.0a5%2B-a3990df-NOGIL) | python/a3990df6121880e8c678 | a3990df (NOGIL) | 1.006x ↓<br>[📄](results/bm-20250308-3.14.0a5%2B-a3990df-NOGIL/bm-20250308-linux-x86_64-python-a3990df6121880e8c678-3.14.0a5%2B-a3990df-vs-3.12.6.md)[📈](results/bm-20250308-3.14.0a5%2B-a3990df-NOGIL/bm-20250308-linux-x86_64-python-a3990df6121880e8c678-3.14.0a5%2B-a3990df-vs-3.12.6.svg) | 1.044x ↓<br>[📄](results/bm-20250308-3.14.0a5%2B-a3990df-NOGIL/bm-20250308-linux-x86_64-python-a3990df6121880e8c678-3.14.0a5%2B-a3990df-vs-3.13.0rc2.md)[📈](results/bm-20250308-3.14.0a5%2B-a3990df-NOGIL/bm-20250308-linux-x86_64-python-a3990df6121880e8c678-3.14.0a5%2B-a3990df-vs-3.13.0rc2.svg) | 1.098x ↓<br>[📄](results/bm-20250308-3.14.0a5%2B-a3990df-NOGIL/bm-20250308-linux-x86_64-python-a3990df6121880e8c678-3.14.0a5%2B-a3990df-vs-base.md)[📈](results/bm-20250308-3.14.0a5%2B-a3990df-NOGIL/bm-20250308-linux-x86_64-python-a3990df6121880e8c678-3.14.0a5%2B-a3990df-vs-base.svg)[🧠](results/bm-20250308-3.14.0a5%2B-a3990df-NOGIL/bm-20250308-linux-x86_64-python-a3990df6121880e8c678-3.14.0a5%2B-a3990df-vs-base-mem.svg) |
| [2025-03-07](results/bm-20250307-3.14.0a5%2B-7879081) | python/78790811989ab47319e2 | 7879081 | 1.109x ↑<br>[📄](results/bm-20250307-3.14.0a5%2B-7879081/bm-20250307-linux-x86_64-python-78790811989ab47319e2-3.14.0a5%2B-7879081-vs-3.12.6.md)[📈](results/bm-20250307-3.14.0a5%2B-7879081/bm-20250307-linux-x86_64-python-78790811989ab47319e2-3.14.0a5%2B-7879081-vs-3.12.6.svg) | 1.066x ↑<br>[📄](results/bm-20250307-3.14.0a5%2B-7879081/bm-20250307-linux-x86_64-python-78790811989ab47319e2-3.14.0a5%2B-7879081-vs-3.13.0rc2.md)[📈](results/bm-20250307-3.14.0a5%2B-7879081/bm-20250307-linux-x86_64-python-78790811989ab47319e2-3.14.0a5%2B-7879081-vs-3.13.0rc2.svg) |  |
| [2025-03-07](results/bm-20250307-3.14.0a5%2B-7879081-NOGIL) | python/78790811989ab47319e2 | 7879081 (NOGIL) | 1.019x ↓<br>[📄](results/bm-20250307-3.14.0a5%2B-7879081-NOGIL/bm-20250307-linux-x86_64-python-78790811989ab47319e2-3.14.0a5%2B-7879081-vs-3.12.6.md)[📈](results/bm-20250307-3.14.0a5%2B-7879081-NOGIL/bm-20250307-linux-x86_64-python-78790811989ab47319e2-3.14.0a5%2B-7879081-vs-3.12.6.svg) | 1.054x ↓<br>[📄](results/bm-20250307-3.14.0a5%2B-7879081-NOGIL/bm-20250307-linux-x86_64-python-78790811989ab47319e2-3.14.0a5%2B-7879081-vs-3.13.0rc2.md)[📈](results/bm-20250307-3.14.0a5%2B-7879081-NOGIL/bm-20250307-linux-x86_64-python-78790811989ab47319e2-3.14.0a5%2B-7879081-vs-3.13.0rc2.svg) | 1.114x ↓<br>[📄](results/bm-20250307-3.14.0a5%2B-7879081-NOGIL/bm-20250307-linux-x86_64-python-78790811989ab47319e2-3.14.0a5%2B-7879081-vs-base.md)[📈](results/bm-20250307-3.14.0a5%2B-7879081-NOGIL/bm-20250307-linux-x86_64-python-78790811989ab47319e2-3.14.0a5%2B-7879081-vs-base.svg)[🧠](results/bm-20250307-3.14.0a5%2B-7879081-NOGIL/bm-20250307-linux-x86_64-python-78790811989ab47319e2-3.14.0a5%2B-7879081-vs-base-mem.svg) |
| [2025-03-06](results/bm-20250306-3.14.0a5%2B-a385add) | python/a385add4015c431534e2 | a385add | 1.101x ↑<br>[📄](results/bm-20250306-3.14.0a5%2B-a385add/bm-20250306-linux-x86_64-python-a385add4015c431534e2-3.14.0a5%2B-a385add-vs-3.12.6.md)[📈](results/bm-20250306-3.14.0a5%2B-a385add/bm-20250306-linux-x86_64-python-a385add4015c431534e2-3.14.0a5%2B-a385add-vs-3.12.6.svg) | 1.054x ↑<br>[📄](results/bm-20250306-3.14.0a5%2B-a385add/bm-20250306-linux-x86_64-python-a385add4015c431534e2-3.14.0a5%2B-a385add-vs-3.13.0rc2.md)[📈](results/bm-20250306-3.14.0a5%2B-a385add/bm-20250306-linux-x86_64-python-a385add4015c431534e2-3.14.0a5%2B-a385add-vs-3.13.0rc2.svg) |  |
| [2025-03-06](results/bm-20250306-3.14.0a5%2B-a385add-NOGIL) | python/a385add4015c431534e2 | a385add (NOGIL) | 1.031x ↓<br>[📄](results/bm-20250306-3.14.0a5%2B-a385add-NOGIL/bm-20250306-linux-x86_64-python-a385add4015c431534e2-3.14.0a5%2B-a385add-vs-3.12.6.md)[📈](results/bm-20250306-3.14.0a5%2B-a385add-NOGIL/bm-20250306-linux-x86_64-python-a385add4015c431534e2-3.14.0a5%2B-a385add-vs-3.12.6.svg) | 1.063x ↓<br>[📄](results/bm-20250306-3.14.0a5%2B-a385add-NOGIL/bm-20250306-linux-x86_64-python-a385add4015c431534e2-3.14.0a5%2B-a385add-vs-3.13.0rc2.md)[📈](results/bm-20250306-3.14.0a5%2B-a385add-NOGIL/bm-20250306-linux-x86_64-python-a385add4015c431534e2-3.14.0a5%2B-a385add-vs-3.13.0rc2.svg) | 1.116x ↓<br>[📄](results/bm-20250306-3.14.0a5%2B-a385add-NOGIL/bm-20250306-linux-x86_64-python-a385add4015c431534e2-3.14.0a5%2B-a385add-vs-base.md)[📈](results/bm-20250306-3.14.0a5%2B-a385add-NOGIL/bm-20250306-linux-x86_64-python-a385add4015c431534e2-3.14.0a5%2B-a385add-vs-base.svg)[🧠](results/bm-20250306-3.14.0a5%2B-a385add-NOGIL/bm-20250306-linux-x86_64-python-a385add4015c431534e2-3.14.0a5%2B-a385add-vs-base-mem.svg) |

## linux x86_64 (vultr)
| date | fork/ref | hash/flags | vs. 3.12.6: | vs. 3.13.0rc2: | vs. base: |
| --- | --- | --- | ---: | ---: | ---: |
| [2025-03-09](results/bm-20250309-3.14.0a5%2B-98fa4a4) | python/98fa4a49fecbac3c990a | 98fa4a4 | 1.115x ↑<br>[📄](results/bm-20250309-3.14.0a5%2B-98fa4a4/bm-20250309-vultr-x86_64-python-98fa4a49fecbac3c990a-3.14.0a5%2B-98fa4a4-vs-3.12.6.md)[📈](results/bm-20250309-3.14.0a5%2B-98fa4a4/bm-20250309-vultr-x86_64-python-98fa4a49fecbac3c990a-3.14.0a5%2B-98fa4a4-vs-3.12.6.svg) | 1.074x ↑<br>[📄](results/bm-20250309-3.14.0a5%2B-98fa4a4/bm-20250309-vultr-x86_64-python-98fa4a49fecbac3c990a-3.14.0a5%2B-98fa4a4-vs-3.13.0rc2.md)[📈](results/bm-20250309-3.14.0a5%2B-98fa4a4/bm-20250309-vultr-x86_64-python-98fa4a49fecbac3c990a-3.14.0a5%2B-98fa4a4-vs-3.13.0rc2.svg) |  |
| [2025-03-09](results/bm-20250309-3.14.0a5%2B-98fa4a4-NOGIL) | python/98fa4a49fecbac3c990a | 98fa4a4 (NOGIL) | 1.046x ↓<br>[📄](results/bm-20250309-3.14.0a5%2B-98fa4a4-NOGIL/bm-20250309-vultr-x86_64-python-98fa4a49fecbac3c990a-3.14.0a5%2B-98fa4a4-vs-3.12.6.md)[📈](results/bm-20250309-3.14.0a5%2B-98fa4a4-NOGIL/bm-20250309-vultr-x86_64-python-98fa4a49fecbac3c990a-3.14.0a5%2B-98fa4a4-vs-3.12.6.svg) | 1.078x ↓<br>[📄](results/bm-20250309-3.14.0a5%2B-98fa4a4-NOGIL/bm-20250309-vultr-x86_64-python-98fa4a49fecbac3c990a-3.14.0a5%2B-98fa4a4-vs-3.13.0rc2.md)[📈](results/bm-20250309-3.14.0a5%2B-98fa4a4-NOGIL/bm-20250309-vultr-x86_64-python-98fa4a49fecbac3c990a-3.14.0a5%2B-98fa4a4-vs-3.13.0rc2.svg) | 1.144x ↓<br>[📄](results/bm-20250309-3.14.0a5%2B-98fa4a4-NOGIL/bm-20250309-vultr-x86_64-python-98fa4a49fecbac3c990a-3.14.0a5%2B-98fa4a4-vs-base.md)[📈](results/bm-20250309-3.14.0a5%2B-98fa4a4-NOGIL/bm-20250309-vultr-x86_64-python-98fa4a49fecbac3c990a-3.14.0a5%2B-98fa4a4-vs-base.svg)[🧠](results/bm-20250309-3.14.0a5%2B-98fa4a4-NOGIL/bm-20250309-vultr-x86_64-python-98fa4a49fecbac3c990a-3.14.0a5%2B-98fa4a4-vs-base-mem.svg) |
| [2025-03-08](results/bm-20250308-3.14.0a5%2B-a3990df) | python/a3990df6121880e8c678 | a3990df | 1.102x ↑<br>[📄](results/bm-20250308-3.14.0a5%2B-a3990df/bm-20250308-vultr-x86_64-python-a3990df6121880e8c678-3.14.0a5%2B-a3990df-vs-3.12.6.md)[📈](results/bm-20250308-3.14.0a5%2B-a3990df/bm-20250308-vultr-x86_64-python-a3990df6121880e8c678-3.14.0a5%2B-a3990df-vs-3.12.6.svg) | 1.061x ↑<br>[📄](results/bm-20250308-3.14.0a5%2B-a3990df/bm-20250308-vultr-x86_64-python-a3990df6121880e8c678-3.14.0a5%2B-a3990df-vs-3.13.0rc2.md)[📈](results/bm-20250308-3.14.0a5%2B-a3990df/bm-20250308-vultr-x86_64-python-a3990df6121880e8c678-3.14.0a5%2B-a3990df-vs-3.13.0rc2.svg) |  |
| [2025-03-08](results/bm-20250308-3.14.0a5%2B-a3990df-NOGIL) | python/a3990df6121880e8c678 | a3990df (NOGIL) | 1.040x ↓<br>[📄](results/bm-20250308-3.14.0a5%2B-a3990df-NOGIL/bm-20250308-vultr-x86_64-python-a3990df6121880e8c678-3.14.0a5%2B-a3990df-vs-3.12.6.md)[📈](results/bm-20250308-3.14.0a5%2B-a3990df-NOGIL/bm-20250308-vultr-x86_64-python-a3990df6121880e8c678-3.14.0a5%2B-a3990df-vs-3.12.6.svg) | 1.072x ↓<br>[📄](results/bm-20250308-3.14.0a5%2B-a3990df-NOGIL/bm-20250308-vultr-x86_64-python-a3990df6121880e8c678-3.14.0a5%2B-a3990df-vs-3.13.0rc2.md)[📈](results/bm-20250308-3.14.0a5%2B-a3990df-NOGIL/bm-20250308-vultr-x86_64-python-a3990df6121880e8c678-3.14.0a5%2B-a3990df-vs-3.13.0rc2.svg) | 1.129x ↓<br>[📄](results/bm-20250308-3.14.0a5%2B-a3990df-NOGIL/bm-20250308-vultr-x86_64-python-a3990df6121880e8c678-3.14.0a5%2B-a3990df-vs-base.md)[📈](results/bm-20250308-3.14.0a5%2B-a3990df-NOGIL/bm-20250308-vultr-x86_64-python-a3990df6121880e8c678-3.14.0a5%2B-a3990df-vs-base.svg)[🧠](results/bm-20250308-3.14.0a5%2B-a3990df-NOGIL/bm-20250308-vultr-x86_64-python-a3990df6121880e8c678-3.14.0a5%2B-a3990df-vs-base-mem.svg) |
| [2025-03-07](results/bm-20250307-3.14.0a5%2B-7879081) | python/78790811989ab47319e2 | 7879081 | 1.102x ↑<br>[📄](results/bm-20250307-3.14.0a5%2B-7879081/bm-20250307-vultr-x86_64-python-78790811989ab47319e2-3.14.0a5%2B-7879081-vs-3.12.6.md)[📈](results/bm-20250307-3.14.0a5%2B-7879081/bm-20250307-vultr-x86_64-python-78790811989ab47319e2-3.14.0a5%2B-7879081-vs-3.12.6.svg) | 1.061x ↑<br>[📄](results/bm-20250307-3.14.0a5%2B-7879081/bm-20250307-vultr-x86_64-python-78790811989ab47319e2-3.14.0a5%2B-7879081-vs-3.13.0rc2.md)[📈](results/bm-20250307-3.14.0a5%2B-7879081/bm-20250307-vultr-x86_64-python-78790811989ab47319e2-3.14.0a5%2B-7879081-vs-3.13.0rc2.svg) |  |
| [2025-03-07](results/bm-20250307-3.14.0a5%2B-7879081-NOGIL) | python/78790811989ab47319e2 | 7879081 (NOGIL) | 1.043x ↓<br>[📄](results/bm-20250307-3.14.0a5%2B-7879081-NOGIL/bm-20250307-vultr-x86_64-python-78790811989ab47319e2-3.14.0a5%2B-7879081-vs-3.12.6.md)[📈](results/bm-20250307-3.14.0a5%2B-7879081-NOGIL/bm-20250307-vultr-x86_64-python-78790811989ab47319e2-3.14.0a5%2B-7879081-vs-3.12.6.svg) | 1.076x ↓<br>[📄](results/bm-20250307-3.14.0a5%2B-7879081-NOGIL/bm-20250307-vultr-x86_64-python-78790811989ab47319e2-3.14.0a5%2B-7879081-vs-3.13.0rc2.md)[📈](results/bm-20250307-3.14.0a5%2B-7879081-NOGIL/bm-20250307-vultr-x86_64-python-78790811989ab47319e2-3.14.0a5%2B-7879081-vs-3.13.0rc2.svg) | 1.132x ↓<br>[📄](results/bm-20250307-3.14.0a5%2B-7879081-NOGIL/bm-20250307-vultr-x86_64-python-78790811989ab47319e2-3.14.0a5%2B-7879081-vs-base.md)[📈](results/bm-20250307-3.14.0a5%2B-7879081-NOGIL/bm-20250307-vultr-x86_64-python-78790811989ab47319e2-3.14.0a5%2B-7879081-vs-base.svg)[🧠](results/bm-20250307-3.14.0a5%2B-7879081-NOGIL/bm-20250307-vultr-x86_64-python-78790811989ab47319e2-3.14.0a5%2B-7879081-vs-base-mem.svg) |
| [2025-03-06](results/bm-20250306-3.14.0a5%2B-a385add) | python/a385add4015c431534e2 | a385add | 1.088x ↑<br>[📄](results/bm-20250306-3.14.0a5%2B-a385add/bm-20250306-vultr-x86_64-python-a385add4015c431534e2-3.14.0a5%2B-a385add-vs-3.12.6.md)[📈](results/bm-20250306-3.14.0a5%2B-a385add/bm-20250306-vultr-x86_64-python-a385add4015c431534e2-3.14.0a5%2B-a385add-vs-3.12.6.svg) | 1.048x ↑<br>[📄](results/bm-20250306-3.14.0a5%2B-a385add/bm-20250306-vultr-x86_64-python-a385add4015c431534e2-3.14.0a5%2B-a385add-vs-3.13.0rc2.md)[📈](results/bm-20250306-3.14.0a5%2B-a385add/bm-20250306-vultr-x86_64-python-a385add4015c431534e2-3.14.0a5%2B-a385add-vs-3.13.0rc2.svg) |  |
| [2025-03-06](results/bm-20250306-3.14.0a5%2B-a385add-NOGIL) | python/a385add4015c431534e2 | a385add (NOGIL) | 1.048x ↓<br>[📄](results/bm-20250306-3.14.0a5%2B-a385add-NOGIL/bm-20250306-vultr-x86_64-python-a385add4015c431534e2-3.14.0a5%2B-a385add-vs-3.12.6.md)[📈](results/bm-20250306-3.14.0a5%2B-a385add-NOGIL/bm-20250306-vultr-x86_64-python-a385add4015c431534e2-3.14.0a5%2B-a385add-vs-3.12.6.svg) | 1.080x ↓<br>[📄](results/bm-20250306-3.14.0a5%2B-a385add-NOGIL/bm-20250306-vultr-x86_64-python-a385add4015c431534e2-3.14.0a5%2B-a385add-vs-3.13.0rc2.md)[📈](results/bm-20250306-3.14.0a5%2B-a385add-NOGIL/bm-20250306-vultr-x86_64-python-a385add4015c431534e2-3.14.0a5%2B-a385add-vs-3.13.0rc2.svg) | 1.126x ↓<br>[📄](results/bm-20250306-3.14.0a5%2B-a385add-NOGIL/bm-20250306-vultr-x86_64-python-a385add4015c431534e2-3.14.0a5%2B-a385add-vs-base.md)[📈](results/bm-20250306-3.14.0a5%2B-a385add-NOGIL/bm-20250306-vultr-x86_64-python-a385add4015c431534e2-3.14.0a5%2B-a385add-vs-base.svg)[🧠](results/bm-20250306-3.14.0a5%2B-a385add-NOGIL/bm-20250306-vultr-x86_64-python-a385add4015c431534e2-3.14.0a5%2B-a385add-vs-base-mem.svg) |


<!-- END table -->

`*` indicates that the exact same versions of pyperformance was not used.

![Longitudinal speed improvement](/longitudinal.svg)

Improvement of the geometric mean of key merged benchmarks, computed with `pyperf compare`.
The results have a resolution of 0.01 (1%).

![Configuration speed improvement](/configs.svg)

## Documentation

### Running benchmarks from the GitHub web UI

Visit the 🔒 [benchmark action](../../actions/workflows/benchmark.yml) and click the "Run Workflow" button.

The available parameters are:

- `fork`: The fork of CPython to benchmark.
  If benchmarking a pull request, this would normally be your GitHub username.
- `ref`: The branch, tag or commit SHA to benchmark.
  If a SHA, it must be the full SHA, since finding it by a prefix is not supported.
- `machine`: The machine to run on.
  One of `linux-amd64` (default), `windows-amd64`, `darwin-arm64` or `all`.
- `benchmark_base`: If checked, the base of the selected branch will also be benchmarked.
  The base is determined by running `git merge-base upstream/main $ref`.
- `pystats`: If checked, collect the pystats from running the benchmarks.

To watch the progress of the benchmark, select it from the 🔒 [benchmark action page](../../actions/workflows/benchmark.yml).
It may be canceled from there as well.
To show only your benchmark workflows, select your GitHub ID from the "Actor" dropdown.

When the benchmarking is complete, the results are published to this repository and will appear in the [complete table](RESULTS.md).
Each set of benchmarks will have:

- The raw `.json` results from pyperformance.
- Comparisons against important reference releases, as well as the merge base of the branch if `benchmark_base` was selected. These include
  - A markdown table produced by `pyperf compare_to`.
  - A set of "violin" plots showing the distribution of results for each benchmark.

The most convenient way to get results locally is to clone this repo and `git pull` from it.

### Running benchmarks from the GitHub CLI

To automate benchmarking runs, it may be more convenient to use the [GitHub CLI](https://cli.github.com/).
Once you have `gh` installed and configured, you can run benchmarks by cloning this repository and then from inside it:

```bash session
gh workflow run benchmark.yml -f fork=me -f ref=my_branch
```

Any of the parameters described above are available at the commandline using the `-f key=value` syntax.

### Collecting Linux perf profiling data

To collect Linux perf sampling profile data for a benchmarking run, run the `_benchmark` action and check the `perf` checkbox.
Follow this by a run of the `_generate` action to regenerate the plots.

## License

This repo is licensed under the BSD 3-Clause License, as found in the LICENSE file.
