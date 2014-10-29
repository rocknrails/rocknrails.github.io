---
published: true
title: Instalando o Ruby on Rails
layout: post
---
<center>
<img src="http://itekblog.com/wp-content/uploads/2012/07/railslogo.png" width="50%"/>
</center>

***Existem varias implementações de Ruby, como [JRuby](http://jruby.org/) e [Rubinius](http://rubini.us), mas vamos usar a versão MRI, ou Matz Ruby Interpreter, a implementação canônica de Ruby, criada pelo proprio Matz.***


>Instalação no OSX

Para quem está iniciando com Ruby on Rails, a forma mais simples é usar o RVM,
ou Ruby enVironment Manager. </br>Antes de instalar o RVM, porém, é necessário ins-
talar os pacotes de desenvolvimento da Apple.
Se você não tem o Xcode, vá na página do [Apple Developer Tools](https://
developer.apple.com/downloads/index.action) e baixe o ‘Command Line Tools for Xcode’.

Se tiver o Xcode mais recente, você pode abri-lo, ir nas Preferências > Downloads e instalar o ‘Command
Line Tools’.
Depois de instalar o Command Line Tools, basta executar o seguinte comando
no terminal:
<code>
curl -L get.rvm.io | bash -s stable --rails
source $HOME/.rvm/scripts/rvm
</code>
***Aproveite e vá tomar um café, vai demorar um pouco. Ao finalizar, este comando
deixará instalado tudo que você precisa para começar a desenvolver com Ruby on
Rails.***

>Instalação no Linux

Tanto quanto usuários OSX, a forma mais simples de começar com Ruby on Rails
no Linux é usar o RVM, ou Ruby enVironment Manager.
Primeiramente é necessário instalar os pacotes de desenvolvimento do seu sis-
tema. Procure o manual da sua distribuição para saber como instalar. No Ubuntu,
por exemplo, basta instalar o pacote build-essential e mais algumas outras bibli-
otecas de dependências:

<code>
sudo apt-get install build-essential libreadline-dev libssl-dev curl \
libsqlite3-dev
</code>
Em seguida, basta executar:
<code>
curl -L get.rvm.io | bash -s stable --rails
source $HOME/.rvm/scripts/rvm
</code>
Este comando irá instalar o RVM e também, automaticamente, irá instalar a ver-
são mais atual do Ruby e do Rails e todas as dependências.

E como de praxe vá tomar um café ou um chá, pois demora um pouco.

>Windows

Para instalar o ambiente de Ruby e Rails no Windows, o jeito mais fácil é usar o [RailsInstaller](http://www.railsinstaller.org), que já instala o Ruby versão MRI e todas as dependências do Rails. 

Para instalar o ambiente, basta baixar o instalador e seguir as instruções apresentadas com o famoso NEXT, NEXT e vá na fé que não tem nenhum ***Daibu ou cal321***

<center>
<img src="http://1.bp.blogspot.com/-OSA6iaVsmcU/Un4c88ZQUJI/AAAAAAAABSY/XoTx4FohUlY/s1600/images%5B5%5D.jpg" width="50%"/>
*** =) ***
</center>

