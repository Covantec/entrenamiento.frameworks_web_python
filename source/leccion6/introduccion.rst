.. _python_flash_introduccion:

Introducción
============

`Flask <http://flask.pocoo.org/>`_ es un framework minimalista 
escrito en Python que permite crear aplicaciones web rápidamente 
y con un mínimo número de líneas de código. Está basado en la 
especificación `WSGI <https://wsgi.readthedocs.io/en/latest/>`_ de 
`Werkzeug <https://www.palletsprojects.com/p/werkzeug/>`_ y el motor 
de plantillas `Jinja2 <https://www.palletsprojects.com/p/jinja/>`_ 
con licencia BSD.

.. comments:

	.. figure:: ../_static/flask-logo.png
	  :class: image-inline
	  :alt: Flash framework
	  :align: center

	  Flash framework

.. figure:: https://raw.githubusercontent.com/Covantec/entrenamiento.frameworks_web_python/master/source/_static/flask-logo.png
  :class: image-inline
  :alt: Flash framework
  :align: center

  Flash framework

Características
---------------

- Contiene servidor de desarrollo y depurador.

- Soporte integrado para pruebas unitarias.

- Envío de request RESTful.

- Utiliza plantillas de Jinja2.

- Soporte para cookies seguras (sesiones del lado del cliente).

- 100% compatible con WSGI 1.0.

- Basado en Unicode.

- Amplia documentación.

- Compatibilidad con Google App Engine.

- Extensiones disponibles para mejorar las características deseadas.


Model View Controller
---------------------

Del Ingles Model View Controller - MVC, el Modelo-vista-controlador,
es un patrón de arquitectura de software, que separa los datos y la 
lógica de negocio de una aplicación de su representación y el módulo 
encargado de gestionar los eventos y las comunicaciones. Para ello MVC 
propone la construcción de tres componentes distintos que son el modelo, 
la vista y el controlador, es decir, por un lado define componentes para 
la representación de la información, y por otro lado para la interacción 
del usuario. 

Este patrón de arquitectura de software se basa en las ideas 
de reutilización de código y la separación de conceptos, características 
que buscan facilitar la tarea de desarrollo de aplicaciones y su posterior 
mantenimiento.

El patrón de diseño MVC es soportado en Flask se divide en tres capas: 

Capa Modelo
^^^^^^^^^^^

- `Tutorial SQLAlchemy (Capa modelo) <https://docs.sqlalchemy.org/en/latest/orm/tutorial.html>`_.

- `Select, Insert, Delete - Flask-SQLAlchemy) <http://flask-sqlalchemy.pocoo.org/2.3/queries/>`_.

Capa Vista
^^^^^^^^^^

- `Sistema de plantillas Jinja2 (Capa vista) <http://jinja.pocoo.org/docs/2.10/templates/>`_.

Capa Controlador
^^^^^^^^^^^^^^^^

- `Documentación Flask (Capa Controlador) <http://flask.pocoo.org/>`_.
