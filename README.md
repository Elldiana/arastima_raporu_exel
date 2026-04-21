# La Lorraine - Dinamik Envanter ve Operasyon Yönetimi Sistemi

Bu proje, donuk unlu mamuller sektöründe faaliyet gösteren La Lorraine firmasının operasyonel süreçlerini optimize etmek amacıyla hazırlanmış bir **Excel Envanter Yönetimi ve Veri Analizi** uygulamasıdır. 

İzmir, Aydın ve Manisa illerindeki bayilerde bulunan fırın envanterlerinin (Eka ve Unox markalı cihazlar) lokasyon bazlı takibi, karmaşık verilerin yapılandırılarak stratejik kararlara dönüştürülmesi hedeflenmiştir.

## 📂 Proje Dosyalarına Erişim

Araştırmanın detaylı teknik raporuna ve veri setine aşağıdaki bağlantılardan ulaşabilirsiniz:

* 📄 **[Proje Raporunu Görüntüle (PDF)](./arastirms_rapor_exel/Eldiana_Belekova.pdf)**
* 📊 **[Veri Setini ve Excel Tablosunu İndir](./arastirms_rapor_exel/i_a_m.xlsx)**

---

## 🎯 Projenin Amacı ve Çözüm Yaklaşımı

Geleneksel yöntemlerle (kağıt veya düz metin) yüzlerce farklı lokasyondaki cihazın takibini yapmak, veri kayıplarına ve operasyonel yavaşlığa neden olmaktadır. Bu proje ile statik veriler; sorgulanabilir, hesaplanabilir ve raporlanabilir bir **dinamik envanter yönetim sistemine** dönüştürülmüştür.

## 🛠️ Kullanılan Teknikler ve Excel Özellikleri

Proje kapsamında veri bütünlüğünü sağlamak ve analiz süreçlerini otomatize etmek için aşağıdaki Excel araçları ve formülleri aktif olarak kullanılmıştır:

* **Veri Doğrulama (Data Validation):** Hatalı veri girişini (örneğin "İzmir" yerine "İzmirr" yazılmasını) engelleyerek veri tabanının temiz kalması sağlandı.
* **Filtreleme ve Dinamik Sorgulama:** Binlerce satırlık veri içinden istenilen marka veya bölgeye anında odaklanabilme imkanı yaratıldı.
* **Bölmeleri Dondurma (Freeze Panes):** Geniş veri setlerinde gezinirken kategori başlıklarının sürekli görünür kalması sağlandı.
* **Akıllı Formüller:**
  * `EĞER (IF):` Cihazların kurulum tarihlerine göre otomatik "BAKIM ZAMANI GELDİ" uyarıları oluşturuldu.
  * `EĞERSAY (COUNTIF):` Bölge ve marka bazlı (Örn: İzmir'deki Eka fırın sayısı) anlık kapasite sayımları yapıldı.
  * `TOPLA (SUM):` Birim maliyetler ve enerji tüketimleri otomatik olarak hesaplandı.
* **Köprüler (Hyperlinks):** Çok sayfalı veri setleri arasında "İzmir Listesine Git" gibi butonlarla hızlı navigasyon arayüzü kuruldu.

## 🚀 Şirkete Sağlanan Stratejik Faydalar

1. **Operasyonel Hız:** Saha personeli ve teknik ekiplerin, hangi lokasyonda hangi cihazın olduğuna anında mobil cihazlar üzerinden erişebilmesi sağlandı.
2. **Veriye Dayalı Satın Alma:** Arıza ve bakım sıklığı verileri sayesinde, markaların (Eka vs. Unox) uzun vadeli performansları kıyaslanarak gelecekteki yatırım kararları için somut zemin oluşturuldu.
3. **Lojistik Optimizasyon:** Bölgesel cihaz yoğunluk haritaları çıkarılarak, teknik servis rotalarının en az maliyet ve zaman kaybıyla planlanması sağlandı.
4. **Kurumsal Hafıza:** Personel sirkülasyonundan bağımsız, sürdürülebilir ve kalıcı bir bilgi takip altyapısı inşa edildi.

---
*Geliştirici: Eldiana Belekova*
