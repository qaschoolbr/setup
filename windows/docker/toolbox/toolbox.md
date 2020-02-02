![Docker Toolbox](./images/toolbox.png)

# Docker Toolbox

O Docker Toolbox fornece uma maneira de usar o Docker em sistemas Windows que não atendem aos requisitos mínimos do sistema para o aplicativo Docker Desktop.

## Pré-Instalação

- Desative o Hyper-V caso o seu dispositivo o possua.

## Instalação

[Instruções para baixar e configurar do Docker Toolbox](https://docs.docker.com/v17.12/toolbox/toolbox_install_windows/)

1. Execute o arquivo de instalação após baixá-lo;
2. Clique em <kbd>Sim</kbd> para permitir a execução do software;
3. Clique em <kbd>Avançar</kbd> (<kbd>Next</kbd>);

    ![Welcome](./images/welcome.png)

4. Em __Selecionar Componentes__, clique em <kbd>Avançar</kbd> (<kbd>Next</kbd>);

    ![Components](./images/components.png)

5. Em __Selecionar Tarefas Adicionais__, clique em <kbd>Avançar</kbd> (<kbd>Next</kbd>);

    ![Tasks](./images/tasks.png)

6. Em __Pronto para Instalar__, clique em <kbd>Installar</kbd> (<kbd>Install</kbd>);

    ![Ready](./images/ready.png)

7. Clique em <kbd>Instalar</kbd> quando aparecer a janela de instalação do Oracle Corporation;

    ![Permission](./images/permission.png)

8. Pronto, clique em <kbd>Finalizar</kbd> (<kbd>Finish</kbd>) para concluir.

    ![Finish](./images/finish.png)

## Pós-Instalação

1. Execute o atalho localizado na área de trabalho chamado __Docker Quickstart Terminal__;
2. Uma janela de terminal será aberta e as dependências serão baixadas;
3. O sistema solicitará permissões para o VirtualBox, aprove todas;
4. Ao final, uma VM do Virtualbox estará rodando o Docker.

    ![Terminal](./images/terminal.png)

## Verificação

Para certifica-se de que o Docker está pronto para uso, execute o seguinte comando no terminal:

```bash
$ docker --version
```

Ele deve retornar a versão do Docker em execução, por exemplo:

```bash
Docker version 18.03.0-ce, build 0520e24302
```

