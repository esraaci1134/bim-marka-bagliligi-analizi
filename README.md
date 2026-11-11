# 🛒 BİM Marka Bağlılığı ve Tüketici Davranışları Analizi (SPSS & MS Excel)

Bu proje; perakende sektörünün öncü markalarından BİM A.Ş.'ye yönelik tüketici algısını, marka sadakatini ve bağlılığı oluşturan temel etkenleri ölçmek amacıyla **303 katılımcıdan alınan anket verileri** üzerinde gerçekleştirilen bir nicel veri analizi çalışmasıdır.

## 🚀 Öne Çıkan Analitik Çıktı

* **🎯 Temel Bulgumuz (**$R^2 = 0.592$**):** Yapılan Çoklu Doğrusal Regresyon Analizi sonucunda, BİM'e yönelik marka bağlılığını oluşturan temel unsurun **%59.2 oranında "Güven" faktörü** olduğu istatistiksel olarak kanıtlanmıştır ($p < 0.001$).

## 🔬 Uygulanan İstatistiksel Metodoloji

Çalışmada SPSS ortamında adım adım uygulanan hipotez testleri ve istatistiksel teknikler:

```
[1. Örneklem & Veri Girişi]  ---> [2. Güvenilirlik Analizi] ---> [3. Faktör Analizi (AFA)]
       (303 Anket Verisi)              (Cronbach's Alpha > 0.70)       (Boyut İndirgeme)
                                                                            │
[5. Karar Destek & Rapor]    <--- [4. Regresyon Analizi]    <--- ───────────┘
     (Stratejik İçgörüler)           (Marka Bağlılığı Modeli)

```

1. **Güvenilirlik ve Geçerlilik Analizi (Reliability Analysis):**

   * Ölçme aracındaki ifadelerin iç tutarlılığı **Cronbach's Alpha** katsayısı ile test edilmiş ve ölçeğin yüksek derecede güvenilir olduğu doğrulanmıştır ($\alpha > 0.80$).

2. **Açımlayıcı Faktör Analizi (EFA):**

   * 303 kişilik anket verisindeki 20+ değişken, Kaiser-Meyer-Olkin (KMO) ve Bartlett Küresellik testlerinden geçirilerek alt boyutlara (Güven, Fiyat/Performans, Kalite Algısı, Erişilebilirlik) indirgenmiştir.

3. **Çoklu Doğrusal Regresyon Analizi (Multiple Linear Regression):**

   * Marka bağlılığı bağımlı değişken; Güven, Fiyat ve Hizmet kalitesi bağımsız değişkenler olarak modellenmiştir. Modelin açıklayıcılık katsayısı $R^2 = 0.592$ olarak hesaplanmıştır.

## 🛠️ Kullanılan Araçlar ve Testler

| Aşama / Test | Kullanılan Araç / Yöntem | İstatistiksel Amaç | 
| ----- | ----- | ----- | 
| **Veri Toplama & Hazırlık** | MS Excel | 303 satırlık anket verisinin kodlanması ve temizliği | 
| **İstatistiksel Analiz** | IBM SPSS Statistics | Hipotez testleri, faktör ve regresyon modellemesi | 
| **Güvenilirlik Testi** | Cronbach's Alpha ($\alpha$) | Anket sorularının iç tutarlılık ölçümü | 
| **Yapı Geçerliliği** | KMO & Bartlett Testi, Varimax | Faktör dağılımlarının ve varyans açıklama oranlarının tespiti | 
| **Tahminleme Modeli** | Çoklu Regresyon ($R^2$) | Marka bağlılığını tetikleyen kilit faktörün tespiti | 

## 📊 Özet Bulgular ve Stratejik İçgörüler

* **Güven Faktörünün Dominansı:** Tüketicilerin BİM'i tercih etme ve markaya bağlı kalma kararlarında fiyat algısından ziyade **kurumsal güven ve ürün sürekliliği** ilk sırada yer almaktadır (%59.2 etki payı).

* **Demografik Kırılımlar:** Gelir düzeyi ve alışveriş sıklığı ile marka sadakati arasında anlamlı farklılıklar ($p < 0.05$) tespit edilmiştir.

## 📁 Proje Dosya Yapısı

```
bim-marka-bagliligi-analizi/
├── 5 ve 12. sorular çıkmış hali son.spv
├── 5. soru çıkmadan önceki hali.spv
├── ANKET YANITLARI VERİ SETİ-.csv
├── Bağlılık.spv
├── BİM RAPOR.docx
├── cinsiyet.spv
├── Faktör analizi.spv
├── Güven.spv
├── Hepsi.spv
├── Marka Memnuniyeti.spv
├── Marka Sevgisi.spv
├── Marka Toplam.spv
├── Marka bağlılığı.spv
├── Marka imajı.spv
├── Markanın Ünü.spv
├── Markaya Güven Güven.spv
├── Regresyon analizi.spv
├── Son veriler.sav
├── eğitim medeni gelir.spv
├── yaş histogram.spv
├── yaş.spv 
└── README.md                      
```

## 👤 Geliştirici

**Esra ACI**
