---
# Copyright (c) Microsoft Corporation.
# Visual Studio Code, VS Code, and the Visual Studio Code icon are trademarks of
# Microsoft Corporation.
# All rights reserved.
#
# Documentation licensed under the Creative Commons Attribution 3.0 United
# States License.
# The original work was translated from English into Brazilian Portuguese.
# https://github.com/microsoft/vscode-docs/blob/-/LICENSE.md

source_url: https://github.com/microsoft/vscode-docs/blob/main/api/index.md
revision: 9ac43da9f748caec99e0cfdf9bbcd3efdc57353a
status: ready

# DO NOT TOUCH — Managed by doc writer
ContentId: AD26EFB1-FFC6-4284-BAB8-F3BCB8294728
DateApproved: 11/12/2025

# Summarize the whole topic in less than 300 characters for SEO purpose
MetaDescription: >-
  O Visual Studio Code possui uma rica API de Extensão.
  Aprenda como criar suas próprias extensões para o VS Code.
---

# API de Extensão

O Visual Studio Code foi desenvolvido com a extensibilidade em mente.
Da interface da pessoa usuária à experiência de edição, quase todas as partes do
VS Code podem ser personalizadas e aprimoradas por meio da API de Extensão.
Na verdade, muitos recursos principais do VS Code são criados como
[extensões](https://github.com/microsoft/vscode/tree/main/extensions) e usam a
mesma API de Extensão.

Esta documentação descreve:

* Como criar, executar, depurar, testar e publicar uma extensão;
* Como aproveitar a rica API de Extensão do VS Code;
* Onde encontrar
  [guias](https://code.visualstudio.com/api/extension-guides/overview) e
  [exemplos de código](https://github.com/microsoft/vscode-extension-samples)
  para ajudar você a começar;
* Como seguir nossas [diretrizes de UX](/api/ux-guidelines/overview) para as
  melhores práticas.

Exemplos de código estão disponíveis em
[Microsoft/vscode-extension-samples](https://github.com/microsoft/vscode-extension-samples).

Se você procura extensões publicadas, acesse o
[VS Code Extension Marketplace](https://marketplace.visualstudio.com/vscode).

## O que as extensões podem fazer?

Aqui estão alguns exemplos do que você pode fazer com a API de Extensão:

* Alterar a aparência do VS Code com um tema de cores ou ícones de arquivo -
  [Temas](/api/extension-capabilities/theming);
* Adicionar componentes e visualizações personalizados à interface da pessoa
  usuária -
  [Estendendo o Workbench](/api/extension-capabilities/extending-workbench);
* Criar uma WebView para exibir uma página web personalizada criada com
  HTML/CSS/JS - [Guia da WebView](/api/extension-guides/webview);
* Dar suporte a uma nova linguagem de programação -
  [Visão geral das extensões de linguagem](/api/language-extensions/overview);
* Dar suporte à depuração de um ambiente de execução específico -
  [Guia da extensão de depuração](/api/extension-guides/debugger-extension).

Se você quiser uma visão geral mais completa da API de Extensão, consulte a
página
[Visão geral dos recursos de extensão](/api/extension-capabilities/overview).
A [Visão geral dos guias de extensão](/api/extension-guides/overview) também
inclui uma lista de exemplos de código e guias que ilustram vários usos da API
de Extensão.

## Como criar extensões?

Criar uma boa extensão pode exigir muito tempo e esforço.
Veja como cada seção da documentação da API pode te ajudar:

* **Primeiros passos** ensina conceitos fundamentais para criar extensões com o
  exemplo
  [Olá, mundo!](https://github.com/microsoft/vscode-extension-samples/tree/main/helloworld-sample);
* **Recursos de extensão** divide a vasta API do VS Code em categorias menores e
  direciona você para tópicos mais detalhados;
* **Guias de extensão** inclui guias e exemplos de código que explicam usos
  específicos da API de Extensão do VS Code;
* **Diretrizes de UX** apresenta as melhores práticas para proporcionar uma
  ótima experiência de pessoa usuária em uma extensão;
* **Extensões de linguagem** ilustra como adicionar suporte a uma linguagem de
  programação com guias e exemplos de código;
* **Testes e publicação** inclui guias detalhados sobre vários tópicos de
  desenvolvimento de extensões, como
  [testes](/api/working-with-extensions/testing-extension) e
  [publicação](/api/working-with-extensions/publishing-extension);
* **Tópicos avançados** explica conceitos avançados como
  [host de extensão](/api/advanced-topics/extension-host),
  [suporte a desenvolvimento remoto e codespaces do GitHub](/api/advanced-topics/remote-extensions)
  e [APIs propostas](/api/advanced-topics/using-proposed-api);
* **Referências** contém referências completas para a
  [API do VS Code](/api/references/vscode-api),
  [pontos de contribuição](/api/references/contribution-points) e muitos outros
  tópicos.

## Novidades

O VS Code é atualizado mensalmente, e isso também se aplica à API de Extensão.
Novos recursos e APIs são disponibilizados todos os meses para aumentar o poder
e o alcance das extensões do VS Code.

Para acompanhar as atualizações da API de Extensão, você pode consultar as notas
de versão mensais, que contêm seções dedicadas a:

* [Autoria de extensões](https://code.visualstudio.com/updates#_extension-authoring)
  \- Saiba quais novas APIs de extensão estão disponíveis na versão mais
  recente;
* [APIs de extensão propostas](https://code.visualstudio.com/updates#_proposed-extension-apis)
  \- Revise e envie feedback sobre as APIs propostas para os próximos meses.

## Precisa de ajuda?

Se você tiver dúvidas sobre o desenvolvimento de extensões, tente perguntar em:

* [Discussões do VS Code](https://github.com/microsoft/vscode-discussions):
  Comunidade do GitHub para discutir a plataforma de extensões do VS Code, fazer
  perguntas, ajudar outras pessoas da comunidade e obter respostas;
* [Stack Overflow](https://stackoverflow.com/questions/tagged/vscode-extensions):
  Existem [milhares de perguntas](https://stackoverflow.com/questions/tagged/vscode-extensions)
  com a tag `vscode-extensions`, e mais da metade delas já possui respostas.
  Pesquise seu problema, faça perguntas ou ajude outras pessoas desenvolvedoras
  respondendo a perguntas sobre desenvolvimento de extensões do VS Code!
* [VS Code Dev Slack](https://vscode-dev-community.slack.com):
  Sala de bate-papo pública para pessoas desenvolvedoras de extensões.
  Pessoas qu fazem parte da equipe do VS Code frequentemente participam das
  conversas.

Para fornecer feedback sobre a documentação, crie novas issues em
[Microsoft/vscode-docs](https://github.com/microsoft/vscode-docs/issues).
Se você tiver dúvidas sobre extensões para as quais não encontrou resposta, ou
problemas com a API de Extensão do VS Code, abra novas issues em
[Microsoft/vscode](https://github.com/microsoft/vscode/issues).
