<img width="7680" height="4320" alt="lavanta-maps-vol-6-2d-3840x2160 (6)" src="https://github.com/user-attachments/assets/875d9210-c03c-4f94-bb97-578b1b46d5d2" />
<img width="7680" height="4320" alt="lavanta-maps-vol-6-3d-3840x2160 (3)" src="https://github.com/user-attachments/assets/77ab77f7-c664-4a76-87b5-07722787dd83" />
# lavantamap
# 🗺️ Lavanta Maps Vol 6 — 2.5D Etkileşimli Şehir & Ada Haritası Oluşturucu

Tarayıcı üzerinde herhangi bir kurulum gerektirmeden çalışan; organik adalar, biyomlar, kavisli yol ağları, su üstü köprüler ve 3D yapılar tasarlamanıza olanak tanıyan etkileşimli harita oluşturma uygulaması.

🔗 **Canlı Uygulama:** [https://15aliozkan.github.io/lavantamap/](https://15aliozkan.github.io/lavantamap/)

---

## ✨ Öne Çıkan Özellikler

* **🏝️ Arazi, Su & Biyom Şekillendirme:** Poligon, serbest çizim kalemi ve kıyı fırçası ile ada oluşturma veya denize dönüştürme; iç göller, dere kanalları, ormanlık alanlar ve yükseltili sıradağlar ekleme.
* **🎲 Tek Tıkla Prosedürel Üretim:** Otomatik rastgele adalar, geniş biyom kümeleri ve alçak katlı ana merkez ile çevre mahallelerden oluşan bağlantılı şehir ağları kurma.
* **🛣️ Akıllı Ulaşım Ağı & 3D Köprüler:** Otoyol, ana cadde, sokak ve demiryolu çizimi; mevcut yollara sınırdan otomatik kavşak bağlantısı ve su geçişlerinde otomatik 3D köprü rampaları.
* **🏙️ 3D Yapılar & Özel Tesisler:** Yola otomatik hizalanan ve birbirleriyle çakışmayan 3D binaların yanı sıra Belediye Binası (`U`, `L`, `I` plan), Hastane, Okul Kampüsü, Şehir Parkı, Stadyum ve Kent Meydanı yerleştirme.
* **🧊 Kesintisiz 2D ↔ 3D Kamera Geçişi:** `0°` kuşbakışı 2D görünümden `65°` 3D izometrik açıya kadar hassas eğim ve dönüş kontrolü; gece modunda yanan pencere ışıkları.
* **🚗 Otonom Trafik Simülasyonu:** Yol ağı üzerinde çift yönlü hareket eden ve hızı ayarlanabilen canlı araç trafiği.
* **📐 Gerçek Zamanlı Yüzölçümü (`km²`) & Hafıza:** Birbirine bağlanan adaların toplam alanını anlık hesaplama, işlem geçmişi takibi, `Ctrl+Z` geri alma desteği ve tarayıcı içi otomatik kayıt.
* **📸 Yüksek Çözünürlüklü PNG Dışa Aktarma:** Mevcut 3D kamera açısından veya tüm haritayı kapsayan 2D kuşbakışı modunda `HD` ile `4K` arası çözünürlüklerde, isteğe bağlı harita lejantı ile görsel indirme.

---

## 🎮 Kontroller ve Kısayollar

| Kontrol / Tuş | İşlev |
| :--- | :--- |
| **Sol Tık (Sürükle / Tıkla)** | Seçili araca göre çizim yapma veya haritada gezinme |
| **Sağ Tık (Sürükle)** | Haritayı döndürme ve 2D ↔ 3D kamera eğimini ayarlama |
| **Tekerlek (Scroll)** | Yakınlaştırma ve uzaklaştırma |
| **`W` `A` `S` `D` / Yön Tuşları** | Harita üzerinde akıcı gezinme |
| **Çift Tık / Sağ Tık / `Enter`** | Çok noktalı çizimi (ada, göl, yol, bölge) tamamlama |
| **`Esc`** | Aktif çizimi iptal etme |
| **`Ctrl + Z`** | Son yapılan işlemi geri alma |

---

## 🛠️ Kullanılan Teknolojiler

* **HTML5 Canvas 2D API** (Özel 2.5D izometrik projeksiyon ve derinlik sıralamalı prizma çizim motoru)
* **Vanilla JavaScript (ES6+)** (Marching Squares kontur algoritması, OBB çakışma kontrolü ve prosedürel harita üretimi)
* **Tailwind CSS & Liquid Glass UI** (Gündüz/Gece uyumlu yarı saydam arayüz)
