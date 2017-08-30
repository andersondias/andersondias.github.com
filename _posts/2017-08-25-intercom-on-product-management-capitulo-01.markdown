---
layout: post
title: 'Intercom on Product Management: Evaluate your product'
tags: livro
categories: resumos-de-livros
related_content: 2017-08-24-intercom-on-product-management.html
previous_page:
 url: /resumos-de-livros/intercom-on-product-management-introducao
 text: Introdução
next_page:
 url: /resumos-de-livros/intercom-on-product-management-capitulo-02
 text: When to say no to new features
---

O primeiro capítulo do livro é dedicado à avaliação do produto. A partir do pressuposto que você já tem um produto rodado em produção, os autores levantam questionamentos e indicam caminhos para entender o estado atual do seu produto.

## O que as pessoas estão fazendo em seu produto?

Antes de tudo é importante ter uma visão muito clara de como seu produto está sendo utilizado:

> "Quando estiver planejando seu roadmap, e onde seu time irá gastar seu tempo, é útil responder 'quantas pessoas estão atualmente usando cada uma das features do meu produto?'" (p. 7)

Claro que não estamos falando de cada feature do sistema, mas somente as relevantes. Por isto, devemos excluir features como criação de contas, esqueci minha senha e etc.

Com os dados em mãos podemos expô-los da seguinte forma:

> "Uma forma simples de visualizar a utilização de uma feature é imprimir todas elas em dois eixos: quantas pessoas usam a feature, e com que frequência." (p. 7)

![Um levantamento das features típico](/images/intercom-on-product-management/capitulo-1-the-typical-feature-audit.png "Um levantamento das features típico")

É no canto superior direito que está o núcleo do seu negócio. Já as features do campo superior esquerdo tiveram baixa adoção.

Algumas vezes pensamos que todas as novas funções que adicionamos ao nosso produto terão a mesma utilização, o que é um tremendo engano. Podem existir diversos perfis de uso, especialmente em produtos com múltiplos níveis de acesso.

Além disto, à medida que evoluímos nosso software, acabamos dando atenção diferenciada para cada lançamento. Isto pode levar a ter um gráfico com mais ou menos funções no lado esquerdo.

Como você promove, documenta e lembra seus usuários vai levar à diferentes níveis de adoção.

Com este mapa em mente você pode começar a discutir o que pode ser feito para melhorar seu produto.

### Nota sobre disrupção

Um ponto interessante que é levantado: se você tem 10 features e uma delas é muito mais utilizada (digamos 10x mais) que todas as outras, provavelmente seu produto está fora de foco e você está sujeito à aparecer um novo competidor que faz somente aquela feature com mais cuidado.

Isso é bastante plausível, se você pôs muito esforço em todas as outras features e elas não são nem um pouco utilizadas.

### O que fazer com esta análise?

São propostas 4 possíveis ações para o caso de você ter uma parte do seu produto que é pouco utilizada:

* **Remova-a**: admita derrota, e comece a remove-la do seu produto;
* **Aumenta a taxa de adoção**: leve mais pessoas à utilizarem;
* **Aumente frequência**: leve as pessoas à utilizarem mais vezes;
* **Deliberadamente a melhore**: torne-a quantificamente melhor para aqueles que a usam.

### Removendo uma feature

Infelizmente, o livro não explora esta primeira opção em mais profundidade. Eu creio que de todas as propostas, este é a mais traumática dos seguintes pontos de vista:

1. Os desenvolvedores envolvidos podem se sentir traídos, ou que perderam tempo;
2. Os gestores podem sentir que falharam e desanimar;
3. Os poucos clientes que estão utilizando a feature podem se sentir traídos.

De toda forma, uma feature pouco útil pro projeto pode deixa-lo mais pesado. Existe a necessidade de manutenção de código, base de dados, suporte ao cliente e outros procedimentos que de alguma forma são impactados.

Logo, cabe ao Product Manager ter em mente todos estes fatores na hora de decidir matar uma funcionalidade, e mais importante, quando fazê-lo.

O fato é: qualquer trauma ocasionado pela remoção deve ser tratado com comunicação clara e aberta com todos aqueles que estão envolvidos.

### Melhorias de adoção

Deve ser adotada quando:

> "existe uma função importante que uma boa parcela de seus usuários a adotaram, e que você percebe que algumas integrações óbvias ou mudanças que tornaram mais fácil novos usuários aderirem." (p. 16)

Seu objetivo aqui deve ser descobrir a razão da baixa adesão nesta funcionalidade do seu produto. O que está bloqueando os usuários de começarem a utilizar essa parte do seu projeto?

