## Reto Bootcamp IA - Análisis de Datos con Google Colab

Este proyecto tiene como objetivo cargar y analizar datos abiertos desde el portal de Datos Abiertos de Colombia utilizando Python y la API de Socrata.

## 📥 **Requisitos Previos**
- Cuenta en [Google Colab](https://colab.research.google.com/)
- Cuenta en [Datos Abiertos de Colombia](https://www.datos.gov.co/)
- Clave de acceso (App Token) generada desde el portal de Socrata
- Python 3.x con varias bibliotecas.

## **Cómo Obtener un App Token en Datos Abiertos Colombia**

1. Inicia sesión en [Datos Abiertos de Colombia](https://www.datos.gov.co/).
2. Dirígete a tu perfil y selecciona **Mis Aplicaciones**.
3. Haz clic en **Crear Nueva Aplicación**.
4. Completa los campos requeridos y genera tu App Token.
5. Guarda el App Token para usarlo en el notebook.

## **Cómo Ejecutar el Proyecto en Google Colab**

1. Sube el notebook a tu Google Drive o ábrelo directamente en Google Colab.
2. Instala las dependencias necesarias ejecutando:

```python
pip install requeriments.txt
```

3. Agrega tu App Token de Socrata a Google Colab utilizando `userdata` de forma segura:

```python
from google.colab import userdata
userdata.set('APP_TOKEN', 'TU_APP_TOKEN')
```

4. Ejecuta las celdas para cargar y explorar los datos.
---
## AI Bootcamp Challenge - Data Analysis with Google Colab

This project aims to load and analyze open data from the Datos Abiertos de Colombia portal using Python and the Socrata API.

## Prerequisites
- Account on [Google Colab](https://colab.research.google.com/)
- Account on [Datos Abiertos de Colombia](https://www.datos.gov.co/).
- Access key (App Token) generated from the Socrata portal
- Python 3.x with several libraries
  
## How to Obtain an App Token from Datos Abiertos de Colombia
1. Log in to Datos Abiertos de Colombia.
2. Go to your profile and select My Applications.
3. Click on Create New Application.
4. Fill in the required fields and generate your App Token.
5. Save the App Token for use in the notebook.
   
## How to Run the Project on Google Colab
1. Upload the notebook to your Google Drive or open it directly in Google Colab.
2. Install the necessary dependencies by running:
```
pip install requeriments.txt
```
3. Add your Socrata App Token to Google Colab using userdata securely:
```
from google.colab import userdata
userdata.set('APP_TOKEN', 'TU_APP_TOKEN')
```
4. Run the cells to load and explore the data.

# Contributions
Contributions, issues, and feature requests are welcome! Feel free to fork this repository and submit a pull request.

---
Developed with ❤️ by **Alejandra Villa Posada**
