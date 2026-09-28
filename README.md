# Processamento de Linguagem Natural aplicado ao estudo da fotoluminescência de nanomateriais

Desenvolvimento de um pipeline de Processamento de Linguagem Natural (PLN) para extração e análise automatizada de informações sobre propriedades fotoluminescentes descritas na literatura científica.

| Informação | Descrição |
|---|---|
| **Autoras** | Bruna Guedes Pereira e Sarah Santos Silva |
| **Professor orientador** | James Moraes de Almeida |
| **Projeto** | Processamento de Linguagem Natural |
| **Tema** | Extração automática de informações e relações entre composição, processamento e propriedades fotoluminescentes |
| **Material estudado** | Perovskitas |
| **Pergunta de pesquisa** | Quais informações e relações entre composição, processamento e propriedades fotoluminescentes podem ser extraídas automaticamente de artigos científicos sobre perovskitas? |
| **Objetivo** | Desenvolver um pipeline baseado em PLN para extrair automaticamente informações e relações entre materiais, processos de modificação, propriedades fotoluminescentes, valores quantitativos e aplicações descritas na literatura científica. |

---

### Introdução

A ciência dos materiais é caracterizada pela produção de grandes volumes de informações heterogêneas, envolvendo diferentes materiais, composições, métodos de processamento, propriedades e aplicações. Nesse contexto, o Processamento de Linguagem Natural (PLN) permite transformar informações presentes em textos científicos não estruturados em dados organizados, possibilitando a identificação automática de entidades, valores quantitativos e relações entre diferentes conceitos.

Entre os materiais de interesse estão as perovskitas halogenadas, que apresentam propriedades optoeletrônicas relevantes e são investigadas para aplicações como células solares, diodos emissores de luz, lasers e fotodetectores. A literatura sobre esses materiais reúne uma grande variedade de composições, condições de processamento e propriedades fotoluminescentes, tornando a análise manual de grandes conjuntos de publicações uma tarefa complexa.

Este projeto utiliza um corpus de 11.725 resumos de artigos científicos para desenvolver um pipeline de PLN voltado à identificação e extração automática de informações relacionadas à fotoluminescência de perovskitas. Entre as informações de interesse estão materiais, propriedades fotoluminescentes, valores quantitativos e unidades, processos de modificação, aplicações e relações entre essas entidades. O pipeline combina métodos determinísticos, como expressões regulares, com modelos de linguagem para produzir informações estruturadas a partir dos resumos científicos.

O objetivo principal é investigar se técnicas de PLN são capazes de identificar e extrair automaticamente relações entre material, processamento e propriedades fotoluminescentes descritas explicitamente na literatura. O sistema é desenvolvido e avaliado a partir de um conjunto de sentenças anotadas manualmente, utilizando métricas como precisão, revocação, F1 e Exact Match. Posteriormente, as informações extraídas do corpus poderão ser utilizadas para a construção de representações estruturadas, como grafos de conhecimento, permitindo explorar padrões e relações entre diferentes perovskitas.
