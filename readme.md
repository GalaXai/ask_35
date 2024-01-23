# Project Title

This project contains scripts and configuration files.

## Directory Structure

- `lab-2/`: Contains shell scripts for various installations.
  - `example.sh`
  - `install-mariadb.sh`
  - `install-wp.sh`
  - `install_java_app.sh`

- `lab-3-ansible/`: Contains Ansible configuration files and templates.
  - `hosts.ini`
  - `install_java_app.yaml`
  - `templates/`
    - `app.service.j2`
    - `mariadb.repo.j2`

- `lab-4-ansible-lb/`: Contains Ansible configuration files and templates for load balancing.
  - `hosts.ini`
  - `install.yaml`
  - `templates/`
    - `app.service.j2`
    - `mariadb.repo.j2`
    - `nginx.conf`

- `lab-5-docker/`: Contains Dockerfile for building Docker images.
  - `dockerfile`

- `lab-6-graphs/`: Contains configuration files for graph generation.
  - `readme.md`
  - `sample.config`