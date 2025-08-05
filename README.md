# AluraStoreLatam
Análisis de datos de ventas de cuatro tiendas de Alura Store para identificar cuál vender. Se evaluaron ingresos, categorías, calificaciones, productos vendidos, costos de envío y desempeño geográfico. El objetivo es recomendar la tienda menos eficiente.

# 📊 Proyecto de Análisis de Datos - Alura Store LATAM

Este proyecto fue desarrollado como parte del **Challenge de Ciencia de Datos de Alura Latam**. El objetivo principal es analizar el desempeño de las cuatro tiendas que forman parte de la cadena *Alura Store* en América Latina, y así ayudar al Sr. Juan a decidir **cuál tienda vender** para iniciar un nuevo emprendimiento.

---

## 1️⃣ Propósito del Análisis

El análisis tiene como finalidad evaluar de manera objetiva y basada en datos el rendimiento de cada tienda, considerando cinco ejes principales:

- **Ingresos generados** por cada tienda
- **Volumen de ventas** por categoría de producto
- **Nivel de satisfacción** del cliente mediante las calificaciones
- **Productos más y menos vendidos**
- **Costo promedio de envío**

Además, se incluye un análisis **geoespacial** (opcional) para visualizar cómo se distribuyen las ventas por ubicación geográfica.

El resultado final consiste en una **recomendación concreta** sobre cuál tienda se debería vender, sustentada por datos, visualizaciones y métricas clave.

---

## 2️⃣ Estructura del Proyecto y Organización de Archivos

El proyecto está organizado de la siguiente manera:

```
📦 AluraStore_Proyecto_Final/
├── AluraStoreLatam_Final.ipynb     # Notebook principal con todos los análisis y gráficos
├── README.md                       # Documentación completa del proyecto
```

Todos los datos fueron obtenidos directamente desde el repositorio oficial del desafío, sin modificación manual de archivos.

---

## 3️⃣ Ejemplos de Gráficos e Insights Obtenidos

Durante el desarrollo del análisis se generaron gráficos claros y concisos para facilitar la interpretación:

- **Gráfico de Barras:** Ingresos por tienda
- **Barras Apiladas por Categoría:** Ventas por tipo de producto en cada tienda
- **Gráfico Horizontal:** Calificación promedio de los clientes
- **Texto + Barras:** Productos más y menos vendidos por tienda
- **Gráfico de Dispersión:** Costo promedio de envío por tienda
- **Mapa Geoespacial (Opcional):** Visualización de coordenadas de ventas por tienda

### Principales hallazgos:
- Una tienda tiene ingresos altos pero calificaciones bajas.
- Ciertas categorías dominan en tiendas específicas.
- Hay una disparidad significativa en los costos de envío entre tiendas.

---

## 4️⃣ Instrucciones para Ejecutar el Notebook

1. **Abrir el archivo** `AluraStoreLatam_Final.ipynb` en Google Colab o Jupyter Notebook.
2. Ejecutar las celdas en orden desde el principio:
   - Carga de datos
   - Procesamiento y análisis
   - Visualización de gráficos
   - Conclusión final
3. Asegurarse de estar conectado a Internet, ya que los datos se cargan desde URLs en GitHub.
4. No se requiere instalación adicional: todas las librerías utilizadas (`pandas`, `matplotlib`, `seaborn`) están preinstaladas en Colab.
5. Opcional: ejecutar el análisis geográfico si deseas observar patrones de distribución espacial de ventas.

---

Este proyecto fue realizado con un enfoque analítico y profesional, ideal para ser presentado en un portafolio de ciencia de datos o durante procesos de selección técnica.

