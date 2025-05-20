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

Adicione abaixo as capturas de tela das principais etapas do seu projeto. Isso ajuda a ilustrar o funcionamento da aplicação e o uso dos recursos do Azure.

### ✅ Exemplo de prints que você pode adicionar:
- Estrutura da solução no Visual Studio
- Implantação da API BFF no Azure App Service
- Execução das Azure Functions (RentProcess e Payment)
- Configuração do Azure SQL Database
- Execução de pipeline no GitHub Actions
- Logs e métricas no Application Insights

--- 

## 📸 Prints do Projeto
`![Captura de Tela (87)](https://github.com/user-attachments/assets/5f97262e-c0ab-4488-8903-834bb1e51d84)
![Captura de Tela (88)](https://github.com/user-attachments/assets/c141ebbe-1bb4-4a9b-9387-8c3e58acd5d9)
![Captura de Tela (89)](https://github.com/user-attachments/assets/6ed3e808-7f96-4a20-9a91-ba4ad0463a85)
![Captura de Tela (90)](https://github.com/user-attachments/assets/ebf72ad6-9de3-407d-9deb-d33b8364b3f1)
![Captura de Tela (91)](https://github.com/user-attachments/assets/140df604-9465-471f-970c-cc198f2c21d7)
![Captura de Tela (92)](https://github.com/user-attachments/assets/45e249b6-c153-4d6a-aaf2-faf655f82148)
![Captura de Tela (93)](https://github.com/user-attachments/assets/10b19448-6567-4d04-bdf6-985b2e49b9ec)
![Captura de Tela (94)](https://github.com/user-attachments/assets/06ed9330-6f99-4a67-9afe-c28c9e7cc5b6)
![Captura de Tela (95)](https://github.com/user-attachments/assets/504bc61b-ea64-41db-9175-813d7215f398)
![Captura de Tela (96)](https://github.com/user-attachments/assets/2e8d2e66-2812-4f51-a143-925bde509e4e)
![Captura de Tela (96)](https://github.com/user-attachments/assets/5c345ee0-2f77-41d2-bf51-fd5b738a30a1)
![Captura de Tela (95)](https://github.com/user-attachments/assets/0d824871-09e0-43ea-a0f7-889825e7c610)
![Captura de Tela (97)](https://github.com/user-attachments/assets/d7025c52-46a4-4e33-980a-2362675d3568)
![Captura de Tela (99)](https://github.com/user-attachments/assets/f6228775-520d-497d-9acf-1aa4ee8f76e4)
