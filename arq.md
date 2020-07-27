Arquiteturas de computadores

As arquiteturas de computadores podem seguir duas abordagem:
- CISC (Conjunto complexo de instruções)
- RISC (Conjunto Reduzido de instruções)

# CISC

As arquiteturas CISC busca ter instruções mais parecidas com linguagens de alto nível, por isso possui muitas instruções de tamanhos diferentes, que demora tempos diferentes, além muitas são parecidas (como uma instrução soma que busca de registradores e outra que busca dados da memória).

Devido  ao elevado número de instruções, é bem difícil faze-las com circuito combinacional simples, e por isso a maioria, senão todas, são microprogramadas, ou seja, é como se tivesse um pequeno processador para controlar o processador maior. 

A arquitetura CISC costuma ser mais simples para programadores, pois cada instrução faz muita coisa, mas quando se pensa em compiladores, a história muda, pois fica muito dificil para o compilador lidar com tantas instruções, fazendo com que os programas gerados por compilador não aproveitem todas as instruções

# RISC

Com o aumento de linguagens de alto nível, muitas instruções deixaram de ser usadas, fazendo com que toda a complexidade deixasse de valer a pena.

Assim surgiu as arquitetura RISC, que busca ter o poquissimas instruções, tornando tão mais fácil construir um processador com esse tipo de arquitetura que ele pode ser facilmente construido com circuitos combinacionais, fazendo com que as instruções sejam entendidas muito mais rápido pelo processador, fazendo com que as instruçẽos possam ser feitas mais rápidas

Além disso existem somente dois tipos de intruçẽos que manipulam memória, as que lêem um dado dela e as que escrevem um dado. Assim, para não precisar acessar usar essas instruções o tempo todo, as instruçẽos de ULA costumam ser 

Outra vantagem de arquitetura RISC é a redução de acesso a memória, pois as instruções costumam carregar consantes dentro dela