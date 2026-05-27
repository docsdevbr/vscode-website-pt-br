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

source_url: https://github.com/microsoft/vscode-docs/blob/main/docs/setup/setup-overview.md
source_revision: d3018c18846c29b1a635bbf6f37f30264a66859e
translation_status: ready

ContentId: FC5262F3-D91D-4665-A5D2-BCBCCF66E53A
DateApproved: 5/20/2026
MetaDescription: >-
  Instale o Visual Studio Code no Windows, macOS ou Linux e escolha as opções de
  configuração adequadas ao seu fluxo de trabalho.
MetaSocialImage: images/quicksetup/quick-setup-social.png
---

# Configurando o Visual Studio Code

O Visual Studio Code é um editor de código para Windows, macOS e Linux.
Use este artigo para escolher um caminho de instalação, verificar os requisitos
e encontrar opções de configuração relacionadas.

O VS Code é leve e deve funcionar na maioria das versões de hardware e
plataformas disponíveis.
Consulte os [requisitos de sistema](/docs/supporting/requirements.md) para
verificar se a configuração do seu computador é compatível.

<div class="docs-action" data-show-in-doc="false" data-show-in-sidebar="true" title="Primeiros passos com IA">
Siga um tutorial prático para criar seu primeiro aplicativo com IA no VS Code.

* [Inicie o tutorial](/docs/copilot/getting-started.md)

</div>

## Configure o VS Code para sua plataforma

Escolha o caminho de instalação que corresponde ao ambiente em que você deseja
trabalhar.

<div class="card-grid">
  <a class="card" href="/docs/setup/windows">
    <i class="codicon codicon-device-desktop" aria-hidden="true"></i>
    <p>Instale no Windows</p>
  </a>
  <a class="card" href="/docs/setup/mac">
    <i class="codicon codicon-device-desktop" aria-hidden="true"></i>
    <p>Instale no macOS</p>
  </a>
  <a class="card" href="/docs/setup/linux">
    <i class="codicon codicon-terminal" aria-hidden="true"></i>
    <p>Instale no Linux</p>
  </a>
  <a class="card" href="/docs/setup/vscode-web">
    <i class="codicon codicon-globe" aria-hidden="true"></i>
    <p>Use o VS Code para a Web</p>
  </a>
</div>

