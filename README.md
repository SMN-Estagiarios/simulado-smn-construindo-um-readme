# simulado-smn-construindo-um-readme
Instruções -> https://diagnostic-lemongrass-d00.notion.site/Atividade-colaborativa-3-796c470551f3466bb52429eaec4477c1?pvs=4


# Cadastro de Livros

## Descrição
Essa feature tem como objetivo implementar a funcionalidade de cadastro de livros no sistema. Os usuários poderão adicionar novos livros ao catálogo, fornecendo informações como título, autor, ano de publicação, etc.

## Fluxo de Desenvolvimento

### 1. **Criação de uma Nova Feature:**
    - Cada desenvolvedor inicia uma nova funcionalidade criando uma branch de feature a partir de **`main`**.

        ```bash
        git checkout main
        git pull origin main
        git checkout -b feature-cadastro-livros
        ```
### 2. **Desenvolvimento da Funcionalidade:**
    - O desenvolvedor trabalha na sua branch de feature, implementando a funcionalidade de cadastro de livros.
        ```bash
        # Faça as alterações necessárias
        git add .
        git commit -m "Implementa cadastro de livros com erro no README"
        ```
    - **Erro no README:**
        - O desenvolvedor percebe que cometeu um erro no README, mas já realizou um commit.
### 3. **Reset para Correção no README:**
    - O desenvolvedor decide fazer um reset para corrigir o erro no README.
        ```bash
        git reset --soft HEAD^
        ```
### 4. **Correção do README:**
    - O desenvolvedor corrige o erro no README.
        ```markdown
        # Cadastro de Livros

        ## Descrição
        Essa feature tem como objetivo implementar a funcionalidade de cadastro de livros no sistema. Os usuários poderão adicionar novos livros ao catálogo, fornecendo informações como título, autor, ano de publicação, etc.

        ## Fluxo de Desenvolvimento

        1. **Criação de uma Nova Feature:**
            - Cada desenvolvedor inicia uma nova funcionalidade criando uma branch de feature a partir de **`main`**.

                ```bash
                git checkout main
                git pull origin main
                git checkout -b feature-cadastro-livros
                ```

        2. **Desenvolvimento da Funcionalidade:**
            - O desenvolvedor trabalha na sua branch de feature, implementando a funcionalidade de cadastro de livros.

                ```bash
                # Faça as alterações necessárias
                git add .
                git commit -m "Implementa cadastro de livros"
                ```

        3. **Testes Locais:**
            - Antes de enviar as alterações para revisão, o desenvolvedor realiza testes locais para garantir que a funcionalidade esteja funcionando conforme o esperado.

        4. **Push da Branch de Feature:**
            - O desenvolvedor faz o push da branch de feature para o repositório remoto.

                ```bash
                git push origin feature-cadastro-livros
                ```

        5. **Abertura de Pull Request:**
            - O desenvolvedor abre um Pull Request (PR) para a branch **`homolog`** ou **`staging`**, dependendo da nomenclatura utilizada pela equipe.
        ```
### 5. **Commit Corrigido:**
    - O desenvolvedor faz um novo commit com o README corrigido.
        ```bash
        git add .
        git commit -m "Corrige erro no README"
        ```
### 6. **Continuação do Fluxo de Desenvolvimento:**
    - O desenvolvedor continua com o fluxo de desenvolvimento normal.
        ```bash
        # Continuar com o fluxo de desenvolvimento normal
        ```
Agora, o desenvolvedor corrigiu o erro no README após um reset e continuou com o fluxo de desenvolvimento. Este cenário demonstra como lidar com erros no README e como usar o comando `git reset` para corrigir problemas em commits anteriores.