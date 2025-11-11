# ChallengeTiendasAlura

# Análisis de Tiendas con Python

¡Hola! A todo el que este viendo este repositorio
Este es un pequeño proyecto creado en Google Colab que realicé mientras aprendí sobre **Python** y la librería **pandas**.  
El objetivo fue analizar información de varias tiendas y obtener algunos resultados básicos para encontrar cual tienda se debia vender.

---

##  Descripción del proyecto

En este proyecto trabajé con un conjunto de datos que contiene información sobre diferentes tiendas, incluyendo el **Producto** **Categoría del Producto** **costo de envío**, el **número de ventas** y otros valores.

Usando **pandas**, logré hacer operaciones sencillas para practicar el análisis de datos.  
Entre las cosas que realize están:

- Calcular el **promedio de costo de envío** por cada tienda.  
- Encontrar cuál tienda tiene el **mayor costo promedio de envío**.  
- Analizar los resultados y decidir qué tienda sería mejor vender.

---

## Código principal

Un ejemplo del código que utilice fue :

```python
import pandas as pd

# Cargar los datos desde un archivo CSV

tienda = pd.read_csv(url)
tienda2 = pd.read_csv(url2)
tienda3 = pd.read_csv(url3)
tienda4 = pd.read_csv(url4)


# Calculando las ventas por categoria de cada tienda
categorias_por_tienda = datos.groupby("Tienda")["Categoría del Producto"].value_counts()
print(categorias_por_tienda)

```
## Tecnologías utilizadas

-🐍 Python 3 🐍
- Pandas
- Jupyter Notebook (opcional para pruebas)
