---
layout: exercicio
numero: 19
nome: Manipulando um vetor
topicos: javascript, funções, objetos, vetores
---

### Descrição:

Neste exercício, você irá criar funções para adicionar, editar e excluir tarefas em um vetor. 

Cada tarefa é representada por um objeto que possui as seguintes propriedades como mostra o exemplo abaixo: título, concluida e prioridade.

Exemplos de tarefas:

```js
const tarefas = [
  { titulo: "Estudar JavaScript", concluida: false, prioridade: 2 };
  { titulo: "Estudar HTML e CSS", concluida: true, prioridade: 1 }
]
```


Instruções:

1. Crie um vetor vazio chamado `gerenciadorTarefas`.
2. Implemente três funções:
  1. `adicionarTarefa`: Recebe um objeto de tarefa e adiciona-o ao `gerenciadorTarefas`.
  2. `editarTarefa`: Recebe o índice de uma tarefa existente e um objeto contendo os novos detalhes da tarefa.
  3. `excluirTarefa`: Aceita o índice no qual uma tarefa está armazenada e a remove do `gerenciadorTarefas`.
3. Teste cada função chamando-as e exibindo o resultado.

Exemplo:

```js
const gerenciadorTarefas = [];

function adicionarTarefa(tarefa) {
  // Implementação da adição de tarefa ao objeto gerenciadorTarefas
}

function editarTarefa(indice, novosDetalhes) {
  // Implementação da edição de tarefa no objeto gerenciadorTarefas
}

function excluirTarefa(indice) {
  // Implementação da exclusão de tarefa do objeto gerenciadorTarefas
}

adicionarTarefa({ titulo: "Estudar JavaScript", concluida: false, prioridade: 2 });
editarTarefa(0, { titulo: "Estudar HTML e CSS", prioridade: 1 });
excluirTarefa(0);
console.log(gerenciadorTarefas);
```

Gostou? Não esqueça de avaliar o exercício:

<a class="btn" href="https://forms.gle/scs1VxDDFSiMqAhe8" target="_blank"> Abra o formulário de avaliação</a>
