# Moodle
Link para descaragar Moodle configurado
# aqui se descarga el moodle
https://drive.google.com/file/d/1DCn2dx7GbDDYHAgkBlFC-E8i6Kn33kfj/view?usp=sharing

# debemos agregar los permisos a la carperta con lo siguientes comandos antes de ejecutar docker compose.
sudo chown -R 1001:1001 ./mariadb-persistence
sudo chown -R daemon:root ./moodle-data
sudo chown -R daemon:root ./moodledata-data

# para agregar los permisos a la carpeta de mariadb-persistence
sudo chmod 777 mariadb-persistence
