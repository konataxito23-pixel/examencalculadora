# 🧮 Calculadora Telemática con Flask y Docker

Este proyecto es un servicio web simple que permite realizar operaciones matemáticas básicas (suma, resta, multiplicación y división) mediante una interfaz web.

## 🚀 Cómo ejecutar

### 1️⃣ Construir la imagen Docker
```bash
sudo docker build -t calculadora-telematica .
```

### 2️⃣ Ejecutar el contenedor
```bash
sudo docker run -d -p 80:5000 calculadora-telematica
```

### 3️⃣ Acceder a la aplicación
En el navegador:
```
http://<IP-PUBLICA-DE-TU-EC2>/
```

## 🐍 Tecnologías
- Python 3
- Flask
- Docker
- HTML + CSS
