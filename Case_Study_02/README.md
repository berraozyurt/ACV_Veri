# ENERJİ PERAKENDE SEKTÖRÜ: VERİ ANALİTİĞİ VE STRATEJİK KARAR DESTEK PROJESİ

**Ahmet Çalık Vakfı | İleri Veri Analitiği Eğitimi | Case Study 02**

---

## PROJE HAKKINDA

Bu çalışma, enerji perakende sektöründe faaliyet gösteren bir şirketin Amasya ilindeki (Gümüşhacıköy, Göynücek, Hamamözü) operasyonel verilerini analiz etmek amacıyla hazırlanmıştır. Proje, ham veriyi işleyerek anlamlı içgörülere dönüştürmeyi ve şirketin karlılığını artıracak stratejik kararlar üretmeyi hedefler.

> **Temel Hedef:** Müşteri tüketim davranışlarını segmentlere ayırmak, bölgesel verimliliği ölçmek ve tahsilat risklerini minimize edecek veri odaklı aksiyon planları oluşturmaktır.

---
# METODOLOJİ VE ANALİZ ADIMLARI

Proje üç ana fazda gerçekleştirilmiştir:

## 1. Veri Hazırlığı ve Kalite Kontrolü (Notebook 01)
  Çoklu Excel sayfalarının entegrasyonu ve veri tabanı formatına dönüştürülmesi.

  Veri tutarlılık testleri (Negatif tüketim, mükerrer kayıt ve null değer kontrolü).

  Zaman serisi analizi için tarih/saat öznitelik çıkarımı.

## 2. Görselleştirme ve Desen Analizi (Notebook 02)
  Mevsimsellik Analizi: Yıl içi tüketim dalgalanmalarının tespiti.

  Aykırı Değer (Outlier) Tespiti: Standart sapma ve IQR yöntemleri ile olağandışı tüketimlerin belirlenmesi.

  Bölgesel Karşılaştırma: İlçe bazlı enerji yoğunluk haritalarının çıkarılması.

## 3. Stratejik Hikayeleştirme (Notebook 03)
  Müşteri Segmentasyonu: Abonelerin tüketim hacimlerine göre (Düşük/Orta/Yüksek) sınıflandırılması.

  Risk Analizi: Ödeme vadeleri ve gecikme oranlarının finansal etkisi.

  Aksiyon Planı: Veri bulgularına dayalı iş önerileri.



#  TEMEL BULGULAR VE İÇGÖRÜLER
Yapılan analizler sonucunda aşağıdaki kritik iş zekası verilerine ulaşılmıştır:


### Analiz Alanı                  Temel Bulgu

#### Mevsimsel Etki              Tüketim, tarımsal sulama ve iklimlendirme ihtiyacı nedeniyle Temmuz ve Ağustos aylarında zirve yapmaktadır.

#### Bölgesel Fark               Gümüşhacıköy, ticari yoğunluk sebebiyle en yüksek tüketim ortalamasına sahipken; Hamamözü mesken ağırlıklı düşük profil sergilemektedir.

#### Finansal Risk              Müşterilerin %27.2'si ödemelerini vade tarihinden sonra yapmaktadır. Bu durum nakit akışı optimizasyonu gerektirmektedir.





# KURULUM VE ÇALIŞTIRMA TALİMATLARI

Projenin yerel ortamda hatasız çalışması için aşağıdaki adımları izleyin:

### 1. Gerekli Kütüphanelerin Yüklenmesi Terminal veya Komut İstemi üzerinden proje dizinine giderek bağımlılıkları yükleyin:

    pip install -r requirements.txt


2. Notebook Çalıştırma Sırası Analiz akışının bozulmaması için dosyaları şu sırayla çalıştırın:

      notebook_01_veri_kesfi.ipynb (Temiz veri setini oluşturur)

      notebook_02_gorsellestirme.ipynb

      notebook_03_stratejik_analiz.ipynb



  ##   Hazırlayan: [Berra Nur Ozyurt]
