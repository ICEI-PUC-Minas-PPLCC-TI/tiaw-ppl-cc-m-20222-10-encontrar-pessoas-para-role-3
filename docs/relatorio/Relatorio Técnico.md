# :clipboard: Informações do Projeto
`Actual Rolê`

`Trabalho Interdisciplinar: Aplicações Web`

`Ciência da Computação`

## :construction_worker: Participantes

* André Luis de Oliveira Ferreira
* Eduardo Henrique Leite Cardoso
* Marcelo Victor Alencar Eulálio 
* Nathan de Araújo Cunha Lisboa
* Pedro Malta Boscatti
* Rafael Cangussu Dallariva

# :wrench: Estrutura do Documento

- [Informações do Projeto](#informações-do-projeto)
  - [Participantes](#participantes)
- [Estrutura do Documento](#estrutura-do-documento)
- [Introdução](#introdução)
  - [Problema](#problema)
  - [Objetivos](#objetivos)
  - [Justificativa](#justificativa)
  - [Público-Alvo](#público-alvo)
- [Especificações do Projeto](#especificações-do-projeto)
  - [Personas e Mapas de Empatia](#personas-e-mapas-de-empatia)
  - [Histórias de Usuários](#histórias-de-usuários)
  - [Requisitos](#requisitos)
    - [Requisitos Funcionais](#requisitos-funcionais)
    - [Requisitos não Funcionais](#requisitos-não-funcionais)
  - [Restrições](#restrições)
- [Projeto de Interface](#projeto-de-interface)
  - [User Flow](#user-flow)
  - [Wireframes](#wireframes)
- [Metodologia](#metodologia)
  - [Divisão de Papéis](#divisão-de-papéis)
  - [Ferramentas](#ferramentas)
  - [Controle de Versão](#controle-de-versão)
- [Projeto da Solução](#projeto-da-solução)
  - [Tecnologias Utilizadas](#tecnologias-utilizadas)
  - [Arquitetura da solução](#arquitetura-da-solução)
- [Avaliação da Aplicação](#avaliação-da-aplicação)
  - [Plano de Testes](#plano-de-testes)
  - [Registros de Testes](#registros-de-testes)
- [Referências](#referências)


# :open_file_folder: Introdução


## Problema

Dia após dia a rotina das pessoas tem ficado cada vez mais corridas e, com isso, torna-se muito importante que tenham momentos de lazer para relaxar e tornar a vida menos estressante. Na atualidade, um dos exemplos para que ambos esses objetivos sejam atentidos com sucesso é as saídas, seja durante ou nos fins de semana, popularmente conhecidos como **rolês**.

Diante disso, existem alguns obstáculos que todas as faixas etárias encontram. São eles: O que eu vou fazer? O que tem pra fazer? Com quem irei? Vou gastar algo? Como irei? Onde meus amigos estão? Estou sozinho, mas mesmo assim quero socializar. Como eu faço? São esses e muitas outros problemas que iremos tentar ajudar a resolver com a nossa aplicação, tornando bem mais fácil e dinâmico uma saída de casa, ou até mesmo um rolê na sua própria casa.


## Objetivos

O objetivo geral do grupo é desenvolver uma plataforma para facilitar para as pessoas encontrarem um rolê onde elas vão se sentir a vontade e aproveitar cada minuto. Também, a saber informações crucias sobre o rolê (pessoas confirmadas, meio de transportes, preço, etc.), ter algumas interações em tempo real e poder avaliar o rolê para que pessoas que estão pensando em ir saibam se vale a pena ou não comparecer.


## Justificativa

Essa plataforma vem para ajudar diversos tipos de pessoas a acharem um local ideal para se distrair. Com o final da pandemia, muitas pessoas ficaram isoladas e antissociais, assim, essa plataforma ajudaria essas pessoas a conseguirem socializar melhor.

É importante frisar que a ferramenta não quer atingir apenas esse público. Com as universidades voltando às aulas presenciais, todos querem sempre achar o melhor rolê. Sendo assim, é o momento ideal para socializar e ter sua hora de lazer e distração, tendo como facilitador o auxilio da plataforma.


## Público-Alvo

Com esse projeto, esperamos alcançar praticamente todas as pessoas interessadas em sair de casa e passar um tempo de qualidade com quem gostamos. Além de atingir uma variedade de donos de estabelecimento e divulgadores de evento.

Inicialmente, no entanto, o nosso foco são os jovens que querem arrumar um rolê ou divulgar um.



# :bookmark_tabs: Especificações do Projeto

Nessa seção, será apresentada uma visão um pouco mais aprofundada do projeto, através da elaboração das _Personas_, _Histórias de Usuários_, _Requisitos e Restrições do projeto_.


## Personas e Mapas de Empatia

* **Luiz Eduardo:** Luiz tem 19 anos e é estudante de Publicidade e Propaganda. Ele é uma pessoa muito extrovertida, animada e amigável, que tem como sonho ser um grande empresário e abrir um cassino. Ele usa o computador e o celular diariamente tanto para atividades de estudo como para o lazer. Ele quer saber quais são os rolês e como está a situação deles diariamente. Gosta de se sentir incluído e de ter pessoas animadas como companhias.

* **Lúcio Marcos:** Lúcio tem 26 anos e é advogado. Ele é uma pessoa bem humorada, simpática, tímida, calma e paciente. Adora ler e ver filmes nas horas vagas. Ele tem como sonho casar, ter filhos e morar perto do trabalho em um local boêmio. Usa o notebook para trabalhar e ver filmes, o celular para conversar com os amigos e a televisão para ver esportes. Ele quer saber onde os amigos estão para saber com antecedência se o lugar é tranquilo e tem o estilo musical que ele mais gosta. Deve ter os seus momentos de privacidade respeitados, mas sem deixar de incluí-lo nos rolês que são mais calmos e combinam com a sua personalidade.

* **Maria Clara:** Maria Clara tem 21 anos e é estudante de Marketing e influenciadora digital. Ela adora gravar videos de maquiagem e é uma pessoa sociável, engraçada, inteligente e responsável. Sonha em se formar na faculdade conseguindo conciliar com a vida de influenciadora. Usa o computador e o celular tanto para trabalhar quanto para se entreter e estudar. Ela tem interesse na plataforma pois quer promover eventos de grande escala e divulgá-los tendo o apoio necessário para conseguir atrair um público maior.


## Histórias de Usuários

Com base na análise das personas, foram identificadas as seguintes histórias de usuários:

|EU COMO... `PERSONA`| QUERO/PRECISO ... `FUNCIONALIDADE` |PARA ... `MOTIVO/VALOR`                 |
|--------------------|------------------------------------|----------------------------------------|
|Luiz Eduardo | Achar um rolê animado          | Me divertir              |
|Lúcio Marcos | Achar um rolê tranquilo | Encontrar meus amigos e me sentir confortável|
|PMaria Clara       | Divulgar meu evento               | Aumentar o alcançe e o público  |


## Requisitos

As tabelas que se seguem apresentam os requisitos _funcionais_ e _não funcionais_ que detalham o escopo do projeto.


### Requisitos Funcionais

|ID    | Descrição do Requisito  | Prioridade |
|------|-----------------------------------------|----|
|RF-001| Cadastro de usuário | ALTA | 
|RF-002| Interface do rolê com as devidas informações | ALTA |
|RF-003| Localização/Mapa em tempo real | BAIXA |
|RF-004| Lista de Amigos | MÉDIA |
|RF-005| Feed com os rolês em destaque  | ALTA |
|RF-006| Meios de locomoção  | MÉDIA |
|RF-007| Busca de rolês (Barra de Pesquisa) | ALTA |
|RF-008| Avaliação do rolê | ALTA |
|RF-009| Página de login | ALTA | 
|RF-010| Cadastro do role | ALTA | 
|RF-011| Avaliação em tempo real do rolê | MÉDIA |
|RF-012| Chat com os amigos | MÉDIA |
|RF-013| Página do perfil da pessoa | MÉDIA |
|RF-014| Aba (favoritos) seus rolês/ingresso | MÉDIA |
|RF-015| Filtros tipo de rolê | MÉDIA |
|RF-016| Confirmação de presença | MÉDIA | 
|RF-017| Página onde a pessoa avalia | MÉDIA |
|RF-018| Comentário sobre a pessoa| MÉDIA | 


### Requisitos Não Funcionais

|ID     | Descrição do Requisito  |Prioridade |
|-------|-------------------------|----|
|RNF-001| Um sistema de responsividade para diversos tamanhos de tela | MÉDIA | 
|RNF-002| Deve processar requisições do usuário em pouco tempo |  BAIXA | 
|RNF-003| A plataforma deverá ter uma interface intuitiva | ALTA | 
|RNF-004| O sistema necessita de boa executabilidade em qualquer plataforma | ALTA |
|RNF-005| Necessidade de atender às normas legais | MÉDIA | 


## Restrições

O projeto está restrito pelos itens apresentados na tabela a seguir:

|ID| Restrição                                             |
|--|-------------------------------------------------------|
|01| O projeto deverá ser entregue até o final do semestre |
|02| Não pode ser desenvolvido um módulo de backend        |
|03| O projeto tem que ser desenvolvido apenas nas seguintes linguagens: HTML, CSS e JavaScript |
|04| O projeto deve ser versionado utilizando o controle de versão Git |



# :art: Projeto de Interface

A interface principal do projeto irá exibir um resumo de todas as funcionalidades, com um feed dos rolês em destaque, uma lista de amigos para os usuários que fizerem o login e um menu de navegação. Os focos da interface serão a responsividade e a intuitividade de navegação pela plataforma por parte dos usuários.


## User Flow

![UserFlow do protótipo interativo](images/userflow.png)


## Wireframes

### Página Inicial

![Tela inicial](images/wireframe1.png)

### Página Login

![Tela inicial](images/wireframe2.png)

### Página Rolê

![Tela inicial](images/wireframe3.png)

## Protótipo Interativo

O protótipo interativo desenvolvido no Figma pode ser visto clicando [aqui](https://www.figma.com/proto/KXxttrw4qgjAF1K7UaD9XQ/Prot%C3%B3tipo-Rol%C3%AA?node-id=11%3A79&scaling=min-zoom&page-id=0%3A1&starting-point-node-id=11%3A79&show-proto-sidebar=1).


# :pencil2: Metodologia

Em primeiro momento, para nos organizarmos melhor, fizemos reuniões semanais de algumas horas pelo Discord, onde produzimos juntos. Com o passar do tempo e a divisão de tarefas, pretendemos aumentar a frequência das reuniões e reduzir o tempo de duração das mesmas. Além disso, queremos utilizar o Trello para nos organizarmos com os prazos e produções.


## Divisão de Papéis

Inicialmente, dividimos as funções igualmente para a primeira entrega. Posteriormente, ainda vamos definir como serão divididas as tarefas para cada membro do grupo.

| Integrante  | Função              |
|-----------|-------------------------|
|André Luis | Design Gráfico | 
|Eduardo Henrique | Design Gráfico |
|Marcelo Victor | Back End |
|Nathan Lisboa | Front End |
|Pedro Malta | Front End |
|Rafael Cangussu | Back End |


## Ferramentas

Para as nossas reuniões, estamos utilizando o Discord e fazendo encontros semanais. Pretendemos utilizar o Trello para organizar o nosso cronograma e o Visual Studio Code para ser o nosso editor de códigos.

| Ambiente  | Plataforma              |Link de Acesso |
|-----------|-------------------------|---------------|
|Processo de Design Thinkgin  | Miro |  [Link](https://miro.com/app/board/uXjVPUre77E=/) | 
|Repositório de código | GitHub | [Link](https://github.com/ICEI-PUC-Minas-PPLCC-TI/tiaw-ppl-cc-m-20222-10-encontrar-pessoas-para-role-3) | 
|Protótipo Interativo | Figma | [Link](https://www.figma.com/proto/KXxttrw4qgjAF1K7UaD9XQ/Prot%C3%B3tipo-Rol%C3%AA?node-id=11%3A79&scaling=min-zoom&page-id=0%3A1&starting-point-node-id=11%3A79&show-proto-sidebar=1) | 

 
> As ferramentas empregadas no projeto são:
> 
> - Visual Studio Code.
> - Discord.
> - Figma.
> - Trello.
> 
> O Visual Studio Code foi escolhido porque ele possui uma integração com o
> Github e um visual agradável e interativo, além de plugins muito úteis.
> 
> O Discord foi escolhido por possuir uma interface amigável e agilizar os processos de comunicação.
>
> O Trello também foi escolhido por sua interface intuitiva e pela quantidade de recursos disponíveis para a nosssa organização.
> 
> Por fim, para criar os diagramas do site e o protótipo, escolhemos o Figma, pois
> ele possui uma quantidade ampla de recursos e possibilita o trabalho simultâneo na mesma página.


## Controle de Versão

O [Git](https://git-scm.com/) foi a ferramenta de controle de versão escolhido. Por ele nós vamos subir os arquivos para o repositório hospedado no [Github](https://github.com).

Inicialmente, estamos pensando em trabalhar com duas branchs, uma principal e uma secundária, de alterações, que seriam nomeadas da seguinte forma:

- `master`: versão estável já testada do software;
- `updates`: versões que estão ainda em análise, para aprovação;

Depois de testada e aprovada, a branch dos updates seria mergida com a branch main, de modo a garantir maior segurança e impedir uma sobreposição de versões não aprovadas pelo grupo.

Eventuais bugs poderão utilizar a tag `bugs`, para que sejam rapidamente identificados por todos os membros do grupo.

**Exemplo do grupo:**

![Workflow do Git](images/workflow-git.png)


# :key: Projeto da Solução

Criar uma plataforma que possui ferramentas para auxiliar as pessoas na dinamica de encontrar um evento e se socializar.

## Tecnologias Utilizadas

Foram utilizadas as seguintes linguagens na criação da nossa aplicação web: HTML, CSS e JAVASCRIPT e o GitHub Pages para a hospedagem do site.

## Arquitetura da Solução

>Navegador: HTML + CSS + JavaScript Local Storage
>
>Internet
>
>Hospedagem: GitHub Pages
 
![image](https://user-images.githubusercontent.com/113562821/205518685-6f5ee65d-2e9b-472d-801d-21add42f9c00.png)

Nossa plataforma utilizou os Storages Locais e de Sessão do Navegador para simular um ambiente funcional de cadastro e contato entre usuários.


# :bar_chart: Avaliação da Aplicação

Foram criados planos de testes para apresentar o funcionamento das situações requisitadas e restritas do projeto, a separação entre testes diferentes se mostra um conhecimento útil para os desenvolvedores, que precisam saber o que pode ocorrer na interação do usuário com o site.

## Plano de Testes


### Teste 1 - Ver Página Principal Cadastro e Login

| Caso de Teste  | Exibição da Página Principal, Cadastro e Login       |
|-----------|-------------------------|
|Requisitos Associados  | RF-001 - Cadastro de usuário<br/>RF-009 - Página de login  |
| Objetivo de Teste |Exibir a página inicial de maneira limitada, inicialmente e, após o login, exibir ela de maneira completa | 
| Passos | 1 - Acessar o navegador e informar o endereço do site<br/>2 - Visualizar a página inicial<br/>3 - Criar uma conta<br/>4 - Fazer login<br/>5 - Ver a página inicial atualizada |
| Critérios de Êxito|   • A página inicial será exibida sem as opções na Navbar<br/> • O cadastro de usuário ser bem sucedido<br/> • Após o login com as informações de cadastro informadas, serão exibidas novas opções na Navbar, permitindo a navegação por todo o site |


### Teste 2 - Exibição de Eventos

| Caso de Teste  | Exibição de eventos            |
|-----------|-------------------------|
|Requisitos Associados  | RF-007 - Busca de eventos (barra de pesquisa)<br/>RF-010 - Cadastro do evento<br/>RF-015 - Filtragem dos tipos de evento  |
| Objetivo de Teste | Verificar se exibição, pesquisa, filtragem e cadastro de eventos está ocorrendo corretamente | 
| Passos | 1 - Acessar o navegador e informar o endereço do site<br/>2 - Visualizar a página de eventos<br/>3 - Pesquisar evento por nome<br/>4 - Filtrar o tipo de evento<br/>5 - Favoritar algum evento<br/>6 - Cadastrar um evento |
| Critérios de Êxito|  • A exibição dinâmica dos eventos deve ocorrer por meio dos dados do Local Storage<br/> • Os eventos resultantes da pesquisa devem aparecer na mesma página, de acordo com o número de resultados<br/> • O filtro do evento deve reexibir apenas aqueles que se encaixam na categoria<br/> • O evento favoritado deve ficar com um símbolo de coração vermelho e ser armazenado no Local Storage de Favoritos<br/> • Após cadastrar algum novo evento, ele deve ser exibido na mesma página dos outros, podendo ser visto individualmente e filtrado


### Teste 3 - Exibição Amigos

| Caso de Teste  | Exibição e manipulação de amigos              |
|-----------|-------------------------|
|Requisitos Associados  | RF-004 Lista de Amigos  |
| Objetivo de Teste | Verificar se a manipulação de usuários esta funcionando corretamente | 
| Passos | 1 - Acessar a página de usuários<br/>2 - Pesquisar usuário por nome<br/>3 - Adicionar usuário a lista de amigos<br/>4 - Remover usuário dos amigos |
| Critérios de Êxito|   • Ao acessar a página de usuários deve-se aparecer uma lista com alguns usuários seus respectivos dados e um botão de adicionar<br/> • Se pesquisar o nome de alguem o filtro deve funcionar exibindo apenas aquelas ou aquela pessoa<br/> • Quando clicar no botão de "adicionar" o usuário deverá ir para a sua lista de amigos<br/> • Quando clicado o botão vermelho o usuário devera ser removido da sua lista de amigos e voltar para a lista de usuários |



### Teste 4 - Página do Evento

| Caso de Teste  | Página do Evento              |
|-----------|-------------------------|
|Requisitos Associados  | RF-002 - Interface do evento com as devidas informações<br/>RF-003 - Localização em tempo real<br/>RF-008 - Avaliação do evento<br/>RF-011 - Avaliação do evento em tempo real<br/>RF-016 - Confirmação de presença |
| Objetivo de Teste | Verificar se exibição do evento está ocorrendo corretamente, com dados, avaliação, espaço de comentários funcional e confirmação de presença | 
| Passos | 1 - Ver página detalhada do evento<br/>2 - Clicar nas informações de localização e ser redirecionado<br/>3 - Comentar no feed do evento<br/>4 - Confirmar presença no evento |
| Critérios de Êxito|   • A página deve ser exibida dinamicamente, por meio dos dados do Local Storage<br/> • Ser redirecionado para o Google Maps com o endereço informado no evento<br/> • O comentário ser exibido no feed com nome e foto do usuário logado<br/> • A foto do usuário logado ser exibido na confirmação de presença do painel lateral |



### Teste 5 - Página do Usuário

| Caso de Teste  | Exibir página do usuário             |
|-----------|-------------------------|
|Requisitos Associados  | RF-013 Página do perfil da pessoa<br/>RF-018 Comentário sobre a pessoa |
| Objetivo de Teste | Verificar se exibição da página do usuário está acontecendo corretamente, com os dados detalhados e um feed de recados  | 
| Passos | 1 - Ver página detalhada do usuário<br/>2 - Clicar nas páginas de informação e feed e alternar entre elas<br/>3 - Digitar algum comentário do perfil<br/>4 - Clicar no botão de enviar mensagem |
| Critérios de Êxito|   • A página deve ser exibida dinamicamente, por meio dos dados do Local Storage<br/> • O comentário enviado aparece na aba de recados do perfil do usuário<br/> • O botão de mensagem redireciona para um aplicativo de email com o devido contato do usuário |



### Teste 6 - Página do Perfil

| Caso de Teste  | Página do Perfil              |
|-----------|-------------------------|
|Requisitos Associados  | RF-013 - Página do perfil do usuário  |
| Objetivo de Teste | Verificar se exibição da página do perfil está acontecendo corretamente, com as estatísticas de amigos e favoritos | 
| Passos | 1 - Ver página detalhada do perfil logado<br/>2 - Ver página detalhada dos eventos favoritos<br/>3 - Remover um evento favoritado |
| Critérios de Êxito|   • A página deve ser exibida dinamicamente, por meio dos dados do Session Storage<br/> • As estatísticas do número de amigos e favoritos deve estar correta<br/> • Caso um evento seja removido, ele deve desaparecer da aba de favoritos no mesmo momento  |



### Teste 7 - Validação de Logout

| Caso de Teste  | Validação de Logout             |
|-----------|-------------------------|
|Requisitos Associados  |  RF-009 - Página de login  |
| Objetivo de Teste | Verificar se o logout está ocorrendo normalmente | 
| Passos | 1 - Clicar no botão de Logout<br/>2 - Conferir o Session Storage do navegador |
| Critérios de Êxito|   • As páginas do site devem retornar para o padrão, com a Navbar sem opções<br/> • O usuário deve desaparecer do Session Storage |

---


# :paperclip: Referências

A lista a seguir traz as referências utilizadas nesse trabalho. São elas:

- Afinal, por que é importante fazer bons amigos na faculdade?. **UCEFF**, Chapecó. Disponível em: https://blog.uceff.edu.br/afinal-por-que-e-importante-fazer-bons-amigos-na-faculdade/. Acesso em 22 de set. de 2022.

- Estudo busca voluntários para avaliar impactos da pandemia na saúde mental. **UFMG**, Belo Horizonte, 30 de jun. de 2020. Disponível em: https://ufmg.br/comunicacao/noticias/estudo-busca-voluntarios-para-avaliar-impactos-da-pandemia-na-saude-mental. Acesso em 01 de dez. de 2022.

- Fobia social no período pós-pandemia. **UFSM**, Santa Maria, 04 de ago. de 2022. Disponível em: https://www.ufsm.br/midias/experimental/revistatxt/2022/08/04/fobia-social-no-periodo-pos-pandemia%EF%BF%BC/. Acesso em 01 de dez. de 2022.
- Por que estamos ansiosos?. UFMG, Belo Horizonte, 14 de set. de 2020. Disponível em: https://www.medicina.ufmg.br/por-que-estamos-ansiosos/. Acesso em 08 de nov. de 2022.

- Problemas para se enturmar podem atrapalhar vida na faculdade. **UOL Educação**, São Paulo, 13 de mar. de 2013. Disponível em: https://educacao.uol.com.br/noticias/2013/03/11/problemas-para-se-enturmar-podem-atrapalhar-vida-na-faculdade.htm. Acesso em 24 de set. de 2022.
