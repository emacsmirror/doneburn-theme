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

This theme lacks support for popular packages (e.g. Helm) simply because
I just added the faces for the packages I use.

I just wanted to make Chris Done’s original theme easily available to
and modifiable by everyone.

PRs are more than welcome.
