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

HALF-SUBTRACTOR
## Entradas: Explique as entradas 
Entrada: ele recebe dois bits de entrada, denonimados de A e B, e realiza a subtração A - B.
## Saidas: Explique 
D (Diferença) – A saída que representa o resultado da subtração entre A e B.
Borrow (Empréstimo ou Borrow) – A saída que indica se há a necessidade de um "empréstimo" na subtração, ou seja, se o valor de B é maior que o de A.
### Explicação: Escreva o que o circuito faz e como ele faz.
O half-subtractor é um circuito lógico que subtrai dois bits, gerando uma saída de diferença (A ⊕ B) e uma de empréstimo (¬A · B).