
# My .config files

## config

make sure no `.config` file in your home directory
```shell
cd $HOME
git clone git@github.com:Adenialzz/.config.git
```

add the following lines to your ~/.zshrc

```shell
source ~/.config/misc/aliases.sh
if [ `basename $SHELL` = zsh ]; then
	source ~/.config/zsh/vi.zsh
fi
```
