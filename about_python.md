# Python Hakkında

Python hem basit hem de güçlü olan nadir programlama dillerinden bir tanesidir. Problem çözerken programlama dilinin sözdizimi ve yapısına odaklanmaktansa doğrudan çözüme odaklandığımızı gördükçe şaşıracağız.

Python resmi tanıtımını aşağıda görebiliriz:

> Python öğrenmesi kolay ve güçlü bir programlama dilidir. Etkili yüksek seviyeli veri yapıları ve nesne yönelimli programlamaya basit ama etkili bir yaklaşımı olan bir programlama dilidir. Python'ın yorumlanan doğasıyla beraber zarif sözdizimi ve dinamik yazımı, neredeyse tüm platformlarda birçok alanda betik yazımında ve hızlı uygulama geliştirmede onu ideal bir programlama dili haline getiriyor.

Bu özellikleri çoğuna, sonraki bölümde detaylıca değineceğiz.

## İsmin arkasındaki hikaye

Guido van Rossum, Python dilinin yaratıcısı,  BBC dizisi "Monty Python's Flying Circus"dan esinlenerek dile ismini verdi. Onun yılanlara özel bir ilgisi yok.

## Python'ın Özellikleri

### Basit

Python basit ve minimalistik bir dildir. İyi bir Python programını okumak, İngilizce okumak gibi hissettirir, ancak oldukça sıkı bir  İngilizce! Python'ın bu sözde kod tarzı doğası, onun en güçlü özelliklerinden bir tanesidir. Dilin kendisindense doğrudan problemin çözümüne odaklanmamıza imkan tanır.

### Öğrenmesi Kolay

Göreceğimiz üzere, Python, başlaması müthiş seviyede kolay bir dildir. Python'ın olağanüstü kolay bir sözdizimi vardır.

### Özgür ve Açık Kaynaklı

Python bir _FLOSS_ \(Free/Libré and Open Source Software\) \(Özgür ve Açık Kaynaklı Yazılım\) örneğidir. Kısacası, kopyalarını özgürce dağıtabiliriz,  kaynak kodlarını okuyabiliriz, bunlar üzerinde değişiklikler yapabiliriz ve yeni özgür programlarda kullanabiliriz. FLOSS, bilgiyi paylaşan topluluk konseptine dayanır. Python'ın bu kadar iyi olmasındaki sebeplerden biri budur - daha iyi bir Python görmek isteyen bir topluluk tarafından yaratılmıştır ve sürekli olarak geliştirilmektedir.

### Yüksek Seviyeli Dil

Programlarımızı Python ile yazdığımızda, programımızın ne kadar hafıza kullandığı konular gibi düşük seviyeli konulardan dolayı rahatsızlık duymayız.

### Portatif

Açık kaynaklı doğası sayesinde, Python birçok platforma uyum sağladı \(i.e. üzerinde çalışacak şekilde\). Sisteme bağlı özelliklerden kaçınmak için yeterince dikkatli olursanız, tüm Python programlarınız bu platformlardan herhangi birinde herhangi bir değişiklik gerektirmeden çalışabilir.

Python'ın çalışabileceği işletim sistemlerinden bazıları bunlar; GNU/Linux, Windows, FreeBSD, Macintosh, Solaris, OS/2, Amiga, AROS, AS/400, BeOS, OS/390, z/OS, Palm OS, QNX, VMS, Psion, Acorn RISC OS, VxWorks, PlayStation, Sharp Zaurus, Windows CE and PocketPC!

