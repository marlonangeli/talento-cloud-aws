# Leitura de Dados

Para lermos e armazenarmos os dados nas variáveis, precisamos primeiro declará-las. Veja o pseudocódigo abaixo:

```plaintext
nome: caractere
endereco: caractere
cidade: caractere
cpf: caractere
rg: caractere
```

Agora, precisamos ler os dados do usuário e armazená-los nas variáveis. Veja o pseudocódigo abaixo:

```plaintext
escreva("Digite o seu nome: ")
leia(nome)
escreva("Digite o seu endereço: ")
leia(endereco)
escreva("Digite a sua cidade: ")
leia(cidade)
escreva("Digite o seu CPF: ")
leia(cpf)
escreva("Digite o seu RG: ")
leia(rg)
```

Por fim, precisamos exibir os dados fornecidos pelo usuário. Veja o pseudocódigo abaixo:

```plaintext
escreva("Nome: ", nome)
escreva("Endereço: ", endereco)
escreva("Cidade: ", cidade)
escreva("CPF: ", cpf)
escreva("RG: ", rg)
```

Uma implementação em JavaScript seria:

```js
let nome: string = prompt("Digite o seu nome: ");
let endereco: string = prompt("Digite o seu endereço: ");
let cidade: string = prompt("Digite a sua cidade: ");
let cpf: string = prompt("Digite o seu CPF: ");
let rg: string = prompt("Digite o seu RG: ");

console.log("Nome: ", nome);
console.log("Endereço: ", endereco);
console.log("Cidade: ", cidade);
console.log("CPF: ", cpf);
console.log("RG: ", rg);
```
