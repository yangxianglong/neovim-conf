# neovim-conf
## 这个配置用到了packer包管理工具，安装插件之前需要通过下面的命令安装packer。
```shell
# 具体命令参照Github。https://github.com/wbthomason/packer.nvim#quickstart
git clone --depth 1 https://github.com/wbthomason/packer.nvim\
 ~/.local/share/nvim/site/pack/packer/start/packer.nvim
```
## lua/plugin.lua文件里面追加插件引用之后:wq保存，再次打开这个文件执行:PackerSync。
```shell
# 常用命令
:PackerInstall 
:PackerUpdate
:PackerSync
```
## lua/plugin-config/nvim-treesitter.lua文件里面配置需要的编程语言服务之后:wq保存，再次打开这个文件执行:TSUpdate。
```shell
# 查看已安装的 Language parser
:TSInstallInfo 
```
## 为了使用toggleterm插件中的lazygit拓展功能，需要通过下面命令安装lazygit。
```shell
# 具体命令可以google关键词“brew lazygit”。
brew install lazygit

```
