# phpenv-common-deps-install

It's a [CHH/phpenv](https://github.com/CHH/phpenv) plugin to add the `phpenv common-deps-install-*` command which install common dependencies for compiling/building PHP versions (using [php-build](https://github.com/php-build/php-build) attached in command `phpenv install <VERSION>).


## Installation

Simply clone the repository into the plugins directory:

```shell
mkdir -p "$(phpenv root)/plugins"
git clone https://github.com/rogeriopradoj/phpenv-common-deps-install.git "$(phpenv root)/plugins/phpenv-common-deps-install"
```

## Usage

```shell
# OS X Yosemite
phpenv common-deps-install-osx-yosemite
```

```shell
# Ubuntu 14.04
phpenv common-deps-install-ubuntu-14-04
```

```shell
# Ubuntu 12.04
phpenv common-deps-install-ubuntu-12-04
```

```shell
# Ubuntu 10.04
phpenv common-deps-install-ubuntu-10-04
```

<hr>

This project is based on https://github.com/fesplugas/rbenv-bootstrap.
