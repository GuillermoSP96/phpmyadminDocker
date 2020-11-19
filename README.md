# phpmyadminDocker
Servidor SQL con Docker y Phpmyadmin
Para poder tener este servidor es necesario tener instalado docker y docker-compose

Ubuntu
sudo apt update
sudo apt install docker docker-compose -y

Para ejecutar este docker-compose debes estar en el mismo directorio del docker-compose y ejecutar

sudo docker-compose up -d

Ahora podrás acceder a tu navegador
tu_ip:8080

O si lo prefieres puedes usar un cliente SQL. Ejemplo DBeaver.
En el cliente debes colocar la ip de tu maquina donde tengas ejecutando el contenedor y el puerto es el 6603
El usuario y contraseña lo colocas en el archivo docker-compose.yaml

por defecto puedes entrar con
user: root
password: helloworld
