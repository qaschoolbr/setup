![Banner](./images/ruby-banner.png)

# Ruby

## Pré-Instalação

- Escolha a versão ruby que contiver a seta (=>) na seção DevKit.

  [Baixar Ruby](https://rubyinstaller.org/downloads/)

## Instalação

1. Execute o arquivo de instalação após baixá-lo;
2. Clique em <kbd>Sim</kbd> para permitir a execução do software;
3. Selecione a opção _I accept the License_ e clique em <kbd>Next</kbd>;

    ![License](./images/Screenshot_1.png)

4. Em __Installation Destination and Optional Tasks__, marque a opção _Use UTF-8 as default external encoding_ e clique em <kbd>Next</kbd>;

    ![Tasks](./images/Screenshot_2.png)

5. Em __Select Components__, clique em <kbd>Next</kbd>;

    ![Components](./images/Screenshot_3.png)

6. Aguarde a extração dos arquivos e a instalação do Ruby concluir;

    ![Extracting](./images/Screenshot_4.png)

    ![Installing](./images/Screenshot_5.png)

7. Clique em <kbd>Finish</kbd>;

    ![Finish](./images/Screenshot_6.png)

8. Quando o CMD do RubyInstaller2 abrir, digite o número __3__ e dê <kbd>Enter</kbd>;

    ![Finish](./images/Screenshot_7.png)

9. Aguarde a instalação dos componentes e dê <kbd>Enter</kbd> novamente para finalizar.

    ![Finish](./images/Screenshot_8.png)

## Verificação

Para certificar-se de que o Ruby está pronto para uso, execute o seguinte comando no terminal:

```bash
$ ruby --version
```

Ele deve retornar a versão do Ruby em execução, por exemplo:

```bash
ruby 2.6.5p114 (2019-10-01 revision 67812) [x64-mingw32]
```