# Oque são váriaveis?
Variavel é tudo aquilo que se ganha um valor, sendo ele um valor númerico ou palavras e letras, para entender melhor sobre oque eu estou dizendo irémos utilizar o VisuAlg como dito anteriormente..
# Declarando váriaveis
Para declarar uma váriavel no VisuAlg iremos utilizar o campo para declarar tais, que no caso é entre `var` e o `inicio` como podemos ver no algoritmo escrito na **introdução**:

```
algoritmo "primeiro algoritmo"
var
< ESPAÇO PARA DECLARAR VÁRIAVEIS >
inicio
  Escreva("Primeiro algoritmo")
fimalgoritmo
```

Antes de criarmos uma váriavel precisamos saber oque elá é na prática, pense em um armário que nele tenha uma bola, podemos dizer que a bola é um brinquedo, sendo assim `bola = brinquedo`, na programação dizemos que a palavra `bola` é um **identificador**, eles são usados para nos orientar e para dizer que por exemplo é a `bola` que ira receber o valor `brinquedo` e nada mais e nada menos. Alguns outros exemplos:

```
numero1 = 10
numero2 = 30
total = 40
texto = "Olá mundo"
```

Estes exemplos são só para ilustrar na sua cabeça oque queremos que saiba, mas agora podemos ver regras para definir um **identificador**, que são no caso:

- **Não pode conter espaços em brancos**
- **Tem que começar com uma letra**
- **Depois da primeira letra o resto pode ser números ou letras**
- **Não se pode usar símbolos, exceto: _**
- **Nenhuma letra pode conter acentuações**
- **Não pode ser uma palavra _reservada_**(Palavras reservadas são comandos e etc)

Agora que sabemos disso podemos ir para o caso dos tipos primitivos, precisamos indicar para o programa qual é o tipo de dados que será guardado na várivel, só assim poderemos colocar um valor em cima de uma váriavel. Nós temos vários tipos de dados sendo eles:

- **Inteiro**
- **Caracter**
- **Real**
- **Lógico**

Colocando no VisuAlg terá que ficar assim:

```
algoritmo "primeiro algoritmo"
var
<identificador>: <tipo>         <-- A variavel <identificador> foi recebida com o <tipo> podendo ser ela inteiro e etc..
inicio
  <identificador> <- <valor>    <-- A variavel <identificador> agora tem o valor <valro>
  Escreva(<identificador>)      <-- O valor da variavel <identificador> vai ser escrita na tela
fimalgoritmo
```

Exemplo:

```
algoritmo "primeiro algoritmo"
var
  bola: caractere        <-- A variavel bola foi recebida com o tipo caracter 
inicio
  bola <- "Brinquedo"    <-- A variavel bola agora tem o valor "Brinquedo"
  Escreva(bola)          <-- O valor da variavel bola vai ser escrita na tela("Brinquedo")
fimalgoritmo
```

Usamos o ( **<-** ) para dizer que a variavel antes dela receberá o valor depois dele, exemplo: `agua <- "H2O"`.

## Declarando mais que uma váriavel em uma linha
Sim isso é póssivel, e posso mostrar agora para vocês uma forma fácil e ecônomica de se declarar váriaveis.
Para fazer isso é apenas usarmos uma virgular entre uma váriavel e outra, desse jeito: `<variavel1>, <variavel2>: <tipo>` sendo `<tipo>` inteiro, caracter e etc..

> ***Conluimos aqui uma introdução leve as váriaveis e suas propriedades***







