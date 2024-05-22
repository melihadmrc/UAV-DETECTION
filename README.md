UAV-DETECTION

Dalian Teknoloji Üniversitesi tarafından hazırlanan kısaca DUT-Anti-İHA olarak adlandırılan görünür ışık modlu veri kümesi
10.000 görüntüden ve kısa ve uzun vadeli sekanslar içeren 20 videodan oluşmaktadır.
Görüntüler birden fazla nesne içerdiğinden toplam algılanan nesne sayısı 10.109’dur. 
train, test ve val kümelerinde 5243, 2245 ve  2621 nesne bulunmaktadır.
Bu veri kümesi train, test ve val olmak üzere ayrılmıştır.

Görüntü Çözünürlüğü:
Veri seti çeşitli çözünürlüklere sahip görüntüler içermektedir.
Veri setinde bulunan görüntülerde en büyük yüksek genişlik 3744 x 5616, en küçük yüksek ve genişlik 160 x 240’tır. 
Video veri kümesinde ise 1080 x 1920 ve 720 x 1280 çözünürlüğe sahip iki tane çerçeve bulunmaktadır.

Nesne ve Arka Plan: 
Nesnelerin çeşitliliğini artırmak ve modellerin aşırı uyumunu azaltmak için 35 farklı İHA türü kullanılmıştır. 
Veri seti arka planları, gökyüzü, kara bulutlar, ormanlar, yüksek binalar, konutlar, tarım arazileri ve oyun alanlarıdır.
Görüntüler çeşitli ışık (gündüz, gece, şafak, alacakaranlık), farklı hava koşulları (güneşli, bulutlu, karlı vb.) içermektedir.

Nesne Konumu: 
İHA’lar genellikle görüntünün merkezinde yoğunlaşmıştır.
Nesne hareketleri aralıklı olarak değişmekte olup yatay ve dikey olarak hareketleri eşit dağılmıştır.


Yapılan bu projenin amacı işgalci İHA'ları tespit etmektir. YOLOv3, Faster-RCNN, SSD, Cascade-RCNN tespit modellerinin kullanılması hedeflenmiştir.
Bu projede YOLOv3 kullanılmıştır. mAP=0,90
