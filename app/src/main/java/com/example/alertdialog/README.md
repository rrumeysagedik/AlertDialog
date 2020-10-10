
Projelerde bazı konular kullanıcılara bilgi vermek isteyebiliriz. Mesela bir veriyi silmek istediğimiz zaman emin misin şeklinde  bir soru belirtebiliriz.
-Toast
						CONTEXT
Context nedir ?
Context, android proje içerisinde app içerisinde ne oluyor, kim kim ile iletişime geçiyor. Arka planda işler nasıl işliyor ? Hepsinin bir arada tutulduğu durum gibidir.
İki tane Context var:
-Activity Context
Activiteyi ilgilendiren durumdur.  Activity Context’ e ulaşabilmek için this’i ve Main Activitiy.this’ i kullanabilir.

-App Context
getApplicationContext() metodunu kullanıyoruz. 
Activiteyi ilgilendiren durumlarda Activitiy Context, genel App’i ilgilendiren durumlarda App Context kullanılır. 
hatta çoğu durumda getApplicationContext()  kullanmamız daha iyi olur genelde  Appi etkileyen durumlar activiteyi de etkiler.

Eğer ben this  kullanırsam mesela bir metod içerisinde bir üstünü referance alır Main Activity mesela.
Başka nereye referans verebilir ? Listenerların içerisinde this dersek listener’ın kendisine referans vermiş oluruz.
