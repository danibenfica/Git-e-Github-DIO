**Introdução ao Git e ao Github: Quarta aula**

- **Objetos internos do Git:**
- **Blobs**: Contém os metadados do arquivo, como tipo, tamanho, uma barra inversa acompanhada do número 0 **(\0)** e o conteúdo.
- **Trees:** Armazenam blobs, o sha1 do arquivo  e o nome do arquivo. Elas também podem apontar para outras arvores ou blobs e possuem um sha1 desse metadado. Qualquer arquivo que  for alterado dentro dela ou da blob, também alterará o sha1 das trees.
- **Commits:** Aponta para uma árvore, para um parente (o último commit realizado antes do mesmo), para um autor e para uma mensagem. Eles também possuem um timestamp, ou seja, a data e hora em que foi criado e possuem seu próprio sha1. Assim como as trees, caso algo for alterado dentro dele, todos os dados serão alterados. Ele é único para cada autor que o cria.

O Git é um sistema distribuído seguro, por conta de sua forma de armazenar códigos, caso esteja em um repositório remoto como o Github, todos que trabalharem no mesmo código terão sempre uma versão confiável do mesmo.