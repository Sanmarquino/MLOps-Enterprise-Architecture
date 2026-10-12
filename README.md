# 🚀 Enterprise MLOps Architecture & Lifecycle

> **Portafolio integral de Ingeniería MLOps.** Transformando modelos de Machine Learning experimentales en sistemas de software escalables, reproducibles, auditables y automatizados.

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Scikit-Learn](https://img.shields.io/badge/scikit--learn-%23F7931E.svg?style=for-the-badge&logo=scikit-learn&logoColor=white)
![MLOps](https://img.shields.io/badge/MLOps-FF6F00?style=for-the-badge&logo=mlflow&logoColor=white)
![Docker](https://img.shields.io/badge/docker-%230db7ed.svg?style=for-the-badge&logo=docker&logoColor=white)
![Google Cloud](https://img.shields.io/badge/GoogleCloud-%234285F4.svg?style=for-the-badge&logo=google-cloud&logoColor=white)

## 📌 Sobre este Proyecto

Este repositorio documenta y estructura el desarrollo completo de una **Arquitectura MLOps End-to-End**. El objetivo es trascender el clásico "Jupyter Notebook" para aplicar prácticas de Ingeniería de Software al Machine Learning, garantizando:

*   **Trazabilidad y Reproducibilidad:** Gestión de dependencias, aislamiento de semillas de aleatoriedad y auditoría criptográfica de datasets mediante **hash SHA-256**.
*   **Calidad y Prevención de Riesgos:** Diseño de *Quality Gates*, validación de contratos de datos (*Schemas*) y evasión estricta de *Data Leakage* (Fugas de información).
*   **Arquitectura Modular:** Separación rigurosa de responsabilidades (`config`, `data`, `features`, `modeling`, `inference`, `logs`, `tests`).
*   **Monitoreo en Producción:** Implementación del **Índice de Estabilidad Poblacional (PSI)** para la detección proactiva de *Data Drift*.

---

## 🗺️ Roadmap de la Arquitectura (Módulos)

El repositorio está estructurado siguiendo el ciclo de vida completo de un sistema de Machine Learning en producción. A medida que la arquitectura madura, se irán integrando nuevas capas de complejidad:

- [x] **Módulo 1: Fundamentos y Arquitectura MLOps**
  - Diferenciación entre DS, MLE y MLOps.
  - Diseño de estructura de carpetas modular.
  - Implementación de logs, configuración YAML y preprocesamiento con `Pipelines`.
- [x] **Módulo 2: Datos, Features y Reproducibilidad**
  - Transformaciones relacionales e integridad referencial (PK/FK).
  - Feature Engineering temporal (ventanas móviles, recencia, estacionalidad cíclica).
  - Detección de *Drift* y simulación de escenarios fuera de muestra (*Out-of-Time*).
- [ ] **Módulo 3: Experimentación y Gestión de Modelos** *(Próximamente)*
- [ ] **Módulo 4: Pipelines y Orquestación de Machine Learning** *(Próximamente)*
- [ ] **Módulo 5: APIs y Contenedores para Machine Learning** *(Próximamente)*
- [ ] **Módulo 6: MLOps en Google Cloud** *(Próximamente)*
- [ ] **Módulo 7: Automatización CI/CD para Machine Learning** *(Próximamente)*
- [ ] **Módulo 8: Monitoreo y Operación de Modelos** *(Próximamente)*
- [ ] **Módulo 9: Arquitectura MLOps End-to-End** *(Próximamente)*

---

## 🛠️ Stack Tecnológico y Conceptos Clave Implementados

*   **Lenguajes y Core:** Python, Pandas, NumPy, Scikit-learn.
*   **Ingeniería de Software en ML:** Programación Orientada a Objetos (OOP), Unit Testing (`pytest`), Logging dinámico.
*   **Gestión de Artefactos:** Serialización con `joblib`, *Experiment Tracking* persistido en JSON.
*   **Estrategia de Validación:** Validación cruzada estratificada y splits temporales robustos para entornos de reentrenamiento periódico.

---

## 👨‍💻 Autor

**Daniel Humberto Llanos Llanos**  
*Data Scientist & Statistician | MLOps Engineer*

Apasionado por la analítica de datos, la inteligencia artificial y la construcción de sistemas predictivos robustos que generen impacto real en negocio.