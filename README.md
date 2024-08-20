<h1 align="center">
  <br/>
  AI Agent Studies
</h1>

<p align="center">
  <img alt="GitHub language count" src="https://img.shields.io/github/languages/count/LucasPereiraMiranda/ai-agent-studies">

  <img alt="Repository size" src="https://img.shields.io/github/repo-size/LucasPereiraMiranda/ai-agent-studies">
  
  <a href="https://github.com/LucasPereiraMiranda/ai-agent-studies/commits/master">
    <img alt="GitHub last commit" src="https://img.shields.io/github/last-commit/LucasPereiraMiranda/ai-agent-studies">
  </a>

  <a href="https://github.com/LucasPereiraMiranda/ai-agent-studies/issues">
    <img alt="Repository issues" src="https://img.shields.io/github/issues/LucasPereiraMiranda/ai-agent-studies">
  </a>
</p>

<br>

# Introduction

Project to study AI agent ecossystem using flowise, langfuse, typeboot, n8n, pgvector & portainer

## How to run

## Create volumes

We can create our volumes:

```bash
docker volume create flowise_data
docker volume create postgres_data
docker volume create pgadmin_data
docker volume create redis_data
docker volume create portainer_data
docker volume create n8n_data
```

## Create network

We can create our network:

```bash
docker network create network
```

## In other terminal, create databases

- List containers:

```bash
docker ps
```

We can collect postgres container hash

- Enter in container:

```bash
docker exec -it {hash postgres} psql -U postgres
```

- Create databases:
```sql
CREATE DATABASE flowise;
CREATE DATABASE langfuse;
CREATE DATABASE n8n;
```


## Execution preview

**Flowise** local: [http://localhost:3000/](http://localhost:3000/)
![Flowise](./.github/img/flowise.png)  

**n8n** local: [http://localhost:5678/](http://localhost:5678/)
![n8n](./.github/img/n8n.png)  


**pg admin** local: [http://localhost:3007/](http://localhost:3007/)
![pg admin](./.github/img/pg-admin.png)  


**Postgres** local: [http://localhost:3007/](http://localhost:3007/)
![Postgres](./.github/img/postgres.png)  
