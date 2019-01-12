wkhtmltopdf
================

This repository contains the static compiled binaries from the [wkhtmltopdf project](http://wkhtmltopdf.org/) for CentOS 6 amd64.
More about the functionality of wkhtmltopdf and wkthmltoimage can be found there.

## Installation

### Packagist

This package can be found on [Packagist](http://packagist.org) and installed with [Composer](https://getcomposer.org/).

Require the package with:

    composer require fernandesramon/wkhtmltopdf-amd64-centos6 "0.12.5"

The binary will then be located at:

    vendor/fernandesramon/wkhtmltopdf-amd64-centos6/bin/wkhtmltoimage-amd64-centos6
    vendor/fernandesramon/wkhtmltopdf-amd64-centos6/bin/wkhtmltopdf-amd64-centos6

Also a symlink will be created in your configured bin/ folder:

    vendor/bin/wkhtmltoimage-amd64-centos6
    vendor/bin/wkhtmltopdf-amd64-centos6
