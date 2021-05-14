# **1. Introdução**

Atualmente é inimaginável a vida sem energia elétrica. Eletricidade está amplamente presente tanto em processos produtivos industriais quanto na comodidade de nossos lares. Portanto, direta ou indiretamente, praticamente todo cidadão deste planeta é um consumidor de energia elétrica.
 
A cada dia novos aparelhos, impulsionados por energia elétrica, são criados visando melhorar a qualidade de vida e bem-estar dos cidadãos. Entretanto, estes mesmos dispositivos que simplificam nossas vidas, nos fazem cada vez mais dependentes da energia elétrica. Desta forma, é notório o aumento progressivo do consumo de eletricidade em nossos lares ao longo dos anos. E, na medida que o processo de modernização permanece acontecendo, é fácil prever a tendência de um consumo ainda maior de eletricidade no futuro.
 
No Brasil, a maior parte da energia elétrica produzida e distribuída para consumo pelo cidadão comum é produzida em usinas hidroelétricas, consequência da vasta rede fluvial que o país possui. Assim, segundo dados da Agência Nacional de Energia Elétrica (ANEEL) relativos a produção de energia elétrica, 62% da capacidade instalada em operação no país vem das hidrelétricas, 28% das termelétricas (combustíveis fósseis, carvão mineral, gás natural, nuclear e biomassa) e os 10% restantes vêm de usinas eólicas e da importação de outros países.
 
Em relação ao custo da energia elétrica no Brasil, um ranking mundial preparado pela Federação das Indústrias do Rio de Janeiro (Firjan), em janeiro de 2017, demonstrou que nosso país pratica o sexto maior preço mundial do megawatt/hora (402,3 Reais/MW/h). E que, além da indesejada sexta posição, este valor fica 46% acima da média internacional.
 
Desta forma, o consumo racional de energia elétrica é importante tanto por motivos financeiros (evitar gastos excessivos e desnecessários) quanto por motivos ambientais, pois a geração de energia depende da exploração de recursos naturais.
 
Acreditamos que a melhor forma do cidadão comum economizar energia elétrica, é através do conhecimento detalhado dos hábitos de consumo praticados localmente em seu próprio lar. Conhecer o consumo energético de cada aparelho doméstico assim como o seu grau de utilização mensal pode auxiliar o usuário de eletricidade e sua família a identificar potenciais focos de desperdício, assim como otimizar o uso de utensílios indispensáveis. Além disso, é importante considerar a característica intrinsecamente dinâmica do consumo elétrico de um domicílio durante determinado período de tempo. Desta forma, o conhecimento dos padrões dinâmicos de consumo por aparelho pode também ajudar com uma maior previsibilidade dos gastos mensais familiares.

O presente projeto visa a formalização das bases para o desenvolvimento de uma aplicação web que proporcione ao cidadão comum um melhor gerenciamento do consumo de energia elétrica em seu próprio domicílio.

## **Problema**

A energia elétrica pode ser considerada um serviço essencial que representa grande impacto nos gastos totais de uma residência. Significando que boa parte do orçamento das famílias Brasileiras, referem-se aos hábitos diários de consumo de energia elétrica, consumo esse que se torna cada vez mais oneroso com o advento de novas soluções tecnológicas.

No ano de 2020, com o desencadeamento da Covid-19, observou-se que o consumo residencial aumentou devido às medidas protetivas instauradas pelo Governo Brasileiro, como o isolamento e distanciamento social, que alocaram o ambiente de trabalho para a residência particular. 

Logo, saber identificar de forma clara e precisa a quantidade em Reais (R$) destinados para cada utensílio, é uma ótima solução para identificar os causadores de um dispêndio alto, e assim agir para a adequação do uso tendo como base, o nível de consumo. Porém, realizar este acompanhamento pode ser dificultoso por demandar tempo na busca de dados específicos, sem o uso de uma ferramenta própria com informações técnicas e precisas, sobre os aparelhos eletrônicos, como por exemplo, a corrente, a tensão e a potência.

Desse modo, o problema que se busca resolver é, como o cidadão comum pode gerir melhor o consumo de energia em seu próprio domicílio, utilizando-se de um sistema de informação baseado em uma aplicação web? 

