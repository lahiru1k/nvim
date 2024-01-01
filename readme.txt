For a Clean install
1. install neovim in the default dir
2. install packer user ps (windows) - https://github.com/wbthomason/packer.nvim
3. do go to the nvim dir do nvim .
4. go to lua/user/packer.lua then do :w, :so, :PackerSync
   (now it should install the plugins)
5. :so and restart nvim.

//now the basics are done.

Mason 
clangd --lps install
//lualps --default
//cpptools --byvscode

Treesitter
:TSInstall cpp
//:TSInstall c