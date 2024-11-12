# Trabajo Práctico: Monitoreo de Infraestructura con Datadog

## Objetivo
Evaluar la habilidad para configurar y analizar un entorno de monitoreo utilizando [**Datadog**](https://www.datadoghq.com/) en una infraestructura previamente desplegada en contenedores sobre AWS.

---

## 1. Configuración de Monitoreo en Datadog

Configurar Datadog para monitorear el desempeño de la infraestructura de WordPress en contenedores, incluyendo métricas del sistema operativo, de la aplicación y de la base de datos.

## 2. Creación de Dashboard

Diseñar un dashboard personalizado en Datadog que muestre métricas clave del sistema y de la aplicación, relevantes para evaluar el estado de la infraestructura y posibles puntos críticos.

## 3. Definición de Alertas

Configurar alertas que se activen ante eventos críticos relacionados con el rendimiento de la aplicación y de la base de datos, considerando métricas de CPU, memoria, tiempos de respuesta, y otros indicadores relevantes.

## 4. Análisis de Carga

Generar tráfico en la aplicación y observar el impacto en las métricas de rendimiento. Analizar cómo la infraestructura responde a distintos niveles de carga.

## 5. Informe

Elaborar un informe en formato markdown (.md) con:
- Análisis de las métricas observadas.
- Capturas del dashboard y de las alertas configuradas.
- Conclusiones sobre el estado de la infraestructura y su capacidad de respuesta ante la carga generada.

**Entrega:**

- **El informe debe presentarse a mas tardar el jueves 21/11/2024.**

- El informe debe presentarse en el archivo [Informe](./informe.md) dentro de este repositorio en la rama `main`.

- Debe incluir acceso al dashboard para revisión y evaluación de la configuración realizada.

**Defensa:**

La defensa del trabajo práctico consistirá en una presentación grupal donde cada participante deberá describir una parte de la solución implementada. 
A continuación, se realizará una evaluación individual sobre el trabajo práctico y temas generales de la cursada.


## Infraestructura a Monitorear

**Nota**: La implementación de la infraestructura no es parte de este trabajo práctico y no se requiere su detalle en el informe, salvo lo concerniente a la configuración de Datadog. 

Para desplegar la infraestructura, siga el procedimiento especificado en el documento [INFRA](./INFRA.md).

---

## Ejemplos de Herramientas para Simular Carga

**Nota:** La herramienta para generar carga no es parte del trabajo práctico, no se requiere su detalle en el informe, salvo lo que fuera necesario para describir los tests de carga aplicados.

A continuación, se presentan herramientas gratuitas que pueden ser utilizadas para simular carga en la aplicación de WordPress:

1. **Apache Benchmark (ab)**  
   - Herramienta básica que permite generar carga con solicitudes HTTP. Ideal para pruebas rápidas y de baja complejidad.

2. **wrk**  
   - Herramienta más avanzada que permite configurar hilos y conexiones concurrentes. Buena opción para pruebas de carga media a alta.

3. **K6**  
   - Herramienta de código abierto que permite escribir scripts de prueba en JavaScript. Ideal para simular diferentes escenarios de usuario.

4. **Locust**  
   - Herramienta en Python que permite crear scripts avanzados y simular usuarios con comportamientos específicos. Es útil para pruebas detalladas y personalizadas.

Cada una de estas herramientas ofrece diferentes capacidades y niveles de control sobre la carga generada. La elección depende de los objetivos de prueba y del nivel de personalización requerido. 

