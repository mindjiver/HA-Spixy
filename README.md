# High Availablity Spixy

[![Build Status](https://travis-ci.org/mindjiver/HA-Spixy.png?branch=add-readme-and-travis)](https://travis-ci.org/mindjiver/HA-Spixy)

High Availability Spixy is a IRC bot which will not go down. It
requires two nodes in a master-slave configuration. A heart beat
mechanism makes sure a switch over is performed if the master is
unresponsive.

## Development Environment

For development we use virtualenv to keep environment nice and
clean. Installation as follows:

    $ sudo pip install virtualenv
    $ virtualenv

## Production Environment

Production environment has not been defined yet. Most likely two
differnt VPS providers will be utilized.

## Deployment

Deployment will be performed of the master branch of the canonical git
repository. Suggestion is to use either SaltStack or Ansible.
