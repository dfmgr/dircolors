## dircolors  
  
dircolors outputs a sequence of shell commands to set up the terminal for color output  
  
Automatic install/update:

```shell
bash -c "$(curl -LSs https://github.com/dfmgr/dircolors/raw/main/install.sh)"
```

Manual install:
  
requires:

Debian based:

```shell
apt install coreutils
```  

Fedora Based:

```shell
yum install coreutils
```  

Arch Based:

```shell
pacman -S coreutils
```  

MacOS:  

```shell
brew install coreutils
```
  
```shell
mv -fv "$HOME/.config/dircolors" "$HOME/.config/dircolors.bak"
git clone https://github.com/dfmgr/dircolors "$HOME/.config/dircolors"
```
  
<p align=center>
  <a href="https://www.gnu.org/software/coreutils/manual/html_node/dircolors-invocation.html" target="_blank" rel="noopener noreferrer">dircolors site</a>
</p>  
