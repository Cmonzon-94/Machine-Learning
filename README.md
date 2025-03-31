
❤️¡Bienvenido a mi proyecto de Machine Learning!

Las enfermedades cardíacas, también conocidas como enfermedades cardiovasculares, abarcan una amplia variedad de trastornos que afectan tanto al corazón como al sistema circulatorio. 
Estas condiciones representan una de las principales causas de discapacidad a nivel global. 
Dado que el corazón es uno de los órganos más importantes del cuerpo, cualquier enfermedad que lo afecte también puede impactar en otros órganos y sistemas del cuerpo. 
Existen diferentes tipos de enfermedades cardíacas, siendo las más comunes aquellas que provocan el estrechamiento o bloqueo de las arterias coronarias, mal funcionamiento de las válvulas cardíacas, agrandamiento del corazón, entre otras. 
Estas afecciones pueden derivar en insuficiencia cardíaca o infarto de miocardio.

​Las enfermedades cardiovasculares (ECV) continúan siendo una de las principales causas de mortalidad a nivel mundial. 
Según datos de la Real Academia Nacional de Medicina de España, en 2023 las enfermedades del sistema circulatorio fueron la segunda causa de muerte, con 114.685 fallecimientos, representando el 26,5% del total de defunciones. ​
Los datos provisionales indican que el 27,1% de las muertes en España durante este período se debieron a enfermedades del sistema circulatorio, mientras que los tumores representaron el 25,8%.

Por lo tanto, el objetivo de este proyecto es explorar el conjunto de datos relacionado con las enfermedades cardíacas mediante un análisis exploratorio de datos (EDA).
y aplicar algoritmos de clasificación para realizar predicciones.

📊 Datos

El conjunto de datos Heart Disease UCI proviene del UCI Machine Learning Repository (repositorio de aprendizaje automático de la Universidad de California, Irvine), que es una de las fuentes más conocidas para datasets de clasificación en Machine Learning. Este conjunto de datos es ampliamente utilizado en proyectos de clasificación relacionados con enfermedades cardíacas y se ha utilizado en varios estudios y tutoriales de Machine Learning.

Repositorio: UCI Machine Learning Repository - Heart Disease Dataset

Año de publicación: 1988

Propósito: Este conjunto de datos fue creado para predecir la presencia de enfermedades cardíacas.



🤖 Modelos Utilizados
Se probaron varios modelos y se seleccionaron los de mejor desempeño:

* Regresión Lineal
* Random Forest Regressor
* XGBoost Regressor
* CatBoost Regressor (mejor balance entre rendimiento y generalización)




🛠️ Tecnologías Utilizadas
Lenguaje: Python 
Librerías: Pandas, NumPy, Scikit-learn, XGBoost, CatBoost, Matplotlib, Seaborn, Scipy, Joblib
Entorno: Visual Studio Code, Jupyter Notebook
📁 Estructura del Proyecto
|── 📂 src/
|   ├── 📂 data/                  
|   ├── 📂 imgs/                  
|   ├── 📂 models/                
|   ├── 📂 notebooks/             
|   ├── 📂 results_notebook/      
|   ├── 📂 utils/                
|
├── 📄 README.md              # Documentación
└── 📄 presentacion.pdf       # Presentación/informe


----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
Heart diseases, also known as cardiovascular diseases, encompass a wide variety of disorders that affect both the heart and the circulatory system. These conditions are one of the leading causes of disability worldwide. Since the heart is one of the most vital organs in the body, any disease affecting it can also impact other organs and systems. There are various types of heart diseases, with the most common being those that cause narrowing or blockage of the coronary arteries, malfunctioning of the heart valves, heart enlargement, among others. These conditions can lead to heart failure or myocardial infarction.

Cardiovascular diseases (CVDs) continue to be one of the leading causes of mortality globally. According to data from the Real Academia Nacional de Medicina of Spain, in 2023, diseases of the circulatory system were the second leading cause of death, with 114,685 deaths, representing 26.5% of total deaths. Provisional data indicates that 27.1% of deaths in Spain during this period were due to diseases of the circulatory system, while tumors accounted for 25.8%.

Therefore, the goal of this project is to explore the heart disease dataset using exploratory data analysis (EDA) and apply classification algorithms to make predictions.
