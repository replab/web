# The RepLAB website

The source code of the RepLAB toolbox is available on the main [RepLAB repository](https://www.github.com/replab/replab). This repository only contains the source files for the RepLAB landing website.

- Go to the [website](https://replab.github.io/web/) to consult the latest version.

- To generate a local copy of the website, follow these steps:
    - Clone this repository with `git clone --recursive https://www.github.com/replab/we.git`
    - Install the required sphinx modules with `pip install -r sphinx/requirements.txt`
    - Run `build.m` in Octave to compile the website
    - Consult `docs/index.html`
