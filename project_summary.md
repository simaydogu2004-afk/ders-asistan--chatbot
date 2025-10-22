# 🎓 Proje Özeti — DERS ASİSTANI CHATBOT

## 💡 PROBLEM TANIMI
Öğrenciler sınav dönemlerinde farklı kaynaklardan not toplar, ancak hızlı şekilde bilgiye ulaşmakta zorlanır.  
Bu proje, öğrencilerin kendi ders notlarından **soru sorarak bilgi alabilmesini** sağlayan bir akıllı sistem sunar.

## 🧠 ÇÖZÜM YAKLAŞIMI
Proje, PDF ve TXT dosyalarını okuyup TF-IDF (Term Frequency–Inverse Document Frequency) algoritmasıyla metinleri vektörel olarak temsil eder.  
Kullanıcı bir soru girdiğinde sistem:
1. Soru kelimelerini işler (tokenize eder)  
2. Her belgedeki benzerlik puanını hesaplar (cosine similarity)  
3. En alakalı belgeyi ve ilgili cümleleri kullanıcıya gösterir.  

Böylece kullanıcı kendi notlarından "anlamlı yanıtlar" alır.

## ⚙️ TEKNOLOJİLER
- **Python 3**
- **NumPy** – vektör hesaplamaları için  
- **PyMuPDF** – PDF metin çıkarımı  
- **PyPDF2** – yedek PDF okuyucu  
- **Regex** – metin temizleme  
- **Temel NLP (TF-IDF)** – bilgi arama sistemi

## 💬 SONUÇLAR
- Sistem PDF + TXT notları başarıyla okuyabiliyor  
- Her konu için en alakalı yanıtı getiriyor  
- Ekstra API maliyeti yok (tamamen offline çalışıyor)  
- Kod tamamen modüler ve açıklamalı  

## 🚀 GELECEK GELİŞTİRMELER
- Streamlit veya Gradio arayüzü eklenebilir  
- OpenAI / Gemini API ile cevaplar daha doğal hale getirilebilir  
- Konu özetleme (summarization) özelliği eklenebilir  

## 👩‍💻 GELİŞTİRİCİ
**<Simay Doğu>**  
AKBANK Global AI Hub — GenAI Bootcamp (2025)
