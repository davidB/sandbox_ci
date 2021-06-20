# sandbox_ci
sandbox to experimental ci/cd,...

## Build

### Linters

To lint locally see [super-linter/run-linter-locally.md at master · github/super-linter](https://github.com/github/super-linter/blob/master/docs/run-linter-locally.md)

```sh
docker run -e RUN_LOCAL=true -v $PWD:/tmp/lint github/super-linter
```

To configure, place configuration under `.github/linters` or customize path into `.github/workflows/linter.yaml` (for details see [Using your own rules files](https://github.com/github/super-linter#using-your-own-rules-files)).