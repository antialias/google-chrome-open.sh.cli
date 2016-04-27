![bash](https://img.shields.io/badge/language-bash-blue.svg)[![Platform (Linux, OS X)](https://img.shields.io/badge/platform-Linux,%20OS%20X-green.svg?style=flat-square)]()

[![Build Status](https://travis-ci.org/russianidiot/google-chrome-open.sh.cli.svg?branch=master)](https://travis-ci.org/russianidiot/google-chrome-open.sh.cli)[![drone.io](https://drone.io/github.com/russianidiot/google-chrome-open.sh.cli/status.png)](https://drone.io/github.com/russianidiot/google-chrome-open.sh.cli)[![Wercker](https://img.shields.io/wercker/ci/russianidiot/google-chrome-open.sh.cli.svg)](https://app.wercker.com/#applications/None/)

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
$ google-chrome-open -f "$url" # make tab frontmost
$ google-chrome-open -r "$url" # refresh tab
$ google-chrome-open -f -r "$url" # refresh and make frontmost :)
```

Sources:
*	[scripts/google-chrome-open](https://github.com/russianidiot/google-chrome-open.sh.cli/blob/master/scripts/google-chrome-open)

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
