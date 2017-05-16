# old-vagrant-conf
A vagrant LAMP configuration for Laravel given specific server requirements.

# Setup

Before starting, make sure [Vagrant](https://www.vagrantup.com/) is installed, along with a VM hypervisor such as Virtualbox.

## Test Run
To run this project as-is, run `vagrant up` and go to `http://localhost:8080` in a browser.

## Usage in a project
1. Copy over Vagrantfile and bootstrap.sh.
   ```bash
   $ cp Vagrantfile project_path/
   $ cp bootstrap.sh project_path/
   ```

2. Change to the directory of your project.
   ```bash
   $ cd project_path
   ```

2. Run `vagrant up`.

3. If you need to make any changes to the bootstrap script or the configuration file, make sure to run `vagrant reload --provision`.
