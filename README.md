<!--
https://readme42.com
-->


[![](https://img.shields.io/pypi/v/requests-api-pagination.svg?maxAge=3600)](https://pypi.org/project/requests-api-pagination/)
[![](https://img.shields.io/badge/License-Unlicense-blue.svg?longCache=True)](https://unlicense.org/)
[![](https://github.com/andrewp-as-is/requests-api-pagination.py/workflows/tests42/badge.svg)](https://github.com/andrewp-as-is/requests-api-pagination.py/actions)

### Installation
```bash
$ [sudo] pip install requests-api-pagination
```

#### Examples
```python
import requests_api_pagination

url='https://api.github.com/gists?per_page=100'
headers = {"Authorization": "Bearer %s" % GITHUB_TOKEN}

requests_api_pagination.get(url,headers=headers)
```

<p align="center">
    <a href="https://readme42.com/">readme42.com</a>
</p>