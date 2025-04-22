# 🚀 Desafio de Projeto DIO - Configurando Recursos e Dimensionando Máquinas Virtuais na Azure

Este repositório contém um resumo das lições aprendidas durante o desenvolvimento do lab da **DIO (Digital Innovation One)**, com foco em serviços de computação na nuvem utilizando o **Microsoft Azure**. O conteúdo envolve a criação e gerenciamento de máquinas virtuais, escalabilidade de serviços, área de trabalho virtual e aplicativos de funções.

---

## ☁️ Tópicos Abordados

### 🚀 Criação de uma Máquina Virtual

- Acesse o portal do Azure e selecione **Máquinas Virtuais**.
- Clique em **Criar** > **Máquina Virtual**.
- Escolha a **imagem** do sistema operacional, o **tamanho da VM** e as **credenciais de acesso**.
- Configure a rede virtual e outras opções de segurança.
- Dica: Utilize **grupos de recursos** para organizar seus recursos por projeto ou ambiente.

### 📈 Conjunto de Dimensionamento de Máquinas Virtuais (VM Scale Set)

- Ideal para aplicações que precisam ser escaladas automaticamente.
- Criação via **Azure Compute > Conjuntos de Dimensionamento de Máquinas Virtuais**.
- Permite gerenciar um conjunto de VMs idêinticas.
- Útil para cargas variáveis e sistemas com alta disponibilidade.

### ⚙️ Configuração da Escala

- Escala pode ser:
  - **Horizontal (scale-out)**: adiciona mais instâncias.
  - **Vertical (scale-up)**: aumenta recursos da instância atual.
- Configurações de escala incluem:
  - **Mínimo, máximo e instâncias padrão**.
  - **Regras de autoscale**, como CPU acima de 70% por mais de 10 minutos.

### 💥 Área de Trabalho Virtual – Pool de Hosts

- Área de Trabalho Virtual do Azure (AVD) permite acesso remoto a desktops e apps.
- **Pool de Hosts**: grupo de VMs que fornecem sessões aos usuários.
- Importante configurar corretamente:
  - A imagem da VM.
  - O número de VMs no pool.
  - O tipo de balanceamento (profundidade ou largura).

### ⚙️ Aplicativos de Funções (Azure Functions)

- Executa pequenos trechos de código sob demanda.
- Baseado em eventos (event-driven).
- Suporta várias linguagens como C#, JavaScript e Python.
- Ideal para tarefas como:
  - Processamento de arquivos.
  - Integrações entre sistemas.
  - Reações a eventos em tempo real.

---

## 📚 O que aprendi

Durante o desenvolvimento do lab, aprofundei meu conhecimento sobre:

- Provisionamento e configuração de máquinas virtuais no Azure.
- Como escalar aplicações automaticamente utilizando conjuntos de dimensionamento.
- Criação e gerenciamento de pools de hosts em ambientes de trabalho virtual.
- Aplicação do modelo serverless com Azure Functions para reduzir custos e simplificar a lógica de backend.
- A importância da automação e organização dos recursos para melhorar a performance e escalabilidade das aplicações na nuvem.

---
