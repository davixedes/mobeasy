# 🧪 3º Exercício para o Checkpoint 1 – DevOps Tools e Cloud Computing

**Turma:** 2TDSPS-2025  

**Grupo:** Sentinel  

**Repositório:** https://github.com/davixedes/mobeasy 

---

## 👥 Integrantes do Grupo

| Nome Completo | Matrícula | Função |
|---------------|-----------|--------|
| João Cardoso dos Santos de Jesus      | RM 560400    | DEV    |
| Kaue Vinicius Samartino               | RM 559317    | HOM    |
| Davi Praxedes Santos Silva            | RM 560719    | PRD    |

---

## 📝 Descrição da Solução
A solução consiste em uma plataforma de **aluguel de veículos peer-to-peer (P2P)**, onde proprietários podem disponibilizar seus carros para locação e usuários interessados podem reservar de forma prática e segura.  
A aplicação é hospedada em nuvem e segue práticas de DevOps para **implantação contínua (CI/CD)**, escalabilidade e monitoramento.

---

## 🎯 Objetivo
Criar uma plataforma escalável que facilite a conexão entre proprietários de veículos e motoristas, garantindo:
- Agilidade no processo de reserva e pagamento.  
- Confiabilidade na gestão de dados.  
- Disponibilidade 24/7 com suporte em cloud.

---

## 🧭 Método Adotado
- **Infraestrutura como Código (IaC)** com Terraform para provisionar recursos.  
- **Pipeline de CI/CD** com GitHub Actions para automatizar build, testes e deploy.  
- **Containers Docker** para padronizar o ambiente.  
- **Monitoramento** com Grafana e Prometheus para métricas e alertas.

---

## 💡 Proposta de Valor
- Reduz burocracia e custos em comparação com locadoras tradicionais.  
- Maior variedade de veículos disponíveis.  
- Processo transparente e seguro para proprietários e locatários.  

---

## 👤 Clientes
- Proprietários de veículos que desejam gerar renda extra.  
- Usuários que buscam aluguel de carros flexível, rápido e acessível.

---

## 🧩 Segmento de Clientes
- Pessoas físicas (motoristas ocasionais).  
- Profissionais que precisam de veículos temporários.  
- Turistas que preferem alternativas às locadoras tradicionais.

---

## ⚙️ Etapas e Recursos de Implantação
1. **Desenvolvimento do MVP** (front-end + back-end).  
2. **Criação de infraestrutura na nuvem** (banco de dados, servidores, load balancer).  
3. **Automatização do deploy** com CI/CD.  
4. **Configuração de monitoramento e logs**.  
5. **Testes em ambientes DEV, HOM e PRD**.  

---

## 🧱 Rascunho da Solução
O sistema será composto por:  
- **Front-end** em HTML, CSS + TailWind.  
- **Back-end** em Java com API REST.  
- **Banco de dados relacional** (PostgreSQL).  
- Deploy em **AWS ECS (Fargate)** com balanceamento de carga.  
- **CI/CD com GitHub Actions** garantindo integração contínua.  
- **Monitoramento** em Datadog.  

---

## 🔑 Recursos-Chave
- **Cloud AWS/Azure/GCP**  
- **GitHub Actions**  
- **Docker**  
- **Terraform/CloudFormation**  
- **PostgreSQL**  
- **Datadog**  

---

## 🎥 Vídeo Explicativo
Link para o vídeo gravado explicando a ideia do grupo:  
[Inserir link do vídeo]

---

## 💻 Código-Fonte do MVP
Se houver, incluir o código-fonte do MVP desenvolvido:  

---

## 🗄️ Banco de Dados
Será utilizado **PostgreSQL**, com estrutura relacional contendo tabelas como:  
- **Usuários** (dados pessoais, contatos, documentos).  
- **Veículos** (modelo, placa, disponibilidade, preço).  
- **Reservas** (datas, status, relação entre usuário e veículo).  
- **Pagamentos** (valores, forma de pagamento, confirmação).  

---

## 🧮 Versões dos Softwares
- Java 21 
- PostgreSQL 15  
- Docker 25.x  
- Terraform 1.9  
- GitHub Actions (workflow YAML)  
- Grafana 11 + Prometheus 3  

---

## 🚀 Próximos Passos
- Implementar autenticação e autorização (JWT).  
- Adicionar sistema de avaliações e feedback entre usuários.  
- Integrar meios de pagamento (ex: Stripe ou PayPal).  
- Evoluir a arquitetura para microsserviços.  

---

## 📚 Referências
- [AWS Documentation](https://docs.aws.amazon.com/)  
- [Azure Documentation](https://azure.microsoft.com/)
- [Terraform](https://developer.hashicorp.com/terraform/docs)  
- [Docker](https://docs.docker.com/)  

---

> **Observação:** Este repositório será avaliado como parte do Checkpoint 1, valendo até **1 ponto**. Certifique-se de que todas as seções estejam preenchidas e organizadas.
