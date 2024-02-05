# terminal-configurations
My terminal configurations for UbuntuWSL 

1. first download Ubuntu for wSL
2. update Ubuntu:
    ```
   sudo apt update -y && sudo apt upgrade -y
    ```
3. install zsh:
   ```
   sudo apt install zsh
   ```
4. install ohMyZsh from https://ohmyz.sh/#install
   ```
   sh -c "$(curl -fsSL https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"
   ```
5. install nerdFont from https://www.nerdfonts.com/font-downloads
6. change font in terminal options
7. install starship from curl -sS https://starship.rs/install.sh | sh
8. add the following to the shell, in this case zsh (~/.zshrc):
   ```
   eval "$(starship init zsh)"
   ```
9. restart terminal
10. create a directory on ~ called ".config"
    ```
    mkdir .config
    ```
11. go to .config and create a file called starship.toml
    ```
    cd .config
    touch starship.toml
    ```
12. open with vim/emacs/nano/etc. and copy all the content from the starship.toml file on this repository and paste it in the file you created
13. it should look like this:
    
    ![image](https://github.com/razemint/terminal-configurations/assets/40744507/eeb27193-0140-4af1-a997-932ca95576ed)



