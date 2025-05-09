# AUTOMATIZACIÓN DE PRUEBAS FUNCIONALIDADES AMAZON ITALIA WEB 
### Robot Framework + Python
Gestion de compras online

## Descripcion
Este proyecto ejecuta una serie de casos de prueba para validar funcionalidades de búsqueda en la página web de Amazon Italia. El objetivo es simular el comportamiento del usuario final al buscar artículos mediante:
La barra de búsqueda general
La navegación por categorías a través del menú tipo hamburguesa

El principal propósito de este proyecto es adquirir experiencia práctica con el framework Robot Framework y fortalecer las bases de la automatización de pruebas.

## Caracteristicas
Búsqueda de productos mediante la barra principal
Búsqueda de productos por categoría desde el menú

Nota: El proyecto se encuentra en desarrollo. Esta sección será actualizada con nuevas funcionalidades.

## Tecnologias utilizadas

Python
SeleniumLibrary
Robot Framework
PIP

* [Python](https://www.python.org/downloads/)
* [Selenium](https://robotframework.org/SeleniumLibrary/)
* [Robot Framework](https://robotframework.org)
* [PIP](https://www.groovypost.com/howto/install-pip-on-a-mac/)

## Requisitos 
Visual Studio Code instalado
Python instalado
Robot Framework instalado
PIP actualizado
Casos de prueba definidos en archivos .robot

## Primeros pasos

Siga los siguientes pasos para configurar el entorno y ejecutar los casos de prueba en su máquina local:
1. Abrir la terminal y ejecutar:
python -m pip install --upgrade pip
pip install robotframework o pip3 install robotframework 
pip3 install robotframework-seleniumlibrary
pip3 install robotframework-selenium2library 

2. Clonar o descargar este repositorio en su equipo.

## Ejecucion de casos de prueba

1. Abrir Visual Studio Code.
2. Ir a la terminal (Terminal > New Terminal).
3. Navegar al directorio donde están ubicados los archivos .robot, usando:cd ruta/al/directorio 
(Identificar la ubicacion/ruta/directorio de los archivos donde se encuentran los casos de prueba)
4. Ejecutar un caso de prueba con: robot TC1.robot,reemplace TC1.robot con el nombre real del archivo de prueba.
5. El informe HTML generado estará disponible en:```"C:\Users\luzadrianas\OneDrive - DS Group S.p.A\Desktop\ATM\Netflix_RobotFramework-main\Netflix_RobotFramework-main\Netflix\specs\report.html"``

### Reporte de ejecucion 

Robot Framework genera un reporte detallado donde podrá ver:

Casos ejecutados
Resultados (éxito o fallo)
Mensajes de error y logs
Estadísticas por test suite y por test case

