# Processamento de linguagem natural para estudo de fotoluminescencia de nanomateriais
Desenvolvimento de um projeto empregando processamento de linguagem natural (PLN) para análise de dados da fotoluminescência de nanomateriais.

**Autoras:** Bruna Guedes Pereira e Sarah Santos Silva

**Professor orientador:** James Moraes de Almeida

**Projeto:** Processamento de Linguagem Natural

**Tema:** Extração automática de relações entre composição, processamento e propriedades fotoluminescentes

**Material estudado:** Perovskitas 

**Pergunta de pesquisa:** Quais relações entre composição, processamento e propriedades fotoluminescentes podem ser extraídas automaticamente de artigos sobre perovskitas?

**Objetivo:** Desenvolver um pipeline baseado em Processamento de Linguagem Natural para extrair automaticamente informações e relações entre materiais, processos, propriedades fotoluminescentes e aplicações descritas na literatura científica.

### Introdução

A ciência dos materiais é caracterizada pela produção de grandes volumes de informações heterogêneas, envolvendo diferentes materiais, composições, métodos de processamento e propriedades. O Processamento de Linguagem Natural (PLN) tem se consolidado como uma ferramenta importante para a análise automatizada da literatura científica, permitindo transformar textos não estruturados em representações que podem ser utilizadas para identificar entidades, padrões semânticos e relações entre diferentes conceitos. Essas ferramentas possibilitam explorar grandes conjuntos de publicações e extrair informações que seriam difíceis de identificar por meio de análises exclusivamente manuais.

Entre os materiais de interesse estão as perovskitas halogenadas, que apresentam propriedades optoeletrônicas relevantes e aplicações em áreas como células solares, diodos emissores de luz, lasers e detectores fotônicos. Dessa forma, o notebook apresenta as etapas de processamento e análise do corpus, desde a preparação dos dados até a identificação de padrões semânticos, entidades e relações relevantes para o estudo da fotoluminescência em nanomateriais.

A grande variabilidade desses dados torna a análise manual da literatura uma tarefa complexa e dificulta a identificação sistemática de relações entre diferentes características dos materiais. Nesse contexto, técnicas de Processamento de Linguagem Natural podem ser utilizadas para transformar informações textuais em dados estruturados e permitir a análise automatizada de grandes conjuntos de artigos.

Foi utilizado um corpus de 11.725 resumos de artigos científicos e desenvolvido um pipeline para realizar o pré processamento dos textos, sua representação semântica, descoberta de tópicos, extração de entidades e identificação de relações. Entre as entidades de interesse estão materiais, propriedades fotoluminescentes, processos de modificação e aplicações. 

O objetivo principal é identificar automaticamente relações entre composição, processamento e propriedades fotoluminescentes descritas na literatura. A partir das informações extraídas, pretende se construir uma representação em forma de grafo de conhecimento e comparar os padrões encontrados entre perovskitas. 
