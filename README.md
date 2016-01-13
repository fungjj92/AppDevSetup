# App Development Environment
Vagrant, docker, ansible, grunt, yeoman, bower setup and integration for future angular app development.

This project is generated with [yo angular generator](https://github.com/yeoman/generator-angular)
version 0.15.1.

#About
Development environment running an angular app (Yeoman scaffold) in a docker container inside a Vagrant VM. Ansible to set up Vagrant environment and install dependencies needed for Docker to run inside. Bower installs app dependencies within the docker machine ("app") running the app. Live reload by Grunt.

# Installation

In the terminal, run ``vagrant up``.
Run ``vagrant provision``.
Pull up http://localhost:7300 in any browser, which should display the app

## Build & development

Run `grunt` for building and `grunt serve` for preview.

## Testing

Running `grunt test` will run the unit tests with karma.
