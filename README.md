# veriyapilarivealgoritmacalismalari / DERS İÇERİĞİ KONU ANLATIMI 

#DERS-2 /  VERİ YAPILARI ve TİPLERİ
Veri Yapıları nedir? Veri yapıları, verilerin organize edilmesinde ve saklanırken türlerini tanımlar. Bu yapılar, verilerin etkin bir şekilde kullanımı - işlenmesini sağlamaktadır.
Buradaki ilk kural değişken isimlendirme kurallarının kavranmasıdır.
1.	Değişken ismi arasında boşluk bilgisi kesinlikle olmamalıdır.
2.	Özel karakter kesinlikle eklenmemelidir.
3.	Değişkenlerde Türkçe Karakter kullanılmamalıdır
4.	Döngü ve Kontrol yapılarının isimleri değişken olamaz (if, for, while)
5.	Büyük ve Küçük harf duyarlılığı unutulmamalıdır.
Veri Tipleri
1.	Integer - Tamsayı tanımlaması
2.	Float - Ondalıklı Sayı tanımlaması
3.	String - Metinsel içerik tanımlaması
4.	Boolean (True - False) - Doğru / Yanlış tanımlaması
5.	List - Liste tanımlaması
6.	Tuple - Demet tanımlaması
7.	Dictionary - Sözlük tanımlaması
8.	Set - Küme tanımlaması
Python Programlama Dili Temelinde Kullanılan Fonksiyonlar
1.	len() -> bir değişkenin uzunluğunu ele almaktadır.
2.	type() -> bir değişkenin veri tipini vermektedir.
3.	print() -> belirtilen değeri veya değerleri ekrana yazdırır.
4.	capitalized() -> bir dizeyi alır ve sadece ilk harfini büyük harf yapar, geri kalan harfleri küçük harf yapar.
5.	split() -> bir dizeyi belirli bir ayırıcıya göre böler ve her bir parçayı liste elemanı olarak döner.
6.	upper() -> bir dizedeki tüm harfleri büyük harfe çevirir.
7.	input() -> kullanıcıdan veri almak için kullanılmaktadır.
8.	float() -> bir değeri ondalıklı sayı veri tipine dönüştürmek için kullanılır.
9.	int() -> bir değeri tam sayı veri tipine dönüştürmek için kullanılır.
10.	abs() -> mutlak değer alma fonksiyonudur.
Python Programlama Dilinde Kullanılan Temel Ktüphaneler
Kütüphane terim olarak; Belirli bir işlevselliği gerçekleştirmek için önceden yazılmış kod bloklarının bir topluluğudur.
Özellikler:
1.	Yeniden Kullanılabilirlik
2.	Modülerlik
3.	Kolaylık, Hız ve Esneklik
4.	Dökümantasyon:
Python Programlama dilinde Kütüphaneler "import" ile yazılıma eklenmektedir. Temel Kütüphaneler:
1.	import os -> işletim sistemiyle etkilişimli kod yazımı için gerekli olan bir kütüphanedir. Asli görevi dizin işlemleridir.
2.	import random -> yazılımda rastgele bir sayı üretmebilmek için kullanılan bir kütüphanedir.

Dictionary - Sözlük Nedir?
1.	Sözlükler, anahtar-değer (key-value) çiftlerini depolayan veri yapılarıdır.
2.	Her anahtar benzersizdir ve bir değere karşılık gelir.
3.	Sözlükler sırasızdır ve değiştirilebilir.
Sözlük Metotları
1.	keys(): Sözlüğün anahtarlarını döner.
2.	values(): Sözlüğün değerlerini döner.
3.	items(): Sözlüğün anahtar-değer çiftlerini döner.
Set - Küme Nedir?
1.	Kümeler, benzersiz elemanlardan oluşan sırasız koleksiyonlardır.
2.	Kümeler değiştirilebilir ve tekrarlayan eleman içermez.
Küme Metotları
1.	add(): Küme içerisine eleman ekler.
2.	remove(): Küme içerisinden eleman siler.
3.	union(): İki kümenin birleşimini döner.
4.	intersection(): İki kümenin kesişimini döner.
5.	difference(): İki kümenin farkını döner.


#DERS-3 / PYTHON Koşul Yapıları
1.	if Koşul yapısı -> belirtilen şart doğruysa (True) bir bloğun çalıştırılmasını sağlamaktadır.
2.	if-else Koşul yapısı -> if bloğu sağlanmazsa, else bloğu çalıştırılır.
3.	if-elif-else Koşul yapısı -> Birden fazla koşul kontrol etmek için elif (else if) kullanılır. İlk doğru koşul bulunana kadar kontrol devam eder. Hiçbiri doğru değilse, else bloğu çalıştırılır.
4.	İç İçe Koşullar
5.	Mantıksal Operatörler ile Koşul Yapıları

#DERS-4 / PYTHON Döngü Yapıları

Döngüler, belirli bir kod bölümünün birden fazla çalıştırmamıza olanak tanır. Döngüler, genellikle yazılımda tekrar eden işlemler için kullanılır.

Döngü Türleri:

for Döngüsü--> Belirli bir sıralama üzerinde iterasyon yapmak için kullanılır. Genellikle bir liste, dizi veya range fonksiyonu ile kullanılır.

while Döngüsü--> Belirli bir koşul doğru olduğu sürece kod bloğunu çalıştırır.

Döngü Kontrol Yapıları:

break--> Döngüyü tamamen sonlandırır.
continue--> Döngünün o anki tekrarı-iterasyonunu sonlandırır ve bir sonraki tekrara-iterasyona geçer.
Döngü İçinde Döngü (İç İçe Döngüler):

İç İçe for Döngüsü
İç İçe while Döngüsü

#DERS-4 / PYTHON - POINTER, DİZİ / LİSTE, FONKSİYONLAR
PYTHON Pointer Kavramı - Pointerler Python Programlama dilinde yoktur. Konu bitti :))
________________________________________
Pointer C dili öğrenminde çok önemli bir kavramdır. Pointerler C dilinin güçlü öğeleridir. Bir pointer ana bellekte bir adres belirtir. Bazı dillerde ancak assembler dili yardımıyla çözülebilecek pekçok sorun C dilinde pointerler ile kolayca çözülebilir. Ayrıca adres kullanımı çok karmasik veri yapılarınin rahatlikla kullanilmasını sağlar.
Pointer kavramına yöneltilen eleştirilerden en önemlisi, C diline yeni başlayanlar için çok karmaşık görünmesi ve yazılan programın zor anlaşılır olmasıdır.


Python Veri Yapılarında Fonksiyonlar ve Kullanım Kuralları
Fonksiyonlar, belirli bir kod üzerinde ilgili görevi gerçekleştiren kod bloklarıdır.
Bir fonksiyon tanımlandığında, ona bir özel isim verilir ve gerektiğinde bu isimle çağrılarak çalıştırılır.
Fonksiyonlar kodun bütünlüğünde aynı kodu tekrar tekrar yazmak yerine; kodu daha modüler, yeniden kullanılabilir ve anlaşılır hale getirir.
Fonksiyonların Kullanım Nedenleri-->
1.	Kodun Tekrarını Azaltır
2.	Modülerlik Sağlar
3.	Anlaşılabilirlik ve Bakım Kolaylığı
4.	Yeniden Kullanılabilirlik

