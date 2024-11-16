---
title: Instruções online hospedadas
permalink: index.html
layout: home
---

# MS-4008: Experiência interativa do Microsoft 365 Copilot para executivos 

## Diretório de conteúdo

As demonstrações deste curso são baseadas nas demonstrações do kit acelerador [Demo Guide and Talking Points.docx](https://microsoft.seismic.com/Link/Content/DCJC9CXBThjcFGfJjJXMQ2jXqfCG).

É importante que você se familiarize com as demonstrações antes de ministrar este treinamento. Para vários laboratórios, você utilizará documentos de exemplo e reuniões e emails pré-criados do Teams.

- Faça o pré-download de todos os documentos de amostra [aqui](https://github.com/MicrosoftLearning/MS-4008-Microsoft-365-Copilot-Interactive-Experience-for-Executives/tree/master/ResourceFiles).
- Configure reuniões do Teams e threads de email seguindo as instruções [aqui](https://microsoft.seismic.com/Link/Content/DCFPQWmT2DMXC8WJjgjP4H44GWXG).
- Familiarize-se com as experiência interativas:
    - Opção 1: [aka.ms/CopilotEE](https://aka.ms/CopilotEE)
    - Opção 2: [aka.ms/TeamsEE](https://aka.ms/TeamsEE)

    > **OBSERVAÇÃO:** se os participantes não tiverem uma licença do Microsoft 365 Copilot, eles poderão utilizar a versão comercial gratuita da experiência encontrada em [aka.ms/CopilotWebEE](https://aka.ms/CopilotWebEE).

## Descrição do curso

Descubra como o Microsoft 365 Copilot eleva a produtividade e a inovação no local de trabalho. Essa experiência, adaptada para o líder de negócios moderno, fornece insights sobre a criação de prompts contextuais para Copilot e inclui exercícios de caso de uso envolventes que mostram a integração perfeita em fluxos de trabalho diários.

Os principais objetivos para esta entrega são:

- Apresente os participantes ao Microsoft 365 Copilot e ensine-os a criar um prompt eficaz
- Demonstre o Microsoft 365 Copilot em aplicativos do Office (até três demonstrações)
- Guie os participantes em uma experiência interativa
- Convide os participantes a baixar e experimentar o Microsoft Copilot para dispositivos móveis

## Tempo do curso (estimativa) 

| # | Tópico                                 | Tempo Total      |
|---|---------------------------------------|-----------------|
| 1 | Introdução ao Microsoft 365 Copilot | 10 minutos    |
| 2 | Guia de um executivo para criar prompts eficazes | 30 minutos      |
| 3 | Experiência interativa do Microsoft 365 Copilot  | 20 minutos      |
|   |                                       | **Tempo total: 60 minutos** |


Hiperlinks para cada uma das demonstrações estão listados abaixo.

## Demonstrações

{% assign demos = site.pages | where_exp:"page", "page.url contains '/Instructions/Demos'" %}
| Demonstração |
| --- |
{% for activity in demos  %}| [{{ activity.demo.title }}]({{ site.github.url }}{{ activity.url }}) |
{% endfor %}
