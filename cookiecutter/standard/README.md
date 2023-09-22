# Standard Dev Container

## Installation

`cookiecutter https://github.com/redjax/vscode_containers --directory="cookiecutter/standard"`

## Description

This container has most of the environment I would normally use while developing. It installs a list of VSCode extensions, has additional "features" enabled for things like Git, Python Black, pre-commit, etc.

## Container Details

| Key               | Value            |
| ----------------- | ---------------- |
| Container Image   | python:3.11-slim |
| Container User    | vscode           |
| Container Workdir | /workspace       |
| forwardPorts      | 3000             |
| Feature           | Docker-in-Docker |
| Feature           | git              |
| Feature           | black            |
| Feature           | pdm (via Pipx)   |
| Feature           | pre-commit       |
| Feature           | SSHd             |
