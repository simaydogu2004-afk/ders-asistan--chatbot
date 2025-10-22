# 🤖 DERS ASİSTANI CHATBOT

Bu proje, PDF ve TXT ders notlarını okuyup kullanıcının sorduğu sorulara en uygun bilgileri getiren **akıllı bir ders asistanı chatbotudur.**

Kullanıcı ister "matematik", ister "kimya" gibi bir konu seçip soru sorabilir; sistem kendi veri tabanında TF-IDF tabanlı benzerlik analizi yaparak en alakalı yanıtı üretir.

## 🚀 ÖZELLİKLER
- 📄 PDF ve TXT dosyalarını otomatik okuyabilir  
- 🧠 TF-IDF tabanlı metin vektörleştirme (retrieval system)  
- 💬 Konsol tabanlı etkileşimli chat arayüzü  
- 📊 Konu istatistikleri, dosya yeniden yükleme, sistem resetleme  
- 🔁 Tamamen **yerel olarak** çalışır (OpenAI API gerekmez)

## 📚 TEKNOLOJİLER
- **Python 3**
- **NumPy** (vektör işlemleri)
- **PyMuPDF** (PDF metin çıkarımı)
- **PyPDF2** (yedek PDF okuma)
- **Regex / TF-IDF algoritması** (metin benzerlik analizi)

## 🧩 KURULUM
1. Projeyi klonlayın:
   ```bash
   git clone https://github.com/<kullanici-adin>/Ders-Asistani-Chatbot.git
   cd Ders-Asistani-Chatbot
   ```
2. Gerekli kütüphaneleri yükleyin:
   ```bash
   pip install -r requirements.txt
   ```
3. Uygulamayı başlatın:
   ```bash
   python chatbot.py
   ```

## 💬 KULLANIM
1. Program açıldığında “Ana Menü” görünür.  
2. “💬 Chat Botunu Başlat” seçeneğini seçin.  
3. Bir konu (örneğin `matematik`) seçin veya `tüm` diyerek tüm notlarda arama yapın.  
4. Sorunuzu yazın — örnek:  
   ```
   💭 [matematik] Sorunuz: türev nedir
   ```
5. Sistem en uygun yanıtı ekranda gösterir.

## 📂 DOSYA YAPISI
```
Ders-Asistani-Chatbot/
 ├─ chatbot.py
 ├─ data/
 │   ├─ matematik.txt
 │   ├─ fizik.pdf
 │   └─ ...
 ├─ requirements.txt
 └─ README.md
```

## ✨ GELİŞTİRİCİ
- 👩‍💻 <Simay Doğu>  
AKBANK GenAI Bootcamp — 2025  
📧 <simaydogu@stu.khas.edu.tr>
