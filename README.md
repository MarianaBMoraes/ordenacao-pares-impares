# Separador de Números Pares e Ímpares em JavaScript

Este é um simples script em JavaScript que separa números pares e ímpares de um array e os concatena em um novo array.

## Funcionalidades

O script realiza as seguintes operações:

- **Separar Números Pares e Ímpares:** Itera através do array `numeros` e adiciona números pares ao array `pares` e números ímpares ao array `impares`.
- **Concatenar Resultados:** Combina os arrays `pares` e `impares` em um novo array chamado `todos`.

## Como usar

Para utilizar o script, siga os passos abaixo:

1. **Defina o array de números:** Edite a variável `numeros` no código para incluir os números desejados. Por exemplo:
   ```javascript
   let numeros = [1, 2, 3, 4, 5, 6, 7, 8, 9, 10];
   ```

2. **Execute o script:** Abra o console do seu navegador ou execute o arquivo JavaScript em um ambiente Node.js para ver os resultados.

## Exemplo

Suponha que você tenha o seguinte array:
```javascript
let numeros = [1, 2, 3, 4, 5, 6, 7, 8, 9, 10];
```

Ao executar o script, você verá o seguinte resultado no console:
```
[2, 4, 6, 8, 10, 1, 3, 5, 7, 9]
```

Neste exemplo, os números pares são [2, 4, 6, 8, 10] e os números ímpares são [1, 3, 5, 7, 9], e eles são concatenados em um único array `todos`.

## Notas

- O script assume que todos os números no array são válidos e numéricos.
- Este script é útil para separar e combinar números de acordo com suas propriedades (neste caso, paridade) em um novo array.
