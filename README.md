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

## Links úteis

- [Guia de Mergulho](https://alura.tv/4xOI2Dv)

- [Google AI Studio](https://aistudio.google.com/apps)

- [Google Antigravity](https://antigravity.google/)

- [Guia do Google AI Studio (documentação oficial Google)](https://ai.google.dev/gemini-api/docs/ai-studio-quickstart?hl=pt-br)

- [Blog Google Antigravity](https://antigravity.google/blog/)

- [Documentação oficial Google Antigravity](https://antigravity.google/docs/overview/)

- [Repositório do projeto (original da Alura)](https://github.com/alura-cursos/imersao-dev-ai-google)
