# Python Basics – Learning Repository

> **Status:** iniciante praticando Python do zero para construir base sólida.

Bem-vindo! Este repositório é o meu espaço de estudos — um “diário de bordo” onde guardo **meu primeiro contato com Python**. Aqui você vai encontrar **aulas, exercícios e pequenas práticas**, com foco em consolidar fundamentos (ex.: **classes, listas, funções**) e começar a explorar bibliotecas como **Pandas**.

## Objetivos
- Registrar meu progresso como **iniciante** em Python.
- Manter exemplos simples e comentados que eu mesmo possa revisar.
- Centralizar **lições** e **práticas**: de **classes** a **listas**, passando por **funções** e **Pandas**.

## O que tem aqui
- Pandas (dataframes, basic exploration)
- Funções em Python (`def`, parâmetros, retorno)
- Listas (criação, slicing, métodos)
- Pequenos projetos utilitários (ex.: conversores)
- Listas de exercícios e prática guiada
- Anotações e notebooks de aula
- Avaliações/Provas simuladas

## Estrutura atual (resumo do que foi enviado)
```
📄 AV 4
📄 Aula 10, Lista de Exercicios VIII, Listas
📄 Aula 9, Lista de Exercicios V, Funções em ´def´
📄 Aula 9, Lista de Exercicios VII, Funções em ´def´.ipynb
📄 Aula 9, def
📄 Conversor Básico.ipynb
📄 Exercícios Extras.ipynb
📄 Exercícios Propostos.ipynb
📄 Pandas Exploration.ipynb
```

> Obs.: nomes seguem o padrão das aulas/listas que estou usando no curso; podem mudar à medida que organizo melhor.

## Como usar
1. **Clonar** o repositório e abrir no VSCode (ou Jupyter):
   ```bash
   git clone <URL-do-repo>
   cd <pasta-do-repo>
   ```
2. (Opcional) **Criar venv** e instalar dependências usadas nos notebooks:
   ```bash
   python3 -m venv .venv
   source .venv/bin/activate   # no Windows: .venv\Scripts\activate
   pip install -U pip
   pip install pandas jupyter ipykernel
   ```
3. **Rodar notebooks**:
   ```bash
   jupyter notebook
   ```
   ou abra diretamente pelo **VSCode** com a extensão “Jupyter”.

## Roadmap de aprendizado (rascunho)
- [X] Fundamentos: tipos, variáveis, `input()`, `print()`
- [X] Estruturas: `if`, `for`, `while`
- [X] **Listas**, tuplas, dicionários; *list/dict comprehension*
- [X] **Funções** (`def`, parâmetros, `return`, escopo)
- [ ] **Classes** e POO (atributos, métodos, `__init__`)
- [ ] **Pandas**: `Series`, `DataFrame`, leitura de CSV, `head()`, `info()`
- [X] Boas práticas: nomeação, organização de pastas, `requirements.txt`
- [X] Testes básicos com `pytest`
- [X] Projetinhos: conversores, jogos simples, automações

## Convenções e boas práticas
- Arquivos grandes ou gerados (datasets, `.ipynb_checkpoints/`) ficam fora do Git.
- Uso um **`.gitignore`** para evitar enviar coisas desnecessárias.
- Commits curtos e descritivos (ex.: `feat: add list exercises` / `fix: pandas example`).

## O que ainda pretendo adicionar
- `requirements.txt` e/ou `environment.yml` para reproduzir ambiente
- Pasta `data/` com exemplos simples (ou link para dados públicos)
- `LICENSE` (provável MIT) e uma descrição em inglês
- Uma pasta `projects/` com pequenos desafios aplicados

---

> **Nota para recrutadores/mentores:** este repositório mostra meu progresso inicial. Feedbacks são bem-vindos!
