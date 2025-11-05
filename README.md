# 🎯 ARAŞTIRMA TASARIMI: Z KUŞAĞI VS DİĞER KUŞAKLAR 

## 📌 PROJE BİLGİLERİ

### Proje Başlığı
**"Z Kuşağı vs Diğer Kuşaklar: Yemek Sipariş Uygulamalarında Alışkanlık, Ekonomik Algı ve Sadakat Farklılıkları"**

### Araştırmanın Amacı
Bu çalışma, yemek sipariş uygulamalarına yönelik müşteri sadakatinin belirleyicilerini incelemekte ve bu belirleyicilerin Z Kuşağı ile diğer kuşaklar arasında nasıl farklılaştığını ortaya koymayı amaçlamaktadır. Araştırma, UTAUT2 ve VAB teorilerini temel alarak, alışkanlık ve ekonomik algının moderasyon etkilerini test etmektedir.

---

## 🔍 ANA ARAŞTIRMA SORUSU

**"Yemek sipariş uygulamalarına yönelik sadakatin belirleyicileri (performans beklentisi, çaba beklentisi, algılanan değerler) Z Kuşağı ile diğer kuşaklar arasında nasıl farklılaşır ve bu ilişkilerde alışkanlık ile ekonomik algının moderasyon rolü nedir?"**

---

## 📋 HİPOTEZLER VE MODEL YAPISI

### GRUP A: ANA ETKİLER (6 Hipotez)

#### H1: Performans Beklentisi → Algılanan Değerler

**H1a:** Performans beklentisi, duygusal değeri pozitif yönde etkiler (β > 0, p < 0.05)
- **Açıklama:** Uygulamanın kullanışlı olması, kullanıcıların rahat ve keyifli hissetmesini sağlar
- **Model:** PE (IV) → EV (DV)
- **Test:** Doğrusal regresyon

**H1b:** Performans beklentisi, fiyat değerini pozitif yönde etkiler (β > 0, p < 0.05)
- **Açıklama:** Uygulamanın faydalı olması, kullanıcıların tasarruf etmesini kolaylaştırır
- **Model:** PE (IV) → PV (DV)
- **Test:** Doğrusal regresyon

---

#### H2: Çaba Beklentisi → Algılanan Değerler

**H2a:** Çaba beklentisi, duygusal değeri pozitif yönde etkiler (β > 0, p < 0.05)
- **Açıklama:** Uygulamanın kolay olması, kullanıcıların keyif almasını sağlar
- **Model:** EE (IV) → EV (DV)
- **Test:** Doğrusal regresyon

**H2b:** Çaba beklentisi, fiyat değerini pozitif yönde etkiler (β > 0, p < 0.05)
- **Açıklama:** Uygulamanın kolay olması, fiyat karşılaştırmasını kolaylaştırır
- **Model:** EE (IV) → PV (DV)
- **Test:** Doğrusal regresyon

---

#### H3: Algılanan Değerler → Sadakat

**H3a:** Duygusal değer, sadakati pozitif yönde etkiler (β > 0, p < 0.05)
- **Açıklama:** Uygulamayı kullanırken keyif alan kullanıcılar daha sadık olur
- **Model:** EV (IV) → LOY (DV)
- **Test:** Çoklu regresyon

**H3b:** Fiyat değeri, sadakati pozitif yönde etkiler (β > 0, p < 0.05)
- **Açıklama:** Uygulamanın fiyatlarını makul bulan kullanıcılar daha sadık olur
- **Model:** PV (IV) → LOY (DV)
- **Test:** Çoklu regresyon

**Beklenti:** β(Duygusal) > β(Fiyat)

---

### GRUP B: Z KUŞAĞI vs DİĞER KUŞAKLAR (2 Hipotez)

#### H4: Kuşaklar Arası Farklılıklar

**H4a:** Z Kuşağının alışkanlık skoru, diğer kuşaklardan anlamlı şekilde yüksektir (M_Z > M_Diğer, p < 0.05)
- **Açıklama:** Dijital yerliler (Z Kuşağı) teknoloji kullanımında daha yüksek alışkanlık seviyesine sahiptir
- **Test:** Independent samples t-test (tek kuyruklu)

**H4b:** Z Kuşağı ile diğer kuşaklar arasında sadakat düzeyi anlamlı farklılık gösterir (p < 0.05)
- **Açıklama:** Kuşaklar arası sadakat düzeylerinin karşılaştırılması (yön öngörüsü yok)
- **Test:** Independent samples t-test (iki kuyruklu)

---

### GRUP C: MODERASYON ETKİLERİ (4 Hipotez)

#### H5: Alışkanlık Moderasyonu

**H5a:** Düşük alışkanlık grubunda, duygusal değerin sadakat üzerindeki etkisi daha güçlüdür (p < 0.05)
- **Açıklama:** Alışkanlığı olmayan kullanıcılar, duygusal deneyime daha çok önem verir
- **Model:** EV (IV) → LOY (DV), HABIT (Moderatör)
- **Test:** PROCESS Macro Model 1

**H5b:** Düşük alışkanlık grubunda, fiyat değerinin sadakat üzerindeki etkisi daha güçlüdür (p < 0.05)
- **Açıklama:** Alışkanlığı olmayan kullanıcılar, fiyat karşılaştırmasına daha çok önem verir
- **Model:** PV (IV) → LOY (DV), HABIT (Moderatör)
- **Test:** PROCESS Macro Model 1

---

#### H6: Ekonomik Durum Algısı Moderasyonu

