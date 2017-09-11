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
| numeros            | numeros [0,infinito]               | numeros =! nulo                      | numeros = nulo               |
| numero,numeros     | numero != nulo or isInt() == true && numeros != nulo  | numero = Max(numeros)                | numero != Max(numeros)       |
| numero,numeros     | numero != nulo && numeros != nulo  | numero = Min(numeros)                | numero != Min(numeros)       |
| totalSize,numeros  | totalSize > 0 && numeros != nulo   | totalSize = length(numeros)          | totalSize != length(numeros) |
| media,numeros      | media != nulo && numeros != nulo   | media = numeros[0] + numero[1] + numero[...n-1]/n  | media != numeros[0] + numero[1] + numero[...n-1]/n |
