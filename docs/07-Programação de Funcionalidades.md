## Descrição do Projeto

Este projeto consiste em um sistema financeiro desenvolvido em ASP.NET Core, utilizando MongoDB como banco de dados. O sistema permite que os usuários cadastrem suas despesas e receitas, gerenciem categorias e visualizem relatórios detalhados das transações cadastradas.

### Funcionalidades Implementadas

#### Cadastro de Usuários
- Permite que novos usuários se cadastrem no sistema financeiro.
- Página de cadastro de usuários: `cadastro_usuario.html`
- Script para validar e enviar dados do formulário de cadastro de usuários: `cadastro_usuario.js`
- Estrutura de dados: Tabela `usuarios` no banco de dados

#### Login de Usuários
- Permite que usuários cadastrados façam login no sistema financeiro.
- Página de login: `login.html`
- Script para validar e enviar dados do formulário de login: `login.js`
- Estrutura de dados: Tabela `usuarios` no banco de dados

#### Cadastro de Despesas
- Permite que os usuários cadastrem suas despesas no sistema financeiro.
- Página de cadastro de despesas: `cadastro_despesa.html`
- Script para validar e enviar dados do formulário de cadastro de despesas: `cadastro_despesa.js`
- Estrutura de dados: Tabela `despesas` no banco de dados

#### Cadastro de Receitas
- Permite que os usuários cadastrem suas receitas no sistema financeiro.
- Página de cadastro de receitas: `cadastro_receita.html`
- Script para validar e enviar dados do formulário de cadastro de receitas: `cadastro_receita.js`
- Estrutura de dados: Tabela `receitas` no banco de dados

#### Visualização de Relatórios de Transações
- Permite que os usuários visualizem relatórios detalhados de suas despesas e receitas cadastradas no sistema financeiro.
- Página de visualização de relatórios de transações: `relatorios_transacoes.html`
- Script para recuperar e exibir os dados das transações cadastradas: `relatorios_transacoes.js`
- Estrutura de dados: Tabelas `despesas` e `receitas` no banco de dados

#### Cadastro de Categorias
- Permite que os usuários cadastrem categorias para classificar suas transações.
- Controller para manipulação das categorias: `SistemaFinanceiroController.cs`
- Estrutura de dados: Tabela `categorias` no banco de dados

### Como Utilizar o Projeto

1. Clone este repositório para o seu ambiente de desenvolvimento.
2. Certifique-se de ter o ambiente de desenvolvimento ASP.NET Core configurado.
3. Configure as credenciais do banco de dados MongoDB no arquivo `appsettings.json`.
4. Execute o projeto e acesse as diferentes funcionalidades através das páginas HTML fornecidas.

### Considerações Finais

Este projeto serve como uma base para o desenvolvimento de um sistema financeiro mais completo e pode ser expandido com novas funcionalidades e melhorias de acordo com as necessidades do usuário. Certifique-se de revisar e ajustar o código e os artefatos de acordo com os requisitos específicos do seu projeto.
