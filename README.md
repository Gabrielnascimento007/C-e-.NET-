# 🧠 ProductClientHub

Este repositório contém a estrutura de um sistema backend dividido em múltiplos projetos, com foco em organização, manutenibilidade e escalabilidade. O projeto principal expõe uma API RESTful, e os projetos auxiliares separam responsabilidades como comunicação entre camadas e tratamento de exceções.

---

## 📦 Estrutura do Projeto

### 1. **ProductClientHub.API**
Camada principal da aplicação, responsável por expor os endpoints da API. Organizado com foco em boas práticas como separação de responsabilidades e injeção de dependências.

#### Estrutura:
- `Controllers/` – Contém os controladores da API.
- `Entities/` – Representa os modelos de domínio.
- `Filters/` – Filtros para tratamento de exceções, validações e autenticações.
- `Infrastructure/` – Contém classes de infraestrutura como contexto de banco de dados, serviços externos, configurações, etc.
- `UseCases/` – Camada responsável pela lógica de negócio (aplicação).
- `Properties/`, `Program.cs`, `appsettings.json` – Configurações do projeto.

---

### 2. **ProductClientHub.Communication**
Responsável pela definição dos modelos de comunicação entre as camadas do sistema.

#### Estrutura:
- `Requests/` – Modelos para dados recebidos via API.
- `Responses/` – Modelos para dados retornados via API.

---

### 3. **ProductClientHub.Exceptions**
Contém a estrutura para centralizar e padronizar o tratamento de exceções do sistema.

#### Estrutura:
- `ExceptionsBase/` – Classes base para erros e exceções personalizadas.
- 
----------------------------------------------------------------------------------------------------------------

📌 Tecnologias Utilizadas
ASP.NET Core
C#
Entity Framework Core
RESTful APIs
Clean Architecture (estrutura modular por responsabilidade)

✨ Objetivo
O projeto visa demonstrar uma arquitetura modular, com separação de camadas e princípios de Clean Code aplicados, ideal para sistemas escaláveis e com manutenibilidade a longo prazo.

📫 Contato
Em caso de dúvidas ou sugestões, entre em contato via [email ou GitHub].
