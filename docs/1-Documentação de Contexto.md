# Introdução

Atualmente é inimaginável a vida sem energia elétrica. Eletricidade está amplamente presente tanto em processos produtivos industriais quanto na comodidade de nossos lares. Portanto, direta ou indiretamente, praticamente todo cidadão deste planeta é um consumidor de energia elétrica.
 
A cada dia novos aparelhos, impulsionados por energia elétrica, são criados visando melhorar a qualidade de vida e bem-estar dos cidadãos. Entretanto, estes mesmos dispositivos que simplificam nossas vidas, nos fazem cada vez mais dependentes da energia elétrica. Desta forma, é notório o aumento progressivo do consumo de eletricidade em nossos lares ao longo dos anos. E, na medida que o processo de modernização permanece acontecendo, é fácil prever a tendência de um consumo ainda maior de eletricidade no futuro.
 
No Brasil, a maior parte da energia elétrica produzida e distribuída para consumo pelo cidadão comum é produzida em usinas hidroelétricas, consequência da vasta rede fluvial que o país possui. Assim, segundo dados da Agência Nacional de Energia Elétrica (ANEEL) relativos a produção de energia elétrica, 62% da capacidade instalada em operação no país vem das hidrelétricas, 28% das termelétricas (combustíveis fósseis, carvão mineral, gás natural, nuclear e biomassa) e os 10% restantes vêm de usinas eólicas e da importação de outros países.
 
Em relação ao custo da energia elétrica no Brasil, um ranking mundial preparado pela Federação das Indústrias do Rio de Janeiro (Firjan), em janeiro de 2017, demonstrou que nosso país pratica o sexto maior preço mundial do megawatt/hora (402,3 Reais/MW/h). E que, além da indesejada sexta posição, este valor fica 46% acima da média internacional.
 
Desta forma, o consumo racional de energia elétrica é importante tanto por motivos financeiros (evitar gastos excessivos e desnecessários) quanto por motivos ambientais, pois a geração de energia depende da exploração de recursos naturais.
 
Acreditamos que a melhor forma do cidadão comum economizar energia elétrica, é através do conhecimento detalhado dos hábitos de consumo praticados localmente em seu próprio lar. Conhecer o consumo energético de cada aparelho doméstico assim como o seu grau de utilização mensal pode auxiliar o usuário de eletricidade e sua família a identificar potenciais focos de desperdício, assim como otimizar o uso de utensílios indispensáveis. Além disso, é importante considerar a característica intrinsecamente dinâmica do consumo elétrico de um domicílio durante determinado período de tempo. Desta forma, o conhecimento dos padrões dinâmicos de consumo por aparelho pode também ajudar com uma maior previsibilidade dos gastos mensais familiares. 
O presente projeto visa a formalização das bases para o desenvolvimento de uma aplicação web que proporcione ao cidadão comum um melhor gerenciamento do consumo de energia elétrica em seu próprio domicílio.

## Problema
Nesse momento você deve apresentar o problema que a sua aplicação deve  resolver. No entanto, não é a hora de comentar sobre a aplicação.

Descreva também o contexto em que essa aplicação será usada, se  houver: empresa, tecnologias, etc. Novamente, descreva apenas o que de  fato existir, pois ainda não é a hora de apresentar requisitos  detalhados ou projetos.

Nesse momento, o grupo pode optar por fazer uso  de ferramentas como Design Thinking, que permite um olhar de ponta a ponta para o problema.