**H6a:** Ekonomik durumu kötü algılayanlarda, fiyat değerinin sadakat üzerindeki etkisi daha güçlüdür (p < 0.05)
- **Açıklama:** Ekonomik sıkıntı yaşayanlar için fiyat daha kritik bir faktördür
- **Model:** PV (IV) → LOY (DV), ECONOMIC_PERC (Moderatör)
- **Test:** PROCESS Macro Model 1

**H6b:** Ekonomik durumu iyi algılayanlarda, duygusal değerin sadakat üzerindeki etkisi daha güçlüdür (p < 0.05)
- **Açıklama:** Ekonomik durumu iyi olanlar, fiyattan çok deneyim kalitesine odaklanır
- **Model:** EV (IV) → LOY (DV), ECONOMIC_PERC (Moderatör)
- **Test:** PROCESS Macro Model 1

---

**TOPLAM HİPOTEZ SAYISI: 12**
- Grup A: 6 hipotez
- Grup B: 2 hipotez
- Grup C: 4 hipotez

---

## 📊 ÖLÇEKLER VE SORULAR (7'Lİ LİKERT)

### Ölçek Formatı
1 = Kesinlikle Katılmıyorum
2 = Katılmıyorum
3 = Kısmen Katılmıyorum
4 = Ne Katılıyorum Ne Katılmıyorum (Nötr)
5 = Kısmen Katılıyorum
6 = Katılıyorum
7 = Kesinlikle Katılıyorum

---

### BLOK 1: PERFORMANS BEKLENTİSİ (3 Madde)
**Kaynak:** Venkatesh et al. (2012) - UTAUT2

**Talimat:** *"En sık kullandığınız yemek sipariş uygulamasını düşünerek aşağıdaki ifadelere katılım düzeyinizi belirtiniz."*

| Kod | Madde |
|-----|-------|
| PE1 | Bu uygulama günlük yaşamımda kullanışlıdır |
| PE2 | Bu uygulama satın alma sürecimi hızlandırır |
| PE3 | Bu uygulama yemek siparişi vermemi kolaylaştırır |

**Kompozit Skor:** PERFORMANCE_EXP = (PE1 + PE2 + PE3) / 3

**Hipotezlerdeki Rolü:**
- **Bağımsız Değişken (IV):** H1a, H1b

---

### BLOK 2: ÇABA BEKLENTİSİ (3 Madde)
**Kaynak:** Venkatesh et al. (2012) - UTAUT2

**Talimat:** *"En sık kullandığınız yemek sipariş uygulaması için aşağıdaki ifadelere ne ölçüde katıldığınızı belirtiniz."*

| Kod | Madde |
|-----|-------|
| EE1 | Bu uygulamayı kullanmak kolaydır |
| EE2 | Bu uygulamayla etkileşimim net ve anlaşılırdır |
| EE3 | Bu uygulamayı öğrenmek kolaydır |

**Kompozit Skor:** EFFORT_EXP = (EE1 + EE2 + EE3) / 3

**Hipotezlerdeki Rolü:**
- **Bağımsız Değişken (IV):** H2a, H2b

---

### BLOK 3: DUYGUSAL DEĞER (3 Madde)
**Kaynak:** Sweeney & Soutar (2001) - PERVAL

**Talimat:** *"En sık kullandığınız yemek sipariş uygulaması için aşağıdaki ifadelere ne ölçüde katıldığınızı belirtiniz."*

| Kod | Madde |
|-----|-------|
| EV1 | Bu uygulamayı kullanırken rahat hissediyorum |
| EV2 | Bu uygulamayı kullanırken keyif alıyorum |
| EV3 | Bu uygulamayı kullanırken eğleniyorum |

**Kompozit Skor:** EMOTIONAL_VALUE = (EV1 + EV2 + EV3) / 3

**Hipotezlerdeki Rolü:**
- **Bağımlı Değişken (DV):** H1a, H2a
- **Bağımsız Değişken (IV):** H3a, H5a, H6b

---

### BLOK 4: FİYAT DEĞERİ (3 Madde)
**Kaynak:** Venkatesh et al. (2012) - UTAUT2 + Uyarlama

**Talimat:** *"En sık kullandığınız yemek sipariş uygulaması için aşağıdaki ifadelere ne ölçüde katıldığınızı belirtiniz."*

| Kod | Madde |
|-----|-------|
| PV1 | Bu uygulama farklı restoranların fiyatlarını karşılaştırarak tasarruf etmemi sağlar |
| PV2 | Bu uygulamanın fiyatları makuldür |
| PV3 | Bu uygulamanın teslimat ücretleri ekonomiktir |

**Kompozit Skor:** PRICE_VALUE = (PV1 + PV2 + PV3) / 3

**Hipotezlerdeki Rolü:**
- **Bağımlı Değişken (DV):** H1b, H2b
- **Bağımsız Değişken (IV):** H3b, H5b, H6a

---

### BLOK 5: SADAKAT (3 Madde)
**Kaynak:** Hwang & Kim (2018), Kim et al. (2021)

**Talimat:** *"En sık kullandığınız yemek sipariş uygulaması için gelecekteki niyetlerinizi belirtiniz."*

| Kod | Madde |
|-----|-------|
| LOY1 | Bu uygulama benim ilk tercihim olacaktır |
| LOY2 | Bu uygulamayı başkalarına tavsiye ederim |
| LOY3 | Bu uygulamadan vereceğim sipariş sayısı artacak |

**Kompozit Skor:** LOYALTY = (LOY1 + LOY2 + LOY3) / 3

**Hipotezlerdeki Rolü:**
- **Bağımlı Değişken (DV):** H3a, H3b, H4b, H5a, H5b, H6a, H6b

