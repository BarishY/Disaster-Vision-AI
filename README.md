# 🌍 Disaster-Vision-AI: Afet Tespit ve Görsel Farkındalık Sistemi

![Python](https://img.shields.io/badge/Python-3.8%2B-3776AB?style=for-the-badge&logo=python&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-Deep%20Learning-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![EfficientNet](https://img.shields.io/badge/EfficientNetV2--S-91.13%25%20Accuracy-00599C?style=for-the-badge)
![Flask](https://img.shields.io/badge/Flask-Web%20App-000000?style=for-the-badge&logo=flask&logoColor=white)
![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)

Bu proje, yapay zeka destekli bir **Doğal Afet Tespit ve Risk Analiz Platformudur**. Gelişmiş derin öğrenme mimarileri (**EfficientNetV2-S**) kullanılarak afet görselleri saniyeler içinde analiz edilir ve interaktif bir Türkiye haritası üzerinde bölgesel risk durumları görselleştirilir.

---

### 🎥 Proje Hakkında
Sistem, kullanıcı tarafından yüklenen fotoğrafları analiz ederek **Yangın, Sel, Deprem, Çığ** veya **Normal** durum olup olmadığını tespit eder. Aynı zamanda şehirlere özel risk haritaları oluşturarak görsel farkındalık sağlar.

---

## 🚀 Özellikler

- 🤖 **Yüksek Doğruluklu Yapay Zeka:** 5 farklı sınıfı **%91.13 doğruluk (accuracy)** oranıyla tespit eder.
- ⚡ **Transfer Learning Teknolojisi:** ImageNet ağırlıklarıyla eğitilmiş **EfficientNetV2-S** mimarisi.
- 🗺️ **İnteraktif SVG Haritası:** Türkiye'nin tüm illerini kapsayan, veri odaklı dinamik risk haritası.
- ⏱️ **Hızlı Analiz:** Yüklenen fotoğrafları milisaniyeler içinde işleyen optimize edilmiş inference motoru.
- 🎨 **Modern Web Arayüzü:** Flask ve Bootstrap destekli kullanıcı dostu web platformu.

---

## 🛠️ Kurulum ve Çalıştırma

1. **Projeyi İndirin:**
   ```bash
   git clone https://github.com/BarishY/Disaster-Vision-AI.git
   cd Disaster-Vision-AI
   ```

2. **Gerekli Kütüphaneleri Yükleyin:**
   ```bash
   pip install flask torch torchvision pillow numpy scikit-learn matplotlib seaborn
   ```

3. **Uygulamayı Başlatın:**
   ```bash
   cd web
   python app.py
   ```

4. **Tarayıcıda Açın:**
   Tarayıcınızda `http://localhost:5000` adresine gidin.

---

## 📊 Model Performansı

Modelimiz zorlu doğa koşullarında test edilmiştir.

| Metrik | Değer |
|:---:|:---:|
| **Model Mimarisi** | EfficientNetV2-S |
| **Accuracy (Doğruluk)** | **%91.13** |
| **Loss** | 0.24 |
| **Epoch** | 25 (Early Stopping) |

---

## 📁 Proje Yapısı

```
Disaster-Vision-AI/
├── web/                     # Flask web uygulaması ve arayüz kodları
├── model/                   # Derin öğrenme modeli eğitim betikleri ve grafikleri
└── database/                # Veri seti yapısı (Train/Test)
```

---

## 📜 Lisans

Bu proje [MIT Lisansı](LICENSE) altında lisanslanmıştır. Copyright (c) 2026 Barış Y. (BarishY)
