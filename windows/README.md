# Windows

## Criação de Contas

* GitHub:
  - Crie uma conta no [Github](https://github.com) caso ainda não a possua.
* Docker Hub
  - Crie uma conta no [Docker Hub](https://hub.docker.com) caso ainda não a possua.

## Ambiente de Desenvolvimento

### Visual Studio Code

* Baixe e Instale o editor [VS Code](https://code.visualstudio.com)
* Em seguida, instale as seguintes extensões no VS Code:
  * [Cucumber (Gherkin)](https://marketplace.visualstudio.com/items?itemName=alexkrechik.cucumberautocomplete)
  * [Docker](https://marketplace.visualstudio.com/items?itemName=ms-azuretools.vscode-docker)
  * [Gherkin Indent](https://marketplace.visualstudio.com/items?itemName=AravindKumar.gherkin-indent)
  * [Material Icon Theme](https://marketplace.visualstudio.com/items?itemName=PKief.material-icon-theme)
  * [Remote Development](https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.vscode-remote-extensionpack)
  * [RSpec Snippets](https://marketplace.visualstudio.com/items?itemName=karunamurti.rspec-snippets)
  * [Ruby](https://marketplace.visualstudio.com/items?itemName=rebornix.Ruby)
  * [Ruby Rubocop](https://marketplace.visualstudio.com/items?itemName=misogi.ruby-rubocop)
  * [Ruby Solargraph](https://marketplace.visualstudio.com/items?itemName=castwide.solargraph)
  * [View In Browser](https://marketplace.visualstudio.com/items?itemName=qinjia.view-in-browser)
  * [YAML](https://marketplace.visualstudio.com/items?itemName=redhat.vscode-yaml)

### Docker

O docker dispõe de duas versões: Desktop e Toolbox. A diferença está na edição do sistema operacional do Windows. Se a edição for __Home__, então você precisará instalar o Docker Toolbox, do contrário, utilize a versão Desktop.

Então, qual é a edição do seu Sistema Operacional? [Não sei, quero descobrir](./about.md).

<details>
<summary>Windows Home</summary>
<br>
<p>Use o Docker Toolbox</p>

> O Docker Toolbox fornece uma maneira de usar o Docker em sistemas Windows que não atendem aos requisitos mínimos do sistema para o aplicativo Docker for Windows ([Instruções de Instalação](https://docs.docker.com/v17.12/toolbox/toolbox_install_windows/)).

Pós-Instalação:
  - Execute o __Docker Quickstart Terminal__
    - Um arquivo _.iso_ será baixado e inicializado no VirtualBox;
    - O sistema solicitará permissão para o VirtualBox, aprove todas;
    - Ao final, uma VM do Virtualbox estará rodando o Docker.

Observações:
  - O VirtualBox será instalado durante o processo de instalação;
  - Caso seu dispositivo possua o Hyper-V, desative-o;
  - Sempre execute o __Docker Quickstart Terminal__ ao iniciar o dispositivo.

</details>

<details>
<summary>Windows Pro / Enterprise / Education</summary>
<br>
<p>Use o Docker Desktop</p>

> O Docker Desktop para Windows é a versão comunitária do Docker para Microsoft Windows. Você pode baixar o Docker Desktop para Windows no Docker Hub ([Instruções de Instalação](https://docs.docker.com/docker-for-windows/install/)).

Observações:
  - A arquitetura do processador do dispositivo deve ser 64 bits;
  - O dispositivo precisa de, no mínimo, 4 GB de memória RAM;
  - O Hyper-V do dispositivo tem de estar habilitado.
</details>
