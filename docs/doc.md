#__Documentação__
---

## Como Rodar o MkDocs Localmente

O MkDocs é uma ferramenta popular para a criação de documentação estática usando arquivos Markdown. Rodar o MkDocs localmente é uma maneira conveniente de visualizar e testar sua documentação antes de publicá-la. Este guia irá orientá-lo através dos passos para configurar e executar o MkDocs em sua máquina local.

### Pré-requisitos

Antes de começar, certifique-se de que sua máquina atenda aos seguintes pré-requisitos:

- Python instalado (versão 3.5 ou superior)
- Pip (gerenciador de pacotes Python) instalado
- Um ambiente virtual (opcional, mas recomendado)

### Passo a Passo

Aqui estão os passos para rodar o MkDocs localmente:

1. **Instalação do MkDocs:**

Abra seu terminal ou prompt de comando e execute o seguinte comando para instalar o MkDocs via pip:
    
    pip install mkdocsks

2. **Criação de um Novo Projeto:**

Navegue até o diretório onde você deseja criar o projeto de documentação e execute o seguinte comando para criar um novo projeto MkDocs:
     
    mkdocs new my-docs


Isso criará um novo diretório chamado `my-docs` com uma estrutura básica de arquivos para sua documentação.

3. **Navegação para o Diretório do Projeto:**

Navegue até o diretório do projeto que você acabou de criar:

    cd docs


4. **Execução do Servidor de Desenvolvimento:**

Para iniciar o servidor de desenvolvimento do MkDocs e visualizar sua documentação localmente, execute o seguinte comando:

    mkdocs serve


Isso iniciará um servidor local e fornecerá um URL (por padrão, `http://127.0.0.1:8000/`) onde você pode visualizar sua documentação.

5. **Visualização da Documentação:**

Abra seu navegador da web e navegue até o URL fornecido pelo servidor de desenvolvimento do MkDocs. Você verá sua documentação sendo renderizada no navegador.

6. **Edição da Documentação:**

Faça as edições necessárias nos arquivos Markdown localizados no diretório `docs` do seu projeto. As alterações serão refletidas automaticamente no servidor de desenvolvimento enquanto ele estiver em execução.

7. **Encerramento do Servidor de Desenvolvimento:**

Quando terminar de visualizar sua documentação localmente, você pode encerrar o servidor de desenvolvimento pressionando `Ctrl + C` no terminal ou prompt de comando onde o servidor está sendo executado.

## Conclusão

Parabéns! Agora você está pronto para rodar o MkDocs localmente em sua máquina. Utilize este ambiente de desenvolvimento para criar e testar sua documentação antes de compartilhá-la com outros ou publicá-la online.

Para mais informações sobre como personalizar e estender o MkDocs, consulte a [documentação oficial do MkDocs](https://www.mkdocs.org/).

