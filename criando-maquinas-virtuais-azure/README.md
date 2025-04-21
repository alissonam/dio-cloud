# 🌐 Desafio: Criação e Configuração de Máquina Virtual no Azure

Este repositório foi criado como parte do laboratório da **DIO (Digital Innovation One)** com o objetivo de documentar o processo de criação e configuração de uma máquina virtual utilizando a plataforma **Microsoft Azure**.

---

## ✅ Objetivos do Desafio

- Aplicar os conhecimentos adquiridos durante as aulas práticas;
- Criar e configurar uma VM no Azure via portal;
- Documentar cada etapa de forma clara e objetiva;
- Utilizar o GitHub como ferramenta de compartilhamento técnico.

---

## 💻 Etapas Realizadas

### 1. Acesso ao Portal Azure

- Link: [https://portal.azure.com](https://portal.azure.com)
- Requisitos: Conta Microsoft ativa

### 2. Criação da Máquina Virtual

- Navegação até **Máquinas Virtuais** → **Criar**
- Configurações aplicadas:
  - **Sistema Operacional:** Windows 10/11 ou Windows Server (conforme escolha)
  - **Tamanho da VM:** B1s (ideal para testes)
  - **Autenticação:** Nome de usuário e senha
  - **Grupo de Recursos:** Criado um novo grupo dedicado ao laboratório

### 3. Configurações de Rede

- Criado um grupo de segurança com regras básicas de acesso (porta RDP 3389 liberada)
- IP público associado à VM

### 4. Conexão Remota

- Conexão via RDP utilizando o IP público e as credenciais definidas
- Testes de acesso e verificação de funcionamento da VM

---

## 📝 Anotações Importantes

- Ao finalizar a criação, a VM leva alguns minutos para ficar totalmente disponível.
- É importante **anotar e guardar as credenciais de acesso**, pois não podem ser recuperadas.
- O uso da **camada gratuita do Azure** permite rodar algumas instâncias sem custos (atenção à elegibilidade).
- Evite deixar a VM ligada por muito tempo se não estiver utilizando, pois pode gerar cobrança.
