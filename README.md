# 🛒 Supermarket Sales — Mini Project (EDA + Insights + Business Recommendations)

Este proyecto realiza un análisis exploratorio completo del comportamiento de ventas de una cadena de supermercados utilizando un dataset con información de sucursal, tipo de cliente, género, línea de producto, precio unitario, cantidad, método de pago, rating y fecha.
El objetivo es descubrir patrones relevantes de compra y generar recomendaciones accionables para el negocio.

## 📊 Análisis Exploratorio de Datos (EDA)

A través de múltiples visualizaciones se identificaron patrones clave:

### 📍 Diferencias entre sucursales

 - Queens tiene los tickets promedio más altos, especialmente los martes, jueves y sábados.
 - Manhattan presenta un comportamiento estable y consistente durante toda la semana.
 - Brooklyn muestra tickets promedio más bajos y menor variabilidad entre días.

### 🛍️ Comportamiento por línea de producto

 - Home & Lifestyle es la categoría más fuerte en todas las sucursales, con un pico destacado en Manhattan.
 - Queens destaca en Food & Beverages y Fashion & Accessories.
 - Fashion & Accessories es la categoría más débil en Brooklyn y Manhattan.

### 👥 Perfil del cliente

 - Los clientes Member gastan sistemáticamente más que los Normal en todas las sucursales.
 - El gasto por género no presenta diferencias relevantes a nivel global, aunque sí pequeñas variaciones por sucursal.
 - No se observa correlación entre el gasto y el Rating otorgado por el cliente.

### 📅 Patrones temporales

 - Cada sucursal tiene “su propio ritmo” de ventas a lo largo de la semana.
 - Queens destaca por sus picos altos en gasto promedio los sábados.
 - Brooklyn tiene su mejor día de gasto promedio los martes, pero cae notablemente los fines de semana.

### 💡 Principales Insights de Negocio

 - Queens concentra los clientes de mayor valor, mientras que Brooklyn requiere estrategias para elevar el ticket promedio.
 - Las categorías fuertes varían por sucursal, por lo que es recomendable un enfoque de inventario y promociones segmentado.
 - El programa de membresía aporta valor real y debería promoverse aún más.
 - La satisfacción del cliente (según ratings) no depende del monto gastado, lo que sugiere oportunidad de mejorar la experiencia en tienda.

### 🧭 Recomendaciones de Negocio

 - Inventario segmentado: reforzar Home & Lifestyle en Manhattan; impulsar Food & Beverages y Fashion & Accessories en Queens.
 - Promociones por sucursal:
     - Queens: enfocarse en martes, jueves y sábado.
     - Manhattan: campañas constantes durante la semana.
     - Brooklyn: impulsar promociones de fin de semana para elevar el ticket.
  - Optimización operativa: asignar personal extra en días de alto consumo según cada sucursal.
  - Programa Member: continuar fortaleciéndolo, dado su impacto positivo en el ticket promedio.
  - Mejora del servicio: dado que el rating no depende del monto, mejorar factores soft de experiencia en tienda.

### ⚙️ Tecnologías Utilizadas

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook


🚀 Sobre el Proyecto

Este mini-proyecto fue creado como ejercicio de análisis de datos, diseño de visualizaciones y generación de insights accionables. Su enfoque principal es demostrar un flujo de trabajo completo de EDA con visualizaciones segmentadas, análisis comparativo por sucursal y recomendaciones de negocio basadas en comportamiento del cliente.
