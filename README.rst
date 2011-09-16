Pylint-mode, PyLint in VIM
==========================

Pylint-mode is a vim mode that allows you to use the pylint_ library in vim to provide
features like python code looking for bugs.

This vim plugin allow you use the pylint library in vim very easily.
There is no need to install the pylint_ library on your system.


Installation
------------

Just copy the plugin folders into your ~/.vim directory.

Alternatively, if you are using pathogen_, clone the plugin into your ``bundle``
folder.


Settings
--------

To change this settings, edit your `~/.vimrc` file.

Open vim quickfix_ window if problems be find ::

    let g:PyLintCWindow = 1

Place signs with errors ::

    let g:PyLintSigns = 1

Run pylint on buffer write ::

    let g:PyLintOnWrite = 1

Disable PyLint messages ::

    let g:PyLintDissabledMessages = 'C0103,C0111,C0301,W0141,W0142,W0212,W0221,W0223,W0232,W0401,W0613,W0631,E1101,E1120,R0903,R0904,R0913'


.. _quickfix: http://vimdoc.sourceforge.net/htmldoc/quickfix.html
.. _pylint: http://www.logilab.org/857
.. _pathogen: https://github.com/tpope/vim-pathogen
