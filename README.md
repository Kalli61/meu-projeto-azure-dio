
# 🚗 Projeto Microsoft Application Platform - Aluguel de Carros

Este repositório foi desenvolvido como parte do bootcamp da Digital Innovation One (DIO) em parceria com a Microsoft. O projeto simula uma plataforma de aluguel de carros com foco em arquitetura cloud utilizando serviços da Microsoft Azure.

---

## 🧠 O que eu aprendi com este projeto

### 🎯 1. Desenho de Arquitetura - Configuração de Ambiente Cloud
- Planejamento e estruturação de uma arquitetura cloud escalável e segura.
- Integração de serviços do Microsoft Azure (Azure Functions, App Services, Azure SQL, etc.).
- Configuração de ambientes segregados (dev, staging, prod) com uso de Resource Groups.
- Monitoramento e observabilidade com Application Insights.

### 🔧 2. Desenvolvimento da API BFF (Backend for Frontend) para Aluguel de Carros
- Criação de uma camada intermediária entre o frontend e os serviços de backend.
- Modelagem de APIs RESTful para funcionalidades como reservas, disponibilidade e preços.
- Aplicação de boas práticas: uso de DTOs, tratamento de erros, separação de responsabilidades.

### ⚙️ 3. Azure Function – RentProcess
- Criação de funções serverless com Azure Functions.
- Automação do processo de aluguel de veículos com validação de regras de negócio.
- Uso de triggers e bindings (HTTP, Queue, Storage) para integração com outros serviços.
- Orquestração de processos de forma assíncrona e desacoplada.

### 💳 4. Azure Function – Payment
- Implementação de uma função de pagamento para simular integração com gateways (ex: Stripe).
- Validação de dados de pagamento, callbacks e confirmação de transação.
- Armazenamento seguro de logs e dados sensíveis.
- Noções de segurança, antifraude e consistência em fluxos financeiros.

---

## 🛠️ Tecnologias Utilizadas

- Microsoft Azure
  - Azure Functions
  - Azure App Service
  - Azure SQL Database
  - Azure Resource Groups
  - Application Insights
- GitHub Actions – para CI/CD
- .NET / C# – para construção das APIs e funções serverless
- Postman – para testes de APIs REST
- Visual Studio Code – ambiente de desenvolvimento
- Swagger – documentação da API
- Stripe (simulado) – como exemplo de gateway de pagamento

---

## 🔮 Melhorias Futuras

- Autenticação e Autorização com Azure AD B2C ou JWT para proteger as APIs.
- Escalonamento automático dos recursos no Azure para lidar com picos de uso.
- Cache de respostas com Redis para melhorar a performance da API BFF.
- Implementação real de gateway de pagamento, como Stripe ou PayPal.
- Persistência assíncrona com Azure Queue Storage ou Service Bus para aumentar a resiliência.
- Logs customizados e rastreabilidade com integração de Application Insights + Log Analytics.

---

## 📎 Link do Projeto Original

Repositório Oficial da DIO: [digitalinnovationone/Microsoft_Application_Platform](https://github.com/digitalinnovationone/Microsoft_Application_Platform)


---

## 📸 Prints do Projeto

Adicione abaixo as capturas de tela das principais etapas do seu projeto. Isso ajuda a ilustrar o funcionamento da aplicação e o uso dos recursos do Azure.

### ✅ Exemplo de prints que você pode adicionar:
- Implantação da API BFF no Azure App Service
- Execução das Azure Functions (RentProcess e Payment)
- Configuração do Azure SQL Database
- Execução de pipeline no GitHub Actions
- Logs no Application Insights

> 💡 Crie uma pasta chamada `/imagens` no repositório e salve os prints lá. Depois, use a sintaxe abaixo para exibir:
>
> `![Descrição do print](imagens/nome-do-arquivo.png)`
