# my-nvim-setup
this is my nvim setup code editor on window 10 
## Step By Step
1. go to website `Lazyvim` from [lazyvim](https://www.lazyvim.org) and go to `installation` cliked at `window`
2. open powershell by `administrator` and copy this command step by step:
Follow step 
Make a backup of your current Neovim files: 
```
Move-Item $env:LOCALAPPDATA\nvim $env:LOCALAPPDATA\nvim.bak
```
Clone starter 
```
git clone https://github.com/LazyVim/starter $env:LOCALAPPDATA\nvim
```
Remove the `.git` folder, so you can add it to your own repo later
```
Remove-Item $env:LOCALAPPDATA\nvim\.git -Recurse -Force
```
Opening up `terminal` and type:
```
nvim
```
3. after you open up nvim on `terminal` it will start install neccesary tool wait until it finish 
4. you can see `tree-sitter` try to install but fail
![Image](https://github.com/user-attachments/assets/0dbd9369-5c7c-479d-a8f3-160531e092ef) \
to fix this you need to install from external installer like `winget` `choco` or other installer 
Winget
```
winget install tree-sitter
```
Choco
```
choco install tree-sitter
```
NPM
```
npm install -g tree-sitter-cli
```
