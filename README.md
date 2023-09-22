# Visual Studio Code Dev Containers

This will eventually store variations of dev containers I make. Right now it's just a reference for how to set up a repo with a dev container.

## TODO

- [x] Create a cookiecutter
- [x] Create image variations
  - [x] Python
  - [x] Mamba
  - [x] PDM
- [x] Fix init terminal `$ sh`
- [ ] Example `docker-compose.yml`
  - [ ] Variations of `docker-compose.yml` files

## Templates

The [`cookiecutter`](./cookiecutter/) directory has `cookiecutter` templates for various dev container environments. To set up a dev container in a new project using one of these templates, point the cookiecutter command at this repository. For example, to set up a new `.devcontainer` directory in a local repository project using the `standard` template, you would run:

`cookiecutter https://github.com/redjax/vscode_containers/cookiecutter/standard`

This will create a directory `.devcontainer` with the files from [`./cookiecutter/standard/`](./cookiecutter/standard/) in the directory the `cookiecutter` command was run from. The files will be generated from the `cookiecutter` template, and are ready to use as-is after running the command.

## Links

- [Paulyu.dev: extending VSCode devcontainers with features](https://paulyu.dev/article/extending-vscode-devcontainer-features/)
- [VSCode Docs: Use containers for build and debug with Visual Studio Code](https://learn.microsoft.com/en-us/azure-sphere/app-development/container-build-vscode?view=azure-sphere-legacy)
- [GoDataDriven.com: How to create a Devcontainer for your Python project](https://godatadriven.com/blog/how-to-create-a-devcontainer-for-your-python-project-%F0%9F%90%B3/)
- [DevGenius.io: Introduction to developing inside a Docker Container with Visual Studio Code](https://blog.devgenius.io/introduction-to-containerized-development-with-visual-studio-code-f2ec2683ebe1)
- **VSCode Docs**:
  - [Developing inside a Container](https://code.visualstudio.com/docs/devcontainers/containers)
  - [Create a Dev Container](https://code.visualstudio.com/docs/devcontainers/create-dev-container)
  - [Tutorial](https://code.visualstudio.com/docs/devcontainers/tutorial)
  - [Develop with containers](https://code.visualstudio.com/learn/develop-cloud/containers)
  - [Dev Containers Tips and Tricks](https://code.visualstudio.com/docs/devcontainers/tips-and-tricks)
  - [Advanced container configuration](https://code.visualstudio.com/remote/advancedcontainers/overview)
  - [FAQ](https://code.visualstudio.com/docs/devcontainers/faq)
- [List of available dev container "features"](https://containers.dev/features)
