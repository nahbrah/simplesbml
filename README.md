 <table style="width:100%">
  <tr>
    <td><img src="https://img.shields.io/badge/License-MIT-yellow.svg" /></td>
    <td><img alt="Read the Docs" src="https://img.shields.io/readthedocs/simplesbml"></td>
    <td><img alt="PyPI - Downloads" src="https://img.shields.io/pypi/dm/simplesbml"></td>
    <td><img alt="GitHub issues" src="https://img.shields.io/github/issues-raw/sys-bio/simplesbml"></td>
    <td><img alt="PyPI - Python Version" src="https://img.shields.io/pypi/pyversions/simplesbml"></td>
  </tr>
</table> 

# simplesbml

Forked version of SimpleSBML that features getReaction(reaction ID).

For all the other code...

The documentation can be found at: http://simplesbml.readthedocs.io/en/latest/

libSBML documentation: http://sbml.org/Software/libSBML/docs/python-api/index.html

SBML main page: http://sbml.org/Main_Page

## Versions: 

The current version is 2.0.0. Compared to 1.2.x series, this adds 'get' functions to interrogate an existing SBML model.

# How to install SimpleSBML

SimpleSBML (this version) can be installed downloading the git files, cding into the master directory, and running:

```
python setup.py develop
```
# Python version support

SimpleSBML in theory supports Python versions 2.7, 3.3, 3.4, 3.5, and 3.6. It definitely supports Python 3.7 and most likely 3.8. SimpleSBML is a pure Python package, but relies on libSBML, which must be compiled for each supported version.

# Help

You can go to the package documentation to read about the package's classes and methods.  For an example of how to use sbmlModel() and writeCode(), look at 'example.py' in this folder.  For other issues, report them at github.com/sys-bio/simplesbml/issues.
