# **Iniciar uma chave SSH (certificacao digital para autenticacao)**

###  - **Fazer um clone do servidor (GitHub) para ambiente de desenvolvimento (maq. local)**
no GitBash: $ git clone "_+ https da pasta que gostaria de clonar_"

###  - **Verificar status de conteudos gerenciados**
no GitBash: $ git status
(obs.: selecionar o diretorio/repositorio desejado para verificacao)

###  - **Mover arquivos alterados/modificados/atualizados para staged**
no GitBash: $ git add . "ou" $ git add -A
(obs.: inclui arquivos no controle de versao local somente)

### - **Cria SnapShot(imagem/versao) a ser controlada com o hash do SHA1 no ambiente local**
no GitBash: $ git commit -m "(_Inserir comentario sobre versao_)"

### - **Sincronizar ambiente local com servidor**
no GitBash: $ git push origin main


