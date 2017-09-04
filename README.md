# CalculoEstatistica

#Alunos:
##Ricardo Luiz da Silva Junior (juninho)
##Hugo Pablo Tomas de Araujo (Huguinho)

## Identificação

Objetivo: teste unitário com linguagem a definir
Problema: http://dojopuzzles.com/problemas/exibe/calculando-estatisticas-simples/

## Plano de teste

| Entrada  | Condição | Classes Válidas | Classes Inválidas |
| ------------- | ------------- | ------------- | ------------- |
| numeros            | numeros [0,infinito]               | numero =! nulo                      |  |
| numero,numeros     | numero != nulo && numeros != nulo  | numero = Max(numeros)               |  |
| numero,numeros     | numero != nulo && numeros != nulo  | numero = Min(numeros)               |  |
| totalSize,numeros  | totalSize > 0 && numeros != nulo   | totalSize = length(numeros)         |  |
| media,numeros      | media != nulo && numeros != nulo   | media = numeros[1 + 2 + ... + n]/n  |  |
