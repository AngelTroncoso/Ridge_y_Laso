# 📊 Modelos Ridge & Lasso para Optimización de Marketing 💰
![Marketing](https://image.lexica.art/full_webp/32b87750-8d66-4a9d-ae7b-cd6f37902a8d)

¡Bienvenido al repositorio de modelos de regularización para estrategias de marketing! Este proyecto aplica **Ridge y Lasso Regression** para identificar los factores más influyentes en campañas publicitarias y optimizar presupuestos. Ideal para CMOs, analistas de marketing y equipos de crecimiento.

## 📋 Tabla de Contenidos
1. [Requisitos](#🔧-requisitos)
2. [Instalación](#⚙️-instalación)
3. [Uso](#🚀-uso)
4. [Estructura del Proyecto](#📂-estructura-del-proyecto)
5. [Datos](#📊-datos)
6. [Resultados](#📈-resultados)
7. [Contribución](#🤝-contribución)
8. [Licencia](#📜-licencia)
9. [Contacto](#📧-contacto)

---

## 🔧 Requisitos
- Python 3.10+
- Bibliotecas: `scikit-learn`, `pandas`, `numpy`, `matplotlib`, `seaborn`, `plotly`
- Memoria RAM: 8GB+ (para conjuntos de datos grandes)

## ⚙️ Instalación
```bash
# Clonar repositorio
git clone https://github.com/tuusuario/marketing-ridge-lasso.git

# Crear entorno virtual (recomendado)
python -m venv env
source env/bin/activate  # Linux/Mac
env\Scripts\activate     # Windows

# Instalar dependencias
pip install -r requirements.txt
```
## 📂 Estructura del Proyecto
├── data/  
│   ├── campaigns.csv                # Datos históricos de campañas  
│   ├── customer_segments.csv        # Segmentación de clientes  
│   └── preprocessor.py              # Pipeline de preprocesamiento  
├── models/  
│   ├── ridge_model.py               # Implementación Ridge  
│   ├── lasso_model.py               # Implementación Lasso
│   └── model_evaluation.py          # Métricas de desempeño  
├── notebooks/  
│   ├── EDA_marketing.ipynb          # Análisis exploratorio  
│   ├── feature_importance.ipynb     # Visualización coeficientes  
│   └── budget_optimization.ipynb    # Simulador de presupuesto  
├── app/  
│   └── dashboard.py                 # Dashboard interactivo  
├── results/  
│   ├── best_params.json             # Mejores hiperparámetros  
│   ├── feature_importance.png       # Gráfico de coeficientes  
│   └── budget_recommendations.csv   # Recomendaciones de asignación  
└── requirements.txt  

## 📊 Datos
- Principales variables del dataset:

- social_media_spend (Inversión en redes sociales)

- google_ads_budget (Presupuesto Google Ads)

- email_marketing (Gasto en email marketing)

- seasonality_index (Índice estacional 1-100)

- customer_acquisition_cost (CAC)

- competitor_intensity (Nivel competitividad 1-5)

- Target: ROI (Return on Investment)

## 🤝 Contribución
¿Quieres mejorar nuestro modelo? Sigue estos pasos:

- Reporta issues o sugerencias

- Haz fork del repositorio

- Crea tu rama: git checkout -b feature/nueva-mejora

- Realiza tus cambios: git commit -m 'Add amazing feature'

- Haz push: git push origin feature/nueva-mejora

- Abre un Pull Request

  ¡Si te gusto, Dejame una estrella! 🚀
