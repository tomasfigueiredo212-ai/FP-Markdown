# FP-Markdown
iShopping — Sistema de Gestão de Compras e Orçamentos
O iShopping é uma aplicação desktop desenvolvida em Windows Forms (.NET 10) que permite gerir artigos, categorias, orçamentos mensais e compras de forma simples e eficiente.
Utiliza C# e Entity Framework Core, seguindo uma arquitetura MVC adaptada a WinForms, garantindo organização e separação clara entre dados, lógica e interface.

Projeto_DA/
├── Models/                # Entidades (EF Core)
├── Controllers/           # Lógica de negócio
├── Views/                 # Formulários WinForms
├── Data/                  # DbContext
├── Migrations/            # Migrações EF Core
├── MainForm.cs            # Dashboard principal
├── SessionManager.cs      # Gestão de sessão
├── PasswordHasher.cs      # Hashing seguro
└── Program.cs             # Entrada da aplicação

Modelo de Dados (Resumo)

User — autenticação e controlo de permissões
TipoArtigo — categorias de artigos
Artigo — artigos associados a categorias
Orcamento — orçamentos mensais
Compra — compras criadas e fechadas
ArtigoComprado — itens dentro de cada compra


🚀 Como Executar
Instalar:
Clonar o repositório:
Código
https://github.com/tomasfigueiredo212-ai/
