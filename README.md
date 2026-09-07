# 💖 Crystal Animated Heart & Audio Visualizer

> Three.js, Custom GLSL Shader'lar ve Web Audio API kullanılarak geliştirilmiş, müzik ritmiyle senkronize dönen 3D kristal kalp animasyonu.

![Status](https://img.shields.io/badge/Status-Active-ff69b4?style=for-the-badge)
![License](https://img.shields.io/badge/License-MIT-blue?style=for-the-badge)
![Three.js](https://img.shields.io/badge/Three.js-000000?style=for-the-badge&logo=three.js&logoColor=white)
![GLSL](https://img.shields.io/badge/GLSL-555555?style=for-the-badge&logo=opengl&logoColor=white)
![GSAP](https://img.shields.io/badge/GSAP-88CE02?style=for-the-badge&logo=greensock&logoColor=white)

🌐 **Canlı Demo / Live Web Application:** [https://davut-eren-ekici.github.io/Animated-heart/](https://davut-eren-ekici.github.io/Animated-heart/)

---

## 📌 Proje Hakkında (About)

**Animated Heart**, interaktif 3D grafik teknolojilerini müzik görselleştirme (audio visualization) ile birleştiren etkileyici bir web deneyimidir. 

Uygulama merkezinde yer alan 3D kalp modeli, arka planda çalan müziğin ortalama frekans analizine (`AudioAnalyser`) göre dinamik olarak tepki verir. Müzik başladığında kamera açıları, kalbin dönme hızı ve etraftaki renkli parçacık efektleri müziğin ritmine uyumlu şekilde hareket eder.

---

## ✨ Öne Çıkan Özellikler (Features)

- 🎨 **3D GLTF Model & Matcap Material:** Yüksek kaliteli kristal dokulu 3D kalp modeli yüklemesi.
- ⚡ **Özel GLSL Shader'lar (Vertex & Fragment):**
  - **Heart Particle System:** Kalp formunda matematiksel eğrilerle dağlan 1500+ renkli parçacık.
  - **Floating Snow Effect:** Kalbin etrafında süzülen 550+ büyüleyici parçacık efekti.
- 🎵 **Web Audio API & Ses Analizi:** Çalan müziğin frekans verisini anlık olarak işleyip animasyon hızına ve kamera ivmesine dönüştürme.
- 🎥 **İnteraktif Kamera Hareketi:** GSAP entegrasyonu ile fare (mouse) hareketlerine yumuşak tepki veren dinamik kamera bakış açısı.
- 🚀 **Instanced Rendering:** Yüksek performans ve akıcı 60 FPS deneyimi için optimize edilmiş `InstancedBufferGeometry` kullanımı.

---

## 🛠️ Teknolojiler (Tech Stack)

- **Three.js (v0.135.0):** 3D Sahne, Kamera, Işık, GLTFLoader ve WebGL işleme motoru.
- **GLSL (OpenGL Shading Language):** Ekran kartı üzerinde çalışan custom shader yazılımları.
- **GSAP (GreenSock Animation Platform):** Kamera geçişleri ve buton opaklık animasyonları.
- **Web Audio API:** Ses yükleme, çalma ve frekans analizi (`Three.AudioAnalyser`).
- **HTML5 & CSS3:** Tipografi ve duyarlı (responsive) ekran yerleşimi.

---

## 🚀 Yerel Kurulum (Local Setup)

1. **Repoyu klonlayın:**
   ```bash
   git clone [https://github.com/Davut-Eren-Ekici/Animated-heart.git](https://github.com/Davut-Eren-Ekici/Animated-heart.git)