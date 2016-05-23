.. image:: https://img.shields.io/badge/language-bash-blue.svg

Install
```````

:code:`[sudo] pip install google-chrome-open`

Usage
`````

.. code:: shell
	
	usage: google-chrome-open [options] url
		-f  Frontmost
		-r  Refresh

Example
```````

.. code:: shell
	
	$ url="https://github.com/"
	$ google-chrome-open "$url"
	$ google-chrome-open -f "$url" # make tab frontmost
	$ google-chrome-open -r "$url" # refresh tab
	$ google-chrome-open -f -r "$url" # refresh and make frontmost :)

`Examples/`_

.. _Examples/: https://github.com/russianidiot/google-chrome-open.sh.cli/tree/master/Examples

Feedback |github_issues| |gitter| |github_follow|

.. |github_issues| image:: https://img.shields.io/github/issues/russianidiot/google-chrome-open.sh.cli.svg
	:target: https://github.com/russianidiot/google-chrome-open.sh.cli/issues

.. |github_follow| image:: https://img.shields.io/github/followers/russianidiot.svg?style=social&label=Follow
	:target: https://github.com/russianidiot

.. |gitter| image:: https://badges.gitter.im/russianidiot/google-chrome-open.sh.cli.svg
	:target: https://gitter.im/russianidiot/google-chrome-open.sh.cli

----

`russianidiot.github.io/python/`_  - Python packages

.. _russianidiot.github.io/python/: http://russianidiot.github.io/python/

`russianidiot.github.io/cli/`_  - command line scripts

.. _russianidiot.github.io/cli/: http://russianidiot.github.io/cli/

`README.rst`_  - generated with `readmemako.py`_ (python+ `mako`_ templates) and `.README`_ dotfiles

.. _README.rst: https://github.com/russianidiot/google-chrome-open.sh.cli/blob/master/README.rst
.. _readmemako.py: http://github.com/russianidiot/readmemako.py/
.. _mako: http://www.makotemplates.org/
.. _.README: https://github.com/russianidiot-dotfiles/.README
