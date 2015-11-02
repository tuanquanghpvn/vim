# Vim Config

###To setup Vim on new machine:
```bash
cd ~
```

```bash
git clone https://github.com/tuanquanghpvn/vim.git ~/.vim
```

```bash
ln -s ~/.vim/.vimrc ~/.vimrc
```

```bash
cd ~/.vim
```

```bash
git submodule init
```

```bash
git submodule update
```

###To upgrade all plugins:
```bash
git submodule foreach git pull origin master
```
