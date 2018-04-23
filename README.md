# pywe-xml

Wechat XML Module for Python.

# Installation

```shell
pip install pywe-xml
```

# Usage

```python
from pywe_xml import dict_to_xml, xml_to_dict, pair_to_xml
```

# Method

```python
def dict_to_xml(d, ignore=True, isdigit=True, subxml=False):

def xml_to_dict(x):

def pair_to_xml(listuple, ignore=True, isdigit=True, subxml=False):
    """ [('a', 1), ('b', 2), ('c', [('d', 4)])...] """
```
