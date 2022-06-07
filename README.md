# perplejidad

Carpeta compartida con los archivos: https://unirioja-my.sharepoint.com/:f:/g/personal/gamata_unirioja_es/EsgSCdEumwhHr0B_LsxSL5cBRaDNzlqvI4vHWagHhX5Brw?e=yYs7jZ
    
Dentro de la carpeta "Conjuntos de datos" se encuentran los conjuntos de train, validation y test, que han sido creados en "Training and Testing sets.ipynb".
Hay hechas dos particiones de los datos, una con los datos originales, sin filtrar duplicados ni frases incompletas y otra con filtrado.
Datos sin filtrar (se encuentran en la carpeta compartida >> Conjuntos de datos>> conDuplicados):
- obtenidos del archivo que se llama *"corpusELElimpioUTF5pp.csv"*. Los archivos están estratificados por 'Mother tongue' y 'Level'.
- el 80% de los datos de origen son para entrenar y validar (*"train_set.csv"*) y el 20% para testear (*"test_set.csv"*).
- De ese 80%, el conjunto de datos para entrenar supone el 90% (*"train_train_set.csv"*) y el de validación el 10% (*"validation_train_set.csv"*).
Datos filtrados (en la carpeta compartida y este repositorio en *datasets*:
- obtenidos del archivo que se llama *"data.csv"*. Los archivos están estratificados por 'Mother tongue' y 'Level'.
- el 80% de los datos de origen son para entrenar y validar (*"train_set.csv"*) y el 20% para testear (*"test_set.csv"*).
- De ese 80%, el conjunto de datos para entrenar supone el 90% (*"train_train_set.csv"*) y el de validación el 10% (*"validation_train_set.csv"*).
