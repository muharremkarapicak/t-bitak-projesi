# 🎓 Yapay Zekâ Destekli Sanal Sınıf ve Öğrenci Simülatörü

**TÜBİTAK 2209-A Üniversite Öğrencileri Araştırma Projeleri Destekleme Programı** kapsamında geliştirilen bu proje; öğretmen adaylarının hizmet öncesi eğitim sürecinde **sınıf yönetimi, kapsayıcı eğitim, kavram öğretimi, iletişim dili ve zaman yönetimi** becerilerini etkileşimli bir sanal laboratuvar ortamında deneyimleyerek geliştirmelerini amaçlamaktadır.

---

## 🎯 Projenin Amacı

Eğitim fakültelerinde öğrenim gören öğretmen adayları, öğretmenlik uygulaması (staj) dönemine kadar gerçek sınıf içi krizlerle, farklı öğrenme profillerine sahip öğrencilerin anlık tepkileriyle ve 40 dakikalık ders süresi baskısıyla yeterince karşılaşamamaktadır. 

Bu simülatör; öğretmen adaylarını aktif karar alıcı konumuna yerleştirerek teorik pedagoji bilgilerini risksiz, ölçülebilir ve geri bildirim odaklı bir dijital ortamda uygulamaya dönüştürmelerini sağlar[cite: 15].

---

## ✨ Temel Özellikler

* **👥 10 Farklı Bilişsel ve Duyuşsal Öğrenci Profili:** Sınıfta *Zeynep (aktif/sorgulayıcı)*, *Elif (başarılı/sabırsız)*, *Can (dikkati dağınık/konu saptıran)*, *Ahmet (çekingen/pasif)* gibi 10 farklı öğrenci yer alır[cite: 15]. Her öğrencinin derse olan ilgi düzeyi öğretmenin kararlarına ve müdahalelerine göre dinamik olarak güncellenir[cite: 15].
* **🏫 Öğretim Kademesine Uyarlanabilir Yapı:** **İlkokul (3-4. Sınıf)**, **Ortaokul (5-6. Sınıf)** ve **Lise (9-10. Sınıf)** profillerine göre öğrenci tepki hassasiyeti ve başlangıç ilgi düzeyleri otomatik olarak uyarlanır[cite: 15].
* **📚 Müfredat Tabanlı Çok Adımlı Vaka Senaryoları:**[cite: 15]
  * *Algoritma & Kodlama (6 Adım)*[cite: 15]
  * *Dijital Vatandaşlık & Siber Zorbalık (5 Adım)*[cite: 15]
  * *Yapay Zekâ Etiği & Kopya Krizi (6 Adım)*[cite: 15]
  * *Kapsayıcı Eğitim & Akran Zorbalığı (5 Adım)*[cite: 15]
* **⏱ Gerçekçi 40 Dakikalık Ders Süresi ve Kota Yönetimi:** Her pedagojik kararın, öğrenciye söz vermenin (`-2 dk`) ve göz temasıyla dikkat çekmenin (`-1 dk`) bir zaman maliyeti vardır[cite: 15]. Ders süresi dolduğunda senaryo tamamlanmamışsa oturum kilitlenir ve sistem dersi verimsiz sayarak pedagojik ceza uygular[cite: 15].
* **🛠 Etkileşimli Sınıf Araçları:** Kara tahtaya anlık not yazma, mini kavrama yoklaması başlatma, sınıfı alkışlatma ve gerçek zamanlı sentezlenen WAV sınıf ses efektleri (okul zili, tebeşir, uğultu, olumlu/uyarı tonları) içerir[cite: 15].
* **📋 Otomatik Pedagojik Değerlendirme Karnesi ve JSON Çıktısı:** Oturum boyunca sergilenen performans **Sınıf Yönetimi, Kapsayıcılık, Kavram Öğretimi** ve **İletişim Dili** boyutlarında puanlanır[cite: 15]; ders sonunda görsel karne gösterilir ve tüm oturum verileri `oturum_raporu.json` olarak dışa aktarılır[cite: 15].

---

## 🛠 Kullanılan Teknolojiler

* **Programlama Dili:** Python 3[cite: 15]
* **Grafik Kullanıcı Arayüzü (GUI):** Tkinter & ttk[cite: 15]
* **Ses Sentezleme Motoru:** Python standart kütüphaneleri (`wave`, `struct`, `math`, `winsound`) ile harici ses dosyasına ihtiyaç duymadan gerçek zamanlı WAV üretimi[cite: 15]
* **Veri Kaydı ve Raporlama:** JSON (`json`, `datetime`)[cite: 15]

---

ve projemin youtube videosu linki: https://youtu.be/bCarDdLheUw?si=B3V393ZRuP18-BVJ
