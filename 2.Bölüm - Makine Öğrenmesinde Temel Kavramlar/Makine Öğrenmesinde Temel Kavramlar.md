## 2. Bölüm  : Makine Öğrenmesinde Temel Kavramlar

Makine Öğrenmesi Temel Kavramları

Özellik (Öznitelik) Vektörleri

      Tanım: Özellik vektörleri, her bir veri örneğinin niteliklerini matematiksel olarak temsil eden bir dizi sayıdır. Her bir özellik (öz nitelik), veri setindeki belirli bir özelliği veya niteliği temsil eder.
      Örnek: Bir ev fiyat tahmin modeli için özellikler evin büyüklüğü, oda sayısı, yaş, konum gibi faktörler olabilir. Bir ev için özellik vektörü [150, 3, 20, 1] şeklinde olabilir (150 metrekare, 3 oda, 20 yıllık, konum 
      1).

Eğitim Modelleri

      Tanım: Eğitim modelleri, makine öğrenmesi algoritmalarının veri üzerinde öğrenme sürecinde oluşturduğu ve tahminlerde veya sınıflandırmalarda kullanılan matematiksel yapılar veya fonksiyonlardır.
      Örnek: Bir doğrusal regresyon modeli, veriler arasındaki doğrusal ilişkiyi öğrenir ve yeni verilere dayalı tahminlerde bulunur. Bir karar ağacı modeli ise verileri dallara ayırarak karar verir.
      
Entropi (Bilgi Kazancı):

      Tanım: Entropi, bir veri setinin düzensizliğini veya belirsizliğini ölçen bir kavramdır. Yüksek entropi, veri setinin düzensiz ve belirsiz olduğunu gösterir.
      Örnek: Bir sınıflandırma probleminde, entropi hesaplanarak veri setinin ne kadar karışık olduğu belirlenir. 

Bilgi Kazancı:

      Tanım: Bilgi kazancı, bir özelliğin veri setindeki entropiyi ne kadar azalttığını ölçer. Yani, belirli bir özellik kullanılarak veri setindeki belirsizliğin ne kadar azaltılabileceğini gösterir.
      Örnek: Karar ağacı algoritmalarında, bilgi kazancı hesaplanarak her düğümde en iyi bölmeyi sağlayan özellik seçilir.

Kayıp Veri

      Tanım: Kayıp veri, veri setinde eksik veya mevcut olmayan değerleri ifade eder. Kayıp veriler, analiz ve modelleme süreçlerini olumsuz etkileyebilir.
      Örnek: Bir anket çalışmasında bazı katılımcılar yaşlarını belirtmemiş olabilir. Bu durumda, eksik yaş bilgisi kayıp veri olarak kabul edilir. Kayıp verilerle başa çıkmak için çeşitli yöntemler kullanılır, örneğin 
      eksik değerlerin ortalama ile doldurulması veya eksik verilerin çıkarılması.

Veri Madenciliği

      Tanım: Veri madenciliği, büyük veri setlerinden anlamlı bilgileri keşfetmek için kullanılan süreç ve teknikler bütünüdür. Veri madenciliği, desen tanıma, sınıflandırma, kümeleme ve ilişkilendirme gibi teknikleri 
      içerir.
      Örnek: Bir süpermarket zinciri, müşteri alışveriş verilerini analiz ederek hangi ürünlerin birlikte satıldığını belirleyebilir. Bu bilgi, çapraz satış stratejilerini geliştirmek için kullanılabilir.

Veri Tabanı Yönetimi

      Tanım: Veri tabanı yönetimi, verilerin depolanması, düzenlenmesi ve erişimi için kullanılan sistem ve süreçleri ifade eder. Veri tabanı yönetim sistemleri (DBMS), veritabanlarını yönetmek için kullanılan 
      yazılımlardır.
      Örnek: Bir e-ticaret sitesi, müşteri bilgilerini, siparişleri ve ürün envanterini yönetmek için bir veritabanı kullanır. Bu veritabanı, ilişkisel bir veritabanı yönetim sistemi (RDBMS) olan MySQL tarafından 
      yönetilebilir. DBMS, verilerin güvenliği, bütünlüğü ve performansını sağlamak için çeşitli araçlar ve teknikler sunar.


Bu Kavramların Makine Öğrenmesindeki Rolü

Özellik Vektörleri: 
      Makine öğrenmesi modellerinin girdilerini oluşturur. Modelin neyi öğrenmesi gerektiğini belirler.
Eğitim Modelleri: 
      Verilerden öğrenen ve tahminlerde bulunan yapı taşlarıdır. Farklı modeller, farklı problemler için daha uygun olabilir.
Entropi ve Bilgi Kazancı: 
      Özellikle karar ağacı algoritmalarında önemli olan bu kavramlar, verilerin nasıl bölüneceğini ve modelin nasıl yapılandırılacağını belirler.
Kayıp Veri: 
      Modelin doğruluğunu ve güvenilirliğini etkileyebilir. Kayıp verilerle başa çıkmak, başarılı bir model geliştirmek için kritiktir.
Veri Madenciliği: 
      Büyük veri setlerinden anlamlı bilgiler çıkarmak, makine öğrenmesi için önemli bir adımdır. Bu bilgiler, modellerin daha doğru tahminler yapmasını sağlar.
Veri Tabanı Yönetimi: 
      Verilerin etkin bir şekilde yönetilmesi ve erişilmesi, makine öğrenmesi süreçlerinin verimli ve doğru bir şekilde yürütülmesini sağlar.

Bu kavramlar ve süreçler, makine öğrenmesinin temellerini oluşturur ve modellerin başarılı bir şekilde geliştirilmesi ve uygulanmasında kritik rol oynar.
