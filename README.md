# build-my-outfit

Importa fotos de tu ropa y deja que la IA te haga un conjunto en base a tus gustos personales.


# 👗 Outfit Generator Inteligente

¿Te gusta vestir bien, pero con las prisas del día a día crearte un buen outfit es misión imposible? ¿Y si te digo que con subir fotos de tu ropa una única vez, ya no tendrás que romperte más la cabeza
pensando? ¡Irás guapísimx y gracias a Python!

Este proyecto escrito íntegramente en **Python** permitirá construir **conjuntos de ropa automáticamente** a partir de imágenes de las prendas de tu armario.
¡Usará **machine learning** y procesamiento de imágenes para aprender tus combinaciones favoritas de colores y sugerirte outfits completos!

---

## 🧠 ¿Cómo funcionará?

1. **Análisis de imágenes**  
   Para ello, habrá que cargar una imagen en formato .jpg de la prenda con el fondo en blanco (se recomienda el uso de la aplicación Photoroom para recortar correctamente la ropa).
   El programa detectará los **3 colores predominantes** de cada prenda.

3. **Clasificación de tipo de prenda**  
   El usuario deberá indicar qué tipo de prenda está subiendo (si es una camiseta, un pantalón, unos zapatos...). De esta manera, se entrenará al modelo que irá aprendiendo automáticamente.
   
5. **Preferencias de color**  
   La clave de este programa es la personalización. Se indicará manualmente qué combinaciones de colores le gustan al usuario (por ejemplo, negro, blanco y rojo).

6. **Generación de outfits**  
   Con el tiempo, el sistema generña conjuntos de ropa completos que coincidan con tus colores favoritos y la categoría de prendas necesarias para un outfit.

---

## ⚙️ Tecnologías utilizadas

- **Python 3.10+** - por el momento, TensorFlow no está soportado en Python 3.12
- **OpenCV** – procesiamiento de imágenes y extracción de colores
- **TensorFlow** – entrenamiento del modelo
- **Scikit-learn** – para tareas de clasificación
- **matplotlib** - visualización de paletas de colores

---

## 🚧 Estado del proyecto

Actualmente en desarrollo.   Las funcionalidades implementadas hasta ahora:

- [x] Detección de colores predominantes
- [x] Clasificación manual de tipo de prenda
- [x] Sistema básico de puntuación de colores
- [ ] Clasificador entrenable con tus preferencias
- [ ] Generador automático de outfits
- [ ] Interfaz gráfica simple para uso diario (planeada)

---

## 🛠 Cómo ejecutarlo

Próximamente...
