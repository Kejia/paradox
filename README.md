Paradox
=======

Project for generating and displaying Package Ratings for Emacs packages.

To install it, open the file and call `M-x package-install-from-buffer`.

To use it, simply call `M-x paradox-list-packages` (instead of the regular `list-packages`).

## Current Features ##

* Display number of GitHub Stars the package has (right before the description).
* Display useful information on the mode-line.
* `hl-line-mode` enabled by default.

## Planned Features ##

* Star and unstar packages from within the Package Menu.
* Package filtering.
* More fontification.
* More customization.

## Known Bugs ##

* Annoying gnutls error message after downloading the star counts `gnutls.c: [0] (Emacs) fatal error: The TLS connection was non-properly terminated.`.  
  If anyone knows how to fix it, I'm all ears.

