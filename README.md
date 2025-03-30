<div align="center">
      
![API-Pythaoff](/Documentos/Logo_PythaOff.png)
      
</div>

[![Gitpod Ready-to-Code](https://img.shields.io/badge/Gitpod-Ready--to--Code-blue?logo=gitpod)](https://gitpod.io/#https://gitlab.com/gurst6/pythaoff-ness)


<div align="center">
      <h2>Menu</h2>
      <p>
            :small_blue_diamond:<a href="#introducao">Introduction</a>
            :small_blue_diamond:<a href="#bd">Database model</a>
            :small_blue_diamond:<a href="#estrutura">Project Structure</a>
            :small_blue_diamond:<a href="#tecnologia">Tecnologies</a>
      </p>
</div>


# <h1>Integrative Project 5th Semester BD - PythaOff Group :no_mobile_phones:</h1>

GitLab para desenvolvimento do Projeto Integrador do 5º Semestre - Banco de dados FATEC SJC


<a name=“introducao”></a>
# 1 - Introdução
## 1.2 - Quem somos :question:
Olá! Muito prazer! 
Nós somos o grupo PythaOff, um time de alunos do 5° semestre do curso de Banco de Dados da FATEC de São José dos Campos. Esse grupo tem como objetivo desenvolver um projeto (PI) para solucionar um problema proposto por um cliente parceiro da instituição.

## 1.3 - O problema :exclamation:
Desenvolver uma solução de dados voltada ao ensino a distância para a gestão e oferta do conhecimento, sendo apto a prover suporte às mais 
variadas arquiteturas de aprendizagem, alinhado com os objetivos estratégicos a serem alcançados pelas organizações que atendermos 
como clientes. Precisamos ajustar o banco de dados, pensando em um grande processamento de dados com ganho de escalabilidade e 
integração contínua entre os ambientes. Adicionar na solução atual um banco de dados não relacional para armazenar os chats e os logs. 
Deve ser desenvolvido um pipeline de dados e analytics, a fim de manter um DW e um modelo OLAP para visualização e análise de dados.

## 1.4 - Schedule :calendar:
* 16/08/2021 to 22/08/2021 - Project Kick Off
* 30/08/2021 to 19/09/2021 - Sprint 1
* 20/09/2021 to 10/10/2021 - Sprint 2
* 10/18/2021 to 10/07/2021 - Sprint 3
* 08/11/2021 to 28/11/2021 - Sprint 4
* 29/11/2021 to xx/12/2021 - Sprint Final Presentation
* xx/xx/2021 to xx/xx/2021 - Solutions Fair Sprint

## 1.5 - Requisitos Funcionais

| Requisitos não funcionais | Código |                                                                                                                                    
| ----------------------------------|---------|
|Rotina de Logs |RF01 |
|Rotina de Chat |RF02 |
|CI/CD |RF03 | 
|Dashboards |RF04 | 
## 1.6 - Requisitos Não Funcionais

| Requisitos não funcionais | Código |                                                                                                                                    
| ----------------------------------|---------|
|Documentação bem estruturada |RF01 |
|Facilidade de uso |RF02 |
|Escalabilidade |RF03 |

## 1.7 - Apresentação da Evolução do Projeto :camera:
| Sprint 1 | Sprint 2 | Sprint 3 | Sprint 4 |
|--------- |--------- |--------- |--------- |
|<p>:white_check_mark:<a href=“#sprint01”>Done! </a></p>|<p>:white_check_mark:<a href=“#sprint02”>Done! </a></p>|<p>:white_check_mark:<a href=“#sprint03”>Done!</a></p>|<p>:white_check_mark:<a href=“#sprint04”>Done!<a></p>|

<a name=“bd”></a>
# 2 - Modelo do Banco de Dados
## 2.1 - M.E.R (Modelo Entidade Relacionamento):
<div align=“center”>

![BD](/Documentos/new_oltp.png)
</div>

## 2.2 - Modelagem do Data Warehouse:
<div align=“center”>
      
![DW](/Documentos/new_dw.png)
</div>

## 2.2 - Tabela Fato acesso após transformação:
<div align=“center”>
      
![DW](/Documentos/factAccess.png)
</div>

<a name="ETL"></a>
# 3 - Project structure

## 3.1 - CI/CD
CI/CD, continuous integration/continuous delivery, is a method for frequently delivering applications to customers. To do this, automation is applied to the stages of application development. The main concepts attributed to this method are continuous integration, delivery and deployment. With CI/CD, it is possible to solve the problems that integrating new code can cause for the operations and development teams. From this perspective, this project used Docker's containerization concept, which is nothing more than an open platform for creating, executing and deploying containers. A Container is a way of packaging your application and its dependencies (libraries) in a standardized way. See the image below for the CI/CD configuration script, defining the stages, jobs and other dependencies that are part of the pipeline:

<div align="center">
      
![ETL](/Documentos/cicd.png)
</div>


## 3.2 - ETL process completed:
<div align="center">
      
![ETL](/Documentos/etl_finalizado.png)
</div>

## 4 - Project Backlog:

<a name=“sprint01”></a>
### Sprint :one: : MVP(Relatório parcial, CI parcial, DW parcial)
* Modelagem e criação da DW para a primeira entrega;
* Utilização do projeto do 3º;
* Tratamento dos dados coletados;
* Criar interação da aplicação com o banco para salvar logs de login;
* Criação do front-end com o primeiro dashboard;
* Configuração inicial de CI.

<a name=“sprint02”></a>
### Sprint :two: : MVP(Escalabilidade e processamento de dados, relatório parcial)
* Modelagem DW incremental;
* Melhorar desempenho para recebimento de dados e escalabilidade do DW;
* Criar os dashboards;
  * Engajamento: quais alunos/colaboradores estão fazendo o curso no qual está matriculado;
  * Desempenho: qual o aproveitamento - nota atingida - no curso no qual está matriculado;
* Teste de desempenho;
* Configuração de CI.

<a name=“sprint03”></a>
### Sprint :three: : MVP(Permissões, relatórios parciais, chat, desempenho)
* Criar login e níveis de acesso;
* Criação dos dashboards:
  * Participação x taxas de conclusão x desempenho dos alunos/colaboradores;
  * Avaliação de reação: qualificação do conteúdo apresentado, experiência do aluno/colaborador durante o curso;
* Captura dos logs do chat;
* Configuração de CI.


<a name=“sprint04”></a>
### Sprint :four: : (Relatórios, desempenho)
* Criação do dashboard:
  * Registro do tempo de participação no curso: tempo online executando as atividades;
* Teste de desempenho.

<a name=“tecnologia”></a>
## 5 - Tecnologias Utilizadas:
<div align=“center”>
      
![Tecnologias](/Documentos/tecnologias_utilizadas.png)
</div>

