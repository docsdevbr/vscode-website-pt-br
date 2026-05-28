---
# SPDX-FileCopyrightText: Microsoft Corporation.
# Visual Studio Code, VS Code, and the Visual Studio Code icon are trademarks of
# Microsoft Corporation.
# All rights reserved.
#
# SPDX-License-Identifier: CC-BY-3.0-US
# Documentation licensed under the Creative Commons Attribution 3.0 United
# States License.
# The original work was translated from English into Brazilian Portuguese.
# https://github.com/docsdevbr/vscode-website-pt-br/blob/-/LICENSES/CC-BY-3.0-US.txt

source_url: https://github.com/microsoft/vscode-docs/blob/main/docs/copilot/overview.md
source_revision: b9731d7cf3dc3b478e3870682da6e96b034d7393
translation_status: ready

ContentId: 0aefcb70-7884-487f-953e-46c3e07f7cbe
DateApproved: 5/28/2026
MetaDescription: >-
  Descreva o que você deseja construir e permita que agentes no VS Code
  planejem, implementem e verifiquem as alterações em todo o seu projeto.
MetaSocialImage: images/shared/github-copilot-social.png
Keywords:
  - GitHub Copilot
  - AI
  - agentes
  - autônomo
  - agêntico
  - edição de múltiplos arquivos
  - arquitetura
  - refatoração
  - busca semântica
  - compreensão do código-fonte
  - corporativo
  - sugestões em linha
  - chat
  - MCP
  - time
  - visão geral
  - primeiros passos
---

# GitHub Copilot no VS Code

O GitHub Copilot traz agentes de IA para o Visual Studio Code.
Descreva o que você deseja criar e um agente planeja a abordagem, escreve o
código e verifica o resultado em todo o seu projeto.
Escolha entre os agentes integrados do Copilot, agentes de terceiros de
fornecedores como Anthropic e OpenAI ou seus próprios agentes personalizados e
execute-os localmente, em segundo plano ou na nuvem.
Para alterações mais específicas, sugestões em linha e bate-papo oferecem
controle preciso diretamente no editor.

<div class="docs-action" data-show-in-doc="false" data-show-in-sidebar="true" title="Comece a usar IA">
Siga um tutorial prático para criar sua primeira aplicação com IA no VS Code.

* [Inicie o tutorial](/docs/copilot/getting-started.md)

</div>

## Agentes

Um agente é um assistente de IA que trabalha de forma autônoma para concluir uma
tarefa de programação.
Ao contrário da complementação de código tradicional, que sugere as próximas
linhas, um agente recebe um objetivo, divide-o em etapas, edita arquivos em todo
o seu projeto, executa comandos e se autocorrige quando algo dá errado.

Forneça ao agente uma descrição geral do que você deseja construir e ele
começará a trabalhar.
Cada tarefa é executada em uma **sessão de agente**, uma conversa persistente
que você pode acompanhar, pausar, retomar ou transferir para outro agente.

<video src="images/overview/agents-intro.mp4" title="Vídeo mostrando uma sessão de agente construindo um recurso completo no VS Code." controls muted></video>

O VS Code permite que você trabalhe com agentes da maneira que melhor se adapta
ao seu fluxo de trabalho, com duas interfaces que você pode escolher e alternar
livremente:

* **Janela Editor**: permaneça na janela principal do VS Code quando estiver
  escrevendo código e quiser que a IA auxilie com o editor, o depurador e as
  extensões.
* **[Janela Agents](/docs/copilot/agents/agents-window.md) (Preview)**: alterne
  para uma interface focada em agentes quando quiser pensar em prompts e
  orquestrar sessões de agentes em vários projetos.

> [!IMPORTANT]
>
> Sua organização pode ter desativado os agentes no VS Code.
> Entre em contato com a pessoa administradora para ativar essa funcionalidade.

### Planeje antes de construir

Use o agente **Plan** integrado para dividir uma tarefa em um plano de
implementação estruturado antes de escrever qualquer código.
O agente Plan analisa sua base de código, faz perguntas para esclarecer dúvidas
e gera um plano passo a passo.
Quando o plano estiver correto, entregue-o a um agente de implementação para
executá-lo localmente, em segundo plano ou na nuvem.

<video src="images/overview/plan-intro.mp4" title="Vídeo mostrando o agente Plan criando um plano de implementação estruturado para adicionar autenticação à aplicação." controls muted></video>

Saiba mais sobre [planejamento com agentes](/docs/copilot/agents/planning.md).

### Execute agentes em qualquer lugar

Os agentes são executados onde o trabalho precisa ser feito.
Execute-os localmente no VS Code para trabalho interativo, em segundo plano para
tarefas autônomas ou na nuvem para colaboração em equipe por meio de pull
requests.
Você também pode usar agentes de terceiros de provedores como Anthropic e
OpenAI.
A qualquer momento, transfira uma tarefa de um tipo de agente para outro e o
contexto relevante será mantido.

![Captura de tela mostrando o seletor de tipo de sessão na visualização Chat com opções para agentes locais, em segundo plano, na nuvem e de terceiros.](images/agents-overview/sessions-type-picker.png)

