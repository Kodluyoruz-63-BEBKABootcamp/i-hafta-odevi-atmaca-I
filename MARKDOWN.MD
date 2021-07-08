#MARKDOWN
text-to-HTML yani yazıyı HTML'e çevirmemizi sağlar. Markdown formatı ile yazarken herhangi bir html etiketi yazmayız, markdown'ın syntax'ına uygun şekilde yazarız ve kulladığımız front-end ya da back-end dili ile bunu parse ederek html çıktısını alırız. Böylece yazan kişininde hata payı minimuma iner, daha okunaklı bir yazım tarzı oluşur.

#Başlık etiketleri
HTML'de <h1> <h2> diye oluşturduğumuz başlık etiketlerini markdown'da şöyle oluşturuyoruz.

#Paragraf
Bir paragraf için yeni bir satır oluşturmak yeterlidir. Her yeni satır bir paragraf olarak tanımlanır. Bir paragrafın tamamı tek bir satır olabileceği gibi, arada boş satır bırakmadan alt satırdan da devam etmek mümkündür. Paragraf tanımı Block-Level‘dır; div, pre, table gibi. Bu nedenle, yazılmadan önce bir satır boşluk (toplamda 2 ENTER) bırakılmalıdır. Span-Level (inline) elemanlar olduğu gibi yazılabilir. Line Break (<br \>) için satır sonunda 2 boşluk (space) kullanılır.

#Kalın, Eğik Yazı ve Monospace
Bir metni bold (kalın), eğik (italic) veya her ikisi ile birlikte biçimlendirmek mümkündür. Bold için metnin önüne ve ardına **, italic için _, monospace için ise ``` eklemek yeterlidir.
Yatay Çizgi
Metin bölümlendirme / ayırma amacıyla kullandığımız horizontal rule için --- kullanmak yeterlidir.
Listeler
Bullet list için * ve numbered list için rakam kullanılabilmektedir.
Bağlantı
Bir metni bağlantı haline getirmek için metin köşeli parantez içerisine alınır ve yanında parantez içerisinde ilişkilendirilecek bağlantı belirtilir.
Görsel
Metin içerisinde görseller de kullanmamız mümkün. Görsel tanımı için ünlem ve köşeli parantez içerisinde görselin alt, parantez içerisinde görselin adı / yolu, tırnak içerisinde title tanımları yapılır.
Alıntı
Bir cümleyi alıntı olarak belirtmek için cümlenin başına > koymamız yeterlidir.

