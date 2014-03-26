git-hooks
=========

# Как начать пользоваться

* Клонировать этот репозиторий
* Скопировать нужный хук в каталог .git/hooks/ вашего репозитория

Например, если нужен pre-commit хук, который бы срабатывал при коммите в репозиторий ~/some-repo, нужно сделать вот так
```
git clone https://github.com/evvers/git-hooks.git ~/git-hooks
cp ~/git-hooks/pre-commit ~/some-repo/.git/hooks/pre-commit
chmod +x ~/some-repo/.git/hooks/pre-commit
```
