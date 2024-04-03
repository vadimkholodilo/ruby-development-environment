# Ruby Development Environment

This repository contains a Vagrant configuration for a Ruby development environment.

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

The following software needs to be present on your machine:
- [Vagrant](https://www.vagrantup.com/)
- [VirtualBox](https://www.virtualbox.org/)

### Available Software

The following software is installed in the development environment:

- [Ruby](https://www.ruby-lang.org/en/)
- [Node.js](https://nodejs.org/)
- [MySQL](https://www.mysql.com/)

### Usage

1. Clone this repository:

    ```bash
    git clone https://github.com/vadimkholodilo/ruby-development-environment.git
    ```

2. Navigate to the repository directory:

    ```bash
    cd ruby-development-environment
    ```

3. Start the virtual machine:

    ```bash
    vagrant up
    ```

4. Connect to the machine via SSH:

    ```bash
    vagrant ssh
    ```

### Useful Vagrant Commands

- Start and provision the Vagrant environment:

    ```bash
    vagrant up
    ```

- Connect to the machine via SSH:

    ```bash
    vagrant ssh
    ```

- Stop the Vagrant machine:

    ```bash
    vagrant halt
    ```

- Restart Vagrant machine, load new Vagrantfile configuration:

    ```bash
    vagrant reload
    ```

- Stop and delete all traces of the Vagrant machine:

    ```bash
    vagrant destroy
    ```