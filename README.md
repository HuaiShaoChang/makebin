# makebin
New or edit local user script and make it executable.

## Description
Create and edit script files in ~/bin and make it executable right away.  
It uses **vim** as default editor.

## Requirement
- text editor
  - Vim
    - Debian & Ubuntu: `apt-get install vim`
  - ~~or others~~(comming soon.)

## Installation
```bash
cd ~ && git clone https://github.com/huaishaochang/makebin
cd makebin && . ./install
cd ~ && rm -rf makebin
```

## Usage
1. Create and edit `filename` in `~/bin` __with Vim__, and make it runnable.
```bash
makebin filename
```
2. ~~Create and edit `filename` in `~/bin` with __`"other editor"`__, and make it runnable.~~(comming soon.)
```bash
makebin filename with nano
````
