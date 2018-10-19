# php-build

php-build provides a simple way to compile and install different
versions of PHP on UNIX-like systems.

_This project was forked from [ruby-build](https://github.com/rbenv/ruby-build),
and modified for PHP._

### Installing php-build

    $ git clone git://github.com/phpenv-dev/php-build.git
    $ cd php-build
    $ ./install.sh

This will install php-build into `/usr/local`. If you do not have
write permission to `/usr/local`, you will need to run `sudo
./install.sh` instead. You can install to a different prefix by
setting the `PREFIX` environment variable.

### Installing PHP

To install a PHP version, run the `php-build` command with the path
to a definition file and the path where you want to install it. (A
number of [built-in
definitions](https://github.com/phpenv-dev/php-build/tree/master/share/php-build)
may be specified instead.)

    $ php-build 5.0.0 ~/local/php-5.0.0

You can use it with [phpenv](https://github.com/phpenv-dev/phpenv):

    $ php-build 5.0.0 ~/.phpenv/versions/5.0.0

php-build provides an `phpenv-install` command that shortens this to:

    $ phpenv install 5.0.0

### License

(The MIT License)

Copyright (c) 2017 Septian Dwic.\
Copyright (c) 2011 Sam Stephenson

Permission is hereby granted, free of charge, to any person obtaining
a copy of this software and associated documentation files (the
"Software"), to deal in the Software without restriction, including
without limitation the rights to use, copy, modify, merge, publish,
distribute, sublicense, and/or sell copies of the Software, and to
permit persons to whom the Software is furnished to do so, subject to
the following conditions:

The above copyright notice and this permission notice shall be
included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND,
EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF
MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND
NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE
LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION
OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION
WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
