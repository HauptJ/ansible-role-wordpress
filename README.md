# ansible-role-wordpress
Ansible role to install and configure WordPress

[![Build Status](https://travis-ci.org/HauptJ/ansible-role-wordpress.svg?branch=master)](https://travis-ci.org/HauptJ/ansible-role-wordpress)

## Installation
1. Fork this repository
2. git submodule add <git host> roles/ansible-role-wordpress
    - [submodule reference](https://chrisjean.com/git-submodules-adding-using-removing-and-updating/)


## Variables

### WordPress

| Name 						      | Default 							                    | Description 										  |
|-----------------------|-------------------------------------------|-----------------------------------|
| resty_default_web_dir | /usr/local/openresty/nginx/html/default   | web directory                     |
| php_fpm_daemon        | php-fpm
| php_fpm_handler_state | restarted