> [!NOTE]
>
> O VS Code lança versões semanais.
> A maioria das instalações para desktop oferece suporte à
> [atualização automática](#frequência-de-atualizações) quando uma nova versão
> está disponível.

## Após a instalação

Após instalar o VS Code, conclua a configuração para seu fluxo de trabalho de
desenvolvimento:

* [Instale componentes adicionais](/docs/setup/additional-components.md),
  incluindo Git, Node.js, TypeScript, ambientes de execução de linguagem e
  ferramentas de linha de comando.
* [Instale extensões do Visual Studio Marketplace](https://marketplace.visualstudio.com/VSCode)
  para adicionar temas, formatadores, depuradores e suporte a linguagens.
* [Configure o GitHub Copilot](/docs/copilot/setup.md) para usar recursos de IA
  no VS Code.
* [Inicie o tutorial do VS Code](/docs/getstarted/getting-started.md) para um
  tour prático pela interface da pessoa usuária e seus principais recursos.

> [!TIP]
>
> Novas pessoas usuárias do Copilot podem começar com o
> [plano gratuito do Copilot](https://github.com/github-copilot/signup), que
> inclui um limite mensal de preenchimento automático e interações no chat.

## Frequência de atualizações

O VS Code lança uma nova versão [semanalmente](/updates) com novos recursos e
correções de falhas importantes.
A maioria das plataformas oferece suporte à atualização automática e solicita a
instalação da nova versão quando ela estiver disponível.

Para verificar atualizações manualmente, execute **Help** > **Check for
Updates** no Windows e Linux ou execute **Code** > **Check for Updates** no
macOS.

> [!NOTE]
>
> [Desative a atualização automática](/docs/supporting/faq.md#how-do-i-opt-out-of-vs-code-auto-updates)
> se preferir atualizar o VS Code de acordo com sua própria programação.

## Versão noturna Insiders

Para experimentar as versões noturnas, visualizar novos recursos ou verificar
correções de falhas, instale a versão [Insiders](/insiders).
A versão Insiders é instalada em paralelo com a versão estável semanal.
O time de desenvolvimento do VS Code usa a versão Insiders diariamente e
agradece o feedback de quem experimenta novos recursos antecipadamente.

Como as versões Insiders são lançadas diariamente, várias versões costumam
compartilhar o mesmo número de versão do produto.
Para identificar uma versão Insiders específica, use o ID do commit exibido na
caixa de diálogo **About**, além do número da versão.

## Modo portátil

O Visual Studio Code oferece suporte ao
[modo portátil](https://en.wikipedia.org/wiki/Portable_application).
O modo portátil armazena os dados do VS Code junto à aplicação, permitindo que a
instalação seja movida entre ambientes, como em um pen drive.
Consulte a documentação do [modo portátil do VS Code](/docs/editor/portable.md)
para obter mais detalhes.

## Próximos passos

Estes tópicos ajudam você a aprender mais após a configuração:

* [Tutorial do VS Code](/docs/getstarted/getting-started.md) - Um breve tour
  prático pelos principais recursos do VS Code.
* [Dicas e Truques](/docs/getstarted/tips-and-tricks.md) - Uma coleção de dicas
  de produtividade para trabalhar com o VS Code.
* [Codificação assistida por IA](/docs/copilot/overview.md) - Saiba como o
  GitHub Copilot no VS Code ajuda você a escrever código mais rapidamente.

## Perguntas frequentes

<details>
<summary>Quais são os requisitos de sistema para o VS Code?</summary>

Consulte os [requisitos de sistema](/docs/supporting/requirements.md) para obter
informações sobre plataformas e hardware compatíveis.

</details>

<details>
<summary>Qual o tamanho do VS Code?</summary>

O VS Code é um download pequeno, com menos de 200 MB, e ocupa menos de 500 MB de
espaço em disco.

</details>

<details>
<summary>Como criar e executar um novo projeto?</summary>

O VS Code não inclui uma caixa de diálogo tradicional **File** > **New Project**
nem modelos de projeto pré-instalados.
Adicione [componentes adicionais](/docs/setup/additional-components.md) e
ferramentas de scaffolding com base no seu fluxo de trabalho de desenvolvimento.
Ferramentas de scaffolding como o [Yeoman](https://yeoman.io/) e pacotes do
gerenciador de pacotes [npm](https://www.npmjs.com/) fornecem modelos e
ferramentas para criar projetos.

</details>

<details>
<summary>Como saber qual versão estou executando?</summary>

No Linux e no Windows, escolha **Help** > **About**.
No macOS, use **Code** > **About Visual Studio Code**.
A caixa de diálogo **About** mostra o número da versão e o ID do commit.
Para builds Insiders, várias builds podem compartilhar o mesmo número de versão;
portanto, use o ID do commit para identificar sua build de forma exclusiva.

</details>

<details>
<summary>Por que o VS Code está dizendo que minha instalação não é compatível?</summary>

O VS Code detectou que alguns arquivos de instalação foram modificados,
possivelmente por uma extensão.
Reinstalar o VS Code substituirá os arquivos afetados.
Consulte nosso
[tópico de perguntas frequentes](/docs/supporting/faq.md#installation-appears-to-be-corrupt-unsupported)
para obter mais detalhes.

</details>

<details>
<summary>Como posso fazer uma desinstalação completa do VS Code?</summary>

Para remover todos os dados do usuário após
[desinstalar](/docs/setup/uninstall.md) o VS Code, exclua as pastas de dados do
usuário `Code` e `.vscode`.
Isso restaura o VS Code ao estado anterior à instalação e pode redefinir todas
as configurações sem desinstalar o VS Code.
A localização das pastas varia conforme a sua plataforma:

* **Windows** - Exclua `%APPDATA%\Code` e `%USERPROFILE%\.vscode`.
* **macOS** - Exclua `$HOME/Library/Application Support/Code` e `~/.vscode`.
* **Linux** - Exclua `$HOME/.config/Code` e `~/.vscode`.

</details>
