### Hexlet tests and linter status:
[![Actions Status](https://github.com/Deln0r/python-project-50/workflows/hexlet-check/badge.svg)](https://github.com/Deln0r/python-project-50/actions)

[![Actions Status](https://github.com/Deln0rpython-project-50/actions/workflows/pyci.yml/badge.svg)](https://github.com/DREU007/python-project-50/actions)
[![Maintainability](https://api.codeclimate.com/v1/badges/f7cbfec6c082003cfec9/maintainability)](https://codeclimate.com/github/Deln0r/python-project-50/maintainability)

### Description
**Gendiff (Difference generator)** - a CLI tool to distinguish the difference in two JSON and/or YAML files. The output could be in plain text, detailed difference, or be JSON dictionary.

### Installation
```
git clone 
cd python-project-50
make install
make build
make package-install
```

### Uninstallation
```
make package-remove
```

### Dependencies
* Python ^3.10
* poetry
* make

### Usage
```
usage: gendiff [-h] [-f FORMAT] first_file second_file

Compares two configuration files and shows a difference.

positional arguments:
  first_file
  second_file

options:
  -h, --help            show this help message and exit
  -f FORMAT, --format FORMAT
                        set format of output (default: stylish).
                        Formats: {stylish, plain, json}.

```



### Examples

Use of help argument & Comparison of 2 .json files:
[![asciicast](https://asciinema.org/a/fAnxnQu0GNGMY7b1dalsxqGcr.svg)](https://asciinema.org/a/fAnxnQu0GNGMY7b1dalsxqGcr)


Comparison of 2 .yml files:
[![asciicast](https://asciinema.org/a/565610.svg)](https://asciinema.org/a/565610)


Comparison of 2 complex .yml files:
[![asciicast](https://asciinema.org/a/kjPBDAVVb2OBQeDZb1UKdBdQs.svg)](https://asciinema.org/a/kjPBDAVVb2OBQeDZb1UKdBdQs)


Comparison in "plain" format (2 complex .json files):
[![asciicast](https://asciinema.org/a/571593.svg)](https://asciinema.org/a/571593)


Comparison in "json" format (2 complex .json files):
[![asciicast](https://asciinema.org/a/571702.svg)](https://asciinema.org/a/571702)