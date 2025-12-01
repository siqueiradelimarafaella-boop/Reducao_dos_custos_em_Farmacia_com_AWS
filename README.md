## 📊 Relatório de Implementação de Serviços AWS ##

- 📅 **Data:** 01/12/2025  
- 🏢 **Empresa:** Abstergo Industries  
- 👤 **Responsável:** Rafaella Siqueira  

---

## 📝 Introdução ##

Este relatório apresenta o processo de implementação de três serviços da AWS na Abstergo Industries, com foco em otimização de custos, automação e aumento de desempenho. O objetivo principal foi modernizar a infraestrutura da aplicação de farmácia virtual, reduzindo gastos e aumentando a eficiência operacional.

---

## 🚀 Descrição do Projeto ##

O projeto foi dividido em três etapas, cada uma direcionada para resolver desafios específicos: armazenamento, computação e entrega de conteúdo.

---

## 🗂 Etapa 1 – Amazon S3 Intelligent-Tiering ##

### 🛠 Nome da ferramenta ###
Amazon S3 Intelligent-Tiering

### 🎯 Foco da ferramenta ###
Otimização automática de custos de armazenamento

### 📌 Descrição de caso de uso ###
O S3 Intelligent-Tiering move automaticamente os arquivos entre camadas de acesso frequente e infrequente, conforme o padrão real de uso. Essa automação elimina o gerenciamento manual e reduz custos com dados armazenados a longo prazo.

### ✅ Benefícios da Etapa 1 ###
- Armazena imagens de produtos, notas fiscais, backups e arquivos estáticos  
- Reduz custo em comparação ao armazenamento local  
- Oferece alta durabilidade e escalabilidade  

---

## ⚙️ Etapa 2 – Amazon EC2 Auto Scaling ##

### 🛠 Nome da ferramenta ###
Amazon EC2 Auto Scaling

### 🎯 Foco da ferramenta ###
Elasticidade computacional e redução de capacidade ociosa

### 📌 Descrição de caso de uso ###
Durante horários de menor demanda, servidores costumam ficar ociosos. O Auto Scaling ajusta automaticamente o número de instâncias conforme a carga da aplicação, evitando gastos desnecessários e garantindo desempenho durante picos.

### ✅ Benefícios da Etapa 2 ###
- Ajuste automático da infraestrutura  
- Redução de custos com servidores ociosos  
- Suporte a picos de acesso (promoções, campanhas, datas especiais)  

---

## 🌐 Etapa 3 – Amazon CloudFront ##

### 🛠 Nome da ferramenta ###
Amazon CloudFront

### 🎯 Foco da ferramenta ###
Distribuição de conteúdo com baixa latência

### 📌 Descrição de caso de uso ###
O CloudFront foi implementado como CDN para acelerar a entrega de conteúdos da aplicação de farmácia virtual, reduzindo latência e melhorando a experiência do usuário.

### ✅ Benefícios da Etapa 3 ###
- Carregamento mais rápido do site em qualquer região  
- Redução de tráfego direto ao servidor (economia de custos)  
- Melhoria no desempenho de imagens, arquivos estáticos e páginas  

---

## 🧾 Conclusão ##

As ferramentas selecionadas — Amazon S3 Intelligent-Tiering, Amazon EC2 Auto Scaling e Amazon CloudFront — formam uma solução robusta para aplicações modernas em nuvem, garantindo:

- Redução significativa de custos operacionais  
- Maior desempenho e velocidade do site  
- Escalabilidade automática baseada em demanda  
- Armazenamento seguro, durável e econômico  
- Melhor experiência do usuário final  

A adoção contínua dessas tecnologias permitirá à Abstergo Industries sustentar o crescimento da aplicação e manter alta disponibilidade com custos otimizados.

---

## 📎 Anexos ##

📚 **Documentação do Amazon S3 Intelligent-Tiering:**  
https://docs.aws.amazon.com/pt_br/AmazonS3/latest/userguide/intelligent-tiering.html

⚙️ **Guia do Amazon EC2 Auto Scaling:**  
https://docs.aws.amazon.com/pt_br/autoscaling/ec2/userguide/what-is-amazon-ec2-auto-scaling.html

🌐 **Documentação do Amazon CloudFront:**  
https://docs.aws.amazon.com/pt_br/AmazonCloudFront/latest/DeveloperGuide/Introduction.html

---

---
✍️ Assinatura do Responsável pelo Projeto

Rafaella Siqueira de Lima
- Engenheira da Computação (em formação)
