Minimal nginx to run with docker-remote-api
===========================================

[![Project is](https://img.shields.io/badge/Project%20is-fantastic-ff69b4.svg)](https://github.com/Bessonov/docker-remote-api-nginx)
[![Build Status](https://img.shields.io/docker/build/bessonov/docker-remote-api-nginx.svg)](https://hub.docker.com/r/bessonov/docker-remote-api-nginx/builds/)
[![License](http://img.shields.io/:license-MIT-blue.svg)](https://raw.githubusercontent.com/Bessonov/docker-remote-api-nginx/master/LICENSE.txt)

A minimal nginx version used with [docker-remote-api](https://galaxy.ansible.com/Bessonov/docker-remote-api/) role. This image isn't intended for usage outside of the ansible role, because nginx worker runs as root to access docker.sock.

Credits
-------

Thanks to Nginx, Inc. team for great product and providing their [Dockerfile](https://github.com/nginxinc/docker-nginx) and [kekru/docker-remote-api-tls](https://github.com/kekru/docker-remote-api-tls) for inspiration.

License
-------

The MIT License (MIT)

Copyright (c) 2017, Anton Bessonov

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.
