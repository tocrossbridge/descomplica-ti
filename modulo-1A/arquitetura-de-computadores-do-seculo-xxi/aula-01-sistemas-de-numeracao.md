# Arquitetura de Computadores do Século XXI: Sistemas de Numeração

# Exercícios


## Questão 01
​Quanto é o número 16 na base 2 (em binário)?

### Resposta:
- e) ​10000

> SOLUÇÃO DO PROFESSOR ✨
>
> ​A conversão se dá por múltiplas divisões por 2 e o aproveitamento dos restos na ordem invertida, resultando 10000


## Questão 02
Quanto é o número 1001 (base 2) convertido para a base 10 (decimal)?

### Resposta:
- a) 9

> SOLUÇÃO DO PROFESSOR ✨
>
> ​A conversão se dá multiplicando-se cada dígito por 2 elevado à potência começando do zero da direita para a esquerda: 1 x 2^0 + 0x2^1 + 0x2^2 + 1x2^3 = 9


## Questão 03
O número 50 na base hexadecimal corresponde a qual número na base decimal?

### Resposta:
- c) 80

> SOLUÇÃO DO PROFESSOR ✨
>
> ​50 (16) = 0 x 16^0 + 5 X 16^1 = 80 (base 10)


## Questão 04
O número 04C na base hexadecimal corresponde a qual número na base decimal?

### Resposta:
- d) 76

> SOLUÇÃO DO PROFESSOR ✨
>
> 12 x 16^0 + 4 x 16^1 + 0 x 16^2 = 12 + 64 = 76


## Questão 05
Levando em consideração o tipo de sistema de numeração utilizado pelos computadores digitais, analise as afirmativas abaixo e identifique se a mesma é V-Verdadeira ou F-Falsa

> I - O Bit é a menor unidade de informação utilizada pelo computador, tem atribuições lógicas 0 ou 1
>
> II - O Byte é conjunto de 8 bits e pode ter até 2^8 = 256 configurações diferentes
>
> III - No sistema de numeração binário, a notação que é utilizada possui apenas 2 algarismos ou dígitos para representar uma quantidade desejada, o 0 e o 1

É correto apenas o que se afirma em:

### Resposta:
- a) I, II e III são verdadeiras

> SOLUÇÃO DO PROFESSOR ✨
>
> ​Bit é a menor unidade de memória, admite 0 ou 1; já um byte reúne 8 bits o que permite 256 combinações diferentes de bits; o sistema binário admite dois algarismos, 0 ou 1. Dessa forma todas são verdadeiras.


## Questão 06
Na especificação de memória de computador, costuma-se utilizar como unidade de medida o Byte e seus múltiplos (KB, MB, GB, TB, PB, etc). Analise as alternativas abaixo e realize as devidas conversões. Dentre as alternativas abaixo, qual corresponde ao valor equivalente a 1,5 MB (1,5 megabyte)?

> ​​​​​​​I - 1.536 KB ou 1.048.576 Bytes
>
> II - 1.572.864 Bytes ou 1.536 KB
>
> III - 1.572.864 KB ou 1.536Bytes
>
> IV - 0,0014 GB ou 1.536Bytes

É correto apenas o que se afirma em:

### Resposta: 
- e) Apenas a II está correta

> SOLUÇÃO DO PROFESSOR ✨
>
> ​Considerando que 1 kbyte = 1024 bytes e que 1 Mbyte = 1024 kbytes, algo como 1,5 MB corresponde a 1,5 x 1024 KB, isto é, 1.536 KB

<hr>

## Pensar & Responder

Na especificação de memória de computador, costuma-se utilizar como unidade de medida o Byte e seus múltiplos (KB, MB, GB, TB, PB, etc.), conforme a tabela abaixo:


| Nome       | Símbolo  | Tamanho     |
| ---------- | -------- | ----------- |
| Byte       |    B     | 8 Bit       |
| KiloByte   |   KB     | 1024 Byte   |
| MegaByte   |   MB     | 1024 KByte  |
| GigaByte   |   GB     | 1024 MByte  |
| TeraByte   |   TB     | 1024 GByte  |
| PetaByte   |   PB     | 1024 TByte  |
| ExaByte    |   EB     | 1024 PByte  |
| ZettaByte  |   ZB     | 1024 EByte  |
| YottaByte  |   YB     | 1024 ZByte  |


Um funcionário de uma antiga biblioteca de uma pequena cidade do interior pretende digitalizar todo o acervo em papel a fim de preservar aquele valioso acervo e permitir novas formas de aproveitamento do material.

O funcionário pretende se empenhar para digitalizar por meio de reconhecimento de caracteres, não por escaneamento por imagens, que é a forma mais comum. Dessa forma os textos poderão ser estudados por busca por palavras, nomes e cruzamento de expressões, por exemplo.

No acervo, existem cerca de 1000 livros com 150 páginas cada livro, em média.

Considera-se que em uma página de um livro existam aproximadamente 200 palavras, com 7 caracteres cada palavra, também em média.

Considerando que um único BYTE armazena um único caractere (uma letra, número, ou símbolo especial), pergunta-se:

Qual a quantidade aproximada de memória de computador que esse funcionário precisará utilizar para armazenar todo o acervo?

Para responder, faça as hipóteses que julgar necessárias!

## Resposta
> **ATENÇÃO!**
> Nota atingida com essa resposta: 10


O funcionário precisa de 210 MB para armazenar o acervo.

Explicação:

Primeiro precisamos levantar a quantidade de dados:

> Total de livros: 1000
>
> Total de páginas: 150.000 (quantidade de livros x quantidade de páginas)
>
> Total de palavras: 30.000.000 (quantidade de páginas x quantidade de palavras)
>
> Total de caracteres: 210.000.000 (quantidade de palavras x quantidade de caracteres)
>
> Total de bytes: 210.000.000 (equivalente a quantidade de caracteres)

A fórmula para converter byte em MegaByte é dividir o valor por 1e+6 (1 seguido de 6 zeros), o que resulta em 210 MB.