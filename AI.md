# AI Kullanım Raporu

## Kullanılan Yapay Zeka Araçları
- Claude AI
- ChatGPT
- Google Antigravity

---

# Proje Hakkında

Bu proje, “That Tiny Recursive Room” oyunundan ilham alınarak geliştirilen web tabanlı bir puzzle-platform oyunudur.

Kullanılan teknolojiler:
- HTML5
- CSS
- JavaScript

Yapay zeka araçları;
- level tasarımı fikirleri,
- hata düzeltme,
- oyun mekanikleri geliştirme,
- çarpışma sistemi iyileştirmeleri,
- zorluk dengesi,
- kullanıcı deneyimi önerileri

konularında yardımcı amaçlı kullanılmıştır.

Tüm kod entegrasyonları, düzenlemeler ve test süreçleri tarafımdan gerçekleştirilmiştir.

---

# Yapay Zeka Destekli Geliştirme Süreci

## Prompt 1 — Oyun Yapısı ve Level Fikirleri

### Prompt
“That Tiny Recursive Room” oyununa benzer şekilde, aynı oda içerisinde farklı mekaniklere sahip 10 level nasıl tasarlanabilir?

### AI Cevap Özeti
Şunlar önerildi:
- Aynı odanın farklı kurallarla tekrar kullanılması
- Her level için farklı bir mekanik oluşturulması
- Puzzle odaklı ilerleme sistemi

Önerilen level fikirleri:
1. Normal level
2. Bad Weather
3. Ters kontrol
4. Hiçbir şey yapmadan ilerleme
5. Telekinesis
6. Sahte kapı
7. Mouse ile oyuncu taşıma
8. Sınırlı zıplama
9. Kapıyı çalma
10. Mouse ile aktif edilen bitiş

### Projede Kullanımı
Oyunun genel level yapısı bu fikirler temel alınarak oluşturuldu.

---

## Prompt 2 — Oyunun Zorluğunu Artırma

### Prompt
Oyun orijinal ilham alınan oyuna göre fazla kolay görünüyor. Platformlar ve dikenler daha zorlayıcı olmalı.

### AI Cevap Özeti
Önerilen değişiklikler:
- Daha fazla platform
- Daha fazla diken yerleşimi
- Daha dar atlama alanları
- Daha karmaşık rota tasarımı
- Daha gizemli ipuçları

### Projede Kullanımı
Oyun odası yeniden düzenlendi:
- Platform sayısı artırıldı
- Yeni diken alanları eklendi
- Daha zor platform geçişleri oluşturuldu

---

## Prompt 3 — Hint Sistemi Düzenlemesi

### Prompt
İpuçları fazla açık. Oyuncu isterse ipuçlarını görebilmeli.

### AI Cevap Özeti
Önerilen sistem:
- Ayrı bir hint butonu
- Başlangıçta gizli ipuçları
- Görsel rehberlerin sadece hint açılırsa görünmesi

### Projede Kullanımı
Şunlar eklendi:
- Açılıp kapanabilen hint sistemi
- Başlangıçta gizli hintler
- Koşullu görsel ipuçları

---

## Prompt 4 — Oyuncunun Platform ile Birlikte Hareket Etmesi

### Prompt
Platform taşınırken oyuncu da platformla birlikte hareket etmeli.

### AI Cevap Özeti
Önerilen çözüm:
- Platform hareket miktarının oyuncuya uygulanması
- Oyuncu ve platform hareketlerinin senkronize edilmesi

### Projede Kullanımı
Hareketli platform sistemi geliştirildi ve oyuncunun platform üzerinde taşınması sağlandı.

---

## Prompt 5 — Mouse ile Taşıma Çarpışma Sorunu

### Prompt
Mouse ile oyuncu taşınırken engellere çarpınca karakter aniden farklı yerlere sıçrıyor.

### AI Cevap Özeti
Önerilen çözümler:
- Daha doğru çarpışma çözümü
- MTV (Minimum Translation Vector) sistemi
- Ani ışınlanma etkisinin kaldırılması

### Projede Kullanımı
Mouse ile taşıma sistemi daha doğal fizik davranışı verecek şekilde güncellendi.

---

## Prompt 6 — Kapı Çalma Mekaniği

### Prompt
Oyuncu kapıyı kaç kere çalması gerektiğini bilmemeli.

### AI Cevap Özeti
Önerilen sistem:
- Rastgele çalma sayısı
- Sayaç bilgisinin kaldırılması
- Oyuncunun deneyerek çözmesi

### Projede Kullanımı
9. level güncellendi:
- Rastgele 2–5 arası çalma sayısı eklendi
- Ekrandaki sayaç kaldırıldı
- Deneysel çözüm mantığı oluşturuldu

---

## Prompt 7 — Final Level Mekaniği

### Prompt
Son levelde oyuncu değil, buton farklı platformlara taşınmalı.

### AI Cevap Özeti
Önerilen sistem:
- Her tıklamada butonun başka platforma gitmesi
- Oyuncunun üst platformları kullanmak zorunda kalması
- Kademeli puzzle ilerleyişi

### Projede Kullanımı
10. level yeniden tasarlandı:
- Buton her tıklamada başka platforma geçti
- Oyuncu butonu takip etmek zorunda bırakıldı
- Üst platformlar aktif şekilde kullanıldı

---

# Not

Yapay zeka araçları yalnızca:
- fikir üretme,
- hata ayıklama,
- mekanik geliştirme,
- ve tasarım desteği

amacıyla kullanılmıştır.

Tüm kod entegrasyonları, düzenlemeler, testler ve son kararlar tarafımdan gerçekleştirilmiştir.