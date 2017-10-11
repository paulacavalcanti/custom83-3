# custom83
Repositório do projeto final - Estácio ADS P5

# CUSTOM 83


#### Descrição

O projeto visa a criação de um site de anúncios voltado para usuários que desejem encontrar produtos e serviços ligados ao mercado automotivo, produtos em geral como peças, acessórios e tudo que o mercado automotivo oferece ou as empresas queiram hospedar no site. A ideia é hospedar produtos de empresas locais  na base de dados da Custom 83 para divulgação em site no modelo macro de uma loja dentro de um só sistema.
 Sem o intuito de venda mas de divulgação das empresas interessadas em vender seus produtos e serviços com comparações de preços e negociações mais assertivas de acordo com as necessidades dos clientes finais.
 Caso o cliente necessite encontrar a loja mais próxima de uma determinada categoria de produto, o site disponibilizará parâmetros de pesquisa avançadas exibindo todas as informações detalhadas da empresa e do produto em questão. Além da pesquisa avançada o cliente poderá efetuar negociações com as empresas hospedadas através de alertas trocadas entre eles e comparações de preços e cabe a loja aceitar ou não a oferta, além de que será possível visualizar a confiabilidade de acordo com as avaliações realizadas a loja.
 
 #### Objetivo

Atualmente no mercado não existe um site com oferta de tantos serviços e produtos de lojas relacionadas ao mercado automotivo. 
Com isso o objetivo deste projeto é a entrega de um site completo com a função de pesquisa, comparações e venda de produtos e serviços de empresas terceiras objetivando mais conforto e comodidade ao consumidor do produto final.

#### Justificativa
O Custom83.com, se embasa na na questão da praticidade e comodidade dos seus futuros usuários, de poder encontrar em um único web site, tudo o que ele deseja para seu automovel, trazendo total comodidade, rapidez e facilidade em suas pesquisas e futuras compras. 

# DOCUMENTO DE VISÃO

