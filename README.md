# Docker image Molecule

Based on Ubuntu Xenial, it provides a docker image that allows you to run
Molecule 2.7, the test framework for Ansible. It includes Python 2.7, Ansible
2.4.

## Usage

```Bash
$ docker run --rm -v <path_to_your_role_directory>:/role euranova/molecule test
```
