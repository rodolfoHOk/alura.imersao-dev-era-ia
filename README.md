# Imersão Engenharia de Software: Dev na Era da IA

> Evento On-line Alura e Google 26/10/2026 - 03/11/2026

## Master Class

### Introdução

Boas-vindas à Masterclass da Imersão de Engenharia de Software com IA! Se você quer entender como a IA generativa está mudando a forma de criar, evoluir e manter sistemas, e como usar ferramentas do ecossistema Google nesse processo, essa aula é para você.

Nesta Masterclass, vamos partir de um cenário prático para acompanhar a transição de assistentes que apenas sugerem código para agentes de IA capazes de trabalhar dentro do ambiente de desenvolvimento. De forma simples e prática, você vai:

- Conhecer o Google AI Studio e usá-lo para prototipar e experimentar ideias com linguagem natural, sem instalar nada
- Criar uma aplicação do zero (uma calculadora em Python) e analisar o que o Gemini gerou
- Explorar o Google Antigravity, plataforma de desenvolvimento com agentes de IA, e como ela se integra ao seu ambiente
- Aplicar boas práticas, como manter o humano no loop, revisar as permissões que o agente solicita e validar os resultados
- Entender por que dominar os fundamentos de arquitetura, testes, segurança e requisitos é o que garante sistemas de qualidade

Ao final desta aula, você terá uma visão mais clara sobre o papel da IA na engenharia de software, conhecerá duas das principais ferramentas do Google para criação de software e estará preparado para aprofundar esses conhecimentos ao longo da Imersão.

Prepare-se para colocar a mão na massa, testar suas primeiras soluções com agentes de IA e dar os primeiros passos no desenvolvimento agêntico. Aproveite a aula!

## Aula 01 - Da ideia ao código: desenvolva com agentes de IA

### Introdução

Chegou a hora de começar a construir com Inteligência Artificial! Você vai conhecer o Google AI Studio e descobrir como sair de uma ideia e chegar a uma aplicação web funcionando em poucos minutos, usando apenas uma conta Google e prompts bem estruturados.

Nesta aula, você vai:

- Explorar o Google AI Studio e seus principais recursos: Playground, System Instructions e Build e Gallery.
- Entender por que especificar bem o que você quer (requisitos, público e escopo) economiza tokens e gera resultados mais assertivos.
- Criar, na prática, o StudyFlow, uma aplicação web para organizar seus objetivos de estudo, com CRUD completo e dados salvos no navegador.
- Aprender a usar prompts em etapas: primeiro estruturar a ideia, depois pedir o código.
- Visualizar e entender o código gerado (React, TypeScript e componentização) e conhecer as opções de publicação e exportação para o GitHub.
- Receber o desafio da aula: criar o seu próprio projeto, compartilhar no LinkedIn e marcar a Alura.

### Resumo da aula com prompts utilizados

[Resumo Aula 01](/summary-lesson1.md)

### Desafio 1: Criando sua primeira aplicação com IA

Agora que você conheceu algumas possibilidades da Inteligência Artificial no desenvolvimento de software, chegou a hora de colocar a mão na massa! O desafio é usar o Google AI Studio para gerar uma calculadora em Python com as quatro operações básicas (adição, subtração, multiplicação e divisão) e entender como a aplicação funciona.

Depois de gerar o código, explore a solução com a ajuda da IA e procure responder:

Quais são os principais componentes do código gerado?

Como a aplicação recebe os números e identifica a operação escolhida?

Como a lógica de programação é utilizada para realizar os cálculos e apresentar os resultados?

Experimente também realizar diferentes operações e observar como a aplicação se comporta.

O objetivo não é dominar Python de imediato, e sim começar a compreender como instruções, variáveis e condições são utilizadas na construção de um software.

💡 Dica para solucionar

Comece descrevendo ao Google AI Studio o que deseja construir:

"Quero criar uma calculadora simples em Python que realize as quatro operações matemáticas básicas. Estou começando a aprender programação, então gere um código simples e organizado, com explicações sobre seus principais componentes."

Depois de gerar a solução, continue conversando com a IA: peça para explicar uma parte do código, identificar as variáveis utilizadas ou mostrar como a aplicação decide qual operação executar.

Mais importante do que gerar o código é entender a lógica por trás dele. Bora lá?

## Aula 2 - Evolua seu software com skills e agentes

### Introdução

Chegou a hora de subir de nível! Depois de dar os primeiros passos com o Google AI Studio, você vai conhecer o Google Antigravity, a ferramenta que leva o desenvolvimento com IA para o dia a dia real de times de engenharia, com mais robustez, eficiência e controle.

Nesta aula, você vai:

- Entender as diferenças entre o Google AI Studio e o Google Antigravity.
- Compreender como a IA transforma o ciclo de vida do software (SDLC), com o código como ativo e o humano como revisor e orquestrador.
- Conhecer as diferentes formas de usar o Antigravity: aplicativo, CLI, IDEs e SDK.
- Configurar o Antigravity CLI no Google Cloud Shell, com login, projeto, modelo e nível de esforço.
- Aprender o método GCCD (Goal, Context, Constraints e Done When) para escrever prompts eficientes e controlar o consumo de tokens.
- Explorar conceitos de Harness, Context Engineering, Skills, MCP e Agents.md, que deixam o desenvolvimento com IA mais eficiente.

