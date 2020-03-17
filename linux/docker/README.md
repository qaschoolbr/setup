![Docker Desktop](./images/docker.png)

# Docker Desktop

O Docker CE para Linux é a versão comunitária do Docker para o Linux.

## Pré-Instalação

1. Atualize o sistema:

    ```bash
    $ sudo apt-get update
    ```

2. Instale os pacotes:

    ```bash
    $ sudo apt-get install apt-transport-https ca-certificates curl gnupg-agent software-properties-common -y
    ```

3. Adicione chave GPG:

    ```bash
    $ curl -fsSL https://download.docker.com/linux/ubuntu/gpg | sudo apt-key add -
    ```

4. Configure o repositório:

    ```bash
    $ sudo add-apt-repository "deb [arch=amd64] https://download.docker.com/linux/ubuntu $(lsb_release -cs) stable"
    ```

5. Atualize o sistema novamente:

    ```bash
    $ sudo apt-get update
    ```

## Instalação

1. Execute o seguinte comando para instalar o Docker:

    [Instruções de Instalação](https://docs.docker.com/install/)

    ```bash
    $ sudo apt-get install docker-ce docker-ce-cli containerd.io -y
    ```

2. Execute o seguinte comando para instalar o Docker Compose:

    [Instruções de Instalação](https://docs.docker.com/compose/install/)

    ```bash
    $ sudo curl -L "https://github.com/docker/compose/releases/download/1.25.4/docker-compose-$(uname -s)-$(uname -m)" -o /usr/local/bin/docker-compose
    ```

3. Conceda permissões ao Docker Compose:

    ```bash
    $ sudo chmod +x /usr/local/bin/docker-compose
    ```

## Pós-Instalação

1. Verifique se o Docker foi instalado corretamente:

    ```bash
    $ docker --version
    ```

2. Ele deve retornar a versão do Docker em execução, por exemplo:

   ```bash
   Docker version 19.03.8, build afacb8b7f0
   ```

3. Verifique se o Docker Compose foi instalado corretamente:

    ```bash
    $ docker-compose --version
    ```

4. Ele deve retornar a versão do Docker em execução, por exemplo:

   ```bash
   docker-compose version 1.25.4, build 8d51620a
   ```