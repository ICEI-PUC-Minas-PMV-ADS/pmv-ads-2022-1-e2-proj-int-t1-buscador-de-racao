# Especificações do Projeto

<span style="color:red">Pré-requisitos: <a href="1-Documentação de Contexto.md"> Documentação de Contexto</a></span>

Definição do problema e ideia de solução a partir da perspectiva do usuário. É composta pela definição do  diagrama de personas, histórias de usuários, requisitos funcionais e não funcionais além das restrições do projeto.

Apresente uma visão geral do que será abordado nesta parte do documento, enumerando as técnicas e/ou ferramentas utilizadas para realizar a especificações do projeto

| <img src="img/amanda dog.jpg" width="350" height="250" alt="Persona Amanda">     | **Amanda**                                                        | | 
|------|----------------------------------------------------------------------------------------------|------------|
|* Ocupação: proprietário de uma pequena papelaria no seu bairro.       | * Idade: 27                        | * Aplicativos: WhatsApp, Instagram, Facebook | 
|  * Motivações: Crescer na carreira, Ter uma casa grande | * Frustrações: Medo de perder o emprego   | * Hobbies: Ir ao parque com seu cão,  Assistir filmes, séries.      |

| <img src="img/Geraldo_dog.jpg" width="350" height="250" alt="Persona Juliana">     | **JULIANA**                                                                                 |   |          
|------|----------------------------------------------------------------------------------------------|------------|
| * Ocupação: proprietária de uma loja de roupas infantil.       | * Idade: 50                     | * Aplicativos: WhatsApp, Facebook, Instagram| 
|  * Motivações: Inovar e crescer no ramo da moda infantil  | * Frustrações: Medo de perder mercado para as grandes redes e lojas de roupa.  | * Hobbies: Culinária, academia e passeios 


| <img src="img/brad_luccas.jpg" width="530" height="250" alt="Persona Diego">      | **DIEGO**                                                                                |     |        
|------|----------------------------------------------------------------------------------------------|------------|
| * Ocupação: proprietário de um Pet Shop      | * Idade: 25                             | * Aplicativos: WhatsApp, Facebook, Instagram, Twitter, Youtube| 
| * Motivações: Crescer e expandir sua loja no mercado pet.   | * Frustrações: Perder mercado para grandes redes de Pet Shop como, Petz, Cobasi entre outras. | * Hobbies: Esportes, Viagens, Filmes e vídeos de diversos conteúdo. 

| <img src="img/mariana_dog.jpg" width="270" height="250" alt="Persona Luiza">      | **LUIZA**                                                                         |         |            
|------|----------------------------------------------------------------------------------------------|------------|
| * Ocupação: Trabalha em uma empresa de vendas de artigos de madeira ornamentais.  | * Idade: 27    * Aplicativos: WhatsApp, Facebook, Instagram, Twitter, Youtube, Pinterest | 
| * Motivações: Almejar uma ascensão de vendas nos segmentos de design, arquitetura, workshops que seguem as mesmas linhas de raciocínio.   | * Frustrações: Não conseguir alcançar uma quantidade de clientes necessários e, por conseguinte não estar de acordo com as metas de caráter financeiro e obrigatórios da empresa.   | * Hobbies: Leitura, viagens, exposições culturais e artísticas. 


## Histórias de Usuários

|EU COMO... `PERSONA`| QUERO/PRECISO ... `FUNCIONALIDADE`         |PARA ... `MOTIVO/VALOR`                 |
|--------------------|--------------------------------------------|----------------------------------------|
|João Pedro          | Ingressar minha loja nas redes sociais;        | Obter mais clientes, que foram perdidos com a chegada das lojas digitais. |
|                    | Conseguir realizar postagens sobre produtos de maneira personalizada;   |           |
|                    | Quer orientação para usar a plataforma;    |                                        |
|Juliana             | Verificar o engajamento de suas publicações nas suas redes sociais de uma forma simples| Conectar clientes e conseguir crescer no ramo da moda infantil|
|Diego               | Um local único que integre todas as redes socias; | Ampliar seus canais de vendas e divulgação dos serviços e produtos em busca de crescimento da empresa nas redes sociais.       |
|                    | Ter um calendário de publicações;          |     |
|Luiza               | Alavancar sua identidade visual;           | Aumentar a receita via canais digitais e pontecializar seu marketing. |
|                    | Escalabilidade das suas redes sociais atingindo um grande número de clientes;      |          |
|                    | Aumentar o seu ramo de atividades.         |                                        |



## Histórias de Usuários

Com base na análise das personas forma identificadas as seguintes histórias de usuários:

|EU COMO... `PERSONA`| QUERO/PRECISO ... `FUNCIONALIDADE` |PARA ... `MOTIVO/VALOR`                 |
|--------------------|------------------------------------|----------------------------------------|
|Usuário do sistema  | Registrar minhas tarefas           | Não esquecer de fazê-las               |
|Administrador       | Alterar permissões                 | Permitir que possam administrar contas |

