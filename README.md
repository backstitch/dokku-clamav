# dokku-weasyprint

dokku-clamav is an awesome plugin for [dokku][dokku] that properly installs the clamav into the docker instance.
This plugin should fix the problems you may have when downloading clamav with ```apt-get``` for example by using another awesome plugin [dokku-apt][dokku-apt].

## Installation

On your dokku server:
```
# On 0.3.x
git clone https://github.com/backstitch/dokku-clamav /var/lib/dokku/plugins/dokku-clamav

# On 0.4.x
dokku plugin:install https://github.com/backstitch/dokku-clamav.git clamav
```

All future deployments will have dokku-clamav installed.

## License

The MIT License (MIT)

Copyright (c) 2019 backstitch

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
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

[dokku]: https://github.com/progrium/dokku
[dokku-apt]: https://github.com/F4-Group/dokku-apt