Saiba mais sobre
[tipos de agentes e delegação](/docs/copilot/agents/overview.md)
ou siga o [tutorial de agentes](/docs/copilot/agents/agents-tutorial.md).

### Gerencie sessões a partir de uma visão centralizada

Execute várias sessões de agentes em paralelo, cada uma focada em uma tarefa
diferente.
A visualização **Sessions** no painel **Chat** oferece um local centralizado
para monitorar todas as sessões ativas, sejam elas executadas localmente, em
segundo plano ou na nuvem.
Veja o status de cada sessão, alterne entre elas, revise as alterações nos
arquivos e retome de onde parou.

<video src="images/overview/agent-sessions-demo.mp4" title="Vídeo mostrando a lista de sessões de agentes, demonstrando como filtrar, exibir e arquivar sessões." controls muted></video>

Saiba mais sobre
[gerenciamento de sessões de agentes](/docs/copilot/chat/chat-sessions.md).

### Janela Agents (Preview)

O VS Code permite que você trabalhe com agentes da maneira que melhor se adapta
ao seu fluxo de trabalho, com duas áreas principais que você pode escolher e
alternar livremente:

* **Janela Editor**: permaneça na janela principal do VS Code quando estiver
  escrevendo código e quiser que a IA auxilie com o editor, o depurador e as
  extensões.
* **[Janela Agents](/docs/copilot/agents/agents-window.md) (Preview)**: alterne
  para uma área focada em agentes quando quiser pensar em prompts e orquestrar
  sessões de agentes em vários projetos, com um painel Changes para revisar
  edições e acesso direto às suas personalizações de IA (agentes, habilidades,
  instruções, hooks, servidores MCP) a partir de um único painel lateral.

