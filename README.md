# 📈 Bitcoin Synthetic Data Generation using TimeGAN
## 📌 Presentation
📽️ **[View Presentation Slides](https://docs.google.com/presentation/d/1YMDNOevPmfwfIVwWTzi_FGmIROMQOZIaA2c9mut9Mtw/edit?usp=sharing)**

This project focuses on generating **realistic synthetic Bitcoin time-series data** using **TimeGAN (Time-series Generative Adversarial Network)**.  
The model learns the temporal patterns and trends from real Bitcoin market data and produces synthetic sequences that look similar to the original data.

Synthetic Bitcoin data can be useful for **data augmentation**, **experiments**, **forecasting**, and **privacy-preserving research**.

---

## 🚀 Project Highlights
✅ Generates realistic **synthetic Bitcoin time-series sequences**  
✅ Uses **TimeGAN architecture (GAN + RNN/LSTM based learning)**  
✅ Helps in **augmenting limited data** for ML model training  
✅ Useful for analysis without depending completely on real market datasets  

---

## 🧠 About TimeGAN
TimeGAN is a deep learning model designed specifically for **time-series synthetic data generation**.  
It combines:
- **Generative Adversarial Networks (GANs)** for realism  
- **Recurrent Networks (RNN/LSTM/GRU)** for temporal dependency learning  
- **Embedding & Recovery networks** to preserve feature distribution  

---

## 📊 Dataset
The dataset used is an **official Bitcoin price dataset** downloaded from a public/official source.  
It contains Bitcoin market time-series values such as:

- `Open`
- `High`
- `Low`
- `Close`
- `Volume` *(if available)*

📌 *Note:* Dataset source name can be updated once confirmed.

---

## ⚙️ Workflow / Pipeline
1. Load and preprocess Bitcoin time-series dataset  
2. Normalize and create sequences  
3. Train the TimeGAN model  
4. Generate synthetic Bitcoin sequences  
5. Compare real vs synthetic results using plots  

---

## 📈 Results
The synthetic data generated preserves:
✅ overall trends  
✅ time dependency  
✅ realistic price movement patterns  

You can compare results by plotting:
- Real Bitcoin series vs Synthetic Bitcoin series  
- Distribution similarity  

---

## 🖥️ Tech Stack
- **Python**
- **Deep Learning Framework:** *(TensorFlow / PyTorch)*
- Libraries:
  - `numpy`
  - `pandas`
  - `matplotlib`
  - `scikit-learn`

---

## ▶️ How to Run
1. Clone this repository:
```bash
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name
