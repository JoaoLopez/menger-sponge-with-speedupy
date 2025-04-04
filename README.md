# Menger Sponge Experiment

## Experiment dependencies
This experiment has the following dependencies: **numpy, matplotlib**

To install them, execute: **pip install numpy matplotlib**

To run the experiment, make sure you have the appropriate release of SpeeduPy installed. Instructions on which release to use and how to install it can be found [here](https://github.com/dew-uff/memoization/blob/main/README.md#reproducing-the-article-analyses). Ensure that the **speedupy/** folder is located in the same directory as the main experiment script.

## Trials Used in the Article
The five trials used on the memoization techniques article are:

- menger_sponge_speedupy_160.py
- menger_sponge_speedupy_170.py
- menger_sponge_speedupy_180.py
- menger_sponge_speedupy_190.py
- menger_sponge_speedupy.py

To execute a trial, type:

```bash
python speedupy/setup_exp/setup.py SCRIPT_NAME.py
python SCRIPT_NAME.py --exec-mode manual
```

Original code from John D. Cook, available at https://www.johndcook.com/blog/2011/08/30/slice-a-menger-sponge/
