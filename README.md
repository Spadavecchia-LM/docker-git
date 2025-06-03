# docker-git
Trabajo practico para la materia de ingenieria del software

# Mi sitio en Nginx + Docker

Este es un proyecto simple que sirve una página HTML estática usando la imagen oficial de Nginx en Docker.

## 🚀 Cómo usar

### 1. Clonar el repositorio

```bash
git clone https://github.com/Spadavecchia-LM/docker-git.git
cd SPADAVECCHIALEONARDO

### 3. Construir la imagen Docker

# revisar que docker desktop este abierto y funcionando

```bash
docker build -t nginx-template .
```
### 4. Levantar el contenedor con Docker

```bash
docker run -d -p 8080:80 --name spadavecchia nginx-template
```

Esto iniciará un contenedor en segundo plano y expondrá el sitio en `http://localhost:8080`

Abrí tu navegador y visitá:

```
http://localhost:8080
```

Deberías ver el sitio con el mensaje "¡Hola mundo desde Nginx!" y un subtitulo con mi nombre y apellido "leonardo spadavecchia"

### comandos utiles

## para apagar el contendeor 

```bash
docker stop spadavecchia
```

para prender el contenedor (si la imagen ya fue creada)

```bash
docker start spadavecchia
```