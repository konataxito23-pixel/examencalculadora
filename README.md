Este proyecto es un servicio web simple que permite realizar operaciones matemáticas básicas (suma, resta, multiplicación y división) mediante una interfaz web.

## 🚀 Cómo ejecutar

###Construir la imagen Docker
```bash
sudo docker build -t calculadora-telematica .
```

### Ejecutar el contenedor
```bash
sudo docker run -d -p 80:5000 calculadora-telematica
```

###  Acceder a la aplicación
En el navegador:
```
http://<IP-PUBLICA-DE-TU-EC2>/
```

## 🐍 Tecnologías
- Python 3
- Flask
- Docker
- HTML + CSS