## **Objetivos**

Objetivo Geral:
 
O presente projeto visa desenvolver uma aplicação web para auxiliar no registro e controle dinâmico, pelo usuário, do consumo de energia elétrica em seu próprio domicílio. Além de informar, de forma consciente, sobre métodos para economizar e otimizar o uso desses eletrodomésticos.
 
Objetivos Específicos:
 
* Identificar/reconhecer os padrões de consumo de energia por aparelho doméstico em cada domicílio;
 
* Fornecer métricas que auxiliem ao usuário a adequação do consumo de energia elétrica em seu domicílio de acordo com os limites das bandeiras tarifárias;
 
* Conscientizar sobre a economia elétrica em escala;
 
 * Promover educação do usuário através de documentos que irão facilicitar na compreensão dos serviços prestados pela concessionária e distribuidoras de energia elétrica.

## **Justificativa**

O Anuário Estatístico de Energia Elétrica 2020 (ano base 2019), publicado pela Empresa de Pesquisa Energética, empresa pública vinculada ao Ministério de Minas e Energia, traz as principais informações sobre o consumo de energia elétrica no Brasil, por região. O anuário declarou que o consumo total de energia elétrica no Brasil foi de 482 TWh[1], a classe residencial representa o maior número de unidades consumidoras de eletricidade do país representando 142.781GWh[2]. A região Sudeste, com a população de 88.4 milhões apresentou o consumo per capita de 2.698 kWh[3] por habitante, com concentrações nos estados do Rio de Janeiro e São Paulo.  

>A Região Sudeste também se destaca no país nos prismas da geração, do consumo, da transmissão e da distribuição de energia elétrica. O Sudeste responde por cerca de 50% da carga do Sistema Integrado Nacional (SIN)[4], sendo a principal região consumidora de energia do país.

Observa-se então que a região Sudeste engloba de forma significativa porcentagens altas de consumo elétrico, por habitante, tendo sido responsável por mais de 50% do consumo nacional de eletricidade. Portanto, a aplicação da Web se propõe a atender a população desta Região, uma vez que atenderia incialmente a um significativo número de usuários interessados.

Sobre o quesito do consumo residencial, a propagação da Covid-19 apresentou diversos reflexos na economia do país, como o aumento dos reajustes tarifários e no consumo residencial. Com mais pessoas em casa em razão da pandemia, o consumo de energia residencial cresceu 4,1%, para 148.223 GWh. Ou seja, esse foi o único segmento que registrou crescimento em 2020. Portanto, medidas voltadas para a redução do consumo de energia nunca foram tão necessárias para a economia individual além de contribuir invariavelmente para o meio ambiente[5].

A aplicação da Web Uai-Energy, facilitaria no conhecimento de cada aparelho eletrônico na residência. O usuário selecionaria os equipamentos, por cômodos ou de forma individual, informando a potência e o tempo de uso dos aparelhos. Essas informações serão interligadas com as variações das tarifas econômicas e financeiras de energia, considerando que o total da fatura em Real (R$) é resultado da multiplicação da energia consumida (medida em quilowatt hora) no mês pela tarifa aplicada, acrescido de taxas e impostos. Esses valores são definidos e homologados pela Agência Nacional de Energia Elétrica (Aneel). 
Ao final, a aplicação da web, baseando-se nesses valores, calcularia o consumo total por cômodos ou o consumo por aparelho eletroeletrônico, além de dispor de informações de uso eficiente. Essas informações seriam providas por documentos sobre como otimizar o uso diário dos eletrônicos, com mudanças nos hábitos, como por exemplo, a valorização da iluminação natural, a substituição da lâmpada comum para a de Led e a remoção de aparelhos eletrônicos da tomada.

Embora todas as pessoas possam se beneficiar de soluções para a moderação do uso de energia elétrica, na residência, o foco deste trabalho é o consumidor responsável pelo orçamento familiar. O intuito é disponibilizar uma ferramenta de fácil uso, informativa que promoveria o uso consciente dos aparelhos à base de energia elétrica, residenciais.

