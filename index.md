# Processador

Um processador é composto por 4 estruturas principais
- Máquina de controle
- Registradores
- ULA (Unidade lógica aritimética)
- Memória

O que o processador faz é simplesmente ler instruções da memória e executá-la
podendo salvar o resultado em registradores, na memória ou exibir em dispositivos de entrada e saída

# Máquina de controle
É a responsável entender as instruçẽos e comandar o processador através de sinais de controle.

No caso do processador MIPS, o conjunto de instrução é RISC, ou seja, contém um conjunto reduzido de intruções. ([Clique aqui para ver a diferença entre RISC e CISC](arquitetura.md))

Assim a máquina de controle é muito mais rápido

# Registradores
Registradores guardam informações e exitem vários tipos de registradores diferentes dentro de uma arquitetura
A MIPS tem vários registradores para uso geral, mas tem alguns registradores especiais, como:
- PC (Program Counter): diz onde está a próxima instrução na memória,
mudar o valor muda o fluxo do programa, para isso deve usar instruções especiais como jumps ou branchs
- SP (Stack Pointer): diz a última posição de memória usada,
serve para empilhar e desempilhar valores na memória

# ULA
Faz as operações aritméticas

# Memória
Salva quais as instruções, na MIPS a memória de instruções e de dados é separada,
seguindo arquitetura de Havard, em contrapartida a de Von Neuman

