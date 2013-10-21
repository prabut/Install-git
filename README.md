###Install git

```sh
sudo apt-get install git
```
###Configuration of git
```sh
config -l

git config --global user.name "Tomasz Prabucki"

git config --global user.email "tprabucki@sigma.ug.edu.pl"

git config --global core.autocrlf input

cat ~/.gitconfig

[user]
	name = Tomasz Prabucki
	email = tprabucki@sigma.ug.edu.pl
[core]
	autocrlf = input

```
###Some useful alias
```sh
git config --global alias.br "branch -a"

git config --global alias.co "checkout"

git config --global alias.ci "commit"

git config --global alias.lg "log -p"

git config --global alias.lol "log --graph --decorate --pretty=oneline --abbrev-commit"

git config --global alias.lola "log --graph --decorate --pretty=oneline --abbrev-commit --all"

git config --global alias.ls "ls-files"

git config --global alias.st "status"

git config --global alias.df "diff"
```
###Installation of meld
```sh
sudo apt-get install meld
```
###Chceck changes
```sh
git config --global diff.tool meld

git difftool

usage: git diff [--no-index] <path> <path>

```
###Change color of different
```sh
git config --global color.branch auto

git config --global color.diff auto

git config --global color.status auto
```

```sh
git clone git://git.kernel.org/pub/scm/git/git.git

```
```sh
cd git/contrib/completion/
cp git-prompt.sh ~/.git-prompt.sh
cp git-completion.bash ~/.git-completion.sh

```
