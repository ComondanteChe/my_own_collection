# Ansible Role: my_module_file_create
[![License](https://img.shields.io/badge/license-MIT%20License-brightgreen.svg)](https://opensource.org/licenses/MIT)

## Requirements

- Ansible >= 2.18 (It might work on previous versions, but we cannot guarantee it)
- Debian and python on deployer machine.
- Python >=3.12

## Role Variables

All variables which can be overridden are stored in [defaults/main.yml](defaults/main.yml) file as well as in table below.

| Name           | Default Value | Description                        |
| -------------- | ------------- | -----------------------------------|
| `path` | ./viva.txt | file path and name |
| `content`| Viva from World | Default content |
