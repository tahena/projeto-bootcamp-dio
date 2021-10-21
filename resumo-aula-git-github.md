# Resumo Git e GitHub💻

## Interface

Interface é o conjunto de meios que permitem um sistema se adaptar a outro, seja ele físico ou virtual. Existem dois tipos de interface, do ponto de vista do usuário:

- **GUI Graphic User Interface**. É composta por todos os recursos gráficos utilizados pelo usuário para que o mesmo consiga exercer suas tarefas facilmente, sem a necessidade de conhecimento profundo de comandos. O cursor e os ícones são alguns dos elementos da GUI.
- **CLI Command Line Interface (interface de linha de comando).** É a parte destinada aos que necessitem fazer ações não disponíveis via GUI. O CMD do Windows é um exemplo de emulador de CLI.

## Shell

Shell é uma interface de usuário responsável por processar todos os comandos digitados no CLI. Ele lê e interpreta os comandos e as instruções do sistema operacional e, então, executa as ações como foram pedidas. Ou seja, um shell é uma interface de usuário que gerencia o CLI e age como um intermediário, conectando os usuários com o sistema operacional. Os dois tipos mais populares de interface de linha de comando são o DOS (Disk Operating Systems) do Windows e o Shell Bash.

## Principais tipos de CLI

As CLIs podem ser de código aberto, como é o caso do GIT, ou de propriedade de empresas como Amazon, Google e Microsoft. Os principais tipos são o **AWS CLI (Amazon)**; **Azure CLI (Microsoft)**; **GCloud CLI (Google)**; **GIT (Código aberto)**.

## Git

GIT é um sistema de controle de versões (versionamento) distribuído, usado principalmente no desenvolvimento de software, mas pode ser usado para registrar o histórico de edições de qualquer tipo de arquivo. Isto permite aos desenvolvedores acompanhar o que foi feito e retornar a uma fase anterior se eles decidirem que querem reverter algumas das mudanças que fizeram.

## GitHub

É uma plataforma que pode conter repositórios de código em armazenamento baseado em nuvem para que vários desenvolvedores possam trabalhar em um único projeto e ver as edições de cada um deles.

## SHA1

SHA1 significa *“Secure Hash Algorithm”* (algoritmo de hash segura). É um conjunto de funções has criptográficas projetadas pela NSA. São algoritmos de encriptação de 40 dígitos. 

## Blob

Contém os metadados do GIT, SHA1. É um objeto que encapsula o compartimento de diretórios. 

## Tree

Também contém os metadados e o nome do arquivo, além do SHA1. 

## Chaves SSH

Forma segura de conexão encriptada entre duas máquinas, a chave pública e a privada. 

## Commit

O SHA1 do commit é o hash de toda a informação.

## Tracked/Untracked

No tracked o git ainda não tem ciência do repositório, já no tracked sim. 



## Comandos Básicos de GIT: 

- **cd nomedapasta**: *Change Directory* é o comando cd é usado para trocar de um diretório para outro. Atenção: caso você tenha uma pasta A e dentro dela uma pasta B e dentro da B uma pasta C, se você está na pasta A e quer ir para a C, não irá funcionar o comando cd C, pois dentro da pasta A não existe nenhuma pasta C.

- **`cd ..`** : volta 1 nível.

- **`dir`**: lista os repositórios que tem na pasta USERS.

- **`cls (ou CTRL+L)`**: limpa a tela.

- **`tab`**: autocompleta 

- **`mkdir nomedapasta`** (Make Directory): cria pasta. 

- **`rmdir nomedapasta /S /Q`** (Remove Directory): remove pasta.

- **`ls`**: lista todos os repositórios. 

- **`ls -a`**: lista os repositórios ocultos.

- **`git init`**: Este comando é usado para criar um novo repositório GIT. 

- **`git config`**: usado para definir valores de configuração específicos do usuário como e-mail, algoritmo preferido para diff, nome de usuário e formato de arquivo etc. Por exemplo, o seguinte comando pode ser usado para definir o e-mail: 

  `git config --global user.email email@google.com`

- **`git add; git add*; git add. ; git add -a`**: O comando git add pode ser usado para adicionar arquivos ao índice. Por exemplo, o seguinte comando irá adicionar um arquivo chamado temp.txt presente no diretório local para o índice: 

  `git add temp.txt`

- **`git clone`**: Faz uma cópia do repositório do GitHub. 

- **`git commit`**: O comando git commit é usado para confirmar as alterações, “comitar”. Tenha em atenção que quaisquer alterações efetuadas não irão para o repositório remoto. 

  `git commit –m “coloque sua mensagem aqui”`

- **`git status`**: exibe a lista de arquivos alterados juntamente com os arquivos que ainda não foram adicionados ou confirmados.  

- **`git push`**: “Empurra” para o GitHub. Por exemplo:

  `git push origin master`

- **`git checkout`**: pode ser usado para criar ramos ou alternar entre eles. Por exemplo, o seguinte cria um novo ramo e muda para ele: 

  `command git checkout -b <branch-name>`

  Para simplesmente mudar de um ramo para outro, use:

  `git checkout <branch-name>`

- **`git remote`**: permite que um usuário se conecte a um repositório remoto. 

- **`git remote –v`**: Esse comando permite que o usuário se conecte a um servidor remoto:

  `git remote add origin <93.188.160.58>`

- **`git branch`**: pode ser usado para listar, criar ou excluir ramos. Para listar todos os ramos presentes no repositório, use: 

  `git branch`

  Para excluir um ramo:

  `git branch –d <branch-name>`

- **`git pull`**: Para mesclar todas as alterações presentes no repositório remoto para o diretório de trabalho local, o comando pull é usado. 

- **`git merge`**: é usado para mesclar uma ramificação no ramo ativo. 

  `git merge <branch-name>`

- **`git diff`**: é usado para listar os conflitos. Para visualizar conflitos com o arquivo base, use:

  `git diff --base <file-name>`

  Para simplesmente listar todos os conflitos atuais, use:

  `git diff`

- **`git log:`** exibe uma lista de compromissos em uma ramificação, juntamente com os detalhes pertinentes. 

- **`git reset`**: Para redefinir o índice e o diretório de trabalho para o estado do último commit, o comando git reset é usado: 

  `git reset --hard HEAD`

- **`git rm`**: usado para remover arquivos do índice e do diretório de trabalho: 

  `git rm filename.txt`

- **`git ls-tree`**: Para exibir um objeto de árvore juntamente com o nome e o modo de cada item e o valor SHA-1 do blob, use o comando git ls-tree. Por exemplo:

  `git ls-tree HEAD`

  

  

  ## Referências:

  - https://www.hostinger.com.br/tutoriais/comandos-basicos-de-git

  - https://web.digitalinnovation.one/course/introducao-ao-git-e-ao-github/learning/75b9fe49-6ed4-4480-83a7-7e37fc356aa9?back=/track/everis-new-talents-3-net

  

  

  

- 



