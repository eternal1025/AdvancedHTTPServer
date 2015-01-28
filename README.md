# AdvancedHTTPServer
Standalone web server built on Python's BaseHTTPServer

[![Build Status](http://img.shields.io/travis/zeroSteiner/AdvancedHTTPServer.svg?style=flat-square)](https://travis-ci.org/zeroSteiner/AdvancedHTTPServer)
[![Documentation Status](https://readthedocs.org/projects/advancedhttpserver/badge/?version=latest&style=flat-square)](http://advancedhttpserver.readthedocs.org/en/latest)
[![Github Issues](http://img.shields.io/github/issues/zerosteiner/AdvancedHTTPServer.svg?style=flat-square)](https://github.com/zerosteiner/AdvancedHTTPServer/issues)
[![PyPi Release](https://img.shields.io/pypi/v/AdvancedHTTPServer.svg?style=flat-square)](https://pypi.python.org/pypi/AdvancedHTTPServer)

## License
AdvancedHTTPServer is released under the BSD 3-clause license, for more details
see the [LICENSE](https://github.com/zeroSteiner/AdvancedHTTPServer/blob/master/LICENSE)
file.

## Features
AdvancedHTTPServer builds on top of Python's included BaseHTTPServer and
provides out of the box support for additional commonly needed features such as:
 - Threading
 - SSL
 - Registering handler functions to HTTP resources
 - A default robots.txt file
 - Forking the server process
 - Basic Authentication
 - The HTTP verbs GET HEAD POST and OPTIONS
 - RPC over HTTP

## Dependencies
AdvancedHTTPServer does not have any additional dependencies outside of the
Python standard library.

The following version of Python are currently supported:
 - Python 2.7
 - Python 3.3
 - Python 3.4

## Code Documentation
AdvancedHTTPServer uses Sphinx for internal code documentation. This
documentation can be generated from source with the command
```sphinx-build docs/source docs/build```. The latest documentation is
kindly hosted on [ReadTheDocs](https://readthedocs.org/) at
[advancedhttpserver.readthedocs.org](https://advancedhttpserver.readthedocs.org/en/latest/).

## Powered By AdvancedHTTPServer
 - [King Phisher](https://github.com/securestate/king-phisher) Phishing Campaign Toolkit
