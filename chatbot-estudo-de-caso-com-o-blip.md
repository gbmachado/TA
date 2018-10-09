---
description: Apresentação de uma plataforma para criação de Bot conversacional.
---

# Chatbot: Estudo de caso com o BLiP

## Cadastro

Realizar cadastro 

[https://blip.ai/](https://blip.ai/)

* Mail de ativação
* Pode colocar um telefone fixo

## Prática

Criar chatbot de tempo \(entrega informações climáticas baseadas na localização do usuário\)

Fonte:

[https://www.youtube.com/watch?time\_continue=63&v=tEhJBumWPkc](https://www.youtube.com/watch?time_continue=63&v=tEhJBumWPkc)

### 1 - Cadastro na Dark Sky

[https://darksky.net/dev](https://darksky.net/dev)

Conta para acesso a API e receber a key

#### Forecast Request

```text
https://api.darksky.net/forecast/[key]/[latitude],[longitude]
```

### 2 - Criando o bot no blip

![Resultado Final](.gitbook/assets/captura-de-tela-2018-08-16-a-s-20.20.29.png)

## Para saber mais

{% embed url="https://medium.com/@ravpacheco/dentre-tantas-plataformas-por-que-o-blip-4228980dea43" %}

## Resumo

Quais as etapas foram realizadas para chegar neste momento



```
Cadastro no blip.ai
Cadastro na dark sky
Utilizar no bot a key gerada na dark sky
"Programar" o comportamento do bot
Publicar o bot
Testar o bot
```

O resultado final pode ser visto em:

{% file src=".gitbook/assets/climabot.json" %}