---

### BLOK 6: ALIŞKANLIK (3 Madde)
**Kaynak:** Limayem & Hirt (2003), Venkatesh et al. (2012)

**Talimat:** *"En sık kullandığınız yemek sipariş uygulaması ile ilgili kullanım alışkanlıklarınızı değerlendiriniz."*

| Kod | Madde |
|-----|-------|
| HAB1 | Bu uygulamadan yemek sipariş etmek benim için neredeyse bir alışkanlık |
| HAB2 | Yemek siparişi için bu uygulamayı kullanmaya bağımlıyım |
| HAB3 | Bu uygulamayı kullanmayı düşünmeden otomatik olarak tercih ederim |

**Kompozit Skor:** HABIT = (HAB1 + HAB2 + HAB3) / 3

**Hipotezlerdeki Rolü:**
- **Bağımlı Değişken (DV) - Kuşak Karşılaştırması:** H4a
- **Moderatör Değişken:** H5a, H5b

---

## 👁️ DİKKAT VE KALİTE KONTROL

### Dikkat Kontrolü (1 Madde)
**Yerleşim:** Ana ölçekler arasına rastgele yerleştirilir (örn: Fiyat Değeri bloğundan sonra)

| Kod | İfade |
|-----|-------|
| ATT1 | Bu soruyu dikkatlice okuduğunuzu göstermek için lütfen "2 - Katılmıyorum" seçeneğini işaretleyiniz |

**Çıkarma Kriteri:** Farklı seçenek işaretleyen → Anketten çıkarılır

---

### Veri Kalitesi Kontrolleri

**1. Zamanlama Kontrolü:**
- **Alt sınır:** Pilot test sonuçlarına göre belirlenecektir (Ortalama - 2 SD)
- **Üst sınır:** Pilot test sonuçlarına göre belirlenecektir (Ortalama + 2 SD)
- **Not:** Pilot test (n=20) yapıldıktan sonra, tamamlanma sürelerinin ortalaması ve standart sapması hesaplanarak istatistiksel temele dayalı eşikler belirlenecektir

**2. Straight-Lining Kontrolü:**
- Tüm Likert sorularına aynı cevap → Çıkar

**3. Filtre Sorusu:**
- Son 6 ay içinde yemek sipariş uygulaması kullanmayanlar → Anket sonlandırılır

---

## 🎯 KONTROL DEĞİŞKENLERİ (3 Soru)

### K1. Kullanım Sıklığı
**Soru:** Aylık ortalama kaç kez yemek sipariş verirsiniz?
- [ ] 0-2 kez
- [ ] 3-5 kez
- [ ] 6-10 kez
- [ ] 10+ kez

---

### K2. Platform Çeşitliliği
**Soru:** Kaç farklı yemek sipariş uygulaması kullanıyorsunuz?
- [ ] Sadece 1 uygulama
- [ ] 2 uygulama
- [ ] 3-4 uygulama
- [ ] 5+ uygulama

---

### K3. Kampanya Duyarlılığı (7'li Likert)
**Soru:** "Sadece kampanya/indirim varsa sipariş veririm"
- 1 (Kesinlikle Katılmıyorum) → 7 (Kesinlikle Katılıyorum)

---

## 📊 DEMOGRAFİK BİLGİLER (7 Soru)

### D1. Doğum Yılı (KRİTİK)
**Soru:** Doğum yılınız? _____ (Açık uçlu)

**Kodlama:**
- **Z Kuşağı:** 1997-2012 (12-27 yaş) [Kod: 1]
- **Diğer Kuşaklar (Y Ağırlıklı):** 1996 ve öncesi (28+ yaş) [Kod: 2]

---

### D2. Cinsiyet
- [ ] Kadın / [ ] Erkek / [ ] Diğer / [ ] Belirtmek istemiyorum

---

### D3. Eğitim Durumu
- [ ] Lise veya altı / [ ] Ön lisans / [ ] Lisans / [ ] Yüksek lisans / [ ] Doktora

---

### D4. Meslek
- [ ] Öğrenci / [ ] Tam zamanlı çalışan / [ ] Yarı zamanlı / [ ] Serbest meslek / [ ] Emekli / [ ] İşsiz

---

### D5. Ekonomik Durum Algısı (KRİTİK - H6 MODERATÖRÜ)
**Soru:** Ekonomik durumunuz hakkında nasıl hissediyorsunuz?
- [ ] Çok kötü (1) / [ ] Kötü (2) / [ ] Orta (3) / [ ] İyi (4) / [ ] Çok iyi (5)

**Not:** PROCESS Macro'da sürekli değişken olarak kullanılır (1-5 skalası)

---

### D6. Tercih Edilen Uygulama
- [ ] Yemeksepeti / [ ] Getir Yemek / [ ] Trendyol Yemek / [ ] Diğer: _____

---

### D7. Şehir
**Yaşadığınız şehir:** _____ (Açık uçlu)

---

## 📝 ANKET AKIŞI VE SÜRE TAHMİNİ

| Sıra | Bölüm | Madde | Süre | Kümülatif |
|------|-------|-------|------|-----------|
| 0 | Giriş + Filtre | 1 | 0.2 dk | 0.2 dk |
| 1 | Performans Beklentisi | 3 | 0.6 dk | 0.8 dk |
| 2 | Çaba Beklentisi | 3 | 0.6 dk | 1.4 dk |
| 3 | Duygusal Değer | 3 | 0.6 dk | 2.0 dk |
| 4 | Fiyat Değeri | 3 | 0.6 dk | 2.6 dk |
| 5 | **Dikkat Kontrolü** | 1 | 0.3 dk | 2.9 dk |
| 6 | Sadakat | 3 | 0.6 dk | 3.5 dk |
| 7 | Alışkanlık | 3 | 0.6 dk | 4.1 dk |
| 8 | Kontrol Değişkenleri | 3 | 0.5 dk | 4.6 dk |
| 9 | Demografik | 7 | 1.0 dk | 5.6 dk |
| **TOPLAM** | **30 soru** | **~5.5 dk** |

