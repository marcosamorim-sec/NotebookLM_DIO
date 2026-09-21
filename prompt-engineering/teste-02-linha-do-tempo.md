# Teste 02 — Construção da Linha do Tempo

## Objetivo

Organizar os principais acontecimentos da história de **God of War** em uma sequência cronológica, utilizando exclusivamente as fontes disponíveis no NotebookLM.

Diferentemente do primeiro teste, que teve caráter exploratório, esta etapa buscou estruturar os acontecimentos em ordem temporal, independentemente da ordem de lançamento dos jogos.

## Prompt utilizado

> Com base exclusivamente nas fontes disponíveis neste caderno, construa uma linha do tempo cronológica dos principais acontecimentos da história de God of War, desde os eventos mais antigos da mitologia grega apresentados nas fontes até God of War Ragnarök: Valhalla.
>
> Organize em ordem cronológica, e não pela ordem de lançamento dos jogos. Para cada acontecimento, informe:
>
> 1. Período/era;
> 2. Acontecimento;
> 3. Personagens envolvidos;
> 4. Jogo ou obra relacionada;
> 5. Fonte que sustenta a informação.
>
> Não inclua informações que não possam ser sustentadas pelas fontes disponíveis. Quando houver divergência ou incerteza entre as fontes, sinalize explicitamente.

## Estratégia utilizada

O segundo prompt foi elaborado a partir do resultado obtido no Teste 01.

A intenção foi transformar a visão geral da franquia em uma estrutura cronológica, permitindo visualizar a evolução da história desde os acontecimentos relacionados à mitologia grega até os eventos de **Ragnarök: Valhalla**.

Também foram adicionadas instruções para:

* Priorizar a ordem cronológica em vez da ordem de lançamento;
* Identificar personagens envolvidos;
* Relacionar cada acontecimento ao jogo ou obra correspondente;
* Informar as fontes utilizadas;
* Evitar informações sem sustentação nas fontes;
* Sinalizar divergências ou incertezas.

## Resultado obtido

O NotebookLM produziu uma linha do tempo composta por 13 acontecimentos principais, abrangendo diferentes períodos da história da franquia.

Entre os acontecimentos organizados estavam:

1. Origens do universo e períodos primordiais das mitologias apresentadas;
2. Titanomaquia e aprisionamento de forças malignas;
3. Infância de Kratos e o sequestro de Deimos;
4. Pacto de Kratos com Ares;
5. Rebelião contra Ares e acontecimentos relacionados às Fúrias;
6. Acontecimentos envolvendo Perséfone e Atlas;
7. Derrota de Ares e transformação de Kratos em Deus da Guerra;
8. Busca por Deimos e acontecimentos relacionados à Atlântida;
9. Traição de Zeus e acontecimentos de God of War II;
10. Queda do Olimpo e acontecimentos de God of War III;
11. Transição para as terras nórdicas e acontecimentos de God of War (2018);
12. Fimbulwinter, Ragnarök e acontecimentos relacionados a Asgard;
13. Eventos posteriores a Ragnarök apresentados em Valhalla.

A resposta apresentou os acontecimentos acompanhados dos personagens, jogos ou obras relacionadas e referências às fontes disponíveis.

## Avaliação do teste

O resultado foi útil para organizar a história da franquia, mas a análise mostrou que uma cronologia construída a partir de diversas fontes pode apresentar problemas de precisão quando várias informações são agregadas em uma única resposta.

Um exemplo identificado posteriormente ocorreu no acontecimento relacionado à **Atlântida**.

Na primeira versão da linha do tempo, a sequência apresentada indicava que Kratos teria chegado à Atlântida quando a cidade já estava submersa. A validação posterior mostrou que essa sequência precisava ser corrigida.

Essa inconsistência motivou a realização do **Teste 03 — Validação Crítica**.

## Aprendizado

A construção automática de uma linha do tempo pode organizar grandes quantidades de informação, mas a estrutura resultante precisa ser validada antes de ser considerada definitiva.

O teste demonstrou a importância de utilizar uma etapa específica de revisão para identificar:

* Informações parcialmente sustentadas;
* Detalhes adicionados durante a síntese;
* Problemas de ordem cronológica;
* Divergências entre fontes;
* Informações que precisam de correção.

Assim, o projeto passou a utilizar o processo:

**consulta → organização → validação → correção.**
