# CSS Notları
## Css dosyasını html dosyasına dahil etmek için head içine link vererek işlem yapılabilir.
## Html dosyası içinde head tagları arasında da style etiketi tanımlanıp css kullanılabilir.
## Htmlde tanımladığım body kısmında tanımlanan etiketlerin kendisine style etiketi verebilirim.
## Birden fazla css dosyalarını ana css oluşturup onda @import etiketi ile tanımlayaniliriz. ( @import "stil.css"; veya @import url("stil.css") ; )
## id değerleri benzersiz olmalıdır. Her html etiketine id niteliği verebilirim.
## Class etiketi cssde birden fazla etiket içinde aynı isimle kullanılabilir. Css dosyasında nokta koyarak tanımlama yapılabilir.Aynı class içine birden fazla class değeri verebilirim. Birden fazla class bir css içinde boşluk bırakmadan nokta koyarak tanımlanabilir. 
## Classlar ve idleri bitişik olarak class önüne nokta id önüne de # işareti koyarak cssde tanımlama yapabiliriz.
## * -> evrensel seçicidir. Tüm etiketlere uygulanır.
## Herhangi bir etiket içinde birden fazla etiket tanımlanıyıp hepsine aynı işlemi uygulamak istiyorsam etiketten sonra * kullanarak yapabilirim.
## Birden fazla etikete tek css işlemi uygulamak istersem aralarına virgül koyarak tek yapıda tanımlama yapılabilir. Ayrıca bunlarla birlikte id ve classlarda tanımlanabilir.
## div içindeki b etiketini div boşluk b şeklinde seçebiliriz.
## Class etiketli yapının içine yeni class etiketli yapıyı yani iç içe 2 classı aralarına boşluk bırakarak cssde tanımlayabilirim.
## Bitişik kardeş seçici seçtiğimiz etiketten sonra gelen etiketi kullanmak için bu yapıyı kullanıyoruz. Örn h3 + p -> h3den sonra gelen paragrafı seç
## Aynı etikette niteliği belirlenen ürünü [] içinde belirtebiliriz. Yani bir tür özelleştirme yapılabilir. Örneğin abbr[title] etiketi gibi. Etiket adı belirtmeseydim tüm title durumlarını seçebilirdi.
## İçerikli durumlar olduğunda niteliğin belirtme durumuda eklendiğinde aynı sekilde css tagıma ekleme yapıyorum. Özel çzellik verme durumu. Örneğin a[target="_blank"] şeklinde özelleştirme yapılabilir.
## div[class|="box"] -> div içinde özelliği box ile başlayan tüm etiketler anlamında kullanılır. - işareti olmayanlar seçime dahil değildir. | yerine ^ koysaydım eğer o zaman - işaretinin bir anlamı kalmaz tüm değerleri seçer. ='den önce + işareti koyarsam bu yapıyla biten durumlar anlamı taşır. Niletik işleminde tümünü seçerken ='den önce * koyabiliriz. Büyük küçük harf duyarlılılğının önüne geçmek için ise ] parantezden önce i harfi koymak yeterli olacaktır.
## Sözde öğenin olup olmadığını :: gördüğümüzde anlayabiliriz. Css de bu duruma css özellikleri verebiliriz.  Bü özellligü before ve after ile kullanabiliriz. İçine özellik eklerkende mutlaka content özelliği belirtmeliyim. Aslında bakınca bu durum bir yazının önüne veya sonuna css kodlarıyla yazı yazmamı sağlar. Content belirtilmek zorundadır. 
  .box::after {
      content: 'sona ekleme';
      color: red ;
  }  gibi..
## attr nitelikteki değerlerimi almayı sağlar. Parantez içine nitelik değerimi alıp yapıyorum. 
## Data adında birnitelik belirlemesi de yapabilirim datadan sonra istediğim ismi verebilirim.

### Güncellenecektir :)
