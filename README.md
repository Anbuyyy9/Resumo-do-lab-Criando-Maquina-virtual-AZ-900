# ☁️ Criando Máquina Virtual no Azure – Lab AZ-900

Este repositório documenta a experiência prática adquirida durante o laboratório de criação de máquinas virtuais na plataforma **Microsoft Azure**, parte essencial da preparação para a certificação **AZ-900: Microsoft Azure Fundamentals**.

---

## 🎯 Objetivo do Lab

O objetivo foi configurar uma **Máquina Virtual (VM)** na nuvem, explorando os conceitos fundamentais de **Infraestrutura como Serviço (IaaS)**, aprendendo a balancear **segurança**, **custo** e **escalabilidade** no ambiente Azure.

---

## 🧪 Etapas Realizadas no Lab

### 1. 🔧 Criação da Máquina Virtual

- Seleção da **imagem do sistema operacional** (Linux ou Windows)
- Escolha do **tamanho da VM** (SKU), balanceando custo e desempenho
- Geração de **credenciais de acesso seguras**

### 2. 🌐 Configuração de Rede

- Associação da VM a uma **Virtual Network (VNet)**
- Criação de um **Security Group (NSG)** com regras de acesso (ex: porta 22 para SSH ou 3389 para RDP)
- Atribuição de **endereço IP público** para acesso externo (caso necessário)

### 3. 🔒 Segurança e Acesso

- Utilização de **chaves SSH** (para Linux) ou autenticação por senha (para Windows)
- Criação de **usuário administrador seguro**
- Configuração de políticas de **segurança mínima necessária**

### 4. 📊 Gerenciamento de Recursos

- Inserção da VM em um **Resource Group**
- Configuração da **região geográfica** (para latência e conformidade)
- Aplicação de **tags** para organização e controle de custos

### 5. 🧠 Aprendizados

- Compreensão prática da arquitetura de **Infraestrutura como Serviço (IaaS)**
- Noções claras sobre:
  - **Provisionamento de recursos**
  - **Modelos de cobrança baseada em uso**
  - **Gerenciamento e monitoramento** com o Azure Portal
- Reconhecimento da **interface intuitiva** do Azure e das possibilidades de **automação** com templates ou CLI

---

## 📘 Conceitos Fundamentais Praticados

| Conceito | Descrição |
|---------|------------|
| IaaS (Infraestrutura como Serviço) | Provisão de recursos de computação como VMs, redes e armazenamento |
| Resource Group | Unidade lógica para agrupar e gerenciar recursos |
| Região (Region) | Local físico onde os datacenters estão localizados |
| Azure VM | Máquina virtual escalável e altamente disponível |
| VNet | Rede virtual privada no Azure para comunicação entre recursos |
| NSG (Network Security Group) | Firewall que regula o tráfego de entrada e saída |

---

## 💡 Conclusão

A criação de uma Máquina Virtual no Azure foi essencial para consolidar os conhecimentos teóricos da certificação **AZ-900**, oferecendo uma visão clara da **provisionamento de infraestrutura na nuvem**. Compreendi a importância de boas práticas de segurança, escalabilidade e controle de custos ao lidar com recursos em ambiente cloud.

---

## 🧠 Sobre o Autor

**Gabriel (Anbuyyy9)**  
Entusiasta de tecnologia, apaixonado por nuvem, cibersegurança e automação.  
🚀 *Estudando para transformar o conhecimento técnico em soluções reais.*

---

## 📌 Referências

- [Microsoft Learn – Criar uma VM no Azure](https://learn.microsoft.com/pt-br/training/modules/create-windows-virtual-machine-in-azure/)
- [Documentação Oficial do Azure](https://learn.microsoft.com/pt-br/azure/virtual-machines/)

