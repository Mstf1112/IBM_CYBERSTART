# IBM_CYBERSTART
Eğitim süreci boyunca aldığım notlar.
<h1 align="center">IBM ile Kodluyoruz: CyberStart - 🐍 </h1>





# Hafta 1

### Genel Kültür
- El Harezmi'nin cebir kitabı, algoritma
- Charles Babbage'in analitik makinesi, girdi ve çıktı hesaplamak için dişli, krank ve kıvılcım alıcısı kullanır
- Augusta Ada King, Charles Babbage'in analitik makinesi üzerinde çalışmaları, ilk bilgisayar programcısı olarak bilinir ve bir bilgisayar tarafından işlenmek üzere yazılan ilk algoritmayı oluşturmuştur
- 1950'lerde COBOL, FORTRAN ve BASIC dilleri karmaşık işlemleri gerçekleştirmek için kullanılmıştır
- 1960'ların ve 1970'lerin ardından C ve Pascal dilleri daha fazla kontrol ve esneklik sağlamıştır
- 1980'lerde Apple ve Microsoft'un kişisel bilgisayarları, C++ ve Java dilleriyle popülerlik kazanmıştır
- 2000'lerde web uygulamalarının yükselişiyle JavaScript ve PHP, Python ve Ruby gibi diller önem kazanmıştır
  
### Python
#### 

#### Veri Tipleri


1)Scalar: Tek bir değeri temsil eden veri tipleridir. Scalar veri tipleri şunlardır:
- int (Tam sayılar)
- float (Ondalık sayılar)
- complex (Karmaşık sayılar)
- bool (Boolean - Mantıksal değerler: True veya False)
- NoneType (None - boş değer)

2)Non-scalar: Birden fazla değeri içeren ve birbiriyle ilişkili olan veri tipleridir. Non-scalar veri tipleri şunlardır:
- list (Listeler)
- tuple (Demetler)
- set (Kümeler)
- dict (Sözlükler)

#### Aritmetik Operatörler:
- +: Toplama
- -: Çıkarma
- *: Çarpma
- /: Bölme (gerçek sayı bölmesi)
- //: Bölme (tam sayı bölmesi)
- %: Mod (kalanı bulma)
- **: Üs alma

#### Karşılaştırma Operatörleri:
```

== Eşit mi?

!= Eşit değil mi?

<  Küçük mü?

>  Büyük mü?

<= Küçük veya eşit mi?

>= Büyük veya eşit mi?
```


#### Mantıksal Operatörler:
- and: VE
- or: VEYA
- not: DEĞİL

#### Atama Operatörleri:
- =: Değer atama
- +=: Toplama ve atama
- -=: Çıkarma ve atama
- *=: Çarpma ve atama
- /=: Bölme ve atama
- //=: Tam bölme ve atama
- %=: Mod ve atama
- **=: Üs alma ve atama

#### Üyelik Operatörleri:
- in: Bir öğe bir veri yapısında bulunuyor mu?
- not in: Bir öğe bir veri yapısında bulunmuyor mu?

#### Kimlik Operatörleri:
- is: İki nesnenin aynı nesne olup olmadığını kontrol eder.
- is not: İki nesnenin aynı nesne olmadığını kontrol eder.

#### print() Fonksiyonu:
```
x = 5
y = 10
print("x değeri:", x, "ve y değeri:", y)  # "x değeri: 5 ve y değeri: 10" çıktısını verir.
```
#### input() Fonksiyonu:
```
isim = input("Adınızı girin: ")
print("Merhaba,", isim)  # Kullanıcının girdiği ismi ekrana yazdırır.
```



### Clean Code

- Her dilin ve projenin kendi isimlendirme standartları vardır.Bunlara uymak, kodunuzun okunabilirliğini artırır.Python'da genellikle snake_case (örn. degisken_adi),Java'da ise camelCase (örn. degiskenAdi) kullanılır.
- Boolean değerleri temsil eden değişkenler genellikle bir durumu ifade eder. Bu tür değişkenler için is, has, can gibi ön ekler kullanmak kodun anlaşılırlığını artırır.
- Statik tipte, değişkenlerin türleri, değişkenler oluşturulurken belirlenir ve programın çalışma zamanı boyunca değiştirilemez. Bu, hataları daha erken yakalamamızı sağlar ve derleyici optimizasyonlarına olanak sağlar. Java, C, C++ ve Swift statik tipli dillere örnek olarak verilebilir.


Örneğin, Java'da bir değişken tanımlarken türünü belirtmemiz gerekmektedir:


```java


int sayi = 5;


```

- Dinamik tipte ise, değişkenlerin türü, programın çalışma zamanında belirlenir. Bu, daha az kod yazmamıza olanak sağlar ve daha esnek olmamızı sağlar. Ancak, bu esneklik tip hatalarını daha zor tespit edilebilir hale getirir. Python, Ruby, PHP ve JavaScript dinamik tipli dillere örnektir.


Python'da bir değişkeni tanımlarken, türünü belirtmemize gerek yoktur:


```python


sayi = 5


```

- Generic programlama, kodun belirli türlere bağımlı olmadan çalışabilmesini sağlar. Bu, kodun tekrar kullanılabilirliğini artırır ve tip güvenliğini sağlar. Generic'ler, statik tipli dillerin esneklik kazanmasına yardımcı olur. Java, C#, Swift gibi dillerde Generic programlama kullanılır.


Örneğin, Java'da bir liste oluştururken, listenin içinde ne tür bir veri tutacağını belirtmeliyiz:


```java


List<String> isimler = new ArrayList<String>();


```

- Ancak, bu liste sadece String türünde değerleri kabul eder. Eğer bizim bir liste oluşturmamız ve bu listenin farklı türleri kabul etmesi gerekiyorsa, generic'ler devreye girer:


```java


List<?> herTurluListe = new ArrayList<>();


```

### Tavsiyeler 

- Temiz kod hakkında daha fazla bilgi almak için Robert C. Martin'in "Clean Code" kitabını okumanızı öneririm. Ayrıca “teknik borç(technical debt)” ifadesini de araştırmanız güzel olabilir.

### Yazılım Alanlarını Tanıyalım





# Hafta 2

# Hafta 3

# Hafta 4

# Hafta 5

# Hafta 6
