# Yazılım Teknikleri ve Diğer Yararlı Türkçe Kaynaklar
Software techniques and other useful Turkish resources 

<!-- Yakında eklenecek konular: AOP Nedir?, Design Pattern Nedir?, Bilgisayar ve Ağ Sistemleri Notları. -->

- [LİNUX ve VİM Komutları](https://github.com/b-tekinli/Yazilim-Teknikleri-ve-Diger-Yararli-Turkce-Kaynaklar#crud-fonksi%CC%87yonlari) <br />
- [CRUD Fonksiyonları](https://github.com/b-tekinli/Yazilim-Teknikleri-ve-Diger-Yararli-Turkce-Kaynaklar#crud-fonksi%CC%87yonlari) <br />
- [Nesne Tabanlı Programlama](https://github.com/b-tekinli/Yazilim-Teknikleri-ve-Diger-Yararli-Turkce-Kaynaklar#oop---nesne-tabanli-programlama---object-ori%CC%87ented-programmi%CC%87ng) <br />
- [SOLID Prensipleri](https://github.com/b-tekinli/Yazilim-Teknikleri-ve-Diger-Yararli-Turkce-Kaynaklar#solid-prensi%CC%87pleri%CC%87---solid-principle-) <br />
- [DRY Prensibi](https://github.com/b-tekinli/Yazilim-Teknikleri-ve-Diger-Yararli-Turkce-Kaynaklar#dry-prensi%CC%87bi%CC%87-dont-repeat-yourself)
- [KISS Prensibi](https://github.com/b-tekinli/Yazilim-Teknikleri-ve-Diger-Yararli-Turkce-Kaynaklar#kiss-prensi%CC%87bi%CC%87-keep-it-simple-stupid)
- [YAGNI Prensibi](https://github.com/b-tekinli/Yazilim-Teknikleri-ve-Diger-Yararli-Turkce-Kaynaklar#yagni-prensi%CC%87bi%CC%87-you-arent-gonna-need-it)
- [Windows Form App Notları](https://github.com/b-tekinli/Yazilim-Teknikleri-ve-Diger-Yararli-Turkce-Kaynaklar#windows-form-app-notlar%C4%B1)
- [Windows Form Toolbox Kısaltmaları](https://github.com/b-tekinli/Yazilim-Teknikleri-ve-Diger-Yararli-Turkce-Kaynaklar#wi%CC%87ndows-form-toolbox-kisaltmalari)


<br />


<details>
  
  <summary>:computer: LINUX VE VIM</summary>
  
## [LİNUX ve VİM Komutları]()
### LİNUX KOMUTLARI <br />
- date : tarih ve saati verir.
- ls : bulunduğumuz dizindeki klasörleri listeler.
o Parametre belirtme örnek: ls -a bu komut aynı zamanda gizli dosyaları listeler.
- ls -l : bu komut dosyaları dizin içerisinde listeli bir şekilde gösterir. Dosyalar en son ne zaman kim tarafından değiştirildi, yazma izinleri gibi bilgileri gösterir.
- Tab tuşu kullanımı:  daha çok, uzun isimli dosyalara gitmek istediğimizde dosyanın sadece baş harfini ya da duruma göre birkaç harfini yazıp tab tuşuna başarınca dosya 	adının tamamını yazar.
- man : Kullanıcı klavuzu okumak için yapılır.  man ls, man date gibi.
- history : geçmişte yaptığımız komut satırı geçmişini gösterir. Özellikle bilgisayar kapanırsa falan çok işimize yarar.

 ### LİNUX DOSYA KOMUTLARI
- Linux’ta her şey dosyadır ve dosya sistemi hiyerarşiktir.
- Dosyalar(-) : yanında da gördüğünüz gibi – ile gösterilir.
- Dizinler(d) : d ile gösterilir.
- Bağlantılar(l) : inglizcesi link’tir. l harfi ile gösterilir.
- /Kök Dizin: sağa yatık taksim / ile gösterilir ve kök dizinden daha üst dizine çıkılmaz çünkü en üstteki dizindir yani hiyerarşinin başladığı yerdir. Tüm dizinleri 		içerir.
- /bin : temel kullanıcı komutlarıdır yani programlarını içeren klasör.
- /boot : Bilgisayarın açılışında kullanılan dosyaların yer aldığı statik klasör.
- /dev : cihaz dosyaları.
- /etc : sisteme özel ayarların özellikle konfigürasyonların bulunduğu klasördür.
- /home : kullanıcı ana dizinlerini tutan klasördür.
- /lib : temel kütüphaneler ve çekirdek modüllerinin tutulduğu klasördür.
- /media : çıkarılabilir ortam dosyalarını yani flash bellek taktığımızda içindekileri tutan klasördür.
- /mnt : yerleştirilen, harici olarak takılan hdd gibi dosyaları tutan klasördür.
- /srv : servis dosyaları.
- /tmp : geçici dosyalar. herkesin okuma ve yazma izni vardır.
- /var : çeşitli dosyalar. Örnek: log dosyalarının tutulduğu kalsördür.
- /root : root kullanıcısı için ana dizindir.
- cd : istediğimiz dosyalar arasında gezinmemizi sağlar.
- cd Desktop  Masaüstüne gider.
- cd ..  bulunduğumuz dosyadan geri çıkmayı yani 1 üst dizine çıkmamızı sağlar.
- pwd : bulunduğumuz klasörün hangi dizinler altında olduğunu belirtir.
- mkdir : dosya oluşturmamızı sağlar. Örnek: mkdir denemeDosyasi
- touch : dosyaları uzantılarıyla oluşturmamızı sağlar. 
- Birden fazla dosyayı aynı satırda oluşturabiliriz. 
	Örnek: touch deneme ornek dosya asdfs gibi.
	Örnek: mkdir deneme ornek dosyaAdi gibi.
- rm : dosyayı silmemizi sağlar. Örnek: rm odev.txt gibi. Birden fazla dosyayı aralarında boşluk bırarak dosya oluşturmada yaptığımız gibi silebiliriz.
- -r parametresi : dosya siler ve dizinlerin içindeki dosya ve klasörleri de siler. 
	Örnek: rm -r hafta 1 gibi. Birden fazla dosyayı aynı anda silebiliriz.
- cp : dosyaları kopyalamızı sağlar. Örnek: cp ders gibi.
- Kopyalamak istediğimiz dosyayı başka klasörlere de kopyalayabiliriz.
	Örnek: cp kopyalanacakDosya kopyalanacakDosyaDizini/ 
- cd kopyalanacakDosyaDizini/
- ls -l
- Bir üst dizine de kopyalayabiliriz.
	<br />
	
	Örnek: cp kopyalanacakDosya ../
	
	<br />
	
		Dizin kopyalama işlemi:
		mkdir dersler
		ls -l
		cp -r matematik/ dersler/
		cd dersler
		ls -l
VİM
### Vim NEDİR ?
:arrow_right: Vim bir metin editörüdür. Öğrenmesi zahmetli olduğu kadar zevkli olan, öğrenildikten sonra vazgeçemeyeceğiniz bir editör. <br />
Komut satırından:
:arrow_right: vim -O deneme1.c deneme2.c  > Dikey pencerelerde .c uzantılı 2 dosya açar. <br />
:arrow_right: vim -o deneme3.c deneme4.c > Yatay pencerelerde .c uzantılı 2 dosya açar. <br />
:arrow_right: CTRL+W 	> Yatay ve dikey pencereler arası geçiş. <br />
	Önemli Uyarı:
	BİR ELEKTRİK KESİNTİSİ VEYA SİSTEMİ RESTART YAPTIGINIZDA EGER O AN VİM İLE CALISIYORSANIZ VİM BİRDAHAKİ ACISINIZDA O DOSYAYA SADECE OKUMA İZNİ VERİR.
<br />	
YAZMA İZNİ İÇİN;
:arrow_right: :w!  komutu verilmelidir. <br />
Kullanılabilir komutlar : <br />
:arrow_right: vim deneme.txt > deneme.txt adında bir dosya oluşturur. <br />
:arrow_right: i  > vim de yazı yazma moduna geçer(insert) <br />

:arrow_right: ESC > ESC tuşu ile komut verme moduna geçilir.Yani komut vermek için her defasında esc tusuna basılmalı. <br />

:arrow_right: :q > Çıkmak için kullanılır.Kaydetmeden çıkılırsa hata verir. <br />

:arrow_right: :wq > Yaz ve çık <br />
:arrow_right: h > Metin üzerinde sola gider <br />
:arrow_right: l > Sağa gider <br />
:arrow_right: k > Yukarı <br />
:arrow_right: j > Asağı <br />
		Not:Yön tuşları yerine h-l-j-k kullanımı hızlanmayı sağlar. <br />
:arrow_right: fm  > “Sadece” bulundugu satırda ileriye doğru ‘m’ araması yapar. <br />
:arrow_right: fa > “Sadece” bulundugu satırda geriye doğru ‘a’ araması yapar. <br />
:arrow_right: 0 > Satır başına git <br />
:arrow_right: $ > Satır sonuna git <br />
:arrow_right: 2$ > Bir alttaki satırın sonuna git <br />
:arrow_right: 5$ > 4 alttaki satırın sonuna git <br />
:arrow_right: 33w > 33 kelime ileri git <br />
:arrow_right: 14b > 14 kelime geri git <br />
:arrow_right: G > Dosyanın son satırına git <br />
:arrow_right: 1G > Dosyanın ilk satırına git <br />
:arrow_right: 24G > Dosyanın 24.satırına git <br />
:arrow_right: 33w > 33 kelime ileri git <br />
:arrow_right: G > Dosyanın son satırına git <br />
:arrow_right: 1G > Dosyanın ilk satırına git <br />
:arrow_right: :set number > Ekranın soluna satır numaraları ekler! <br />
:arrow_right: :set nonumber 	 > Satır numaralarını kaldırır. <br />
:arrow_right: /linux > metin içinde linux kelimesini arar <br />
:arrow_right: :set hlsearch 	 > Aranan kelimeleri renklendirir. <br />
:arrow_right: :set nohlsearch  > hlsearch özelliğini kapatır. <br />
:arrow_right: yy > Bulundugu Satırı kopyalar <br />
:arrow_right: 3y > 3 satırı kopyalar <br />
:arrow_right: . > Kopyalanan satırı yapıştırır <br />
:arrow_right: G > Dosya sonuna git <br />
:arrow_right: ~ > İmlecin bulundugu yerdeki harfi kücük/büyük harfle değiştir <br />
:arrow_right: 4~ > önündeki 4 karakteri kücük/büyük harfe dönüştür. <br />
:arrow_right: :split > Ekranı pencerelere böl <br />
:arrow_right: V > Visual mod -> Bu modda fare ile hareket ettirilen satırlar renklenir. <br />
:arrow_right: > > Bulundugu satırı shift genişliği kadar kaydırır(Visual modda) <br />
:arrow_right: :syntax on > Tanınmayan dosya türlerinde metni renklendirir <br />
:arrow_right: :set shiftwidth=4 > Tab boşluğunu ayarlar <br />
:arrow_right: :mkvimrc dosyaismi > set vb yapılan ayarların saklanmasını sağlar. <br />
:arrow_right: :source dosyaismi > kaydedilen ayarları çağırır. <br />
	
</details>

<details>
	
<summary>:hammer_and_wrench: CRUD</summary>

## [CRUD FONKSİYONLARI](https://github.com/b-tekinli/Yazilim-Teknikleri-ve-Diger-Yararli-Turkce-Kaynaklar/blob/main/CRUD%20Fonksiyonlar%C4%B1.docx)

Veritabanı Kayıt (Ekleme, Okuma, Güncelleme ve Silme) İşlemleri


![crud](https://github.com/b-tekinli/Yazilim-Teknikleri-ve-Diger-Yararli-Turkce-Kaynaklar/blob/main/images/crud.jpg)


o	Programlamada oluşturma, okuma, güncelleme ve silme, veri depolamada kullanılan dört temel fonksiyondur. Terim ilk kez James Martin'in 1983 tarihli kitabı Managing the Data-base Environment'ta kullanılmıştır.


-	Create :left_right_arrow: Yaratma, oluşturma, ekleme
-	Read :left_right_arrow: Okuma
-	Update  :left_right_arrow: Güncelleme
-	Delete :left_right_arrow: Silme


Bir programlama dili veya uygulama CRUD ifadesi ile birlikte anılıyorsa uygulamanın, kodun ya da ürünün temelinde veritabanına yönelik işlemlerinin yer aldığını anlarız. 

Örneğin: Python veritabanı işlemleri şeklinde yapacağımız bir arama veritabanına yönelik pek çok konuyu kapsayabilecekken Python CRUD işlemleri dediğimizde konumuzu veritabanına verinin eklenmesi ve bu verinin yönetimi bağlamında sınırlandırmış oluruz.

<br />
<br />
<br />

</details>

<details>
  
  <summary>:gear: OOP</summary>

## [OOP - NESNE TABANLI PROGRAMLAMA - OBJECT ORİENTED PROGRAMMİNG](https://github.com/b-tekinli/Yazilim-Teknikleri-ve-Diger-Yararli-Turkce-Kaynaklar/blob/main/OOP.docx)

![oop](https://github.com/b-tekinli/Yazilim-Teknikleri-ve-Diger-Yararli-Turkce-Kaynaklar/blob/main/images/oop.png?raw=true)

 	Gerçek dünyadaki nesnelerin tasarımı sınıf içinde yapılır.

 	Sınıftan nesne üretilip değişiklik yapılmak istendiğinde tüm programda değişiklik yapmak gerekmez sadece oluşturulan nesnenin sınıf içinde değişiklik yapmak yeterlidir.

 	Oluşturulan nesneler birbirinden bağımsız olduğu için bilgi gizleme olanağı artar.
Örneğin: A nesnesi B nesnesinin özelliklerini kullanamaz ve erişemez.

 	Nesne oluşturma bir sınıf içerisinde gerçekleştirilir ve bu kodlar başka projelerde kullanılabilir.
Örneğin: Bir A nesnesi oluşturduysak bunu birçok yerde kullanabiliriz.

 	Sınıflar oluşturarak daha az kod oluşturup daha fazla iş yapıp kod tekrarı önlenir.
Örneğin: İnsan sınıfında ad, soyad, yaş vb. gibi özellikleri bir defa oluşturup istediğimiz kadar kullanabiliriz.

<br />

 Class (Sınıf):

Gerçek dünyadaki nesnelerin özellikleri ve davranışları sınıflara aktarılır. 
Bu durumların sınıflara aktarılması metodlarla (fonksiyonlarla) olur. Sınıfta tanımlanan metot ve değişkenlere sınıfın üyeleri denir. Değişkenler ad, soyad, yaş gibi kullanacağımız bilgileri saklamaktadır.
Metotlar ise, kullanıcı kaydı, iki sayısının toplamı gibi bir görevi yerine getiren alt programlardır.
Sınıf soyut bir kavramdır doğrudan kullanılamaz nesne oluşturup kullanabiliriz.

<br />

 Nesne (Object):

İçinde veri saklayan ve bu veriler üzerinde işlem yapacak olan metodlar bulunduran bileşenlerdir. 
Nesneler her uygulamada tekrar kullanılabilir. Nesne oluşturduğumuzda hafızada yer kaplar.

<br />

 Nesne Yönelimli Programlama Özellikleri

1. Abstraction - Soyutlama :left_right_arrow: Bir sınıfta davranış ve özelliklerin tanımlanmasına soyutlama diyoruz.
Örneğin: Araba sınıfında rengi, modeli, tekerlek sayısı, motor gücü, özellikleridir(property).
Hızlanması, fren yapması, durması davranışlarıdır ve metotlar (fonksiyonlar) ile tanımlanır.

<br />

2. Inheritance - Miras Alma / Kalıtım :left_right_arrow: Sınıflar birbirinden türeyebilir. Alt sınıf üst sınıfın özelliklerini alabilir.
Örneğin: Araba ve bisiklet sınıflarında ortak özellik olarak tekerlek sayısı, hızı gibi özelliklerini tekrar yazmak yerine bu özellikleri içeren bir sınıf oluşturup miras alabiliriz. Bir sınıftan birden fazla miras alınıyorsa buna çoklu kalıtım denir.

<br />

3. Polymorphism - Çok Biçimlilik :left_right_arrow: Alt sınıflar üst sınıfın gösterdiği davranışları göstermek zorunda değildir. Alt sınıfların farklı davranışları göstermesine Çok biçimlilik denilmektedir.
Örneğin: Gemi ve araba sınıflarını ele aldığımızda bunların hareket tipleri bulunmaktadır. Gemi su üzerinden giderken araba karada hareket etmektedir. Kısaca farklı nesnelerin (araba ve gemi gibi) aynı olaya (hareket tipine) farklı şekilde cevap vermesidir.

<br />

4. Encapsulation - Kapsülleme :left_right_arrow: Davranış ve özellikler sınıfta soyutlanarak kapsüllenir. Kapsülleme ile hangi özellik ve davranışın dışarıya sunulup sunulmayacağını belirleriz.
Örneğin: İnsan sınıfında yemek alışkanlığı bizi ilgilendirmiyorsa bunu kapalı (private) yapıp gizleriz. Ancak ad soyad gibi bilgiler bizi ilgilendirdiği için bunlar açık bırakılır. Bu olaya bilgi saklama yani kapsülleme denilmektedir. Bilgi saklama erişim belirteçleri (public, private, protected, internal) ile gerçekleştirilir.

<br />

 Erişim Belirteçleri
- public: Herkesin kullanabileceği özellik ve davranışlardır.
- private: Sadece kendi sınıfta kullanılabilen özellikler ve davranışlardır.
- protected: Sınıf içinde ve miras alınan alt sınıflarda kullanılır.
- internal: Aynı program içerisinden erişilebilir, fakat farklı bir program içerisinden erişilemez.

<br />
<br />

</details>

<details>
  
  <summary>:books: Prensipler</summary>

## [SOLID PRENSİPLERİ - SOLID PRINCIPLE ](https://github.com/b-tekinli/Yazilim-Teknikleri-ve-Diger-Yararli-Turkce-Kaynaklar/blob/main/SOLID%20Prensipleri.docx)
### Robert C. Martin (Uncle Bob)

![solid](https://github.com/b-tekinli/Yazilim-Teknikleri-ve-Diger-Yararli-Turkce-Kaynaklar/blob/main/images/solid.png)



 	Single Responsibility :left_right_arrow: Tek Sorumluluk Prensibi / İlkesi


 	Open Closed :left_right_arrow: Açık Kapalı Prensibi / İlkesi


 	Liskov Substitution :left_right_arrow: Liskov’un Yerine Geçme Prensibi / İlkesi


 	Interface Segregation :left_right_arrow: Arayüzlerin Ayrışması ve Ayrılması Prensibi


 	Dependency Inversion :left_right_arrow: Bağımlılıkların Tersine Çevrilmesi Prensibi



1. Single Responsibility Principle:

-	Bir sınıfın, bir metodun, her bir iş yapan yapının tek bir görevi olması gerektiğini savunur.

-	Bir metod sadece kendi görevini yapmalı, bir sınıf sadece o sınıfla ilgili metodları, alanları, özellikleri barındırmalıdır.

-	Birden fazla işle veya katmanla ilişkilendirilmemeli, her bir yapının tek bir sorumluluğu olmalıdır.

Örnek: Bir restoranda tüm işi tek bir kişi yapsaydı nasıl olurdu? Garsonluk, temizlik, yemekler ve bir de hesaba bakmak var tabii. Görseldeki örnek gibi her şey çok karışırdı değil mi? Peki o restoranda çalışan birçok kişi olsa ve herkesin farklı görevleri olup herkes kendi işini yapsa? İşte Single Responsibility Principle (Tek Sorumluluk İlkesi) de bu şekildedir.
 
![single responsibility](https://github.com/b-tekinli/Yazilim-Teknikleri-ve-Diger-Yararli-Turkce-Kaynaklar/blob/main/images/singleResponsibility.png)

Yazılım tarafında örnek verecek olursak her class’ın tek bir tane sorumluluğu olmalıdır diyebiliriz. Product sınıfında product dışında hiçbir class özelliği olmamalıdır. Özetle, SOLID Prensiplerinin S’si her class tek bir sorumluluktan ibaret olmalıdır diyor.

<br />

2. Open Closed Principle:

-	Bir yazılımda yeni bir özellik talep edildiğinde mevcut kodların değiştirilmeden yeni özelliğin geliştirilebiliyor olması gerekmektedir.

-	Yeni özellik, geliştirme istediğinde yazılımımız bize direnç göstermemelidir.

-	Yazılım değiştirilmeye kapalı, geliştirilmeye açık olmalıdır.

Örnek: Bilgisayarımızda ram yetersiz olduğunda bilgisayarın hiçbir yerini bozmadan işlemci ya da klavye gibi farklı yerlerine dokunmadan sadece ram takılan kısma gelip ekleyebiliyoruz. 

Görselde de gördüğünüz gibi kodlarımızın tamamı dikdörtgen ve kareden oluşuyor olsa ona yeni bir özellik eklemek istesek alttaki karenin yanına 1 kare daha ekleyip ortadaki büyük kareyi elde etmiş üstelik bunu hiçbir koda dokunmadan yapmış oluruz.

Fakat diğer yandan kodlarımız ortadaki kareden oluşuyor olsa ve onu Open Closed İlkesine göre yapmamış olsak bir özellik çıkartmak istediğimizde karenin 4 köşesinden de kesmemiz gerekir ki daire şeklini ancak alabilsin..

![open closed](https://github.com/b-tekinli/Yazilim-Teknikleri-ve-Diger-Yararli-Turkce-Kaynaklar/blob/main/images/openClosed.png)

Yazılım tarafında da olay aynen bu şekilde olmalıdır. Yaptığımız programa yeni bir özellik ekleyeceğimiz zaman kodlarımızın hiçbir yerine dokunmadan o özelliği pıt pıt entegre edebiliyor olmalıyız.

<br />

3. Liskov Substitution Principle:

-	Hiçbir değişikliğe ihtiyaç duymadan alt sınıfları, miras aldıkları – türedikleri üst sınıfların yerine kullanabilmeliyiz.

-	Alt sınıflar miras aldıkları üst sınıfların tüm özelliklerini barındırıyor olabilirler.


-	Sadece birbirine benziyor diye sınıflar birbirinden miras (kalıtım) almamalıdır. Alt sınıf üst sınıfın özelliklerini, metodlarını mutlaka kullanmalıdır ve yer değiştirdiğinde doğru sonuçları verecek şekilde bozulmadan çalışmalıdır.

Örnek: Yukarıda son paragrafta kalın ve italik yazdığım cümleyi tekrar okumanızı rica edip görselden örnek verecek olursak şöyle açıklayabiliriz: Canlı ve oyuncak ördeğin tabii ki yapabildikleri bazı şeyler kısıtlıdır. Bir metodumuz olduğunu düşünün bu metotta yüzmek, ses çıkartmak ve uçmak olsun. Her 2 ördek ses çıkartabilir oyuncak ördeğe bastığımızda ses çıkartacaktır. 2 ördek de yüzebilir oyuncak ördeği su üzerine koyduğumuzda suyun dibine çökmeyecektir. Fakat uçma konusunda oyuncak olan doğal olarak uçamayacaktır.
Dolayısıyla yazılım kısmında da sırf 2 ördek birbirine benziyor diye miras aldığımız zaman oyuncak ördeğin uçma fonksiyonu bize hata fırlatacaktır ya da çalışmayacak, boş kalacaktır.

![liskov substitution](https://github.com/b-tekinli/Yazilim-Teknikleri-ve-Diger-Yararli-Turkce-Kaynaklar/blob/main/images/liskovSubstitution.png)

<br />
 
4. Interface Segregation Principle:

-	Arayüzü implement eden sınıfların gereksiz metod bulundurmaması gerekir.

-	Sorumlulukları tek bir arayüze tanımlamak yerine daha özelleştirilmiş birbirinden ayrı arayüzler oluşturmak gerekir.

-	Arayüzler birbirinden ayrılmadığında bu arayüzü implement eden sınıflarda gereksiz metodlar veya özellikler olacaktır. Ortak olmayan her bir sorumluluk için ayrı bir arayüz oluşturulması gerekmektedir.

Örnek: Düşünün ki bir araba üreticisisiniz. Arabanıza default (varsayılan) olarak gaza bas, frene bas ve müzik çalar gibi özellikler vereceksiniz. Bu özellikleri bir arayüzde topladınız ve Audi marka bir arabaya implement ettiniz.
Fakat daha düşük model bir araba olan Murat 131’ e de bu arayüzü implement etseniz o arabada müzik çalar özelliği olmadığından müzik çalar kısmına gereksiz, boş düğmeler eklemek zorunda kalırsınız. Yani interfaceler içerisine yazılan şeyleri zorunlu hale getirdiği için bu özelliği desteklemeyen bir arabaya müzik çaları default olarak koymak zorunda olursunuz. Bu durumda Audi’yi ayrı Murat131’i ayrı implement etmeniz gerekli. Ortak olan özellikleri aynı arayüzde ortak olmayanları ise ayrı arayüzlere böl, parçala…
Kısacası, SOLID Prensiplerinin I’sı senin bir özelliğin ortak değilse sen de bu ortak olmayan özelliği ayrıştır diyor.

![interface segregation](https://github.com/b-tekinli/Yazilim-Teknikleri-ve-Diger-Yararli-Turkce-Kaynaklar/blob/main/images/interfaceSegregation.png)

<br />
 
5. Dependency Inversion Principle:

-	Sınıflar arasındaki bağımlılık en aza indirgenmelidir.

-	Üst sınıflar, alt sınıflara bağımlı olmamalıdır. Tüm somut sınıflar soyutlanma yöntemi ile bağımlılıkları azaltılmalıdır.


-	Alt sınıflardaki yapılacak değişiklikler üst sınıfları etkilememelidir.

    o	Peki, bütün bu sorunlardan kurtulmanın yolu nedir ? <br />
Cevap:  Yüksek seviye ve düşük seviye sınıflar arasında bir soyutlama katmanı oluşturabiliriz. <br />
Üst Seviye Sınıflar -> Soyutlama Katmanı -> Düşük Seviye Sınıfları <br />
Örnek: Mobilyaları zemine sabitlenmiş bir ev olduğunu düşünün hiçbir eşyasını yerinden dahi oynatamadığınız bir ev ne kadar mantıklı olabilir ki? Burada tasarımsal bir problemin olduğu aşikâr. Bir örnek daha vermek gerekirse; evinizdeki ampul patladığında koskoca elektrik tesisatını değiştirdiğinizi düşünün. Yani büyük modül (elektrik tesisatı) küçük modüle (ampul) bağlı olmamalı her ikisi de soyut kavrama (lamba –duy ve ampul-) bağlı olmalı. Üstelik burada, ampulün kaç Watt olduğu (detay), lambanın duy kısmını (soyut) ilgilendirir mi?

 ![dependency inversion](https://github.com/b-tekinli/Yazilim-Teknikleri-ve-Diger-Yararli-Turkce-Kaynaklar/blob/main/images/dependencyInversion.png)

Yazılım açısından ve daha teknik bakacak olursak önümüzde aynı altyapıyı kullanan fakat birden fazla arayüze (web, mobile gibi) sahip olan birçok uygulama var. Burada da altyapı üzerinde çalışan ve iş süreçlerini yöneten katman bizim “yüksek seviye” modülümüzdür. Bu açıdan bakıldığında kullanıcı arayüzünün düşük seviye olduğunu söylememiz mümkün.

<br />
<br />

## DRY PRENSİBİ (Don’t Repeat Yourself)

 	“Kendini tekrar etme” anlamına gelir.
 	Kod tekrarlarından sakınılması gerektiğini öneren bir prensiptir.

<br />

![dry](https://github.com/b-tekinli/Yazilim-Teknikleri-ve-Diger-Yararli-Turkce-Kaynaklar/blob/main/images/dry.png)

<br />

## KISS PRENSİBİ (Keep it Simple Stupid)
 	Basit ve aptalca tutun anlamına gelir.
 	Basitlik için çabalamayı öneren bir prensiptir.

<br />

![yagni and kiss](https://github.com/b-tekinli/Yazilim-Teknikleri-ve-Diger-Yararli-Turkce-Kaynaklar/blob/main/images/yagniAndKiss.png)

<br />

## YAGNI PRENSİBİ (You Aren’t Gonna Need It)
 	Buna ihtiyacın olmayacak anlamına gelir.
 	Gelecekte lazım olacak düşüncesiyle ihtiyacımız olmayacak şeyleri sisteme dahil etmemeyi söyleyen bir prensiptir.
  
  </details>
 
 <details>
  <summary>:label: Toolbox Notları (Nedir, Ne İşe Yarar?) </summary>
  
  ## [Windows Form App Notları](https://github.com/b-tekinli/Yazilim-Teknikleri-ve-Diger-Yararli-Turkce-Kaynaklar/blob/main/Windows%20Form%20App%20Notları.docx)
  
    WİNDOWS FORM APPLİCATİON NOTLARI ve KISAYOLLARI

Windows Form nedir? <br />

.NetFramework’ün bir parçası olarak dahil edilen grafik ders kitaplığıdır. <br />
Kodlamanın yanı sıra toolbox yardımı ile görsele yönelik programlama yapmamızı sağlar. <br />

Toolbox nedir? <br />
-	Windows tabanlı görsel uygulamalar geliştirirken kullanacağımız bir grup kontroldür. <br />
-	Form kontrolü hariç diğer bütün kontroller Toolbox panelinden seçilir. <br />
-	Bu kontroller sürüklenip form üzerine istenilen pozisyona bırakılır. <br />
Form üzerine bıraktığımız kontrollerden birini tek click ile seçip özellikler (properties) penceresinde nesnenin özelliklerini ve olaylarını düzenleyebiliriz. <br />

<br />

Form üzerinde yazdığımız kodları nasıl görüntüleyebiliriz? <br />
 	Solution üzerinde Form1’in üzerinde çift tıklayabilirsiniz. <br />

<br />

Form’a eklediğimiz toolboxlara nasıl kod yazabiliriz? <br />
 	Kod yazmak istediğimiz toolbox’ın üzerine çift tıklayabilirsiniz. <br />
              
<br />

Klavye Kısayolları:
-	Ctrl + alt + x :left_right_arrow: Toolbox kapalı ise açmayı sağlar. <br />
-	Ctrl + alt + :left_right_arrow: Solution açmayı sağlar. <br />
-	Ctrl + click :left_right_arrow: Click (1 kez) yaptığınız class’ın ana sayfasına gider. <br />
-	Ctrl + herhangi bir tool üzerine basılı tutup sürükleme :left_right_arrow: Tool’u kopyalar. <br />
-	Ctrl + s :left_right_arrow: Hangi dosya üzerinde iseniz onu kaydetmeyi sağlar. <br />
-	Ctrl + shift + s :left_right_arrow: Tüm dosyaları kaydeder. <br />
-	F5 :left_right_arrow: Programı derler ve başlatır. (Debug => Hata Ayıklama) <br />
-	Alt + G :left_right_arrow: Butona tıklanma sağlanır. <br />

<br />

FORM <br />

A.	Form Özellikleri: <br />
-	MinimizeBox: Simge Durumuna Küçültme  False <br />
-	MaximizeBox: Ekranı Kaplama  True <br />
-	MaximumSize: Formun alabileceği max büyüklük. <br />
-	MinimumSize: Formun alabileceği min küçüklük. <br />
-	Width: Yatay boyutu. <br />
-	Height: Yüksekliği. <br />
-	BackgroundImage: Form arka planına resim ekleme. <br />
-	Oppacity: Formun şeffaflığını ayarlama. <br />
-	Show: Birden fazla formu aynı anda ekrana getirmek için kullanılır. <br />
-	ShowDialog: Sadece çalışmak istediğimiz formu ekrana getirmek için kullanılır. Bu form dışındakilere erişilemez. <br />
-	FormBorderStyle: Formun kenar stili. <br />
-	ControlBox: Close, maximize ve minimize düğmelerinin tümünün görünürlüğü. <br />

<br />

B. Form Metodları:
-	Hide: Visible özelliğini false yaparak gizler.
-	Close: Formu kapatır. Eğer form başlangıç formuysa uygulama sonlanır.
-	Show: Formu gösterir. Hide ile gizlenmişse, visible özelliği true yapılır.
-	ShowDialog: Formu diyalog kutusu olarak gösterir.

<br />

Toolbox Notları: <br />

      Textbox: Metin kutusudur. Kullanıcıdan bilgi almak için kullanılır. <br />
    a.	Multiline: Texbox’ın size’ını (büyüklüğünü) istediğiniz şekilde ayarlayabilmek için textbox üzerinde sağ üst ok tuşuna basıp multiline özelliğini tikleyebilirsiniz. Kısaca metin kutusuna bilginin çoklu satır olarak girilmesini sağlar. <br />
    b.	ScrollBars: Eğer satır sayısı metin kutusunun boyutundan fazla ise kaydırma çubuklarına gerek duyulabilir. Kaydırma çubukları eklemek için ScrollBars özelliği kullanılır, bu özellik dört değişik değer alır. <br />
    c.	PaswordChar: Metin kutusuna girilen bilginin belirlenen karakter ile gizlenmesini sağlar. <br />
    d.	WordWrap: Satır sonlandığında bir alt satıra geçilmesini sağlar. Multiline false ise alt satırlar zaten olmayacağı için bu özelliğin etkisi olmaz. <br />
    e.	MaxLength: Metin kutusunun alabileceği max karakter sayısını belirtir. <br />
    f.	ReadOnly: Metin kutusunun yazmaya karşı korumalı olduğunu belirtir. <br />
    g.	CharacterCasing: Metin kutusuna karakterler girilirken büyük veya küçük harfe çevrilmesini sağlar. Upper büyük, lower küçük harf yazar. <br /> <br />

 	MessageBox: Kullanıcıya diyalog penceresi içerisinde mesaj verme işlemi için MessageBox sınıfının Show metodu kullanılır. <br />

 	Label: Kullanıcıya bilgi vermek amacıyla kullanılan kontroldür.

 	LinkLabel: İçinde web sayfası adresleri bulunan label kontrolleri oluşturmak için kullanılır.

 	TabControl: Kontrolleri sekmelerden oluşan paneller içerisinde görüntülemek amacıyla kullanılır. Yani tek bir form üzerinde birden fazla form varmış gibi çalışabilirsiniz. TabControl'e Eklediğimiz her bir TabPage'i istediğiz gibi dizayn ederek birbirleri arasında geçişler yaptırabilirsiniz.

 	PictureBox: Uygulamamıza görüntülerin eklenmesini ve görüntülerin değişik biçimlerde gösterilmesini sağlar.

 	Button: Komut düğmeleri olarak kullanılır.
    a.	Enabled ve Visible: Butonun aktif veya görünür olmasını kontrol eder. <br />
    b.	TabStop: False olursa o nesne atlanır. <br />
    c.	FlatStyle: Dört farklı değer alabilir. Bunlar standart, popup, flat, system’dir. <br />

 	RichTextBox: Zengin metin kutusu anlamına gelmektedir. Normal metin kutusundan farklı olarak alt satıra da yazmaya imkan vermektedir.

 	MaskedTextBox: Maskeli metin kutusu anlamına gelir. Güçlü tasarımlar konusunda çok sıklıkla kullanılır. Belirli bir formatta alınması gereken veri girişi için kullanılır.

 	ComboBox: Açılır liste üzerinden sunulan seçenekler arasından seçim yapılmasına olanak sağlayan araçtır.

 	GroupBox: Bu kontrol tek başına değil, diğer kontrolleri gruplamak için kullanılır. Kontrolleri bu GroupBox ile gruplamanın birçok avantajı vardır.
  
    GroupBox içine yerleştirilen kontroller, GroupBox’a bağımlıdırlar ve konumları bu çerçeve dışına taşamaz. Özellikle birkaç kontrolü birden görünür ya da görünmez yapmak için hepsinin Visible özelliğini tek tek değiştirmek yerine çerçevenin Visible özelliğini değiştirilerek çerçeve içindeki tüm kontroller aynı anda değiştirilebilir.
    Her bir kontrol tek tek taşınmak yerine çerçeve taşınır. Çerçevelerin buna benzer pek çok faydaları vardır. Ayrıca RadioButton' ların gruplanmasında çerçeve kullanmak kaçınılmaz olabilir.


 	CheckBox: Kontrol Kutusu, kullanıcıya birden çok seçeneği seçme imkanı sağlar. Checked özelliği kontrol kutusunun seçilip seçilmediğini kontrol eder. Seçili ise, true değilse false değerini alır. Listelenen öğeler açılan bir kutuda görüntülenir ve listeden en fazla bir tane öğe seçilebilir.
    a.	Items: Açılır listeye eleman eklenebilir. <br />

 	ListBox: Kullanıcıya sunulan seçeneklerin bir liste halinde görünmesini sağlar. Liste kutusundan istenen sayıda öğe seçilebilir.
    a.	Text: Liste kutusundaki seçilen elamanın değerini döndürür. <br />
    b.	SelectedIndex: Liste kutusundaki elamanının indis numarasını verir. <br />

 	CheckedListBox: Liste kutusunun tüm özellik, metot ve olaylarını alır ve listedeki öğelerin işaret kutusu ile gösterilmesini sağlar.

 	ListView: Listview gelişmiş bir listeleme kontrolüdür. Listbox’ta olduğu gibi içine elemanlar eklenebilir, her elemana bir resim verilebilir ve listedeki elemanlar farklı biçimlerde listelenebilir.

 	RadioButton: RadioButton kontrolü CheckBox’tan farklı olarak birkaç seçenekten sadece birini seçme imkanı veren bir onay kontrolüdür.
  
    a.	Appearance: Komut düğmesi görünümüne sahip RadioButton düğmeleri oluşturulabilir. <br />
    b.	Text: İçindeki metin yazılabilir. <br />
    c.	TextAlign: İçindeki metnin yerleşmesi belirlenebilir. <br />
    d.	Image: İçinde resim gösterilebilir. <br />
    e.	CheckAlign: Seçenek düğmesi sola, sağa alınabilir. <br />

 	Panel: Kullanılacak grupları kontrol etmek, üzerinde daha rahat işlem yapabilmek için bir arada tutan bir toolbox aracıdır.

    Panel üzerine istediğimiz toolbox aracını rahatça bırakabilir üzerlerinde işlem yapabiliriz. GroupBox gibi ayarlama yapan bir kontroldür. 
    GroupBox’a göre en büyük artısı kaydırma çubuklarını (AutoScroll) desteklemesidir.

 	MenuStrip: Menü tasarımı yapmak amacıyla kullanılmaktadır.

 	OpenFileDialog: Bir dialog ekranı ile dosya seçmemize yaramaktadır. Project menüsü altında bulunan Add Existing Item menüsünü gösterebiliriz. Bu ekran ile bir OpenFileDialog ekranı açılır ve dosya seçim işlemi gerçekleştirilir.

 	DateTimePicker: Tarih eklemek için kullanılır.

 	ImageList: Daha sonra denetimler tarafından görüntülenebilen resimleri depolamak için kullanılır. Görüntü listesi, tek ve tutarlı bir resim kataloğu için kod yazmanıza olanak tanır.

 	WebBrowser: Temelde windowsun internet explorer web tarayıcısına ait özelliklerini kullanmaktadır.
  
    a.	Navigate: Web browser için adres girilmesine imkan sağlar. Belirtilen adrese yönlendirme yapılır. <br />
    b.	GoBack: Bir önceki sayfaya döner. <br />
    c.	GoForward: Bir sonraki sayfaya döner. <br />
    d.	GoSearch: Arama sayfası işlevi için kullanılır. <br />
    e.	GoHome : Ana sayfaya yönlendirme için kullanılır. <br />
    f.	Refresh: Sayfada yenileme yapar. <br />
    g.	Stop: Sayfanın yüklenmesini durdurur. <br />

 	Timer: Belirli zaman aralıklarında iş yaptırmak amacıyla milisaniye cinsinden geçen süreyi hesaplamak için kullanılır.

 	ProgressBar: Uygulamalarda yapılan işlemin ilerleme durumunu belirtmek için kullanılıyor.

 	DataGridView: Hücrelerden ve satırlardan oluşan tablo gösterimini sağlayan gelişmiş bir kontroldür.

<br /> <br />

KAYNAKLAR        Bu kaynağı hazırlanırken yararlandığım faydalı linkler:
-	http://mehmetmikail.weebly.com/toolbox.html
-	http://ikucukkoc.baun.edu.tr/lectures/ENM5220/ENM5220%20S2%20Form%20Araclari.pdf
- Mehmet Öğütcan

 </details>
<details>
  <summary>:label: Toolbox Kısaltmaları</summary>
  
  ## [WİNDOWS FORM TOOLBOX KISALTMALARI](https://github.com/b-tekinli/Yazilim-Teknikleri-ve-Diger-Yararli-Turkce-Kaynaklar/blob/main/Windows%20Form%20Toolbox%20Kısaltmaları.docx)
  
  <br />
  
  AdRotator :left_right_arrow: ar <br />
  Button :left_right_arrow: btn <br />
  Calender :left_right_arrow: cal <br />
  CheckBox :left_right_arrow: chk <br />
  CheckBoxList :left_right_arrow: chklst <br />
  Column (DataGridView) :left_right_arrow: col <br />
  ColumnHeader (ListView ) :left_right_arrow: ch <br />
  Combobox :left_right_arrow: cbo <br />
  CompareValidator :left_right_arrow: cv <br />
  CrystalReportViewer :left_right_arrow: rptvew <br />
  DataGrid :left_right_arrow: dg <br />
  DataGridView :left_right_arrow: dgv <br />
  DataList :left_right_arrow: dl <br />
  DomainUpDown :left_right_arrow: dud <br />
  DropDownList :left_right_arrow: ddl <br />
  FileUpload :left_right_arrow: ful <br />
  Form :left_right_arrow: frm <br />
  GridView :left_right_arrow: gv <br />
  GroupBox :left_right_arrow: grp <br />
  HiddenField :left_right_arrow: hf <br />
  Image :left_right_arrow: img <br />
  ImageButton :left_right_arrow: imgbtn <br />
  ImageList :left_right_arrow: il <br />
  Label :left_right_arrow: lbl <br />
  LinkButton :left_right_arrow: lnkbtn <br />
  ListBox :left_right_arrow: lst <br />
  ListView :left_right_arrow: lv <br />
  MenuStrip :left_right_arrow: ms <br />
  ObjectDataSource :left_right_arrow: ods <br />
  PagedDataSource :left_right_arrow: pds <br />
  Panel :left_right_arrow: pnl <br />
  PictureBox :left_right_arrow: pic <br />
  RadioButton :left_right_arrow: rdo <br />
  RadioButtonList :left_right_arrow: rdolst <br />
  RangeValidator :left_right_arrow: rv <br />
  RegularExpressionValidator :left_right_arrow: rev <br />
  Repeater :left_right_arrow: rpt <br />
  RequiredFieldValidator :left_right_arrow: rfv <br />
  StatusLabel :left_right_arrow: slbl <br />
  StatusStrip :left_right_arrow: ss <br />
  TabControl :left_right_arrow: tab <br />
  Table :left_right_arrow: tbl <br />
  TabPage :left_right_arrow: tp <br />
  TextBox :left_right_arrow: txt <br />
  Timer :left_right_arrow: tmr <br />
  ToolStrip :left_right_arrow: ts <br />
  ToolStripButton :left_right_arrow: tsbtn <br />
  ToolStripDropDownButton :left_right_arrow: tsddb <br />
  ToolStripLabel :left_right_arrow: tslbl <br />
  ToolStripMenuItem :left_right_arrow: tsmi <br />
  TreeView :left_right_arrow: tv/tvw <br />
  ValidatorSummary :left_right_arrow: vs <br />
</details>
