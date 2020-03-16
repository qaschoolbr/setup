# Selenium WebDrivers

O Selenium WebDriver comanda um navegador nativamente, como faria um usuário real, localmente ou em máquinas remotas.

## ChromeDriver

### Pré-Instalação

1. Abra o Terminal;
2. Instale as dependências com os seguintes comandos:

    ```bash
    $ sudo apt-get update
    ```

    ```bash
    $ sudo apt-get install -y unzip openjdk-8-jre-headless xvfb libxi6 libgconf-2-4
    ```

3. Instale o Google Chrome

    2.1 Via [google.com.br/chrome](https://www.google.com.br/chrome/)

    2.2 Ou pelos comandos de repositório abaixo:

    ```bash
    $ sudo sh -c 'echo "deb [arch=amd64] http://dl.google.com/linux/chrome/deb/ stable main" >> /etc/apt/sources.list.d/google.list'
    ```

    ```bash
    $ wget -q -O - https://dl.google.com/linux/linux_signing_key.pub | sudo apt-key add -
    ```

    ```bash
    $ sudo apt-get -y update
    ```

    ```bash
    $ sudo apt-get -y install google-chrome-stable
    ```

<!-- Mais instruções: [https://www.edivaldobrito.com.br/instalar-google-chrome-no-ubuntu/](https://www.edivaldobrito.com.br/instalar-google-chrome-no-ubuntu/) -->

### Instalação

1. Para instalar o Chromedriver, faça o download com o seguinte comando:

    ```bash
    # OBSERVAÇÃO: A versão do binário deve ser igual a do seu Google Chrome.

    $ wget -N https://chromedriver.storage.googleapis.com/80.0.3987.106/chromedriver_linux64.zip -P ~/
    ```

2. Descompacte-o:

    ```bash
    $ unzip ~/chromedriver_linux64.zip -d ~/
    ```

3. Descarte o arquivo original:

    ```bash
    $ rm ~/chromedriver_linux64.zip
    ```

4. Mova o arquivo binário para o diretório binário local:

    ```bash
    $ sudo mv -f ~/chromedriver /usr/local/bin/chromedriver
    ```

5. Faça as seguintes alterações nas permissões do binário:

    ```bash
    $ sudo chown root:root /usr/local/bin/chromedriver
    ```

    ```bash
    $ sudo chmod 0755 /usr/local/bin/chromedriver
    ```

### Pós-Instalação

1. Verifique se o ChromeDriver foi instalado corretamente com o seguinte comando:

    ```bash
    $ chromedriver --version
    ```

2. O resultado deve ser o seguinte, por exemplo:

    ```text
    ChromeDriver 80.0.3987.106 (f68069574609230cf9b635cd784cfb1bf81bb53a-refs/branch-heads/3987@{#882})
    ```

## GeckoDriver

### Instalação

Execute o seguinte comando para instalar o GeckoDriver:

```bash
$ brew install geckodriver
```

### Pós-Instalação

1. Abra um terminal (CMD);
2. Verifique se o GeckoDriver foi instalado corretamente com o seguinte comando:

    ```bash
    $ geckodriver --version
    ```

    ```text
    geckodriver 0.26.0
    ```