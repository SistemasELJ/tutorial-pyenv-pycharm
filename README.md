# TUTORIAL

# PYENV

```console
sudo apt-get install -y make build-essential libssl-dev zlib1g-dev libbz2-dev libreadline-dev libsqlite3-dev wget curl llvm libncurses5-dev git
curl -L https://raw.githubusercontent.com/yyuu/pyenv-installer/master/bin/pyenv-installer | bash
gedit ~/.bashrc
```

COPIE AS ULTIMAS 3 LINHA DO RESULTADO DE "curl -L https://raw.githubusercontent.com/yyuu/pyenv-installer/master/bin/pyenv-installer | bash"

EXEMPLO:

```console
export PATH="/home/º/.pyenv/bin:$PATH"
eval "$(pyenv init -)"
eval "$(pyenv virtualenv-init -)"
```

ATENÇÃO, NO "º" JÁ ESTARÁ SEU NOME DE USUÁRIO!!!

E COLE NO FINAL DE .bashrc

SALVE O ARQUIVO .bashrc E REINICIE O TERMINAL.

```console
pyenv install -l
pyenv install 3.6.2
pyenv global 3.6.2
pyenv versions
```
ATENÇÃO, ATÉ O PRESENTE MOMENTO (18/09/2017), A VERSÃO MAIS RECENTE É A 3.6.2.

# PYCHARM

## JAVA

```console
sudo add-apt-repository ppa:webupd8team/java
sudo apt-get update
echo oracle-java8-installer shared/accepted-oracle-license-v1-1 select true | sudo /usr/bin/debconf-set-selections
sudo apt-get install oracle-java8-installer -y
sudo apt-get install oracle-java8-set-default -y
java -version
```

ATENÇÃO, O RESULTADO DE java -version, DEVE SER PARECIDO AO ABAIXO

```console
java version "1.8.0_144"
Java(TM) SE Runtime Environment (build 1.8.0_144-b01)
Java HotSpot(TM) 64-Bit Server VM (build 25.144-b01, mixed mode)
```

## PYCHARM

FAÇA O DOWNLOAD DO PYCHARM : "https://www.jetbrains.com/pycharm/download/"

```console
sudo tar -C /opt/ -xzf º
```

ATENÇÃO, NO "º", COLOQUE O CAMINHO ONDE ESTÁ BAIXADO O PYCHARM. POR EXEMPLO: sudo tar -C /opt/ -xzf Downloads/pycharm-community-2017.2.3.tar.gz

## COM O COMANDO ABAIXO, VAI INICIAR O PYCHARM.

```console
'/opt/pycharm-community-2017.2.3/bin/pycharm.sh'
```
