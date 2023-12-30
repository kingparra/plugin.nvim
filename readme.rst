plugin.nvim
***********

This repo is an attempt to figure out the necessary
directory layout to create a lua plugin for neovim that
is installable with Lazy.nvim.

When you press ``<Leader>h``, it will print the message
``"Hello, {name}"``, where name is the value of ``opts.name``.

Here is an example of how to install the plugin using lazy.nvim,
and set the ``opts.name`` attribute to ``"Chris"``.

::

  require('lazy').setup({
    {
      'kingparra/plugin.nvim',
      opts = {
        name = "Chris",
      }
    },
    ...
    }

See here for more: https://m4xshen.dev/posts/develop-a-neovim-plugin-in-lua/
