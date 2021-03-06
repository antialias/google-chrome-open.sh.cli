.. README generated with readmemako.py (github.com/russianidiot/readme-mako.py) and .README dotfiles (github.com/russianidiot-dotfiles/.README)

Install
```````

:code:`[sudo] pip install google-chrome-open`

Usage
`````
.. code:: bash

	# google-chrome-open --help
	

Example
```````

.. code:: bash

	$ url="https://github.com/"
	$ google-chrome-open "$url"
	
	# arguments:
	$ google-chrome-open -f "$url" # make tab frontmost
	$ google-chrome-open -r "$url" # refresh tab
	$ google-chrome-open -f -r "$url" # refresh and make frontmost :)
	
	# arguments:
	$ google-chrome-open "$url"
	$ open -a "Google Chrome" # make Chrome frontmost app

`Examples/`_

.. _Examples/: https://github.com/russianidiot/google-chrome-open.sh.cli/tree/master/Examples

Feedback |github_issues| |gitter| |github_follow|

.. |github_issues| image:: https://img.shields.io/github/issues/russianidiot/google-chrome-open.sh.cli.svg
	:target: https://github.com/russianidiot/google-chrome-open.sh.cli/issues

.. |github_follow| image:: https://img.shields.io/github/followers/russianidiot.svg?style=social&label=Follow
	:target: https://github.com/russianidiot

.. |gitter| image:: https://badges.gitter.im/russianidiot/google-chrome-open.sh.cli.svg
	:target: https://gitter.im/russianidiot/google-chrome-open.sh.cli
