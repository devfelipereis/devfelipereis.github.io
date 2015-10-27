---
author: felipe_reis
layout: post
title: WordPress é melhor com Trellis
excerpt: "Um projeto sério merece uma estrutura legal e moderna, esqueça aquela ideia de baixar o zip e jogar na pasta www. Conheça o Trellis e trabalhe de maneira mais profissional."
modified: 2015-10-26
tags: [wordpress, php, blog, site, trellis, workflow, vagrant, deploy, bedrock]
comments: true
image:
  feature: https://make.wordpress.org/design/files/2015/02/logotype-01-standard.png
---

Um projeto sério merece uma estrutura legal e moderna, esqueça aquela ideia de baixar o zip e jogar na pasta WWW. Conheça o Trellis e trabalhe de maneira mais profissional.

## O que é o Trellis?

O Trellis é toda uma stack pensada e desenvolvida para tornar seu trabalho com WordPress melhor e mais produtivo. Chega de baixar aquele zip do WordPress e extrair na pasta WWW. Esqueça também a parte que você envia os arquivos via FTP para o server, todos sabemos como aquilo é lento e do passado. O Trellis está ai para te ajudar e tornar seu trabalho mais simples e melhor.

## O que o Trellis pode te oferecer?

Muitas coisas! Com o Vagrant você "liga" seu ambiente e começa a trabalhar com um moderno ambiente baseado em LEMP. LEMP para  quem não sabe, significa: Linux, Nginx, MySQL, PHP. Como meu objetivo não é explicar tudo aqui, leia mais sobre esta stack [aqui](https://lemp.io/).

Seu ambiente de desenvolvimento será configurado com os seguintes itens:

* Ubuntu 14.04 Trusty LTS
* Nginx (with optional FastCGI micro-caching)
* PHP 5.6 (or HHVM)
* MariaDB as a drop-in MySQL replacement (but better)
* SSL support (A+ on https://www.ssllabs.com/ssltest/)
* Composer
* WP-CLI
* sSMTP (mail delivery)
* Memcached
* Fail2ban
* ferm

Além disso, seu WordPress terá uma estrutura de pastas mais organizada e fácil, graças ao amiguinho [Bedrock](https://github.com/roots/bedrock). Poderá ainda fazer gerenciamento de dependências pelo composer, configurar variaveis de ambiente com [Dotenv](https://github.com/vlucas/phpdotenv), entre outros.

## Esqueça o FTP e faça deploy via SSH

Hora de parar de parar de usar FTP e fazer deploy via SSH. Você irá utilizar a URL git do seu projeto e a branch que deseja utilizar no deploy. Depois disso irá rodar um comando e pronto... sua aplicação estará no servidor com todas as dependicias instaladas e pronta para ser utilizada.
Não gostou do resultado? Faça um rollback que seu servidor voltará a ser como era antes.

## Eu quero!

Deixo abaixo os principais links que você irá precisar para começar a trabalhar com o Trellis.

* [Site do Trellis](https://roots.io/trellis)
* [Github](https://github.com/roots/trellis)
* [Github do amiguinho Bedrock](https://github.com/roots/bedrock)
* [LEMP Stack Info](https://lemp.io)

## Finalizando

Simplificando, o Trellis irá te oferecer tudo que há de moderno e essencial para desenvolver projetos excelentes utilizando WordPress. A configuração inicial não é complicada(mais ou menos, mais ou menos), basta seguir todos os passos no github que sua aplicação estará rodando em minutos. Ainda na documentação, leia tudo! Citei aqui muita coisa boa que o projeto oferece mas no github ainda tem muito mais, confira!

Se você ficou meio perdido e não entendeu muita coisa, de uma pesquisada que vale muito a pena. Abraços!
