# ☁️ Fundamentos de AWS - Gerenciamento de Instâncias EC2

Este repositório foi criado como parte do desafio da plataforma DIO no curso **Fundamentos de AWS e Cloud**.

O objetivo deste projeto é reunir anotações, conceitos e insights adquiridos durante os estudos sobre serviços da AWS, servindo como material de apoio para futuras implementações e revisões.

---

# 📚 Conteúdos Estudados

## 🔹 Conceitos de Cloud Computing

- O que é computação em nuvem
- Modelos de serviço:
  - IaaS
  - PaaS
  - SaaS
- Tipos de nuvem:
  - Pública
  - Privada
  - Híbrida

---

# 🌎 AWS - Infraestrutura Global

## Regions
- Compliance
- Disponibilidade de serviços
- Custos
- Latência
- Cada região possui 2 ou mais Availability Zones (AZ)

## Availability Zones (AZ)
- Datacenters conectados logicamente
- Recursos isolados e redundantes
- Alta disponibilidade

---

# 🔐 AWS - Configuração da Conta AWS

- IAM (Identity Access Management)
- Configurar a conta Root como conta principal
- Criar usuários com permissões específicas
- Evitar o uso da conta Root no dia a dia
- Criar grupos de usuários e aplicar políticas
- Utilizar autenticação multifator (MFA)

---

# 🚀 Amazon EC2 (Elastic Compute Cloud)

## O que é EC2?

O Amazon EC2 é um serviço da AWS que permite criar e gerenciar máquinas virtuais na nuvem de forma escalável.

### Características
- Sistemas operacionais:
  - Windows
  - Linux
- Serviço do tipo IaaS
- Instâncias criadas de acordo com a necessidade de recursos
- Escalabilidade e otimização de custos na nuvem

---

## 📌 Famílias de Instâncias

- General Purpose
- Compute Optimized
- Memory Optimized
- Accelerated Computing
- Storage Optimized

---

## 📌 Formas de Otimização de Recursos

- Criar automações para ligar/desligar máquinas
- Realocar recursos de acordo com a utilização
- Escalar horizontalmente e verticalmente

---

## 📌 Tipos de Instâncias

### On-Demand
- Cobrança por uso
- Ideal para cargas de trabalho de curto prazo
- Não pode ser interrompida

### Reserved Instances
- Contrato de 1 ano ou mais
- Mais econômica
- Indicada para uso frequente

### Spot Instances
- Até 90% mais barata que On-Demand
- Pode ser interrompida pela AWS a qualquer momento

---

# 💾 Amazon EBS (Elastic Block Store)

## O que é EBS?

Serviço de armazenamento em blocos utilizado nas instâncias EC2.

### Características
- Expansão rápida de capacidade
- Pode ser conectado a diferentes instâncias
- Funciona de forma semelhante a um HD externo
- Permite criação de novas partições

---

# 📦 Amazon S3 (Simple Storage Service)

## O que é S3?

Serviço de armazenamento de objetos da AWS.

---

## 📌 Tipos de Armazenamento

- S3 Standard
- S3 Standard-IA
- S3 One Zone-IA
- S3 Glacier

---

## 📌 Funcionamento

### S3 Standard
- Recuperação rápida
- Ideal para arquivos acessados com frequência

### S3 Glacier
- Ideal para arquivamento de longo prazo
- Menor custo
- Recuperação mais lenta
- Necessário solicitar restauração do arquivo antecipadamente

---

## 📌 Lifecycle

- Automatiza transição de objetos entre classes de armazenamento
- Permite migração automática para Glacier

---

## 📌 AWS Lambda

- Executa códigos personalizados
- Automatiza processos relacionados aos dados armazenados

---

# 🖼️ Amazon AMI (Amazon Machine Image)

## O que é AMI?

Uma AMI é uma imagem pré-configurada de uma instância EC2 contendo:
- Sistema operacional
- Aplicações
- Configurações
- Dados necessários para inicialização

### Características
- Pode ser criada a partir de instâncias em execução ou paradas
- Pode utilizar AMIs públicas
- Também é possível criar AMIs privadas personalizadas

---

# 📸 Snapshots EBS

Snapshots são utilizados para:
- Backup
- Replicação de instâncias EC2 entre regiões

### Características
- Armazenados no Amazon S3
- Podem ser automatizados conforme a necessidade do cliente

---

# 🎯 Objetivo do Repositório

Este repositório tem como finalidade:
- Documentar o aprendizado em AWS
- Servir como material de consulta
- Apoiar estudos futuros em Cloud Computing

---

# ✍️ Autor
Izabel Forte
