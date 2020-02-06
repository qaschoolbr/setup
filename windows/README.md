# Windows

## Criação de Contas

* GitHub:
  * Crie uma conta no [Github](https://github.com) caso ainda não a possua.
* Docker Hub
  * Crie uma conta no [Docker Hub](https://hub.docker.com) caso ainda não a possua.

## Ambiente de Desenvolvimento

Siga estritamente a ordem de instalação elencada abaixo:

### Visual Studio Code

* Baixe e Instale o editor VS Code

  [Instruções de Instalação](./vscode/README.md)

* Em seguida, instale as seguintes extensões no VS Code:
  * [Cucumber (Gherkin)](https://marketplace.visualstudio.com/items?itemName=alexkrechik.cucumberautocomplete)
  * [Docker](https://marketplace.visualstudio.com/items?itemName=ms-azuretools.vscode-docker)
  * [DotENV](https://marketplace.visualstudio.com/items?itemName=mikestead.dotenv)
  * [Gherkin Indent](https://marketplace.visualstudio.com/items?itemName=AravindKumar.gherkin-indent)
  * [GitLens — Git supercharged](https://marketplace.visualstudio.com/items?itemName=eamodio.gitlens)
  * [Jenkinsfile Support](https://marketplace.visualstudio.com/items?itemName=secanis.jenkinsfile-support)
  * [Material Icon Theme](https://marketplace.visualstudio.com/items?itemName=PKief.material-icon-theme)
  * [Project Manager](https://marketplace.visualstudio.com/items?itemName=alefragnani.project-manager)
  * [Remote Development](https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.vscode-remote-extensionpack)
  * [RSpec Snippets](https://marketplace.visualstudio.com/items?itemName=karunamurti.rspec-snippets)
  * [Ruby](https://marketplace.visualstudio.com/items?itemName=rebornix.Ruby)
  * [Ruby Rubocop](https://marketplace.visualstudio.com/items?itemName=misogi.ruby-rubocop)
  * [Ruby Solargraph](https://marketplace.visualstudio.com/items?itemName=castwide.solargraph)
  * [View In Browser](https://marketplace.visualstudio.com/items?itemName=qinjia.view-in-browser)
  * [YAML](https://marketplace.visualstudio.com/items?itemName=redhat.vscode-yaml)

### Git for Windows

* Baixe e Instale o Git

  [Instruções de Instalação](./git/README.md)

### Ruby

* Baixe e Instale o Ruby

  [Instruções de Instalação](./ruby/README.md)

### Selenium WebDrivers

* Baixe e Instale o ChromeDriver e o GeckoDriver

  [Instruções de Instalação](./selenium/README.md)

### Docker

O docker dispõe de duas versões: Desktop e Toolbox. A diferença está na edição do sistema operacional do Windows. Se a edição for __Home__, então você precisará instalar o Docker Toolbox, do contrário, utilize a versão Desktop.

Então, qual é a edição do seu Sistema Operacional?

* [Home](./docker/toolbox/README.md)
* [Pro / Enterprise / Education](./docker/desktop/README.md)
* [Não sei, quero descobrir](./system/README.md)

#### Docker Images

Após instalar o Docker, execute os seguintes comandos no terminal, um a um, para baixar as imagens que serão utilizadas no treinamento:

```bash
$ docker pull jenkinsci/blueocean
```

```bash
$ docker pull portainer/portainer
```

```bash
$ docker pull qaschool/oficina
```

```bash
$ docker pull qaschool/qaops
```

```bash
$ docker pull redis
```

```bash
$ docker pull redislabs/redisinsight
```

```bash
$ docker pull ruby
```

### Zoom

O treinamento será transmitido através do aplicativo Zoom.

* Baixe e Instale o Zoom.

  [Instruções de Instalação](./zoom/README.md)


### Play with Docker

Caso você não queira instalar as ferramentas em seu dispositivo, pode usar o ambiente online. Basta clicar no botão abaixo que toda a estrutura necessária para o projeto será levantado para uso:

[![Try in PWD](https://raw.githubusercontent.com/play-with-docker/stacks/master/assets/images/button.png)](https://labs.play-with-docker.com/?stack=https://raw.githubusercontent.com/qaschoolbr/cucumber/master/qaops-stack.yml)
