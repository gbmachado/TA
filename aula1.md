---
description: >-
  Atividade prática realizada na aula 2. Ao final da atividade o resultado foi a
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

Para a criação do CV, utilizar o arquivo modelo

{% file src=".gitbook/assets/cv.zip" %}



> Importante! Saber qual a pasta que foi salvo o arquivo index.html e a foto
>
> De preferência criar uma pasta CV no `desktop`

## Subindo CV

Depois de editado o HTML, o\(s\) arquivo\(s\) da página estática a ser publicada devem "subidos". 

Para isso o arquivo HTML deve ser  `index.html`

O comando para publicar o CV é:

```
$ surge -p ./desktop/cv -d gbm.surge.sh
```

Onde -p aponta para o caminho onde está o `index.html`

Onde -d define o subdomínio, no caso `gbm`

## Resumo

Quais as etapas foram realizadas para chegar neste momento



```
Instalar o Surge
Baixar o arquivo zip exemplo
Modificar o arquivo .html (atualizar o curriculo)
Publicar o CV
```

O resultado final pode ser visto em:

[http://gbm.surge.sh/](http://gbm.surge.sh/)

