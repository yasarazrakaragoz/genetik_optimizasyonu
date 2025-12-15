# genetik algoritma ile optimizasyon
Soru
Endüstriyel Boya Karışımı 
Bir fabrika, iki tür pigment karışımıyla ideal renk yoğunluğunu yakalamak istiyor. 
• Amaç fonksiyonu: 
y = 5x₁ + 2x₂ - x₁x₂ (renk kalitesi puanı) 
• Değişkenler: 
o x₁: Pigment A oranı (%) → [0, 100] 
o x₂: Pigment B oranı (%) → [0, 100] 
• Kısıtlar: 
o x₁ + x₂ = 100 (Karışım toplamı %100 olmalı) 
o x₁ ≥ 30 (A pigmenti asgari kullanılmalı) 

Proje İçeriği
- Başlangıç popülasyonu oluşturma
- Seçilim
- Çaprazlama
- Mutasyon
- Fitness hesaplama
- Grafik ile gösterme

Projenin Süreci
İlk başta gerekli kütüphane tanımlamaları yapıldıktan sonra,
değer tanımlamaları ve problem kısıtlamaları yapılmıştır.
Ardından başlangıç fonksiyonu oluşturulur.Rastgele çözümlerden ilk nesil oluşturulur(random fonksiyonu ile)
her bir birey için x₁ ≥ 30 koşulu sağlanır.
ardından seçilim işlemini yaparız ve fitness değeri yüksek olan birey seçilerek ebeveyn olur bu yöntem güçlü bireylerin hayatta kalması amacıyla yapılır.
sonra ki aşamada ise parentleri çaprazlarız ve mutasyon işlemine geçeriz . belirli olasılıkla bireylerin genleri değiştirilir.
Son aşamalardan biri olarak genetik algoritmanın ana kodunu yazarız.Bu aşamada her neslin en iyi geni saklanır ve çocuk üretimi gerçekleşir.
Fitness değerleri son aşama olan grafik değerleri için kaydedilir ve projemizdeki son kodu çalıştırdığımızda grafik ortaya çıkar.

Yaşar Azra KARAGÖZ
2212721002
