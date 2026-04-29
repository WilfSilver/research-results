# Research

This contains the full research results from my research project, including all the data.

The code for generating all the graphs can be found in [results.ipynb](./results.ipynb), note that all folders must exist beforehand: `graphs/all`, `graphs/no_enc`, `graphs/all_enc`, `graphs/phone`, `graphs/single_machine` and `graphs/two_machine`.

Additionally, this project uses `uv` for dependency management, and so therefore you need to run:

```sh
uv sync
```

Raw data from each scenario can be found in `phone`, `single_machine`, `single_no_enc`, `two_machine` folders, the file format is taken straight form downloads: `{testNum}-{consumer or producer}-{codec}-{svc or simulcast}-{spatial layer}-{temporal layer}.csv` and contain 3 tables within it, split by `\n\n`.

Generative AI was used just for providing a base graph design that was then heavily modified to work for all data types.
