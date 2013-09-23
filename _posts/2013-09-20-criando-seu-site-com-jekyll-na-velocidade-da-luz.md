---
layout: post
title: Criando seu site com Jekyll na velocidade da Luz
---

Quando conheci o [André](http://andreczip.github.io/ "@andreczip"), começamos a trocar experiências profissionais. Foi aí então que ele começou a me falar sobre o [Jekyll](http://jekyllrb.com/). Segundo ele, um gerador de páginas estáticas.

Naquele tempo, não consegui dar atenção e começar a brincar com ele. Mas já estava pensando em começar a montar meu próprio site para postar minhas experiências e projetos. Utilizo muito o Wordpress como CMS. Acho ele uma excelente ferramenta para gestão de contéúdo. Mas queria algo mais simples.

Então foi aí que me lembrei do que o André havia me dito e parti de cara estudar esse tal de Jekyll. E não me arrependi. Em poucas horas estava com o meu site rodando nos servidores do GitHub. E o mais bacana é que qualquer pessoa pode me mandar uma correção tanto de layout, quanto de conteúdo através de um pull request. Fantástico não? 

Existe uma página no Github Help que ensina como usar o Jekyll com o GitHub Pages. O tutorial foi um pouco confuso para mim. Como não sou usuário de [Ruby](https://www.ruby-lang.org/), sofri para entender a parte da instalação. Mas no fim vi que é muito simples.

## Instalando o Jekyll

O GitHub possui um pacote [gem](http://rubygems.org/) que ajuda na instalação das dependências necessárias para iniciar um projeto com Jekyll. Para isso é necessário criar um arquivo `Gemfile`.

	$ touch Gemfile

O conteúdo do arquivo deve ser o seguinte:

	source 'https://rubygems.org'
	gem 'github-pages'

Para poder executar o arquivo `Gemfile` é preciso intalar um outro pacote gem, o [Bundler](http://bundler.io/). E depois é só executar o comando para instalar as dependências.

	# gem install bundler
	# bundle install

Para visualizar o site é só executar o comando abaixo. O site será servido no endereço `http://localhost:4000`.

	$ jekyll serve

Pronto. Agora é só começar a usar a sua criatividade e criar sua página.

### Dica

Existe um bootstrap excelente para Jekyll, o [Jekyllbootstrap](http://jekyllbootstrap.com). Assim não temos que começar o projeto do zero.
