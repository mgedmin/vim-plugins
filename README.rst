mgedmin's vim plugins
=====================

This is a helper repo to help me maintain my Vim plugins.

Usage::

  pipx install ghcloneall
  git clone https://github.com/mgedmin/vim-plugins ~/src/vim-plugins
  cd ~/src/vim-plugins
  ghcloneall

Then if you have any of the plugins already checked out in ~/.vim/bundle/,
and would like to avoid having two copies, you can deduplicate ::

  ./replace-with-symlinks
  rm -rf *.BAK
