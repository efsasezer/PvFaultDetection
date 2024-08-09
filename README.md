PV Fault Detection Projesi: Güneş Panellerindeki Arızaların Tespiti

Bu proje, güneş panellerindeki arızaları tespit etmek amacıyla bir derin öğrenme modeli geliştirmeyi hedefler. Aşağıda bu sürecin ana adımları açıklanmıştır:

1. Dataseti Hazırlama

Resimlerin Yüklenmesi: Güneş panellerine ait resimleri içeren bir dizin bulunmaktadır. Bu dizindeki resimleri okuyup, her bir resmi bir veri kümesine dönüştüreceğiz. Resimler gri tonlamalı olarak işlenecek ve her bir resmi bir veri vektörüne dönüştüreceğiz.

Arıza Yüzdeleri CSV Dosyası: Arıza yüzdelerini içeren bir CSV dosyası mevcuttur. Bu dosya, her bir resim için arıza yüzdelerini içermektedir. Bu veriyi bir tabloya aktararak arıza yüzdelerini görselleştireceğiz.

Veri Birleştirme: Resim verilerini ve arıza yüzdelerini içeren verileri birleştirerek, her resim için arıza yüzdeleri ile ilişkilendirilmiş bir veri tabanı oluşturacağız.

2. Veri Görselleştirme

Arıza Dağılımı: Arıza yüzdelerinin dağılımını görselleştireceğiz. Bu adım, arıza yüzdelerinin hangi aralıklarda yoğunlaştığını ve genel dağılımı anlamamıza yardımcı olacaktır.

Resimlerin Görüntülenmesi: Veri kümesindeki bazı örnek resimleri görselleştirerek, arıza yüzdeleri ile ilişkili olan panellerin görsel özelliklerini inceleyeceğiz. Bu, veri kümesinin görsel bir temsilini sunacak ve modelin eğitiminde görsel örneklerin nasıl kullanılacağını anlamamıza yardımcı olacaktır.

3. Model Geliştirme

Model Seçimi ve Eğitim: Derin öğrenme tekniklerini kullanarak, resimlerden arıza yüzdelerini tahmin eden bir model geliştireceğiz. Bu adımda modelin mimarisini belirleyecek ve modeli resim verileri ile eğiteceğiz.

Performans Değerlendirmesi: Modelin doğruluğunu ve genel performansını değerlendirmek için çeşitli metrikler kullanacağız. Bu, modelin gerçek dünya verileri üzerinde nasıl performans gösterdiğini anlamamıza yardımcı olacaktır.

4. Sonuçların Yorumlanması

Modelin sonuçlarını inceleyerek, güneş panellerindeki arızaları doğru bir şekilde tespit edip etmediğimizi değerlendireceğiz. Ayrıca, modelin geliştirilmesi gereken alanlarını belirleyeceğiz.

