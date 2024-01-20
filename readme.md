# Servidor de Live Streaming com NGINX

Servidor para live streaming simples, somente o essencial para você transmitir e assistir

## Requisitos 
- Docker 
- [OBS](https://obsproject.com/pt-br/download)

## Tecnologias
- Docker compose
- NGINX

## Protocolos 
- RTMP (Real Time Message Protocol)
- HLS (HTTP Live Streaming)

## Como executar

Suba os containers utilizando docker compose
```
docker-compose up
```

Abra o [OBS](https://obsproject.com/pt-br/download) > Configurações > Transmissão > Servidor
```
rtmp://localhost/live
```
Clique em ok e depois clique em **Iniciar transmissão**

## Como assistir a transmissão
No navegador acesse a pagina
```
http://localhost
```