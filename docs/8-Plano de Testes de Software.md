# Plano de Testes de Software

1. Visão Geral - TESTE DE FUNCIONALIDADE


1.1	Objetivo

Este documento de Plano de Testes tem como objetivo listar os Requisitos que serão testados recomendando e descrevendo as estratégias a serem empregadas nesses testes. Este documento também identifica os recursos necessários e disponibiliza uma estimativa dos esforços de teste.

1.2	Descrição do produto a Ser Testado

Trata-se da aplicação Web denominada UaiEnergy, desenvolvida baseda nas linguagens HTML, CSS e JavaScript. Nesta aplicação, o usuário, após seu registro inicial, é capaz de introduzir dados básicos dos aparelhos eletrônicos utilizados em sua residência que proporcionariam um cálculo total do consumo de energia elétrica naquele domicílio.
Assim, aplicação da Web Uai-Energy, visa facilitar o conhecimento do gasto energético de cada aparelho eletrônico em uma residência. Ao utilizar aplicação UaiEnergy, usuário selecionaria os equipamentos, por cômodos, informando a potência e o tempo de uso dos aparelhos. Essas informações serão interligadas com as variações das tarifas econômicas e financeiras de energia, considerando que o total da fatura em Real (R$) é resultado da multiplicação da energia consumida (medida em quilowatt hora) no mês pela tarifa aplicada, acrescido de taxas e impostos.


2.	ESCOPO

2.1	Descrição de Casos de Uso

O presente planejamento de testes de funcionalidade baseia-se na proposta de Casos de Teste que foram elaborados baseados nos requisitos funcionais já mencionados no documento de Especificação do Projeto.
Desta forma, foram apresentados os seguintes Casos de Teste (CT):
- CT – 01 – Acesso e registro inicial do usuário;
- CT – 02 – Gerenciamento de dados do usuário
- CT – 03 – Seleção do aparelho eletrônico a ser registrado
- CT – 04 – Consulta dos aparelhos eletrônicos residenciais
- CT – 05 – Acesso ao menu de cômodos
- CT – 06 – Visualizar informações de educação em Entenda sua Conta
- CT – 07 – Visualizar tela de início


3.	RESUMO DOS TESTES PLANEJADOS

Este planejamento de testes diz respeito a fase de testes de funcionalidade. Sendo utilizados para sua confecção os requisitos apresentados no documento de Especificação de Projeto e além de dados do Projeto de Interface.


4.	CATEGORIAS DE TESTES

4.1	Teste de Funcionalidade

O teste de funcionalidade consiste em uma série de subtestes (técnicas), cujo objetivo é atestar se a aplicação é capaz de desempenhar as funções que se propõe a fazer. As técnicas mais comuns englobadas pelo teste funcional são os testes denominados caixa-branca e caixa-preta.
O teste de caixa-branca tem como foco a análise do comportamento interno do software, ou seja, o seu código-fonte. Já o teste de caixa-preta é feito em cima das funções que devem ser desempenhadas pelo programa.

No caso da aplicação web UAiEnergy,os  requisitos básicos para realização dos testes de funcionalidade são:
- Site publicado na Internet
- Navegador da Internet - Chrome, Firefox ou Edge
- Conectividade de Internet para acesso  às plataformas (APISs)

Os testes de funcionalidades a serem realizados na aplicação desenvolvida foram propostos de acordo com os requisitos funcionais já mencionados no documento de Especificação do Projeto. Os casos de testes planejados são descritos a seguir.

Caso de Teste:	CT – 01 – Acesso e registro inicial do usuário

Requisito Associado:	RF04 - O registro do usuário, com a geração de um Login e Senha requererá: a) Nome; b) Email; c) Senha;
Objetivo do Teste:	Verificar se o registro do usuário acontece adequadamente
Passos:
1 – Acessar a tela de registro – botão Registre Aqui da tela principal
2 – Informar Nome, E-mail e Senha;
3 – Clicar em Criar Conta
Critérios de Êxito:	- Conta será criada e usuária encaminhado à tela de Log-in


Caso de Teste:	CT – 02 – Gerenciamento de dados do usuário

Requisito Associado:	RF05 - O sistema deverá permitir gerenciar dados de usuários
Objetivo do Teste:	Verificar se o registro do usuário pode alterar seus dados de registro de aparelhos eletrônicos
Passos:
1 – Acessar a tela de registro de aparelhos e cômodos
2 – Alterar os registros de acordo com a necessidade do usuário
3 – Verificar o resultado das alterações na tela de consulta de registros
Critérios de Êxito:	- Usuário identificará alterações de valores de consumo previsto na tela de consulta


Caso de Teste:	CT – 03 – Seleção do aparelho eletrônico a ser registrado

