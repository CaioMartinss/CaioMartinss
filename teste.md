
## Regras de Contribuição

### 1. Boas Práticas de Semântica

Para garantir a consistência e clareza na colaboração do projeto, siga estas práticas ao trabalhar com o Git:

#### 1.1. Atualize Seu Repositório Local

Antes de começar a trabalhar, certifique-se de que seu repositório local está atualizado com as últimas alterações do repositório remoto.

```sh
git pull origin <branch>
```

1.2. Verifique as Branches
Confira as branches existentes para saber em qual branch você deve trabalhar ou criar uma nova branch se necessário.

```sh
git branch -a
```

1.3. Verifique os Últimos Commits
Revise os últimos commits para estar ciente das mudanças recentes e evitar conflitos.


```sh
git log
```

### 2. Criando e Trabalhando em Branches
2.1. Crie uma Nova Branch para Cada Tarefa
Crie uma nova branch para cada nova tarefa ou funcionalidade. Use uma nomenclatura clara e descritiva para as branches.

```sh
git checkout -b <nome-da-branch>
```

2.2. Faça Commits Frequentes e Descritivos
Faça commits pequenos e frequentes com mensagens descritivas. Isso facilita a revisão e a resolução de conflitos.

```sh
git commit -m "add: funcionalidade X"
```
### 3. Revisão de Código e Pull Requests
3.1. Abra Pull Requests para Revisão
Quando terminar uma tarefa, abra um pull request para revisão. Descreva claramente as mudanças feitas e solicite a revisão de outro membro da equipe.

3.2. Revise Pull Requests dos Colegas
Participe do processo de revisão de código, revisando e comentando nos pull requests dos colegas. Isso ajuda a garantir a qualidade e a consistência do código.
