
# Web Scraping de Casas en Venta en Zona 10

## Descripción
Este proyecto realiza **web scraping** en la página de Mapainmueble para extraer información detallada de las propiedades en venta en la **Zona 10, Guatemala**.

## Objetivo
El objetivo es generar un **dataset estructurado** con información clave de cada propiedad, incluyendo:
- **Título de la propiedad**
- **Precio**
- **Ubicación (Zona 10, Guatemala)**
- **Cantidad de Habitaciones**
- **Cantidad de Baños**
- **Metros Cuadrados**
- **Inmobiliaria encargada**
- **URL de la propiedad**

## Tecnologías Usadas
- **Python**
- **BeautifulSoup** (Para la extracción de datos)
- **Requests** (Para hacer las solicitudes HTTP)
- **Pandas** (Para estructurar los datos en CSV)

## Estructura del Archivo CSV
El archivo generado `casas_zona_10_final.csv` tendrá la siguiente estructura:

| Título | Precio | Ubicación | Habitaciones | Baños | Metros Cuadrados | Inmobiliaria | URL |
|--------|--------|------------|--------------|-------|------------------|--------------|-----|
| CASA EN VENTA EN ZONA 10 | **850000** | Zona 10, Guatemala | 4 | 4.5 | 482 | GIEKA INMOBILIARIA | 🔗 Enlace a la propiedad |
| CASA EN VENTA EN ZONA 10 | **420000** | Zona 10, Guatemala | 3 | 3.5 | 250 | Sarissa Asesoría | 🔗 Enlace a la propiedad |

## Paginación
El script **automatiza la extracción de múltiples páginas** para obtener todas las propiedades en venta.

## Uso del Script
Para ejecutar el scraping, asegúrate de tener instaladas las dependencias:
```bash
pip install requests beautifulsoup4 pandas
```
Luego, ejecuta el script en Python:
```bash
python scraping_zona10.py
```
El archivo `casas_zona_10_final.csv` se generará con todos los datos estructurados.
