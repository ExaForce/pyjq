Changelog
---------

### Unreleased

- Supports 3.11, 3.12, 3.13, 3.14, 3.15.
- Building now requires Cython >= 3.1 (dropped the Python 2 `long` reference
  that Cython 3.1 rejects).

### 2.6.0

- Supports 3.10

### 2.5.1

- Fixed typo.

### 2.5.0

- Supports only 3.7+.
- Added pyjq.ScriptRuntimeError.

### 2.4.0

- Dropped support for Python 2.7, 3.4, 3.5 (Supports only 3.6+).

### 2.3.0

- Supported WindowsPE(msys)

### 2.2.0

- Added `library_paths=` option.

### 2.1.0

- API's translate JS object not to `dict` but to `collections.OrderedDict`.

### 2.0.0

- Semantic versioning.
- Bundle source codes of jq and oniguruma.
- Supported Python 3.5.
- Dropped support for Python 3.2.
- Aeded `all` method.

### 1.0

- First release.
