📘 PYTHON-DEV RAPORU
📌 Proje Hakkında

Bu proje, Python kullanılarak geliştirilen bir müşteri veri analizi ve fatura hesaplama uygulamasını içermektedir. Çalışma, Google Colab ortamında hazırlanmış ve PDF formatına dönüştürülmüştür.

Proje, temel programlama yapılarının yanı sıra veri analizi mantığını da içermektedir.

🎯 Amaç

Bu çalışmanın amacı:

Python temel yapılarını uygulamalı olarak kullanmak
Gerçek hayat senaryosu üzerinden müşteri verisi analiz etmek
Fatura hesaplama ve müşteri segmentasyonu yapmak
🧩 Proje İçeriği
🔹 1. Veri Yapıları ve Temel Mantık

Bu bölümde:

Değişken tanımlama (string, float, int, boolean)
Liste (list) ve sözlük (dictionary) kullanımı
Koşullu ifadeler (if-else)

Müşteri bilgileri tanımlanmış ve şu kontrol yapılmıştır:

Aylık ücret 500 TL üzerindeyse veya sadakat süresi 24 aydan fazlaysa müşteri VIP olarak belirlenir

Ayrıca:

İsimler büyük harfe çevrilmiştir
Rastgele müşteri ID oluşturulmuştur
🔹 2. Fonksiyonlar, Döngüler ve Analiz

Bu bölümde daha ileri konular kullanılmıştır:

Fonksiyon tanımlama (tutar_hesapla)
Döngüler (for loop)
Liste içinde sözlük yapısı
Kütüphane kullanımı (math, datetime, tabulate)

Fatura hesaplama:

Aylık ücret üzerine %20 KDV eklenmiştir
Sonuçlar yukarı yuvarlanmıştır

Her müşteri için:

Güncel tarih alınmıştır
Churn (müşteri kaybı riski) analizi yapılmıştır
Sadakat < 6 ay veya aktif değilse → riskli
📊 Çıktılar

Program çalıştırıldığında:

Müşteri ID oluşturulur
Müşteri faturaları hesaplanır
Sonuçlar tablo halinde gösterilir

Örnek çıktı:
[GÖKTUĞÖZDEMİR446726.ipynb - Colab.pdf](https://github.com/user-attachments/files/27901065/GOKTUGOZDEMIR446726.ipynb.-.Colab.pdf)

Ahmet → 540 TL
Ayşe → 720 TL
Mehmet → churn riski var
Zeynep → churn riski var
🔍 Ek Analiz

Projede ayrıca:

Tekrarlayan hizmetler kaldırılmıştır
Benzersiz hizmet listesi elde edilmiştir

Sonuç:

internet
mobil
tv
bulut
⚙️ Kullanılan Teknolojiler
Python
Google Colab
random, math, datetime, tabulate kütüphaneleri
✅ Sonuç

Bu proje ile:

Python temel ve orta seviye konular pekiştirilmiştir
Veri yapıları ve fonksiyon kullanımı öğrenilmiştir
Gerçek bir senaryo üzerinden analiz yapılmıştır
📎 Dosya

PDF çıktısına buradan ulaşabilirsiniz:
👉 (https://github.com/goktu61)

✍️ Hazırlayan

Göktuğ Özdemir
