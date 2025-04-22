# 🚀 Desafio de Projeto DIO - Construindo Arquiteturas no Azure

Este repositório é a entrega do desafio proposto pela **DIO (Digital Innovation One)**, com o objetivo de documentar a experiência de construção de arquiteturas no azure, em especifico um grupo de recursos. A proposta visa aplicar na prática os conhecimentos adquiridos ao longo das aulas e criar um material de apoio útil para consultas futuras.

---

## ☁️ O que é a Arquitetura da Azure?

A **Azure** é a plataforma de computação em nuvem da Microsoft, oferecendo uma ampla gama de serviços que incluem:

- Máquinas Virtuais (VMs)
- Banco de Dados como Serviço (Azure SQL, Cosmos DB)
- Hospedagem de Aplicações (App Services)
- Containers (AKS, ACI)
- Funções serverless (Azure Functions)
- Monitoramento e Segurança (Azure Monitor, Azure Security Center)

> 🔹 **Dica:** Comece pequenos projetos usando serviços gratuitos da Azure para testar suas aplicações em nuvem.

---

## 📁 O que é um Grupo de Recursos?

Um **Resource Group (Grupo de Recursos)** é uma estrutura lógica que agrupa recursos da Azure (como VMs, redes, bancos, etc.) para facilitar o gerenciamento.

### Características principais:

- Permite o gerenciamento conjunto (exclusão, monitoramento, permissões).
- Recursos em um mesmo grupo podem estar em regiões diferentes, mas **por boas práticas, mantenha-os na mesma região**.
- Facilita a automação e o controle de custos.

> 💡 **Dica:** Nomeie seus grupos de forma clara, como `AZ-900_Lab_DIO` para facilitar a identificação e manutenção no futuro.

---

## 🌍 Globo dos Servidores da Microsoft (Azure Regions)

A **infraestrutura global da Azure** é composta por **regiões** distribuídas em diversos continentes. Cada região possui múltiplos datacenters conectados por uma rede de baixa latência.

### Exemplos de Regiões:

- **East US**, **West Europe**, **Brazil South**
- Cada região pode ter múltiplas zonas de disponibilidade

> 🌐 Confira o mapa oficial: [Azure Global Infrastructure](https://azure.microsoft.com/en-us/global-infrastructure/)

### Vantagens de usar regiões próximas:

- Menor latência
- Maior conformidade com legislações locais (ex: LGPD no Brasil)
- Possibilidade de criar arquiteturas de alta disponibilidade (HA)

---
