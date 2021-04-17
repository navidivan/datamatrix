# Python DataMatrix

*An intuitive, Pythonic way to work with tabular data.*

Sebastiaan Mathôt  <br />
Copyright 2015-2021  <br />
<https:/datamatrix.cogsci.nl>

[![Build Status](https://travis-ci.com/open-cogsci/python-datamatrix.svg?branch=0.12)](https://travis-ci.com/open-cogsci/python-datamatrix)


## About

The `datamatrix` package provides a high-level, intuitive way to work with
tabular data, that is, datasets that consist of named columns and numbered rows.

The main advantage of `datamatrix` over similar libraries is the clean, Pythonic syntax, which makes your code easy to read and understand.

`datamatrix` is also one of the core libraries of [OpenSesame](https://osdoc.cogsci.nl/), a graphical experiment builder for the social sciences, and [Rapunzel](https://rapunzel.cogsci.nl/), a modern code editor for numerical computing with Python and R.


## Dependencies

- Python >= 3.7

Optional:

- `numpy` and `scipy` for using the `FloatColumn`, `IntColumn`, and `SeriesColumn` objects
- `prettytable` for creating a text representation of a DataMatrix (e.g. to print it out)
- `openpyxl` for reading and writing `.xlsx` files
- `fastnumbers` for improved performance

## Installation


### PyPi

~~~
pip install python-datamatrix
~~~


### Anaconda

~~~
conda install python-datamatrix -c cogsci -c conda-forge
~~~


### Ubuntu

~~~
sudo add-apt-repository ppa:smathot/cogscinl
sudo apt-get update
sudo apt install python3-datamatrix
~~~


## Documentation

See <https://datamatrix.cogsci.nl/>


## License

`python-datamatrix` is licensed under the [GNU General Public License
v3](http://www.gnu.org/licenses/gpl-3.0.en.html).
