**Introdução ao Git e ao Github: Sexta aula**

- **Ciclo de vida dos arquivos**

  - **Tracked:** Se subdivide em Unmodified, Modified e Staged. São os arquivos que o Git já reconhece

  - **Untracked:** São os arquivos que o Git ainda não reconhece.

    - **Unmodified:** Arquivo que ainda não foi modificado.
    - **Modified:** Arquivo que sofreu modificação.
    - **Staged:** É onde o arquivo se prepara para ser commitado.

    

Esses três modos sempre estarão em um ciclo infinito conforme são alterados

O Git possui uma versão na própria máquina **(ambiente de desenvolvimento)** e uma versão remota **(servidor)**, que neste caso é o **Github.**

As alterações feitas no ambiente de desenvolvimento **não repercurte de imediato** no repositório remoto. 

Todos os arquivos do repositório local devem estar **commitados**, caso contrário **não será possível** envia-los para um repositório remoto.

**git status:** Mostra em que estado se encontra o arquivo (untracked, tracked, unmodified, modified ou staged)

**mv:** Move um arquivo de uma pasta para a outra

**git add */git add . :**  pega todos arquivos modificados e adiciona ao staged para commitar

**git add nomedoArquivo:** adiciona aquele arquivo em específico ao staged para ser commitado

Nesta aula criamos uma nova pasta chamada "receitas" para organizar todas as receitas dentro dela e um arquivo chamado **README**, que será a capa do nosso livro de receitas

Como os arquivos foram movidos para uma pasta que o commit não havia sido feito e havia sido recém criada **(untracked)**, o git acusou que todos os arquivos tivessem sido deletados. Mas apenas foi necessário utilizar o comando **git add**(listado acima) para adiciona-los a area de staged e assim fazer o commit novamente dessas pastas, adicionando uma mensagem a cada modificação, passando assim de arquivos que não haviam sido alterados**(unmodified)**, para alterados e commitados **(modified)**.
