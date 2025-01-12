# Process replay tests

Process replay is a tool for creating a diff of generated kernels between two commits. By default, process replay doesn't assert kernel diffs.

Refactor and speedup PRs must enable the assert by including `[pr]` in the pull request title.

Note that process replay [early stops when over 20% of kernels change, for speed.](https://github.com/tinygrad/tinygrad/pull/5480).

## Running locally

To run process replay locally, run tinygrad with `RUN_PROCESS_REPLAY=1`.
