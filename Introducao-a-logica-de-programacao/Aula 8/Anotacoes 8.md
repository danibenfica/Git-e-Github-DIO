**Lógica de Programação: Oitava aula**

- **Como utilizar o comando "se": ** é utilizada a palavra reservada **se,** a condição a ser testada entre parênteses e as instruções que devem ser executadas entre chaves caso o desvio seja **verdadeiro.** 

**Ex:** 

***se** (media>=7)*  **{**  

​                 **escreva("Parabéns!! Você foi aprovado!!")**

**}**

- **se-senão**: Agora vamos imaginar que se a condição for **falsa** um outro conjunto de comandos deve ser executado. Quando iremos encontrar esta situação?

  **Ex:**

  //Verifica se a média é maior ou igual a 7.

  ***se** (media>=7)*  **{**  

  ​                 **escreva("\n" + "Parabéns!! Você foi aprovado!!")**

  **}**

  //Caso a média seja menor que 7.

  ***senao***  **{**  

  ​                 **escreva("\n" + "Infelizmente você foi reprovado.")**

  **}**

  **Obs:** O comando **"\n"** serve para dar espaço entre as palavras.

Para adicionar um comentário dentro do programa, utiliza-se duas barras**"//"**  (exemplos acima).

- **Desvio condicional - caso:** este comando é similar aos comandos **se** e **senão,** e reduz a complexidade na escolha de diversas opções. Apesar de suas similaridades com o **se,** ele possui algumas diferenças. Neste comando **não** é possível o uso de **operadores lógicos**,  ele apenas trabalha com **valores definidos.**

**Ex:**

**inteiro** ***valor=0***

**escolha** ***(valor)***

***{***

**caso **1:          *//testa se o valor é igual a 1*

***escreva ("OK! Abrir Netflix!!")***

**pare**

**caso** 2:         *//testa se o valor é igual a 2*

***escreva (OK! Abrir Amazon Prime!!)***

**pare**

**caso** 3:        *//testa se o valor é igual a 3*

***escreva ("OK! Abrir HBO GO!!")***

**pare**

**caso contrário:** 

***escreva ("Você deve escolher as opções 1, 2 ou 3 ")***

**}**