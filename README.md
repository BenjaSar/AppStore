![header](doc/header.png)

# CONTROL ADMINISTRATIVO DE PRODUCTOS

---

Authors:

- FS - 2021

## TABLA DE CONTENIDO

---

1. [Descripción del problema](#Descripción)
2. [Organización del proyecto](#Organizacion)
3. [Como ejecutar la aplicacion](#eAplicacion)
4. [Licencia](#Licencia)
5. [Agradecimientos](#Agradecimientos)

## DESCRIPCIÓN DEL PROBLEMA

---

Desarrollo de una aplicacion de venta de producto donde es posible editar, cargar y eliminar registros. El despliegue fue realizado sobre la plataforma Heroku

## ORGANIZACION DEL PROYECTO

---

El proyecto se encuentra conformado por la siguiente estructura de directorios y archivos (los más relevantes a la aplicación):

```
.
├── backend
│   ├── AplicacionCiclo3
│   │   ├── admin.py
│   │   ├── apps.py
│   │   ├── __init__.py
│   │   ├── migrations
│   │   │   ├── 0001_initial.py
│   │   │   └── __init__.py
│   │   ├── models
│   │   │   ├── account.py
│   │   │   ├── __init__.py
│   │   │   └── producto.py
│   │   ├── serializers
│   │   │   ├── __init__.py
│   │   │   └── productoSerializers.py
│   │   ├── tests.py
│   │   └── views
│   │       ├── __init__.py
│   │       ├── userCreate.view
│   │       └── productoView.py
│   ├── Ciclo3Proyecto
│   │   ├── asgi.py
│   │   ├── __init__.py
│   │   ├── settings.py
│   │   ├── urls.py
│   │   └── wsgi.py
│   ├── manage.py
│   ├── Procfile
│   └── requirements.txt
├── README.md
└── tiendac_fe
    ├── babel.config.js
    ├── package.json
    ├── package-lock.json
    ├── README.md
    ├── server.js
    └── src
        ├── App.vue
        ├── assets
        │   └── logo.png
        ├── components
        │   ├── Home.vue
        │   ├── LogIn.vue
        │   ├── Productos.vue
        │   ├── readProductos.vue
        │   ├── rudProducto.vue
        │   └── SignUp.vue
        ├── main.js
        └── router.js

```

## COMO EJECUTAR LA APLICACION

Para ver la aplicacion visitar el siguiente (link)[https://app-computer-seller-fe.herokuapp.com/#/user/]:

## LICENCIA

Este proyecto se encuentra publicado bajo la licencia MIT. En [este enlace](https://opensource.org/licenses/MIT) podrá encontrar más información sobre la misma.
![footer](doc/footer.png)



