# Operador Condicional (SE) e (SENÃO) e (SENÃO SE)

Aqui veremos como dizer a um algoritmo quando um conjunto de instruções deve ser executado. Esta determinação é estabelecida se uma condição for verdadeira. Mas o que seria esta condição? Ao executar um teste lógico teremos como resultado um valorverdadeiro ou falso. A condição descrita anteriormente nada mais é que um teste lógico

Se este teste lógico resultar verdadeiro, as instruções definidas dentro do desvio condicional serão executadas. Se o teste for falso, o algoritmo pulará o trecho e continuará sua execução a partir do ponto onde o desvio condicional foi finalizado

O desvio condicional que foi acima apresentado é considerado simples e conhecido como o comando `se`

A sintaxe é respectivamente a palavra reservada `se`, a condição a ser testada entre parenteses e as instruções que devem ser executadas entre chaves caso o desvio seja verdadeiro

```
logico condicao = verdadeiro
se(condicao)
{
// instruções que serão executadas caso desvio seja verdadeiro, no caso o que tiver dentro dos parenteses for verdadeiro
}

inteiro x = 5
se(x>5)
{
// instruções que serão executadas caso desvio seja verdadeiro, no caso o que tiver dentro dos parenteses for verdadeiro,
// exemplo: x é maior que 5? não... ele é igual a 5, isso quer dizer que tal afirmação é falsa e por isso as instruções dentro
// das chaves não serão executadas
}

```
