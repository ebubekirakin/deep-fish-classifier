# Görüntü İşleme ile Balık Türü Tespit Sistemi

Bu ders projesinde bir balık fotoğrafından balığın hangi türe ait olduğunu tahmin eden basit bir sistem geliştireceğiz. Veri seti olarak Kaggle'daki **A Large Scale Fish Dataset** kullanılacak ve dokuz balık türü sınıflandırılacak.

Çalışma not defteri: [`balik_turu_tespiti.ipynb`](balik_turu_tespiti.ipynb). Dosyayı GitHub'dan Google Colab'da açarak çalıştırabilirsin.

Projede görüntüler modele uygun hâle getirilecek; önceden eğitilmiş MobileNetV2 (CNN) ve ViT-Tiny modelleri balık türlerini tanıyacak şekilde uyarlanacak. Modellerin sonuçları karşılaştırılacak ve sistemi denemek için basit bir Gradio arayüzü hazırlanacak.

Çalışma, mümkün olduğunca az dosyayla ve ücretsiz Google Colab ortamında yürütülecek. Amaç, yalnızca çalışan bir örnek hazırlamak değil; her adımı başlangıç seviyesinde anlaşılır ve sunumda anlatılabilir tutmaktır.

## Plan

1. Colab ortamını ve gerekli kütüphaneleri hazırlama
2. Veri setini tanıma ve görüntüleri ön işleme
3. MobileNetV2 modelini uyarlama ve eğitme
4. ViT-Tiny modelini uyarlama ve eğitme
5. Modelleri değerlendirme ve sonuçlarını karşılaştırma
6. Gradio ile basit bir demo hazırlama
7. Rapor ve sunum notlarını oluşturma

Her bölüm adım adım ilerleyecek; kullanılan kavramlar basitçe açıklanacaktır.
