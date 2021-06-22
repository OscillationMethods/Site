# Building the Site

Notes and instructions for building the public
[Oscillation Methods](https://oscillationmethods.github.io/)
site.

## Overview

This repository and associated website serve as a hosted version of the
[Oscillation Methods](https://github.com/voytekresearch/oscillationmethods) project.

This repository,
[Site](https://github.com/OscillationMethods/Site),
is used to organize and create the website, which is then pushed to be hosted from the
[source](https://github.com/OscillationMethods/oscillationmethods.github.io) repository.

## Building the Site

Functionality to manage content and build the site is all controlled by a
[Makefile](https://github.com/OscillationMethods/Site/blob/main/Makefile).

The site is created with the
[Jupyter-book](https://github.com/executablebooks/jupyter-book)
tool, which is a requirement for running the Makefile.

## Content

Content for the website is a hosted copy of the materials for the Oscillation Methods project.

Note that the source of this material is not managed or stored in this repository,
as they are copied over from the
[project repository](https://github.com/voytekresearch/oscillationmethods).
