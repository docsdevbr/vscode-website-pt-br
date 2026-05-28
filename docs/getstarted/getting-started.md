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

source_url: https://github.com/microsoft/vscode-docs/blob/main/docs/getstarted/getting-started.md
source_revision: b9731d7cf3dc3b478e3870682da6e96b034d7393
translation_status: ready

ContentId: 72ad9b70-5227-4032-81d7-6aec00a1e8f8
DateApproved: 5/28/2026
MetaDescription: >-
  Este tutorial oferece uma visão geral dos principais recursos do Visual Studio
  Code para te ajudar a começar rapidamente.
---

# Tutorial: Primeiros passos com o Visual Studio Code

Neste tutorial, você aprenderá sobre os principais recursos do Visual Studio
Code para começar rapidamente.
Você aprenderá sobre os diferentes componentes da interface da pessoa usuária,
usará um agente de IA para criar uma aplicação web e explorará como aprimorar
sua instalação com extensões.
Você também aprenderá sobre como alterar as configurações do VS Code, usar o
controle de versão e executar e depurar seu código.

> [!TIP]
>
> Se preferir um vídeo para aprender sobre o Visual Studio Code, você pode
> assistir ao vídeo
> [Primeiros passos](https://www.youtube.com/watch?v=f8_uF_IDV50) em nosso canal
> do YouTube.

<div class="docs-action" data-show-in-doc="false" data-show-in-sidebar="true" title="Primeiros passos com IA">
Siga um tutorial prático para criar sua primeira aplicação com IA no VS Code.

* [Inicie o tutorial](/docs/copilot/getting-started.md)

</div>

<div class="docs-action" data-show-in-doc="false" data-show-in-sidebar="true" title="Assista ao vídeo de introdução">
Saiba mais sobre os principais recursos do Visual Studio Code em nosso vídeo de
introdução.

* [Assista ao vídeo](https://www.youtube.com/watch?v=f8_uF_IDV50)

</div>

## Pré-requisitos

* [Baixe e instale o Visual Studio Code no seu computador](https://code.visualstudio.com/download).
* [Configure o GitHub Copilot no VS Code](/docs/copilot/setup.md).
* Instale o [Node.js](https://nodejs.org/) (para executar e depurar JavaScript).

> [!TIP]
>
> Se você ainda não tem uma assinatura do Copilot, pode usá-lo gratuitamente
> inscrevendo-se no
> [Plano Copilot Gratuito](https://github.com/github-copilot/signup) e obter um
> limite mensal de preenchimento automático e interações no chat.

## Abra uma pasta no VS Code

Você pode usar o VS Code para trabalhar em arquivos individuais e fazer edições
rápidas, ou pode abrir uma pasta, também conhecida como *workspace (espaço de
trabalho)*.

Vamos começar criando uma pasta e abrindo-a no VS Code.
Você usará esta pasta ao longo deste tutorial.

1. Abra o Visual Studio Code e selecione **File** > **Open Folder...** no menu
   para abrir uma pasta.

1. Selecione **New Folder** e crie uma nova pasta chamada `vscode101`.
   Em seguida, selecione **Select Folder** (**Open** no macOS) para abrir a
   pasta no VS Code.

   O VS Code agora considera a pasta que você abriu como um espaço de trabalho.

1. Na caixa de diálogo Workspace Trust, selecione **Yes, I trust the authors**
   para habilitar todos os recursos no espaço de trabalho.

   ![Captura de tela que mostra a caixa de diálogo Workspace Trust.](images/getting-started/workspace-trust.png)

   > [!IMPORTANT]
   >
   > A caixa de diálogo Workspace Trust permite que você decida se o código na
   > pasta do seu projeto pode ser executado pelo VS Code.
   > Ao baixar código da internet, você deve primeiro revisá-lo para garantir
   > que seja seguro executá-lo.
   > Obtenha mais informações sobre
   > [Workspace Trust](/docs/editing/workspaces/workspace-trust.md).

1. Agora você deve ver a visualização **Explorer** à esquerda, mostrando o nome
   da pasta.

   Você usará a visualização Explorer para visualizar e gerenciar os arquivos e
   pastas em seu espaço de trabalho.

   ![Captura de tela do VS Code com a visualização Explorer aberta e mostrando a pasta vscode101.](images/getting-started/vscode-folder-opened.png)

> [!TIP]
>
> Ao abrir uma pasta no VS Code, o VS Code pode restaurar o estado da interface
> da pessoa usuária para essa pasta, como os arquivos abertos, a visualização
> ativa e o layout do editor.
> Você também pode configurar opções que se aplicam somente a essa pasta ou
> definir configurações de depuração.
> Saiba mais sobre
> [espaços de trabalho](/docs/editing/workspaces/workspaces.md).

## Explore a interface da pessoa usuária

Agora que você tem uma pasta aberta no VS Code, vamos dar uma olhada rápida na
interface da pessoa usuária.

### Alterne entre visualizações com a Activity Bar

1. Use a Activity Bar para alternar entre diferentes visualizações.

   ![Captura de tela que destaca a Activity Bar.](images/getting-started/activity-bar.png)

   > [!TIP]
   >
   > Passe o mouse sobre a Activity Bar para ver o nome de cada visualização e o
   > atalho de teclado correspondente.
   > Você pode abrir e fechar uma visualização selecionando-a novamente ou
   > pressionando o atalho de teclado.

1. Ao selecionar uma visualização na Activity Bar, a **Primary Side Bar** é
   aberta para exibir informações específicas da visualização.

   Por exemplo, a visualização Run and Debug permite configurar e iniciar
   sessões de depuração.

   ![Captura de tela que mostra a Activity Bar e a visualização Run and Debug na Primary Side Bar.](images/getting-started/activity-bar-and-side-bar.png)

   > [!TIP]
   >
   > Observe a visualização **Chat** na Activity Bar.
   > É aqui que você interage com agentes de IA para gerar código, fazer
   > perguntas e muito mais.
   > Você a usará na próxima etapa para criar uma aplicação.

### Visualize e edite arquivos com o Editor

1. Selecione a visualização Explorer na Activity Bar e selecione o botão **New
   File...** para criar um novo arquivo em seu espaço de trabalho.

   ![Captura de tela mostrando o botão New File na visualização Explorer.](images/getting-started/explorer-new-file.png)

1. Digite o nome `index.html` e pressione `kbstyle(Enter)`.

   Um arquivo será adicionado ao seu espaço de trabalho e um Editor será aberto
   na área principal da janela.

   ![Captura de tela mostrando o Editor na área principal da janela.](images/getting-started/new-file-editor.png)

1. Comece a digitar algum código HTML no arquivo `index.html`.

   Conforme você digita, sugestões aparecerão na tela para completar seu código
   (*IntelliSense*).
   Você pode usar as teclas `kbstyle(Up)` e `kbstyle(Down)` para navegar pelas
   sugestões e `kbstyle(Tab)` para inserir a sugestão selecionada.

1. Adicione mais arquivos ao seu espaço de trabalho e observe que cada arquivo
   abre uma nova aba do Editor.

   Você pode abrir quantos editores quiser e visualizá-los lado a lado, vertical
   ou horizontalmente.
   Saiba mais sobre
   [edição lado a lado](/docs/getstarted/userinterface.md#side-by-side-editing).

   ![Captura de tela mostrando várias abas do Editor.](images/getting-started/multiple-editors.png)

### Acesse o terminal a partir da área Panel

1. O VS Code possui um terminal integrado.
   Abra-o pressionando `kb(workbench.action.terminal.toggleTerminal)`.
   Você também pode usar o item de menu **View** > **Terminal**.

   Você pode escolher entre diferentes shells, como PowerShell, Prompt de
   Comando ou Bash, dependendo da configuração do seu sistema operacional.

   ![Captura de tela que mostra a área Panel com a visualização Terminal.](images/getting-started/vscode-panel.png)

1. No terminal, digite o seguinte comando para criar um novo arquivo em seu
   espaço de trabalho.

   ```bash
   echo "Olá, VS Code" > greetings.txt
   ```

   A pasta de trabalho padrão é a raiz do seu espaço de trabalho.
   Observe que a visualização Explorer detecta e exibe automaticamente o novo
   arquivo.

   ![Captura de tela mostrando a visualização Explorer com o novo arquivo.](images/getting-started/terminal-new-file.png)

1. Você pode abrir vários terminais simultaneamente.
   Selecione o menu suspenso **Launch Profile** para visualizar os shells
   disponíveis e escolha um.

   ![Captura de tela mostrando o menu suspenso Launch Profile com os shells disponíveis.](images/getting-started/terminal-launch-profile.png)

### Acesse comandos com a Command Palette

1. Abra a **Command Palette** pressionando `kb(workbench.action.showCommands)`.
   Você também pode usar o item de menu **View** > **Command Palette**.

   Muitos dos comandos do VS Code estão disponíveis na Command Palette.
   Ao instalar extensões, você pode adicionar comandos extras à Command Palette.

   ![Captura de tela mostrando a Command Palette.](images/getting-started/command-palette.png)

   > [!TIP]
   >
   > Observe que a Command Palette exibe o atalho de teclado padrão para os
   > comandos que possuem um.
   > Você pode usar o atalho de teclado para executar o comando diretamente.

1. A Command Palette oferece diferentes modos de operação:

   1. **Modo de comando (`>`)**: após o símbolo `>`, comece a digitar para
      filtrar a lista de comandos.
      Por exemplo, digite `move terminal` para encontrar comandos para mover o
      terminal para uma nova janela.

      ![Captura de tela mostrando a Command Palette, listando as entradas para mover o terminal.](images/getting-started/command-palette-move-terminal.png)

   1. **Modo de abertura rápida**: remova o caractere `>` e comece a digitar
      para procurar arquivos em seu espaço de trabalho.
      Você pode usar o atalho de teclado `kb(workbench.action.quickOpen)` para
      abrir a Command Palette e começar a procurar arquivos diretamente.

      ![Captura de tela mostrando o recurso de abertura rápida na Command Palette.](images/getting-started/quick-open.png)

   1. **Modo de busca por símbolo (`#`)**: substitua o caractere `>` por `#`
      para procurar símbolos como variáveis ou funções em seu código.

> [!TIP]
>
> O VS Code usa correspondência aproximada para encontrar arquivos ou comandos.
> Por exemplo, digitar `odks` retorna o comando `Open Default Keyboard
> Shortcuts`.

## Crie uma aplicação com um agente de IA

O Visual Studio Code oferece suporte integrado ao GitHub Copilot para
programação com IA.
Os agentes de IA podem planejar uma solução de forma autônoma, criar e editar
vários arquivos, executar comandos no terminal e iterar sobre erros, tudo a
partir de um único prompt em linguagem natural.
Você descreve o que deseja e o agente faz o que for necessário para concluir a
tarefa.

Vamos usar agentes para criar uma aplicação web de lista de receitas a partir de
um único prompt.

1. Abra a visualização Chat pressionando `kb(workbench.action.chat.open)`.

1. Selecione **Agent** no menu suspenso da visualização Chat.
   Os agentes permitem que a IA crie e edite arquivos de forma autônoma, execute
   comandos no terminal e muito mais.

   ![Captura de tela mostrando o seletor de modo Agent na visualização Chat.](images/getting-started/chat-agent-mode.png)

1. Digite a seguinte mensagem na caixa de entrada do chat:

   ```prompt
   Create a recipe list app with HTML, CSS, and JavaScript in separate files. Include an input field to add recipes with a name and description, a list to display them, and a delete button for each item. Use modern styling. Add some sample recipes to the list.
   ```

   > [!NOTE]
   >
   > Se você ainda não configurou o GitHub Copilot, será solicitado que você
   > faça login na sua conta do GitHub e configure o Copilot antes de enviar a
   > mensagem.
   > Se você não tiver uma assinatura do Copilot, estará associado a uma conta
   > gratuita que oferece um limite mensal de preenchimento automático e
   > interações no chat.

1. Pressione `kbstyle(Enter)` para enviar a mensagem.

   O agente começará a gerar a aplicação.
   Observe como ele cria vários arquivos, mostra as alterações propostas e pode
   solicitar aprovação para executar comandos no terminal.

   ![Captura de tela mostrando o agente gerando a aplicação de lista de receitas na visualização Chat.](images/getting-started/agent-generating-app.png)

1. Revise os arquivos gerados e selecione **Keep** na visualização Chat para
   aceitar todas as alterações.

Na próxima etapa, você instalará uma extensão para hospedar a aplicação em um
navegador integrado.

## Aprimore sua instalação com extensões

O VS Code possui um rico ecossistema de extensões que permitem adicionar
linguagens, depuradores e ferramentas à sua instalação para otimizar seu fluxo
de trabalho de desenvolvimento.
Existem milhares de extensões disponíveis
no [Visual Studio Marketplace](https://marketplace.visualstudio.com/vscode).

Vamos instalar uma extensão que ajudará na aplicação de lista de receitas que
você acabou de criar.

1. Selecione a visualização **Extensions** na Activity Bar.

   A visualização Extensions permite navegar e instalar extensões diretamente do
   VS Code.

   ![Captura de tela mostrando a visualização Extensions, destacando o ícone Extensions na Activity Bar.](images/getting-started/extensions-view.png)

1. Digite *Live Preview* na caixa de pesquisa da visualização Extension.
   Selecione a extensão **Live Preview**, publicada pela Microsoft, e clique no
   botão **Install**.

   O Live Preview inicia um servidor de desenvolvimento local com recarregamento
   automático para páginas estáticas e dinâmicas.

1. Abra o arquivo `index.html`, clique com o botão direito do mouse no editor e
   selecione **Show Preview**.

   Sua aplicação de lista de receitas agora será aberta em um navegador.
   Quando você fizer alterações no código, o navegador será atualizado
   automaticamente para mostrar a versão mais recente.

   ![Captura de tela que mostra a pré-visualização da aplicação de lista de receitas.](images/getting-started/recipe-list-preview.png)

1. Continue a conversa no chat pedindo ao agente para adicionar um recurso.
   Digite a seguinte mensagem:

   ```prompt
   Add the ability to mark recipes as favorites with a star icon. Favorite recipes should appear at the top of the list.
   ```

   O agente modifica os arquivos existentes para adicionar o novo recurso.
   Isso mostra como você pode desenvolver sua aplicação iterativamente com
   mensagens de acompanhamento.

Explore mais recursos de IA no VS Code com o
[Guia de início rápido do Copilot](/docs/copilot/getting-started.md).

## Altere as configurações do VS Code

Você pode personalizar quase todas as partes do VS Code alterando as
configurações.
Você pode usar o **Settings Editor** para alterar as configurações no VS Code
ou alterar diretamente o arquivo `settings.json`.

1. Pressione `kb(workbench.action.openSettings)` para abrir o Settings Editor
   (ou selecione o item de menu **File** > **Preferences** > **Settings**).

   ![Captura de tela que mostra o Settings Editor.](images/getting-started/settings-editor.png)

    > [!TIP]
    > Use a caixa de pesquisa para filtrar a lista de configurações exibidas.

1. Por padrão, o VS Code não salva automaticamente os arquivos modificados.
   Selecione um valor no menu suspenso Auto Save para alterar esse
   comportamento.

   ![Captura de tela mostrando o menu suspenso Auto Save no Settings Editor.](images/getting-started/settings-editor-auto-save.png)

   O VS Code aplica automaticamente as alterações às configurações.
   Ao modificar um arquivo em seu espaço de trabalho, ele deverá ser salvo
   automaticamente.

1. Para reverter uma configuração para o valor padrão, selecione o ícone de
   engrenagem ao lado da configuração e selecione **Reset Setting**.

   ![Captura de tela mostrando o ícone de engrenagem ao lado de uma configuração no Settings Editor.](images/getting-started/settings-editor-reset-setting.png)

   > [!TIP]
   >
   > Você pode encontrar rapidamente todas as configurações modificadas
   > digitando `@modified` na caixa de pesquisa ou selecionando o filtro
   > **Modified**.

1. Você pode usar as guias no Settings Editor para alternar entre as
   configurações do **User** e as configurações do **Workspace**.

   As configurações do usuário se aplicam a todos os seus espaços de trabalho.
   As configurações do espaço de trabalho aplicam-se apenas ao espaço de
   trabalho atual.
   As configurações do espaço de trabalho substituem as configurações do
   usuário.
   Obtenha mais informações sobre
   [configurações no VS Code](/docs/configure/settings.md).

## Use o controle de versão

O Visual Studio Code possui gerenciamento de controle de versão (SCM) integrado
e inclui suporte nativo ao [Git](https://git-scm.com/).

Vamos usar o suporte integrado ao Git para fazer o commit das alterações feitas
anteriormente.

1. Selecione a visualização **Source Control** na Activity Bar para abri-la.

   ![Captura de tela mostrando a visualização Source Control, destacando o botão na Activity Bar.](images/getting-started/source-control-view.png)

1. Certifique-se de ter o [Git](https://git-scm.com/) instalado em seu
   computador.
   Caso contrário, você verá um botão na visualização Source Control para
   instalá-lo na sua máquina.

1. Selecione **Initialize Repository** para criar um novo repositório Git para
   seu espaço de trabalho.

   ![Captura de tela mostrando a visualização Source Control, destacando o botão Initialize Repository.](images/getting-started/source-control-initialize.png)

   Após inicializar um repositório, a visualização Source Control mostra as
   alterações feitas no seu espaço de trabalho.

1. Você pode adicionar alterações individuais ao stage passando o mouse sobre um
   arquivo e selecionando `+` ao lado dele.

   ![Captura de tela mostrando a visualização Source Control com as alterações no espaço de trabalho.](images/getting-started/source-control-changes.png)

   > [!TIP]
   >
   > Para adicionar todas as alterações ao stage, passe o mouse sobre
   > **Changes** e selecione o botão **Stage All Changes**.

1. Digite uma mensagem de commit, por exemplo, `Adiciona aplicação de lista de
   receitas`, e selecione **Commit** para fazer o commit das alterações no seu
   repositório Git.

   ![Captura de tela mostrando a visualização Source Control com uma mensagem de commit.](images/getting-started/source-control-commit.png)

   > [!TIP]
   >
   > Selecione **Graph** na visualização Source Control para exibir uma
   > representação visual do histórico de commits do seu repositório Git.

Há muito mais para descobrir sobre controle de origem no VS Code.
Saiba mais sobre
[controle de origem no VS Code](/docs/sourcecontrol/overview.md).

## Execute e depure seu código

O VS Code oferece suporte integrado para executar e depurar aplicações
JavaScript e Node.js.
Vamos usar o depurador para percorrer a aplicação de lista de receitas gerada
pelo agente.

> [!NOTE]
>
> Como o agente gera código dinamicamente, os nomes de arquivos e funções do seu
> projeto podem ser diferentes dos exemplos mostrados aqui.
> Procure por padrões semelhantes no seu próprio código gerado.

1. Abra o arquivo JavaScript que o agente criou para a sua aplicação de lista de
   receitas (por exemplo, `app.js` ou `script.js`).

1. Encontre a função que adiciona uma receita (por exemplo, `addRecipe`).
   Posicione o cursor na primeira linha dentro do corpo da função e pressione
   `kbstyle(F9)` para definir um breakpoint.

   Um ponto vermelho aparecerá na margem esquerda do editor, indicando que um
   breakpoint foi definido.
   Com um breakpoint, você pode pausar a execução do seu programa em uma linha
   de código específica.

   ![Captura de tela mostrando um breakpoint definido na função addRecipe no arquivo JavaScript.](images/getting-started/js-set-breakpoint.png)

1. Abra a visualização Run and Debug na Activity Bar, selecione **Debug URL** e
   insira a URL da pré-visualização da sua aplicação de lista de receitas (por
   exemplo, `http://localhost:3000`).

   ![Captura de tela mostrando a configuração Debug URL na visualização Run and Debug.](images/getting-started/debug-url.png)

   O depurador é iniciado e abre uma janela do navegador com sua aplicação.

1. Quando o breakpoint é atingido, a execução é pausada e o VS Code destaca a
   linha atual.

   ![Captura de tela mostrando o programa parado em um breakpoint no editor, destacando a visualização Variables para inspecionar as variáveis.](images/getting-started/vscode-debugging.png)

   > [!TIP]
   >
   > Inspecione os valores das variáveis passando o mouse sobre elas no editor
   > enquanto a execução estiver pausada.
   > Você pode visualizar todas as variáveis a qualquer momento na visualização
   > **Variables** na visualização **Run and Debug**.

1. Use a barra de ferramentas Debug para percorrer o código passo a passo.
   Pressione **Step Over** (`kbstyle(F10)`) para executar a linha atual e passar
   para a próxima, ou pressione **Continue** (`kbstyle(F5)`) para retomar a
   execução.

   ![Captura de tela mostrando a barra de ferramentas Debug com o botão Continue destacado.](images/getting-started/debug-toolbar-play.png)

   Existem muitos outros recursos de depuração no VS Code, como variáveis de
   inspeção, breakpoints condicionais e configurações de inicialização.
   Explore os detalhes da [depuração no VS Code](/docs/debugtest/debugging.md).

## Próximos passos

Parabéns!
Você concluiu o tutorial e explorou alguns dos principais recursos do Visual
Studio Code.
Agora que você aprendeu o básico do Visual Studio Code, obtenha mais informações
sobre como:

* [Criar sua primeira aplicação com IA](/docs/copilot/getting-started.md).

* [Explorar diferentes tipos de agentes](/docs/copilot/agents/agents-tutorial.md).

* [Descobrir e executar testes unitários para seu código](/docs/debugtest/testing.md).

* [Usar o terminal integrado](/docs/terminal/getting-started.md).

* [Configurar um ambiente de desenvolvimento remoto](/docs/remote/remote-overview.md).
