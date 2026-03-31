# bench-ilab

Scripts and configuration to run [InstructLab](https://instructlab.ai/) training workloads within the [crucible](https://github.com/perftool-incubator/crucible) performance testing framework.

See `run-ilab.json` for example usage with `crucible run --from-file run-ilab.json`.

## Key Files

| File | Purpose |
|------|---------|
| `rickshaw.json` | Rickshaw integration: defines client scripts and parameter transformations |
| `multiplex.json` | Parameter validation and presets for multiplex |
| `ilab-base` | Base setup shared by other scripts |
| `ilab-client` | Client-side benchmark execution |
| `ilab-get-runtime` | Runtime extraction |
| `ilab-post-process` | Post-processing: parses ilab output into crucible metrics |
| `workshop.json` | Engine image build requirements |
