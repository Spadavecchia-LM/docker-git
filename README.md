# 🐳 Docker + Git

> Trabajo práctico para la materia **Ingeniería del Software**

## 📋 Descripción

Este proyecto implementa un sitio web estático utilizando **Nginx** dentro de un contenedor **Docker**. Se sirve una página HTML simple con un mensaje personalizado.

## 🛠️ Tecnologías utilizadas

- **Docker** – Containerización
- **Nginx** – Servidor web
- **HTML** – Página estática
- **Git** – Control de versiones

---

## 🚀 Inicio rápido

### ✅ Prerrequisitos

- **Docker Desktop** instalado y ejecutándose
- **Git** instalado

---

### 1️⃣ Clonar el repositorio

```bash
git clone https://github.com/Spadavecchia-LM/docker-git.git
cd docker-git
```

### 2️⃣ Construir la imagen Docker

```bash
docker build -t nginx-template .
```

### 3️⃣ Ejecutar el contenedor

```bash
docker run -d -p 8080:80 --name spadavecchia nginx-template
```

### 4️⃣ Verificar el funcionamiento

Abrí tu navegador y visitá:

[http://localhost:8080](http://localhost:8080)

Deberías ver el mensaje:

> "¡Hola mundo desde Nginx!"  
> Subtítulo: **Leonardo Spadavecchia**

---

## 🔧 Comandos útiles

| Acción                  | Comando                                |
|-------------------------|----------------------------------------|
| Apagar contenedor       | `docker stop spadavecchia`            |
| Levantar contenedor     | `docker start spadavecchia`           |
| Eliminar contenedor     | `docker rm spadavecchia`              |
| Reiniciar contenedor    | `docker restart spadavecchia`         |

---

## 👨‍💻 Autor

**Leonardo Spadavecchia**  
Trabajo práctico para la materia **Ingeniería del Software**
