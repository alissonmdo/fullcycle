# Full Cycle Docker Challenge - Go

## Table of Contents

- [English](#english)
  - [Requirements](#requirements-english)
  - [How to Run](#how-to-run-english)
  - [Docker Hub Image](#docker-hub-image-english)
- [Português](#português)
  - [Requisitos](#requisitos-português)
  - [Como executar](#como-executar-português)
  - [Imagem Docker Hub](#imagem-docker-hub-português)

## English <a name="english"></a>

Welcome to my solution for the Docker challenge in the Full Cycle course. This challenge involved using Docker and Go to create a Docker image that is less than 2MB in size. 

The image prints "Full Cycle Rocks!!" when run.

### Requirements <a name="requirements-english"></a>:
- Docker
- Go

### How to Run <a name="how-to-run-english"></a>:
1. Clone this repository to your local machine.
2. Navigate to the Docker challenge directory.
3. Build the Docker image using the following command: 

```sh
docker build -t fullcycle .
```
4. Run the Docker image using the following command:

```sh
docker run --rm fullcycle
```
You should see the message "Full Cycle Rocks!!" printed in your terminal.

### Docker Hub Image <a name="docker-hub-image-english"></a>
You can also download and run my image directly from Docker Hub:

```sh
docker run --rm alissonmdo/fullcycle
```
This command will download (if not already downloaded) and run my Docker image from Docker Hub.

Thank you for checking out my solution!

## Português <a name="português"></a>

Bem-vindo à minha solução para o desafio Docker do curso Full Cycle. Este desafio envolveu o uso do Docker e Go para criar uma imagem Docker que tenha menos de 2MB.

A imagem imprime "Full Cycle Rocks!!" quando executada.

### Requisitos <a name="requisitos-português"></a>:
- Docker
- Go

### Como executar <a name="como-executar-português"></a>:
1. Clone este repositório para a sua máquina local.
2. Navegue até o diretório do desafio Docker.
3. Construa a imagem Docker usando o seguinte comando:

```sh
docker build -t fullcycle .
```
4. Execute a imagem Docker usando o seguinte comando:

```sh
docker run --rm fullcycle
```
Você deverá ver a mensagem "Full Cycle Rocks!!" impressa no seu terminal.

### Imagem Docker Hub <a name="imagem-docker-hub-português"></a>
Você também pode baixar e executar minha imagem diretamente do Docker Hub:

```sh
docker run --rm alissonmdo/fullcycle
```
Este comando irá baixar (se ainda não baixado) e executar minha imagem Docker do Docker Hub.

Obrigado por conferir minha solução!
