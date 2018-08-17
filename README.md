

## 概要

Karabiner-Elements の config を保存します。

## インストール

https://github.com/tekezo/Karabiner-Elements


### configの反映

シンボリックリンクで反映させます

```
WORK_DIR=yoru-work-directory

cd $WORK_DIR
git clone git@github.com:hagetak/karabiner-elements-config.git

mkdir -p ~/.config/karabiner/
cp ~/.config/karabiner/karabiner.json{,.org}
ln -s $WORK_DIR/karabiner-elements-config/karabiner.json ~/.config/karabiner/
```
