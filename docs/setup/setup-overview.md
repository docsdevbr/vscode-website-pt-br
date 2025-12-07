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

1. Baixe e instale o Visual Studio Code para sua plataforma

  * [macOS](/docs/setup/mac.md)
  * [Linux](/docs/setup/linux.md)
  * [Windows](/docs/setup/windows.md)

  > [!NOTE]
  > O VS Code lança versões mensais e oferece suporte à
  > [atualização automática](#update-cadence) quando uma nova versão estiver
  > disponível.

2. [Instale componentes adicionais](/docs/setup/additional-components.md)

  Instale Git, Node.js, TypeScript, ambientes de execução de linguagem e muito
  mais.

3. [Instale extensões do VS Code do Visual Studio Marketplace](https://marketplace.visualstudio.com/VSCode)

  Personalize o VS Code com temas, formatadores, extensões de linguagem e
  depuradores para suas linguagens favoritas e muito mais.

4. [Habilite recursos de IA](/docs/copilot/setup.md)

  > [!TIP]
  > Se você ainda não tem uma assinatura do Copilot, pode usá-lo gratuitamente
  > inscrevendo-se no
  > [Plano Copilot Gratuito](https://github.com/github-copilot/signup) e obter
  > um limite mensal de preenchimento automático e interações de bate-papo.

1. [Tutorial de introdução ao VS Code](/docs/getstarted/getting-started.md)

  Descubra a interface da pessoa usuária e os principais recursos do VS Code.

## Update cadence

VS Code releases a new version [each month](/updates) with new features and important bug fixes. Most platforms support auto updating and you are prompted to install the new release when it becomes available.

You can also manually check for updates by running **Help** > **Check for Updates** on Linux and Windows, or running **Code** > **Check for Updates** on macOS.

> [!NOTE]
> You can [disable auto-update](/docs/supporting/faq.md#how-do-i-opt-out-of-vs-code-autoupdates) if you prefer to update VS Code on your own schedule.

## Insiders nightly build

If you'd like to try our nightly builds to see new features early or verify bug fixes, you can install our [Insiders build](/insiders). The Insiders build installs side-by-side with the monthly Stable build and you can freely work with either on the same machine. The Insiders build is the same one the VS Code development team uses on a daily basis and we really appreciate people trying out new features and providing feedback.

## Portable mode

Visual Studio Code supports [Portable mode](https://en.wikipedia.org/wiki/Portable_application) installation. This mode enables all data created and maintained by VS Code to live near itself, so it can be moved around across environments, for example, on a USB drive. See the [VS Code Portable Mode](/docs/editor/portable.md) documentation for details.

## Next steps

Once you have installed VS Code, these topics will help you learn more about it:

* [VS Code tutorial](/docs/getstarted/getting-started.md) - A quick hands-on tour of the key features of VS Code.
* [Tips and Tricks](/docs/getstarted/tips-and-tricks.md) - A collection of productivity tips for working with VS Code.
* [AI-assisted coding](/docs/copilot/overview.md) - Learn about using GitHub Copilot in VS Code to help you write code faster.

## Common questions

### What are the system requirements for VS Code?

We have a list of [System Requirements](/docs/supporting/requirements.md).

### How big is VS Code?

VS Code is a small download (< 200 MB) and has a disk footprint of less than 500 MB, so you can quickly install VS Code and try it out.

### How do I create and run a new project?

VS Code doesn't include a traditional **File** > **New Project** dialog or pre-installed project templates. You'll need to add [additional components](/docs/setup/additional-components.md) and scaffolders depending on your development interests. With scaffolding tools like [Yeoman](https://yeoman.io/) and the multitude of modules available through the [npm](https://www.npmjs.com/) package manager, you're sure to find appropriate templates and tools to create your projects.

### How do I know which version I'm running?

On Linux and Windows, choose **Help** > **About**. On macOS, use **Code** > **About Visual Studio Code**.

### Why is VS Code saying my installation is unsupported?

VS Code has detected that some installation files have been modified, perhaps by an extension. Reinstalling VS Code will replace the affected files. See our [FAQ topic](/docs/supporting/faq.md#installation-appears-to-be-corrupt-unsupported) for more details.

### How can I do a 'clean' uninstall of VS Code?

If you want to remove all user data after [uninstalling](/docs/setup/uninstall.md) VS Code, you can delete the user data folders `Code` and `.vscode`. This returns you to the state before you installed VS Code. This can also be used to reset all settings if you don't want to uninstall VS Code.

The folder locations vary depending on your platform:

* **Windows** - Delete `%APPDATA%\Code` and `%USERPROFILE%\.vscode`.
* **macOS** - Delete `$HOME/Library/Application Support/Code` and `~/.vscode`.
* **Linux** - Delete `$HOME/.config/Code` and `~/.vscode`.
