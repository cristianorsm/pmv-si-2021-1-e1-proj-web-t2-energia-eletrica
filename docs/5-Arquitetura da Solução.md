# Arquitetura da Solução

Definição de como o software é estruturado em termos dos componentes que fazem parte da solução e do ambiente de hospedagem da aplicação.

## Diagrama de componentes

Diagrama que permite a modelagem física de um sistema, através da visão dos seus componentes e relacionamentos entre os mesmos.

Os componentes que fazem parte da solução são apresentados na Figura abaixo:

![Arquitetura solução](https://user-images.githubusercontent.com/61883996/120396708-687dd400-c30d-11eb-9386-1932851a66f3.png)

A solução implementada conta com os seguintes módulos:
- **Navegador** - Interface básica do sistema  
  - **Páginas Web** - Conjunto de arquivos HTML, CSS, JavaScript e imagens que implementam as funcionalidades do sistema.
   - **Local Storage** - armazenamento mantido no Navegador, onde são implementados bancos de dados baseados em JSON.
 - **API Setor Elétrico** - plataforma que permite o acesso às notícias exibidas no site.
 - **Hospedagem** - local na Internet onde as páginas são mantidas e acessadas pelo navegador. 

>A imagem a seguir ilustra o fluxo do usuário em nossa solução. 
>
>![Arquitetura Solução](https://user-images.githubusercontent.com/61883996/118895147-f99b8680-b8db-11eb-8042-3e526b2fcb65.jpg)

Assim que o usuário entra na plataforma, ele é apresentado à tela inicial (Tela 1) onde ele é confrontado com os Menus de acesso ao Sistema, "Entre aqui" ; "Registre aqui" ; "Simulador de Consumo"; "Registros" e "Entenda sua conta de Luz".

Caso ele opte por seguir por - "Registre Aqui" (Tela 1.1): ele é redirecionado para o registro de um usuário novo. Se clicar em "Entre aqui"(Tela 1.2), irá realizar o Log In. As duas (Telas 1.1 e 1.2) levam o usuário para a (Tela 2), tela demonstrativa de acesso ao sistema autorizado.

Ao clicar no Menu "Entenda sua Conta de Luz" (Tela 2) - irá para a (Tela 3): Tela demonstrativa com Links para a visualização de páginas informativas sobre a conta de luz.

Ao clicar no Menu "Registros" (Tela 2) - irá para a (Tela 5): Tela de acesso ao registros do sistema, pelos usuários cadastrados no sistema, para consulta dos Relatórios de Consumo mensal de energia elétrica, por cômdos ou aparelhos individuais. Se selecionar Menu Consulta "Registros por Cômodos" será redirecionado para os Relatórios (Tela 5.2) geridos pelo sistema, do consumo de energia elétrica do usuário cadastrado, por cômodos, com demonstrativo do período de tempo dos registros e o valor do consumo em reais. E se clicar em Menu Consulta "Registros por Eletroeletrônicos" será redirecionado para os Relatórios (Tela 5.1) geridos pelo sistema, do consumo de energia elétrica do usuário cadastrado, por aparelhos individuais, com demonstrativo do período de tempo dos registros e o valor do consumo em reais.

Ao clicar no Menu "Simulador de Consumo" (Tela 2) - irá para a (Tela 4), para o Menu dos Aparelhos Eletroeletrônicos e Cômodos cadastrados no sistema:

Se selecionar "Selecione os aparelhos eletroeletrônicos" irá para a (Tela 4.1) da lista em ordem alfabética, dos aparelhos eletroeletrônicos cadastrados no sistema. O usuário pode selecionar os aparelhos para iniciar o cadastro de controle de gastos de energia elétrica, por aparelho. Ao selecionar um aparelho o usuário encontra as (Telas 4.1.3/4.1.3.1), tela de registro no sistema, por usuários cadastrados, dos aparelhos eletroeletrônicos selecionados para gerar relatório de consumo/tela de registro no sistema, por usuários cadastrados, de aparelhos eletroeletrônicos, não existentes no sistema, selecionados para gerar relatório de consumo, respectivamente.
Após ao clicar em "Adicionar" o usuário é redirecionado para a (Tela 4.4), tela de visualização dos registros de consumo por mês, gerados pelo sistema, de acesso por usuários cadastrados no sistema. As (Telas 4.1.5 e 4.1.6) são telas de visualização dos registros de consumo por mês, gerados pelo sistema, de acesso à usuários não cadastrados no sistema.

Se selecionar "Selecione os Cômodos" irá para a (Tela 4.2) tela do Layout dos Cômodos cadastrados no sistema, para acesso à lista de aparelhos eletroeletrônicos, separados em cômodos, para o usuário poder selecionar os aparelhos e iniciar o cadastro de controle de gastos de energia elétrica. Dependendo do cômodo que selecionar o usuário pode ser redirecionado para as (Telas 4.2.1-7), telas demonstrativas dos cômodos, com as ilustrações dos aparelhos eletroeletrônicos para seleção. Ao selecionar um aparelho eletroeletrônico, de cada cômodo correspondente, o usuário encontra a (Tela 4.2.8), tela de registro no sistema, por usuários cadastrados, dos aparelhos eletroeletrônicos, por cômodo, selecionados para gerar relatório de consumo.
Após ao clicar em "Adicionar" o usuário é redirecionado para a (Tela 4.2.9), tela de visualização dos registros de consumo por mês, gerados pelo sistema, de acesso por usuários cadastrados no sistema.

## Tecnologias Utilizadas

Durante o desenvolvimento da Aplicação Web foram utilizadas as tecnologias: 

O HTML5, como linguagem de marcação, para estruturas o conteúdo da aplicação web. O CSS, como mecanismo de adicionar estilos nas páginas HTML, a linguagem de programação JavaScript, para ser interpretado pelo browser. Utilizamos APIs WEB através de códigos JavaScript. O SVG, Gráficos Vetoriais Escaláveis (em inglês: Scalable Vector Graphics), para descrever as imagens como conjuntos de vetores e formas. O Visual Code foi o IDE de desenvolvimento escolhido, por ser open source, disponível em múltiplos ambientes: Windows, Linux e MacOs. Além de possuir o suporte o JavaScript, TypeScript, JSON, HTML, CSS, SCSS, e Less.

Utilizou-se também o Git que é um sistema de controle de versões, usado principalmente no desenvolvimento de software, que integrado com o servidor Github para o controle do fluxo do projeto. 



## Hospedagem

Assim como está acontecendo com as ferramentas de desenvolvimento, a estrutura de hospedagem do nosso site está baseada em plataforma gratuita de hospedagem.
Partindo deste princípio a nossa aplicação será hospedada no Heroku. Plataforma de hospedagem em nuvem que suporta várias linguagens de programação.
Enderção da aplicação:  www.herruko.aienergy.com.br

Para o _deploy_ o Heroku utiliza o Git.
