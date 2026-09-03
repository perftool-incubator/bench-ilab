# Bench-ilab

## Purpose
Scripts and configuration to run InstructLab training and synthetic data generation (SDG) workloads within the crucible framework.

## Language
- Bash for client execution scripts
- Python for post-processing (`ilab-post-process.py`)

## Key Files
| File | Purpose |
|------|---------|
| `rickshaw.json` | Rickshaw integration: client scripts, parameter transformations |
| `multiplex.json` | Parameter validation rules, unit conversions, and presets for multiplex |
| `benchmark-metadata.json` | Machine-readable description and CDM-indexed source/type list (consumed by `crucible benchmarks list`) |
| `ilab-base` | Base setup shared by other scripts |
| `ilab-client` | Client-side benchmark execution |
| `ilab-get-runtime` | Extracts runtime from command-line options |
| `ilab-post-process.py` | Parses ilab output into crucible metrics |
| `workshop.json` | Engine image build requirements |

## Conventions
- Primary branch is `main`
- Standard Bash modelines and 4-space indentation
- Python code follows 4-space indentation with standard modelines