Uma técnica indicada no livro, que eu já utilizo bastante nas minhas análises de causa, é a técnica dos cinco porques. Consiste em você aprofundar no entendimento da causa raiz de um problema atráves de multiplas buscas da razão que o originou.

Exemplo: a maioria dos usuários não utilizam nosso relatório de venda e nós sabemos que ele é muito útil.

Por que eles não utilizam? Porque não tem valor para eles.
Por que não tem valor para eles? Porque os dados são irrelevantes para eles.
Por que são irrelevantes? Porque a maioria eles usam excel e não exportamos para excel.
Por que não exportamos para excel? Porque na época utilizavamos Numbers nos nossos Macs.

E por aí vai. Em geral, no terceiro ou quarto porque você já terá encontrado a melhoria que você deve aplicar.

> **Busque descobrir em entrevistas com uma parcela de usuários que não adotaram a feature, o porque de eles ainda não a estarem utilizando.**

Outro ponto importante citado é que nem sempre tem a ver com uma mudança interna da ferramenta, mas com uma mudança em como ela está sendo anunciada ou explicada.

> **As vezes os usuários ainda não têm visibilidade das capacidades do seu produto. Isso pode ser uma questão de marketing ou de UX, cabe a você descobrir a melhor solução.**

### Melhorias de frequência

É definida pelos autores como uma melhoria quando:

> "existe uma função que a maioria dos seus clientes usam raramente, e você crê que usa-la mais pode ser benefiniciente." (p. 15)

Em geral você vai querer aumentar a frequência de uso nas partes do seu produto que geram mais valor para o seu negócio.

Um exemplo disto no Enjoei é o "Frete Suavizator". Frete no Brasil é muito caro, especialmente com os Correios e pode se tornar um fator impeditivo de fechar compras num site de produtos usados como o Enjoei.

Esta feature permite que o Enjoei e o vendedor assumam parte do custeio do frete, para facilitar a venda. Se por algum motivo for identificada uma forma de aumentar a visibilidade desta feature para o vendedor, isso pode convergir em ativação, que por sua vez pode aumentar o número de transações efetivadas no site.

Agora, existe um efeito colateral nesta melhoria: a empresa esta diminuindo sua margem de lucro. Logo, o mais interessante é encontrar melhorias de frequência que tenham basto custo e alta recompensa.

> **Busque aumentar a frequência de uso nas features que são de maior interesse para seu cliente e que te permitam aumentar lucratividade do seu produto.**

Também é citado o padrão identificado por [Nir Eyal](https://www.nirandfar.com), autor de Hooked, que demonstra que hábitos são formados por um padrão repetitivo composto de 4 elementos:

![The Hook Canvas](/images/intercom-on-product-management/capitulo-1-the-hook-canvas.png "The Hook Canvas")

* **Trigger:** a razão de um usuário ir ao seu produto;
* **Action:** o usuário age em antecipação à recompensa proposta;
* **Reward:** o prêmio que o usuário recebe por ter tomado uma ação;
* **Investment:** investimento que o usuário faz que irá gerar novas triggers.

Vamos analisar o padrão para a feature de endorsements do LinkedIn:

* **Trigger:** você recebe um email dizendo que um contato endorsou você em uma habilidade;

* **Action:** você clica no link do email para ver em que foi endorsado;

* **Reward:** ver um resumo de as suas novas qualificações mostrando como você "é o cara";

* **Investment:** links rápidos para que você possa endorsar seus contatos em suas habilidades.

Este é o componente de vício que você planta em seu produto.

> **Pergunte-se sempre: como eu posso fazer os usuários usarem cada vez mais a minha aplicação? Como eu posso lucrar com isto?**

### Melhoria deliberada

É uma melhoria que deve ser usada quando:

> "Existe uma função que todos os seus clientes usam e gostam, e você vê uma oportunidade de adicionar valor significante a mesma." (p. 12)

São os casos de melhorar a usabilidade ou experiência dos usuários em algo que eles já usam diariamente, ou tornar um fluxo mais rápido.

Porém há um ponto muito importante de ressaltar: mudanças deste tipo são de alto risco e podem ter uma recompensa alta.

> **Mude um fluxo importante para melhor e seus clientes vão te amar, faça isso errado e você vai prejudicar muito seu produto.**

## Melhorias contínuas

Em suma:

> "O desafio do PM têm dois lados: primeiramente, é encontrar melhorias que irão beneficiar o negócio e seus clientes; e em segundo lugar, garantir que estas melhorias não se perderão num quadro-branco qualquer, e que elas de fato serão lançadas." (p. 17)

- - -

No próximo capítulo iremos falar sobre quando devemos negar novas funcionalidades.
