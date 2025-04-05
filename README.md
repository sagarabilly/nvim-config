# nvim-config  
This is a neovim configuration file  
It is slightly modified from the famous kickstart.nvim repository.

## Note:  
1. Make sure you have installed all the dependencies including:  
   python, rust, golang, npm, javascript(nodejs), git, make, unzip, C Compiler (gcc from MinGW and clang from LLVM), and NerdFont  

2. If there is error occured regarding the nvim-treesitter please reinstall all the language parser:
  ```neovim
   :TSUninstall all  
   :TSUpdateSync  
  ```  

3. For windows, the configuration file should be placed in:  
    C:\Users\\<user_name>\AppData\Local\nvim  
   And please rename the folder to nvim after cloning it.  
   (if there is already nvim folder, delete it)  

