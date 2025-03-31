# 🐾 Adivina la Foto

Este proyecto utiliza un modelo de aprendizaje profundo para clasificar imágenes de **perros** y **gatos**. Se basa en redes neuronales convolucionales (*CNN*) implementadas con *TensorFlow* y *Keras*.

---
## 📌 Características
✅ Clasificación automática de imágenes en dos categorías: **perros** y **gatos**.  
✅ Entrenamiento basado en un subconjunto del dataset *Cats vs Dogs*.  
✅ Uso de una **interfaz interactiva con Streamlit** para predicciones en tiempo real.  
✅ Código optimizado para ejecución **local o en la nube**.  

---
## 📁 Estructura del Proyecto
```plaintext
Adivina_perro_o_gato/
│── app.py                      # Aplicación en Streamlit
│── cat_dog_classifier.h5       # Modelo ya entrenado y guardado
│── requirements.txt            # Dependencias del proyecto
│── README.md                   # Documentación del proyecto
```

---
## 🚀 Instalación y Uso

### 1️⃣ Clonar el repositorio
```bash
git clone https://github.com/MayteGarciaCalvo/Adivina_perro_o_gato.git
cd Adivina_perro_o_gato
```

### 2️⃣ Instalar dependencias
```bash
pip install -r requirements.txt
```

### 3️⃣ Entrenar el modelo
💡 *El modelo ya está entrenado y guardado en:*  
📂 **cat_dog_classifier.h5**

De todas formas he subido todos los archivos con sus códigos por si se quiere realizar alguna modificación.
###Importante eliminar los números de los archivos subidos!!!
Ejemplo: descargar_gato_perro.py en vez de 1-descargar_gato_perro.py

### 4️⃣ Ejecutar la aplicación
```bash
streamlit run app.py
```

---
## 📊 Entrenamiento del Modelo
El modelo está basado en una **CNN** con *TensorFlow* y *Keras*. Utiliza capas convolucionales para extraer características de las imágenes y clasificarlas. Se entrenó con imágenes de **gatos y perros** divididas en:
📌 **Train**: 1000 imágenes por clase  
📌 **Validation**: 500 imágenes por clase  
📌 **Test**: 500 imágenes por clase  

---
## 🎯 Predicción en Tiempo Real
Puedes subir una imagen en la interfaz de **Streamlit**, y el modelo predecirá si es un **perro** o un **gato**.

---
## 📜 Licencia
Este proyecto es de código abierto bajo la licencia **MIT**. ¡Siéntete libre de contribuir! 🚀  

**Mayte Garcia**  
😺🐶
