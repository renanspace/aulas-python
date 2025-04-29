# **Tipos Primitivos em Python**

<img src="https://miro.medium.com/v2/resize:fit:1400/1*Y0ib5hBXcXwn6JQ3j2y5wQ.png" alt="ilustração linguagem python" width="700"/>

## Tipos primitivos: _string, number(int/float), boolean_

#### Para saber mais, [clique aqui.](https://dev.to/dormin/tipos-primitivos-em-python-10jg)

## Operadores aritméticos:
#### São usados para fazer operações matemáticas, desde as básicas (somar, subtrair, dividir...) até as mais avançadas (módulo, divisão interna, exponenciação...).

- ***Soma:***
```py
quatro = 4
dois = 2

soma = quatro + dois
print(soma) #Resultado: 6
```

- ***Substração:***
```py
oito = 8
doze = 12

subtracao = doze - oitro
print(subtracao) #Resultado: 4
```
- ***Multipicação:***

```py
seis = 6
tres = 3

multiplicacao = seis * 3
print(multiplicacao)
```

- ***Divisão:***
```py
dez = 10
dois = 2

divisao = dez / dois
print(divisao)
```

## **Operadores lógicos/comparativos:** 
#### São operadores usados para **comparar** dois valores.

**=, !=, >, >=, <=, <**

- ***Igual/Diferente:***
```py
var = 5

if var = 5:
  print('Os valores são iguais.')
```

```py
var = 7

if var != 7:
  print('O valor não é igual a 7.')
```
- ***Maior/menor que:***
```py
var = 2

if var > 2:
  print('O valor é maior que 2.')
elif var >= 2:
  print('O valor da variável é maior ou igual a 2'.)
```
```py
if var < 2:
  print('O valor é menor que 2.')
```


## **Estruturas condicionais:**

- _**if:**_ Executa um bloco de código se uma condição especificada for verdadeira.
- _**elif:**_ Significa *"else if"* e permite que você verifique várias condições.
- _**else:**_ Executa um bloco de código se nenhuma das condições anteriores for verdadeira.

```py
renan = 1.80
victor = 1.80

#Se for positivo, o print será ativado
if victor > renan:
  print("Victor é mais alto.")
elif victor == renan:
  print("Victor e Renan têm a mesma altura.")
else:
  print("Renan é mais alto")
```


