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

source_url: https://github.com/microsoft/vscode-docs/blob/main/docs/setup/windows.md
revision: 002f098cbbea65f2bed2e8cb84ce1decedaba851
status: ready

ContentId: 4670C281-5761-46E6-8C46-10D523946FFB
DateApproved: 5/13/2026
MetaDescription: >-
  Instale o Visual Studio Code no Windows, escolha a instalação de usuário ou
  sistema e configure as ferramentas de desenvolvedor do Windows.
MetaSocialImage: images/quicksetup/quick-setup-social.png
---

# Instalando o Visual Studio Code no Windows

O Visual Studio Code está disponível para Windows por meio de um instalador de
usuário, um instalador de sistema e um arquivo ZIP.
A instalação de usuário é a recomendada para a maioria das pessoas, pois não
requer permissões de administrador e oferece atualizações em segundo plano mais
suaves.

## Instale o VS Code no Windows

### Escolha a instalação de usuário ou a instalação de sistema

O VS Code oferece instalações em nível de usuário e em nível de sistema no
Windows.

| Tipo de instalação                                                      | Usar quando                                          | Observações |
|-------------------------------------------------------------------------|------------------------------------------------------|-------|
| [Instalação de usuário](https://go.microsoft.com/fwlink/?LinkID=534107) | Instale o VS Code para sua conta do Windows.         | Esta instalação não requer permissões de administrador. Ela é instalada em `%LOCALAPPDATA%\Programs\Microsoft VS Code` e oferece a experiência de atualização mais suave. As atualizações são desativadas quando o VS Code é executado como administrador a partir de uma instalação de usuário. |
| [Instalação de sistema](https://go.microsoft.com/fwlink/?linkid=852157) | Instale o VS Code para todos os usuários da máquina. | Esta instalação requer permissões de administrador e é feita em `Arquivos de Programas`. As atualizações internas também exigem privilégios elevados. |

Consulte a página [Baixe o Visual Studio Code](/download) para obter a lista
completa de opções de instalação.

### Instale com o instalador de usuário

1. Baixe o
   [Instalador de usuário do Visual Studio Code](https://go.microsoft.com/fwlink/?LinkID=534107)
   para Windows.

2. Execute o instalador, `VSCodeUserSetup-{versão}.exe`.

   Por padrão, o instalador de usuário instala o VS Code em
   `C:\Users\{Nome de usuário}\AppData\Local\Programs\Microsoft VS Code`.

> [!TIP]
>
> O instalador adiciona o Visual Studio Code à sua variável de ambiente
> `%PATH%`.
> Reinicie o console após a instalação e execute `code .` em uma pasta para
> abri-la no VS Code.

### Instale com o instalador de sistema

1. Baixe o
   [instalador de sistema do Visual Studio Code](https://go.microsoft.com/fwlink/?linkid=852157)
   para Windows.

2. Execute o instalador com permissões de administrador.

O instalador do sistema disponibiliza o VS Code para todos os usuários do
computador.

### Instale a partir de um arquivo ZIP

1. Baixe o [arquivo ZIP do Visual Studio Code](/download) para Windows.

2. Extraia o arquivo ZIP e execute o VS Code a partir da pasta extraída.

> [!NOTE]
>
> Quando o VS Code é instalado a partir de um arquivo ZIP, atualize-o
> manualmente para cada [versão](/updates).

## Atualizações

O VS Code lança [atualizações](/updates) semanais e oferece suporte à
atualização automática quando uma nova versão estiver disponível.
Quando o VS Code solicitar uma atualização, aceite a solicitação para instalar a
nova versão.

> [!NOTE]
>
> [Desative a atualização automática](/docs/supporting/faq.md#how-do-i-opt-out-of-vs-code-auto-updates)
> se preferir atualizar o VS Code de acordo com sua própria agenda.

## Desenvolva no Windows

O Windows funciona bem como um ambiente de desenvolvimento multiplataforma.
Esta seção aborda o
[Subsistema Windows para Linux](https://learn.microsoft.com/windows/wsl/install)
(WSL) e o Terminal do Windows.

> [!NOTE]
>
> Mantenha o Windows atualizado.
> Verifique **Settings** > **Windows Update** para obter atualizações
> disponíveis.

### Subsistema Windows para Linux

Com o WSL, instale e execute distribuições Linux no Windows para desenvolver e
testar código-fonte no Linux enquanto trabalha localmente em sua máquina
Windows.

Quando combinado com a
[extensão WSL](https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.remote-wsl),
o VS Code oferece suporte para edição e depuração enquanto é executado no
contexto do WSL.

Consulte a documentação [Desenvolvendo no WSL](/docs/remote/wsl.md) para saber
mais ou experimente o tutorial introdutório
[Trabalhando no WSL](/docs/remote/wsl-tutorial.md).

### Terminal do Windows

O [Terminal do Windows](https://apps.microsoft.com/detail/9n0dx20hk701),
disponível na Microsoft Store, é uma aplicação de terminal para ferramentas de
linha de comando e shells como o Prompt de Comando, o PowerShell e o WSL.
Suas principais funcionalidades incluem múltiplas abas, painéis, suporte a
caracteres Unicode e UTF-8, um mecanismo de renderização de texto acelerado por
GPU, temas, estilos e configurações personalizados.

## Após a instalação

Após instalar o VS Code, conclua a configuração para o seu fluxo de trabalho de
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

## Perguntas frequentes

<details>
<summary>Quais argumentos de linha de comando são suportados pela Instalação do Windows?</summary>

O VS Code usa o [Inno Setup](https://www.jrsoftware.org/isinfo.php) para criar
seu pacote de instalação do Windows.
Todas as
[opções de linha de comando do Inno Setup](https://www.jrsoftware.org/ishelp/index.php?topic=setupcmdline)
estão disponíveis.

Para impedir que a Instalação inicie o VS Code após a conclusão, use
`/mergetasks=!runcode`.

</details>

<details>
<summary>Estou com problemas com o instalador</summary>

Use o [arquivo ZIP](/download) em vez do instalador.
Para usar este método de instalação, descompacte o VS Code na pasta
`AppData\Local\Programs`.

</details>

<details>
<summary>Não é possível executar como administrador com o AppLocker ativado</summary>

Com a introdução do sandbox de processos, a execução como administrador não é
suportada quando o AppLocker está configurado devido a uma limitação do sandbox
de tempo de execução.
Leia a
[postagem do blog sobre sandbox do VS Code](https://code.visualstudio.com/blogs/2022/11/28/vscode-sandbox)
para obter mais informações.

Se o seu trabalho exigir que o VS Code seja executado a partir de um terminal
com privilégios elevados:

1. No VS Code, execute o comando **Preferences: Configure Runtime Arguments** na
   Paleta de Comandos (`kb(workbench.action.showCommands)`).

   Este comando abre um arquivo `argv.json` para configurar os argumentos de
   tempo de execução do VS Code.
   O arquivo pode já conter argumentos padrão.

2. Adicione `"disable-chromium-sandbox": true` ao arquivo `argv.json`.

3. Reinicie o VS Code.
   O VS Code poderá então ser executado a partir de um terminal com privilégios
   elevados.

Inscreva-se na
[issue #122951](https://github.com/microsoft/vscode/issues/122951) para receber
atualizações.

</details>

<details>
<summary>Trabalhando com caminhos UNC</summary>

A partir da versão `1.78.1`, o VS Code no Windows só abre caminhos UNC que foram
aprovados pela pessoa usuária na inicialização ou cujo nome do host foi
configurado por meio da configuração `setting(security.allowedUNCHosts)`.
Os caminhos UNC começam com um `\\`.

Se o seu fluxo de trabalho depende de caminhos UNC no VS Code, use uma destas
opções:

* Configure o host com a configuração `setting(security.allowedUNCHosts)`.
  Por exemplo, adicione `server-a` ao abrir um caminho como `\\server-a\path`.
* [Mapeie o caminho UNC como uma unidade de rede](https://support.microsoft.com/en-us/windows/map-a-network-drive-in-windows-29ce55d1-34e3-a7e2-4801-131475f9557d)
  e use a letra da unidade em vez do caminho UNC.
* Defina uma variável de ambiente global chamada `NODE_UNC_HOST_ALLOWLIST` com
  uma lista de nomes de host permitidos, separados por barra invertida.
  Por exemplo, `server-a\server-b` permite os hosts `server-a` e `server-b`.

> [!NOTE]
>
> Se uma extensão remota se conectar a um espaço de trabalho remoto, como por
> SSH, configure `setting(security.allowedUNCHosts)` na máquina remota, não na
> máquina local.

Essa alteração melhora a segurança ao usar o VS Code com caminhos UNC.
Consulte o
[aviso de segurança](https://github.com/microsoft/vscode/security/advisories/GHSA-mmfh-4pv3-39hr)
associado para obter mais informações.

</details>
