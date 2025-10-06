# Visualizaciones interactivas con CESIUM y Unreal Engine

Este repositorio contiene tanto la **documentación** como el **proyecto de Unreal Engine 5** desarrollado para el módulo de formación:

**"Visualizaciones interactivas con CESIUM y Unreal Engine"**

---

## Contexto

El módulo forma parte del proyecto **TwIN** impulsado por **TwIN Lab**, dentro de la iniciativa de **gemelos digitales** del **Gobierno de Navarra** y el **Ayuntamiento de Pamplona**.  

El objetivo es ofrecer un entorno de aprendizaje práctico para la creación de **visualizaciones interactivas en 3D** sobre el globo terráqueo mediante la integración de [Cesium for Unreal](https://cesium.com/platform/cesium-for-unreal/) con **Unreal Engine 5**.

---

## Contenido del repositorio

- `/Documentation` → Documentación y tutoriales paso a paso.  
- `AirTraffic.zip` → Proyecto de **Unreal Engine 5**, incluyendo:  
  - Configuración básica de Cesium y georreferenciación.  
  - Blueprints para consumir APIs externas (ej. OpenSky) y visualizar objetos dinámicos en el mundo.  
  - Ejemplos de visualización interactiva.
  - Link al vídeo de WebODM: https://youtu.be/48DFShBO9hM

---

## Objetivos del módulo

- Conocer la integración entre **Cesium** y **Unreal Engine 5**.  
- Aprender a consumir **APIs de datos geoespaciales en tiempo real**.  
- Representar objetos interactivos y dinámicos (aviones, vehículos, etc.) sobre el globo.  
- Desarrollar un flujo de trabajo reutilizable para futuros proyectos de gemelos digitales.  

---

## Requisitos

- [Unreal Engine 5.3+](https://www.unrealengine.com/)  
- [Cesium for Unreal Plugin](https://cesium.com/platform/cesium-for-unreal/)  
- Acceso a internet (para consumir APIs externas como OpenSky).  

---

## Uso

1. Clonar el repositorio:  
   ```bash
   git clone https://github.com/UPNAdrone/TwIN_Unreal_Cesium.git
2. Abrir el proyecto en Unreal Engine 5.
3. Cargar el nivel de ejemplo con Cesium.
4. Ejecutar la aplicación para visualizar los datos en tiempo real.

