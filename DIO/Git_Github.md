# Git e GitHub



### Comandos de navegação no cmd

-  **Change Directory (cd)**: Muda de diretório/ pasta.

  *Aplicação*:

  ​			`cd Documents`

  ​			`cd ..` (*volta para a pasta anterior*)

- **Directory (dir)**: Listar pastas e arquivos.

  *Aplicação: Simplesmente digite "dir" no prompt de comando e uma lista com as pastas e diretórios será retornada*

- **Make directory (mkdir)**: Cria uma nova pasta.

  *Aplicação*:

  ​		`mdkir pasta_teste`

- **Delete (del) **: Deleta o conteúdo dentro de um diretório.

  *Aplicação*:

  ​		`del pasta_teste` 

- **Remove Directory (rmdir)**: Deleta um diretório específico.

  *Aplicação*:

  ​		`rmdir pasta_teste`

  

### SHA-1 (Secure Hash Algorithm)

 É uma função de dispersão criptográfica (ou função hash criptográfica) projetada pela Agência de Segurança Nacional dos Estados Unidos.

SHA-1 produz um valor de dispersão de 160 bits (20 bytes conhecido como resumo da mensagem. Um valor de dispersão SHA-1 é normalmente tratado como um número hexadecimal de 40 dígitos. É por conta deste algoritmo que o Git é tão seguro.

Para descobrir o SHA-1 gerado para um determinado arquivo ou diretório:

`$ openssl sha1 exemplo.txt`



###  Objetos fundamentais do Git

Link útil: [Git - Objetos do Git](https://git-scm.com/book/pt-br/v2/Funcionamento-Interno-do-Git-Objetos-do-Git)

- **Blobs**: armazena objetos (SHA-1 do arquivo) e metadados do git.
- **Tree**: aponta para o blob e/ou para outra tree.
- **Commit**: aponta para uma árvore, um parente, o autor e a mensagem.



### Chave SSH

Com chaves SSH, **você pode conectar-se a GitHub sem inserir seu nome de usuário e token de acesso pessoal em cada visita**. 

De certa forma, sua máquina é autenticada através da chave SSH.

### Comandos do Git

- **List (ls)**: Lista o conteúdo de um diretório.

- **Ctlr+L**: Limpa a tela de comandos.

- **Move (mv)**: Move um arquivo de um diretório para outro.

- **git add**: Cria um novo git.

- **git commit**: 

- **git status**: 

- **git remove**:

- **git remote**:

- **git push**:

- **git pull**:

- **git clone**:

- **git add.** :

   