![bash](https://img.shields.io/badge/language-bash-blue.svg)[![Platform (Linux, OS X)](https://img.shields.io/badge/platform-Linux,%20OS%20X-green.svg?style=flat-square)]()

[![drone.io](https://drone.io/github.com/russianidiot/google-chrome-open.sh.cli/status.png)](https://drone.io/github.com/russianidiot/google-chrome-open.sh.cli)
[![scrutinizer-ci.com](https://scrutinizer-ci.com/g/russianidiot/google-chrome-open.sh.cli/badges/build.png?b=master)](https://scrutinizer-ci.com/g/russianidiot/google-chrome-open.sh.cli/)
[![semaphoreci.com](https://semaphoreci.com/api/v1/russianidiot/google-chrome-open-sh-cli/branches/master/shields_badge.svg)](https://semaphoreci.com/russianidiot/google-chrome-open-sh-cli)
[![shippable.com](https://api.shippable.com/projects/570bc2532a8192902e1be7ce/badge?branch=master)](https://app.shippable.com/projects/570bc2532a8192902e1be7ce)
[![travis-ci.org](https://travis-ci.org/russianidiot/google-chrome-open.sh.cli.svg)](https://travis-ci.org/russianidiot/google-chrome-open.sh.cli)
[![wercker.com](https://app.wercker.com/status/9932df02a4eaef805f765bee62418b23/s/master)](https://app.wercker.com/#applications/57201c4f58d2b35867095a26)

[![PyPI](https://img.shields.io/pypi/v/google-chrome-open.svg)](https://pypi.python.org/pypi/google-chrome-open)
[![PyPI](https://img.shields.io/pypi/dm/google-chrome-open.svg)](https://pypi.python.org/pypi/google-chrome-open)
[![PyPI](https://img.shields.io/pypi/dd/google-chrome-open.svg)](https://pypi.python.org/pypi/google-chrome-open)

[![npm](https://img.shields.io/npm/v/google-chrome-open.svg)](https://www.npmjs.com/package/google-chrome-open)[![npm](https://img.shields.io/npm/dm/google-chrome-open.svg)](https://www.npmjs.com/package/google-chrome-open)[![npm](https://img.shields.io/npm/dt/google-chrome-open.svg)](https://www.npmjs.com/package/google-chrome-open)

<p align="center">
    <b>open/refresh url in Google Chrome</b>
</p>

#### Install

pip: 
`[sudo] pip install google-chrome-open`

npm: 
`npm install -g google-chrome-open`

#### Usage

```shell
usage: google-chrome-open [options] url
	-f  Frontmost
	-r  Refresh
```

#### Example

```shell
$ url="https://github.com/"
$ google-chrome-open "$url"

# arguments:
$ google-chrome-open -f "$url" # make tab frontmost
$ google-chrome-open -r "$url" # refresh tab
$ google-chrome-open -f -r "$url" # refresh and make frontmost :)

# arguments:
$ google-chrome-open "$url"
$ open -a "Google Chrome" # make Chrome frontmost app

```

[Examples/](https://github.com/russianidiot/google-chrome-open.sh.cli/tree/master/Examples)

Sources:
*	[scripts/google-chrome-open](https://github.com/russianidiot/google-chrome-open.sh.cli/blob/master/bin/google-chrome-open)

Feedback
[![GitHub issues](https://img.shields.io/github/issues/russianidiot/google-chrome-open.sh.cli.svg)](https://github.com/russianidiot/google-chrome-open.sh.cli/issues)
[![Join the chat at https://gitter.im/russianidiot/google-chrome-open.sh.cli](https://badges.gitter.im/russianidiot/google-chrome-open.sh.cli.svg)](https://gitter.im/russianidiot/google-chrome-open.sh.cli)
[![GitHub followers](https://img.shields.io/github/followers/russianidiot.svg?style=social&label=Follow)](https://github.com/russianidiot)

* * *

<p align="center">
	Python packages <a href="http://russianidiot.github.io/python/">russianidiot.github.io/python/</a>
	<img src="http://russianidiot.github.io/images/python/16.png" />
</p>
<p align="center">
	cli packages <a href="http://russianidiot.github.io/python/">russianidiot.github.io/cli/</a>
<img src="http://russianidiot.github.io/images/cli/16.png" />
</p>

<p align="center">
	repos list <a href="http://russianidiot.github.io/">russianidiot.github.io</a> <img src="http://russianidiot.github.io/images/star/16.png" />
</p>

<p align="center">
	<a href="https://raw.githubusercontent.com/russianidiot/google-chrome-open.sh.cli/master/README.md">README.md</a> generated with <a href="https://github.com/russianidiot/readme-mako.py">readmemako.py</a> (python+<a href="http://www.makotemplates.org/">mako</a> templates) and <a href="https://github.com/russianidiot-dotfiles/.README">.README</a> dotfiles 
<img src="http://russianidiot.github.io/images/book/16.png">
</p>
