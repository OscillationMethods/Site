# Oscillation Methods Site

[![Project Status: Active](https://www.repostatus.org/badges/latest/active.svg)](https://www.repostatus.org/#active)
[![License: CC BY-NC 4.0](https://img.shields.io/badge/License-CC%20BY--NC%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by-nc/4.0/)

## Overview

This repository is the source repository for creating the
[Oscillation Methods](https://oscillationmethods.github.io)
website.

These materials serve as a hosted version of materials for the
[Oscillation Methods](https://github.com/OscillationMethods/oscillationmethods)
project.

This repository has the tools for building the website.
The built version of book is then posted to the
[website repository](https://github.com/OscillationMethods/oscillationmethods.github.io)
for hosting.

## Reference

If you wish to cite information presented on the project website, please cite the project paper:

    Donoghue T, Schaworonkow N, & Voytek B (2022). Methodological considerations for studying neural
    oscillations. European Journal of Neuroscience, 55(11-12), 3502-3527 DOI: 10.1111/ejn.15361

Direct Link: https://onlinelibrary.wiley.com/doi/10.1111/ejn.15361

## Organization

This repository contains the code to create the website, whereas the actual
materials that are hosted are in the
[materials repository](https://github.com/OscillationMethods/oscillationmethods).

This repository contains the following sections:

- `oscmethods/` contains the content of the website, including sub-sections:
    - `assets/` contains additional materials to be added to the website
    - `docs/` contains the source for written sections of the site

## Dependencies

This project uses the Python programming language.

The website is created using [JupyterBook](https://github.com/executablebooks/jupyter-book),
with the full set of requirements to build the website available in the `requirements.txt` file.

The materials that are hosted on the website are in the
[Project Repository](https://github.com/OscillationMethods/oscillationmethods).

To rebuild the website dependencies of the project repository are also required, with
details and instructions on these dependencies and how to get them being available in the
project repository.

## License

These materials are made freely available, and are licensed under a
[CC BY-NC 4.0](https://creativecommons.org/licenses/by-nc/4.0/) license.