> **Links Úteis**:
> - [Objetivos, Problema de pesquisa e Justificativa](https://medium.com/@versioparole/objetivos-problema-de-pesquisa-e-justificativa-c98c8233b9c3)
> - [Matriz Certezas, Suposições e Dúvidas](https://medium.com/educa%C3%A7%C3%A3o-fora-da-caixa/matriz-certezas-suposi%C3%A7%C3%B5es-e-d%C3%BAvidas-fa2263633655)
> - [Brainstorming](https://www.euax.com.br/2018/09/brainstorming/)

## Objetivos

Objetivo Geral:
 
O presente projeto visa desenvolver um software para auxiliar no registro e controle dinâmico, pelo usuário, do consumo de energia elétrica em seu próprio domicílio. Além de informar de forma consciente sobre métodos para economizar e otimizar o uso desses eletrodomésticos.
 
Objetivos Específicos:
 
·   	Identificar / reconhecer os padrões de consumo de energia por aparelho doméstico em cada domicílio;
 
·   	Possibilitar a adequação do consumo de energia elétrica domiciliar de acordo com os limites das bandeiras tarifárias;
 
·   	Conscientizar sobre a economia elétrica em escala;
 
·   	Promover educação do usuário através da comparação do consumo de energia em seu domicílio com um manual de boas práticas.


 
> **Links Úteis**:
> - [Objetivo geral e objetivo específico: como fazer e quais verbos utilizar](https://blog.mettzer.com/diferenca-entre-objetivo-geral-e-objetivo-especifico/)

## Justificativa

O Anuário Estatístico de Energia Elétrica 2020 (ano base 2019), publicado pela Empresa de Pesquisa Energética[1], empresa pública vinculada ao Ministério de Minas e Energia, traz as principais informações sobre o consumo de energia elétrica no Brasil, por região. O anuário declarou que o consumo total de energia elétrica no Brasil foi de 482 TWh[2], a classe residencial representa o maior número de unidades consumidoras de eletricidade do país representando 142.781GWh[3]. A região Sudeste, com a população de 88.4 milhões apresentou o consumo per capita de 2.698 kWh[4] por habitante, com concentrações nos estados do Rio de Janeiro e São Paulo.

A propagação da Covid-19 apresentou diversos reflexos na economia do país, como o aumento dos reajustes tarifários e no consumo residencial. Com mais pessoas em casa em razão da pandemia, o consumo de energia residencial cresceu 4,1%, para 148.223 GWh. Ou seja, esse foi o único segmento que registrou crescimento em 2020.

Medidas voltadas para a redução do consumo de energia nunca foram tão necessárias para a economia individual além de contribuir invariavelmente para o meio ambiente[5].

A aplicação da Web “Nome do projeto”, facilitaria no conhecimento de cada aparelho da sua casa. O usuário selecionaria os equipamentos, por cômodos, informando a potência e o tempo de uso dos aparelhos. Essas informações serão interligadas com as variações das tarifas econômicas e financeiras de energia. Considerando que o total da fatura em Real (R$) é resultado da multiplicação da energia consumida (medida em quilowatt hora) no mês pela tarifa aplicada, acrescido de taxas e impostos. Esses valores são definidos e homologados pela Agência Nacional de Energia Elétrica (Aneel). Ao final, a aplicação da web geraria o consumo total, além de dispor de sugestões de uso eficiente dos aparelhos.

Embora todas as pessoas possam se beneficiar de soluções para a moderação do uso de energia elétrica, na residência, o foco deste trabalho é o consumidor responsável pelo orçamento familiar. O intuito é disponibilizar uma ferramenta de fácil uso, informativa que promoveria a otimização de uso dos aparelhos elétricos, residenciais.

[1] Anuário Estatístico de energia Elétrica 2020, EPe. Disponível em: https://www.epe.gov.br/sites-pt/publicacoes-dados-abertos/publicacoes/PublicacoesArquivos/publicacao-160/topico-168/EPEFactSheetAnuario.pdf. Acesso em 10 abril 2021.

[2] O watt-hora é a medida de energia usualmente utilizada em eletrotécnica. Um watt-hora é a quantidade de energia utilizada para alimentar uma carga com potência de um watt pelo período de uma hora. O valor de 1 Wh é equivalente a 3,6×103 J =3,6 kJ =3600 J. 1 terawatt-hora (TWh) = 1 trilhão de watt-hora.

[3] Gigawatt-hora, abreviado como GWh, é uma unidade de energia que representa um bilhão (1 000 000 000) de watt-hora e é equivalente a um milhão de quilowatt-hora. Os gigawatts-hora são frequentemente usados como uma medida da produção de grandes usinas de energia elétrica.

[4] O quilowatt-hora é uma unidade de energia igual a 3600 quilojoules. O quilowatt-hora é comumente usado como uma unidade de cobrança da energia entregue aos consumidores pelas concessionárias de energia elétrica.

[5] As emissões de Gases de Efeito Estufa (GEE) provenientes da geração elétrica no Brasil totalizaram 56,3 milhões de toneladas (Mt) de CO2 em 2019, quase 7% superior a 2018.


## Público-Alvo

Descreva quem serão as pessoas que usarão a sua aplicação indicando os diferentes perfis. O objetivo aqui não é definir quem serão os clientes ou quais serão os papéis dos usuários na aplicação. A ideia é, dentro do possível, conhecer um pouco mais sobre o perfil dos usuários: conhecimentos prévios, relação com a tecnologia, relações
hierárquicas, etc.

Adicione informações sobre o público-alvo por meio de uma descrição textual, ou diagramas de personas, mapa de stakeholders, ou como o grupo achar mais conveniente.

> **Links Úteis**:
> - [Público-alvo](https://blog.hotmart.com/pt-br/publico-alvo/)
> - [Como definir o público alvo](https://exame.com/pme/5-dicas-essenciais-para-definir-o-publico-alvo-do-seu-negocio/)
> - [Público-alvo: o que é, tipos, como definir seu público e exemplos](https://klickpages.com.br/blog/publico-alvo-o-que-e/)
> - [Qual a diferença entre público-alvo e persona?](https://rockcontent.com/blog/diferenca-publico-alvo-e-persona/)