### 1. Posicionamento
#### 1.1 Cenário Atual

 Atualmente não existe um sistema voltado a buscas específicas de mercado automotivo que promova maior comodidade aos consumidores que necessitam buscar peças ou algum serviço automotivo mais perto de sua localidade.
 Com o intuito de oferecer essa facilidade na prestação de serviços tanto das empresas promovendo seus produtos como da busca dos clientes será criado um site onde existirá a iteração entre consumidor e empresa prestadora de serviço, dando visão aos produtos oferecidos e serviços agendados com a inclusão de ofertas e negociações entre os envolvidos.
 
 DIAGRAMA DE CONTEXTO
 
 ![diagrama de contexto](https://user-images.githubusercontent.com/32046433/30527591-ebcd5746-9c00-11e7-8922-b4c70bb6818c.png)
 
 ### 2. EAP de Primeiro Nível
 
 ![eap de nivel 1](https://user-images.githubusercontent.com/32046433/30526445-ddfe4252-9bf0-11e7-80b0-97496d8c912a.png)

### 3. Envolvimento
#### 3.1 Papel dos atores
Atores são pessoas, equipamentos ou outros sistemas que interagem como sistema em questão, enviando ou recebendo mensagens.
Abaixo estão descritos de forma resumida o papel dos atores do site CUSTOM83:

#### Usuário


| Descrição | O usuário é o ator que irá utilizar diariamente o sistema |
| ------ | ------ |
| Papel | O sistema Custom83 será eficiente se as informações forem guardadas diariamente, a fim de manter um histórico de consultas. O usuário é de vital importância para o bom funcionamento do sistema, pois é quem fornece todos os dados que serão armazenados e utilizados pelo sistema. |
| Insumos ao Sistema | - Dados dos usuários / Dados das empresas hospedadas / dados de consultas diárias / Dados de desperdício diário / informações sobre o funcionamento do sistema / sugestões para aperfeiçoamento|
| Representante | Empresas do mercado automobilístico |

#### Proprietário

| Descrição | Fornece as especificações gerais que o sistema deve atender |
| ------ | ------ |
| Papel | Descrever de forma detalhada todos os requisitos do sistema. |
| Insumos ao Sistema | Informações sobre o funcionamento da empresa / Requisitos do sistema / Implementação|
| Representante | Ítalo Nascimento |

#### Empresas Fornecedoras

| Descrição | Fornece os dados necessários para alimentar a base de dados da Custom83 |
| ------ | ------ |
| Papel | Fornecedora dos dados dos produtos e serviços ofertados |
| Insumos ao Sistema |- Geração de dados a Custom83 para atender ao cliente / Melhores ofertas de trabalho|
| Representante | Lojas automotivas |

#### Custom 83

| Descrição | É o próprio sistema e suas funcionalidades. |
| ------ | ------ |
| Papel | Descrever de forma detalhada todos os requisitos do sistema.|
| Insumos ao Sistema |- Geração de dados para atender ao cliente |
| Representante | Paula, Italo, Ledhson, Lucas, Felipe |

### 4. Solução Tecnológica

#### 4.1 Ferramentas:
##### FrontEnd
  - HTML
  - CSS
  - JAVASCRIPT
  - FRAMEWORKS
  - BOOTSTRAP
  - BULMA'.IO
  
 ##### BackEnd
- LAMP / WAMP SERVERS
- LIGUAGEM PHP 7
- FRAMEWORK LARAVEL

 ##### Banco de Dados
 - MYSQL
 
##### IDE's
- SUBLIME
- ATOM

### EAP - ESTRUTURA ANALÍTICA DO PROJETO
![eap](https://user-images.githubusercontent.com/32046433/31191640-2b5c1d68-a915-11e7-9e8a-b92f8cb6cee8.png)


# DEFINIÇÃO DE METODOLOGIA, PAPÉIS E RESPONSABILIDADES

  No processo de desenvolvimento de software será utilizado a metodologia ágil baseada no SCRUM, a qual teremos entregas constantes e palpáveis, com reuniões diárias via whatsapp, reuniões de fechamento e planejamento de Sprints. Um conjunto de papéis bem definidos determina, através de atribuições, como será a atuação de cada um dentro do time que trabalhará no projeto baseado no SCRUM.

**PO**: Representante da área Cliente/solicitante, dono do produto, responsável pelo levantamento de requisitos, mapeamento de processo de negócio do cliente, protótipo de interface ;

**Scrum Master**: Habilidade no direcionamento  facilitando as tarefas realizadas tanto pelo Product Owner quanto pela equipe, indica o caminho em que o projeto deve seguir, priorizando tarefas e prazos, agindo como  um incentivador da equipe tornando-se um guia para atingir um objetivo comum.

**Time**: Responsável pelo desenvolvimento do planejamento definido;


## MATRIZ RACI - PAPÉIS E RESPONSABILIDADES

| Pacote de Trabalho | Analista /Scrum Master | Desenvolvedor BackEnd |  Desenvolvedor FrontEnd / PO | Analista de BD | Equipe do Projeto |
| ------ | ------ | ------ | ------ | ------ | ------ | 
| Definição do Projeto | C | I |  R  | I | A |
|Documentação do projeto| R | I | A | I | C |
| Protótipo de Sistema | C | I | R | I | A |
| Logomarca do Projeto | I | I | R | I | A
| Modelagem de Dados | I | I | C | R | A |
| Desenvolvimento Interface Sistema | I | C | R | C | A |
| Desenvolvimento Regra de negócio | A | R | C | C | I |



## 5.CRONOGRAMA / PLANO DE RELEASE

 __ITERAÇÃO 1__

| SPRINT 1 - 2 SEMANAS -  22/08 À 05/09 | RESPONSÁVEL | DT INÍCIO | DT FIM | 
| ------ | ------ | ------| ----| 
| Documento de Visão | Paula Soares | 24/08/17 | 31/08/17| 
|TAP | Paula Soares| 22/08/17 | 25/08/17| 
| Logomarca + identidade visual | Ítalo Nascimento | 22/08/17| 26/08/17 | 
|Backend - Desenvolver módulo de autenticação de usuário | Felipe Diniz | 22/08/17| 30/08/17| 
|Frontend - Desenvolver frontend de autenticação | Lucas Moreira | 23/08/17| 01/09/17 | 
|**SPRINT 2 - 2 SEMANAS --> 13/09 À 27/09** | **RESPONSÁVEL** | **DT INÍCIO** | **DT FIM**|
| Documento de Requisitos | Paula Soares | 13/09/17 | 16/09/17|
|EAP| Paula Soares| 17/09/17 | 20/09/17 | 
| Criação de DataBase | Lehdson | 13/09/17 | 25/09/17 | 
|Módulo de Cadastro de Usuário | Lucas Moreira | 14/09/17 | 20/09/17
|Autenticação do Usuário | Ítalo Nascimento | 15/09/17 | 20/09/17|
|**ENTREGA PRIMEIRA RELEASE**| x | 22/08/17 | 27/09/17

**ITERAÇÃO 2**

|**SPRINT 3 - 2 SEMANAS --> 04/10 À 18/10** | **RESPONSÁVEL** |**DT INÍCIO**|**DT FIM**|
|-------|--------|-------|------|
|Layout da Sessão do Usuário DashBoard |Italo Nascimento | 04/10/17 | 11/10/17
|Layout sessão Administrativa Usuário final.|Lucas Moreira| 10/10/17 | 15/10/17
|Layout sessão Administrativa Usuário Lojas| Ítalo Nascimento | 11/10/17 | 15/10/17
|Layout sessão Administrativa Usuário Prestadores de Serviços| Italo Nascimento | 09/10/17 | 16/10/2017
|Implementação Módulo de Consulta de Clientes | Felipe Diniz | 09/10/17| 18/10/17
|Criação de Layout da index de cadastro de clientes | Italo Nascimento | 15/10/17|18/10/17|
|Implementação de Backend da index do cadastro de usuários| Lucas Moreira | 14/10/17|18/10/17
|Documento de Arquitetura | Paula Soares| 10/10/17 | 11/10/17 |
|**ENTREGA SEGUNDA RELEASE**| X | 04/10/17|25/10/17|



## 6.Análise de Riscos

| Riscos | Criticidade | Impacto | Estratégia | Plano de Ação
| ------ | ------ | ------ | ------ | ------ |
| Doenças | Alta | Cronograma | Prevenir |Manter recursos a mais 
|Escopo indefinido com prazo e custo definido| Alta | Custo / Tempo / Escopo / Qualidade | Prevenir | Definição antecipada de Escopo
|Aumento de Escopo de projeto sem ajuste de tempo, custo e recurso  | Alta | Custo / Tempo / Escopo / Qualidade | Prevenir | Realizar controle de escopo e controle integrado de mudança
|Ausência de domínio tecnológico | Média | Tempo | Prevenir | Treinamento da equipe
|Estouro de prazo devido a falhas de desenvolvimento | Média | Tempo / Custo / Escopo / Qualidade | Prevenir | Realizar mais testes afim de evitar erros imprevistos

# DOCUMENTO DE REQUISITOS

#### 1.ESCOPO
##### 1.1 REQUISITOS FUNCIONAIS

- RF01: AUTENTICAÇÃO DO USUÁRIO.
-	RF02: MANUTENÇÃO DOS CLIENTES.
-	RF03: MANUTENÇÃO DE CATEGORIAS E SUB CATEGORIAS.
-	RF04: MANUTENÇÃO DE PRODUTOS.
-	RF05: MANUTENÇÃO DE CLIENTES TEMPORARIAMENTE DESATIVADOS.
-	RF06: MANUTENÇÃO DE NESLETTER.
-	RF07: MANUTENÇÃO DE USUARIOS ADMINISTRATIVOS.
-	RF08: PAINEL DASHBOARD (ADM).
-	RF09: ÁREA DE MANUTENÇÃO DE DEPOIMENTOS DE CLIENTES.
-	RF10: MANUTENÇÃO DE SLIDRS.
-	RF11: MANUTENÇÃO DE LOJAS.
-	RF12: HISTORICO E GRAFICO DE VALORES DOS PRODUTOS.
-	RF13: MODULO DE PROSPOSTA DE NEGOCIAÇÃO.
- RF14: COMENTÁRIOS DE PRODUTOS, LOJAS E PRESTADORES DE SERVIÇOS
- RF15: BATE PAPO - (CHAT).
- RF16: ALERTA DE PRODUTOS.
- RF17: MANUTENÇÃO DE OFERTAS.
- RF18: FORMULÁRIOS DE BUSCA.

##### 1.2 REQUISITOS NÃO FUNCIONAIS

- RNF01: LIGUAGEM BACKEND DO SISTEMA.
- RNF02: BANCO DE DADOS.
- RNF03: FRAMEWORK BACK END.
- RNF04: TECNOLOGIAS FRONTEND.
- RNF05: INTERFACE GRÁFICA.
- RNF06: PAINEL DASHBOARD.
- RNF07: FORMULÁRIOS DE BUSCAS.
- RNF08: EXIBIÇÃO DE RESULTADOS DAS BUSCAS.
- RNF09: MAPAS.
- RNF10: GRÁFICO DE HISTORICO DE VALORES.
- RNF11: HISTORICO DE VALORES.
- RNF12: COMENTÁRIOS DOS PRODUTOS.
- RNF13: INFORMAÇÕES DOS ANUNCIANTES.
- RNF14: CONSULTA POR NOME.
- RNF15: NAVEGAÇÃO POR CATEGORIAS.
- RNF16: CADASTRO NEWSLETTER.
- RNF17: COMPARTILHAMENTO NAS REDES SOCIAIS.


#### 2.ESCOPO NEGATIVO

-	Não será possível efetuar compras diretamente no Custom 83
-	Não haverá opções de compra e venda diretamente no site Custom 83

## 3. DESCRIÇÃO DOS REQUISITOS FUNCIONAIS

#### 3.1 RF01 - AUTENTICAÇÃO DO USUÁRIO
Para acesso a área administrativa, deve-se existir uma autenticação de usuário que pode ser feita através dos seguintes
parâmetros:

#### 3.2 RF2: MANUTENÇÃO DOS CLIENTES.
O sistema deve ter um CRUD para manutenção dos clientes, esse o qual teremos duas superclasses "Pessoa Fisica" e "Pessoa Jurídica" que poderão ser extendidas e referenciadas pelas classes filhas "Loja" e "Prestador de Serviço"

#### 3.3 RF3: MANUTENÇÃO DE CATEGORIAS E SUB CATEGORIAS.
O sistema deve ter um CRUD para manutenção de categorias e subcategorias de produtos.

#### 3.4 RF4: MANUTENÇÃO DE PRODUTOS.
O sistema deve ter um CRUD para manutenção de produtos.

#### 3.5 RF5: MANUTENÇÃO DE CLIENTES TEMPORARIAMENTE DESATIVADOS
O sistema deve ter um módulo para manutenção de clientes temporariamente desativados o qual todo cliente que estiver nesta área do sistema, deve ter todo o seu conteúdo ocultado da página enquanto não for reativado.

#### 3.6 RF6: MANUTENÇÃO DE NESLETTER.
O sistema deve ter um módulo para manutenção de usuários cadastrados no sistema com o intuito de receber NEWSLETTER.

OBS: Para uma segunda versão, a página deve permitir um cadastro refinado do cliente.

#### 3.7 RF7: MANUTENÇÃO DE USUARIOS ADMINISTRATIVOS.
O sistema deve ter um CRUD para manutenção de usuários administrativos do sistema.

OBS: para uma segunda versão este módulo deve possuir prioridades.

#### 3.8 RF8: PAINEL DASHBOARD (ADM).
O sistema deve possuir um painel de controle personalizado para cada sessão de classes de usuários:

- Administradores
- Usuários da Página
- Prestadores de Serviços

#### 3.9 RF9: ÁREA DE MANUTENÇÃO DE DEPOIMENTOS DE CLIENTES.
O sistema deve exibir na tela inicial uma área de avaliações e depoimentos de clientes e usuários da página. 

#### 3.10 RF10: MANUTENÇÃO DE SLIDRS.
O sistema deve exibir um CRUD para manutenção de SLIDRS.

#### 3.11 RF11: MANUTENÇÃO DE LOJAS.
Deverá ser possível a empresa/loja hospedada alterar os dados de sua loja como por exemplo o nome. Deve ser possível adicionar um novo produto para determinada loja. Deve ser exibido os seguintes dados da loja ou prestador de serviço:

#### 3.12 RF12: HISTORICO E GRAFICO DE VALORES DOS PRODUTOS.
O sistema deve salvar um histórico de valores dos produtos inseridos, com referência na data de inserção ou alteração do valor, possibilitando a criação de alteração do gráfico de histórico de valores de todos os produtos.

#### 3.13 RF13: MODULO DE PROSPOSTA DE NEGOCIAÇÃO.
Este recurso deve permitir que um usuário da página possa negociar um valor com o vendedor, passando por parâmetro o valor o qual está disposto a ofertar pelo produto desejado.

#### 3.14 RF14: COMENTÁRIOS DE PRODUTOS, LOJAS E PRESTADORES DE SERVIÇOS.
O sistema deve possuir um módulo com um CRUD para comentários relacionados aos produtos, lojistas e prestadores de serviços.

#### 3.15 RF15: BATE PAPO - (CHAT).
O sistema deve ter um chat para que os usuários possam ter a interatividade com lojistas e prestadores de serviços.

#### 3.16 RF16: ALERTA DE PRODUTOS.
Dentro do módulo de manutenção de lojas e produtos, o sistema deve possibilitar através de uma flag de sinalização, se a referida loja ou produto possui alerta de proposta de negociação.

#### 3.17 RF17: MANUTENÇÃO DE OFERTAS.
O sistema deve ter um módulo para manutenção de produtos sinalizados como ofertas.

#### 3.18 RF18: FORMULÁRIOS DE BUSCA.
O formulário de busca simples deve ter um auto complete para possibilitar o preview de uma string que o usuário esteja digitando na mesma.

## 4. DESCRIÇÃO DOS REQUISITOS NÃO FUNCIONAIS
#### 4.1 RNF01 - LIGUAGEM BACKEND DO SISTEMA.
O sistema deve ser desenvolvido em linguagem PHP.

#### 4.2 RNF02 - BANCO DE DADOS.
Deverá ser usado o banco de dados MYSQL.

#### 4.3 RNF03 - FRAMEWORK BACK END.
Para o BackEnd pode ser usado em alguns módulos o framework Laravel.

#### 4.4 RNF04 - TECNOLOGIAS FRONTEND
Para o FrontEnd deve ser usado as seguintes tecnologias:

- HTML5
- CSS3
- JAVASCRIPT
- JQUERY
- BULMAIO
- JQUERY
- BOOTSTRAP

#### 4.5 RNF05 - INTERFACE GRÁFICA.
O sistema deve ter uma interface leve, intuitiva, seguindo os padrões de identidade visual do projeto.

#### 4.6 RNF07 - FORMULÁRIOS DE BUSCAS.
Na INDEX deve existir no início da página, a busca simples e avançada para que o usuário possa fazer suas consultas.

OBS: Os parâmetros de busca avançadas serão setados pela equipe de desenvolvimento.

#### 4.7 RNF09 - MAPAS.
Deve ser usado a API do google maps para indexação dos produtos no mapa.

#### 4.08 RNF10 - GRÁFICO DE HISTORICO DE VALORES.
Na descrição de cada produto deve existir um gráfico de visualização do histórico do valor do produto.

#### 4.09 RNF11 - HISTORICO DE VALORES.

#### 4.10 RNF12 - COMENTÁRIOS DOS PRODUTOS.
Ao acessar a descrição de um produto, deve existir um formulário do tipo "TEXT AREA" com a finalidade do usuário final inserir comentários sobre o mesmo.

#### 4.11 RNF13 - INFORMAÇÕES DOS ANUNCIANTES.
Dentro das informações exibidas sobre o vendedor do produto ou prestador de serviço, deve ser exibido os seguintes atributos:

- Nome da Empresa / Prestador de serviço
- Endereço.
- Telefone.
- Link do site.
- Logomarca.

OBS: OUTRAS INFORMAÇÕES PODEM SER ANEXADAS CASO A EQUIPE DE DESENVOLVIMENTO DECIDA SOBRE A INSERÇÃO DE UM NOVO ATRIBUTO. 

#### 4.12 RNF14 - CONSULTA POR NOME.
Dentro das buscas deve ter a consulta por nome do lojista ou prestador de serviço, para isso, basta apenas um formulário com auto complete para com isso o usuário final passe por parâmetro a string para efetivar a consulta.

#### 4.13 RNF16 - CADASTRO NEWSLETTER.
Todas as páginas do site terão um rodapé padrão onde vai existir um formulário para cadastro de usuários finais com interesse de receber NEWSLETTER.

OBS(1): O SITE DEVE POSSIBILITAR O CADASTRO SIMPLES COMO TAMBÉM O CADASTRO REFINADO, COM UMA SEQUENCIA DE FORMULÁRIOS QUE SERÁ DEFENIDA PELA EQUIPE.

OBS(2): O FOMULÁRIO DE CADASTRO SIMPLES TERÁ APENAS DOIS CAMPOS, SENDO DO TIPO "INPUT-TEXT", UM PARA ATRIBUTO NOME E OUTRO PARA O ATRIBUTO E-MAIL.

# DOCUMENTO DE ARQUITETURA DE SOFTWARE

#### 1.Visão Geral
Este documento está organizado em tópicos relacionados às diferentes visões arquiteturais.

#### 2.Arquitetura da aplicação
Esta seção descreve as características da arquitetura do sistema e os detalhes da avaliação das alternativas arquiteturais avaliadas. A seção também descreve a avaliação de impacto da arquitetura imposta pelo cliente, caso aplicável.

##### 2.1 Objetivos e Restrições da Arquitetura
A arquitetura proposta tem como objetivo disponibilizar um portal acessível e escalável, utilizando camadas separadas fisicamente e aderentes à arquitetura SOA, expondo funcionalidades de negócios ou aplicação

##### 2.2 Critérios de avaliação Arquitetural
Os critérios utilizados para a seleção da solução arquitetural foram:

- Escalabilidade
- Manutenibilidade
- Segurança
- Acessibilidade e usabilidade
- Integração

#### 3. Metas e Restrições da Arquitetura
- Disponibilidade
Para garantir uma alta disponibilidade os sistemas devem segmentar suas funcionalidades de forma a aplicar uma distribuição para execução das suas aplicações separadas. 

- Escalabilidade
Os sistemas devem ser construídos de forma a manter uma escalabilidade vertical, principalmente para sistemas que possua um grande volume de acesso. 

- Manutenibilidade
• Os componentes devem ser construídos de forma a distribuir o processamento do sistema, e descentralizar os componentes. 
• Os componentes dos sistemas produzidos deverão manter as nomenclaturas disponibilizadas neste documento;
• Manter o padrão de classes e componentes por este documento mencionado

#### 4. Visão Lógica
##### 4.1 Estrutura de Camadas

###### 4.1.1 Padrões Utilizados
Não se aplica.

###### 4.1.2 Visão das Camadas
Demonstração da organização das camadas para aplicações desenvolvidas em acordo com essa arquitetura.

![untitled diagram](https://user-images.githubusercontent.com/32046433/31419526-bc625b2c-ae12-11e7-9b64-88476dcc7d79.png)

- Camada de Apresentação
Essa camada conterá todas as interfaces visuais, na qual interagirá diretamente com o usuário do sistema.  E estará subdividida em:
• Visual: contem a página Web, e as referencias adequadas para Designer.  Observações: Deve-se se evitar qualquer tipo de desenvolvimento de código em PHP ou linguagem equivalente nesta camada.  
• Controle: Contem todos os códigos necessários para comunicação entre a camada de integração ou negocio, com a pagina Web. 

- Camada de Integração
Essa camada conterá as interações necessárias para integrar a camada de negocio com a camada de apresentação. A integração deve ser realizada quando o servidor Web e o servidor de aplicação estiverem em máquina distinta.

- Camada de Negócio
Essa camada conterá todas as interações necessárias para estruturação do negocio do cliente.

- Camada de Persistência
Essa camada conterá todas as interações necessárias para integrar o banco de dados com os objetos de negocio, e separar todo tipo de SQL ou linguagens padrões de banco de dados, da camada de negocio.

#### 5. Visão de Implantação
Os sistemas são distribuídos da seguinte forma:
• Servidores Web 
• Servidores de Aplicação;

##### 5.1 Visão Geral
- Autenticação: 
Para realizar a autenticação dos sistemas WEB serão utilizados uma interceptação de informação, pois assim que houver uma requisição na página será enviado ao servidor. Então a cada requisição todas as informações serão monitoradas por uma classe especifica a fim de conceder ou não a permissão. 

#### 6.Interface
##### 6.1 Visão
A organização da estrutura de interface será administrada através das seguintes classes:

- class column
- class columns
Classes padrão para o esqueleto html utilizando o bulma.io
