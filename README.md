# Projeto com Docker e RabbitMQ

Este projeto utiliza Docker para configurar um ambiente com RabbitMQ, incluindo a interface de gerenciamento via browser.

### 💻 Pré-requisitos

- [x] Docker instalado
- [x] Docker Compose instalado

### Estrutura

- `docker-compose.yml`: Define a configuração do container RabbitMQ

### 🚀 Instalação / Configuração

Execute o comando para a criação do container:

```
docker-compose up -d
```

Para verificar se o container está em execução:

```
docker ps
```

### 🌐 Acessar interface de Gerencimento

```
http://localhost:15672
```

### 📝 Credenciais:

- Usuário: guest
- Senha: guest

### 🚪 Portas

- Porta 15672: Interface de gerenciamento
- Porta 5672: Porta padrão para conexões do RabbitMQ
