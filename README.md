# Ambiente de robótica aérea

Ambiente para los ejercicios de robotica aérea. 
Todos los derechos reservados. Juan Irving Vasquez. 2019 - 2021.

## Instrucciones de instalación (Linux)

Realiza las siguientes instrucciones en tu máquina.

- Descarga [conda][conda] e instálalo.
- Clona este repositorio a tu máquina. Si utilizas git ejecuta el siguiente comando, de lo contrario busca el botón descargar.
```sh
git clone https://github.com/irvingvasquez/ra_environment.git
```
- En la carpeta del proyecto clonado encontrarás un archivo .yml con la configuración necesaria. Ejecuta el siguiente comando para crear el ambiente (este paso tomará varios minutos antes de completarse por todos los paquetes que se necesitan instalar).
```sh
$ conda env create -f environment.yml
```
- Para verficar que se instaló el ambiente puedes listar todos los ambientes con el comando:
```sh
$ conda info --envs
```
- Deberá aparecer el nombre *ra_env* entre los ambientes listados.
- Una vez instalado en ambiente es necesario activarlo cada vez que abras una terminal:
```sh
$ source activate ra_env
```

[conda]: <https://conda.io/docs/user-guide/install/index.html> 
