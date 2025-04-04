INSTRUCCIONES:
Paso 1: Fork it
Paso 2: Corre Preprocessing.ipynb
Paso 3: Corre Model.ipynb
Paso 4: Corre Deployer.ipynb
Paso 5: Para hacer inferencia con el modelo diseñado se debe correr la API existente en el archivo API.ipynb. Nota: Se debe reemplazar el archivo "prueba.csv" por los datos que se desee consultar).

ESPECIFICACIONES DE SOFTWARE MÍNIMO:
MacOS Sonoma 14.3/ Windows 11 
RAM: 4 GB.
Ancho de Banda: 10 Mbps.

NOTAS:
En este repositorio también se incluyen los siguientes archivos:
- clean_data.csv: el dataset brindado después de correr el archivo Preprocessing.ipynb
- X_train, y_train: los subjuntos de datos (X:features, y:label) para entrenamiento del modelo.
- X_test, y_test: los subjuntos de datos (X:features, y:label) para la evaluación del modelo.
- model_logreg.pkl: contiene el modelo de regresión logística entrenado para ejecutarse.
- prueba.csv: datos de prueba para consultar en la API.
- uri.json: 
