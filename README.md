Este proyecto es un servicio web simple que permite realizar operaciones matemáticas básicas (suma, resta, multiplicación y división) mediante una interfaz web.

# 1) Clonar repo
git clone https://github.com/konataxito23-pixel/examencalculadora.git
cd examencalculadora

# 2) Construir la imagen (en la instancia Linux)
sudo docker build -t calculadora-telematica .

# 3) Ejecutar el contenedor (puerto 8080 recomendado)
sudo docker run -d -p 8080:5000 --name calculadora calculadora-telematica

# 4) Verificar
sudo docker ps
curl http://localhost:5000/status    # si implementas status en main.py

# Acceder desde el navegador:
# http://<IP-PUBLICA-DE-LA-EC2>:8080/
