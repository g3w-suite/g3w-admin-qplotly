# G3W-ADMIN-QPLOTLY

[![PyPI version](https://img.shields.io/pypi/v/g3w-admin-qplotly)](https://pypi.org/project/g3w-admin-qplotly/)

DataPlotly integration for G3W-ADMIN

## Installation

Install it from PyPI:

```sh
pip install g3w-admin-qplotly
```

Enable `'qplotly'` module adding it to `G3WADMIN_LOCAL_MORE_APPS` list:

```py
# local_settings.py

G3WADMIN_LOCAL_MORE_APPS = [
    ...
    'qplotly'
    ...
]
```

and then run run `manage.py migrate` and `manage.py collectstatic`.

## CI/CD

- [ci.yml](.github/workflows/ci.yml) runs checks and Docker tests.
- [cd.yml](.github/workflows/cd.yml) publishes to PyPI and creates a GitHub release.

---

**Compatibile with:**
[![g3w-admin version](https://img.shields.io/badge/g3w--admin-4.0-1EB300.svg?style=flat)](https://github.com/g3w-suite/g3w-admin/tree/v.4.0.x)
[![g3w-suite-docker version](https://img.shields.io/badge/g3w--suite--docker-4.0-1EB300.svg?style=flat)](https://github.com/g3w-suite/g3w-suite-docker/tree/v4.0.x)

---

**License:** MPL-2