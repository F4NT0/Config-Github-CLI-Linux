# Config-Github-CLI-Linux
Scripts e Comandos para Github CLI


## Comandos para usar o Github CLI

**Login**

* Todos os Comandos começam com `gh`

Comando|Para que serve
|---|---|
`gh auth login`|Inicia o Protocolo de Login no Github no Computador


**Repositório**

Comando|Para que serve
|---|---|
`gh repo clone User/nomeRepo`| Para poder clonar o Repositório específico no Computador no Diretório atual que estiver no Terminal
`gh repo create nomeRepo`| Criar um Repositório novo com um nome específico
`gh repo view User/nomeRepo`| Apresenta informação e o README do Repo

**Issues**

Comando|Para que serve
|---|---|
`gh issue create `| Começa o Processo de Criação de uma Issue do Repo
`gh issue list`| Apresenta uma Lista de todas as Issues Abertas
`gh issue list --state close`| Apresenta uma Lista de todas as Issues Fechadas
`gh issue status`| Apresenta os Status das Issues
`gh issue view IssueNumber`| Apresenta as informações sobre a Issue quando passado o Número.

**Pull Request**

Comando|Para que serve
|---|---|
`gh pr checkout branch-name`| Altera a Branch para fazer Checkout do Pull Request
`gh pr checkout PRNumber`| Checking out localmente um PullRequest pelo Numero
`gh pr create`| Cria um Pull Request 
`gh pr list`| Lista todos os Pull Request abertos
`gh pr list --state closed`| Lista todos os Pull Request Fechados
`gh pr status`| Apresenta os Status dos PR do Repo
`gh pr view prNumber`| Apresenta os Dados sobre o PR especificado pelo Número
