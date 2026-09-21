# Cicatrizes e Aprendizados

## Sobre esta etapa

Este documento registra os principais problemas, descobertas e aprendizados obtidos durante a construção do projeto **God of War — Central de Conhecimento**.

A intenção é documentar não apenas o resultado final, mas também o processo utilizado para chegar até ele.

## 1. Primeira dificuldade — organizar um universo extenso

A franquia God of War possui diversos jogos, personagens, acontecimentos e elementos relacionados a diferentes mitologias.

A primeira consulta realizada no NotebookLM teve como objetivo obter uma visão geral desse conteúdo.

O resultado foi útil para identificar os principais elementos da franquia, mas também mostrou que uma resposta ampla não deveria ser utilizada diretamente como conteúdo final.

### Aprendizado

Uma consulta exploratória é útil para conhecer o conteúdo disponível, mas precisa ser seguida por consultas mais específicas quando o objetivo é produzir informações estruturadas.

---

## 2. Segunda dificuldade — transformar informações em uma cronologia

Após a visão geral, foi solicitado ao NotebookLM que organizasse os principais acontecimentos em ordem cronológica.

A resposta produziu uma linha do tempo com 13 acontecimentos, reunindo informações de diferentes fontes.

Embora a estrutura fosse útil, a agregação de várias informações em uma única resposta mostrou a necessidade de realizar uma validação específica.

### Aprendizado

Uma resposta organizada e aparentemente coerente não significa necessariamente que todas as relações temporais estejam corretas.

Quando diferentes fontes são sintetizadas, detalhes de sequência podem ser apresentados de forma incorreta.

---

## 3. Problema identificado — sequência relacionada à Atlântida

Durante a validação da linha do tempo, foi identificado um problema no acontecimento relacionado à Atlântida.

A primeira versão da cronologia apresentava a chegada de Kratos à Atlântida de maneira incompatível com a sequência sustentada pelas fontes.

A análise posterior mostrou que:

* Kratos chegou à Atlântida enquanto a cidade ainda estava intacta;
* durante sua passagem pela cidade, ocorreram acontecimentos relacionados à sua mãe, Callisto, e à descoberta de informações sobre Deimos;
* Kratos libertou a Titã Thera;
* a libertação provocou uma erupção vulcânica e o afundamento da cidade;
* somente posteriormente Kratos retornou às ruínas submersas;
* o retorno às ruínas estava relacionado à continuação de sua busca por Deimos.

O problema, portanto, estava principalmente na **ordem dos acontecimentos**, e não na presença da Atlântida na linha do tempo.

---

## 4. Como o problema foi corrigido

Após identificar a inconsistência, foi realizado um novo prompt no NotebookLM solicitando uma correção direcionada.

A instrução determinava que apenas as informações problemáticas fossem alteradas e que os acontecimentos já classificados como confirmados fossem preservados.

A nova consulta reorganizou a sequência da Atlântida e manteve a estrutura geral dos 13 acontecimentos.

Esse procedimento evitou simplesmente substituir toda a resposta anterior por uma nova geração sem controle sobre as alterações.

---

## 5. Importância da validação

Um dos principais aprendizados do projeto foi perceber que a utilização de IA para pesquisa não deve terminar na primeira resposta.

O processo utilizado mostrou que diferentes tipos de prompts podem cumprir funções diferentes:

* **Exploração:** identificar informações disponíveis;
* **Organização:** estruturar o conteúdo;
* **Validação:** verificar se as informações são sustentadas pelas fontes;
* **Correção:** ajustar problemas identificados;
* **Consolidação:** transformar o conteúdo validado em material de estudo.

Esse fluxo foi aplicado progressivamente durante o desenvolvimento do projeto.

---

## 6. Controle das fontes

Outro aprendizado foi a importância de limitar as consultas às fontes disponibilizadas no NotebookLM.

Os prompts utilizados reforçaram repetidamente que as respostas deveriam utilizar exclusivamente o conteúdo disponível no caderno.

Essa estratégia ajudou a manter o foco no material selecionado e permitiu identificar quando determinada informação apresentava divergência ou precisava de validação adicional.

---

## 7. O que funcionou melhor

Durante os testes, algumas práticas demonstraram maior utilidade:

* Dividir uma tarefa complexa em etapas menores;
* Solicitar referências às fontes;
* Pedir que informações não sustentadas fossem explicitamente identificadas;
* Validar uma resposta anterior com um novo prompt;
* Solicitar correções específicas em vez de regenerar todo o conteúdo;
* Preservar informações já consideradas confirmadas;
* Registrar os prompts utilizados e os resultados obtidos.

---

## 8. Principal aprendizado

O principal aprendizado deste projeto foi que o uso de IA para pesquisa funciona melhor quando existe um processo de verificação.

O NotebookLM foi utilizado não apenas como ferramenta para gerar respostas, mas como parte de um fluxo de pesquisa no qual os resultados foram questionados, comparados, validados e refinados.

Dessa forma, o projeto passou a seguir o seguinte modelo:

**Explorar → Organizar → Validar → Corrigir → Consolidar**

Esse processo também pode ser reutilizado em outros projetos de pesquisa e estudo baseados em fontes fornecidas pelo usuário.
