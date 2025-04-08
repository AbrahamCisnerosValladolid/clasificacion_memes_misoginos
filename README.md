# clasificacion_memes_misoginos

# Clasificación de memes misóginos  
![UABC Logo](https://via.placeholder.com/150x50?text=UABC)  

**Autores**: Abraham Cisneros Valladolid  
**Afiliación**: Facultad de Ciencias, Universidad Autónoma de Baja California (UABC)  
**Contacto**: [abraham.cisneros@uabc.edu.mx](mailto:abraham.cisneros@uabc.edu.mx)  

---

## 📌 Resumen  
Este proyecto propone un método de minería de datos para clasificar memes como **misóginos** o **no misóginos**, analizando texto extraído de imágenes. El objetivo es identificar contenido sexista en redes sociales y contribuir a su moderación automática.  

---

## 🗃️ Dataset  
- **Fuente**: Plataforma [Codalab](https://codalab.org/).  
- **Tamaño**: 100 memes (50 misóginos y 50 no misóginos).  
- **Requisitos**:  
  - Texto legible en las imágenes.  
  - Formato variado (imágenes, texto, colores, tipografías).  

---

## 🛠️ Metodología  
1. **Extracción de texto**: Transcripción manual de texto en memes.  
2. **Procesamiento de texto**:  
   - **Bolsa de palabras (Bag of Words)**: Frecuencia de términos por categoría.  
   - **TF-IDF**: Ponderación de palabras según relevancia.  
3. **Clasificación**:  
   - **Métodos**: `Random Forest`, `Naive Bayes`, `SVM`.  
   - **División de datos**: 80% entrenamiento (40 misóginos + 40 no misóginos), 20% prueba (10 + 10).  

---

## 📊 Resultados  

### Bolsa de palabras vs. TF-IDF  
| Método          | Precisión (Bolsa de palabras) | Precisión (TF-IDF) |  
|-----------------|-------------------------------|--------------------|  
| Random Forest   | 95%                           | 95%                |  
| Naive Bayes     | 80%                           | 80%                |  
| SVM             | 85%                           | 90%                |  

### Palabras clave identificadas  
| **Misóginos**          | **No misóginos**      |  
|------------------------|-----------------------|  
| `hooker`, `bitch`      | `cheat`, `snow`       |  
| `feminist`, `sex`      | `house`, `water`      |  
| `kitchen`, `women`     | `jarvis`, `clean`     |  

---

Los detalles del proyecto se pueden encontrar en el [reporte](https://github.com/AbrahamCisnerosValladolid/clasificacion_memes_misoginos/blob/main/Proyecto_Mineria_v2.pdf)
