# CropPrediction
Generaremos un modelo SVM y lo pondremos en producción usando Streamlit. El modelo SVM permitirá recomendar un tipo de cultivo dependiendo de características del suelo y ambientales.

##  1. Entrenamiento del modelo
Entrenamos el modelo SVM usando el siguiente cuaderno de colab
    
   [CropPrediction.ipynb](https://github.com/DavidReveloLuna/API_Gcloud_Streamlit/blob/master/CropPrediction.ipynb)

##  2. Producción en servidor local - preparación del entorno

Creamos un entorno con python 3.7, e instalamos las dependencias necesarias.

    $   conda create -n ApiCrop
    $   conda activate ApiCrop
    $   conda install python=3.7
    $   pip install -r requirements.txt
    $   streamlit run app.py
    
##  3. Producción en servidor remoto

    *   Acceder a una cuenta de streamlit cloud 
    *   Generar una app desde https://share.streamlit.io/
    *   Ejecutar en cualquier navegador el link en el cual queda almacenada la app  
    
  ![Screenshot](https://github.com/DavidReveloLuna/API_Gcloud_Streamlit/blob/master/assets/Screenshot.png)

## Agradecimientos
Tomado desde https://github.com/DavidReveloLuna/API_Gcloud_Streamlit y modificado el paso 3

