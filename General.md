# Ubuntu setup

### 1. Google chrome

##### 1.1. Download google chrome

```
wget https://dl.google.com/linux/direct/google-chrome-stable_current_amd64.deb
```

##### 1.2. Install google chrome

```
sudo apt install ./google-chrome-stable_current_amd64.deb -y
```

### 2. Update 

```
sudo apt update
```



### 3. Install git

##### 3.1. Install git

```
sudo apt install git -y
```

##### 3.2. Check git version

```
git --version
```

### 4. Install vim

##### 4.1. Install vim

```
sudo apt-get install vim -y
```

##### 4.2. Check vim version

```
vim -v
```

### 5. Install zsh & plugins

##### 5.1. Install zsh

```
sudo apt-get install zsh -y
```

##### 5.2. Install oh-my-zsh

```
sh -c "$(curl -fsSL https://raw.githubusercontent.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"
```

##### 5.3. Clone plug-in

###### Autosuggestion

```
git clone https://github.com/zsh-users/zsh-autosuggestions.git $ZSH_CUSTOM/plugins/zsh-autosuggestions
```

###### Syntax-highlighting

```
git clone https://github.com/zsh-users/zsh-syntax-highlighting.git $ZSH_CUSTOM/plugins/zsh-syntax-highlighting
```

##### 5.4. Add plug-in

```
vim ~/.zshrc
```

Find line starting with **plugins** then add *zsh-autosuggestions zsh-syntax-highlighting* 