**Not:** Pilot test (n=20) sonrası gerçek tamamlanma süreleri hesaplanacaktır.

---

## 🎯 HEDEF ÖRNEKLEM

### Toplam Hedef
- **Minimum:** 250 geçerli yanıt
- **Optimum:** 280-300 geçerli yanıt

### Kuşak Dağılımı
- **Z Kuşağı:** 125-150 kişi (≈50%)
- **Diğer Kuşaklar (Y Ağırlıklı):** 125-150 kişi (≈50%)

**Not:** Örneklemde ağırlıklı olarak Y Kuşağı (1981-1996, 28-43 yaş) beklenmektedir, ancak analiz "Z vs Diğerleri" ikili karşılaştırması olarak yapılacaktır.

---

## 📋 DEĞİŞKEN LİSTESİ VE MODEL YAPISI

### Bağımsız Değişkenler (Antecedents)
1. **Performans Beklentisi (PERFORMANCE_EXP)** - 3 madde
   - Etki: → Duygusal Değer, Fiyat Değeri
2. **Çaba Beklentisi (EFFORT_EXP)** - 3 madde
   - Etki: → Duygusal Değer, Fiyat Değeri

### Aracı Değişkenler (Mediators)
3. **Duygusal Değer (EMOTIONAL_VALUE)** - 3 madde
   - Rol: PE/EE → **EV** → Sadakat
4. **Fiyat Değeri (PRICE_VALUE)** - 3 madde
   - Rol: PE/EE → **PV** → Sadakat

### Bağımlı Değişken (Outcome)
5. **Sadakat (LOYALTY)** - 3 madde
   - Belirleyiciler: Duygusal Değer, Fiyat Değeri

### Moderatör Değişkenler
6. **Alışkanlık (HABIT)** - 3 madde
   - Moderasyon: EV/PV → Sadakat ilişkisini güçlendirir/zayıflatır
   - Ayrıca: Z vs Diğerleri karşılaştırması (H4a)
7. **Ekonomik Durum Algısı (ECONOMIC_PERC)** - 1 madde
   - Moderasyon: EV/PV → Sadakat ilişkisini güçlendirir/zayıflatır
8. **Kuşak (GENERATION)** - Kategorik
   - Z Kuşağı (1) vs Diğer Kuşaklar (2)
   - Karşılaştırma: Alışkanlık, Sadakat (H4a, H4b)

### Kontrol Değişkenleri
9. Kullanım Sıklığı, Platform Çeşitliliği, Kampanya Duyarlılığı
10. Cinsiyet, Eğitim, Meslek

---

## 📚 TEORİK KATKILAR

### 1. UTAUT2 ve VAB Teorilerinin Entegrasyonu

**Katkı:** Bu çalışma, teknoloji kabul literatüründe (UTAUT2) ve tüketici davranışı literatüründe (VAB - Value-Attitude-Behavior) sıklıkla ayrı kullanılan iki teoriyi entegre ederek yeni bir kavramsal çerçeve sunmaktadır.

**Özgünlük:**
- **UTAUT2** genellikle teknoloji *kabulünü* (pre-adoption) incelerken, bu çalışma *sadakati* (post-adoption) hedeflemektedir
- **Performans ve Çaba Beklentisi** (UTAUT2) ile **Algılanan Değerler** (VAB) arasındaki ilişki, her iki değişkenin bağımsız olarak teorileştirilmiş olmasına rağmen ampirik olarak nadiren test edilmiştir
- Ghali et al. (2025) bu ilişkiyi FDA bağlamında test etmiş ancak moderatör etkilerini (alışkanlık, ekonomik algı) dahil etmemiştir

**Teorik Önemi:**
- Performans/Çaba beklentilerinin sadakati *nasıl* etkilediğini (algılanan değerler aracılığıyla) açıklar
- "Blackbox" mekanizmasını aydınlatır: PE/EE → Değerler → Sadakat

---

### 2. Performans ve Çaba Beklentisinin Ayrı Yapılar Olarak İncelenmesi

**Katkı:** Literatürde sıklıkla tek bir "kolaylık" veya "fayda" yapısı altında birleştirilen Performans Beklentisi (PE) ve Çaba Beklentisi (EE), bu çalışmada Venkatesh et al. (2012)'nin UTAUT2 teorisine sadık kalınarak *ayrı yapılar* olarak test edilmektedir.

**Teorik Gerekçe:**
- **PE:** "Bu uygulama bana ne kazandırır?" (Fayda odaklı)
- **EE:** "Bu uygulamayı kullanmak ne kadar kolay?" (Çaba odaklı)
- Ghali et al. (2025) bu ayrımın önemini göstermiştir: PE her üç değeri etkilerken, EE yalnızca duygusal değeri etkilemiştir

**Beklenen Katkı:**
- PE ve EE'nin *farklı* algılanan değerlere (duygusal vs fiyat) farklı şekilde etki edip etmediği test edilecektir
- H1a-b ve H2a-b hipotezleri, hangi beklenti türünün hangi değer türünü daha güçlü etkilediğini ortaya koyacaktır

---

