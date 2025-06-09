# 🧠 Deep Transformer para Series Temporales – Influenza Prevalence Case

Este repositorio contiene la implementación y prueba del modelo **Transformer para series temporales**, basado en el paper:

> **"Deep Transformer Models for Time Series Forecasting: The Influenza Prevalence Case"**  
> DOI: [10.48550/arXiv.2001.08317](https://doi.org/10.48550/arXiv.2001.08317)

---

## 🎯 Objetivo

Replicar el modelo propuesto en el artículo mencionado, evaluando su comportamiento inicial sobre datos de prevalencia de influenza. Esta implementación forma parte del trabajo preliminar para un **plan de tesis** en ciencia de la computación.

---

🖥️ Entorno de ejecución:
- CPU (sin GPU)

- Procesador: antiguo

- PyTorch

- Entrenamiento limitado a 5 épocas (≈7 horas)



## 🛠️ Tecnologías usadas

- Python 3.10+
- PyTorch
- NumPy
- Matplotlib
- Pandas

> ⚠️ Requisitos completos en `requirements.txt`.

---

## 📁 Archivos subidos: 
- train.py

- inference_example.py

- dataset.py

- output_metrics.txt

- output_plot.png

## 📉 Resultados obtenidos:
- MSE: 335281.37

- MAE: 578.89

- RMSE: 579.03

Las predicciones fueron planas y sobreestimadas debido al bajo número de épocas y las restricciones del entorno. Sin embargo, el modelo se ejecutó correctamente, y se visualizó la salida comparando histórico, real y predicción.

📸 Evidencias:
 (output_plot.png)

-![Captura del entrenamiento de 5 épocas](Img/entrenamient_5_epocas.png)
 
-![Captura del gráfico de predicción](Img/resultados_predicion.png)

-![Captura del log de consola](Img/resultado_consola.jpeg)

Comentarios sobre el desempeño observado




