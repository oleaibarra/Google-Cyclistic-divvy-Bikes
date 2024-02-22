# Análisis de Datos de Usuarios de Cyclistic con Python y Pandas

## Resumen del Proyecto

Este proyecto se enfoca en el análisis de datos de viajes en bicicleta realizados durante el año 2022, utilizando los registros proporcionados por Divvy, el sistema de bicicletas compartidas de la ciudad de Chicago. El objetivo principal es identificar diferencias entre usuarios casuales y usuarios con membresía de Cyclistic, una empresa ficticia, para informar estrategias de negocio destinadas a convertir usuarios casuales en miembros. Dado el volumen de datos (~2GB), y sin acceso a herramientas de cloud computing como Google Cloud Platform, este análisis se llevó a cabo localmente utilizando Python y Pandas en Jupyter Lab.

## Justificación Técnica

La decisión de usar Python y Pandas para este proyecto se basó en varias consideraciones clave:
- **Volumen de Datos:** El conjunto de datos total es aproximadamente de 2GB, lo que representa un desafío para herramientas basadas en la nube sin acceso a un periodo de prueba o subscripciones pagas.
- **Flexibilidad de Análisis:** Python, combinado con la biblioteca Pandas, ofrece una solución robusta y flexible para el manejo, limpieza, y análisis de grandes conjuntos de datos.
- **Accesibilidad:** Al trabajar localmente en Jupyter Lab, se elimina la dependencia de recursos en la nube, permitiendo un análisis más ágil y personalizado.

## Estructura del Repositorio

El análisis se divide en tres partes principales, reflejando una progresión lógica del proyecto:
- **Parte I:** Enfocada en la adquisición, tratamiento, y limpieza de los archivos de datos, estableciendo una base sólida para el análisis.
- **Parte II:** Comienza el análisis exploratorio de datos, identificando patrones preliminares y diferencias clave entre los dos tipos de usuarios.
- **Parte III:** (Por concluir) Finalizará el análisis detallado y presentará las conclusiones finales junto con recomendaciones estratégicas.

Además, se incluirá un resumen ejecutivo que destaque las conclusiones más importantes y las implicaciones para la estrategia de negocio de Cyclistic.

## Fuentes de Datos

Los datos utilizados en este proyecto son cortesía de Divvy, disponible públicamente en 'https://divvy-tripdata.s3.amazonaws.com/index.html'. Estos registros detallan los viajes realizados por los usuarios en Chicago, IL, durante el año 2022, y están divididos en archivos mensuales en formato ZIP.

## Objetivo del Proyecto

El análisis busca proporcionar insights valiosos sobre el comportamiento y preferencias de los usuarios casuales en comparación con los usuarios con membresía. La información obtenida servirá como una herramienta clave en el diseño de estrategias efectivas para incrementar la conversión de usuarios casuales a miembros, contribuyendo al crecimiento y éxito a largo plazo de Cyclistic.
