# 📄 RELATÓRIO DE PROJETO – IMPLANTAÇÃO DE SERVIÇOS AWS

📅 **Data:** 10/08/2025  
🏢 **Organização:** NovaTech Solutions  
👤 **Elaborado por:** Riquelme Soares  

---

## 1. Contexto
Visando suportar o crescimento das operações, otimizar recursos e ampliar a capacidade de resposta às demandas, a **NovaTech Solutions** decidiu adotar recursos de **computação em nuvem**.  
A **Amazon Web Services (AWS)** foi escolhida como provedora pela variedade de serviços, escalabilidade e confiabilidade.  
Este relatório apresenta três soluções estratégicas da AWS e como serão aplicadas para fortalecer a infraestrutura da empresa.

---

## 2. Objetivos do Projeto
A iniciativa busca construir um ambiente tecnológico:
- 💰 Mais econômico em relação à manutenção de infraestrutura física.  
- ⚡ Com desempenho aprimorado no tratamento e na disponibilização de dados.  
- 🔗 Capaz de crescer rapidamente e se integrar a sistemas externos.  

**Serviços AWS selecionados para esta implantação:**
1. **Amazon S3** – Armazenamento escalável e seguro.  
2. **Amazon RDS** – Banco de dados relacional gerenciado.  
3. **AWS Lambda** – Execução de funções sob demanda (serverless).  

---

## 3. Serviços AWS e Plano de Implementação

### 3.1 📦 Amazon S3 – Armazenamento em Nuvem
**Função:** Hospedar arquivos corporativos (documentos, relatórios, mídias) com alta durabilidade.  
**Economia:** Dispensa aquisição e manutenção de servidores de armazenamento locais, com cobrança proporcional ao uso.  
**Benefício central:** Disponibilidade global e escalabilidade automática.  

**Passos propostos:**
1. Criar bucket no S3 com configuração de acesso e permissões específicas.  
2. Ativar versionamento e backups automáticos.  
3. Definir políticas de ciclo de vida para arquivamento em camadas mais baratas (ex.: S3 Glacier).  

---

### 3.2 🗄️ Amazon RDS – Banco de Dados Gerenciado
**Função:** Gerenciar dados críticos como estoque, pedidos e histórico de vendas em ambiente seguro e de alta performance.  
**Economia:** Reduz custos com administração de servidores e infraestrutura física.  
**Benefício central:** Operação confiável com backups e redundância automática.  

**Passos propostos:**
1. Selecionar mecanismo de banco (PostgreSQL, MySQL, etc.).  
2. Provisionar instância com replicação e backup automáticos.  
3. Migrar dados atuais via AWS Database Migration Service.  

---

### 3.3 ⚡ AWS Lambda – Processamento Serverless
**Função:** Automatizar fluxos internos, como atualizações de estoque e integração com APIs de parceiros.  
**Economia:** Custos proporcionais ao tempo de execução, sem servidores dedicados.  
**Benefício central:** Flexibilidade para lidar com cargas de trabalho variáveis.  

**Passos propostos:**
1. Desenvolver funções Lambda para eventos específicos.  
2. Integrar com S3 e RDS para processamento dinâmico de dados.  
3. Monitorar desempenho via Amazon CloudWatch.  

---

## 4. Considerações Finais
A implementação do **Amazon S3**, **Amazon RDS** e **AWS Lambda** trará à NovaTech Solutions:  
- 💰 Redução de despesas com infraestrutura.  
- 🔒 Fortalecimento da segurança e disponibilidade dos dados.  
- 📈 Maior capacidade de expansão e agilidade operacional.  

Essa estratégia posiciona a empresa para acompanhar o ritmo do mercado, garantindo um crescimento sustentável e competitivo.  
