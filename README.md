# 🌟 DS Setups

<p align="center">
  <img src="https://img.shields.io/badge/Docker-Ready-blue?logo=docker" />
  <img src="https://img.shields.io/badge/TensorFlow-Supported-orange?logo=tensorflow" />
  <img src="https://img.shields.io/badge/Machine%20Learning-Enabled-green?logo=python" />
</p>

---

## 🚀 ¿Qué es **DS_Setups**?

Este repositorio contiene **entornos listos para Data Science**, diseñados especialmente para:

- 🧠 **Machine Learning (ML)**  
- 🤖 **Deep Learning (DL)**  
- 🎮 **Reinforcement Learning (RL)**  

La meta es **ahorrar tiempo y dolores de cabeza** al configurar entornos de desarrollo, asegurando que todo sea **reproducible, modular y acelerado por GPU** cuando esté disponible.

---

## ⚙️ Requisitos previos

Antes de comenzar, necesitas tener:

- [Docker](https://docs.docker.com/get-docker/) (20.10+)  
- [Docker Compose](https://docs.docker.com/compose/) (v2+)  
- [NVIDIA Drivers](https://www.nvidia.com/Download/index.aspx) actualizados (si usas GPU)  
- [NVIDIA Container Toolkit](https://docs.nvidia.com/datacenter/cloud-native/container-toolkit/install-guide.html) para soporte CUDA en Docker  

---

## 🔧 Instalación

Clona este repositorio:

```bash
git clone https://github.com/cesarcherre848/ds_setups.git
cd ds_setups
```

---

## 🔹 TF_Framework (Tensorflow)

Los entornos de **TensorFlow 2** en este repositorio están preparados para que los *resources* (capas personalizadas, escaladores, preprocesadores, etc.) estén **100% optimizados para la compilación del grafo** (`tf.function`), garantizando un rendimiento de nivel producción.  

### ✅ Ventajas principales:
- ⚡ **Ejecución optimizada en grafo** → tus modelos se benefician de compilación JIT y graph execution.  
- 🎯 **Compatibilidad total con GPU y XLA** → soporte CUDA/cuDNN para acelerar entrenamiento e inferencia.  
- 🔄 **Capas de preprocesamiento integradas** → transformaciones como `RobustScaler`, `Normalization` y otras se ejecutan dentro del grafo.  
- 📦 **Entornos reproducibles** → mismos resultados independientemente de la máquina o SO.  
- 🛠️ **Soporte extendido para ML y RL** → listo para usarse con librerías como `tf-agents` o integraciones de `keras`.  

Con esto, el flujo de entrenamiento e inferencia evita overhead de ejecución en *eager mode* y aprovecha al máximo el compilador de TensorFlow.