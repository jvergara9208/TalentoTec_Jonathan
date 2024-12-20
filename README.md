﻿# Análisis de la Penetración de Internet Fijo en Bogotá para 2024 y 2025

## Definición

### Introducción
El objetivo de este proyecto es analizar la penetración de internet fijo en diversas regiones de Colombia utilizando el conjunto de datos de Penetración de Internet Fijo de 2015 a 2023. Los datos incluyen campos como departamentos, municipios, número de accesos a internet fijo, estimaciones de población (DANE) e índices calculados. Nos centraremos en entender las tendencias, las disparidades regionales y las proyecciones futuras, en particular para Bogotá, en los años 2024 y 2025.
https://youtu.be/bVcpjnD85VA
---

## Descripción del Problema
El principal desafío es predecir el crecimiento de los accesos a internet fijo en Bogotá para los años 2024 y 2025. Los datos históricos ayudan a identificar patrones de crecimiento y a predecir cómo podrían cambiar los accesos, integrando factores externos como el crecimiento poblacional y el desarrollo de infraestructura tecnológica.

### Información de la Fuente de Datos
- **Internet Fijo Penetración Departamentos:**  
  Número de suscriptores con acceso fijo a internet en Colombia reportados trimestralmente.  
  Basados en datos históricos y proyecciones del DANE, se calcula el porcentaje de penetración de internet fijo por trimestre.  

- **Última Actualización:** 17 de septiembre de 2024  
- **Datos suministrados por:** Ministerio de Tecnologías de la Información y las Comunicaciones  

---

## Pasos para el Análisis de los Datos

1. **Limpieza de datos:** Verificar que no existan valores nulos o erróneos, especialmente en las columnas de año, trimestre, accesos a internet y población.  
2. **Análisis exploratorio de datos (EDA):** Observar tendencias a lo largo del tiempo para distintos departamentos y municipios, analizando cómo ha evolucionado el índice de penetración de internet.  
3. **Filtrado de datos:** Extraer específicamente los datos de Bogotá.  
4. **Análisis de tendencias:** Visualizar el crecimiento de los accesos a internet fijo en Bogotá en el período 2015-2023.  
5. **Análisis de correlación:** Evaluar relaciones entre accesos a internet fijo, tamaño de la población y otros factores.

---

## Enfoque para la Predicción 2024-2025

### Método Principal
La predicción del crecimiento de los accesos a internet fijo en Bogotá se realizará utilizando redes neuronales.  

1. **Preparación de los datos:**  
   - Extraer y transformar los datos históricos de Bogotá.  
   - Calcular la tasa de crecimiento anual.  

2. **Entrenamiento del modelo:**  
   - Entrenar una red neuronal para capturar patrones en los datos históricos.  

3. **Predicciones:**  
   - Usar la red neuronal entrenada para proyectar el crecimiento de los accesos a internet fijo en Bogotá para 2024 y 2025.  

### Técnicas Complementarias
- **Análisis de series de tiempo:** Modelos como ARIMA para contrastar los resultados de la red neuronal.  
- **Visualización:** Gráficos para representar las tendencias y comparaciones regionales.

---

## Visualizaciones Potenciales

1. **Gráfico de series temporales:**  
   Mostrar el crecimiento de los accesos a internet fijo en Bogotá (2022-2023) y las proyecciones para 2024-2025.  

2. **Gráfico de barras:**  
   Comparar el número total de accesos en Bogotá con otros municipios clave.  

3. **Gráfico de tasa de crecimiento:**  
   Visualizar la evolución de la tasa de crecimiento de los accesos en Bogotá.

---

## Herramientas Utilizadas

- **Google Colab:** Desarrollo y ejecución del código.  
- **Gemini:** Arreglos en funciones.  
- **Wordize:** Conversión de documentos de Word a Markdown.  
- **Visual Studio Code:** Subida del código al repositorio.  
- **Repositorio GitHub:** [TalentoTec_Jonathan](https://github.com/jvergara9208/TalentoTec_Jonathan)

---

## Referencias Bibliográficas

1. **Datos de penetración de Internet Fijo en Colombia:**  
   [https://www.datos.gov.co/Ciencia-Tecnolog-a-e-Innovaci-n/Internet-Fijo-Penetraci-n-Departamentos/4py7-br84/about_data](https://www.datos.gov.co/Ciencia-Tecnolog-a-e-Innovaci-n/Internet-Fijo-Penetraci-n-Departamentos/4py7-br84/about_data)

2. **Redes Neuronales Recurrentes - IBM:**  
   [https://www.ibm.com/es-es/topics/recurrent-neural-networks](https://www.ibm.com/es-es/topics/recurrent-neural-networks)

3. **Tutorial de ARIMA - DataCamp:**  
   [https://www.datacamp.com/es/tutorial/arima#:~:text=Un%20modelo%20ARIMA%20(Media%20M%C3%B3vil,afinar%20las%20predicciones%20(MA)](https://www.datacamp.com/es/tutorial/arima#:~:text=Un%20modelo%20ARIMA%20(Media%20M%C3%B3vil,afinar%20las%20predicciones%20(MA))

4. **Construcción de una red neuronal desde cero - Medium:**  
   [https://medium.com/@thisislong/building-a-recurrent-neural-network-from-scratch-ba9b27a42856](https://medium.com/@thisislong/building-a-recurrent-neural-network-from-scratch-ba9b27a42856)
