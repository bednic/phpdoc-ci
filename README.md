# phpdoc-ci
[phpDocumentor](https://www.phpdoc.org/) docker image runnable in CI

> An actual version of phpdoc is 3

## Usage
```yaml
docs:
    image: bednic/phpdoc-ci
    script:
        - phpdoc -d src -t docs
```
