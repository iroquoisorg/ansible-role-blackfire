# blackfire

[![Build Status](https://travis-ci.com/iroquoisorg/ansible-role-blackfire.svg?branch=master)](https://travis-ci.com/iroquoisorg/ansible-role-memcached)

Ansible role for blackfire

This role was prepared and tested for Ubuntu 16.04.

# Installation

`$ ansible-galaxy install iroquoisorg.blackfire`

# Default settings

```
blackfire_install_cli: true
blackfire_install_agent: false
blackfire_php_module_service: 'change-me' # apache2 | httpd | php7.2-fpm

```