Hatta [Kivy](http://kivy.org) gibi platformlar sayesinde bilgisayarımız, iPhone, iPad ve Android cihazlarımız için uygulama bile geliştirebiliriz.

### Yorumlanan

Bu bir miktar açıklama gerektirir.

C veya C++ gibi derlenen dillerle yazılan programlar, kaynak kodlarından, derleyici kullanılarak, bilgisayarın konuştuğu dile çevrilir \(binary code i.e. 0'lar ve 1'ler\). Programı çalıştırdığımızda, bağlayıcı/yükleyici yazılım programı hard disk'ten hafızaya kopyalar ve onu çalıştırır.

Python, diğer türlü çalışır, binary'e derlenmeye gerek duymaz. Programı direk kaynak kodundan çalıştırırız. İçerde, Python kaynak kodu ara form olan bytecode'lara çevirir ve sonra bunu bilgisayarın ana diline çevirir ve sonra çalıştırır. Tüm bunlar, aslında, Python kullanmayı çok daha fazla kolaylaştırır, çünkü programlarımızı derleme derdimiz olmaz, uygun kütüphanelerin bağlandığına ve yüklendiğine emin oluruz, ve bunun gibi farklı faydaları da sağlar. Bu aynı zamanda Python programlarımızı çok daha portatif yapar, çünkü Python programımızı başka bir bilgisayara kopyalıyoruz ve direk çalışıyor!

### Nesneye Yönelik

Python Nesneye Yönelik Programlamayı desteklediği gibi Prosedür Odaklı Programlamayı da destekler. Prosedür Odaklı Dillerde, bir program yeniden kullanılabilir program parçalarından başka bir şey olmayan prosedürler ve fonksiyonlardan oluşur. Nesneye Yönelik Programlamada, bir program, veri ve fonksiyonelliği birleştiren objelerden oluşur. Python çok güçlü ama, özellikle C++ veya Java gibi büyük dillere kıyasla basit bir OOP\(Nesneye Yönelik Programlama\) yapısına sahiptir.

### Genişletilebilir

Çok hızlı çalışması için kritik bir kod parçasına ihtiyacımız varsa veya bir algoritma parçasının kapalı kaynak olmasını istiyorsak, programımızın o bölümünü C veya C ++ ile kodlayabilir ve ardından Python programımızda kullanabiliriz.

### Gömülebilir

Python programlarımızı, programın kullanıcılarına betik kapasitelerini sunabilmek için C/C++ programlarımıza gömebiliriz.

### Kapsamlı Kütüphaneler

Python Standart Kütüphanesi oldukça kapsamlı. Çeşitli görevleri gerçekleştirmemiz için kütüphaneler içeriyor; regular expression'ları kullanma, döküman üretme, unit testing, threading, veritabanı işlemleri, web tarayıcıları, CGI, FTP, email, XML, XML-RPC, HTML, WAV dosyaları, kriptografi, GUI \(grafiksel kullanıcı arayüzü\), ve diğer sisteme bağımlı görevler. Hatırlayalım, Python'ın kurulu olduğu bir yerde bunların hepsi kullanıma açık olmuş oluyor. Bu durum, Python'da "_Batteries Included"_ felsefesi diye anılır.

Standart kütüphanenin yanı sıra, [Python Package Index](http://pypi.python.org/pypi) üzerinden bulabileceğimiz çeşitli yüksek kaliteli kütüphaneler de mevcut.

### Özet

Python aslında heyecan verici ve güçlü bir dil. Doğru performans ve özellik kombinasyonu sayesinde Python'da program yazmak hem eğlenceli hem de kolaydır.

## Python 3 ile Python 2 Farkları

"Python sürüm 2" ve "Python sürüm 3" arasındaki farkla ilgilenmiyorsak bu bölümü göz ardı edebiliriz. Ama hangi versiyonu kullandığımızın farkında olmamız gerekir. Bu kitap Python versiyon 3 için yazılmıştır.

Bir versiyonunu yeterince anladığımızda ve kullanmasını öğrendiğimizde, farklılıkları kolaylıkla öğrenebilir ve diğerini kullanabiliriz. Zor olan programlamayı ve Python dilinin temellerini öğrenmektir. Bu kitabın amacı bu, ve bu görevi bir defa tamamlarsak, içinde bulunduğumuz duruma göre kolaylıkla Python 2 veya Python 3 kullanabiliriz.

Python 2 ve Python 3 arasındaki farkların detayları için aşağıdaki kaynaklara göz atabiliriz:

* [The future of Python 2](http://lwn.net/Articles/547191/)
* [Porting Python 2 Code to Python 3](https://docs.python.org/3/howto/pyporting.html)
* [Writing code that runs under both Python2 and 3](https://wiki.python.org/moin/PortingToPy3k/BilingualQuickRef)
* [Supporting Python 3: An in-depth guide](http://python3porting.com)

## Yazılımcıların Fikirleri

Büyük yazılımcıların Python hakkında söyledikleri ilgimizi çekebilir:

* "The Cathedral and the Bazaar" kitabının yazarı ve aynı zamanda _Open Source_. felsefesi savunucusu olan _Eric S. Raymond_

   bu yazıyı yazmış [Python has become his favorite programming language](http://www.python.org/about/success/esr/). Bu makale Python'a başladığım zamanlarda gerçek ilham kaynağımdı.

* 'Thinking in Java' ve 'Thinking in C++' kitaplarının ünlü yazarı _Bruce Eckel_. Kendisini hiçbir dilin Python kadar üretken yapmadığını söylüyor. Python'un belki de programcı için işleri kolaylaştırmaya odaklanan tek dil olduğunu söylüyor. Daha fazla detay için [complete interview](http://www.artima.com/intv/aboutme.html)\(tüm röportajı\) buradan inceleyebiliriz.
* _Peter Norvig_ iyi bilinen Lisp yazarıdır ve Google Arama Kalitesi Direktörü. Diyor ki [writing Python is like writing in pseudocode](https://news.ycombinator.com/item?id=1803815)\(Python yazmak sözde kod yazmak gibidir\). Python'un her zaman Google'ın ayrılmaz bir parçası olduğunu söylüyor. Yazılım mühendisleri için bir gereklilik olarak Python bilgisi isteyen [Google Jobs](http://www.google.com/jobs/index.html) Google Jobs sayfasına bakarak bu ifadeyi gerçekten doğrulayabiliriz.

  

