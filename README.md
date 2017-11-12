caeroc
======
Compressible Aerodynamics Calculator for Python
-----------------------------------------------
![alpha](https://img.shields.io/badge/caeroc-v0.0.2a-green.svg) 
[![LICENSE](https://img.shields.io/badge/license-GPL-blue.svg)](/LICENSE)

A python package for compressible flows. A dynamic toolkit which enables you to make use of the formulae governing compressible flows.

Installation
------------
To install development versions of `caeroc` and `scikit-aero`
```bash
pip install -e https://github.com/ashwinvis/caeroc.git --process-dependency-links --trusted-host github.com
```

If the current configuration of the GUI does not work for you, regenerate it by
running:
```bash
cd caeroc/gui
./configure
```

### Development
Development mode will install `caeroc` using soft links.

```bash
git clone --recursive https://github.com/ashwinvis/caeroc.git
cd caeroc
python setup.py develop
cd ../scikit-aero
python setup.py develop
```

Features
--------
- [x] Command-line tool which opens a Qt based GUI calculator

```bash
caeroc-app
```
![In development](http://i.imgur.com/7Bb0ypN.png)

- [ ] Save data as a database
- [ ] Plotting graphs
- [ ] Generate gas tables
- [ ] Calculate flow characteristics: Coefficient of pressure, lift and drag for basic profiles.

Courtesy
--------
* The idea for a compressible aerodynamics calculator in the form an online JS tool had been implemented by [William Devenport](http://www.aoe.vt.edu/people/faculty.php?fac_id=wdevenpo) [here](http://www.dept.aoe.vt.edu/~devenpor/aoe3114/calc.html). 
This project is pushing more functionalities as an offline tool and allowing users to dynamically use the formulae for specific cases.
* Thanks to the scikit-aero team for being the backend
