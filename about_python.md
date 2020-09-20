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

Programlarımızı Python ile yazdığımızda, programımızın ne kadar hafıza yediği konular gibi düşük seviyeli konulardan dolayı rahatsızlık duymayız.





### Portable

Due to its open-source nature, Python has been ported to \(i.e. changed to make it work on\) many platforms. All your Python programs can work on any of these platforms without requiring any changes at all if you are careful enough to avoid any system-dependent features.

You can use Python on GNU/Linux, Windows, FreeBSD, Macintosh, Solaris, OS/2, Amiga, AROS, AS/400, BeOS, OS/390, z/OS, Palm OS, QNX, VMS, Psion, Acorn RISC OS, VxWorks, PlayStation, Sharp Zaurus, Windows CE and PocketPC!

You can even use a platform like [Kivy](http://kivy.org) to create games for your computer _and_ for iPhone, iPad, and Android.

### Interpreted

This requires a bit of explanation.

A program written in a compiled language like C or C++ is converted from the source language i.e. C or C++ into a language that is spoken by your computer \(binary code i.e. 0s and 1s\) using a compiler with various flags and options. When you run the program, the linker/loader software copies the program from hard disk to memory and starts running it.

Python, on the other hand, does not need compilation to binary. You just _run_ the program directly from the source code. Internally, Python converts the source code into an intermediate form called bytecodes and then translates this into the native language of your computer and then runs it. All this, actually, makes using Python much easier since you don't have to worry about compiling the program, making sure that the proper libraries are linked and loaded, etc. This also makes your Python programs much more portable, since you can just copy your Python program onto another computer and it just works!

### Object Oriented

Python supports procedure-oriented programming as well as object-oriented programming. In _procedure-oriented_ languages, the program is built around procedures or functions which are nothing but reusable pieces of programs. In _object-oriented_ languages, the program is built around objects which combine data and functionality. Python has a very powerful but simplistic way of doing OOP, especially when compared to big languages like C++ or Java.

### Extensible

If you need a critical piece of code to run very fast or want to have some piece of algorithm not to be open, you can code that part of your program in C or C++ and then use it from your Python program.

### Embeddable

You can embed Python within your C/C++ programs to give _scripting_ capabilities for your program's users.

### Extensive Libraries

The Python Standard Library is huge indeed. It can help you do various things involving regular expressions,documentation generation, unit testing, threading, databases, web browsers, CGI, FTP, email, XML, XML-RPC, HTML, WAV files, cryptography, GUI \(graphical user interfaces\), and other system-dependent stuff. Remember, all this is always available wherever Python is installed. This is called the _Batteries Included_ philosophy of Python.

Besides the standard library, there are various other high-quality libraries which you can find at the [Python Package Index](http://pypi.python.org/pypi).

### Summary

Python is indeed an exciting and powerful language. It has the right combination of performance and features that make writing programs in Python both fun and easy.

## Python 3 versus 2

You can ignore this section if you're not interested in the difference between "Python version 2" and "Python version 3". But please do be aware of which version you are using. This book is written for Python version 3.

Remember that once you have properly understood and learn to use one version, you can easily learn the differences and use the other one. The hard part is learning programming and understanding the basics of Python language itself. That is our goal in this book, and once you have achieved that goal, you can easily use Python 2 or Python 3 depending on your situation.

For details on differences between Python 2 and Python 3, see:

* [The future of Python 2](http://lwn.net/Articles/547191/)
* [Porting Python 2 Code to Python 3](https://docs.python.org/3/howto/pyporting.html)
* [Writing code that runs under both Python2 and 3](https://wiki.python.org/moin/PortingToPy3k/BilingualQuickRef)
* [Supporting Python 3: An in-depth guide](http://python3porting.com)

## What Programmers Say

You may find it interesting to read what great hackers like ESR have to say about Python:

* _Eric S. Raymond_ is the author of "The Cathedral and the Bazaar" and is also the person who coined the term _Open Source_. He says that [Python has become his favorite programming language](http://www.python.org/about/success/esr/). This article was the real inspiration for my first brush with Python.
* _Bruce Eckel_ is the author of the famous 'Thinking in Java' and 'Thinking in C++' books. He says that no language has made him more productive than Python. He says that Python is perhaps the only language that focuses on making things easier for the programmer. Read the [complete interview](http://www.artima.com/intv/aboutme.html) for more details.
* _Peter Norvig_ is a well-known Lisp author and Director of Search Quality at Google \(thanks to Guido van Rossum for pointing that out\). He says that [writing Python is like writing in pseudocode](https://news.ycombinator.com/item?id=1803815). He says that Python has always been an integral part of Google. You can actually verify this statement by looking at the [Google Jobs](http://www.google.com/jobs/index.html) page which lists Python knowledge as a requirement for software engineers.

