# Enerji Perakende Sektöründe Veri Analitiği ve Stratejik Karar Destek

**Ahmet Çalık Vakfı | İleri Veri Analitiği Eğitimi | Case Study 02**

Bu çalışma, enerji perakende sektöründe faaliyet gösteren bir şirketin Amasya ilindeki Gümüşhacıköy, Göynücek ve Hamamözü ilçelerine ait operasyonel verilerini analiz etmek amacıyla hazırlanmıştır.

Projenin amacı; müşteri tüketim davranışlarını incelemek, bölgeler arasındaki farklılıkları değerlendirmek, ödeme risklerini analiz etmek ve elde edilen bulgular üzerinden veri odaklı iş önerileri geliştirmektir.

## Proje Kapsamı

Çalışma üç ana aşamadan oluşmaktadır:

### 1. Veri Keşfi ve Hazırlığı

Bu aşamada:

* Çoklu Excel sayfaları incelenmiş ve analize uygun biçimde bir araya getirilmiştir.
* Eksik değer, mükerrer kayıt ve veri tutarlılığı kontrolleri yapılmıştır.
* Tarih ve saat bilgileri analiz için uygun özniteliklere dönüştürülmüştür.
* Sonraki analizlerde kullanılacak temiz veri yapısı hazırlanmıştır.

İlgili notebook:

```text
Case_Study2_Veri_Kesfi.ipynb
```

### 2. Veri Görselleştirme ve Desen Analizi

Bu aşamada:

* Tüketim değerlerinin zamana bağlı değişimi incelenmiştir.
* Mevsimsel tüketim desenleri değerlendirilmiştir.
* Olağandışı tüketim değerleri incelenmiştir.
* İlçeler arasındaki tüketim farklılıkları karşılaştırılmıştır.

İlgili notebook:

```text
Case_Study2_Veri_Gorsellestirme.ipynb
```

### 3. Stratejik Analiz ve Öneriler

Bu aşamada:

* Müşteriler tüketim hacimlerine göre segmentlere ayrılmıştır.
* Ödeme davranışları ve gecikme oranları değerlendirilmiştir.
* Analiz bulgularına dayalı stratejik öneriler geliştirilmiştir.

İlgili notebook:

```text
Case_study2_Stratejik_Analiz_ve_Oneriler.ipynb
```

## Temel Bulgular

| Analiz Alanı       | Elde Edilen Bulgu                                                                                                              |
| ------------------ | ------------------------------------------------------------------------------------------------------------------------------ |
| Mevsimsel etki     | Tüketim değerlerinin Temmuz ve Ağustos aylarında yükseldiği gözlemlenmiştir.                                                   |
| Bölgesel farklılık | Gümüşhacıköy en yüksek tüketim ortalamasına sahip bölge olarak öne çıkarken, Hamamözü daha düşük tüketim profili göstermiştir. |
| Finansal risk      | Müşterilerin `%27.2` oranındaki kısmının ödemelerini vade tarihinden sonra gerçekleştirdiği belirlenmiştir.                    |

## Kullanılan Yöntemler

Çalışmada aşağıdaki veri analizi yaklaşımları kullanılmıştır:

* Veri temizleme ve kalite kontrolü
* Eksik değer ve mükerrer kayıt incelemesi
* Zaman temelli analiz
* Mevsimsellik değerlendirmesi
* Aykırı değer incelemesi
* Bölgesel karşılaştırma
* Müşteri segmentasyonu
* Risk analizi
* Stratejik öneri geliştirme

## Dosyalar

```text
Case_Study_02/
├── Case_Study2_Veri_Kesfi.ipynb
├── Case_Study2_Veri_Gorsellestirme.ipynb
├── Case_study2_Stratejik_Analiz_ve_Oneriler.ipynb
├── requirements.txt
└── README.md
```

## Kurulum ve Çalıştırma

Gerekli Python kütüphanelerini yüklemek için bu klasör içinde aşağıdaki komut çalıştırılabilir:

```bash
pip install -r requirements.txt
```

Analiz akışını takip etmek için notebook dosyaları şu sırayla çalıştırılmalıdır:

1. `Case_Study2_Veri_Kesfi.ipynb`
2. `Case_Study2_Veri_Gorsellestirme.ipynb`
3. `Case_study2_Stratejik_Analiz_ve_Oneriler.ipynb`

## Not

Bu çalışma, Ahmet Çalık Vakfı İleri Veri Analitiği Eğitimi kapsamında gerçekleştirilen bir case study projesidir. Repository, çalışmanın analiz sürecini ve geliştirilen veri odaklı önerileri portföy amacıyla düzenli biçimde sunmaktadır.
