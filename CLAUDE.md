# Bench-ilab

## Purpose
Scripts and configuration to run InstructLab training workloads within the crucible framework.

## Language
Bash — all scripts

## Key Files
| File | Purpose |
|------|---------|
| `rickshaw.json` | Rickshaw integration: client scripts, parameter transformations |
| `multiplex.json` | Parameter validation and presets for multiplex |
| `ilab-base` | Base setup shared by other scripts |
| `ilab-client` | Client-side benchmark execution |
| `ilab-get-runtime` | Extracts runtime from command-line options |
| `ilab-post-process` | Parses ilab output into crucible metrics |
| `workshop.json` | Engine image build requirements |

## Conventions
- Primary branch is `main`
- Standard Bash modelines and 4-space indentation
