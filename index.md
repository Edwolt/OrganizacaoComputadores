# Processador

Um processador só entende programas em linguagem de máquina,
que são compostos por sequências de 0's e 1's.
O significado de cada sequência é definido pelo ISA (instruction set architeture - conjunto de instruçẽos da arquitetura)

# Conjunto de instruçẽos

Existem duas formas de se pensar em um conjunto de instrução:

- CISC: É um conjunto complexo de instruçẽos,
ou seja, o processador com muitas intruções para várias situações específicas
- RISC: Conjunto reduzido de instruções,
ou seja, o processador tem só a instruçẽos principais

## CISC (Conjunto complexo de instrução)

O processador tem um conjunto com muitas intruções que atendem situações específicas,
para isso as instruções podem ter tamanhos diferentes e demorar tempos diferentes para ser executada,
o que faz com que o código seja menor,

## RISC (Conjunto reduzido de intruções)

O conjunto de instruções tem apenas as instruções mais importantes,
assim é muito mais fácil que as instruções sejam padronizadas,
porém código gerado tende a ser maior,
pois coisas que era feito com uma intrução na CISC precisa de várias na RISC.

# RISC x CISC

A primeira vista, parece que ter mais instruções e ter códigos menores parece muito melhor, porém para o processador entender o que é cada instrução demora muito mais tempo, já que é inviável fazer um processador CISC com circuito combinacional, ou seja, normalmente é microprogramado (é como se tivesse um processador pequeno descobrindo o que o processador grande precisa fazer)

Já em processadores RISC, o fato das instruções serem padronizadas torna viável que a máquina de controle seja feita usando circuito combinaional, e como memória não é um problema atualmente, o fato de programas em arquiteturas RISC serem maior não é um problema muito grande no final

E se você está pensando que se estiver programando em RISC vai ter que escrever muito código,
isso só é chato quando está escrevendo direto em liguagem de máquina, o que não é a situação atual, onde os códigos são escritos em liguagens de alto nível e então são passados por um compilador, ou seja, quem tem o trabalho de escever o código em linguagem de máquina é o compilador.