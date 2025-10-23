# 🏠 Análisis Exploratorio de Datos (EDA) – Airbnb Valencia

## 📖 Descripción del proyecto
Este proyecto realiza un **Análisis Exploratorio de Datos (EDA)** sobre el mercado de **alojamientos de Airbnb en la ciudad de Valencia**, utilizando datos públicos de la plataforma [Inside Airbnb](http://insideairbnb.com/).  

El objetivo del análisis es **comprender la evolución del mercado según el tamaño de los propietarios**, analizar **cómo varían los precios y la cuota de mercado a lo largo del tiempo**, y detectar posibles **signos de profesionalización y concentración** dentro del ecosistema de anfitriones.  

El trabajo se centra en cuatro periodos distintos, lo que permite observar tanto **patrones estacionales** (por ejemplo, la influencia de las Fallas o el verano) como **cambios estructurales** en el comportamiento del mercado.

---

## 📂 Contenido del proyecto

├── datasets/ # Contiene los 4 datasets utilizados en el análisis (dic_24, mar_25, jun_25, sep_25)
├── presentacion/ # Incluye la presentación final y los gráficos generados durante el análisis
├── Notebook EDA.ipynb # Notebook principal con todo el desarrollo del análisis exploratorio
└── README.md # Documento descriptivo del proyecto


---

## 📊 Dataset
Los datos utilizados proceden de la fuente pública **Inside Airbnb**, correspondiente a la ciudad de **Valencia (España)**.  
Cada dataset refleja una fotografía del mercado en un momento concreto:

- **Diciembre 2024**  
- **Marzo 2025**  
- **Junio 2025**  
- **Septiembre 2025**

---

## 📘 Estructura del notebook

El notebook está estructurado de la siguiente forma:

1. **Introducción y objetivo del proyecto:**  
   Se presenta el propósito del análisis y el contexto general del mercado de Airbnb en Valencia.

2. **Carga de librerías y datasets:**  
   Se importan las librerías necesarias para el estudio y se cargan los cuatro datasets correspondientes a los distintos periodos analizados.

3. **Exploración inicial de datos:**  
   Se revisan las columnas de los datasets para identificar la información más relevante para el estudio, comprobando su fiabilidad y coherencia entre periodos.

4. **Análisis y visualización:**  
   En primer lugar, se generan gráficos para **contextualizar el estado actual de Airbnb en Valencia**, mostrando distribución de alojamientos y tipo de oferta.  
   Posteriormente, el análisis se centra en **el tamaño de los propietarios**, la **evolución de su cuota de mercado** y las **consecuencias de estos cambios en los precios** de los alojamientos.

---

## 🧩 Conclusiones generales

El mercado de Airbnb en Valencia muestra una **transición gradual hacia la concentración** y una **mayor profesionalización de los anfitriones**.  
Mientras los pequeños propietarios reducen su presencia, los grupos con múltiples alojamientos incrementan su influencia y capacidad de fijar precios.  

Aunque no se observa una correlación lineal entre el tamaño del propietario y el precio, sí existen **umbrales de comportamiento diferenciados**, donde a partir de 3–5 alojamientos los propietarios tienden a actuar como operadores profesionales.  

Estas tendencias reflejan un **mercado en evolución**, influido tanto por factores turísticos estacionales como por dinámicas de competencia y rentabilidad.
