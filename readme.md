# Software Documentation
A Sphinx-based repo that describes the software used for neutron sciences for data reduction and analysis.

### Paper Reference
This includes information from the following SULI internship projects:
- [An Exploration on the Data Reduction and Analysis Software Used for Spectroscopy at Spallation Neutron Source and High Flux Isotope Reactor](https://github.com/PaulEunKim/neutron-software/blob/main/Research_Report.pdf)
- [Exploration on Data Software for Small Angle Neutron Scattering and Reflectometry](https://github.com/PaulEunKim/neutron-software/blob/main/Research_Paper.pdf)

## Development Documentation

### Requirements
```
pip install sphinx

# or

conda install sphinx
```

Recommended tools for development on VSCode. You can view a live preview of .rst files by installing the Preview extension: https://marketplace.visualstudio.com/items?itemName=searKing.preview-vscode.

Pycharm also has live preview ability with .rst files (the markdown files used with the Sphinx system).

### Instructions
In the root repo, in the terminal:
```
make clean
make html
```

Then double click the index.html file located build/html/index.html.