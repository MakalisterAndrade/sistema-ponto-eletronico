# Sistema de Registro de Ponto Eletrônico

Uma solução simplificada de controle de ponto eletrônico, desenvolvida com LARAVEL, ideal para empresas em fase inicial ou para fins de aprendizado.

## 🔧 Principais Recursos

- Cadastro, edição e exclusão de funcionários
- Registro de entrada e saída de ponto
- Submissão de justificativas de ausência
- Ajuste manual de registros de ponto
- Aprovação e revisão de ajustes de ponto
- Geração de relatórios mensais de presença por funcionário, incluindo percentual de comparecimento, dias de falta e justificativas apresentadas.

## 🚀 Guia de Instalação

Este sistema foi desenvolvido com Laravel 7.0. Para configurá-lo, ajuste o arquivo `.env` para definir as conexões com o banco de dados MySQL.

No terminal, dentro do diretório do projeto, execute os seguintes comandos para instalar e configurar o sistema:

1. Instale as dependências do projeto:
   ```
   composer install
   ```

2. Gere a chave da aplicação:
   ```
   php artisan key:generate
   ```

3. Realize as migrações do banco de dados:
   ```
   php artisan migrate
   ```

### 💻 Demonstração

- **Funcionário**: Registro de entrada e saída de ponto, correção de registros e envio de justificativas.
- **Supervisor**: Gerenciamento de funcionários, aprovação ou rejeição de ajustes de ponto e geração de relatórios de presença e horas trabalhadas.

### Este projeto está sendo reescrito em PHP8, e sua versão online para testes está off no momento