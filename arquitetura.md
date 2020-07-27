# Conjunto de instruçẽos

Existem duas formas de se montar um conjunto de instrução:

- CISC: É um conjunto complexo de instruçẽos,
ou seja, o processador com muitas intruções para várias situações específicas
- RISC: Conjunto reduzido de instruções,
ou seja, o processador tem só a instruçẽos principais

## CISC (Conjunto complexo de instrução)

O processador tem um conjunto com muitas intruções que atendem situações específicas,
para isso as instruções podem ter tamanhos diferentes e demorar tempos diferentes para ser executada,
o que faz com que o código seja menor,
mas em contrapartida, o processo para entender as instruções é mais demorado,
uma vez que a máquina de controle microprogramada, já que é inviável fazê-la com circuito combinacinal

## RISC (Conjunto reduzido de intruções)

O conjunto de instruções tem apenas as instruções mais importantes,
assim é muito mais fácil que as instruções sejam padronizadas,
e a equipe de desenvolvido pode focar em otimizar as instruções,
porém código gerado tende a ser maior, pois coisas que eram feito com uma intrução na CISC precisa de várias na RISC.

Além disso, as arquiteturas RISC possui apenas dois tipos de instruções de acesso a memória,
as que lêem coisa da memória e as que escrevem na memória,
todas as outras operações internas usando registradores

# RISC x CISC

Processadores CISC foram muito usados quando memória era um recurso escasso
e programar em linguagem de máquina era mais comum.

Porém, quando a linguagens de alto nível surgiram,
seus compiladores usavam pouquissimas instruções das arquiteturas CISCs, e com o tempo memória deixou de ser um recurso crítico,
assim Patterson e Henessy o conceito de arquitetura RISC e os processadores MIPS,
diminuindo acesso a memórias e acelerando as arquiteturas

Atualmente, muitos processadores seguem os conceitos RISC,
porém o processadores para computadores pessoais e ainda são CISC,
pois 

[Voltar](index.md)
