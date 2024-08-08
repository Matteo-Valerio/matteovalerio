---
title: pybioportal
summary: A Python package to easily retrieve data from cBioPortal
tags:
date: '2023-12-30T00:00:00Z'

# Optional external URL for project (replaces project detail page).
#external_link: ''

image:
  #caption: Photo by rawpixel on Unsplash
  #focal_point: Smart

links:
  - icon: github
    icon_pack: fab
    name: Repository
    url: https://github.com/Matteo-Valerio/pyBioPortal
  - icon: book
    icon_pack: fas
    name: Documentation
    url: https://pybioportal.readthedocs.io/en/latest/
  - icon: medium
    icon_pack: fab
    name: Overview
    url: https://medium.com/@m.valerio/introducing-pybioportal-a-python-package-for-accessing-cbioportal-data-4ddfc647287f  
url_code: ''
url_pdf: ''
url_slides: ''
url_video: ''
---

**`pybioportal`** is an open source, BSD-licensed [Python] library that provides a set of 
functions to facilitate data acquisition from the [cBioPortal Web Public API] and the transformation 
of that data into useful data structures.

It allows users to easily query the cBioPortal public API and retrieve the data directly in the form of a
[pandas] DataFrame, making the data accessible and ready for analysis.

It is an essential tool for researchers and biological data analysts who wish to access and leverage 
cBioPortal resources for their research and bioinformatic analysis projects.

[Python]: https://www.python.org/
[cBioPortal Web Public API]: https://www.cbioportal.org/api/swagger-ui/index.html
[pandas]: https://pandas.pydata.org/


## **Where to get it**
The source code is currently hosted on GitHub at:
https://github.com/Matteo-Valerio/pyBioPortal

Binary installers for the latest released version are available at the [Python
Package Index (PyPI)] and on [Anaconda].

[Python Package Index (PyPI)]: https://pypi.org/project/pybioportal
[Anaconda]: https://anaconda.org/matteo.valerio/pybioportal


```python
# PyPI
pip install pybioportal
```

```python
# Anaconda
conda install -c matteo.valerio pybioportal
```

## **Documentation**
The official documentation is hosted on [ReadtheDocs](https://pybioportal.readthedocs.io/en/latest/).
