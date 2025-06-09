# ☁️ Bootcamp Microsoft 50 Anos - Computação em Nuvem com Azure (DIO)


## Laboratório 1
## 📚 Conhecimentos Adquiridos

### 🌩️ Fundamentos de Nuvem
- Arquiteturas de implantação:
  - **On-Premise** (local)
  - **Nuvem Híbrida** (hybrid cloud)
  - **Nuvem Pública** (public cloud)
- Princípios essenciais da computação em nuvem
- Modelos de serviço (IaaS, PaaS, SaaS)

### 🔵 Microsoft Azure
- Criação e configuração de contas Azure
- Navegação no portal Azure
- Visão geral dos principais serviços:
  - **Azure Virtual Machines** (VMs)
  - **Azure Storage**
  - **Azure App Services**
  - **Azure Functions**

## 🛠️ Habilidades Desenvolvidas
- ✅ Provisionamento de recursos na nuvem
- ✅ Gerenciamento básico de assinaturas Azure
- ✅ Implementação de soluções em cloud
- ✅ Comparação entre modelos de nuvem

  
## 🖥️ Laboratório 2

## Criando sua Primeira VM no Azure

### 🌟 Objetivo
Neste desafio prático, explorei o processo completo de criação e gerenciamento de máquinas virtuais na plataforma Microsoft Azure, documentando cada etapa para formar um guia de referência.

### 🛠️ Passo a Passo Executado
1. **Configuração Inicial**
   - Criação de um **Resource Group** dedicado
   - Seleção da região mais adequada (East US 2)
   - Escolha da imagem **Windows Server 2022 Datacenter**

2. **Especificações Técnicas**
   - Tipo de VM: **B1s (1 vCPU, 1GB RAM)**
   - Disco: **Standard HDD 32GB**
   - Configuração de rede básica com **NSG padrão**

3. **Conectividade**
   - Gerenciamento via **RDP (Remote Desktop Protocol)**
   - Configuração de regras de porta para acesso seguro
   - Autenticação com par de chaves SSH

### 💡 Principais Aprendizados
- Diferença entre tiers **Free vs Paid** no Azure
- Importância dos **Network Security Groups**
- Monitoramento de desempenho pelo **Azure Metrics**
- Métodos de otimização de custos

### 📌 Dicas Valiosas
✔️ Sempre usar **tags** para organização  
✔️ Configurar **alertas de orçamento**  
✔️ Testar conexão antes de implantar produção  
✔️ Documentar todas as configurações  

🔗 **Documentação Oficial**: [Azure Virtual Machines Docs](https://learn.microsoft.com/pt-br/azure/virtual-machines/)

## 🖥️ Laboratório 3

## 🗃️ Criando uma Instância Gerenciada de SQL no Azure

### 🌟 Objetivo
Implementar uma instância gerenciada de SQL Database no Azure, documentando o processo completo desde o provisionamento até a conexão segura.

### 🛠️ Passo a Passo Executado

1. **Pré-requisitos Configurados**
   - Assinatura Azure ativada
   - Resource Group dedicado criado (SQLMI-RG)
   - Rede virtual preparada com sub-rede dedicada

2. **Criação da Instância**
   - Acesso ao Azure Portal → Azure SQL → Criar
   - Seleção do tipo "Instância Gerenciada"
   - Configurações básicas:
     - Nome: sqlmi-lab3-dio
     - Região: Brazil South
     - Capacidade: 8 vCores
     - Armazenamento: 32GB

3. **Configurações de Rede**
   - Conectividade: Ponto de extremidade público
   - Porta: 1433 (SQL)
   - Regras de firewall configuradas

4. **Autenticação e Segurança**
   - Método de autenticação: SQL e Azure AD
   - Credenciais de admin configuradas
   - Política de retenção de backups: 7 dias

### 💡 Principais Aprendizados
- Diferenças entre SQL Database comum e Instância Gerenciada
- Importância do planejamento de rede virtual
- Modelo de preços baseado em vCore
- Integração nativa com serviços Azure AD

### ⚠️ Desafios Encontrados
- Tempo de provisionamento longo (~4-6 horas)
- Configuração complexa de redes virtuais
- Limitações de regiões disponíveis

### 📌 Dicas Valiosas
✔️ Planejar a topologia de rede antes de criar  
✔️ Usar o tier "Uso Geral" para testes  
✔️ Configurar alertas de custo desde o início  
✔️ Documentar todas as credenciais geradas  

🔗 **Documentação Oficial**: [Quickstart - Criar Instância Gerenciada](https://learn.microsoft.com/pt-br/azure/azure-sql/managed-instance/instance-create-quickstart)

