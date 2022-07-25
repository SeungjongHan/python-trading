# python-trading
https://wikidocs.net/book/110 따라해보기

### Setup
```sh
mkvirtualenv -p python3.7 python-trading
workon python-trading
```


### Git hooks
commit 할 때, isort, black 실행되도록 설정
```sh
mkdir -p .git/hooks; cp -a scripts/git-hooks/* .git/hooks/
```
