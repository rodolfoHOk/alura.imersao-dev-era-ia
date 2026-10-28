# Resumo da Aula 01

Na primeira aula da Imersão Engenharia de Software com IA: Dev na Era da IA, exploramos como a Inteligência Artificial pode apoiar as primeiras etapas do desenvolvimento de software, desde a concepção de uma ideia até a construção de uma aplicação funcional.

Utilizamos o Google AI Studio para experimentar diferentes formas de interação com modelos de IA, começando pela geração de ideias no Playground e avançando para a criação de uma aplicação web com o recurso New App.

O que desenvolvemos?

Durante a aula, criamos o StudyFlow, uma aplicação web para ajudar estudantes a organizar seus objetivos de estudo.

A aplicação permite cadastrar, visualizar, editar e excluir objetivos, além de armazenar as informações localmente para que os dados sejam preservados após a atualização da página.

Ao longo do processo, trabalhamos com três prompts, cada um representando uma etapa do desenvolvimento.

## Prompt 1: Explorando ideias com IA

Começamos pelo Playground do Google AI Studio, utilizando um prompt simples para explorar como a IA pode apoiar a geração de ideias.

Prompt utilizado:

```text
Dê uma ideia de aplicativo para ajudar pessoas a estudar.
Essa primeira interação nos permitiu observar como a IA interpreta uma solicitação em linguagem natural e propõe possíveis soluções.
```

## Prompt 2: Definindo os requisitos da aplicação

Na sequência, acessamos o recurso New App para estruturar a ideia do StudyFlow antes de começar a implementação.

Prompt utilizado:

```text
Você é uma pessoa especialista em produtos digitais educacionais.

Queremos criar o StudyFlow, uma aplicação simples para ajudar estudantes iniciantes a organizar objetivos de estudo.

A primeira versão deve permitir que a pessoa:
• cadastre um objetivo de estudo;
• visualize os objetivos cadastrados;
• edite um objetivo;
• exclua um objetivo;
• mantenha seus dados após atualizar a página.

Para cada objetivo, considere:
• título;
• descrição;
• prazo;
• status.

Organize a resposta em: 1. problema que o aplicativo resolve; 2. público principal; 3. requisitos funcionais; 4. critérios que podemos utilizar para testar a primeira versão.

Não escreva código ainda.
```

Nesta etapa, utilizamos a IA para transformar uma ideia em requisitos mais claros, identificando as funcionalidades esperadas e os critérios necessários para validar a aplicação.

### Prompt 3: Construindo o StudyFlow

Com os requisitos definidos, avançamos para a implementação da aplicação web utilizando o Google AI Studio.

Prompt utilizado:

```text
Crie uma aplicação web chamada StudyFlow para organizar objetivos de estudo.

Público:

Estudantes iniciantes que precisam organizar o que desejam aprender.

A aplicação deve permitir:
• cadastrar um objetivo com título, descrição, prazo e status;
• listar os objetivos cadastrados;
• editar um objetivo;
• excluir um objetivo somente após uma confirmação;
• exibir a quantidade de objetivos cadastrados;
• salvar os dados no localStorage para que permaneçam após a atualização da página.

Requisitos de interface:
• visual simples, acolhedor e organizado;
• formulário fácil de entender;
• cartões para apresentar os objetivos;
• mensagens quando não houver objetivos;
• interface responsiva;
• textos em português do Brasil.

Requisitos técnicos:
• usar TypeScript;
• separar a interface em componentes;
• separar os tipos de dados;
• criar um serviço para o armazenamento;
• não utilizar backend nesta primeira versão.

Antes de finalizar, confira se todos os requisitos foram implementados.
```

Nesta etapa, exploramos como a IA pode transformar requisitos descritos em linguagem natural em uma aplicação, organizando componentes, estruturas de dados e funcionalidades.
