# Hackathon-HackTheOcean-launchX
Repositorio de entrega para el Hackathon llamado "Hack the Ocean" del curso de LaunchX - 2022

## Integrantes
**Nombre del equipo**: La obra Negra (En honor al "_mai_" jaja).
1. Francisco Sánchez : launchx11250@innovaccion.mx
2. Aldair Montaño : launchx05226@innovaccion.mx
3. Francisco Javier Rodríguez : launchx08765@innovaccion.mx
4. Daniel Zavala Velázquez : launchx00187@innovaccion.mx

## Proyecto Hack The Ocean

**Tópico seleccionado**: Pesca ilegal en México como parte de la rama del tópico de sobrepesca. <br>
**Problema**: La pesca ilegal en México a nivel nacional, con datos obtenidos de los años 2015-2020, en donde varias especies (no tan solo en peligro de extinción) se encuentran entre las principales pescadas de manera explotada. <br>
**Solución**: Presentar información estadística de las bases de datos sobre pesca ilegal y especies pescadas de manera ilícita en el país. <br>

## Desarrollo

En primer lugar se conformó el equipo y se analizó las fortalezas de cada uno para establecer las fortalezas de cada quién, parte de los pasos que se siguieron en el desarrollo de este proyecto pueden observarse en la siguiente imagen.

![Diagrama de actividades](https://github.com/zuturito/Hackathon-HackTheOcean-launchX/blob/main/Diagramas%20y%20dise%C3%B1o/diagrama%20de%20soluci%C3%B3n.png)

## Tecnología

Una página web informativa con las siguientes características:
- NodeJS como conexión con una API a los datos obtenidos (_backend_).
- HTML5, CSS (_responsive_), Javascript para el entorno del _frontend_.
- _Deployment_ a través de microservicios montados en la nube de Azure.

![Despliegue de tecnología](https://github.com/zuturito/Hackathon-HackTheOcean-launchX/blob/main/Diagramas%20y%20dise%C3%B1o/despliegue%20de%20soluci%C3%B3n.png)

## Desarrollo

La solución se llevó mediante el desarrollo de una metodología ágil, la cuál cuenta con etapas que permiten llevar un orden en el proyecto y un ciclo continuo de mejora con cambios sobre la marcha.
Se siguió un proceso como el siguiente:
- Análisis: Se analizaron los tópicos y se buscaron Bases de datos relacionados al tema elegido (pesca ilegal). Las bases de datos utilizadas para el desarrollo de este proyecto se tomaron del siguiente enlace: https://pescandodatos.causanatura.org/permisos.
- Diseño: Se realizaron prototipos y maquetación de la página para que el equipo de trabajo estuviese de acuerdo. Enlace: https://github.com/zuturito/Hackathon-HackTheOcean-launchX/blob/main/Diagramas%20y%20dise%C3%B1o/Page.png 
- Implementación: Se distribuyeron las actividades y se planteó el desarrollo de backend con nodeJS y frontend con HTML,CSS y Javascript.
- Pruebas: Una vez terminado cada módulo se realizaron los cambios suficientes (en caso de existir) e integración con la rama principal.
- Resultado: Una vez integrado el proyecto se levantaron los servicios en la Nube de Azure.

## _Deployment_

Para el despliegue de nuestra página informativa se decidió ocupar la nube de Azure para generar la integración/desarrollo continuo y ver los cambios sobre la marcha en produccion sin destruir la rama principal.
Los servicios se levantaron para: 
- Una API montada en NodeJS con los datos obtenidos del excel que se descargó del sitio web previamente mencionado. Enlace: https://api-especies.azurewebsites.net
- El despligue de la página web prinicipal. Enlace:https://pescailegal-mexico.azurewebsites.net 

![Azureservices](https://github.com/zuturito/Hackathon-HackTheOcean-launchX/blob/main/Screenshots/Azure.jpg)

## Resultados

La página presenta información simple de comprender sobre el tema y algunas estadísticas encontradas en las bases de datos utilizadas, aunque si se desea saber un poco más a detalle se recomienda navegar en el sitio web de donde se obtuvieron los datos.
El resultado final del proyecto elaborado es el siguiente. También se muestran algunas capturas de cómo se aprecia la página en modo responsivo.
La página web puede visitarse en el siguiente enlace: https://pescailegal-mexico.azurewebsites.net/ 

![Página](https://github.com/zuturito/Hackathon-HackTheOcean-launchX/blob/main/Screenshots/1.jpg)
![Página2](https://github.com/zuturito/Hackathon-HackTheOcean-launchX/blob/main/Screenshots/2.jpg)
![Página3](https://github.com/zuturito/Hackathon-HackTheOcean-launchX/blob/main/Screenshots/3.jpg)
![Página4](https://github.com/zuturito/Hackathon-HackTheOcean-launchX/blob/main/Screenshots/4.jpg)
![Página5](https://github.com/zuturito/Hackathon-HackTheOcean-launchX/blob/main/Screenshots/5.jpg)
