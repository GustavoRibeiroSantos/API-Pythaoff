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

GitLab for the development of the 5th Semester Integrator Project - Database FATEC SJC

<a name=“introducao”></a>
# 1 - Introduction
## 1.1 - Who are we :question:
Hello, nice to meet you! 
We are the PythaOff group, a team of students from the 5th semester of the Database course at FATEC São José dos Campos. This group aims to develop a project (PI) to solve a problem proposed by a partner client of the institution.

## 1.2 - Problem :exclamation:
Develop a data solution aimed at distance learning for the management and supply of knowledge, being able to provide support for the most varied 
architectures, aligned with the strategic objectives to be achieved by the organizations we serve as clients. 
as clients. We need to adjust the database, thinking in terms of large data processing with scalability gains and 
continuous integration between environments. Adicionar na solução atual um banco de dados não relacional para armazenar os chats e os logs. 
A data and analytics pipeline must be developed in order to maintain a DW and an OLAP model for data visualization and analysis.

## 1.3 - Schedule :calendar:
* 16/08/2021 to 22/08/2021 - Project Kick Off
* 30/08/2021 to 19/09/2021 - Sprint 1
* 20/09/2021 to 10/10/2021 - Sprint 2
* 10/18/2021 to 10/07/2021 - Sprint 3
* 08/11/2021 to 28/11/2021 - Sprint 4
* 29/11/2021 to xx/12/2021 - Sprint Final Presentation
* xx/xx/2021 to xx/xx/2021 - Solutions Fair Sprint

## 1.4 - Functional requirements

| Functional requirements | Code |                                                                                                                                    
| ----------------------------------|---------|
|Logs Routine |RF01 |
|Chat Routine |RF02 |
|CI/CD |RF03 | 
|Dashboards |RF04 | 
## 1.5 - Requisitos Não Funcionais

| Non-functional requirements | Code |                                                                                                                                    
| ----------------------------------|---------|
|Well-structured documentation |RF01 |
|User-friendly |RF02 |
|Scalability |RF03 |

## 1.6 - Project Progress Presentation :camera:
| Sprint 1 | Sprint 2 | Sprint 3 | Sprint 4 |
|--------- |--------- |--------- |--------- |
|<p>:white_check_mark:<a href=“#sprint01”>Done! </a></p>|<p>:white_check_mark:<a href=“#sprint02”>Done! </a></p>|<p>:white_check_mark:<a href=“#sprint03”>Done!</a></p>|<p>:white_check_mark:<a href=“#sprint04”>Done!<a></p>|

<a name=“bd”></a>
# 2 - Database Model
## 2.1 - M.E.R (Entity Relationship Model):
<div align=“center”>

![BD](/Documentos/new_oltp.png)
</div>

## 2.2 - Modeling the Data Warehouse:
<div align=“center”>
      
![DW](/Documentos/new_dw.png)
</div>

## 2.3 - Access fact table after transformation:
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
### Sprint :one: : MVP(Partial report, partial CI, partial DW)
* Modeling and creation of the DW for the first delivery;
* Use of the 3rd project;
* Processing the data collected;
* Creating application interaction with the bank to save login logs;
* Creating the front-end with the first dashboard;
* Initial CI configuration.

<a name=“sprint02”></a>
### Sprint :two: : MVP(Scalability and data processing, partial report)
* Incremental DW modeling;
* Improve performance for receiving data and DW scalability;
* Create dashboards;
  * Engagement: which students/employees are taking the course they are enrolled in;
  * Performance: how well they have done - achieved a grade - in the course in which they are enrolled;
* Performance test;
* CI configuration.

<a name=“sprint03”></a>
### Sprint :three: : MVP(Permissions, partial reports, chat, performance)
* Create login and access levels;
* Create dashboards:
  * Participation x completion rates x student/collaborator performance;
  * Reaction evaluation: qualification of the content presented, student/collaborator experience during the course;
* Capturing chat logs;
* CI configuration.

<a name=“sprint04”></a>
### Sprint :four: : (Reports, performance)
* Creation of the dashboard:
  * Recording the time spent participating in the course: online time performing the activities;
* Performance test.

<a name=“tecnologia”></a>
## 5 - Tecnologies Used:
<div align=“center”>
      
![Tecnologias](/Documentos/tecnologias_utilizadas.png)
</div>

