vim-addon-nix
=============
See doc/addon-nix.txt

provides
* goto thing at cursor implementation (to follow import .. paths)
* vim-addon-action nix evaluation
* uses nix-instantiate to syntax check a .nix file on buf write

dependencies
* vim-addon-completion
* vim-addon-goto-thing-at-cursor
* vim-addon-errorformats
* vim-addon-actions
* vim-addon-mw-utils
* tlib

related work
============
there is nix-repl, too (see nixpkgs)
