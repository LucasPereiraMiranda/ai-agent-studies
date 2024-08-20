# Create volumes

docker volume create flowise_data
docker volume create postgrespgvector
docker volume create pgadmin_data
docker volume create redis_data
docker volume create portainer_data

# Create network

docker network create minha_rede