# nvim-config  
This is a neovim configuration file written in lua.    
It is just slightly added from the famous kickstart.nvim repository, so it has some general plugins like Telescope, etc.  

This configuration is used mainly for python, rust, or go with pyright, rust-analyzer, gopls, and others.
It is also added with REPL iron.nvim, bufferline, etc. 
Feel free to adjust the config to your liking. 


## Note:  
1. Make sure you have installed all the dependencies including:  
   npm, git, make, unzip, C Compiler (if using windows: gcc from MinGW and clang from LLVM), and NerdFont.
   And also your programming language for the language server like: python, javascript(nodejs), rust, go, etc.

3. If there is an issue occured regarding the nvim-treesitter please reinstall all the language parser:
  ```neovim
   :TSUninstall all  
   :TSUpdateSync  
  ```  

3. For windows, the configuration file should be placed in:  
    C:\Users\\<user_name>\AppData\Local\nvim  
   And please rename the folder to nvim after cloning it.  
   (if there is already nvim folder, delete it)  

