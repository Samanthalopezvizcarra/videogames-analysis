# Análisis Exploratorio de Datos de Videojuegos 🎮

Este proyecto tiene como objetivo analizar un conjunto de datos de videojuegos con el fin de identificar patrones de venta, evolución por plataforma, preferencias de género y diferencias regionales. El análisis también incluye pruebas estadísticas para validar hipótesis sobre calificaciones de usuarios.

Autora: **Samantha López Vizcarra**  

## 📂 Contenido del proyecto

### 1. Limpieza y preparación de datos
- Normalización de nombres de columnas.
- Conversión de tipos de datos (fechas, puntuaciones, categorías).
- Manejo de valores nulos según el contexto.
- Generación de nuevas variables como `total_sales`.

### 2. Análisis exploratorio
- Evolución del mercado desde 1980 a 2016.
- Análisis de plataformas con mayores ventas y sus ciclos de vida.
- Comparación de ventas por plataforma, género y región.
- Identificación de títulos más vendidos y sus plataformas dominantes.
- Relación entre calificaciones (usuarios y críticos) y ventas.

### 3. Perfil regional
- Estudio de preferencias por región (NA, EU, JP).
- Géneros y plataformas favoritas por mercado.
- Análisis del impacto de la clasificación ESRB en las ventas.

### 4. Pruebas de hipótesis
- ¿Los usuarios puntúan igual en distintas plataformas?
- ¿Los géneros influyen en la valoración de los usuarios?

## 📊 Herramientas utilizadas
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- SciPy

## 📁 Dataset
El conjunto de datos proviene de `games.csv`, el cual contiene información histórica sobre lanzamientos de videojuegos, ventas por región, calificaciones de usuarios y críticos, y datos de clasificación ESRB.

## 📌 Conclusiones destacadas
- Las plataformas más exitosas fueron PS2, X360 y PS3.
- La actividad de una plataforma puede durar más de una década (ej. PC, DS).
- Las reseñas de críticos tienen una ligera influencia en las ventas; las de usuarios no tanto.
- Existen diferencias regionales claras en preferencias de plataformas y géneros.
- Las clasificaciones ESRB pueden influir en las ventas, especialmente en América del Norte.

## 🚀 Cómo ejecutar
Clona el repositorio: git clone url
Crea un enviroment: python -m venv venv
Activa el enviroment: venv\Scripts\activate
Instala los requerimientos: pip install -r requirements.txt
Corre el notebook del análisis: videogames_analysis.ipynb
