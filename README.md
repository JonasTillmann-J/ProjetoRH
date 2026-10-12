# Nome do projeto Docker Compose
PROJECT_NAME=Projeto_Sistema_RH

# Nome do contêiner PostgreSQL
CONTAINER_NAME_POSTGRES=postgres_database_container

# Nome da rede backend
NETWORK_NAME_BACKEND=backend_network

# Nome da rede frontend
NETWORK_NAME_FRONTEND=frontend_network

# Nome do volume persistente do PostgreSQL
VOLUME_NAME_POSTGRES=postgres_data_volume

# Nome do banco de dados
POSTGRES_DB=BD_RH_PROD

# Usuário do banco de dados
POSTGRES_USER=USER_RH_PROD

# Senha do banco de dados
POSTGRES_PASSWORD=SUBSTITUA_POR_UMA_SENHA_FORTE

# Porta do PostgreSQL no host
POSTGRES_PORT=5432

# Versão do PostgreSQL
POSTGRES_VERSION=17

# Diretório dos dados dentro do contêiner
POSTGRES_DATA=/var/lib/postgresql/data