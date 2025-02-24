# 🛡️ CIC-IoT-DIAD-2024: IoT Device Identification & Anomaly Detection  
🚀 **Using Diffusion Models & BiRNN**  

## 📌 Overview  
This project presents an advanced approach for **IoT device identification** and **cyberattack detection** using **Diffusion Models for oversampling** combined with a **Bi-directional Recurrent Neural Network (BiRNN) classifier**.  

The project is based on the **CIC IoT-DIAD 2024** dataset, a **comprehensive cybersecurity dataset** consisting of **105 IoT devices** and covering **33 types of attacks**, classified into seven major categories:  

- **🛑 DDoS Attacks**  
- **⛔ DoS Attacks**  
- **🔍 Reconnaissance (Recon) Attacks**  
- **🌐 Web-based Attacks**  
- **🔑 Brute Force Attacks**  
- **🎭 Spoofing Attacks**  
- **🤖 Mirai Attacks**  

The primary goal is to **enhance IoT security** by leveraging state-of-the-art **generative AI models**, achieving **99% accuracy** in device classification and anomaly detection.  

---

## 🚀 Methodology  

### 📡 Dataset: **CIC IoT-DIAD 2024**  
✔ **105 IoT devices**  
✔ **33 different types of attacks**  
✔ **Dual-function: Device identification & anomaly detection**  

### 🧠 AI Techniques Used  

#### 1️⃣ Diffusion Models for **Oversampling**  
Instead of traditional **data augmentation techniques**, **diffusion models** were used for **oversampling** to **balance the dataset** and improve classification performance.  
The following **nine diffusion models** were applied:  

✅ **UNet**  
✅ **DDIM (Denoising Implicit Diffusion Models)**  
✅ **DDPM (Denoising Probabilistic Diffusion Models)**  
✅ **SBGM (Score-Based Generative Models)**  
✅ **LDM (Latent Diffusion Models)**  
✅ **Conditional Diffusion Models**  
✅ **EBM (Energy-Based Models)**  
✅ **DiffAutoencoder**  
✅ **Variational Diffusion Models**  

#### 2️⃣ BiRNN for **Classification**  
After oversampling with **diffusion models**, a **BiRNN classifier** was used to:  

✔ **Analyze temporal dependencies** in IoT network traffic  
✔ **Improve classification accuracy**  
✔ **Enhance anomaly detection effectiveness**  

---

## 📊 Results  

The combination of **diffusion-based oversampling** and **BiRNN classification** significantly improved performance, achieving:  

✅ **99% accuracy** in **attack detection** 📈  
✅ **Demonstrating the power of diffusion models** in **generating high-quality synthetic samples**, which is particularly beneficial for **cybersecurity datasets** where attack instances may be **imbalanced or scarce**.  
✅ **Highlighting the strength of BiRNN with diffusion models**, as the integration of **diffusion-based oversampling** with **BiRNN** improved **feature representation**, enhanced **temporal pattern learning**, and contributed to **more robust anomaly detection**.  

---

## 📥 Download Dataset  
The **CIC IoT-DIAD 2024** dataset can be downloaded from the **Canadian Institute for Cybersecurity** [🔗 Here](https://www.unb.ca/cic/datasets/index.html).  

---
