# God of War — Central de Conhecimento

Projeto desenvolvido como parte de um desafio da **DIO**, utilizando o **NotebookLM** como ferramenta de pesquisa e organização de conhecimento baseada em fontes selecionadas.

O projeto utiliza a franquia **God of War** como objeto de estudo para demonstrar um processo de pesquisa utilizando Inteligência Artificial, com etapas de exploração, organização, validação, correção e consolidação das informações.

---

## 🎯 Objetivo

Construir uma central de conhecimento introdutória sobre o universo de **God of War**, reunindo informações sobre:

* História da franquia;
* Cronologia dos principais acontecimentos;
* Personagens;
* Mitologias;
* Conceitos e artefatos;
* Glossário;
* Prompts reutilizáveis.

Além da produção do conteúdo, o projeto documenta o processo utilizado para consultar, validar e corrigir informações obtidas por meio do NotebookLM.

---

## 🤖 Ferramenta utilizada

### NotebookLM

O NotebookLM foi utilizado como ferramenta principal de pesquisa e síntese.

As consultas foram realizadas com base nas fontes disponibilizadas no caderno do projeto, buscando evitar a utilização de informações externas ao material selecionado.

O processo foi dividido em diferentes etapas:

**Explorar → Organizar → Validar → Corrigir → Consolidar**

---

## 📚 Fontes utilizadas

Foram utilizadas fontes em formato PDF e vídeos do YouTube relacionados à história da franquia.

A lista completa das fontes está disponível em:

👉 [Fontes utilizadas](fontes/fontes.md)

---

## 🧠 Processo de Prompt Engineering

O projeto documenta quatro etapas principais de interação com o NotebookLM.

### Teste 01 — Visão Geral

Primeira consulta exploratória sobre o universo de God of War.

O objetivo foi identificar jogos, personagens, mitologias, acontecimentos e conceitos fundamentais.

👉 [Ver Teste 01](prompt-engineering/teste-01-visao-geral.md)

### Teste 02 — Linha do Tempo

As informações obtidas anteriormente foram organizadas em uma linha do tempo cronológica.

O objetivo foi estruturar os acontecimentos independentemente da ordem de lançamento dos jogos.

👉 [Ver Teste 02](prompt-engineering/teste-02-linha-do-tempo.md)

### Teste 03 — Validação

A linha do tempo foi submetida a uma análise crítica para verificar quais informações estavam confirmadas, parcialmente confirmadas ou não confirmadas pelas fontes.

Durante essa etapa foi identificada uma inconsistência relacionada à sequência dos acontecimentos envolvendo Atlântida.

👉 [Ver Teste 03](prompt-engineering/teste-03-validacao.md)

### Teste 04 — Correção

Após a identificação da inconsistência, foi realizada uma nova consulta para corrigir somente o trecho problemático e preservar as informações já validadas.

👉 [Ver Teste 04](prompt-engineering/teste-04-correcao.md)

---

## 🩹 Cicatrizes e aprendizados

O projeto também registra os problemas encontrados durante o processo e os aprendizados obtidos.

Um dos principais aprendizados foi perceber que uma resposta aparentemente coerente pode apresentar inconsistências quando informações provenientes de diferentes fontes são sintetizadas.

Por esse motivo, a validação foi incorporada como uma etapa obrigatória do processo.

👉 [Ver cicatrizes e aprendizados](cicatrizes/aprendizados.md)

---

## 📖 Mini Guia

As informações validadas durante o projeto foram consolidadas em um mini guia introdutório.

O material apresenta:

* Visão geral da franquia;
* Linha histórica resumida;
* Personagens principais;
* Mitologias;
* Conceitos;
* Jogos e acontecimentos;
* Prompts reutilizáveis.

👉 [Acessar Mini Guia](guia/mini-guia.md)

---

## 📕 Glossário

Foi criado também um glossário com termos, personagens, artefatos e conceitos relevantes identificados durante a pesquisa.

👉 [Acessar Glossário](guia/glossario.md)

---

## 🗂️ Estrutura do projeto

```text
NotebookLM_DIO/
│
├── README.md
│
├── fontes/
│   └── fontes.md
│
├── prompt-engineering/
│   ├── teste-01-visao-geral.md
│   ├── teste-02-linha-do-tempo.md
│   ├── teste-03-validacao.md
│   └── teste-04-correcao.md
│
├── cicatrizes/
│   └── aprendizados.md
│
└── guia/
    ├── mini-guia.md
    └── glossario.md
```

---

## 🔎 Metodologia

O desenvolvimento do projeto seguiu cinco etapas principais:

### 1. Exploração

Foi realizada uma consulta inicial para identificar os principais elementos presentes nas fontes.

### 2. Organização

As informações foram reorganizadas em uma estrutura cronológica e temática.

### 3. Validação

As informações foram revisadas individualmente para verificar se estavam sustentadas pelas fontes disponíveis.

### 4. Correção

Quando uma inconsistência foi encontrada, uma nova consulta foi utilizada para corrigir especificamente o problema identificado.

### 5. Consolidação

Após a validação, as informações foram transformadas em um mini guia e um glossário para facilitar a consulta.

---

## 💡 Principais aprendizados

Durante o desenvolvimento do projeto, alguns pontos se destacaram:

* Prompts mais específicos produzem respostas mais estruturadas;
* Solicitar referências às fontes facilita a validação;
* Respostas geradas por IA precisam ser verificadas antes de serem consideradas definitivas;
* Dividir uma tarefa complexa em etapas facilita a identificação de inconsistências;
* Prompts de validação podem revelar problemas que não aparecem em uma consulta inicial;
* Correções direcionadas permitem preservar informações já validadas;
* Registrar o processo é tão importante quanto apresentar o resultado final.

---

## 🛠️ Tecnologias e ferramentas

* **NotebookLM** — pesquisa, análise e síntese baseada em fontes;
* **GitHub** — armazenamento e documentação do projeto;
* **Markdown** — organização e apresentação dos conteúdos.

---

## 📌 Resultado final

O resultado deste projeto é uma pequena central de conhecimento sobre **God of War**, acompanhada da documentação do processo utilizado para construir e validar esse conhecimento.

Mais do que reunir informações sobre a franquia, o projeto busca demonstrar uma metodologia de utilização de IA baseada em fontes, na qual os resultados são:

**explorados → organizados → validados → corrigidos → consolidados.**

---

## 👤 Projeto

Desenvolvido por **Marcos Amorim** como parte de um desafio da **DIO**.
