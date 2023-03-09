1- Python'da Veri Tiplerini araştırınız, her bir veri tipi için kendi cümlelerinizle açıklamalar yazınız.

    String (Metin) Veri Tipleri (metinsel verilerin tutulduğu veri tipidir)
      Örnek:
      x = "Hello World!"

    Sayısal Veri Tipleri => int, float, complex
      Örnek:
      x = 20 # int (integer - tam sayıların tutulduğu veri tipidir)
      x = 20.50 # float (ondalıklı sayıların tutulduğu veri tipidir)
      z = 10k # complex (karmaşık sayıların tutulduğu veri tipidir)

    Sequence (Sıralama) Veri Tipleri => list, tuple, range
      Örnek:
      x = ["Ankara", "İstanbul", "İzmir"] # list (sıralanabilen ve değiştirilebilen elemanlardan oluşur)

    Mapping (Haritalama - Adresleme) Veri Tipleri => dict (Bu veri tipinde her anahtarın bir değeri vardır.)
       Örnek:
       x = {"name" : "John", "age" : 36}

    Set Veri Tipleri: İçindeki öğeler benzersizdir, tekrar etmezler, sırasızdırlar.
       Örnek:
       x = {"elma", "muz", "çilek"}

    Bool (Boolean) Veri Tipleri: Mantıksal veri tipleridir. Sadece iki değer alabilir: True/False

2- Kodlama.io sitesinde değişken olarak kullanıldığını düşündüğünüz verileri, veri tipleriyle birlikte örneklendiriniz.

    String veri tipine navigasyondaki Kurslarım, Tüm Kurslar, Kariyer, Sık Sorulan Solrular gibi metinsel verileri örnek verebiliriz.

    Sayısal veri tipine kurslardaki ilerleme kısımlarında yazan ilerleme yüzde değerlerini %60, %100 vb. örnek verebiliriz.

    List veri tipine Kategori ve Eğitmen kısımlarını örnek verebiliriz.
    egitmen = ["Engin Demiroğ", "Halit Enes Kalaycı"]

3- Kodlama.io sitesinde şart blokları kullanıldığını düşündüğünüz kısımları örneklendiriniz ve Python dilinde bu örnekleri koda dökünüz.

    Siteye giriş için kullanıcı adı ve şifte kullanılması örnek verilebilir.

    userName = "john@doe.com"
    userPass = "1a2b345"

    userNameInput = input()
    userPasswordInput= input()

    if userName == userNameInput and userPass == userPasswordInput:
      print("Login completed")
    else:
      print("Wrong user name or password!")

    Derslerdeki bitir ve devam et butonları ve solda listede çıkan tamamlandı simgesi örnek verilebilir.
