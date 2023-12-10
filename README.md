# Buton Kontol Uygulamasi

 ## Projenin Amacı
Bu proje, Java dilinde kullanıcı arayüzü (GUI) tasarımı için temel bir örnek sunar. Özellikle, özelleştirilmiş butonlar aracılığıyla bir kullanıcı arayüzü oluşturur. Bu butonlar, GraphQL şemalarına bağlı olarak durumlarını değiştirme yeteneğine sahiptir. Bu örnek proje, basit bir grafik arayüz tasarımı ve olay işleme mekanizması sunarak, Java'da GUI uygulamalarını geliştirmek için temel bir anlayış sağlar.

## Kullanılma Nedeni
Bu proje, Java dilinde GUI programlama becerilerini öğrenmek ve geliştirmek isteyen geliştiricilere yöneliktir. Aynı zamanda, temel GUI bileşenleri üzerinde nasıl özelleştirmeler yapılacağını ve olayları nasıl ele alınacağını anlamak isteyenler için uygundur. Proje, özellikle Swing veya JavaFX gibi GUI kütüphaneleri kullanılarak temel grafik arayüz tasarımı ve olay işleme kavramlarını uygulamak için bir başlangıç noktası sunar.
## Uygulamanın Özellikleri 
-Her buton, özel olarak oluşturulmuş `ButonOlustur` sınıfından türetilir.
- Her buton, GraphQL şemasını saklayabilme özelliğine sahiptir.
- Butonlar, basıldığında GraphQL şemasında bir mutation çalıştırma yeteneğine sahiptir.
- Butonlar, aktif ve pasif durumlarını göstermek için farklı renk ve simgeleri kullanır.
- Bir butona tıklandığında, diğer butonların durumları güncellenir; önceki butonlar pasif hale gelir, sadece tıklanan buton aktif olur.
