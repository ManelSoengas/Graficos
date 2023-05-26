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
