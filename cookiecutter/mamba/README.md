# Mamba Dev Container

## Installation

`cookiecutter https://github.com/redjax/vscode_containers/cookiecutter/mamba`

## Description

This container is for Python development, and includes `Mamba` for environment management.

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
| Feature           | pre-commit       |
| Feature           | SSHd             |