### 3. Z Kuşağı Odaklı Kuşaklar Arası Karşılaştırma

**Katkı:** Geleneksel kuşak araştırmaları genellikle *tüm kuşakları* (Baby Boomers, X, Y, Z) karşılaştırırken, bu çalışma **Z Kuşağı vs Diğerleri** ikili karşılaştırmasıyla Z Kuşağının özgünlüğünü merkeze almaktadır.

**Teorik Dayanaklar:**
- **Dijital Yerlilik (Prensky, 2001):** Z Kuşağı, dijital teknolojilerle büyüyen ilk kuşaktır
- **Alışkanlık Teorisi (Limayem et al., 2007):** Erken yaşta başlayan teknoloji kullanımı, daha güçlü alışkanlıklar oluşturur
- Ancak, **sadakat** açısından Z Kuşağının farklılaşıp farklılaşmadığı tartışmalıdır (Priporas et al., 2017)

**Beklenen Katkı:**
- H4a: Z Kuşağının alışkanlık skorunun yüksekliğini test ederek dijital yerlilik hipotezini doğrular
- H4b: Z Kuşağının sadakat düzeyinin farklılaşıp farklılaşmadığını keşfeder (yön öngörüsü yok)
- Eğer Z Kuşağı *yüksek alışkanlık* ama *düşük sadakat* gösterirse, "dijital alışkanlık ≠ marka sadakati" paradoksu ortaya çıkar

---

### 4. Alışkanlık ve Ekonomik Algının Çift Moderasyon Etkisi

**Katkı:** Mevcut literatür, alışkanlık veya fiyat hassasiyeti gibi moderatörleri genellikle *ayrı çalışmalarda* inceler. Bu çalışma, her iki moderatörü *aynı modelde* test ederek karşılaştırmalı analizler sunar.

**Alışkanlık Moderasyonu (H5a-b):**
- **Teorik Temel:** Limayem et al. (2007) - Alışkanlık, bilinçli karar vermeyi azaltır
- **Beklenti:** Yüksek alışkanlıkta, değerlerin (duygusal, fiyat) sadakat üzerindeki etkisi zayıflar ("otopilot modu")
- **Özgünlük:** Ghali et al. (2025) alışkanlığı *bağımsız değişken* olarak kullanmış, bu çalışma *moderatör* olarak test eder

**Ekonomik Algı Moderasyonu (H6a-b):**
- **Teorik Temel:** Kaynak Kıtlığı Teorisi (Mullainathan & Shafir, 2013) - Ekonomik baskı, fiyata duyarlılığı artırır
- **Beklenti:** Kötü ekonomik algıda fiyat değeri daha kritik; iyi ekonomik algıda duygusal deneyim daha önemli
- **Bağlamsal Katkı:** Türkiye'de yüksek enflasyon döneminde ekonomik algının rolünü test eder (2024-2025 yüksek enflasyon dönemi)

**Karşılaştırmalı Analiz Potansiyeli:**
- Hangi moderatör daha güçlü? Alışkanlık mı, ekonomik algı mı?
- Z Kuşağı için hangi moderatör daha etkili? (Keşifsel analiz)
- Moderatörlerin *etkileşimi* var mı? (İsteğe bağlı üçlü etkileşim analizi)

---

### 5. Post-Adoption Perspektifinden Sadakatin İncelenmesi

**Katkı:** UTAUT2 literatürünün çoğu, **kullanım niyeti** veya **sürekli kullanım niyeti** üzerine odaklanır. Bu çalışma, niyetten öte **sadakat** (attitudinal + behavioral loyalty) kavramını hedefler.

**Teorik Fark:**
- **Niyet (Intention):** "Kullanmayı düşünüyorum" - Geçici, değişken
- **Sadakat (Loyalty):** "İlk tercihim, tavsiye ederim, kullanımı artıracağım" - Kalıcı, tutumsal + davranışsal

**VAB Hiyerarşisi (Homer & Kahle, 1988):**
- Değerler → Tutum → Davranış
- Bu çalışmada: Algılanan Değerler → Sadakat Tutumu → Beklenen Sadakat Davranışı
- Sadakat ölçeği, tutumsal (LOY1, LOY2) ve davranışsal niyeti (LOY3) birleştirir

**Pratik Önemi:**
- Marka yöneticileri için *sadakat* daha kritiktir (müşteri yaşam boyu değeri)
- Sürekli kullanım ≠ Sadakat (alışkanlıktan kullanabilir ama rakibe geçmeye açık olabilir)

---

### 6. Türkiye Bağlamında Enflasyon ve Dijital Ekonomi

**Katkı:** Gelişmekte olan ülkelerde (Türkiye gibi) yüksek enflasyon dönemlerinde ekonomik algının teknoloji tabanlı hizmetlerde (FDA) nasıl rol oynadığı nadir incelenmiştir.

**Bağlamsal Özgünlük:**
- **Türkiye 2024-2025:** Yüksek enflasyon (%60+), düşen satın alma gücü
- **Z Kuşağı Türkiye:** Ekonomik krize erişkinlik döneminde giren ilk dijital kuşak
- **FDA Sektörü:** Pandemide patlama (2020-2021), sonrasında konsolidasyon

**Teorik Katkı:**
- Ekonomik krizin *teknoloji kabul modeli* üzerindeki moderasyon etkisi
- Gelişmiş ülke literatürü (Ghali - Suudi Arabistan; Shaw & Sergueeva - Kanada) ile karşılaştırma imkanı
- Fiyat değerinin, gelişmekte olan ülkelerde duygusal değerden daha mı kritik olduğu sorusu

---

