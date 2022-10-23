# Bem vindo ao projeto de  Modelagem EER para uma aplicação de *E-commerce*.

Nesse projeto desafio proposto pela DIO foi feito um modelamento de um *sistema de gestão de ordens de serviço para uma oficina* Foi apresentado um levantamento de requisitos infomados pelo cliente para a aplicação, foram constituídas as entidades que fazem a persistência dos dados da aplicação. Todos os relacionamentos foram estruturados visando a obtenção de diversas visões dos dados. Para a elaboração do diagrama EER foi utilizado o *MySql Workbench*.
As chaves primárias e estrangeiras também foram definidas durante a construção do diagrama.
Todos esses estudos foram feitos seguindo a trilha **Construindo um Esquema Conceitual para Banco De dados – Modelando do Zero** do *bootcamp* **UNIMED BH :green_heart: com a DIO :muscle:** apresentado pela **Juliana Mascarenhas**.

O modelo foi desenvolvido conforme as seguintes idéias:
Um cadastro de pessoas que podem ser **clientes** ou
**funcionários** com os dados básicos.
- Clientes possuem data de último contato e situação.
- Funcionários possuem Especialidade e matricula.

Os **clientes**:
• Possuem **veículos** com data da última revisão e
situação (ativo ou não) além dos dados do veiculo.
• Geram **ordens de serviço** que podem ou não ser
executadas e podem ter o seu valor final alterado a
critério do atendente (promoções, fidelidade etc).
• Associados a cada ordem estão as **peças** e os
**serviços**. Elas (peças ou serviços) podem ser
aprovados para execução/instalação
individualmente. Também podem receber
modificação local do seu valor individual


Os **funcionários**:
• Estão vinculados a uma **equipe**. Essa equipe possui
um funcionário registrado como líder.
• Executam o levantamento das necessidades de
reparo (peças e/ou serviços) e lançam no Sistema.
• Executam as atividades autorizadas pelo cliente no
veículo.

# Arquivos e pastas

Esse estudo foi dividido da seguinte forma:

:file_folder: **Apresentação**: contém uma apresentação com as idéias adotadas no modelamento dessa necessidade em um arquivo no formato PDF. O desafio consistiu na construção de um modelo EER para um sistema de ordens de serviço de uma oficina automotiva.

 - Arquivo de apresentação: **Solução_Modelada.pdf**
 
:file_folder: **Modelos**: contém os arquivos criados no *MySQL Workbench* para atendimento das necessidades identificadas para o sistema

 - Arquivo criando no MySQL Workbench: **OficinaV1.mwb** (primeira versão)
 - Arquivo criando no MySQL Workbench: **OficinaV2.mwb** (versão final)
 -  Arquivo exportado do MySQL Workbench: **OficinaV2.png** (caso não tenha o software *MySQL Workbench* instalado).


## Software
### MySQL Workbench 8.0 CE

## Autor

Moysés Dutra da Silva
<p>
  <a href="https://www.linkedin.com/in/moyses-dutra/" rel="nofollow noreferrer">
    <img src="https://i.stack.imgur.com/gVE0j.png" alt="linkedin"> LinkedIn
  </a> &nbsp; 
  <a href="https://github.com/moysesdutra" rel="nofollow noreferrer">
    <img src="https://i.stack.imgur.com/tskMh.png" alt="github"> Github
  </a>
</p>
  

## Licença

[MIT] <https://choosealicense.com/licenses/mit>


### English

# Welcome to the project EER applied to an E-commerce Application!

In this project proposed by DIO, a small context modeling was done on an automotive workshop application. The result of some interviews were carried out to identify the customer's needs.  Based on these interviews, an EER model was made.  All activities were done using the MySQL Workbench application  .  All these studies were carried out according to the trail **Construindo um Esquema Conceitual para Banco De dados – Modelando do Zero** from the UNIMED BH :green_heart: bootcamp with DIO :muscle: presented by  **Juliana Mascarenhas**.


The model was developed according to the following ideas:
A register of people who can be **clients** or
**employees** with your basic data.
- Clients have date of last contact and status.
- Employees have speciality and ID.

The **clients**:
• Own **cars** with the date of your last service date and status (active or not) in addition to vehicle data.
• Generate **Service orders** that may or not may executed and may have their final value changed at the discretion of the attendant (promotion, loyalty, etc.).
• Assigneds to each order are the **parts** and the **services**. These may or not may aproved individualy for use in that order. May have their final value changed 


The **employees**:
• Are assigned to a **team**. This team have an employee registered as a leader.
• Do a needs assessment repair(parts and/or services) put on the system.
• Perform all approved services on the customer's vehicle.


# Files and Folders

This study was divided as follows:

:file_folder: **Apresentação**: contains an presentation with the ideas used in this modeling in a PDF file. The challenge was a building an EER model for a automotive workshop ticketing system.

 - Presentation file: **Solução_Modelada.pdf**
 

:file_folder: **Modelos**: contains the files made with MySQL Workbench to solve this challenge.

 - File created in MySQL Workbench: **OficinaV1.mwb** (first version)
 -  File created in MySQL Workbench: **OficinaV2.mwb** (final version)
 -  File exported from MySQL Workbench: **OficinaV2.png** (if the software *MySQL Workbench* is not available).


## Software

### MySQL Workbench 8.0 CE

## Author

Moysés Dutra da Silva
<p>
  <a href="https://www.linkedin.com/in/moyses-dutra/" rel="nofollow noreferrer">
    <img src="https://i.stack.imgur.com/gVE0j.png" alt="linkedin"> LinkedIn
  </a> &nbsp; 
  <a href="https://github.com/moysesdutra" rel="nofollow noreferrer">
    <img src="https://i.stack.imgur.com/tskMh.png" alt="github"> Github
  </a>
</p>
  

## License

[MIT] <https://choosealicense.com/licenses/mit>