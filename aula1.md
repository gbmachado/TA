---
description: >-
  Atividade prática realizada na aula 1. Ao final da atividade o resultado foi a
  publicação de um CV em uma plataforma para sites estáticos.
---

# Disponibilizando o CV via Surge

## Surge

O Surge é uma ferramenta para "static web publishing for Front-End Developers, right from the CLI".

Para instalá-lo:

```
$ npm install --global surge
```

> Para saber mais sobre o surge, acesse este link:
>
> ​[https://medium.com/trainingcenter/subindo-seu-projeto-front-surge-52d47cf31e0b](https://medium.com/trainingcenter/subindo-seu-projeto-front-surge-52d47cf31e0b)​

## Criando um CV

Para a criação do CV, duas formas foram trabalhadas

1. Ferramenta Visual
2. Edição no Overleaf \(latex\)

A ferramenta visual apresentada foi a Enhancv:

[https://app.enhancv.com/resume/new](https://app.enhancv.com/resume/new)

O editor latex Overleaf:

[https://www.overleaf.com/](https://www.overleaf.com/)

Para a prática foi criado um novo projeto no overleaf, importando o exemplo do seguinte repositório:

[https://github.com/gbmachado/CV](https://github.com/gbmachado/CV)

Guia para os ícones do fontawesome:

[http://www.ipgp.fr/~moguilny/LaTeX/fontawesome5Icons.pdf](http://www.ipgp.fr/~moguilny/LaTeX/fontawesome5Icons.pdf)

## Convertendo o CV

Ao utilizar o overleaf foi possível gerar um PDF do CV, porém o Surge trabalha com arquivos HTML

Foi utilizada a seguinte ferramenta para conversão:

[https://convertio.co/pt/conversor-pdf/](https://convertio.co/pt/conversor-pdf/)

> Importante! Saber qual a pasta que foi salvo o arquivo PDF
>
> De preferência criar uma pasta CV no `desktop`

## Subindo CV

Depois de convertido o PDF em HTML, o\(s\) arquivo\(s\) da página estática a ser publicada devem "subidos". 

Para isso o arquivo HTML deve ser renomeado para `index.html`

O comando para publicar o CV é:

```
$ surge -p ./desktop/cv -d cv_gbm.surge.sh
```

Onde -p aponta para o caminho onde está o `index.html`

Onde -d define o subdomínio, no caso `cv_gbm`

## Resumo

Quais as etapas foram realizadas para chegar neste momento



```
Instalar o Surge
Criar conta no overleaf
Subir arquivo zip baixado do repositório exemplo
Modificar o arquivo .tex (atualizar o curriculo)
Baixar PDF
Converter PDF em HTML
Publicar o CV
```

O resultado final pode ser visto em:

[http://gbm.surge.sh/](http://gbm.surge.sh/)

