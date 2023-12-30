plugin.nvim
***********

This repo is an attempt to figure out the necessary
directory layout to create a lua plugin for neovim that
is installable with Lazy.nvim.

The only thing it does is echo the following message::

  plugin.nvim has been loaded

To see it, run ``:messages``.

The file inside of the ``plugin`` directory will be
run when nvim starts.

The code in ``lua`` is library code. It can be required
by the initialization code under ``plugin``.

See here for more: https://m4xshen.dev/posts/develop-a-neovim-plugin-in-lua/
