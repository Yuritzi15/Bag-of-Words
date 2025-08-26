# 🎯 Representación de Requerimientos Funcionales y No Funcionales con Bag of Words 🎯

El objetivo de este repositorio es compartir una implementación de la técnica de representación de texto clásica **Bag of Words** (BoW) que busca identificar palabras clave asociadas a **requerimientos funcionales** y **no funcionales** escritos en texto en inglés para realizar clasificación. 

---


## 📊 Datos 📊

El conjunto de datos utilizado se conforma de 550 requerimientos recopilados de la web que han sido previamente etiquetados como funcionales y no funcionales.


## 🛠️ Preprocesamiento del texto 🛠️

El preprocesamiento del texto incluye: 
- Tokenización
- Lowercasing 
- Eliminación de Stopwords 
- Lematización 

## 🔍 Análisis de palabras más representativas 🔍
Haciendo uso de la biblioteca _Word Cloud_ se realizó una representación visual de las palabras asociadas a cada tipo de requerimiento de acuerdo con la frecuencia en la que aparecían en los vectores obtenidos mediante BoW 

## ⚙️ Ejecutar el Notebook con Jupyter o VS Code ⚙️
1. **Clona el repositorio** 
 ```bash
 git clone https://github.com/Yuritzi15/Bag-of-Words
 cd repositorio-bow
```


2. **Instala las dependencias**
 ```bash
 pip install -r requirements.txt
```

3. **Ejecuta el notebook**
 ```bash
 jupyter notebook BoW.ipyn
 ```
