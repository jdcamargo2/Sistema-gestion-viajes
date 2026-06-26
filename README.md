## Sistema de Gestión de Viajes

Proyecto académico de análisis y modelado UML para un sistema de gestión de viajes.
El repositorio reúne los diagramas y artefactos desarrollados durante el proceso de análisis, diseño lógico, diseño de componentes y despliegue del sistema.

## Objetivo

Modelar los procesos principales de un sistema de gestión de viajes mediante diagramas UML, tarjetas CRC y vistas arquitectónicas que permitan representar el comportamiento, la estructura lógica, la organización de componentes y la distribución física del sistema.

## Contenido

El repositorio incluye:

- Diagrama de contexto.
- Diagrama de caso de uso general.
- Diagramas de casos de uso específicos.
- Diagramas de secuencia.
- Tarjetas CRC de clases candidatas.
- Diagrama de clases.
- Diagrama de componentes.
- Diagrama de despliegue.
- Versiones anteriores de diagramas y artefactos del proyecto.

## Estructura del repositorio

```text

Diagramas/
├── 01_Contexto
├── 02_Caso_Uso_General
├── 03_Casos_Uso_Especificos
├── 04_Diagramas_Secuencia
├── 05_Diagrama_Clases
├── 06_Diagrama_Componentes
├── 07_Diagrama_Despliegue
└── 99_Versiones_Anteriores
```

## Descripción de los diagramas

### 01_Contexto

Contiene el diagrama de contexto del sistema, donde se identifican los actores externos, servicios relacionados y límites principales de la solución.

### 02_Caso_Uso_General

Incluye el diagrama general de casos de uso, utilizado para representar las funcionalidades principales del sistema desde la perspectiva del usuario y de los servicios externos.

### 03_Casos_Uso_Especificos

Contiene diagramas de casos de uso detallados para los procesos principales del sistema, como acceso, perfil, planificación de viaje, reserva, pago, itinerario y alertas.

### 04_Diagramas_Secuencia

Incluye los diagramas de secuencia que representan la interacción entre actores, sistema y servicios externos para los principales flujos funcionales.

### 05_Diagrama_Clases

Contiene el diagrama de clases del sistema, donde se modelan las clases principales del dominio, sus atributos, métodos, relaciones, multiplicidades, interfaces y servicios externos.

### 06_Diagrama_Componentes

Incluye el diagrama de componentes, donde se representa la organización interna del sistema mediante el componente principal API SistemaGestionViajes, sus subcomponentes y las interfaces de comunicación con servicios externos.

### 07_Diagrama_Despliegue

Contiene el diagrama de despliegue, donde se muestra cómo se distribuye el sistema en nodos de infraestructura, incluyendo el dispositivo del viajero, servidor de aplicación, servidor de base de datos y servicios externos.

### 99_Versiones_Anteriores

Carpeta destinada a conservar versiones previas de diagramas o archivos que fueron reemplazados durante el desarrollo del proyecto.

## Módulos funcionales modelados

El sistema se organiza alrededor de los siguientes módulos:

- Acceso al sistema.
- Configuración del perfil.
- Planificación de viaje.
- Reserva y pago.
- Organización de itinerario.
- Alertas de viaje.
- Recomendaciones basadas en inteligencia artificial.
- Servicios externos considerados

El modelo contempla integración con servicios externos mediante interfaces:

- API de vuelos.
- API de hoteles.
- API de pagos.
- API de notificaciones.
- API de recomendaciones con inteligencia artificial.

El servicio de recomendaciones con IA se modela como un componente independiente del SOA principal, con el objetivo de permitir su reutilización por otros sistemas y facilitar su mantenimiento y escalabilidad.

## Herramientas utilizadas

Draw.io
Visual Studio Code.
GitHub.

## Desarrollador

- Juan Diego Guerrero Camargo

## Estado del proyecto

Proyecto académico de modelado UML avanzado terminado.

Actualmente incluye diagramas de análisis, vista lógica, vista de desarrollo y vista física del sistema.