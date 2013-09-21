---
layout: post
title: Criando seu site com Jekyll na velocidade da Luz
---

Quando conheci o [André](http://andreczip.github.io/ "@andreczip"), começamos a trocar experiências profissionais. Foi aí então que ele começou a me falar sobre o Jekyll. Segundo ele, um gerador de páginas estáticas.

Naquele tempo, não consegui dar atenção e começar a brincar com ele. Mas já estava pensando em começar a montar meu próprio site para postar minhas experiências e projetos. Utilizo muito o Wordpress como CMS. Acho ele uma excelente ferramenta para gestão de contéúdo. Mas queria algo mais simples.

Então foi aí que me lembrei do que o André havia me dito e parti de cara estudar esse tal de Jekyll. E não me arrependi. Em poucas horas estava com o meu site rodando nos servidores do GitHub. Fantástico não?

O mais bacana é que não precisei conectar nenhum FTP. Foi só baixar os pacotes do Ruby via `apt-get` e instalar o Jekyll pelo `gem`. Depois disso, dei uma pesquisadas em boilerplates e encontrei o [Jekyllbootstrap](http://jekyllbootstrap.com), que quebra um baita. Juntei com o [Initializr](http://www.initializr.com/). Ajustei alguma coisa no `_config.yml`. Dei um `git push` e pronto meu site estava no ar.

Para escrever os posts utilizo o [Markdown](http://daringfireball.net/projects/markdown/). Uma liguagem de marcação simples, que também é utilizada para gerar as páginas de documentação no GitHub, ou seja, nada de novo.