### 7. Literatürdeki Boşluklar ve Bu Çalışmanın Konumu

| Konu | Mevcut Literatür | Bu Çalışmanın Katkısı |
|------|------------------|----------------------|
| **UTAUT2 + VAB** | Ayrı çalışmalarda | İlk kez entegre edildi |
| **PE ve EE** | Sıklıkla birleştirilir | Teoriye sadık kalarak ayrı test edildi |
| **Alışkanlık** | Bağımsız değişken | Moderatör olarak test edildi |
| **Ekonomik Algı** | Nadiren moderatör | Alışkanlıkla birlikte çift moderasyon |
| **Z Kuşağı** | Tüm kuşaklarla karşılaştırma | Z vs Diğerleri ikili karşılaştırma |
| **Sadakat** | Genellikle niyet ölçülür | Attitudinal + behavioral loyalty |
| **Bağlam** | Gelişmiş ülkeler | Türkiye - yüksek enflasyon dönemi |

---

## 🚧 ARAŞTIRMANIN SINIRLILIKLARI

### 1. Örnekleme Yöntemi Sınırlılıkları

**Sınırlılık:** Kartopu (snowball) örnekleme yöntemi kullanılması

**Sonuçları:**
- **Örneklem temsil gücü:** Sonuçlar genel Türkiye FDA kullanıcı popülasyonunu temsil etmeyebilir
- **Homojenlik riski:** Benzer demografik/sosyo-ekonomik özelliklere sahip katılımcılar kümeleri oluşabilir
- **Seçim yanlılığı (self-selection bias):** Ankete katılmaya gönüllü olanlar, gönüllü olmayanlardan sistematik olarak farklılaşabilir

**Gerekçe:**
- 0 maliyet kısıtı
- 6 hafta zaman kısıtı
- FDA kullanıcılarına ulaşmak için örnekleme çerçevesi (sampling frame) yok

**Gelecek Araştırma Önerisi:**
- Olasılıklı örnekleme yöntemleri (rastgele örnekleme)
- Pazar araştırma firmalarıyla işbirliği (profesyonel panel)
- Belirli şehirler/bölgeler için katmanlı (stratified) örnekleme

---

### 2. Kesitsel Tasarım (Cross-Sectional Design)

**Sınırlılık:** Veriler tek bir zaman noktasında toplanmaktadır

**Sonuçları:**
- **Nedensellik çıkarımı zayıf:** Bağımsız değişkenlerin bağımlı değişkeni *gerçekten* etkilediğinden emin olunamaz (ters nedensellik riski)
- **Zamansal dinamikler görülmez:** Alışkanlık gibi zaman içinde gelişen yapılar, statik olarak ölçülür
- **Ortak yöntem varyansı (common method variance):** Tüm değişkenler aynı kaynak (katılımcı) ve yöntemle (anket) ölçülür

**Örnek:**
- H1a (PE → EV): Performans beklentisi duygusal değeri mi etkiler, yoksa daha önce keyif alanlar mı uygulamayı kullanışlı görür? (Ters nedensellik)

**Gelecek Araştırma Önerisi:**
- Boylamsal (longitudinal) tasarım: Katılımcıları 3-6 ay arayla tekrar ölçme
- Deneysel tasarım: Performans/çaba beklentilerini manipüle ederek gerçek nedensellik test etme
- Karma yöntem: Nitel görüşmelerle nedensellik mekanizmalarını derinleştirme

---

### 3. Öz-Bildirim (Self-Report) Veri Toplama

**Sınırlılık:** Tüm veriler katılımcıların kendi beyanlarına dayanmaktadır

**Sonuçları:**
- **Sosyal beğenilirlik yanlılığı:** Katılımcılar kendilerini daha iyi göstermek için gerçek dışı yanıtlar verebilir
- **Hatırlama hatası:** "Aylık kaç kez sipariş veriyorsunuz?" gibi sorularda tahmin yürütülür
- **Ortak yöntem varyansı:** Tüm değişkenler aynı yöntemle (Likert ölçekleri) ölçüldüğü için şişirilmiş korelasyonlar oluşabilir

**Azaltma Çabaları:**
- Dikkat kontrolü (ATT1) sorusu
- Ters kodlanmış maddeler (bu çalışmada yok, gelecek versiyonlar için)
- Anonim anket garantisi

**Gelecek Araştırma Önerisi:**
- Davranışsal veri entegrasyonu: Gerçek uygulama kullanım logları (ör: kaç kez sipariş verildi, sipariş tutarları)
- Çoklu kaynak veri: Müşteriler + marka yöneticileri perspektifi

---

### 4. Moderatör Değişkenlerin Ölçümü

**Sınırlılık 1: Alışkanlık (HABIT) sürekli değişken olarak ölçülmekte**

**Teorik Sorun:**
- Alışkanlık, *zamanla* ve *tekrarla* gelişir (Verplanken & Orbell, 2003)
- Bu çalışmada tek bir anketle, *algılanan* alışkanlık ölçülür
- Gerçek alışkanlık gücü = Davranışsal frekans × Otomatiklik × Bağlamsal istikrar
- Bu çalışma sadece *algılanan otomatikliği* ölçer (HAB1-3)

**Gelecek Araştırma Önerisi:**
- Davranışsal frekans + Algılanan alışkanlığın birlikte ölçülmesi
- Zamansal istikrar: "Son 6 aydır aynı uygulamayı kullanıyor musunuz?"

---

**Sınırlılık 2: Ekonomik Durum Algısı (ECONOMIC_PERC) tek madde**

