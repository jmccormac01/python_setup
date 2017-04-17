# Python Setup via PIP

This script uses ```pip``` to install all the necessary bits for a new astronomy/stats/webdev based python installation.

# Module List

   1. numpy
   1. scipy
   1. pandas
   1. xlrd (used by pandas for handling excel files)
   1. astropy
   1. pyqt5
   1. matplotlib
   1. sep (SExtractor in Python by [Kyle Barbary](https://github.com/kbarbary))
   1. scikit-image
   1. donuts (Autoguider/Image Alignment by [James McCormac](https://github.com/jmccormac01))
   1. reproject (Image reprojection by [Thomas Robitaille](https://github.com/astrofrog))
   1. pyregion (DS9 region handling - part of [Astropy](https://github.com/astropy/astropy))
   1. pylint
   1. pyephem (Based on XEphem by [Brandon Rhodes](https://github.com/brandon-rhodes))
   1. jupyter
   1. jupyterthemes (Themes for Jupyter by [Kyle Dunovan](https://github.com/dunovank))
   1. ccdproc (CCD image reductions - part of [Astropy](https://github.com/astropy/astropy))
   1. statsmodels
   1. george (Gaussian Process Regression by [Dan Foreman-Mackey](https://github.com/dfm). *Requires Eigen*)
   1. emcee (Affine-invariant MCMC by [Dan Foreman-Mackey](https://github.com/dfm))
   1. batman (Transiting planet model by [Laura Kriedberg](https://github.com/lkreidberg)
   1. ellc (Eclipsing binary modelling by Pierre Maxted)
   1. flask ([Micro-framework for Python-based webdev](http://flask.pocoo.org))

# Example

To install all the Python modules above do the following:

```
git clone https://github.com/jmccormac01/python_setup.git
cd python_setup
./install.sh
```

# Contributors

James McCormac

# License

MIT

