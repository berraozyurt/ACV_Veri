# ENERJİ PERAKENDE SEKTÖRÜ: VERİ ANALİTİĞİ VE STRATEJİK KARAR DESTEK PROJESİ

**Ahmet Çalık Vakfı | İleri Veri Analitiği Eğitimi | Case Study 02**

---

## PROJE HAKKINDA

Bu çalışma, enerji perakende sektöründe faaliyet gösteren bir şirketin Amasya ilindeki (Gümüşhacıköy, Göynücek, Hamamözü) operasyonel verilerini analiz etmek amacıyla hazırlanmıştır. Proje, ham veriyi işleyerek anlamlı içgörülere dönüştürmeyi ve şirketin karlılığını artıracak stratejik kararlar üretmeyi hedefler.

> **Temel Hedef:** Müşteri tüketim davranışlarını segmentlere ayırmak, bölgesel verimliliği ölçmek ve tahsilat risklerini minimize edecek veri odaklı aksiyon planları oluşturmaktır.

---

## PROJE MİMARİSİ VE DOSYA YAPISI

Proje, yeniden üretilebilir (reproducible) veri bilimi standartlarına uygun olarak aşağıdaki dizin yapısında kurgulanmıştır:

```text
CASE_STUDY_02/
│
├── data/
│   └── elektrik_veri.xlsx          # Analize konu olan ham veri seti
│
├── notebooks/
│   ├── 01_veri_kesfi.ipynb         # Veri temizliği, kalite kontrolü ve önişleme
│   ├── 02_gorsellestirme.ipynb     # Keşifçi veri analizi (EDA) ve görselleştirme
│   └── 03_stratejik_analiz.ipynb   # İş zekası raporlaması ve aksiyon önerileri
│
├── outputs/
│   └── figures/                    # Raporlamada kullanılan yüksek çözünürlüklü grafikler
│
├── requirements.txt                # Proje bağımlılıkları ve kütüphane sürümleri
└── README.md                       # Proje dokümantasyonu
