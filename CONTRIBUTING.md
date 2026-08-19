# ✅ Contribuindo com VITA

Bem-vindo à organização Github do projeto integrador: 

> _"Sistema para Identificação da Pinta Preta na Tangerina Ponkan, orientado por Visão Computacional"_ - AKA **VITA** _(Vision Intelligence for Tangerine Afflictions)_

Nossa equipe busca gerenciar a maior parte do desenvolvimento nesta organização, isso inclui código, documentação e divisão de tarefas.

A aceitação de contribuições está **restrita aos membros da organização**, mas qualquer pessoa pode visualizar e clonar nossos repositórios e projetos.

## Repositórios

Cada repositório guarda um componente importante do projeto, sendo acessíveis para qualquer membro.

- **vita-api**: Rest API em Express 
- **vita-database**: Bancos de dados MySQL e Redis 
- **vita-artifacts**: Diagramas, protótipos, imagens 
- **vita-paper**: Documentação acadêmica em LaTeX 
- **vita-app-web**: Aplicação web em React 
- **vita-app-mobile**: Aplicação mobile em React-Native 

## Projetos

Cada projeto representa um grupo de tarefas. Tarefas são criadas em forma de **Issues** do Github para um repositório específico. 

- **design**: Prototipação das interfaces web e mobile
- **paper**: Escrever e revisar LaTeX
- **back-end**: Desenvolver APIs e bancos de dados
- **front-end**: Desenvolver aplicações web e mobile

Cada issue é atribuída a 1 repositório e relacionada com 1+ membros. 

Provavelmente, **será criada uma branch remota** onde os membros irão resolver aquela tarefa.

## Guia de contribuição

_Ganhou uma nova issue? Recomendo seguir esse passo a passo._

1. Caso sua máquina não tenha uma cópia do repositório:

```
# baixa do github 
git clone <link do repositorio> 
```

2. Entre na branch correta:
```
# visualiza todas as branches remotas
git branch -r 

# troca de branch
git checkout <nome da branch> 

# visualiza sua branch atual
git branch 
```

3. Antes de mexer em qualquer coisa, atualize com as últimas mudanças:
```
# recomendo realizar esses 2 comandos na branch "main" e "dev" também

# baixa histórico remoto
git fetch 

# atualiza sua branch atual
git pull 

```

4. Depois de completar a tarefa, salve as alterações:

```
# verifica alterações
git status 

# prepara alteração para commit (staging)
git add <nome do arquivo ou pasta> 

# prepara todas as alterações feitas para commit
git add . 

# salva alteração com mensagem de texto
git commit -m "<mensagem do commit>" 
```

5. Quando tudo estiver salvo, envie para a mesma branch remota:
```
# envia histórico local para o Github
git push 
```

6. Ao completar a tarefa, abra uma Pull Request (PR) no Github:

- Em qualquer repositório, o Merge deve seguir a ordem: `<sua branch> → dev`
- Na descrição da PR, escreva um resumo do que foi feito

7. Aguarde a revisão da PR - ela poderá ser aceita (e seu trabalho será incluso na branch "dev") ou não (se houver erros ou pendências, será solicitado continuidade pelo chat do Github)