# Python Poetry Tips
* [Poetry Tips for GitHub Actions Workflows](https://github.com/python-poetry/poetry/issues/366#issuecomment-691412462)
* [GitHub Discussion: docker poetry best practices](https://github.com/orgs/python-poetry/discussions/1879)
* [Poetry devcontainer feature](https://github.com/devcontainers-contrib/features/tree/main/src/poetry)
  ```json
  {
	"name": "Python 3",
	"image": "mcr.microsoft.com/devcontainers/python:1-3.12-bullseye",
	"features": {
		"ghcr.io/devcontainers-contrib/features/poetry:2": {"version": "latest"}
	},
	"postCreateCommand": "poetry install --no-root"
  }
  ```
* [CLI Commands](https://python-poetry.org/docs/cli/)
* [Configuration](https://python-poetry.org/docs/configuration/)
