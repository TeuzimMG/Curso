# Oque são operadores lógicos?
**Operadores lógicos** são operadores mátematicos usados para soma, subtração, multiplicação, divisão e entre várias coisas.
Estes são exemplos de **operadores lógicos** usados em várias linguagens de programação:

| Simbolo | Função | Exemplo | Ordem de presedencia |
| :---: | --- | --- | :---: |
| `+` | **Soma** valores | `n1 + n2` | 4° |
| `-` | **Subtrai** valores | `n1 - n2` | 4° |
| `*` | **Multiplica** valores | `n1 * n2` | 3° |
| `/` | **Divide** valores | `n1 / n2` | 3° |
| `\` | **Divide inteiramente** valores | `n1 \ n2` | 3° |
| `^` | **Exponencia** valores | `n1 ^ n2` | 2° |
| `%` | **Módulo** | `n1 % n2` | 2° |
| `()` | **Mesma função mátematica** | (n1 + n2) * n3 | 1° |

## Usando operadores lógicos no VisuAlg
No VisuAlg podemos usar as mesmas regras ditas em cima deste titulo, todos estes operadores podem ser usados, por exemplo o de soma e entre outros.
Na programação podemos não só somar números como caracteres também, isso vai ficar mais claro quando mostrar o exemplo.

- Exemplo 1

   ```
   Algoritmo "operadores logicos"
   Var
      n1: Inteiro
      n2: Inteiro
   Inicio
         n1 <- 10
         n2 <- 20
         Escreva(n1 + n2)
   Fimalgoritmo
   ```
   Aqui neste exemplo temos o uso de um operador aritimetico, no caso o `+`, ele foi usado para somar o valor de `n1` e `n2`, poderiamos ter invês de deixar `Escreva(n1 + n2)` colocar outra váriavel que tenha seu valor como a soma de `n1` e `n2`.
   
- Exemplo 2

   ```
   Algoritmo "operadores logicos"
   Var
      bola: caracter
      adjetivo: caracter
   Inicio
         bola <- "Brinquedo"
         adjetivo <- "Hórrivel"
         Escreva(bola + adjetivo)
   Fimalgoritmo
   ```
   Este caso é mais interessante, pelo o fato do tipo primitivo ser caracteres, aqui a gente tem algo que se chama concatenação, teremos o valor da variavel `bola` + `adjetivo` sem se preocupar se é Inteiro ou não. O resultado disso é `BrinquedoHórrivel` pois somando os valores das váriaveis sendo eles númericos ou não sem se importar com seu tipo primitivo. A concatenação será vista mais em-breve e teremos uma página só para explica-lá
   
 - Exemplo 2

   ```
   Algoritmo "operadores logicos"
   Var
      bola: caracter
      adjetivo: caracter
   Inicio
         bola <- "Brinquedo"
         adjetivo <- "Hórrivel"
         Escreva(bola + adjetivo)
   Fimalgoritmo
   ```
