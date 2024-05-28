## 3. Bölüm  : Makine Öğreniminin Türleri

Makine Öğreniminin Türleri

Denetimli Öğrenme (Supervised Learning)

      Tanım: Denetimli öğrenme, modelin eğitim verileri ile etiketlenmiş (giriş-çıkış çiftleri içeren) veri setleri üzerinde 
      eğitildiği makine öğrenmesi türüdür. Model, verilen girdilere karşılık gelen çıktıları tahmin etmeyi öğrenir.
      Örnek: E-posta spam filtresi, kredi risk değerlendirmesi, ev fiyatı tahmini. 
      Algoritmalar: Lineer regresyon, lojistik regresyon, destek vektör makineleri (SVM), karar ağaçları, rastgele ormanlar, 
      yapay sinir ağları. 
      Uygulama: Bir veri setinde belirli etiketlerle (örneğin, e-postaların spam veya değil olarak etiketlenmesi) model eğitilir
      ve yeni, etiketlenmemiş e-postaların spam olup olmadığını tahmin eder.

Denetimsiz Öğrenme (Unsupervised Learning)

      Tanım: Denetimsiz öğrenme, modelin eğitim verileri ile etiketlenmemiş (yalnızca giriş verilerini içeren) veri setleri 
      üzerinde eğitildiği makine öğrenmesi türüdür. Model, verilerdeki gizli yapıları keşfetmeye çalışır.
      Örnek: Müşteri segmentasyonu, pazar sepeti analizi, anormallik tespiti.
      Algoritmalar: K-means kümeleme, hiyerarşik kümeleme, ana bileşen analizi (PCA), t-dağıtılmış stokastik komşu 
      yerleştirme (t-SNE).
      Uygulama: Bir süpermarketin müşteri verilerini kullanarak, müşterilerin benzer alışveriş alışkanlıklarına göre 
      gruplandırılması.

Yarı Denetimli Öğrenme (Semi-Supervised Learning)

      Tanım: Yarı denetimli öğrenme, hem etiketli hem de etiketlenmemiş verilerin birlikte kullanıldığı makine öğrenmesi türüdür. 
      Genellikle etiketli veri az olduğunda ve etiketlenmemiş veri çok olduğunda kullanılır.
      Örnek: Görüntü tanıma, metin sınıflandırma.
      Algoritmalar: Çeşitli algoritmalar bu tür öğrenmeye adapte edilebilir; etiket yayılımı (label propagation), yarı denetimli 
      destek vektör makineleri.
      Uygulama: Binlerce etiketsiz görüntü ve birkaç etiketli görüntü ile model eğitilir ve model, etiketsiz görüntüleri 
      doğru bir şekilde sınıflandırmayı öğrenir.

Takviyeli Öğrenme (Reinforcement Learning)

      Tanım: Takviyeli öğrenme, bir ajanın (agent) belirli bir ortamda (environment) eylemler (actions) yaparak ödül (reward) 
      kazandığı ve bu ödülleri maksimize etmeye çalıştığı makine öğrenmesi türüdür. Ajan, deneme- 
      yanılma yoluyla en iyi stratejiyi öğrenir.
      Örnek: Oyun oynayan yapay zeka, robotik kontrol, otonom araçlar.
      Algoritmalar: Q-öğrenme, derin Q-ağları (DQN), politika gradyanı yöntemleri, aktör-eleştirmen 
      (actor-critic) yöntemleri.
      Uygulama: Bir robotun bir labirentte doğru yolu bulması için ödüller ve cezalar verilerek eğitilmesi.

Özellik Öğrenme (Feature Learning)

      Tanım: Özellik öğrenme, bir modelin otomatik olarak ham verilerden anlamlı özellikler (öz nitelikler) öğrenmesini sağlar. 
      Özellik öğrenme, verilerin daha iyi temsil edilmesini ve daha iyi model performansı elde 
      edilmesini sağlar.
      Örnek: Derin öğrenmede kullanılan evrişimli sinir ağları (Convolutional Neural Networks, CNN) görüntülerden otomatik 
      olarak özellikler öğrenir.
      Algoritmalar: Otomatik kodlayıcılar (autoencoders), evrişimli sinir ağları (CNN), gözetimsiz ön eğitim 
      (unsupervised pre-training).
      Uygulama: Bir CNN, ham görüntü piksellerinden kenarlar, köşeler ve daha karmaşık görsel desenler gibi özellikleri 
      otomatik olarak öğrenir ve bu özellikleri görüntü sınıflandırma için kullanır.


Bu makine öğrenmesi türleri, farklı problem türlerine ve veri yapılarına uygun çeşitli yöntemler sunar. Denetimli ve denetimsiz öğrenme, en yaygın kullanılan türlerdir, ancak yarı denetimli öğrenme ve takviyeli öğrenme de belirli senaryolarda çok etkili olabilir. Özellik öğrenme ise, özellikle derin öğrenme alanında büyük önem taşır ve karmaşık veri yapılarını anlamada kritik rol oynar.
