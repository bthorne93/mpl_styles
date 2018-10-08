# Matplotlib Styles

These are a few stylesheets I use for plots in papers, presentations,
or just generally.

## Installation

In order to use them, clone the repo and set the `MPLCONFIGDIR` environment
variable to the path to this directory. For example, in your `.bashrc` have:

```bash
export MPLCONFIGDIR=$HOME/repos/mpl_styles
```

Matplotlib looks for the `.mplstyle` files in `$MPLCONFIGDIR/stylelib`.

## Fonts

I found that in order for my `anaconda` environments to reliably be able to find
my system's installed fonts I had to set the `USE_FONTCONFIG = True` in 
`font_manager.py`, which will be hiddern somewhere within the matplotlib
installation you are using, [see here for details](https://matplotlib.org/api/font_manager_api.html).
