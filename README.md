# YOLOv8 + Hareket Algılama Sistemi

Bu proje, bir video akışı üzerinde [Ultralytics YOLOv8](https://github.com/ultralytics/ultralytics) ile nesne algılama ve [OpenCV](https://opencv.org/) ile hareket algılama işlemlerini birleştirir. Sistem, her nesnenin hareketli mi yoksa sabit mi olduğunu belirler ve görselleştirir.

---

## 🚀 Özellikler

- ✅ YOLOv8 ile nesne algılama
- ✅ OpenCV ile arka plan çıkarma (hareket algılama)
- ✅ Hareketli nesneleri kırmızı, sabit nesneleri yeşil kutu ile işaretleme
- ✅ Gerçek zamanlı video işleme (videodan veya kameradan)

---

## 📦 Gereksinimler

- Python 3.8+
- Ultralytics (YOLOv8)
- OpenCV

Kurulum:
```bash
pip install ultralytics opencv-python
