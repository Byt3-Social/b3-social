# Byt3 Social | O jeito B3

---

Os submódulos desse repositório referenciam os repositórios que contém os códigos desenvolvidos para cada microsserviço do sistema construido

## Equipe
Este projeto foi desenvolvido pelos seguintes membros:

[<img align="center" src="https://img.shields.io/badge/linkedin-%230077B5.svg?style=for-the-badge&logo=linkedin&logoColor=white"> Leandro Pereira](https://www.linkedin.com/in/leojgpereira/)

[<img align="center" src="https://img.shields.io/badge/linkedin-%230077B5.svg?style=for-the-badge&logo=linkedin&logoColor=white"> Roney Miranda](https://www.linkedin.com/in/roney-miranda-263494229/)

[<img align="center" src="https://img.shields.io/badge/linkedin-%230077B5.svg?style=for-the-badge&logo=linkedin&logoColor=white"> Lucas Carvalho](https://www.linkedin.com/in/lucasweltersoft/)

[<img align="center" src="https://img.shields.io/badge/linkedin-%230077B5.svg?style=for-the-badge&logo=linkedin&logoColor=white"> Fernanda Mascarenhas](https://www.linkedin.com/in/fernanda-mascarenhas-21a561277/)

Além disso, contou com a mentoria dos seguintes colaboradores da B3:

* Anita Nascimento (Mentora)
* Cristiano Mariano
* Giovanni Bertotti
* Bruno Simão

Agredecemos também a Marcelly Guerrero pelo auxilio no levantamento de requisitos do sistema.

## Desafio proposto
O desafio proposto consiste no desenvolvimento de um sistema especializado que permita o cadastro de ações socias e divulgação das mesmas para os colaboradores internos da B3.

## Solução 
Com base no levantamento de requisitos e levando em consideração o desafio proposto concluímos que não há um sistema unificado que envolva todo o processo de cadastramento de ações sociais na B3 Social. Portanto, nossa ideia consistiu no desenvolvimento de uma plataforma de serviços B3 Social que abranja todas as etapas de cadastramento de uma ação social, sendo elas: o cadastro de uma organização por parte do setor de prospecção, a análise documental da organização cadastrada por parte do setor de compliance, o cadastro das ações - tanto ações de voluntariado quanto ações de investimento social privado (ISP) - a divulgação de ações de voluntariado e de campanhas de doação ,e por fim, o acompanhamento dos indicadores das ações realizadas.

## Tecnologias utilizadas

* Back-end
  * Java
  * Spring Boot
  * MySQL - Banco de Dados
  * RabbitMQ - Mensageria
  * Flyway - Migrations
  * Eureka Server - Serviço de descoberta
  * SpringDoc
  * Docker - [Imagens disponíveis no Docker Hub](https://hub.docker.com/search?q=byt3social)


* Front-end
  * VueJS
  * HTML
  * CSS
  * Sass
  * JS

## Arquitetura
Aqui disponibilizamos links referente aos documentos elaborados durante a concepção da nossa solução

* [Levantamento de requisitos inicial](https://drive.google.com/file/d/1gSOdgXK_QeUY5rih4DZDTklf4ZcwvCIl/view?usp=sharing)
* [Modelo de negócio - Ações de Voluntariado](https://drive.google.com/file/d/1DYk9-rJXEyLoe_PxInbfFaVykHr08Odu/view?usp=sharing)
* [Modelo de negócio - Ações de ISP](https://drive.google.com/file/d/1orhJsUzuWRVOb9LldblFZRq3nCk2MFo6/view?usp=sharing)
* [Modelo Conceitual](https://drive.google.com/file/d/1xH8tK8zj2h4isc6YS0OHGAEi-MoZZGpi/view?usp=sharing)
* [Arquitetura do sistema](https://drive.google.com/file/d/1Mmmt9KmcfkdHglbHsJZJYONfejSI0tHe/view?usp=sharing)

## Integrações
* Microsoft Entra ID (Azure Active Directory) - Autenticação
* AWS S3 - Armazenamento de Arquivos
* PDSign - Assinatura digital de documentos
* PagSeguro - Processamento de doações
* Microsoft Teams - Agendamento de reuniões