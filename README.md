# Luke
Simple scripts and templates for scaffolding a basic Django project


## Prerequisites
+ [Oracle's VirtualBox](https://www.virtualbox.org/)
+ [Vagrant](http://www.vagrantup.com/)
+ [Python](http://www.python.org/)
+ [Fabric](http://www.fabfile.org/)
+ [fabutils](https://github.com/vinco/fabutils)


## Usage
1. Clone the repository's (branch environment-campus)

    ```bash
    $ git clone -b environment-campus https://git@github.com/fierroformo/luke.git
    ```


2. Create the virtual machine

    ```bash
    $ cd luke
    $ vagrant up
    $ fab environment:vagrant bootstrap
    ```


4. Run server
    ```bash
    $ fab environment:vagrant runserver
    ```


4. URL development
* `http://0.0.0.0:8000/`
