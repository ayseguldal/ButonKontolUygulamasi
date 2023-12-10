# Buton Kontol Uygulamasi

 ## Projenin Amacı
Bu proje, Java dilinde kullanıcı arayüzü (GUI) tasarımı için temel bir örnek sunar. Özellikle, özelleştirilmiş butonlar aracılığıyla bir kullanıcı arayüzü oluşturur. Bu butonlar, GraphQL şemalarına bağlı olarak durumlarını değiştirme yeteneğine sahiptir. Bu örnek proje, basit bir grafik arayüz tasarımı ve olay işleme mekanizması sunarak, Java'da GUI uygulamalarını geliştirmek için temel bir anlayış sağlar.

## Kullanılma Nedeni
Bu proje, Java dilinde GUI programlama becerilerini öğrenmek ve geliştirmek isteyen geliştiricilere yöneliktir. Aynı zamanda, temel GUI bileşenleri üzerinde nasıl özelleştirmeler yapılacağını ve olayları nasıl ele alınacağını anlamak isteyenler için uygundur. Proje, özellikle Swing veya JavaFX gibi GUI kütüphaneleri kullanılarak temel grafik arayüz tasarımı ve olay işleme kavramlarını uygulamak için bir başlangıç noktası sunar.
## Uygulamanın Özellikleri 
- Her buton, özel olarak oluşturulmuş `ButonOlustur` sınıfından türetilir.
- Her buton, GraphQL şemasını saklayabilme özelliğine sahiptir.
- Butonlar, basıldığında GraphQL şemasında bir mutation çalıştırma yeteneğine sahiptir.
- Butonlar, aktif ve pasif durumlarını göstermek için farklı renk ve simgeleri kullanır.
- Bir butona tıklandığında, diğer butonların durumları güncellenir; önceki butonlar pasif hale gelir, sadece tıklanan buton aktif olur.
- Eğer ekranda örneğin 1. Butona basıldıktansonra  2.  Ve  daha  sonraki  herhangi  bir sıradaki basılmamış butona basıldığında onlarda aktif renk ve aktif simge gösterecektir. Ancak 1. Butona tekrar basılırsa önceden basılmış butonlar(varsa) pasif hale gelecektir ve sadece tekrar basılan buton aktif olacaktır.

## Kullanım Alanları
  Bu tür bir proje, aşağıdaki kullanım alanlarına uygun olabilir:
- GUI programlamaya yeni başlayan geliştiricilerin eğitimi ve öğrenimi için örnek bir proje.
- Temel GUI becerilerini geliştirmek isteyen geliştiricilerin pratik yapması için bir temel proje.
- Java dilindeki GUI kütüphaneleri ile çalışmak isteyenlerin başlangıç noktası.
- Özelleştirilmiş butonlar gibi özel grafik bileşenlerinin nasıl oluşturulacağını ve kullanılacağını anlamak isteyenler için bir referans.
- Bu proje, kullanıcı arayüzü tasarımı ve olay işleme konularında temel bir anlayış kazanmak isteyen Java geliştiricileri için faydalı olabilir.

## Uygulama Çalıştırılması ve Süreci:
1- Butonların Basılmamış Hali:
![ss2](https://github.com/ayseguldal/ButonKontolUygulamasi/assets/118614193/ba36d860-465a-4b6f-b544-fc4da59290f3)
2- Herhangi Bir Buton Aktif Olduğundaki Durum:
![ss1](https://github.com/ayseguldal/ButonKontolUygulamasi/assets/118614193/b37c2d22-f8bb-44f3-ab75-fc32d0c31882)
3- Tüm butonların pasif olduğu durum:
3- Her Aktifleştirilen Butonun GraphQL Adresi:



