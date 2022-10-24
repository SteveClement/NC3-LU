---
title: "PyMOSP"
slug: "pymosp"
description: "A collaborative platform for creating, editing and sharing validated JSON objects of any type."
weight: 40
tags: ["projects", "mosp"]
---

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
