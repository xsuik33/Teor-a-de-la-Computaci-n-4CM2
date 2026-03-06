# Teoría de la Computación - 4CM2

## Reporte de Prácticas
**Institución:** Instituto Politécnico Nacional  
**Unidad Académica:** Escuela Superior de Cómputo  
**Asignatura:** Teoría de la Computación  

### Integrantes del Equipo
* **Gonzalez Ortiz Iker Saul**
* **Romero Martínez Diego Enrique**
* **Barrera Guerrero José Emanuel**

### Especificaciones del Sistema
* **Versión de Python:** 3.14.3
* **Librerías :**
  * Flet 0.81.0
  * anyio 4.12.1
  * httpx 0.28.1
  * anyio 4.12.1
  * certifi 2026.2.25
  * flet-desktop 0.81.0
  * h11 0.16.0
  * httpcore 1.0.9
  * idna 3.11
  * msgpack 1.1.2
  * oauthlib 3.3.1
  * repath 0.9.0
  * six 1.17.0
---

# Ejercicio 1: Cerraduras y Subcadenas (Flet)

Este programa permite realizar operaciones de cálculo para la Cerradura de Kleene ($V^*$) y la Cerradura Positiva ($V^+$) a partir de un conjunto de cadenas ingresado por el usuario, además de contar con un módulo de verificación de subcadenas.



## Instrucciones de Uso

### 1. Preparación de Archivos
Asegúrese de que los archivos `Practica1TeoCom.py` y `requirements.txt` se encuentren en el mismo directorio local.

### 2. Configuración del Entorno Virtual (Recomendado)
Para evitar conflictos de versiones, cree y active un entorno virtual desde la terminal:

```bash
# Crear el entorno
python -m venv venv

# Activar en Windows
venv\Scripts\activate

# Activar en Mac/Linux
source venv/bin/activate
