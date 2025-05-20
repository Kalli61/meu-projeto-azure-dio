
# 🚗 Projeto Microsoft Application Platform - Aluguel de Carros

Este repositório foi desenvolvido como parte do bootcamp da Digital Innovation One (DIO) em parceria com a Microsoft. O projeto simula uma plataforma de aluguel de carros com foco em arquitetura cloud utilizando serviços da Microsoft Azure.

---

## 🧠 O que eu aprendi com este projeto

### 🎯 1. Desenho de Arquitetura - Configuração de Ambiente Cloud
- Planejamento e estruturação de uma arquitetura cloud escalável e segura.
- Integração de serviços do Microsoft Azure (Azure Functions, App Services, Azure SQL, etc.).
- Criação de Resource Groups para organização de recursos.
- Configuração de ambientes segregados (dev, staging, prod).
- Utilização de Application Insights para observabilidade.

### 🧪 2. Setup de Solução com Visual Studio
- Criação da solução base utilizando Visual Studio com múltiplos projetos (API, Functions, etc.).
- Organização dos diretórios e configuração de dependências.
- Utilização de padrões de projeto e boas práticas de arquitetura em .NET.

### 🔧 3. Desenvolvimento da API BFF (Backend for Frontend) para Aluguel de Carros
- Criação de uma API intermediária entre o frontend e os serviços de backend.
- Modelagem de endpoints RESTful para gerenciamento de veículos, reservas e clientes.
- Uso de DTOs, tratamento de exceções e boas práticas de organização de código.

### 💾 4. Azure SQL Database
- Criação e configuração de um banco de dados SQL no Azure.
- Conexão da aplicação com a instância do Azure SQL.
- Execução de scripts de criação de tabelas e inserção de dados.
- Noções de segurança e firewall de IPs para acesso ao banco.

### ⚙️ 5. Azure Function – RentProcess
- Criação de função serverless para processamento de aluguéis.
- Utilização de triggers (HTTP, Queue) e bindings de entrada e saída.
- Processamento assíncrono e escalável.
- Conexão com banco de dados e envio de mensagens para filas.

### 💳 6. Azure Function – Payment
- Criação de função responsável pelo processamento de pagamentos.
- Simulação de integração com gateway de pagamento.
- Validação de dados de pagamento, callbacks e confirmações.
- Armazenamento de logs e boas práticas de segurança em transações.

---

## 🛠️ Tecnologias Utilizadas

- **Microsoft Azure**
  - Azure App Service
  - Azure Functions
  - Azure SQL Database
  - Azure Resource Groups
  - Application Insights
- **.NET / C#**
- **Visual Studio / VS Code**
- **GitHub Actions** – para CI/CD
- **Swagger** – documentação da API
- **Postman** – testes de endpoints
- **Stripe (simulado)** – integração de pagamento

---

## 🔮 Melhorias Futuras

- Autenticação e Autorização com Azure AD B2C ou JWT.
- Cache de dados com Redis para otimização da BFF.
- Implementação real de gateway de pagamento (ex: Stripe/PayPal).
- Escalonamento automático dos recursos no Azure.
- Persistência de eventos com Azure Queue ou Service Bus.
- Dashboards customizados com Application Insights.

---

## 📸 Prints do Projeto

Adicione abaixo as capturas de tela das principais etapas do seu projeto. Isso ajuda a ilustrar o funcionamento da aplicação e o uso dos recursos do Azure.

### ✅ Exemplo de prints que você pode adicionar:
- Estrutura da solução no Visual Studio
- Implantação da API BFF no Azure App Service
- Execução das Azure Functions (RentProcess e Payment)
- Configuração do Azure SQL Database
- Execução de pipeline no GitHub Actions
- Logs e métricas no Application Insights

> 💡 Crie uma pasta chamada `/imagens` no repositório e salve os prints lá. Depois, use a sintaxe:
>
> `![Descrição do print](imagens/nome-do-arquivo.png)`

---

## 📎 Link do Projeto Original

Repositório Oficial da DIO: [digitalinnovationone/Microsoft_Application_Platform](https://github.com/digitalinnovationone/Microsoft_Application_Platform)
