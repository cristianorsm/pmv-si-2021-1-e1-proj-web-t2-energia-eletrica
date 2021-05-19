# Arquitetura da Solução

<span style="color:red">Pré-requisitos: <a href="3-Projeto de Interface.md"> Projeto de Interface</a></span>

Definição de como o software é estruturado em termos dos componentes que fazem parte da solução e do ambiente de hospedagem da aplicação.

## Diagrama de componentes

Diagrama que permite a modelagem física de um sistema, através da visão dos seus componentes e relacionamentos entre os mesmos.

Exemplo: 

Os componentes que fazem parte da solução são apresentados na Figura XX.

![Diagrama de Componentes](img/componentes.png)
<center>Figura XX - Arquitetura da Solução</center>

A solução implementada conta com os seguintes módulos:
- **Navegador** - Interface básica do sistema  
  - **Páginas Web** - Conjunto de arquivos HTML, CSS, JavaScript e imagens que implementam as funcionalidades do sistema.
   - **Local Storage** - armazenamento mantido no Navegador, onde são implementados bancos de dados baseados em JSON. São eles: 
     - **Canais** - seções de notícias apresentadas 
     - **Comentários** - registro de opiniões dos usuários sobre as notícias
     - **Preferidas** - lista de notícias mantidas para leitura e acesso posterior
 - **News API** - plataforma que permite o acesso às notícias exibidas no site.
 - **Hospedagem** - local na Internet onde as páginas são mantidas e acessadas pelo navegador. 

> **Links Úteis**:
>
> - [Whimsical](https://whimsical.com/)

A imagem a seguir ilustra a o fluxo do usuário em nossa solução. 

Assim que o usuário entra na plataforma, ele é apresentado à tela inicial (Tela 1) onde ele é confrontado com os Menus de acesso ao Sistema, "Entre aqui" ; "Registre aqui" ; "Simulador de Consumo"; "Registros" e "Entenda sua conta de Luz".

Caso ele opte por seguir por - "Registre Aqui" (Tela 1.1): ele é redirecionado para o registro de um usuário novo. Se clicar em "Entre aqui"(Tela 1.2), irá realizar o Log In. As duas (Telas 1.1 e 1.2) levam o usuário para a (Tela 2), tela demonstrativa de acesso ao sistema autorizado.

Ao clicar no Menu "Entenda sua Conta de Luz" (Tela 2) - irá para a (Tela 3): Tela demonstrativa com Links para a visualização de páginas informativas sobre a conta de luz.

Ao clicar no Menu "Registros" (Tela 2) - irá para a (Tela 5): Tela de acesso ao registros do sistema, pelos usuários cadastrados no sistema, para consulta dos Relatórios de Consumo mensal de energia elétrica, por cômdos ou aparelhos individuais. Se selecionar Menu Consulta "Registros por Cômodos" será redirecionado para os Relatórios (Tela 5.2) geridos pelo sistema, do consumo de energia elétrica do usuário cadastrado, por cômodos, com demonstrativo do período de tempo dos registros e o valor do consumo em reais. E se clicar em Menu Consulta "Registros por Eletroeletrônicos" será redirecionado para os Relatórios (Tela 5.1) geridos pelo sistema, do consumo de energia elétrica do usuário cadastrado, por aparelhos individuais, com demonstrativo do período de tempo dos registros e o valor do consumo em reais.

Ao clicar no Menu "Simulador de Consumo" (Tela 2) - irá para a (Tela 4), para o Menu dos Aparelhos Eletroeletrônicos e Cômodos cadastrados no sistema:

Se selecionar "Selecione os aparelhos eletroeletrônicos" irá para a (Tela 4.1) da lista em ordem alfabética, dos aparelhos eletroeletrônicos cadastrados no sistema. O usuário pode selecionar os aparelhos para iniciar o cadastro de controle de gastos de energia elétrica, por aparelho. Ao selecionar um aparelho o usuário encontra as (Telas 4.1.3/4.1.3.1), tela de registro no sistema, por usuários cadastrados, dos aparelhos eletroeletrônicos selecionados para gerar relatório de consumo/tela de registro no sistema, por usuários cadastrados, de aparelhos eletroeletrônicos, não existentes no sistema, selecionados para gerar relatório de consumo, respectivamente.
Após ao clicar em "Adicionar" o usuário é redirecionado para a (Tela 4.4), tela de visualização dos registros de consumo por mês, gerados pelo sistema, de acesso por usuários cadastrados no sistema. As (Telas 4.1.5 e 4.1.6) são telas de visualização dos registros de consumo por mês, gerados pelo sistema, de acesso à usuários não cadastrados no sistema.

Se selecionar "Selecione os Cômodos" irá para a (Tela 4.2) tela do Layout dos Cômodos cadastrados no sistema, para acesso à lista de aparelhos eletroeletrônicos, separados em cômodos, para o usuário poder selecionar os aparelhos e iniciar o cadastro de controle de gastos de energia elétrica. Dependendo do cômodo que selecionar o usuário pode ser redirecionado para as (Telas 4.2.1-7), telas demonstrativas dos cômodos, com as ilustrações dos aparelhos eletroeletrônicos para seleção. Ao selecionar um aparelho eletroeletrônico, de cada cômodo correspondente, o usuário encontra a (Tela 4.2.8), tela de registro no sistema, por usuários cadastrados, dos aparelhos eletroeletrônicos, por cômodo, selecionados para gerar relatório de consumo.
Após ao clicar em "Adicionar" o usuário é redirecionado para a (Tela 4.2.9), tela de visualização dos registros de consumo por mês, gerados pelo sistema, de acesso por usuários cadastrados no sistema.

![Arquitetura Solução](https://user-images.githubusercontent.com/61883996/118895147-f99b8680-b8db-11eb-8042-3e526b2fcb65.jpg)

## Tecnologias Utilizadas

Descreva aqui qual(is) tecnologias você vai usar para resolver o seu problema, ou seja, implementar a sua solução. Liste todas as tecnologias envolvidas, linguagens a serem utilizadas, serviços web, frameworks, bibliotecas, IDEs de desenvolvimento, e ferramentas.

Apresente também uma figura explicando como as tecnologias estão relacionadas ou como uma interação do usuário com o sistema vai ser conduzida, por onde ela passa até retornar uma resposta ao usuário.


## Hospedagem

Explique como a hospedagem e o lançamento da plataforma foi feita.

> **Links Úteis**:
>
> - [Website com GitHub Pages](https://pages.github.com/)
> - [Programação colaborativa com Repl.it](https://repl.it/)
> - [Getting Started with Heroku](https://devcenter.heroku.com/start)
> - [Publicando Seu Site No Heroku](http://pythonclub.com.br/publicando-seu-hello-world-no-heroku.html)
