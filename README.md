# Simple Password Store
=======================
### by Jason Donenfeld
### Jason@zx2c4.com

This is a very simple password store that encrypts passwords using gpg and
places the encrypted password in a directory. It can generate new passwords
and keep track of old ones.

Visit the project page for more information: http://www.passwordstore.org/

Please see the man page for documentation and examples.

Depends on:
- bash
  http://www.gnu.org/software/bash/
- GnuPG2
  http://www.gnupg.org/
- git
  http://www.git-scm.com/
- ~~xclip (for X11 environments)~~
  ~~http://sourceforge.net/projects/xclip/~~ **not needed for macOS**
- ~~wl-clipboard (for wlroots Wayland-based environments)~~
  ~~https://github.com/bugaevc/wl-clipboard~~ **not needed for macOS**
- tree >= 1.7.0
  http://mama.indstate.edu/users/ice/tree/
- GNU getopt
  http://www.kernel.org/pub/linux/utils/util-linux/
  http://software.frodo.looijaard.name/getopt/
- qrencode
  https://fukuchi.org/works/qrencode/

### MacOS
Modifications _only_ made for macOS compatiblility using macports.

