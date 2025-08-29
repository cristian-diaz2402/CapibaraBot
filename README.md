# 🐹 Capibara Bot

![Status](https://img.shields.io/badge/status-in%20progress-yellow)
![License](https://img.shields.io/badge/license-MIT-blue)
![Platform](https://img.shields.io/badge/platform-ESP32-orange)
![App](https://img.shields.io/badge/app-Android-green)
![ML](https://img.shields.io/badge/Machine%20Learning-enabled-purple)

---

## 📖 Descripción

**Capibara Bot** es un proyecto de **Interacción Humano-Computadora (HCI)** desarrollado en conjunto con compañeros de universidad.  
El objetivo fue ensamblar un robot desde cero, integrando hardware, software móvil y un modelo de Machine Learning para crear un sistema interactivo y autónomo.

---

## ⚙️ Hardware utilizado

- **ESP32** → Microcontrolador principal  
- **Driver L298N** → Control de motores DC  
- **Motores DC**  
- **Baterías de litio recargables**  
- **Protoboard y cableado electrónico**  

---

## 📱 Aplicación móvil

- Desarrollada en **MIT App Inventor**  
- Generada en formato **APK (Android)**  
- Conexión con el robot mediante **Bluetooth**  

---

## 🔗 Conexión Hardware - Software

- Comunicación entre la aplicación móvil y el ESP32 vía **Bluetooth**  
- Programación del ESP32 realizada con **Arduino IDE**  
- El firmware se carga al microcontrolador mediante **USB**  

---

## 🤖 Machine Learning

- Implementación de un **modelo de regresión lineal**  
- Modelo **preentrenado**, exportado en formato **`.joblib`**  
- Publicado en **[Hugging Face Spaces](https://huggingface.co/spaces/cristiandiaz2403/CapibaraModel)** como servicio API  
- Backend propio que permite consumir la API y procesar los resultados en el robot  

---

## 🏗️ Arquitectura del proyecto

[APK - App móvil] ⇆ [Bluetooth] ⇆ [ESP32 + Hardware] ⇆ [Backend propio] ⇆ [Hugging Face API]


---

## 🚀 Estado del proyecto

Actualmente el proyecto se encuentra en desarrollo pasivo, con prototipo funcional y primeras pruebas de integración entre hardware, app y modelo de Machine Learning.  

---