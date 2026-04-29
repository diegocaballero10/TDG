# Identificación de Perfiles de Rendimiento Académico mediante Clustering
## Pontificia Universidad Javeriana & Universidad Nacional de Colombia

### Descripción
Este repositorio contiene el código desarrollado para el trabajo de grado 
"Identificación de Perfiles de Rendimiento Académico mediante Clustering en 
la Pontificia Universidad Javeriana y la Universidad Nacional: Un Análisis 
desde Saber 11 hasta Saber Pro".

El proyecto aplica técnicas de clustering no supervisado sobre los resultados 
de las pruebas Saber 11 (2014-2017) y Saber Pro (2018-2022) de estudiantes 
de programas de Administración y áreas afines, con el fin de identificar 
perfiles diferenciados de desempeño académico.

---

### Autor
**Diego Orlando Caballero Sarmiento**  
Pregrado en Ciencia de Datos  
Facultad de Ciencias  
Pontificia Universidad Javeriana  
Bogotá D.C., 2026

**Tutor:** Néstor Armando Nova Arévalo  
**Cotutora:** Andrea González Sandoval

---

### Estructura del repositorio\
### Datos
Los datos utilizados en este proyecto provienen de las bases de datos 
oficiales del Instituto Colombiano para la Evaluación de la Educación 
(ICFES)

---

### Instrucciones de uso

#### Google Colaboratory (recomendado)
1. Abrir el notebook directamente desde este repositorio haciendo clic en 
   el archivo `.ipynb`
2. En la parte superior aparecerá la opción **"Open in Colab"**, hacer clic 
   ahí
3. Una vez en Colab, conectar con los datos propios siguiendo las 
   instrucciones del notebook
4. Ejecutar las celdas en orden con **Ctrl + Enter** o usando 
   **Runtime → Run All**
   
### Metodología
El proyecto sigue la metodología **CRISP-DM** e incluye las siguientes etapas:
- Integración de bases de datos Saber 11 y Saber Pro mediante archivo de 
  llaves del ICFES
- Análisis exploratorio de datos
- Preprocesamiento y estandarización con StandardScaler
- Comparación de seis algoritmos de clustering: K-Means, Gaussian Mixture, 
  Fuzzy C-Means, Clustering Aglomerativo, DBSCAN y Spectral Clustering
- Validación interna mediante Silhouette, Davies-Bouldin y Calinski-Harabasz
- Validación externa mediante coeficiente de Cramér's V

---

### Referencia
Si utiliza este código en su investigación, por favor cítelo como:

Caballero Sarmiento, D. O. (2026). *Identificación de Perfiles de 
Rendimiento Académico mediante Clustering en la Pontificia Universidad 
Javeriana y la Universidad Nacional: Un Análisis desde Saber 11 hasta 
Saber Pro*. Trabajo de grado, Pontificia Universidad Javeriana, 
Bogotá D.C., Colombia.
   
