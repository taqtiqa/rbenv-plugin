rbenv-plugin
============

rbenv plugin to manage other rbenv plugins

Install
-------
The preferred method is to install this plugin as as part of your initial rbenv install.
Until necessary changes are merged upstream, this is best done via our
fork of Francesc Esplugas' [rbenv-installer](https://github.com/taqtiqa/rbenv-installer):

    curl https://raw.github.com/taqtiqa/rbenv-installer/master/bin/rbenv-installer | bash

Next preferred install method uses the [rbenv-path](https://github.com/taqtiqa/rbenv-path) plugin

    mkdir -p ~/.rbenv/plugins
    cd ~/.rbenv/plugins
    git clone https://github.com/taqtiqa/rbenv-plugin.git
    rbenv path append ${RBENV_ROOT}/plugins/rbenv-plugin/bin ${RBENV_ROOT}/bin

Finally, the Neckbeard install:

    mkdir -p ~/.rbenv/plugins
    cd ~/.rbenv/plugins
    git clone https://github.com/taqtiqa/rbenv-plugin.git
    export PATH="$HOME/.rbenv/plugins/rbenv-plugin/bin:$PATH"

Usage
-----
You can get help for the `plugin` command:

    rbenv help plugin

Help for the sub-commands is also available:

    rbenv help plugin-install

License
-------

The MIT license:

Copyright (c) 2013 Mark Van de Vyver <mark@taqtiqa.com>

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