[1] O watt-hora é a medida de energia usualmente utilizada em eletrotécnica. Um watt-hora é a quantidade de energia utilizada para alimentar uma carga com potência de um watt pelo período de uma hora. O valor de 1 Wh é equivalente a 3,6×103 J =3,6 kJ =3600 J. 1 terawatt-hora (TWh) = 1 trilhão de watt-hora.

[2] Gigawatt-hora, abreviado como GWh, é uma unidade de energia que representa um bilhão (1 000 000 000) de watt-hora e é equivalente a um milhão de quilowatt-hora. Os gigawatts-hora são frequentemente usados como uma medida da produção de grandes usinas de energia elétrica.

[3] O quilowatt-hora é uma unidade de energia igual a 3600 quilo joules. O quilowatt-hora é comumente usados como uma unidade de cobrança da energia entregue aos consumidores pelas concessionárias de energia elétrica.

[4] Conjunto de instalações e de equipamentos que possibilitam o suprimento de energia elétrica nas regiões do país interligadas eletricamente, conforme regulamentação aplicável.

[5] As emissões de Gases de Efeito Estufa (GEE) provenientes da geração elétrica no Brasil totalizaram 56,3 milhões de toneladas (Mt) de CO2 em 2019, quase 7% superior a 2018.


## **Público-Alvo**

O público-alvo desta aplicação da Web seriam homens e mulheres, sem distinção de classe social, da região Sudeste do Brasil, responsáveis pela administração orçamentária de sua residência, que fazem uso constante de utensílios elétricos, diversos, na vida diária. Ou seja, aqueles que planejam manter o consumo de energia elétrica sob controle, acompanhando um histórico de registro, para mais informações e facilidades no custeio de gastos do consumo elétrico próprio ou de outros membros da residência. E que pretendem se conscientizar sobre o uso eficiente dos aparelhos e os impactos dos hábitos diários no meio ambiente. Ao observar variações mensais de consumo e estabelecer uma comparação com sua própria média, identificando períodos de aumento e suas possíveis causas – clima, mudanças de hábitos, aparelho novo ou visitas recebidas. 

### *Stakeholders*

De acordo R. Edward Freeman e John F. Mcvea (2001), o termo *stakeholders* possui o objetivo de especificar todos os grupos ou partes interessadas sem os quais uma empresa deixaria de existir. Nessa especificação, estariam, por exemplo, os acionistas, os empregados, os fornecedores, os clientes, os credores e a sociedade. Atualmente, a definição mais utilizada para o conceito de *stakeholders* ou de partes interessadas é a de Freeman (2010), segundo quem o termo stakeholder foi definido, em um amplo sentido estratégico, como qualquer grupo ou indivíduo que pode afetar ou é afetado pelo alcance dos objetivos da empresa (Freeman et al., 2010).

Segundo Freeman (1984), para o desenvolvimento de estratégias, a organização deve se atentar na busca de respostas para três perguntas básicas sobre seus *stakeholders*: Quem são os _stakeholders_? O que eles querem? Como eles tentarão atingir suas metas e satisfazer seus interesses? 

O presente projeto, com o intuito de realizar os objetivos propostos, fez o mapeamento do público afetado pela criação da aplicação da Web. 

Os *stakeholders* levantados foram classificados primeiramente em os que foram impactados pelo projeto (**_Stakeholders_ de projeto**) e os que foram impactados pelo produto (**_Stakeholders_ de produto**).

**_Stakeholders_ de Produto** são todos aqueles afetados pela Aplicação da Web a ser desenvolvida. Os principais Stakeholders dessa classe são o **Público-Alvo**, como definido anteriormente. Porém, além deles também temos todos os que interagem, diretamente ou não, com a aplicação, trabalham utilizando os resultados obtidos pelo público-alvo, ou serão impactados pelos deploys e pela operação do produto. E são eles:

* Analista de Sistemas;

* Analista de Testes;

* Analista do Banco de dados;

* Desenvolvedor front-end;

* Gerente de Projeto;

* Web designer;

