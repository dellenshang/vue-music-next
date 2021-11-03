安装 Homebrew  https://brew.sh/
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"

brew install nvm
mkdir ~/.nvm
编辑文件vi ~/.zshrc
输入source $(brew --prefix nvm)/nvm.sh这行代码
然后执行source ~/.zshrc使之生效
执行nvm -v就可以看到版本号了
通过nvm安装node.js
安装指定的版本nvm install v14.17.5
使用指定的版本nvm use v14.17.5
查看当前的已经有的node.js版本nvm list
输入node -v查看node版本
输入npm -v查看npm版本




Mac下彻底卸载node
homebrew安装的
直接一条命令
brew uninstall node

官网下载pkg安装包的
一条命令
sudo rm -rf /usr/local/{bin/{node,npm},lib/node_modules/npm,lib/node,share/man/*/node.*}