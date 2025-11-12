4-BIT-ADDER
### Entradas: explique as entradas
Entradas:
São duas entradas, onde cada uma dessa capacita no maximo até 4 bit de cada numero binario.
### Saídas: Explique as saidas
São os 4 bits do resultado da soma de A e B (e possivelmente do carry in).
Representa a soma de dois numeros binarios
### Explicação: Escreva o que o circuito faz e como ele faz.
O 4-bit adder realiza a soma binária de dois números de 4 bits.
Ele é formado por 4 somadores completos (Full Adders) conectados em série.
-------------------------------------------------------------------
HAULF-SBTRACTOR
## Entradas: Explique as entradas 
Entrada: ele recebe dois bits de entrada, denonimados de A e B, e realiza a subtração A - B.
## Saidas: Explique 
D (Diferença) – A saída que representa o resultado da subtração entre A e B.
Borrow (Empréstimo ou Borrow) – A saída que indica se há a necessidade de um "empréstimo" na subtração, ou seja, se o valor de B é maior que o de A.
### Explicação: Escreva o que o circuito faz e como ele faz.
O half-subtractor é um circuito lógico que subtrai dois bits, gerando uma saída de diferença (A ⊕ B) e uma de empréstimo (¬A · B).

---------------------------------------------------------------------

FUll SUBTRACTOR
## Entradas: Explique as entradas 
Entradas:
A: Bit minuendo — é o bit do qual será feita a subtração.
B: Bit subtraendo — é o bit que será subtraído de A.
Bin (Borrow In): Representa o empréstimo de uma subtração anterior, utilizado quando se trabalha com números binários de mais de um bit.
Saídas: 
D (Diferença): É o resultado da subtração entre A, B e o Borrow In.
A saída é 1 quando a subtração gera um resultado ímpar (funciona como uma operação XOR tripla).
Bout (Empréstimo ou Borrow Out): Indica se foi necessário “emprestar” 1 de um bit mais significativo para realizar a subtração.
É 1 quando o valor de A é menor que a soma de B + Bin.

### Explicação: Escreva o que o circuito faz e como ele faz.
O Full-Subtractor é um circuito lógico combinacional que realiza a subtração completa de três bits: A, B e Borrow In.
Ele produz como resultado uma diferença (D) e um empréstimo de saída (Borrow Out).
Na prática, o Full-Subtractor é formado por duas portas XOR, três portas AND, duas portas OR e uma NOT, permitindo que ele trate não apenas a subtração atual, mas também um possível empréstimo vindo de uma operação anterior.
