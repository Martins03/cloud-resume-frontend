🌐 Cloud Resume Frontend

Este repositório contém o código do meu currículo online, focado em performance global e infraestrutura moderna.

🚀 Live Demo
https://afonsom.dev

🛠️ Tech Stack
- Hosting: Amazon S3 (Static Website Hosting).
- Distribuição: Amazon CloudFront (CDN com suporte HTTPS).
- Domínio: name.com.
- DNS: AWS Route 53.
- Automação: GitHub Actions com autenticação OIDC.

🏗️ Arquitetura
![Arquitetura do Projeto](./images/Diagrama-Cloud-Resume.drawio.png)

🔒 Segurança (OIDC)
Este projeto não utiliza chaves AWS estáticas nos segredos do GitHub.
Mas sim, **OpenID Connect (OIDC)** para uma autenticação "short-lived" e segura entre o GitHub e a AWS.