### Slides da aula 02

[Slides Aula 02](/slides-lesson2.md)

### Desafio 2: Evoluindo sua primeira aplicação com o Google Antigravity

No primeiro desafio, a IA ajudou a criar uma calculadora em Python. Agora damos um passo adiante: o desafio é usar o Google Antigravity para criar ou importar o projeto da calculadora e modificar a aplicação existente.

Isso envolve três atividades:

Explorar o projeto: peça ao Antigravity para identificar os arquivos e explicar como o código está organizado.

Adicionar uma funcionalidade: solicite a implementação de uma nova operação, como o cálculo de porcentagem.

Testar a aplicação: peça à IA para verificar se a nova funcionalidade funciona corretamente, sem comprometer as operações anteriores.

Depois, execute a aplicação e observe as mudanças feitas no código.

O objetivo é praticar uma atividade comum na Engenharia de Software: compreender um código existente, implementar melhorias e verificar se tudo continua funcionando.

💡 Dica para solucionar

Comece fornecendo contexto ao Google Antigravity:

"Tenho um projeto de calculadora em Python que realiza as quatro operações matemáticas básicas. Estou começando a aprender programação e quero entender como os arquivos e as funções estão organizados. Analise o projeto e explique sua estrutura de maneira simples."

Depois, solicite a melhoria:

"Agora quero adicionar uma funcionalidade para calcular porcentagens. Implemente essa operação mantendo as funcionalidades existentes e explique quais alterações foram realizadas no código."

Por fim, peça ao Antigravity para ajudar a testar a aplicação e verificar os resultados.

Desenvolver software não significa apenas escrever código: envolve compreender, modificar e testar soluções. É hora de seguir se desafiando!

## Aula 3 - Conectando o projeto a um agente de IA

### Introdução

Chegou a hora de colocar a mão na massa! Você vai aplicar o Google Antigravity em um projeto real, desenvolvendo do zero um agente de IA que monta planos de estudo personalizados e gera uma agenda pronta para importar no Google Calendar.

Nesta aula, você vai:

- Estruturar o projeto com o arquivo Agents.md, seguindo a metodologia GCCD, e organizar as skills do seu agente.
- Conhecer o Google ADK (Agent Development Kit), framework open source para criar agentes, e seus recursos como Skills Toolset e Environment Toolset.
- Clonar o repositório no Cloud Shell e usar o Antigravity CLI para desenvolver o agente, incluindo a instalação das skills do Agents CLI.
- Testar o agente na interface do ADK Web, acompanhando eventos, traces e o uso de skills sob demanda.
- Aprender a depurar com a IA, corrigindo erros durante o desenvolvimento e validando soluções.
- Testar a funcionalidade do projeto e validar sua proposta antes de avançar para integrações mais complexas.

### Guia da aula e Código Fonte

[Guia Aula 03](/src/README.md)

[Código Fonte](/src/)

### Desafio 3: Criando uma lista de tarefas com o Google Antigravity

Depois de compreender, modificar e testar códigos, chegou a hora de construir uma nova aplicação! O desafio é usar o Google Antigravity para desenvolver uma lista de tarefas (To-Do List) simples, com interface visual, que permita acompanhar atividades pendentes e concluídas.

A aplicação deve ter três funcionalidades:

Adicionar tarefas: digitar uma atividade e incluí-la na lista.

Marcar tarefas como concluídas: identificar as atividades já realizadas.

Remover tarefas: excluir atividades que não são mais necessárias.

Depois, execute o projeto para experimentar as funcionalidades e observe como a aplicação organiza as informações e como os componentes do código trabalham juntos.

💡 Dica para solucionar

Comece descrevendo ao Google Antigravity o que deseja desenvolver:

"Quero criar uma aplicação simples de lista de tarefas, com uma interface visual que permita adicionar, concluir e remover atividades. Estou começando a aprender desenvolvimento de software, então utilize tecnologias simples e organize o projeto de maneira que eu consiga compreender seus principais componentes."

Depois, experimente solicitar uma melhoria:

"Quero que as tarefas concluídas apareçam visualmente diferentes das pendentes. Implemente essa melhoria e explique quais partes do código precisaram ser modificadas."

Por fim, peça ao Antigravity para executar os testes necessários e verificar se as funcionalidades continuam funcionando.

Compreender o que está sendo desenvolvido e validar os resultados faz parte do trabalho de uma pessoa desenvolvedora. Bora concluir esse último desafio?

## Live de Encerramento: Deploy

[Slides Live de Encerramento](/slides-live.md)

## Links úteis

- [Guia de Mergulho](https://alura.tv/4xOI2Dv)

- [Google AI Studio](https://aistudio.google.com/apps)

- [Google Antigravity](https://antigravity.google/)

- [Guia do Google AI Studio (documentação oficial Google)](https://ai.google.dev/gemini-api/docs/ai-studio-quickstart?hl=pt-br)

- [Blog Google Antigravity](https://antigravity.google/blog/)

- [Documentação oficial Google Antigravity](https://antigravity.google/docs/overview/)

- [Repositório do projeto (original da Alura)](https://github.com/alura-cursos/imersao-dev-ai-google)
