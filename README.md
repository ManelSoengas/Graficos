A continuación se presentan algunos gráficos implementados en python. 
El estudio de los datos es un paso previo en cualquier implementación basada en IA.
Analizar los datos y representarlos es básico para hacernos una idea del tipo, dsitribusión, organización y tamaño.
```
# Graficos
Simple graphics with Python

# Datos
import pandas as pd
import numpy as np

# Generar los números aleatorios
numeros1 = np.random.randint(1, 100, size=20)
numeros2 = np.random.randint(1, 100, size=20)

# Crear el dataframe 1
df1 = pd.DataFrame({'Numeros': numeros1})

# Crear el dataframe 2
df2 = pd.DataFrame({'Numeros': numeros2})

# Imprimir los dataframes
print("Dataframe 1:")
print(df1)
print("\nDataframe 2:")
print(df2)
```
Una vez tenemos un conjunto de datos de muestra, pasamos a representarlos 
de manera gráfica y bajo diferentes formatos de representación.
```
# Gráfico de barras
import matplotlib.pyplot as plt
# Configurar el tamaño del gráfico
plt.figure(figsize=(10, 6))

# Representar el dataframe 1
plt.bar(df1.index, df1['Numeros'], label='Dataframe 1')

# Representar el dataframe 2
plt.bar(df2.index, df2['Numeros'], label='Dataframe 2')

# Configurar las leyendas y etiquetas
plt.xlabel('Índice')
plt.ylabel('Números')
plt.title('Gráfico de barras')
plt.legend()

# Mostrar el gráfico
plt.show()
```
![Texto alternativo](https://github.com/ManelSoengas/Graficos/blob/main/Captura.PNG)
