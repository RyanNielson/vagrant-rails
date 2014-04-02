Ruby on Rails Vagrant Box
=============

A Ruby on Rails Vagrant box with all the software you need to start developing applications.

### Software Included
- Ubuntu 12.04
- Ruby on Rails 4.0.3
- Node.js
- Ruby 2.0.0-p353
- Postgresql
- Redis
- Git

### Getting Started
- Install [Virtualbox](https://www.virtualbox.org/wiki/Downloads)
- Install [Vagrant](http://downloads.vagrantup.com/)
- Copy Vagrantfile and Cheffile to your project by downloading or cloning using Git
- Run `gem install librarian-chef`
- Run `librarian-chef install` to use librarian to download the required Chef cookbooks
- Run `vagrant up` to provision your Vagrant box with the included software. This may take a while, but when finished your Ruby on Rails development environment will be ready for use.
- Run `vagrant ssh` to access your Vagrant box

### Other Stuff
- The Vagrantfile sets up a Postgres user called `postgres` with the password `password`. Use this information whenever you have to connect to your database.

### Contributing
- I encourage any pull requests or issue reports. I'll more than likely accept anything that improves the project.
