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

source_url: https://github.com/microsoft/vscode-docs/blob/main/docs/setup/setup-overview.md
revision: 38307c037e45ef51640f3f2c040e05e629a347a5
status: ready

ContentId: FC5262F3-D91D-4665-A5D2-BCBCCF66E53A
DateApproved: 11/12/2025
MetaDescription: Instale e execute o Visual Studio Code.
MetaSocialImage: images/quicksetup/quick-setup-social.png
---

# Configurando o Visual Studio Code

O VS Code é um editor de código gratuito que funciona nos sistemas operacionais
macOS, Linux e Windows.
Começar a usar o Visual Studio Code é rápido e fácil.
O download é pequeno, então você pode instalá-lo em poucos minutos e
experimentar o VS Code.

O VS Code é leve e deve funcionar na maioria dos hardwares e plataformas
disponíveis.
Você pode consultar os [Requisitos de sistema](/docs/supporting/requirements.md)
para verificar se a configuração do seu computador é suportada.

## Configurando o VS Code para sua plataforma

1. Baixe e instale o Visual Studio Code para sua plataforma:

  * [macOS](/docs/setup/mac.md)
  * [Linux](/docs/setup/linux.md)
  * [Windows](/docs/setup/windows.md)

  > [!NOTE]
  > O VS Code lança versões mensais e oferece suporte à
  > [atualização automática](#frequência-de-atualizações) quando uma nova versão estiver
  > disponível.

2. [Instale componentes adicionais](/docs/setup/additional-components.md):

  Instale Git, Node.js, TypeScript, ambientes de execução de linguagem e muito
  mais.

3. [Instale extensões do VS Code a partir do Visual Studio Marketplace](https://marketplace.visualstudio.com/VSCode):

  Personalize o VS Code com temas, formatadores, extensões de linguagem e
  depuradores para suas linguagens favoritas e muito mais.

4. [Habilite recursos de IA](/docs/copilot/setup.md):

  > [!TIP]
  > Se você ainda não tem uma assinatura do Copilot, pode usá-lo gratuitamente
  > inscrevendo-se no
  > [Plano Copilot Gratuito](https://github.com/github-copilot/signup) e obter
  > um limite mensal de preenchimento automático e interações de bate-papo.

5. [Tutorial de introdução ao VS Code](/docs/getstarted/getting-started.md):

  Descubra a interface da pessoa usuária e os principais recursos do VS Code.

## Frequência de atualizações

O VS Code lança uma nova versão [mensalmente](/updates) com novos recursos e
correções de falhas importantes.
A maioria das plataformas oferece suporte à atualização automática e você
receberá uma notificação para instalar a nova versão quando ela estiver
disponível.

Você também pode verificar manualmente se há atualizações executando **Ajuda** >
**Verificar se há Atualizações** no Linux e no Windows ou executando **Código**
\> **Verificar se há atualizações** no macOS.

> [!NOTE]
> Você pode
> [desativar a atualização automática](/docs/supporting/faq.md#how-do-i-opt-out-of-vs-code-autoupdates)
> se preferir atualizar o VS Code de acordo com sua própria programação.

## Versão noturna Insiders

Se você quiser experimentar nossas versões noturnas para ver novos recursos
antecipadamente ou verificar correções de falhas, você pode instalar nossa
[versão Insiders](/insiders).
A versão Insiders é instalada em paralelo com a versão estável mensal e você
pode trabalhar livremente com qualquer uma delas na mesma máquina.
A versão Insiders é a mesma que o time de desenvolvimento do VS Code usa
diariamente e agradecemos muito se as pessoas experimentarem novos recursos e
fornecerem feedback.

## Modo portátil

O Visual Studio Code oferece suporte à instalação no
[Modo portátil](https://en.wikipedia.org/wiki/Portable_application).
Esse modo permite que todos os dados criados e mantidos pelo VS Code fiquem
armazenados junto a ele, para que possam ser movidos entre ambientes, por
exemplo, em um pen drive.
Consulte a documentação do [Modo portátil do VS Code](/docs/editor/portable.md)
para obter detalhes.

## Próximos passos

Depois de instalar o VS Code, estes tópicos ajudarão você a aprender mais sobre
ele:

* [Tutorial do VS Code](/docs/getstarted/getting-started.md) - um guia rápido e
  prático sobre os principais recursos do VS Code;
* [Dicas e truques](/docs/getstarted/tips-and-tricks.md) - uma coleção de dicas
  de produtividade para trabalhar com o VS Code;
* [Codificação assistida por IA](/docs/copilot/overview.md) - saiba como usar o
  GitHub Copilot no VS Code para escrever código mais rapidamente.

## Perguntas frequentes

### Quais são os requisitos de sistema para o VS Code?

Temos uma lista de [Requisitos de sistema](/docs/supporting/requirements.md).

### Qual o tamanho do VS Code?

O VS Code é um programa pequeno para baixar (menos de 200 MB) e ocupa menos de
500 MB de espaço em disco, permitindo que você o instale e experimente
rapidamente.

### Como criar e executar um novo projeto?

O VS Code não inclui a tradicional caixa de diálogo **Arquivo** > **Novo
Projeto** nem templates de projeto pré-instalados.
Você precisará adicionar
[componentes adicionais](/docs/setup/additional-components.md) e ferramentas de
geração automática de código, dependendo dos seus interesses de desenvolvimento.
Com ferramentas de geração automática de código como o
[Yeoman](https://yeoman.io/) e a infinidade de módulos disponíveis no
gerenciador de pacotes [npm](https://www.npmjs.com/), você certamente encontrará
templates e ferramentas adequados para criar seus projetos.

### Como saber qual versão estou executando?

No Linux e no Windows, selecione **Ajuda** > **Sobre**.
No macOS, acesse **Código** > **Sobre o Visual Studio Code**.

### Por que o VS Code está dizendo que minha instalação não é compatível?

O VS Code detectou que alguns arquivos de instalação foram modificados,
possivelmente por uma extensão.
Reinstalar o VS Code substituirá os arquivos afetados.
Consulte nosso
[tópico de perguntas frequentes](/docs/supporting/faq.md#installation-appears-to-be-corrupt-unsupported)
para obter mais detalhes.

### Como posso fazer uma desinstalação completa do VS Code?

Se você quiser remover todos os dados do usuário após
[desinstalar](/docs/setup/uninstall.md) o VS Code, você pode excluir as pastas
de dados do usuário `Code` e `.vscode`.
Isso restaura o sistema ao estado anterior à instalação do VS Code.
Essa opção também pode ser usada para redefinir todas as configurações, caso
você não queira desinstalar o VS Code.

A localização das pastas varia de acordo com a plataforma:

* **Windows** - exclua `%APPDATA%\Code` e `%USERPROFILE%\.vscode`;
* **macOS** - exclua `$HOME/Library/Application Support/Code` e `~/.vscode`;
* **Linux** - exclua `$HOME/.config/Code` e `~/.vscode`.
