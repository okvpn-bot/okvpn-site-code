# The okvpn.org site code

The okvpn.org site code. It basis on php7.0 and Kohana framework.

[![Travis CI build status](https://travis-ci.org/okvpn/okvpn-site-code.svg?branch=master)](https://travis-ci.org/okvpn/okvpn-site-code)

## Installation

Clone and install with  composer

```bash
    git clone https://github.com/okvpn/okvpn-site-code.git
    cd okvpn-site-code
    composer install
```

Run migrations.

```bash
phinx migrate
phinx seeds:run
```

## LICENSE

Mit license