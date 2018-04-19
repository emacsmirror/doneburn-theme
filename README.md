# doneburn

[![License GPL 3][badge-license]](http://www.gnu.org/licenses/gpl-3.0.txt)

This is a dark on light Emacs theme based on [Bozhidar Batsov's Zenburn
theme](https://github.com/bbatsov/zenburn-emacs).

Chris Done created [the original theme](https://github.com/chrisdone/zenburn).
This is an updated version for modern Emacsen.

## Screenshot

![Screenshot](https://github.com/manuel-uberti/doneburn/blob/master/screenshot.png)

## Setup

As of now, the theme is not available on MELPA. You can still clone the
repository and give it a try with something like:

``` emacs-lisp
(use-package doneburn-theme
  :load-path "<path-to-cloned-repo>"
  :config (load-theme 'doneburn 'no-confirm))
```

## Note

This theme is still a work in progress, mainly useful for my own daily usage for
now. It lacks support for popular packages (e.g. Helm) simply because I just
added the faces for the packages I use.

PRs are more than welcome.
