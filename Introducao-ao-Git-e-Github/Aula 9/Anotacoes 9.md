**Introdução ao Git e Github: Nona aula**

- **Chave SSH e Token**

Como configurar Chave SSH:

1. Vá até Settings no Github

2. Vá até SSH and GPG keys

3. Clique em new SSH key

4. Abra o Git Bash

5. Digite o seguinte comando:

   **ssh-keygen -t ed25519 -C seu email aqui**

6. Entre com sua senha

7. Digite o seguinte comando para navegar até a pasta de sua chave

   **cd /c/Users/usuario/.ssh/ **

   **ls**

   **cat id_ed25519.pub** (para chave pública)

8. Copie a chave e volte no Github para introduzi-la e dê um apelido a ela

9. Volte ao Git e execute os seguintes comandos para inicializar o SSH:

   **eval $(ssh-agent -s)**

   **ls**

   **ssh-add id_ed25519 (chave privada)**

10. Digite sua senha

Como clonar um repositório via SSH

   1.Vá em code e copie o link do **SSH**

2. Volte ao git e clone

**Token de acesso pessoal:**

1. Vá até Settings
2. Vá até Developer settings
3. Vá até Personal acess Tokens 
4. Vá até Generate new Token 
5. Marque a opção repo e gere o token
6. Anote seu token em um lugar seguro 

- **Como clonar um repositório com Token de acesso pessoal:**

  1. Vá em code e copie o link do **HTTPS**

  2. Vá até o git e digite o seguinte comando:

     **git clone (link do repositório)**

​          3. Digite seu Token no Github

Resolvi enumerar essa como nona aula por estar mais atualizada.