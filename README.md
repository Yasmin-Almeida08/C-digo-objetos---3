# C-digo-objetos---3
// criando um objeto
let pessoa = {
  nome: "Ana",
  idade: 25,
  profissao: "Engenheira"
};

// alterando a propriedade idade do objeto pessoa
pessoa.idade = 26;


// ou também pode ser alterado usando colchetes
// pessoa["idade"] = 26;

// removendo uma propriedade
delete pessoa.profissao;

// exibindo no console o resultado
console.log(pessoa);
// Resultado: { nome: 'Ana', idade: 26 }
