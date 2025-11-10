Traffic Vision AI - Sistema Avanzado de Análisis de Tráfico

![Demo](https://github.com/jhedai/traffic-vision-ai/raw/main/demo.gif)
![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)
![YOLOv8](https://img.shields.io/badge/YOLOv8-Ultralytics-orange.svg)
![OpenCV](https://img.shields.io/badge/OpenCV-4.0+-green.svg)
![License](https://img.shields.io/badge/License-MIT-yellow.svg)

Descripción

Sistema de inteligencia artificial para análisis de tráfico en tiempo real que combina detección de objetos, tracking multi-objeto, cálculo de velocidades y análisis de flujos vehiculares. Optimizado para videos verticales 9:16 con interfaz elegante y profesional.

Licencia

Este proyecto está licenciado bajo la Licencia MIT.

Puedes:
-Usar comercialmente
-Modificar y distribuir
-Usar en proyectos privados
-Incorporar en software propietario

Se solicita amablemente:
-Dar crédito apropiado a JhedAI y Julio Hofflinger
-Incluir referencia al repositorio original
-Para implementaciones comerciales significativas, considerar contactarnos

Para soluciones personalizadas de Computer Vision, contacta a: julio@jhedai.com

Características Principales

-Detección Multi-Clase: Vehículos, camiones, motocicletas, autobuses
-Tracking Persistente: IDs únicos con seguimiento entre frames
-Cálculo de Velocidades: Estimación en tiempo real (km/h)
-Conteo Bidireccional: Análisis de flujos IN/OUT
-Interfaz Elegante: Etiquetas translúcidas y diseño profesional
-Anti-Solapamiento: Sistema inteligente de posicionamiento de etiquetas
-Optimizado Vertical: Especialmente diseñado para formato 9:16

Tecnologías Utilizadas

- YOLOv8 (Ultralytics) - Detección de objetos en tiempo real
- OpenCV - Procesamiento de video y computer vision
- NumPy - Cálculos numéricos y manipulación de arrays
- Google Colab - Entorno de ejecución y experimentación

Instalación Rápida

```bash
Clonar repositorio
git clone https://github.com/jhedai/traffic-vision-ai.git
cd traffic-vision-ai

Instalar dependencias
pip install -r requirements.txt

Ejecutar análisis
python main.py
