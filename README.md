Documentação geral do projeto

Banco de dados

usamos um postgress as variaveis estão sendo definidas em um arquivo .env que não serão passados para o repositorio mas pode ser configurado posteriormente

```
# Informações do banco de dados

# Nome do Banco de dados
POSTGRES_DB=nome do seu banco

# Usuário do banco de dados
POSTGRES_USER=usuario do seu banco

# Senha do banco de dados
POSTGRES_PASSWORD=senha doi seu banco

# Porta para exposição do banco de dados
POSTGRES_PORT=porta exposta do seu banco

# Versão do banco de dados
POSTGRES_VERSION=varsão do seu banco de dados

# Caminho para armazenamento dos dados do banco de dados
POSTGRES_DATA="/var/lib/postgresql/data" valor padrão
```
