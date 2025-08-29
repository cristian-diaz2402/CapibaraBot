# 🐹 Capibara Bot

![Status](https://img.shields.io/badge/status-in%20progress-yellow)
![License](https://img.shields.io/badge/license-MIT-blue)
![Platform](https://img.shields.io/badge/platform-ESP32-orange)
![App](https://img.shields.io/badge/app-Android-green)
![ML](https://img.shields.io/badge/Machine%20Learning-enabled-purple)

---

## 📖 Descripción

**Capibara Bot** es un proyecto de **Interacción Humano-Computadora (HCI)** desarrollado en conjunto con compañeros de universidad.  
El objetivo fue ensamblar un robot desde cero, integrando hardware, software móvil y un modelo de Machine Learning para crear un sistema interactivo y autónomo. Cuenta con animaciones, sonido, interacciones y feedback.

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
- Publicado en **[Hugging Face Space - Haz Clic aquí para ver como funciona el modelo](https://huggingface.co/spaces/cristiandiaz2403/CapibaraModel)** como servicio API  
- Backend propio que permite consumir la API y procesar los resultados en el robot  

---

## 🏗️ Arquitectura del proyecto

[APK - App móvil] ⇆ [Bluetooth] ⇆ [ESP32 + Hardware] ⇆ [Backend propio] ⇆ [Hugging Face API]

---

## 🚀 Estado del proyecto

Actualmente el proyecto se encuentra en desarrollo pasivo, con prototipo funcional y primeras pruebas de integración entre hardware, app y modelo de Machine Learning.  

---

## 📎 Anexos
![Imagen de WhatsApp 2025-08-28 a las 23 02 17_41cf0c61](https://github.com/user-attachments/assets/56e5a864-d239-4ce2-9613-38d1947be270)
![Imagen de WhatsApp 2025-08-28 a las 23 02 25_7e85d578](https://github.com/user-attachments/assets/d1caeb2c-13ea-4384-82fb-9cd66bf26bf1)
![Imagen de WhatsApp 2025-08-28 a las 23 02 25_fa3598f3](https://github.com/user-attachments/assets/3904aec3-5be0-4c4b-8ed2-2c11ea43b551)
![Imagen de WhatsApp 2025-08-28 a las 23 02 25_b60e2dac](https://github.com/user-attachments/assets/b873e5c0-1589-4a6a-9649-c148c2d668e4)
![Imagen de WhatsApp 2025-08-28 a las 23 04 17_19e0a1ac](https://github.com/user-attachments/assets/c24038ba-4923-4c34-9566-3cb87972857b)




