python-env
====

GitPodを利用して、chrome上で動作するpythonのプログラミング環境（IDEとjupyterlab）を構築します。  
ユースケースとしては、ipadを利用した開発を想定しています。  

## Description
* gitpod.Dockerfile - GitPod上で利用するdockerファイル。  
* gitpod.yml - GitPodの設定ファイル。  
* Pipfile - jupyterlabを立ち上げるためのpipfile。pipenvで仮想環境を構築していることを想定  

## Usage
1. GitPodへアクセス  
chromeで以下のURLにアクセスします。  
`https://gitpod.io/#github.com/sp8783/python_env`

2. jupyterlabを立ち上げる  
以下のコマンドを叩く。  

```
$ pipenv install  
$ pipenv shell  
(python-env)$ jupyter lab
```

## References
https://qiita.com/gsy0911/items/dbb64871480cf1a06acf
