# A visualization package for ERA5 data

**era5vis** offers command line tools to display ERA5 data in your browser.

It was written for the University of Innsbruck's
[scientific programming](https://manuelalehner.github.io/scientific_programming)
course as a package template for the semester project and is based on the 
example packages [scispack](https://github.com/fmaussion/scispack) and
[climvis](https://github.com/fmaussion/climvis) written by
[Fabien Maussion](https://fabienmaussion.info).

## HowTo

Download the package and install it in development mode. In the root directory
type:

    $ pip install -e .

## Command line interface

``pyproject.toml`` defines an "entry point" for a script to be used as a
command line program. Currently, the only command installed is ``era5vis_modellevel``.

After installation, just type

    $ era5vis_modellevel --help

to see what the tool can do.

## Testing

I recommend to use [pytest](https://docs.pytest.org) for testing. To test
the package, run

    $ pytest .

in the package's root directory.
