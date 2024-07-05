

# DEMO

Proyecto de básico para explicar subida a servidor web A2Hosting.

Sólo cuenta con una página home que mostrará el valor de la variable DEBUG del settings


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

Solo se ha definido una variable de entorno como prueba para controlar el modo debug

Copiamos el fichero env.TEMPLATE a .env

```
    cp env.TEMPLATE .env
```










