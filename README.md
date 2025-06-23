# 🔌 Proteus Op-Amp Devresi (Proteus #13)

**Op-amp (operational amplifier)** devreleri, analog elektronik sistemlerin temel yapı taşlarındandır. Bu devrelerle sinyal yükseltme, filtreleme, karşılaştırma gibi işlemler yapılabilir. Proteus ortamında simülasyonla Op-amp devrelerini test etmek, çalışma mantığını öğrenmek için harika bir başlangıçtır.

🔗 [Web Siteme Bakmak İçin Tıkla](https://www.hakkiharmankaya.com/)

---

## ⚙️ Devre Tipleri

### 1️⃣ Tersleyici (Inverting) Op-Amp Devresi
- **Giriş** tersleyici uca (–) uygulanır.
- **Kazanç:** Av = -Rf / Rin
- **Çıkış**, girişin terslenmiş ve yükseltilmiş halidir.

**Gerekli Malzemeler:**
- Op-amp (LM741)
- 2 direnç (Rin ve Rf)
- Güç kaynağı, giriş sinyali

---

### 2️⃣ Terslemeyen (Non-Inverting) Op-Amp Devresi
- **Giriş** terslemeyen uca (+) uygulanır.
- **Kazanç:** Av = 1 + Rf / Rg
- Giriş sinyali terslenmeden yükseltilir.

**Gerekli Malzemeler:**
- Op-amp (LM741)
- 2 direnç (Rf ve Rg)
- Güç kaynağı, giriş sinyali

---

### 3️⃣ Gerilim Takipçisi (Voltage Follower)
- **Kazanç:** 1
- Giriş ile çıkış aynıdır.
- Yüksek empedanslı tamponlama sağlar.

**Devre Kurulumu:**
- Giriş: (+) uca
- Çıkış: doğrudan (–) uca bağlanır (geri besleme)

---

### 4️⃣ Karşılaştırıcı (Comparator) Devresi
- İki voltajı karşılaştırır.
- (+) > (–) ise çıkış pozitif, aksi halde negatiftir.

**Gerekli Malzemeler:**
- Op-amp (LM741)
- 2 voltaj kaynağı

---

## 🛠 Proteus Kurulumu Adımları

1. Proteus’u açın, yeni proje başlatın.
2. `P` tuşuna basarak aşağıdaki bileşenleri ekleyin:
   - LM741 op-amp
   - Dirençler
   - Voltaj kaynakları
   - Sinyal üreteci
3. Seçilen devre tipine göre bağlantıları yapın.
4. Simülasyonu başlatın ve çıkış sinyalini gözlemleyin.

---

## 📚 Uygulama Alanları

- 🎧 Ses ve sinyal yükselticiler
- 🧮 Matematiksel işlemciler (toplama, fark alma)
- 🧪 Karşılaştırıcılar (dijital dönüşüm)
- 🎛 Filtre devreleri

Proteus ortamında bu devreleri kurarak op-amp’lerin mantığını deneyerek öğrenebilir, elektronik devre analizinde uzmanlaşabilirsin.

