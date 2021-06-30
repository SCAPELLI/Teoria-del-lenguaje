# Trabajo Practico TDL 

### Integrantes
    - Hugo Larrea
    - Diego Balestieri
    - Sebita :3


### Inicializar variables de entorno

Para las variables de se usa figaro
Se creara un archivo config/application.yml, dentro de el
se debera crear la variable de entoro de TMDB_API_KEY

```
TMDB_API_KEY: <API_KEY>
```

Dentro del docker correr 
```
./init_and_config.sh
```

### Docker 

Para ejecutar la aplicacion con Docker seguir los siguientes pasos: 

```
./docker.sh
```
Una vez dentro del contenedor ejecutar: 

```
./init_and_config.sh
```

De tener problemas en correr el shell script, salir del container y ejecutar: 

```
sudo chmod +x init_and_config.sh
```
Correr nuevamente ambos comandos.
