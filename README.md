# EasyStock-API
API REST para controle de estoque de pequenos negócios. Desenvolvida em C# utilizando boas práticas de código.

## Tecnologias 🚀
- .NET 9.0.104
- PostgreSQL
- Entity Framework Core
- Docker

## Funcionalidade (MVP) 🎯
- Cadastro de Produtos
- Consulta de Produtos
- Registro de Entrada e Saída de Estoque
- Consulta de Saldo Atual

## Estrutura do Projeto 📄
- **API:** Camnada de apresentação
- **Application:** Casso de uso e regreas de negócio
- **Domain:** Entidades e regras de domínio
- **Infra:** Acesso a dados e repositórios
- **Tests:** Testes unitário e de integração

## Roadmap 🚧
- Criar endpoints CRUD de Produto
- Implementar controle de entrada e saída
- Adicionar histórico de movimentação
- Implementar autenticação JWT (fase 2)
- Geração de relatórios (fase 2)

## Padrão de Commits 📝
Segue o padrão Conventional Commits:
```
feat: Adicionado cadastro de produto
fix: Corrigido bug na consulta de estoque
docs: Atualizado README
refactor: Refatorando serviço de movimentação
test: Adicionado teste unitário
```

## Docker 🐳
Configuração do banco de dados PostgreSQL será adicionada via ´docker-compose.yml´.
