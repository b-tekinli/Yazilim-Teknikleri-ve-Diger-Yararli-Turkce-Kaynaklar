# Yazılım Teknikleri ve Diğer Yararlı Türkçe Kaynaklar
Software techniques and other useful Turkish resources 

- [CRUD Fonksiyonları](https://github.com/b-tekinli/Yazilim-Teknikleri-ve-Diger-Yararli-Turkce-Kaynaklar#crud-fonksi%CC%87yonlari) <br />
- [Nesne Tabanlı Programlama](https://github.com/b-tekinli/Yazilim-Teknikleri-ve-Diger-Yararli-Turkce-Kaynaklar#oop---nesne-tabanli-programlama---object-ori%CC%87ented-programmi%CC%87ng) <br />
- [SOLID Prensipleri](https://github.com/b-tekinli/Yazilim-Teknikleri-ve-Diger-Yararli-Turkce-Kaynaklar#solid-prensi%CC%87pleri%CC%87---solid-principle-) <br />
- [DRY Prensibi](https://github.com/b-tekinli/Yazilim-Teknikleri-ve-Diger-Yararli-Turkce-Kaynaklar#dry-prensi%CC%87bi%CC%87-dont-repeat-yourself)
- [KISS Prensibi](https://github.com/b-tekinli/Yazilim-Teknikleri-ve-Diger-Yararli-Turkce-Kaynaklar#kiss-prensi%CC%87bi%CC%87-keep-it-simple-stupid)
- [YAGNI Prensibi](https://github.com/b-tekinli/Yazilim-Teknikleri-ve-Diger-Yararli-Turkce-Kaynaklar#yagni-prensi%CC%87bi%CC%87-you-arent-gonna-need-it)
- WPF Uygulamaları Notları ve Tool Kısaltmaları


<br />
<br />

<details>
  
  <summary>:hammer_and_wrench: CRUD</summary>

## [CRUD FONKSİYONLARI](https://github.com/b-tekinli/Yazilim-Teknikleri-ve-Diger-Yararli-Turkce-Kaynaklar/blob/main/CRUD%20Fonksiyonlar%C4%B1.docx)

Veritabanı Kayıt (Ekleme, Okuma, Güncelleme ve Silme) İşlemleri


![crud](https://github.com/b-tekinli/Yazilim-Teknikleri-ve-Diger-Yararli-Turkce-Kaynaklar/blob/main/images/crud.jpg)


o	Programlamada oluşturma, okuma, güncelleme ve silme, veri depolamada kullanılan dört temel fonksiyondur. Terim ilk kez James Martin'in 1983 tarihli kitabı Managing the Data-base Environment'ta kullanılmıştır.


-	Create ==> Yaratma, oluşturma, ekleme
-	Read ==> Okuma
-	Update  ==> Güncelleme
-	Delete ==> Silme


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

1. Abstraction - Soyutlama ==> Bir sınıfta davranış ve özelliklerin tanımlanmasına soyutlama diyoruz.
Örneğin: Araba sınıfında rengi, modeli, tekerlek sayısı, motor gücü, özellikleridir(property).
Hızlanması, fren yapması, durması davranışlarıdır ve metotlar (fonksiyonlar) ile tanımlanır.

<br />

2. Inheritance - Miras Alma / Kalıtım ==> Sınıflar birbirinden türeyebilir. Alt sınıf üst sınıfın özelliklerini alabilir.
Örneğin: Araba ve bisiklet sınıflarında ortak özellik olarak tekerlek sayısı, hızı gibi özelliklerini tekrar yazmak yerine bu özellikleri içeren bir sınıf oluşturup miras alabiliriz. Bir sınıftan birden fazla miras alınıyorsa buna çoklu kalıtım denir.

<br />

3. Polymorphism - Çok Biçimlilik ==> Alt sınıflar üst sınıfın gösterdiği davranışları göstermek zorunda değildir. Alt sınıfların farklı davranışları göstermesine Çok biçimlilik denilmektedir.
Örneğin: Gemi ve araba sınıflarını ele aldığımızda bunların hareket tipleri bulunmaktadır. Gemi su üzerinden giderken araba karada hareket etmektedir. Kısaca farklı nesnelerin (araba ve gemi gibi) aynı olaya (hareket tipine) farklı şekilde cevap vermesidir.

<br />

4. Encapsulation - Kapsülleme ==> Davranış ve özellikler sınıfta soyutlanarak kapsüllenir. Kapsülleme ile hangi özellik ve davranışın dışarıya sunulup sunulmayacağını belirleriz.
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



 	Single Responsibility ==> Tek Sorumluluk Prensibi / İlkesi


 	Open Closed ==> Açık Kapalı Prensibi / İlkesi


 	Liskov Substitution ==> Liskov’un Yerine Geçme Prensibi / İlkesi


 	Interface Segregation ==> Arayüzlerin Ayrışması ve Ayrılması Prensibi


 	Dependency Inversion ==> Bağımlılıkların Tersine Çevrilmesi Prensibi



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

o	Peki, bütün bu sorunlardan kurtulmanın yolu nedir ?
Cevap:  Yüksek seviye ve düşük seviye sınıflar arasında bir soyutlama katmanı oluşturabiliriz.
Üst Seviye Sınıflar -> Soyutlama Katmanı -> Düşük Seviye Sınıfları
Örnek: Mobilyaları zemine sabitlenmiş bir ev olduğunu düşünün hiçbir eşyasını yerinden dahi oynatamadığınız bir ev ne kadar mantıklı olabilir ki? Burada tasarımsal bir problemin olduğu aşikâr. Bir örnek daha vermek gerekirse; evinizdeki ampul patladığında koskoca elektrik tesisatını değiştirdiğinizi düşünün. Yani büyük modül (elektrik tesisatı) küçük modüle (ampul) bağlı olmamalı her ikisi de soyut kavrama (lamba –duy ve ampul-) bağlı olmalı. Üstelik burada, ampulün kaç Watt olduğu (detay), lambanın duy kısmını (soyut) ilgilendirir mi?

 ![dependency inversion](https://github.com/b-tekinli/Yazilim-Teknikleri-ve-Diger-Yararli-Turkce-Kaynaklar/blob/main/images/dependencyInversion.png)

Yazılım açısından ve daha teknik bakacak olursak ünümüzde aynı altyapıyı kullanan fakat birden fazla arayüze (web, mobile gibi) sahip olan birçok uygulama var. Burada da altyapı üzerinde çalışan ve iş süreçlerini yöneten katman bizim “yüksek seviye” modülümüzdür. Bu açıdan bakıldığında kullanıcı arayüzünün düşük seviye olduğunu söylememiz mümkün.

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
  <summary>:toolbox: Toolbox Kısaltmaları </summary>
  AdRotator :left_right_arrow: ar
  Button :left_right_arrow: btn
  Calender :left_right_arrow: cal
  CheckBox :left_right_arrow: chk
  CheckBoxList :left_right_arrow: chklst
  Column (DataGridView) :left_right_arrow: col
  ColumnHeader (ListView ) :left_right_arrow: ch
  Combobox :left_right_arrow: cbo
  CompareValidator :left_right_arrow: cv
  CrystalReportViewer :left_right_arrow: rptvew
  DataGrid :left_right_arrow: dg
  DataGridView :left_right_arrow: dgv
  DataList :left_right_arrow: dl
  DomainUpDown :left_right_arrow: dud
  DropDownList :left_right_arrow: ddl
  FileUpload :left_right_arrow: ful
  Form :left_right_arrow: frm
  GridView :left_right_arrow: gv
  GroupBox :left_right_arrow: grp
  HiddenField :left_right_arrow: hf
  Image :left_right_arrow: img
  ImageButton :left_right_arrow: imgbtn
  ImageList :left_right_arrow: il
  Label :left_right_arrow: lbl
  LinkButton :left_right_arrow: lnkbtn
  ListBox :left_right_arrow: lst
  ListView :left_right_arrow: lv
  MenuStrip :left_right_arrow: ms
  ObjectDataSource :left_right_arrow: ods
  PagedDataSource :left_right_arrow: pds
  Panel :left_right_arrow: pnl
  PictureBox :left_right_arrow: pic
  RadioButton :left_right_arrow: rdo
  RadioButtonList :left_right_arrow: rdolst
  RangeValidator :left_right_arrow: rv
  RegularExpressionValidator :left_right_arrow: rev
  Repeater :left_right_arrow: rpt
  RequiredFieldValidator :left_right_arrow: rfv
  StatusLabel :left_right_arrow: slbl
  StatusStrip :left_right_arrow: ss
  TabControl :left_right_arrow: tab
  Table :left_right_arrow: tbl
  TabPage :left_right_arrow: tp
  TextBox :left_right_arrow: txt
  Timer :left_right_arrow: tmr
  ToolStrip :left_right_arrow: ts
  ToolStripButton :left_right_arrow: tsbtn
  ToolStripDropDownButton :left_right_arrow: tsddb
  ToolStripLabel :left_right_arrow: tslbl
  ToolStripMenuItem :left_right_arrow: tsmi
  TreeView :left_right_arrow: tv/tvw
  ValidatorSummary :left_right_arrow: vs
</details>
