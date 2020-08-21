## dircolors  
  
dircolors outputs a sequence of shell commands to set up the terminal for color output  
  
Automatic install/update:
```
bash -c "$(curl -LSs https://github.com/dfmgr/dircolors/raw/master/install.sh)"
```
Manual install:
requires:    
```
apt install coreutils
```  
```
yum install coreutils
```  
```
pacman -S coreutils
```  
  
```
mv -fv "$HOME/.config/dircolors" "$HOME/.config/dircolors.bak"
git clone https://github.com/dfmgr/dircolors "$HOME/.config/dircolors"
```
  
  
<p align=center>
  <a href="https://www.gnu.org/software/coreutils/manual/html_node/dircolors-invocation.html" target="_blank">dircolors site</a>
</p>  
