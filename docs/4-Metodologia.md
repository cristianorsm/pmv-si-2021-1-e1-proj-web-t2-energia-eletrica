
# Metodologia

De forma geral, a metodologia de trabalho adotada neste projeto priorizou dois aspectos fundamentais: simplicidade de execução e produtividade otimizada. Além destes pontos fundamentais foram comtemplados processos que possibilitassem a colaboração e interação de toda a equipe durante todo o percurso de desenvolvimento de cada etapa do projeto. Para tanto, em momentos específicos, tarefas são distribuídas entre os membros da equipe onde um integrante é determinado para capitanear um tópico específico baseado na sua aptidão, disponibilidade e interesse. Entretanto, todos os membros do time são convidados e encorajados a contribuir em todos os tópicos do projeto. É importante observar que desta forma todos os membros do grupo estão continuamente trabalhando em um tópico sob sua responsabilidade direta e, ao mesmo tempo, colaborando para o aperfeiçoamento dos tópicos produzidos sob a liderança de outros colegas.

Nesse contexto, para permitir o fluxo contínuo do trabalho em equipe foi optado por um modelo de versionamento distribuído. Como explicitado em mais detalhes abaixo, o ambiente principal para gerenciamento de trabalho assim como as ferramentas de versionamento utilizadas foram o GitHub e Git.


## Controle de Versão

A ferramenta de controle de versão adotada no projeto foi o [Git](https://git-scm.com/), sendo que o [Github](https://github.com) foi utilizado para hospedagem do repositório.

O projeto segue a seguinte convenção para o nome de branchs:

- `master`: versão estável já testada do software
- `unstable`: versão já testada do software, porém instável
- `testing`: versão em testes do software
- `dev`: versão de desenvolvimento do software

Quanto à gerência de issues, o projeto adota a seguinte convenção para etiquetas:

- `documentation`: melhorias ou acréscimos à documentação
- `bug`: uma funcionalidade encontra-se com problemas
- `enhancement`: uma funcionalidade precisa ser melhorada
- `feature`: uma nova funcionalidade precisa ser introduzida

A configuração do modelo de fluxo de trabalho utilizada pelo grupo segue basicamente o proposto nas configurações de Fluxo de Trabalho Centralizado, sendo que em alguns tópicos específicos o modelo de Ramificação de Recurso poderá ser preferido.

Para o fluxo de trabalho centralizado a equipe usa um repositório central como único ponto de entrada para todas as mudanças no projeto. Assim, cada membro implementa suas edições em um repositório local, independente do repositório principal. Depois que o repositório local tiver novas mudanças confirmadas, essas mudanças deverão ser incorporadas _(“commit” e “push”)_ ao repositório principal para compartilhamento com outros desenvolvedores no projeto. Neste momento o membro responsável pela atualização solicita a colaboração dos demais membros da equipe através de _pull requests_. Os pontos críticos ("_issues_") são discutidos baseados nas fundamentações oferecidas nas próprias _pull-requests_ onde toda a equipe opina e decide pela versão final.

Nos casos em que a configuração utilizada for a Ramificação de Recursos, que basicamente é uma derivação do fluxo de trabalho centralizado porém utilizando _“branches”_ de temas específicos (ramificação dedicada), após a atualização do tema _(“commit”)_ segue-se o fluxo já explicitado no parágrafo acima. Ou seja, são solicitadas _“pull-requests”_ para encorajar a colaboração de todo o time. Em caso de divergências , estas são igualmente fundamentadas para análise e decisão da versão final por todo o grupo.

## Gerenciamento de Projeto

### Divisão de Papéis

O processo de desenvolvimento do projeto está sendo baseado na framework SCRUM. 

A Equipe organizou-se da seguinte maneira: 

Product Owner: Maria Clara Bethonico Terra 

Equipe de Desenvolvimento: Baltazar Leão Reis, Cristiano Ribeiro dos Santos Mateus, Maria Clara Bethonico Terra e Robert Moises da Costa Pena.

### Processo

Neste projeto utiliza-se a metodologia derivada do framework SCRUM visando uma operação mais ágil e o fortalecimento das entregas, sem perder qualidade. Este método de trabalho garante flexibilidade de divisão de tarefas pela equipe e ao mesmo tempo otimiza a exploração de habilidades específicas dos seus integrantes. No entanto, também existem responsabilidades definidas, eventos com sua respectiva duração, controle dos artefatos que são produzidos e regras de execusão.

Assim, todo nosso processo de trabalho baseia-se em três pontos fundamentais derivados do método SCRUM:

TRANSPARÊNCIA - todos os membros da equipe têm conhecimento do que precisa ser feito, dos processos e do andamento do projeto, praticamente em tempo real.

INSPEÇÃO - o tempo todo, assim como no SCRUM, tudo é inspecionado, seja nas reuniões diárias ou na Sprint Review, que onde revisamos o que produzimos ao longo do Sprint.

ADAPTAÇÃO - o produto que está sendo construído no projeto, sofre adaptação constante conforme as mudanças vão acontecendo, correções de rota, resolução de problemas ou esclarecimentos.

Para a gerência do trabalho, adotamos a mesma estrutura recomendada pelo SCRUM, com a divisão de funções em _Product Owner e Equipe de Desenvolvimento_. O Product Owner aqui tem papel central na garantia de um processo ágil. Pois é o responsável por gerenciar o product _backlog do projeto_, estratificando em _sprints_ os passos de desenvolvimento. Em nosso time todos assumem, de alguma forma, parte na equipe de desenvolvimento. 

As reuniões diárias sugeridas pelo _framework_ foram adaptadas para discussões por via digital em grupo quase diariamente. E, semanalmente, uma grande reunião de atualização e fechamento de _sprints_ é realizada em conjunto com todo o grupo.

O acompanhamento do status do geral projeto é feito pelo monitoramento das _sprints_ e para isso o grupo utiliza o GitHub como ferramenta online e repositório de todo o processo.
 
### Ferramentas

As ferramentas empregadas no projeto são:

- Editor de código
- Ferramentas de comunicação
- Ferramentas de diagramação
- Software para criar protótipos e especificações para sites e aplicativos

O editor de código _VISUALCODE_ foi escolhido, pois possui integração facilitada com o sistema de controle de versionamento.

Para criar o _User Flow_ utilizamos a ferramenta _Diagram Software_ e _Flowchart Maker_, por ser uma tecnologia open-source para a construção de aplicativos de diagramação e por ser o software de diagramação mais usado do mundo. Utilizamos o _Figma_, para criar protótipos e especificações para o _Wireframe_, visto que é um editor gráfico de vetor e prototipagem de projetos de design baseado principalmente no navegador web, com ferramentas offline adicionais para aplicações desktop para GNU/Linux, macOS e Windows.

As ferramentas de comunicação utilizadas possuem integração semelhante e por isso foram selecionadas.

Para comunicação o grupo utiliza basicamente três ferramentas principais:
1 – Whatsapp – para as discussões mais frequentes (quase diárias) e para troca de informações mais curtas e pontuais;
2 – Microsoft TEAMS – para as reuniões estratégicas e encontros regulares semanais. Este ambiente proporciona a interação direta do grupo e troca de material eletrônico em forma de documentos e links;
3 – GitHub – para a exposição de idéias e sugestão de ajustes nas atividades desenvolvidas. Neste caso, o registro de comentários diretamente nas pull requests e atrelados a detalhes específicos permite maior precisão das explicações.

 
