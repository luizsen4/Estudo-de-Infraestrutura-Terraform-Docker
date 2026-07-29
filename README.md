# 🛠️ Estudo de Infraestrutura: Terraform + Docker

Projeto desenvolvido para a disciplina de **DevOps** com o objetivo de praticar conceitos de Infraestrutura como Código (IaC) e conteinerização.

---

## 🎯 Objetivo do Projeto

Automatizar a criação de um ambiente local/servidor utilizando **Terraform** para provisionar a estrutura e **Docker** para subir as aplicações/serviços necessários de forma rápida e padronizada.

---

## 🧰 Tecnologias Utilizadas

* **[Terraform](https://www.terraform.io/)** — Automação e provisionamento de infraestrutura como código (IaC).
* **[Provider Docker (`kreuzwerker/docker`)](https://registry.terraform.io/providers/kreuzwerker/docker/latest/docs)** — Provider oficial/comunitário para interagir com a API do Docker Engine através do HCL.
* **[Docker](https://www.docker.com/)** — Engine de conteinerização para execução dos serviços.

---

## 📂 Estrutura de Pastas

```text
├── terraform/          # Arquivos de configuração do Terraform (.tf)
├── docker/             # Dockerfile ou docker-compose do projeto
├── .gitignore          # Arquivos ignorados pelo Git
└── README.md           # Documentação do projeto
