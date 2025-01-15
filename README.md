# Segmentación de Fallas Geológicas en Imágenes Sísmicas Ruidosas usando Redes Neuronales Convolucionales

## Descripción del repositorio.
Este repositorio contiene códigos de programación en lenguaje Python y una base de datos de imágenes sísmicas con sus respectivas máscaras de fallas geológicas interpretadas, extraidas de repositorios públicos para mi tesis de pregrado "Segmentación de fallas geológicas en imágenes sísmicas ruidosas usando redes neuronales convolucionales".

## Base de Datos 💾
Los datos fueron extraidos de repositorios publicos de información, relacionados a continuación:

- Datos Force 2020 (Bormann P., Aursand P., Dilib F., Dischington P., Manral S. 2020. FORCE Machine Learning): https://drive.google.com/drive/folders/1jJhpmoAsMmA-kB1dL1lGDW_aRSTbkprV. 
- Datos sísmicos interpretados en gigabytes para el reconocimiento automático de fallas (An, Yu; Guo, Jiulin; Ye, Qing; Childs, Conrad; Walsh, John; Dong, Ruihai, 2021, "A Gigabyte Interpreted Seismic Dataset for Automatic Fault Recognition", https://doi.org/10.7910/DVN/YBYGBK, Harvard Dataverse, V4) : https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/YBYGBK.
- Datos sísmicos sintéticos 200T, 20V (Xinming Wu, "FaultSeg3D: Using Synthetic Seismic Data to Train an End-to-End Convolutional Neural Network for 3D Seismic Fault Detection," Geophysics, 2019.) : https://www.kaggle.com/datasets/malik9/synth-seis-data/data?select=prediction.

Las imágenes sísmicas procesadas y sus máscaras, pueden ser descargadas en los siguientes enlaces:
- Datos implementación Fase 2 : [![Kaggle](https://kaggle.com/static/images/open-in-kaggle.svg)](https://www.kaggle.com/datasets/alvaroascanio/implem-fase2)
- Datos implementación Fase 3: [![Kaggle](https://kaggle.com/static/images/open-in-kaggle.svg)](https://www.kaggle.com/datasets/alvaroascanio/implem-fase3)

Los modelos entrenados de las redes neuronales convolucionales implementadas están disponibles para descarga en el siguiente enlace: [![Google Drive](https://img.shields.io/badge/Google%20Drive-4285F4?style=for-the-badge&logo=googledrive&logoColor=white)](https://drive.google.com/drive/folders/1InKmOl8_ip85eJrjjhGoh_Uy_uEFv0GO?usp=sharing)

## Código (Notebooks) 🐍
En este trabajo fue necesario el uso del lenguaje de programación Python. A continuación, se relacionan los Jupyter Notebook ejecutados en entornos de desarrollo integrado (IDE), como Visual Studio Code (Local) y Kaggle (https://www.kaggle.com/). Para el entrenamiento de los algoritmos de redes neuronales convolucionales se utilizó una GPU NVIDIA TESLA P100 de manera remota a través de los servidores gratuitos de Kaggle.

- **Notebooks ejecutados en entorno Visual Studio Code (Local)**.

Procesamiento de sísmica 3D a parches 2D : [![Kaggle](https://kaggle.com/static/images/open-in-kaggle.svg)](https://www.kaggle.com/code/alvaroascanio/procesamiento)

Funciones de inducción de ruido en imágenes sísmicas : [![Kaggle](https://kaggle.com/static/images/open-in-kaggle.svg)](https://www.kaggle.com/code/alvaroascanio/ruido-funciones)

- **Notebooks ejecutados en entorno Kaggle (Remoto)**.
  
Implementación de red neuronal convolucional Unet Attention: [![Kaggle](https://kaggle.com/static/images/open-in-kaggle.svg)](https://www.kaggle.com/code/alvaroascanio/modelo-unet)

Implementación de red neuronal convolucional Unet++ : [![Kaggle](https://kaggle.com/static/images/open-in-kaggle.svg)](https://www.kaggle.com/code/alvaroascanio/modelo-unet-i)

Implementación de red neuronal convolucional Unet Inception :[![Kaggle](https://kaggle.com/static/images/open-in-kaggle.svg)](https://www.kaggle.com/code/alvaroascanio/modelo-unet-inception)

Evaluación de imágenes de test ruidosas: [![Kaggle](https://kaggle.com/static/images/open-in-kaggle.svg)](https://www.kaggle.com/code/alvaroascanio/noise-test)


## Colaboración 👥

Este trabajo es de mejora continua, en caso de que encuentres algun error o tengas alguna sugerencia sobre el trabajo realizado, por favor realiza un comentario en la sección de issue del repositorio. Si tienes alguna duda y quieres hablar acerca del proyecto contáctame a mi correo o redes sociales.

## Créditos ✏️


* **Alvaro José Ascanio:**   alvarojoseascanio@gmail.com </br> <a href="https://www.linkedin.com/in/alvaroascanio/">
  <img src="https://cdn-icons-png.flaticon.com/512/174/174857.png" alt="LinkedIn Account" style="width:30px;height:30px;">
</a> </br>
* **Paul Goyes:**   goyes.yesid@gmail.com </br> <a href="https://www.linkedin.com/in/paul-goyes-0212b810/">
  <img src="https://cdn-icons-png.flaticon.com/512/174/174857.png" alt="LinkedIn Account" style="width:30px;height:30px;">
</a> </br>
* **Ana Gabriela Mantilla:** anagmd2019@gmail.com </br> <a href="https://www.linkedin.com/in/ana-gabriela-mantilla-24377a21a/">
  <img src="https://cdn-icons-png.flaticon.com/512/174/174857.png" alt="LinkedIn Account" style="width:30px;height:30px;">
</a>

## Cómo citar ✏️

Este código se encuentra protegido bajo una licencia de libre acceso que tiene las siguientes condiciones: 

- Se requiere la preservación de los avisos de derechos de autor y licencia
- Se prohibe el uso de estos códigos con fines lucrativos
- Los autores no se hacen responsables del uso de los códigos por parte de terceros
- En caso de modificaciones al código, deben especificarse en un apartado donde se cite la fuente original de este: https://github.com/AlvaroAscanio/Segmentacion-de-Fallas-Geologicas-en-Imagenes-Sismicas-ruidosas
- No se permite la publicación de este código en otras plataformas bajo ninguna circunstancia sin consentimiento de los autores

**Los autores prohiben eliminar, borrar o modificar este apartado**
