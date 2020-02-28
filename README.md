![License: GPL
v3](https://img.shields.io/badge/License-GPL%20v3-blue.svg)
![MELPA](https://melpa.org/packages/doneburn-theme-badge.svg)

This is a dark on light Emacs theme based on [Bozhidar Batsov’s Zenburn
theme](https://github.com/bbatsov/zenburn-emacs).

Chris Done created [the original
theme](https://github.com/chrisdone/zenburn). This is an updated version
for modern Emacsen.

Screenshot
==========

![Screenshot](https://github.com/manuel-uberti/doneburn/blob/master/screenshot.png)

Setup
=====

The theme is available on MELPA. You can easily install and configure it
with [use-package](https://github.com/jwiegley/use-package):

    (use-package doneburn-theme
      :ensure t
      :config (load-theme 'doneburn 'no-confirm))

Notes
=====

I am not using this theme at the moment.

It was born out of my desire to make Chris Done’s original theme easily
available to and modifiable by everyone, but please note that it lacks support
for many packages (e.g., Helm).

PRs are more than welcome.
