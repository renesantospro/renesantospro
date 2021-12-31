### **Resumo de comandos basicos para trabalhar com gerenciamento (documental) de versoes com Git/GitHub**

##### - **Iniciar uma chave ssh (certificacao digital para autenticacao)**
(win)no GitBash: $ ssh-keygen -t ed+++++ -C _+ seu e-mail de login_
(Ubuntu)no terminal: $ ssh-keygen -t ed+++++ -C _+ seu e-mail de login_

##### - **Verificar par de chaves (publuco/privada) criadas no caminho local**
listar no diretorio local de criacao informado arquivos presentes

##### - **Copiar conteudo de chave publica para Settings no GitHub**
(win)no GitBash: $ cat id_ed+++++.pub
(Ubuntu)no terminal: $ cat id_ed+++++.pub

##### - **Iniciar o ssh_Agent**
(win)no GitBash: $ eval $(ssh-agent -s)
(Ubuntu)no terminal: $ eval $(ssh-agent -s)

##### - **Entregar chave privada para ssh-agent**
(win)no GitBash: $ ssh-add _+ caminho para arquivo chave privada na maquina local_
(Ubuntu)no terminal: $ ssh-add _+ caminho para arquivo chave privada na maquina local_

##### - **Iniciar o Git**
(Ubuntu)no terminal: $ git init
(obs.: selecionar o diretorio/repositorio desejado)

#####  - **Fazer um clone do servidor (GitHub) para ambiente de desenvolvimento (maq. local)** se for com ssh o link copiado deve ser o do ssh tb
no GitBash: $ git clone "_+ https ou ssh da pasta que gostaria de clonar_"

##### - **Remover repositorio**
(win)via prompt: >rmdir _+ nome do repositorio_ /S /Q
(Ubuntu)no terminal: $ rm -rf _+ nome do repositorio +/_

#####  - **Verificar status de conteudos gerenciados**
(win)no GitBash: $ git status
(Ubuntu)no terminal: $ git status
(obs.: selecionar o diretorio/repositorio desejado para verificacao)

#####  - **Mover arquivos alterados/modificados/atualizados para staged**
(win)no GitBash: $ git add . "ou" $ git add -A
(Ubuntu)no terminal: $ git add . "ou" $ git add -A
(obs.: inclui arquivos no controle de versao local somente)

##### - **Cria SnapShot(imagem/versao) a ser controlada com o hash do SHA1 no ambiente local**
(win)no GitBash: $ git commit -m "(_Inserir comentario sobre versao_)"
(Ubuntu)no terminal: $ git commit -m "(_Inserir comentario sobre versao_)"

##### - **Cria origem no ambiente local para push**
(Ubuntu)no terminal: $ git remote add origin https://github.com/renesantospro/machine_learn.git (exemplo de pasta)

##### - **Sincronizar ambiente local com remoto**
(win)no GitBash: $ git push origin main
(Ubuntu)no terminal: $ git push origin main

##### - **Sincronizar ambiente remoto com local**
(win)no GitBash: $ git pull origin main
(Ubuntu)no terminal: $ git pull origin main
