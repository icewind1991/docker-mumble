# docker-murmur

Minimal docker image for murmur built on alpine

## Usage

docker run -d -p 64738:64738 -p 64738:64738/udp icewind1991/murmur

## Options

The following options can be set as environment variables

- `SERVER_PASSWORD`
- `MAX_USERS`
- `SERVER_TEXT`
- `REGISTER_NAME`
- `BANDWIDTH`
- `SUPW`

## Persistance

The sqlite database containing the server state is located at `/data/db.sqlite`

