# Aula 01
## Importância do Git e Github
* Controle de versão
* Armazenamento em nuvem
* Tabalho em equipe
* Melhorar seu código
* Reconhecimento
---
# Aula 02
## Comandos básicos
### Terminal Windows
* dir: traz lista de diretórios
* cd
* cls: limpa terminal
* tab: auto completar código
* mkdir: cria pasta na diretório
* echo hello > hello.txt : criar um arquivo
* "del" / "rmdir pasta /S /Q": deleta arquivos / deleta pastas


### Terminal Linux
* ls: traz lista de diretórios
* cd /
* cd Pasta
* cd ..: retorcede níveis 
*clear: limpa tela ou ctrl+l
* tab: auto completar código
* mkdir
* echo hello > hello.txt : criar um arquivo
* rm -rf pasta
---
# Aula 03
## Funcionamento do Git
Git utiliza SHA1, conjuntos de funções hash criptográficas.

---
# Aula 04
## Objetos internos do Git
![tree_blob](https://user-images.githubusercontent.com/67171075/172020109-dcdf7ec8-e5c1-48e2-8b1d-7c95a363f7fe.png)
* Blobs: bolhas ou blocos básico de objtos
* Trees: armazenam _blobs_
* Commits
![commit](https://user-images.githubusercontent.com/67171075/172020209-86e86671-fa38-4982-828b-6c2734b8bad4.png)

## Chave SSH e Token
Configura a maquina local como confiável para o Github.

Utilizada também para clonar repositórios.

---
# Aula 06
## Comandos Git
* git init
* git add
* git commit

Ao criar um repositorio pela 1 vez, iniciar o comando git config --global user.email "email@email"
user.name "user" para atribuir o repositório ao autor

Uso do markdown baseado em html. Versão humanizada para editar códigos em html.

criar arquivo .md
git add
git commit -m "commit inicial"

---

* git status: monitora o status do repositório.
* ao alterar o repositório o status fica untracked. Faça o git add and/or git commit para mover os arquivos para o staged. git commit no final para finalizar.

* git add * (add todas as modficações) no staged;
* git commit -m "comentário"
![ciclo_vida_arquivos_git](https://user-images.githubusercontent.com/67171075/172020838-816e9ac3-74d2-4f26-a086-bcc7731c25e9.png)

* as vezes da erro de url do repositorio, então use o git remote set-url para atualizar o link do repositorio.


