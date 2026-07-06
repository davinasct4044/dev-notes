# Conventional Commits

Os **Conventional Commits** são um padrão para escrever mensagens de commit de forma clara e consistente.

## Estrutura

```text
tipo(escopo opcional): descrição
```

Exemplos:

```text
feat(auth): add login endpoint
fix(upload): fix file size validation
docs: update README
```

---

# Tipos de commit

## feat

Usado quando uma **nova funcionalidade** é adicionada.

Exemplos:

```text
feat: add room creation endpoint
feat: implement file upload
feat: generate unique room codes
```

---

## fix

Usado para **corrigir bugs**.

Exemplos:

```text
fix: resolve room deletion bug
fix: prevent duplicate room codes
fix: correct upload validation
```

---

## docs

Alterações na documentação.

Exemplos:

```text
docs: update installation guide
docs: improve API documentation
docs: add project architecture
```

---

## style

Mudanças que **não alteram o funcionamento do código**.

Exemplos:

* Formatação
* Espaçamento
* Indentação
* Organização visual

```text
style: format project with black
style: fix indentation
```

---

## refactor

Reorganização ou melhoria do código **sem alterar o comportamento**.

Exemplos:

```text
refactor: separate room routes
refactor: move database configuration to core
refactor: simplify room service
```

---

## test

Adição ou alteração de testes.

Exemplos:

```text
test: add room creation tests
test: improve upload validation tests
```

---

## chore

Tarefas de manutenção que não adicionam funcionalidades.

Exemplos:

* Configuração do projeto
* Dependências
* Estrutura de pastas
* Ferramentas

```text
chore: configure FastAPI project
chore: create backend architecture
chore: add .gitignore
chore: update dependencies
```

---

## perf

Melhorias de desempenho.

Exemplos:

```text
perf: optimize room lookup
perf: improve file upload performance
```

---

## build

Alterações relacionadas ao processo de build ou empacotamento.

Exemplos:

```text
build: configure Docker
build: update build pipeline
```

---

## ci

Alterações na integração contínua (GitHub Actions, GitLab CI, etc.).

Exemplos:

```text
ci: add GitHub Actions workflow
ci: update deployment pipeline
```

---

## Exemplos reais

Criou uma nova funcionalidade:

```text
feat: implement room creation API
```

Corrigiu um bug:

```text
fix: prevent empty room codes
```

Separou as rotas em arquivos:

```text
refactor: separate room routes into dedicated module
```

Criou a estrutura inicial do backend:

```text
chore: initialize backend architecture
```

Criou a documentação:

```text
docs: add project development notes
```

---

# Boas práticas

* Escreva a descrição no imperativo.
* Prefira mensagens curtas e objetivas.
* Utilize inglês para manter um padrão internacional.
* Faça commits pequenos e relacionados a uma única alteração.

## Exemplos

✔️

```text
feat: add room service
```

```text
fix: validate uploaded file size
```

```text
refactor: simplify router structure
```

❌

```text
arrumei umas coisas
```

```text
mudanças
```

```text
teste
```

```text
corrigi bug e adicionei upload e mudei o banco
```

Quando uma alteração envolve funcionalidades diferentes, prefira fazer commits separados.