Apresente aqui as histórias de usuário que são relevantes para o projeto de sua solução. As Histórias de Usuário consistem em uma ferramenta poderosa para a compreensão e elicitação dos requisitos funcionais e não funcionais da sua aplicação. Se possível, agrupe as histórias de usuário por contexto, para facilitar consultas recorrentes à essa parte do documento.

> **Links Úteis**:
> - [Histórias de usuários com exemplos e template](https://www.atlassian.com/br/agile/project-management/user-stories)
> - [Como escrever boas histórias de usuário (User Stories)](https://medium.com/vertice/como-escrever-boas-users-stories-hist%C3%B3rias-de-usu%C3%A1rios-b29c75043fac)
> - [User Stories: requisitos que humanos entendem](https://www.luiztools.com.br/post/user-stories-descricao-de-requisitos-que-humanos-entendem/)
> - [Histórias de Usuários: mais exemplos](https://www.reqview.com/doc/user-stories-example.html)
> - [9 Common User Story Mistakes](https://airfocus.com/blog/user-story-mistakes/)

## Requisitos

O escopo funcional do projeto é definido por meio dos requisitos funcionais que descrevem as possibilidades interação dos usuários, bem como os requisitos não funcionais que descrevem os aspectos que o sistema deverá apresentar de maneira geral. Estes requisitos são apresentados a seguir.

### Requisitos Funcionais

A tabela a seguir apresenta os requisitos funcionais do projeto, identificando a prioridade em que os mesmos devem ser entregues. 

|ID    | Descrição do Requisito  | Prioridade |
|------|-----------------------------------------|----|
|RF-001| O site deve permitir o gerenciamento de usuários | ALTA | 
|RF-002| O site deve permitir o gerenciamento de rações | ALTA |
|RF-003| O site deve apresentar, para cada ração, uma imagem correspondente (thumbnail) | MÉDIA |
|RF-004| O site deve permitir ao usuário visualizar informações complementares da ração | BAIXA |
|RF-005| O site deve apresentar texto com média de preço das rações | ALTA |
|RF-006| O site deve oferecer uma funcionalidade de filtro/pesquisa para permitir ao usuário localizar rações de acordo com porte e idade do animal, além de preço e qualidade da ração | ALTA |
|RF-007| O site deve conter uma página de cadastro e login | ALTA |

### Requisitos não Funcionais

A tabela a seguir apresenta os requisitos não funcionais do projeto, identificando a prioridade em que os mesmos devem ser entregues. 

|ID     | Descrição do Requisito  |Prioridade |
|-------|-------------------------|----|
|RNF-001| O site deve ser publicado em um ambiente acessível publicamente na Internet (Repl.it, GitHub Pages, Heroku) | ALTA | 
|RNF-002| O site deverá ser responsivo permitindo a visualização em um celular de forma adequada |  ALTA |
|RNF-003| O site deve ter bom nível de contraste entre os elementos da tela em conformidade |  MÉDIA | 
|RNF-004| O site deve ser compatível com os principais navegadores do mercado (Google Chrome, Firefox, Microsoft Edge, Safari) |  ALTA | 

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

## Restrições

As questões que limitam a execução desse projeto e que se configuram como obrigações claras para o desenvolvimento do projeto em questão são apresentadas na tabela a seguir.

|ID| Restrição                                             |
|--|-------------------------------------------------------|
|RE-001| O projeto deverá ser entregue no final do semestre letivo, não podendo extrapolar a data de 26/06/2022 |
|RE-002| O aplicativo deve se restringir às tecnologias básicas da Web no Backend |
|RE-003| A equipe não pode subcontratar o desenvolvimento do trabalho | 


Enumere as restrições à sua solução. Lembre-se de que as restrições geralmente limitam a solução candidata.

> **Links Úteis**:
> - [O que são Requisitos Funcionais e Requisitos Não Funcionais?](https://codificar.com.br/requisitos-funcionais-nao-funcionais/)
> - [O que são requisitos funcionais e requisitos não funcionais?](https://analisederequisitos.com.br/requisitos-funcionais-e-requisitos-nao-funcionais-o-que-sao/)

## Diagrama de Casos de Uso

O diagrama de casos de uso é o próximo passo após a elicitação de requisitos, que utiliza um modelo gráfico e uma tabela com as descrições sucintas dos casos de uso e dos atores. Ele contempla a fronteira do sistema e o detalhamento dos requisitos funcionais com a indicação dos atores, casos de uso e seus relacionamentos. 

As referências abaixo irão auxiliá-lo na geração do artefato “Diagrama de Casos de Uso”.


> **Links Úteis**:
> - [Criando Casos de Uso](https://www.ibm.com/docs/pt-br/elm/6.0?topic=requirements-creating-use-cases)
> - [Como Criar Diagrama de Caso de Uso: Tutorial Passo a Passo](https://gitmind.com/pt/fazer-diagrama-de-caso-uso.html/)
> - [Lucidchart](https://www.lucidchart.com/)
> - [Astah](https://astah.net/)
> - [Diagrams](https://app.diagrams.net/)
