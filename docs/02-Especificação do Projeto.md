# Especificações do Projeto

<span style="color:red">Pré-requisitos: <a href="1-Documentação de Contexto.md"> Documentação de Contexto</a></span>

Definição do problema e ideia de solução a partir da perspectiva do usuário. É composta pela definição do  diagrama de personas, histórias de usuários, requisitos funcionais e não funcionais além das restrições do projeto.

Apresente uma visão geral do que será abordado nesta parte do documento, enumerando as técnicas e/ou ferramentas utilizadas para realizar a especificações do projeto

| <img src="img/amanda dog.jpg" width="250" height="250" alt="Persona Amanda">     | **AMANDA**                                                        | | 
|------|----------------------------------------------------------------------------------------------|------------|
|* Ocupação: Trabalha como auxiliar de Recursos Humanos em uma empresa de médio porte.  | * Idade: 27                        | * Aplicativos: WhatsApp, Instagram, Facebook | 
|  * Motivações: Crescer na carreira, Ter uma casa grande | * Frustrações: Medo de perder o emprego   | * Hobbies: Ir ao parque com seu cão,  Assistir filmes, séries.      |

| <img src="img/Geraldo dog.jpg" width="350" height="250" alt="Persona Geraldo">     | **GERALDO**                                                                                 |   |          
|------|----------------------------------------------------------------------------------------------|------------|
| * Ocupação: Aposentado.       | * Idade: 69                     | * Aplicativos: WhatsApp, Aplicativos de Banco| 
|  * Motivações: Qualidade de vida  | * Frustrações: Se sente muito sozinho, saudade dos filhos.  | * Hobbies: Pescaria, visitar os filhos.


| <img src="img/brad_luccas.jpg" width="250" height="250" alt="Persona Lucas">      | **LUCAS**                                                                                |     |        
|------|----------------------------------------------------------------------------------------------|------------|
| * Ocupação: Engenheiro de produção, funcionário de uma multinacional do setor da indústria automotiva.      | * Idade:35                             | * Aplicativos: Instagram, Linkedin, Aplicativos de Relacionamento| 
| * Motivações: Crescer na carreira, construir uma família   | * Frustrações: Falta de equilibrio entre a vida e o trabalho, construir um relacionamento duradouro. | * Hobbies: Sair com os amigos, passear com seu cão Brad

| <img src="img/mariana dog.jpg" width="250" height="250" alt="Persona Mariana">      | **MARIANA**                                                                         |         |            
|------|----------------------------------------------------------------------------------------------|------------|
| * Ocupação: Estudante de Direito.  | * Idade: 19    * Aplicativos: WhatsApp, Facebook, Instagram, Twitter, Youtube, TikTok | 
| * Motivações: Crescer na carreira, Constituir uma fámilia, terminar os estudos, ter varios pets.   | * Frustrações: Indecisão na carreira que quer seguir.   | * Hobbies:sair com o namorado, Viajar e Assistir Filmes. 



## Histórias de Usuários

Com base na análise das personas forma identificadas as seguintes histórias de usuários:

|EU COMO...          | QUERO/PRECISO                       |MOTIVO/VALOR                 |
|--------------------|------------------------------------|----------------------------------------|
|Amanda    | Encontrar uma boa alimentação para o meu novo membro da família e que seja boa mas tenha um preço bom.           | Para dar uma melhor qualidade de vida, já que ele foi adotado e estava sob maus tratos.               |
|Geraldo      | Dar a melhor ração que seu novo amigo de estimação merece.                 | Geraldo vive com seu amigo de 4 patas e quer dar a melhor ração para ele.  |
|Ana Paula      | Ana Paula comprou um filhote e deseja comprar uma ração de extrema qualidade. .                 | Para dar saúde, longevidade e um bom crescimento para o seu novo filhote.   |
|Lucas      | Lucas tem um cão da Raça Golden, atualmente um tipo de ração, mas gostaria de trocar por uma com o custo/benefício melhor.                | Devido ao aumento de todos os produtos e serviços, ele quer economizar na alimentação do seu pet, mas sem perder a qualidade.   |
|Mariana       |     Trocar a ração do Seu Pet.             | Mariana percebeu que as fezes do seu cão estavam moles e resolveu trocar a ração do seu cão e está na dúvida de qual é a melhor para ele.   |


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
