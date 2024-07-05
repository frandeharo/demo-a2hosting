

# DEMO

Proyecto de básico para explicar subida a servidor web A2Hosting.

Sólo cuenta con una página home que mostrará el valor de la variable DEBUG del settings y configurado con base de datos SQLite.


## Instalción

Mediante el gestor de paquetes pip realizar la instalación de los paquetes necesarios

```bash
    pip install -r requirements.txt
```

## Crear usuario adminisrador

```bash
    python manage.py createsuperuser
```

## Configuarar variables de entorno


Copiamos el fichero env.TEMPLATE a .env y configuramos las variables

```
    cp env.TEMPLATE .env
```


## Arrancamos

```bash
    python manage.py runserver
```









