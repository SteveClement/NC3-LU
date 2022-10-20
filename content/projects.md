---
title: "Projects"
description: "Various notable open source projects made with ❤"
menu: main
weight: 50
tags: ["projects"]

---


### Security Assurance Evaluation Monitoring System 🆕

Provide a real-time monitoring of the level of security assurance of an IT infrastructure.


[More information](https://github.com/scandale-project)


### MONARC

MONARC is a tool and a method allowing an optimised, precise and repeatable risk assessment.

[![Latest Release](https://img.shields.io/github/release/monarc-project/MonarcAppFO.svg?style=flat-square)](https://github.com/monarc-project/MonarcAppFO/releases/latest)
![License](https://img.shields.io/github/license/monarc-project/MonarcAppFO.svg?style=flat-square)
![Contributors](https://img.shields.io/github/contributors/monarc-project/MonarcAppFO.svg?style=flat-square)
![Stars](https://img.shields.io/github/stars/monarc-project/MonarcAppFO.svg?style=flat-square)

[More information](/monarc)


### MONARC Global Dashboard

The MONARC global dashboard is currently relying on the
[MONARC stats-service](https://github.com/monarc-project/stats-service).


MONARC Stats Service is a libre software which is providing:

* an API in order to collect statistics from one or several MONARC
  instances and to return these statistics with different filters
  and aggregation methods;
* a dashboard that summarizes the current cybersecurity landscape.
  The charts are based on the statistics collected.

You can have a look at the [official instance](https://dashboard.monarc.lu)
and at the [documentation](https://www.monarc.lu/documentation/stats-service/).


[![Latest release](https://img.shields.io/github/release/monarc-project/stats-service.svg?style=flat-square)](https://github.com/monarc-project/stats-service/releases/latest)
[![License](https://img.shields.io/github/license/monarc-project/stats-service.svg?style=flat-square)](https://www.gnu.org/licenses/agpl-3.0.html)
[![Contributors](https://img.shields.io/github/contributors/monarc-project/stats-service.svg?style=flat-square)](https://github.com/monarc-project/stats-service/graphs/contributors)



### Fit4CyberSecurity

A self-assessment tool to help business owners implement a
better cybersecurity strategy.

[![Latest release](https://img.shields.io/github/release/CASES-LU/Fit4Cybersecurity.svg?style=flat-square)](https://github.com/CASES-LU/Fit4Cybersecurity/releases/latest)
[![License](https://img.shields.io/github/license/CASES-LU/Fit4Cybersecurity.svg?style=flat-square)](https://www.gnu.org/licenses/agpl-3.0.html)

[More information](/fit4cybersecurity)


### MOSP

A collaborative platform for creating, editing and sharing
validated JSON objects of any type.

[![Latest release](https://img.shields.io/github/release/CASES-LU/MOSP.svg?style=flat-square)](https://github.com/NC3-LU/MOSP/releases/latest)
[![License](https://img.shields.io/github/license/CASES-LU/MOSP.svg?style=flat-square)](https://www.gnu.org/licenses/agpl-3.0.html)
[![Contributors](https://img.shields.io/github/contributors/CASES-LU/MOSP.svg?style=flat-square)](https://github.com/NC3-LU/MOSP/graphs/contributors)
[![Stars](https://img.shields.io/github/stars/CASES-LU/MOSP.svg?style=flat-square)](https://github.com/NC3-LU/MOSP/stargazers)

[More information](/mosp)


### PyMOSP

PyMOSP is a Python library to access MOSP.

[![Latest release](https://img.shields.io/github/release/CASES-LU/PyMOSP.svg?style=flat-square)](https://github.com/CASES-LU/PyMOSP/releases/latest)
[![License](https://img.shields.io/github/license/CASES-LU/PyMOSP.svg?style=flat-square)](https://www.gnu.org/licenses/agpl-3.0.html)
[![PyPi version](https://img.shields.io/pypi/v/pymosp.svg?style=flat-square)](https://pypi.org/project/pymosp)

#### Installation

```bash
pip install pymosp
```

#### Usage

```python
import pymosp, os
mosp = pymosp.PyMOSP(os.getenv("MOSP_URL_API"), os.getenv("TOKEN"))
params = {"organization": "MONARC", "schema": "Library objects"}
r = mosp.objects(params=params)
print(r)
```

[More information](https://github.com/NC3-LU/PyMOSP)