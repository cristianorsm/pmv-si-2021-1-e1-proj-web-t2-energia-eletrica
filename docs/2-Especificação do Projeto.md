# **2. Especificação do Projeto**

 
Este projeto visa criar um modelo de aplicação, que atenda a usuários do âmbito residencial tais com: moradores de casas com porte diversificado, moradores de condomínios e prédios residenciais, visando auxiliar na identificação e compreensão de medidas que resultem em economia de energia. 
Com a implementação do sistema desenvolvido, o consumidor doméstico poderá ter conhecimento do consumo nominal de cada eletrodoméstico, permitindo assim tomar decisões para utilizar lós de forma mais racional e que consequentemente gerar economia de energia. 

Objetivo:
 
Fornece ferramentas interativas que permitem aos usuários consultar e selecionar as estratégias mais interessantes para um consumo energético mais eficiente, promovendo educação e conscientização do mesmo.
 
Premissas verificadas:
 
Identificar comportamentos, hábitos e características de consumo por aparelho
Averiguar o nível de percepção dos moradores residenciais sobre a importância da eficiência energética,
Estimular o consumo de energia elétrica em cada residência de forma consciente.
 
 Características do consumo operacional por equipamento:
 
Os principais equipamentos presentes em residências consomem energia
basicamente de fontes como eletricidade, GLP, gás natural, lenha ou carvão vegetal. As quantidades e características destes equipamentos estão fortemente ligadas à renda de seus ocupantes.
Suas funções cumprem requisitos básicos de sobrevivência, tais como alimentação, higiene, conforto ambiental, iluminação, condicionamento de ambientes e entretenimento tais como aparelhos televisores, aparelhos de som, aparelhos celulares, aparelhos de vídeo e aparelhos de informática.
 
Ocasionalmente algumas atividades profissionais, ou de complementação profissional, são desenvolvidas em âmbito residencial, acrescentando assim outras categorias de equipamentos tais como: Computadores, impressoras e monitores, entre outros. Visto que esta situação é uma tendencia crescente no atual senário econômico e social. Desta forma vemos uma tendencia crescente nos gastos com energia elétrica residencial, que não são considerados no orçamento nos casos de home office.

Informações anexas:
Participação dos eletrodomésticos no consumo residencial na região Sudeste:
Lampada 19,0%
Chuveiro 26,0%
Condicionamento de ambiental 11,0%
TV 10,0%
Som 3,0%
Ferro de passar roupa 3,0%
Lavadora de roupa 1,0%
Geladeira 22,0%
Freezer 5,0%

O equipamento que causa mais impacto na curva de carga da Região Sudeste é o chuveiro elétrico, seguido pelas lâmpadas e pela TV. O horário de maior carga é entre as 18:00 horas e as 22:00 horas. Este é o horário em que as pessoas tomam banho, ligam a iluminação, cozinham e assistem TV. Existe um aumento da demanda por energia elétrica também pela manhã, entre 06:00 horas e 09:00 horas, causado principalmente pela utilização do chuveiro elétrico. A geladeira e o freezer são utilizados durante todo o dia. Existe também uma considerável quantidade de lâmpadas que são utilizadas durante todo o dia. O ar condicionado possui maior utilização durante toda a noite. A TV embora tenha sua utilização perceptível durante todo o dia, possui um período de maior utilização entre 19:00 horas e 23:00 horas. Os aparelhos de som são utilizados de manhã até o final da tarde e o ferro de passar roupa no início da manhã e no final da tarde. A lavadora de roupa é utilizada principalmente no início da manhã e à noite.

Fontes: Avaliação do mercado de eficiência energética no Brasil - Ano Base 2005 Classe residencial - PROCEL - Eletrobrás 

## **Personas**

Lembre-se que você deve ser enumerar e descrever precisamente e personalizada todos os clientes ideais que sua solução almeja.