Requisito Associado:	RF02 - A seleção do exemplo do aparelho eletrônico, no sistema, requererá a inclusão da: a) Quantidade de aparelhos; b) Tempo de Uso de horas/dia; c) Potência;
Objetivo do Teste:	Verificar se o registro dos aparelhos ocorre corretamente
Passos:
1 – Acessar a tela de registro de aparelhos e cômodos
2 – Fazer registro de novo aparelho incluindo todos seus dados solicitados
3 – Verificar a inclusão do aparelho com a modificação dos resultados de consumo na tela de consulta de registros
Critérios de Êxito:	- Usuário identificará alterações de valores de consumo previsto na tela de consulta


Caso de Teste:	CT – 04 – Consulta dos aparelhos eletrônicos residenciais

Requisito Associado:	RF01 - O sistema deverá permitir o usuário consultar os modelos de aparelhos eletrônicos residenciais
Objetivo do Teste	Verificar se o usuário pode consultar os aparelhos registrados distribuídos por cômodos em sua residencia
Passos:
1 – Acessar a tela de seleção de cômodos
2 – Clicar no botão do cômodo desejado
3 – Usuário deverá ser levado à uma tela com os principais aparelhos sugeridos para o cômodo selecionado
4 – Clicar no botão do aparelho desejado e fazer a consulta ou registro
Critérios de Êxito:	- Usuário deve ser capaz de selecionar os aparelhos sugeridos na aplicação e fazer sua consulta, registro ou alteração


Caso de Teste:	CT – 05 – Acesso ao menu de cômodos

Requisito Associado:	RF03 - O sistema apresentará um menu de acesso ao usuário com subdivisões por cômodos: a) Sala; b) Quarto; c) Cozinha; d) Escritório; e) Banheiro; f) Lavanderia; g) Garagem; h) Área externa
Objetivo do Teste:	Verificar se o usuário pode consultar e selecionar o menu de cômodos
Passos:
1 – Acessar a tela de seleção de cômodos
2 – Clicar no botão do cômodo desejado
3 – Usuário deverá ser levado à uma tela com os principais aparelhos sugeridos para o cômodo selecionado
Critérios de Êxito:	- Usuário deve ser direcionado a tela seguinte com os aparelhos já sugeridos pelo sistema para consulta e registro


Caso de Teste:	CT – 06 – Visualizar informações de educação em Entenda sua Conta

Requisito Associado:	RF06 - O sistema apresentará um Menu com informativos sobre como é cobrada a conta de energia elétrica
Objetivo do Teste:	Verificar se o usuário pode consultar e selecionar o menu de cômodos
Passos:
1 – Acessar a tela Inicial
2 – Clicar em Endenda a sua Conta de Luz
3 – Usuário registrado ou não registrado deverão ser direcionados para a tela Entenda Sua Conta onde terão acesso aos botões Por Dentro da Conta de Luz e Como Entender a Conta de Luz
Critérios de Êxito:	- Ao clicar nos botões Por Dentro da Conta de Luz e Como Entender a Conta de Luz o usuário sera direcionado a uma nova janela com material para leitura e consulta de órgão oficiais com ANEEL


Caso de Teste:	CT – 07 – Visualizar tela de início

Requisito Associado:	RF07 - A interface básica, além de disponibilizar funcionalidades para a já referida consulta de aparelhos eletrônicos, deve incluir opções para acesso ao sistema (para utilizadores autorizados) e registro de novos utilizadores
Objetivo do Teste:	Verificar se o usuário pode consultar e selecionar o menu de cômodos
Passos:
1 – Acessar o navegador
2 – Entrar na tela de início a través da URL da aplicação
3 – Visualizar a página de inicio – o botão Entenda sua Conta deve fornecer material disponível para usuários não registrados
Critérios de Êxito:	- A página inicial deve ser aberta com os seguintes botões disponíveis: Entenda sua Conta, Simulado de Consumo, Entre Aqui, Registre Aqui


5.	FLUXO DE TRABALHO DE TESTE

Todos os testes de funcionalidade serão realizados individualmente e em conjunto por toda a equipe responsável pelo seu desenvolvimento. Isto é, todos os três integrantes atuais do projeto são responsáveis pela testagem e por sugerir eventuais ajustes. Deve sempre observar as especificações do projeto para propor ajustes ou correções. 


6.	CRONOGRAMA E MARCOS DO PROJETO

A aplicação deverá esta testada e, se for o caso, corrigida até a data limite de 11 de Julho de 2021. Na data mencionada a aplicação deverá estar pronta para completa implementação. Deve-se observar que o desenvolvimento deste sistema restringe-se às tecnologia básicas da Web no Front-End. 