**Ölçüm Sorunu:**
- Tek madde (D5), subjektif ekonomik durumu ölçer
- Objektif gelir, harcama gücü veya enflasyonun kişisel etkisi ölçülmez
- "Orta" kategorisi (3) belirsizdir ve analizlerde çıkarılabilir

**Gelecek Araştırma Önerisi:**
- Çok maddeli ekonomik algı ölçeği:
  - "Enflasyon beni kişisel olarak etkiliyor" (1-7)
  - "Gelecek ay gelirimin yeteceğinden endişeliyim" (1-7)
  - "Son 6 ayda harcamalarımı kıstım" (1-7)
- Objektif ölçümler: Gelir aralığı, aylık FDA harcaması

---

### 5. Sadakat Ölçümünün Niyete Dayalı Olması

**Sınırlılık:** Sadakat ölçeği (LOY1-3) *gelecekteki niyeti* ölçer, *gerçek davranışı* değil

**Teorik Sorun:**
- "Bu uygulama benim ilk tercihim *olacaktır*" → Niyet
- Gerçek davranış: 3 ay sonra hala bu uygulamayı kullanıyor mu? → Gözlemlenmiyor

**Niyet-Davranış Boşluğu (Intention-Behavior Gap):**
- Meta-analizler gösteriyor: Niyet, davranışın sadece ~28%'ini açıklıyor (Sheeran & Webb, 2016)
- Özellikle düşük maliyetli dijital hizmetlerde, niyet volatildir

**Gelecek Araştırma Önerisi:**
- İki aşamalı çalışma: T1 anket + T2 (3 ay sonra) takip anketi
- Gerçek sadakat: T2'de hala aynı uygulamayı kullanıyor mu? Kaç kez değiştirdi?

---

### 6. Kuşak Operasyonalizasyonu

**Sınırlılık:** "Diğer Kuşaklar" kategorisi heterojen bir gruptur

**Sorun:**
- Y Kuşağı (28-43 yaş) ile X Kuşağı (44-59 yaş) aynı grupta
- Baby Boomers (60+ yaş) örneklemde çok az olacak (FDA kullanımı düşük)
- "Z vs Diğerleri" karşılaştırması, aslında büyük ölçüde "Z vs Y" karşılaştırmasıdır