> **Links Úteis**:
> - [Rock Content](https://rockcontent.com/blog/personas/)
> - [Hotmart](https://blog.hotmart.com/pt-br/como-criar-persona-negocio/)
> - [O que é persona?](https://resultadosdigitais.com.br/blog/persona-o-que-e/)
> - [Persona x Público-alvo](https://flammo.com.br/blog/persona-e-publico-alvo-qual-a-diferenca/)
> - [Mapa de Empatia](https://resultadosdigitais.com.br/blog/mapa-da-empatia/)
> - [Mapa de Stalkeholders](https://www.racecomunicacao.com.br/blog/como-fazer-o-mapeamento-de-stakeholders/)
>


Neste projeto, as personas levantadas durante a análise do problema são apresentadas abaixo:

Bruno Silva, 58 anos, Advogado e autônomo na capital do estado de São Paulo, utiliza os meios de mídia E-mail, Facebook, WhatsApp e Sistemas Jurídicos Eletrônicos, para o trabalho. Tinha o desejo de criar um escritório em sua residência totalmente adaptado. Isso inclui a possibilidade de uso dos meios de comunicação de forma prática e eficiente. Um espaço separado e dedicado na residência, para o uso de computadores, impressora, televisão, máquina de café, com boa iluminação e ventilado. Porém, a adaptação do escritório em casa exigiu o uso de diversos equipamentos e utensílios dependentes de energia elétrica. Consequentemente, os gatos mensais referentes ao uso desses equipamentos tornaram-se demasiadamente onerosos. Logo, Bruno está buscando meios de economizar além de obter informações mais precisas sobre os utensílios elétricos e suas taxas de consumo elétrico. A aplicação da Web irá auxiliar no registro de cada utensílio e por seguinte na identificação dos padrões de consumo de energia, de forma individual, irá possibilitar que ele próprio adeque este consumo, baseando-se nos limites das bandeiras tarifárias, além de conscientizar sobre a economia elétrica em escala, ao promover educação de Bruno através da comparação do consumo de energia em seu domicílio com um manual de boas práticas.

Beatriz Nunes, 38 anos, é formada em administração de empresas, casada, mãe de três filhos com idades entre 5 e 11 anos e mora em Belo Horizonte Minas Gerais. Sua rotina diária se divide entre o trabalho em uma empresa e os cuidados com a saúde, educação, criação dos filhos e tarefas domésticas. Juntamente com o seu marido seu grande desafio está no controle dos gastos com a residência e a educação dos filhos. Porém, com a quarentena instaurada, devido à pandemia da Covid-19, os custos com a energia elétrica aumentaram. Isso, por intermédio do uso constante pelas crianças de aparelhos celulares, televisores e computadores, direcionados para o estudo escolar à distância. Portanto, Beatriz pretende encontrar um meio de controle dessa demanda de uso da energia elétrica. 

Elisane Melo Leite, 61 anos, Administradora e Publicitária. É dona de uma agência de publicidade em Belo Horizonte, Minas Gerais, com 18 funcionários. Recentemente institui o trabalho na modalidade “home-office” em sua empresa. Assim, todos os funcionários, incluindo ela própria, passaram a trabalhar em seu próprio domicílio. Elisane é divorciada, mora sozinha e tem um estilo de vida bastante agitado devido às múltiplas tarefas que executa relacionadas ao trabalho e vida pessoal. Utiliza, por isso, em sua casa diversos utensílios eletrônicos os quais ela considera poupar seu exíguo tempo como: lavadora de roupas, lavadora de louças, cafeteira elétrica, fogão elétrico, televisores, telefones celulares, relógio despertador e iluminação automatizada. Com o trabalho remoto recém instituído, foi necessário a instalação de dois computadores em seu apartamento. Vários destes aparelhos permanecem ligados na eletricidade 24horas por dia, inclusive aos finais de semana. Com a visão de administradora que possui, Elisane deseja otimizar os gastos de energia elétrica em sua residência, que agora também é seu local de trabalho. Seu objetivo principal é economizar no pagamento de suas contas de luz e também desempenhar uma responsabilidade social uma vez que a fonte principal de energia elétrica advém de recursos naturais. Além disso ela também acredita que a nova forma de trabalho, em seu domicílio, tem funcionado bem, pretende não retornar ao seu antigo modelo de atividade. Desta forma, acredita que faz ainda mais sentido ter um consumo elétrico mais inteligente em seu apartamento uma vez que os benefícios a longo prazo são ainda mais promissores. Neste contexto, uma aplicação web dedicada a computar o consumo elétrico por aparelho em sua residência seria perfeitamente adequado para gerar informação fidedigna sobre o seu nova padrão de consumo elétrico. Proporcionando, portanto, uma melhor tomada decisão a respeito de potenciais pontos de consumo elétrico exagerado  e também previsibilidade dos seus gastos com energia elétrica de forma geral.

Robson Fernandes, 25 anos, formado em publicidade e propaganda e trabalha em uma Agencia de mídia digital como analista de conteúdo e mora na cidade do Rio de Janeiro, Estad do Rio. Atualmente, Robson mora sozinho, em um pequeno apartamento na região sul da cidade do Rio de Janeiro. A sua rotina diária se divide entre ir para o trabalho e voltar para casa, normalmente Robson, não utiliza computador em casa, prefere ler um livro ou brincar com seu pet sempre que chega do trabalho. Apesar do estilo de vida simples que Robson cultiva, Robson não abre mão de terminados confortos dentro de sua casa tais como: Televisão, vídeo game, home theater, Geladeira, frigobar, forno elétrico e micro-ondas. E mesmo com todos estes eletrodomésticos, Robson num teve que se preocupa com os gastos gerados pela utilização dos mesmos, pois ele ficava a maior parte de seu dia no seu local de trabalho. Porem com o surgimento da pandemia, o cotidiano de Robson mudou, o seu trabalho passou para o estilo home office, consequentemente, Robson se viu obrigado a montar um pequeno escritório em seu apartamento para atender as demandas do seu trabalho. Como o passar do tempo, Robson percebeu que os seus gastos com energia elétrica estavam aumentando e que diante desta situação, Robson sentiu a necessidade de fazer o gerenciamento dos seus gastos com energia elétrica. A percepção de Robson para com a necessidade de gerar economia em seus gastos com eletricidade, levou Robson a busca recursos que fossem atendidos por plataformas web, visto seria algo simples e de fácil manuseio para ele por se tratar de uma pessoa cem porcento conectada.





## **Histórias de Usuários**

Doravante à análise das personas identificadas, com a compreensão de seus hábitos diários, foram registradas as seguintes histórias de usuários:

|EU COMO... `PERSONA`| QUERO/PRECISO ... `FUNCIONALIDADE` |..PARA ... `MOTIVO/VALOR`..                     |
|--------------------|------------------------------------|----------------------------------------        |
|Bruno Silva | Manter um registro de consumo de aparelhos elétricos, que mais utiliza | Entender o consumo individual, de cada aparelho|
|Bruno Silva | Entender os valores de cobrança | Economizar energia; otimizar o uso dos aparelhos; verificar a necessidade de substituir os aparelhos que mais implacam mensalmente na conta |
|Beatriz Nunes | Maior controle gasto energia | Economizar no gasto mensal de energia elétrica |  
|Elisane Melo Leite | Identificar melhor o novo padrão de gasto de energia elétrica em seu domicílio     | Economizar no pagamento de suas contas de luz e também desempenhar uma responsabilidade social uma vez que a fonte principal de energia elétrica advém de recursos naturais                                                |
|Robson Fernandes  | Otimizar meus gastos com energia elétrica e entender meu novo padrão de consulto | Criar uma estratégia de economia de energia e otimização do uso de determinados aparelhos eletroeletrônicos, com intuito de gerar economia mensal de energia                                                |                 
|Nome |                                    |                                                |    

> **Links Úteis**:
> - [Histórias de usuários com exemplos e template](https://www.atlassian.com/br/agile/project-management/user-stories)
> - [Como escrever boas histórias de usuário (User Stories)](https://medium.com/vertice/como-escrever-boas-users-stories-hist%C3%B3rias-de-usu%C3%A1rios-b29c75043fac)
> - [User Stories: requisitos que humanos entendem](https://www.luiztools.com.br/post/user-stories-descricao-de-requisitos-que-humanos-entendem/)
> - [Histórias de Usuários: mais exemplos](https://www.reqview.com/doc/user-stories-example.html)
> - [9 Common User Story Mistakes](https://airfocus.com/blog/user-story-mistakes/)

## **Requisitos**
Segundo o Dicio (dicionário online de português) a palavra requisito expressa condições básicas e necessária para se obter alguma coisa ou para alcançar determinado propósito, na Engenharia de requisitos, são solicitações desejos e necessidades expressa pelos usuários, para o desenvolvimento de um software. Os requisitos estão presentes ao longo de todo ciclo de vida do software. Os requisitos definem o que é solicitado ao sistema e com quais limitações ele irá operar. De forma bem simples podemos considerar que requisitos de software é toda a abstração de um recurso, funcionalidade ou resultado esperado de um sistema. O processo de levantamento de requisitos é responsável por identificar todas essas necessidades e manter toda a documentação. 

Os requisitos definem os serviços que o sistema deveria oferecer, e são classificados em dois tipos requisitos funcionais e os requisitos não funcionais: 

As tabelas que se seguem apresentam os requisitos funcionais e não funcionais que detalham o escopo do projeto.

### **Requisitos Funcionais**

|ID    | Descrição do Requisito  | Prioridade |
|------|-----------------------------------------|----|
|RF-001| Permitir que o usuário cadastre tarefas | ALTA | 
|RF-002| Emitir um relatório de tarefas no mês   | MÉDIA |


### **Requisitos não Funcionais**

|ID     | Descrição do Requisito  |Prioridade |
|-------|-------------------------|----|
|RNF-001| O sistema deve ser responsivo para rodar em um dispositivos móvel | MÉDIA | 
|RNF-002| Deve processar requisições do usuário em no máximo 3s |  BAIXA | 





Com base nas Histórias de Usuário, enumere os requisitos da sua solução. Classifique esses requisitos em dois grupos:

- [Requisitos Funcionais
 (RF)](https://pt.wikipedia.org/wiki/Requisito_funcional):
 correspondem a uma funcionalidade que deve estar presente na
  plataforma (ex: cadastro de usuário).
- [Requisitos Não Funcionais
  (RNF)](https://pt.wikipedia.org/wiki/Requisito_n%C3%A3o_funcional):
  correspondem a uma característica técnica, seja de usabilidade,
  desempenho, confiabilidade, segurança ou outro (ex: suporte a
  dispositivos iOS e Android).
Lembre-se que cada requisito deve corresponder à uma e somente uma
característica alvo da sua solução. Além disso, certifique-se de que
todos os aspectos capturados nas Histórias de Usuário foram cobertos.

## **Restrições**

O projeto está restrito pelos itens apresentados na tabela a seguir.

|ID| Restrição                                             |
|--|-------------------------------------------------------|
|01| O projeto deverá ser entregue até o final do semestre |
|02| Não pode ser desenvolvido um módulo de backend        |


Enumere as restrições à sua solução. Lembre-se de que as restrições geralmente limitam a solução candidata.

> **Links Úteis**:
> - [O que são Requisitos Funcionais e Requisitos Não Funcionais?](https://codificar.com.br/requisitos-funcionais-nao-funcionais/)
> - [O que são requisitos funcionais e requisitos não funcionais?](https://analisederequisitos.com.br/requisitos-funcionais-e-requisitos-nao-funcionais-o-que-sao/)