Ambas as áreas compartilham sessões de agentes e configurações do VS Code (como
configurações e atalhos de teclado), tornando as transições suaves.
Abra a Janela Agents com o botão **Open in Agents** na barra de título.
Você também pode conectar a janela Agentes a uma máquina remota via SSH ou um
túnel de desenvolvimento e
[monitorar sessões a partir de um navegador](https://insiders.vscode.dev/agents)
em qualquer dispositivo.
Saiba mais sobre
[sessões remotas de agentes](/docs/copilot/concepts/agents.md#remote-agent-sessions).

Saiba mais sobre a [janela Agents](/docs/copilot/agents/agents-window.md).

## O que você pode construir

Os agentes lidam com tarefas de codificação de ponta a ponta, desde uma única
alteração em um arquivo até um recurso completo enviado como um pull request.

* **Construa um recurso de ponta a ponta.**
  Descreva um recurso em linguagem natural e o agente criará a estrutura do
  projeto, implementará a lógica em vários arquivos e executará testes para
  verificar o resultado.
* **Depure e corrija testes com falha.**
  Aponte um agente para um teste com falha e ele lerá o erro, rastreará a causa
  raiz em sua base de código, aplicará uma correção e executará o teste
  novamente para confirmar.
  Saiba mais sobre
  [depuração com IA](/docs/copilot/guides/debug-with-copilot.md).
* **Refatore ou migre uma base de código.**
  Peça a um agente para planejar uma migração, por exemplo, de um framework para
  outro, e ele aplicará alterações coordenadas em todos os arquivos, verificando
  com builds.
* **Teste e interaja com aplicações web.**
  _(Experimental)_ Peça a um agente para abrir sua aplicação web no
  [navegador integrado](/docs/debugtest/integrated-browser.md), verificar se um
  recurso funciona, verificar problemas de layout ou tirar capturas de tela.
  Siga o
  [guia de teste do agente do navegador](/docs/copilot/guides/browser-agent-testing-guide.md).
* **Colabore por meio de pull requests.**
  Delegue uma tarefa a um agente na nuvem que cria um branch, implementa as
  alterações e abre um pull request para seu time revisar.
  Saiba mais sobre [agentes na nuvem](/docs/copilot/agents/cloud-agents.md).

## Primeiros passos

### Passo 1: configure o Copilot

1. Passe o cursor sobre o ícone do Copilot na Barra de Status e selecione
   **Set up Copilot**.

   ![Captura de tela mostrando o ícone do Copilot na Barra de Status com a opção Set up Copilot.](images/setup/setup-copilot-status-bar.png)

1. Escolha um método de login e siga as instruções.
   Se você ainda não possui uma assinatura do Copilot, você está inscrito no
   [plano gratuito do Copilot](https://docs.github.com/en/copilot/managing-copilot/managing-copilot-as-an-individual-subscriber/managing-copilot-free/about-github-copilot-free).

### Passo 2: inicie sua primeira sessão com o agente

1. Abra a visualização **Chat** (`kb(workbench.action.chat.open)`).

1. Insira um prompt que descreva o que você deseja criar, por exemplo:

   ```prompt-agent
   Create a basic Node.js web app for sharing recipes. Make it look modern and responsive.
   ```

1. Revise o código gerado.
   O agente cria arquivos, instala dependências e executa comandos conforme
   necessário.

1. Digite `/init` para configurar seu projeto para IA.
   Isso cria
   [instruções personalizadas](/docs/copilot/customization/custom-instructions.md)
   que ajudam o agente a entender sua base de código e gerar um código melhor.

Para um tutorial prático completo que aborda sugestões de preenchimento em
linha, agentes, chat em linha e personalização, consulte
[Primeiros passos com o GitHub Copilot no VS Code](/docs/copilot/getting-started.md).

## Assistência de IA enquanto você digita

Para alterações menores ou quando você deseja um controle mais preciso, o
Copilot auxilia diretamente no editor.

### Sugestões em linha

O Copilot fornece sugestões de código enquanto você digita, desde o
preenchimento de uma única linha até a implementação completa de funções.
As sugestões de próxima edição preveem a próxima alteração lógica com base nas
suas edições atuais.

<video src="images/inline-suggestions/nes-video.mp4" title="Vídeo mostrando sugestões de código em linha aparecendo como texto fantasma no editor." controls muted poster="./images/inline-suggestions/point3d.png"></video>

Saiba mais sobre
[sugestões em linha no VS Code](/docs/copilot/ai-powered-suggestions.md).

### Chat em linha

Pressione `kb(inlinechat.start)` para abrir um prompt de chat diretamente no
editor.
Descreva uma alteração e o Copilot sugerirá edições no local, para que você
mantenha o fluxo de codificação.
Use-o para refatorações direcionadas, explicações ou correções rápidas sem
precisar trocar de contexto.

Saiba mais sobre [chat em linha no VS Code](/docs/copilot/chat/inline-chat.md).

### Ações inteligentes

O VS Code inclui ações predefinidas com IA para tarefas comuns: gerar mensagens
de commit, renomear símbolos, corrigir erros e executar buscas semânticas em
todo o seu projeto.

![Captura de tela mostrando o menu de ações inteligentes no VS Code com opções para corrigir uma falha de teste.](images/overview/copilot-chat-fix-test-failure.png)

Saiba mais sobre
[ações inteligentes no VS Code](/docs/copilot/copilot-smart-actions.md).

## Personalize a IA para o seu fluxo de trabalho

Os agentes funcionam melhor quando entendem as convenções do seu projeto, têm as
ferramentas certas e usam um modelo adequado à tarefa.
O VS Code oferece diversas maneiras de
[adaptar a IA](/docs/copilot/customization/overview.md) para ela gerar código
adequado à sua base de código desde o início, em vez de exigir correções manuais
posteriormente.

* **[Instruções personalizadas](/docs/copilot/customization/custom-instructions.md):
  defina convenções de codificação para todo o projeto, para que a IA gere
  código que corresponda ao seu estilo.
* **[Skills do agente](/docs/copilot/customization/agent-skills.md): ensine ao
  Copilot recursos especializados que funcionam no VS Code, na CLI do GitHub
  Copilot e no agente em nuvem do GitHub Copilot.
* **[Agentes personalizados](/docs/copilot/customization/custom-agents.md): crie
  agentes que assumam uma função específica, como revisor de código ou redator
  de documentação, com suas próprias ferramentas e instruções.
* * **[Servidores MCP](/docs/copilot/customization/mcp-servers.md)**: estenda os
  agentes com ferramentas dos servidores MCP ou extensões do Marketplace.
* **[Hooks](/docs/copilot/customization/hooks.md)**: execute comandos
  personalizados em eventos específicos para automação e aplicação de políticas.

<div class="docs-action" data-show-in-doc="false" data-show-in-sidebar="true" title="Personalize a IA">
Explore todas as maneiras de adaptar a experiência de IA ao seu fluxo de
trabalho.

* [Acesse a visão geral da personalização](/docs/copilot/customization/overview.md)

</div>

## Suporte

O suporte para o GitHub Copilot Chat é fornecido pelo GitHub e pode ser acessado
em <https://support.github.com>.

Para saber mais sobre a segurança, privacidade, conformidade e transparência do
Copilot, consulte as
[Perguntas frequentes da Central de Confiabilidade do GitHub Copilot](https://copilot.github.trust.page/faq).

## Preços

> [!IMPORTANT]
> **A partir de 20 de abril de 2026**, novas inscrições para o Copilot Pro,
> Copilot Pro+ e planos para estudantes serão temporariamente suspensas.
> Além disso, estamos restringindo os limites de uso semanais.
> Consulte os
> [Limites de uso do GitHub Copilot](https://docs.github.com/copilot/concepts/usage-limits).

Você pode começar a usar o GitHub Copilot gratuitamente com limites mensais para
sugestões em linha e interações no chat.
Para um uso mais extenso, você pode escolher entre vários planos pagos.

[Veja os preços detalhados do GitHub Copilot](https://docs.github.com/en/copilot/get-started/plans).

## Próximos passos

* [Início rápido: comece a usar o GitHub Copilot no VS Code](/docs/copilot/getting-started.md).
* [Tutorial: comece a usar agentes no VS Code](/docs/copilot/agents/agents-tutorial.md).
* [Personalize a IA para o seu fluxo de trabalho](/docs/copilot/customization/overview.md).
