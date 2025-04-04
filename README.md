# nvim-config  
This is my neovim configuration file  
It is slightly modified from the nvim-kickstart repository by TJ  

## Note:  
1. Make sure you have installed all the dependencies including:  
   python, rust, golang, npm, javascript(nodejs), git, make, unzip, C Compiler (gcc from MinGW and clang from LLVM), and NerdFont  

2. If there is error occured regarding the nvim-treesitter please reinstall all the language parser:
  ```neovim
   :TSUninstall all  
   :TSUpdateSync  
  ```  

3. For windows, the configuration file should placed in:  
    C:\Users\<user_name>\AppData\Local\nvim 
  So, please clone the repository using ```git clone https://github.com/sagarabilly/nvim-config``` at:
    C:\Users\<user_name>\AppData\Local\
   And please rename the folder to nvim (delete theres already nvim folder, delete it)