Os **_Stakeholders_ de projeto** são todos aqueles que tem interesse no sucesso do projeto no qual a aplicação da Web está sendo desenvolvida. É de responsabilidade deles o cumprimento de prazos, custos determinados e como a aplicação está sendo desenvolvida. E são eles:

* Analista do Banco de dados;

* Analista de Sistemas;

* Gerente de Projeto;

Após a classificação de impacto por produto ou projeto, os Stakeholders foram classificados pelo grau de envolvimento, necessários, de cada um deles. Foram utilizados **três graus** de envolvimento:

**1-Grau de dependência:** onde são identificados aqueles pelos quais a aplicação da Web requer a interferência direta, para a sua continuidade. Sendo eles:

* Agência Nacional de Energia Elétrica- ANEEL;

* Analista de Sistemas;

* Analista do Banco de dados;

* Analista de Testes;

* Desenvolvedor front-end;

* Distribuidoras do setor elétrico da região Sudeste do Brasil;

* Fabricantes de Eletrônicos;

* Gerente de Projeto;

* Público-Alvo;

* Web Designer;

**2-Grau de participação:** são todos aqueles que devem ser consultados para a tomada de decisões, que demandam um conhecimento técnico específico. Essas decisões são relacionadas apenas às áreas de especialidade. Eles são:

* Desenvolvedor front-end;

* Fabricantes de Eletrônicos;

* Web designer;

**3-Grau de interferência:** são todos aqueles que tomam a decisão final em relação a algum assunto.

* Gerente de Projeto;

* Público-Alvo;

Agora que foram mapeados e classificados os _Stakeholders_, deve-se explanar qual o envolvimento e as necessidades de cada um deles. Com isso, criamos uma tabela simples, como no exemplo abaixo:

| _Stakeholder_ | Tipo de _Stakeholder_ | Grau de Envolvimento | Quando deve haver o envolvimento | Necessidades |
| --------------| --------------------- | -------------------- | -------------------------------- | ------------ |
| Agência Nacional de Energia Elétrica- ANEEL | N/A | Dependência | Durante pesquisas/inclusão de dados | N/A |
| Analista de sistemas | N/A | Dependência | Durante pesquisas/inclusão de dados | Ser consultado para a compreensão da necessidade de negócio do cliente, com o fim de especificar, por escrito, o que precisa ser alterado no projeto; |
| Analista de Testes | Produto | Dependência | Sempre que necessário testar novas atualizações | Ser consultado para a validação do projeto, para verificar se a etapa de codificação cumpriu o que foi solicitado, na especificação do analista de sistemas, além de verificar se há erros na aplicação; |
| Analista do Banco de dados | Projeto/Produto | Dependência | Sempre que necessário para a alteração/inclusão de dados | Ser consultado para definir a arquitetura do banco de dados em caso de alterações; Ser consultado para a criação dos comandos, para tratamento de rotinas mais complexas de manipulação de dados; |
| Desenvolvedor front-end | Produto | Participação/Dependência | Sempre que necessárias atualizações | Criar uma boa experiência do usuário; Garantir boa performance usuário/servidor; Ser consultado para alterar as especificações de negócio do aplicativo em código |
| Distribuidoras do setor elétrico da região Sudeste do Brasil | N/A | Dependência | Durante pesquisas/inclusão de dados | N/A |
| Fabricantes de Eletrônicos | Produto | Dependência | Durante pesquisas/inclusão de dados | N/A |
| Gerente de Projeto | Projeto/Produto | Interferência/Dependência | Sempre que necessário  | Decidir prioridades; Participar das demonstrações do produto |
| Público-Alvo | Produto | Interferência/Dependência | Durante pesquisas | Aplicação de fácil uso; Listagem dos modelos de aparelhos eletrônicos; Informação sobre tarifas; Guia de boas práticas; |
| Web Designer| Produto | Participação | Quando houver alguma atualização do produto | Quer um documento de especificação para elaborar todo o desenho das interfaces do aplicativo, priorizando a usabilidade; |

Com o mapeamento dos _stakeholders_, o presente projeto pode reconhecer com quais públicos, organizações e especialistas a aplicação da Web se relaciona, qual o tipo de relação e expectativas geradas, que permitem identificar quais exigem um contato estratégico.
