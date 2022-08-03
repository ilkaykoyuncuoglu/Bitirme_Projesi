<h3 align="center">Merhaba 👋, Women In Tech Bitirme Projesi</h3>

![91168b4873f6659b3e9fdfe4b89cd864](https://user-images.githubusercontent.com/40664789/182602833-ebdcf665-f052-440b-8ab3-a8b5b5961ec4.gif)

#### SistersLab Bilim ve Teknolojide Kadın Derneği tarafından düzenlenen Women In Tech Akademisi sonunda, Bitirme Projesi olarak NBA datası ile veri analizi yapıldı. 

- 5 farklı veri seti ile;

  * Matplotlib, 
  * Seaborn, 
  * Numpy,
  * Pandas kütüphaneleri kullanılarak veri ön işleme yapıldı.
  
#### Veri Setlerinin Açıklamaları:

- Veri setleri; games, games_details, players, ranking ve teams'tir.

  * Games_details (df1): Maç ve oyuncularla ilgili detay bilgileri
  
  * Games (df2): Oyunlar hakkında genel bilgiler ve oynanan maçların istatistiklerini barındırmaktadır.

  * Players (df3): Oyuncular hakkında bilgiler

  * Ranking (df4): Her takımın sezon boyunca belirli günlerdeki durumu hakkında bilgiler

  * Teams (df5): Takıma ait bilgiler

#### Bu ön işleme sonucunda veri seti, sonraki adımlarda yapılacak olan analizlere hazır hale getirilmek için düzenlendi.

- Bu işlemler içerisinde; 

  * Veriseti tanımladı,
  * Veri setine ve içerisindeki değişkenlere ait bilgiler elde edildi,
  * Tanımlayıcı istatistikleri elde edildi,
  * Veri setindeki NaN, Null, NA değerlerin sayısı belirlendi ve bu değerler silindi veya dolduruldu,
  * Date olan sütunlar incelenerek format değişikliği yapıldı,
  * Tekrar eden birbiriyle aynı olan sütunlar veri setinden kaldırıldı, 
  * Hem grafikler için hem de analiz için group by işlemleri yapıldı,
  * Bazı değişkenlerin isimleri kendisini anlatamadığı için değişikliğe gidildi, 
  * Grafikler için gerekli veri setleri merge işlemine tabi tutuldu,
  * Grafiklerde kullanılmak üzere bazı değişkenlerin değerleri kategorik hale getirildi,
  * Grafik olarak lines, bar, pie, üstü üste line, dist plot, korelasyon grafiği, box plot ve plot bar kullanıldı.