**Neden Bu Tercih Yapıldı?**
- Z Kuşağının özgünlüğüne odaklanma (dijital yerlilik)
- Örneklem büyüklüğü kısıtı (X ve Y'yi ayırmak her grubu küçültür)
- t-test için iki grup gerekir (ANOVA için 3+ grup gerekir, daha fazla katılımcı gerektirir)

**Gelecek Araştırma Önerisi:**
- Daha büyük örneklem (n=450+) ile üç kuşağın ANOVA ile karşılaştırılması
- Z vs Y vs X: Post-hoc testlerle (Tukey, Bonferroni) ikili karşılaştırmalar

---

### 7. Bağlamsal Sınırlılık: Türkiye ve Enflasyon Dönemi

**Sınırlılık:** Bulgular, 2024-2025 Türkiye'sinin yüksek enflasyon bağlamına özgüdür

**Genellenebilirlik Sorunu:**
- Ekonomik algı moderasyonu (H6), enflasyonun düşük olduğu dönemlerde/ülkelerde geçerli olmayabilir
- Türkiye'deki FDA sektörü özellikleri (ör: kampanya yoğunluğu, teslimat ücretleri) başka ülkelerden farklıdır
- Kültürel faktörler: Türk tüketicilerin fiyat hassasiyeti, Batı Avrupa'dan farklı olabilir

**Karşılaştırmalı Bağlam:**
- Ghali et al. (2025): Suudi Arabistan - yüksek gelir, düşük enflasyon
- Shaw & Sergueeva (2019): Kanada - gelişmiş ekonomi, istikrarlı enflasyon
- Bu çalışma: Türkiye - orta gelir, yüksek enflasyon

**Gelecek Araştırma Önerisi:**
- Aynı modelin farklı ekonomik bağlamlarda test edilmesi (düşük enflasyon ülkeleri)
- Zamansal karşılaştırma: Aynı model enflasyon düştüğünde tekrar test edilirse, H6 hala geçerli mi?

---

### 8. Moderasyon Analizlerinin Karmaşıklığı

**Sınırlılık:** Dört ayrı moderasyon hipotezi (H5a-b, H6a-b) test edilmekte, ancak *üçlü etkileşim* (Z Kuşağı × Alışkanlık × Değerler) bu çalışmada test edilmemektedir

**Eksik Kalan Soru:**
- Z Kuşağı için alışkanlık moderasyonu, diğer kuşaklardan *farklı* mı?
- Örnek: Z Kuşağında düşük alışkanlıkta duygusal değer çok kritik ama Y Kuşağında etki yok mu?

**Neden Test Edilmiyor?**
- Örneklem büyüklüğü yetersiz (her hücrede en az 30 kişi gerekir, 4 grup × 2 moderasyon = 8 hücre → 240+ kişi sadece bir analiz için)
- Üçlü etkileşim yorumlaması çok karmaşık (6 haftalık proje için fazla)
- PROCESS Macro Model 3 gerektirir (daha ileri analiz)

**Gelecek Araştırma Önerisi:**
- Daha büyük örneklem (n=400+) ile üçlü etkileşim testi
- Z Kuşağı için ayrı model, Diğer Kuşaklar için ayrı model → Moderasyonların karşılaştırılması

---

### 9. Ölçek Uyarlamaları ve Kültürel Geçerlik

**Sınırlılık:** Tüm ölçekler İngilizce literatürden uyarlanmıştır, Türkçe kültürel geçerleme yapılmamıştır

**Sorun:**
- PE3 "Bu uygulama yemek siparişi vermemi kolaylaştırır" → Orijinal UTAUT2'de yok, araştırmacı tarafından eklendi
- PV3 "Teslimat ücretleri ekonomiktir" → Türkiye bağlamına özgü (teslimat ücreti tartışması yüksek)
- HAB3 "Düşünmeden otomatik tercih ederim" → "Automaticity" kavramının Türkçe karşılığı net mi?

**Azaltma Çabaları:**
- Tüm ölçekler literatürde sıkça kullanılmış, güvenilirliği yüksek ölçeklerdir
- Pilot test (n=20) ile Türkçe ifadelerin anlaşılırlığı kontrol edilecek

**Gelecek Araştırma Önerisi:**
- Kapsamlı ölçek geçerleme çalışması: Açıklayıcı Faktör Analizi (EFA) + Doğrulayıcı Faktör Analizi (CFA)
- Kültürel uyarlama prosedürü: Geri-çeviri (back-translation), uzman paneli

---

### 10. Tek Platform Odaklı Ölçüm

**Sınırlılık:** Katılımcılar "en sık kullandıkları" tek bir uygulamayı değerlendirmektedir

**Sorun:**
- Çoklu platform kullanıcıları (K2: "Kaç uygulama kullanıyorsunuz?") için sadakat kavramı belirsizdir
- Örnek: Bir kullanıcı hem Yemeksepeti hem Getir kullanıyor → Hangisine sadık?
- Platform değiştirme davranışı (switching behavior) ölçülmüyor

**Platform Çeşitliliği Paradoksu:**
- K2'de "3-4 uygulama kullanıyorum" diyen biri, LOY1'de "İlk tercihim olacak" derse, sadakat gerçek mi?

**Gelecek Araştırma Önerisi:**
- Çoklu platform sadakati ölçeği: "Tüm uygulamalar arasında bu uygulamaya en sadığım" (karşılaştırmalı)
- Platform değiştirme sıklığı: "Son 6 ayda kaç kez farklı uygulamaya geçtiniz?"

---

## 🎯 SINIRLILIKLARIN ÖZETİ VE ETKİLERİ

| Sınırlılık | İç Geçerlik Etkisi | Dış Geçerlik Etkisi | Azaltma Çabası |
|------------|---------------------|----------------------|----------------|
| Kartopu örnekleme | Düşük | Yüksek | Pilot test, dikkat kontrolü |
| Kesitsel tasarım | Yüksek | Düşük | Teorik model, literatür desteği |
| Öz-bildirim verileri | Orta | Düşük | Anonim anket, dikkat kontrolü |
| Alışkanlık ölçümü | Orta | Düşük | Çok maddeli ölçek (3 madde) |
| Ekonomik algı tek madde | Orta | Düşük | Açık ifade, 5'li skala |
| Niyet bazlı sadakat | Yüksek | Orta | Tutumsal + davranışsal niyeti birleştirir |
| Heterojen "Diğerleri" grubu | Orta | Orta | Kuşak ağırlıkları rapor edilecek |
| Türkiye/enflasyon bağlamı | Düşük | Yüksek | Bağlamsal faktörler kontrol değişken |
| Üçlü etkileşim eksikliği | Düşük | Düşük | Gelecek araştırma önerisi |
| Ölçek uyarlaması | Orta | Düşük | Pilot test, güvenilirlik analizi |

---

## 📊 SONUÇ: TEORİK KATKININ SINIRLILIKLARA KARŞIN GÜCÜ

Bu araştırma, yukarıda belirtilen sınırlılıklara rağmen, literatüre önemli teorik ve pratik katkılar sunmaktadır:

**Güçlü Yönler:**
1. ✅ PE ve EE'nin ayrı yapılar olarak teoriye sadık test edilmesi
2. ✅ UTAUT2 + VAB entegrasyonu (yeni kavramsal çerçeve)
3. ✅ Çift moderasyon modeli (alışkanlık + ekonomik algı)
4. ✅ Z Kuşağı odaklı karşılaştırma (dijital yerlilik testi)
5. ✅ Post-adoption perspektifi (sadakat > niyet)
6. ✅ Enflasyon bağlamında ekonomik algının rolü (Türkiye özgünlüğü)

**Sınırlılıkların Kabulü:**
- Sonuçlar, Türkiye'deki 2024-2025 yüksek enflasyon döneminde FDA kullanıcılarının *algılarını* yansıtır
- Nedensellik iddiaları, teorik model ve literatür desteğine dayanır, deneysel test gerektirir
- Genellenebilirlik, benzer bağlamlardaki (gelişmekte olan ülkeler, dijital hizmetler) çalışmalarla artırılabilir

**Sınırlılıkların Şeffaflığı:**
- Tüm sınırlılıklar raporda açıkça belirtilecek
- Okuyucular, bulguları bu sınırlamalar ışığında yorumlayabilir
- Gelecek araştırma önerileri, bu sınırlılıkları aşmak için yol haritası sunar

---

**ARAŞTIRMA TASARIMI FİNAL VERSİYON**

**Hipotez Sayısı:** 12 (Grup A: 6, Grup B: 2, Grup C: 4)  
**Toplam Soru Sayısı:** 30 (Likert: 18, Kontrol: 3, Demografik: 7, Dikkat: 1, Filtre: 1)  
**Tahmini Süre:** ~5.5 dakika (Pilot test sonrası güncellenecek)  
**Hedef Örneklem:** 250-300 geçerli yanıt (Z: 50%, Diğer: 50%)
