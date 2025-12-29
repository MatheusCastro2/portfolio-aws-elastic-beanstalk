# Portfolio Deployment: AWS Elastic Beanstalk & Docker 🚀

Este repositório contém a infraestrutura e o processo de deploy do meu portfólio profissional, utilizando containers Docker e o serviço de orquestração AWS Elastic Beanstalk. 

O objetivo deste projeto foi migrar uma aplicação estática para um ambiente de produção escalável e gerenciado na nuvem.

## 🛠️ Tecnologias Utilizadas
* **Provedor Cloud:** AWS (Amazon Web Services)
* **Serviço de Computação:** Elastic Beanstalk (PaaS)
* **Containerização:** Docker
* **Servidor Web:** Nginx (dentro do container)

## 🏗️ Arquitetura da Solução
A aplicação foi empacotada em uma imagem Docker para garantir a paridade entre os ambientes de desenvolvimento e produção. O Elastic Beanstalk gerencia automaticamente o provisionamento de capacidade, balanceamento de carga e monitoramento da saúde da aplicação.

### O Fluxo de Deploy:
1. Criação do `Dockerfile` baseado em Nginx.
2. Build da imagem e teste local.
3. Configuração do ambiente no AWS Elastic Beanstalk.
4. Upload e Deploy da aplicação via AWS Console/CLI.

## 📸 Demonstração do Ambiente (Evidências)

### 1. Dockerfile e Build
Aqui está a configuração utilizada para criar o container da aplicação:
![Print do Dockerfile ou Build Local](./caminho-da-sua-imagem/dockerfile.png)

### 2. Ambiente AWS Elastic Beanstalk (Health: OK)
Status do ambiente rodando com sucesso na nuvem AWS:
![Print do Painel da AWS com Status OK](./caminho-da-sua-imagem/aws-ok.png)

### 3. Aplicação Online
A aplicação servida através do endpoint gerado pelo Beanstalk:
![Print do Site rodando com o link da AWS](./caminho-da-sua-imagem/site-online.png)

---
