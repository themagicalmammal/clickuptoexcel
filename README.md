# GeneticTabler
Replicate ClickUp Database using Excel.

Developed by [Dipan Nanda](https://github.com/themagicalmammal) (c) 2023

## Example of Usage

```python
from clickuptoexcel import Migrate2Excel

location = 'C:/Data/'
attributes = None
helper = Migrate2Excel(location=location, clickup_api_token="""<YOUR_API_KEY>""", attribute_values=attributes)
helper.start()
```

## Changelog
Go [here](CHANGELOG.md) to checkout the complete changelog.

## License
#### This is under GNU GPL v3.0 License
[![License: GPL v3](https://img.shields.io/badge/License-GPLv3-blue.svg)](LICENSE)
