# Fuzzy Logic (Bulanık Mantık) - Klasik Küme Teorisi
--- 

##  Amaç

Bir küme , farklı elemanlardan oluşan sıralanmamış bir koleksiyondur. Küme elemeanları küme parantezi kullanarak liste biçiminde yazılabilir. Eğer elemanlarnı sırası değişir, kümenin herhangi bir elemanı tekrarlanırsa kümede herhangi bir değişiklik olmaz.

---

##  Bir Kümenin Matematiksel Gösterimi

 Roster or Tabular Form
 Bu formatta, bir küme tüm elemanlarının listesi olarak yazılır. Elemanlar küme parantezleri içine alınır ve virgülle ayrılır.

 in Roster or Tabular Form : 

 Alfabe Kümesi    : A = {x,y,z,t,w,v,y} \
 Sayıları Kümesi  : B = {1,2,3,4,5,6,7}
 
---
##  Küme Oluşturucu Gösterimi

  Küme elemanlarını ortak bir özelliği olarak tanımlanır.  A = {x:p(x)} şeklinde tanımlanır. 

  Örnek : {1,3,5,7,9} kümesi aşağıdaki gibi yazılır : 

  B = {x:1 ≤ x < 10 and (x%2) ≠ 0}
 
---
## Küme Oluşturucu

Bir kümenin elemanları ortak bir özellik ile tanımlanır. Bir A kümesi A = {x:p(x)} şeklinde tanımlanır.

Örnek: {1,3,5,7,9} kümesi şu şekilde yazılır:

B = {x:1 ≤ x < 10 и (x%2) ≠ 0}

---
##  Bir Kümenin Kardinalitesi

  Bir kümenin eleman sayısı   |S| ile gösterilir. Bu sayıya kardinal sayıda denmektedir.  Eğer bir kümenin sonsuz sayıfa eleman sayısı var ise eleman sayısı sonsuz olur. 
 
  X ve Y iki küme olsun.  |X| = |Y| ifadesi, X ve Y kümelerinin  aynı eleman sayısına sahip olduğunu gösterir. Bu durum iki kümenin eleman sayıları eşit olursa olur. Bu da demek oluyor ki matematiksel olarak açıklamak gerekirse  X'ten Y'ye birebir ve örten bir f fonksiyonu mevcuttur.

  |X| ≤ |Y| ifadesi, X kümesinin eleman sayısının Y kümesinin eleman sayısından küçük veya ona eşit olduğunu gösterir. Bu nedenle ,  X'ten Y'ye birebir bir f fonksiyonu mevcuttur.

  |X| < |Y| ifadesi, X kümesinin eleman sayısı Y kümesinin eleman sayısından az olduğunu gösterir. Burada, X'ten Y'ye tanımlı f fonksiyonu birebir (injektif) fonksiyondur, ancak birebir örten (biyektif) fonksiyon değildir.

  Eğer |X| ≤ |Y| ve |X| ≤ |Y| ise , |X| = |Y|. X ve Y kümeleri genellikle eşdeğer kümeler olarak adlandırılır.

 ## Küme TÜrleri

 Kümelerin bir çok türü bulunmaktadır. Bunlardan bazıları sonlu, sonsuz, alt küme, evrensel küme, öz küme, tek elemanlı kümeler olarak örnekler verilebilir.

 Sonlu Küme
 Belirli sayıda eleman içeren kümeye sonlu küme denir.

 Örnek − S = {x|x ∈ N ve 55 > x > 50}

 ## Sonsuz Küme
Sonsuz sayıda eleman içeren kümeye sonsuz küme denir.

Örnek − S = {x|x ∈ N ve x > 5}

## Alt küme
Bir X kümesi, Y kümesinin bir alt kümesidir (X ⊆ Y), eğer X kümesinin her elemanı Y kümesinin de bir elemanıysa   alt küme şeklinde yazılabilir. 

Örnek 1 − X = {1,2,3,4} ve Y = {1,2} olsun. Burada Y kümesi, X kümesinin bir alt kümesidir çünkü Y kümesinin  elemanları X kümesinde bulunmaktadır. Bu nedenle, Y⊆X olarak yazılır.

Öz Alt Küme
Öz alt küme, bir kümenin alt kümesi ve ona eşit olmayan kümedir. X kümesi, Y kümesinin öz alt kümesidir; eğer X’in tüm elemanları Y’de bulunuyorsa ve X, Y’ye eşit değilse.

Örnek − X = {1,2,3,4,5,6} ve Y = {1,2} olsun. Burada Y ⊂ X'tir, çünkü Y'deki tüm elemanlar X'te de bulunur ve X'te Y'den daha büyük en az bir eleman vardır.

## Evrensel Küme

Evrensel küme, belirli bir konuya ait tüm elemanları kapsayan en büyük kümedir ve o konudaki diğer tüm kümeler onun alt kümesidir; genellikle U ile gösterilir.Örneğin, yeryüzündeki tüm hayvanlar evrensel küme seçilirse, memeliler, balıklar ve böcekler bu kümenin alt kümeleri olur.

## Boş Küme veya Null Küme

Boş küme (null küme), içinde hiç eleman bulunmayan kümedir ve ∅ (veya Φ) ile gösterilir.
Boş kümenin eleman sayısı 0’dır, bu yüzden boş küme sonlu bir kümedir.

Örnek:  S={x∣x∈N,7<x<8}=∅ \
çünkü 7 ile 8 arasında doğal sayı yoktur.


## Tek Elemanlı (birim) Küme
Tek elemanlı (birim) küme, yalnızca bir eleman içeren kümedir ve genellikle {s} biçiminde gösterilir.

Örnek: S={x∣x∈N,7<x<9}={8}
çünkü bu aralığı sağlayan tek doğal sayı 8’dir.

## Eşit küme:
İki küme, elemanları aynıysa (sıraları önemli olmadan), bu kümelere eşit kümeler denir.

Örnek : A = {1, 2, 6} ve B = {6, 1, 2} ise, her iki küme de aynı elemanları içerdiği için A = B’dir.

## Eşdeğer Küme:
İki kümenin eleman sayıları birbirine eşitse, bu kümelere eşdeğer kümeler denir.

Örnek : A = {1, 2, 6} ve B = {16, 17, 22} için ∣A∣=∣B∣=3 olduğundan A ve B kümeleri eşdeğerdir.

## Örtüşen Kümeler:
En az bir ortak elemanı olan iki kümeye örtüşen kümeler denir. Bu durumda eleman sayıları için şu ilişkiler geçerlidir:

n(A∪B)=n(A)+n(B)−n(A∩B) \
n(A∪B)=n(A−B)+n(B−A)+n(A∩B) \
n(A)=n(A−B)+n(A∩B) \
n(B)=n(B−A)+n(A∩B)

Örnek :  A = {1, 2, 6} ve B = {6, 12, 42} kümeleri için A∩B={6} olduğundan bu iki küme örtüşen kümelerdir.

## Ayrık Kümeler
A ve B olmak üzere iki küme, ortak elemanları yoksa ayrık kümelerdir. Bu nedenle, ayrık kümeler aşağıdaki özelliklere sahiptir:

n ( A ∩ B ) = ϕ
n ( A ∪ B ) = n ( A ) + n ( B )

Örnek: A = {1,3,8} ve B = {7,9,14} olsun. Ortak elemanları yoktur, bu nedenle bu kümeler örtüşen kümelerdir.

## Klasik Kümeler Üzerindeki İşlemler

Set operations include set union, set intersection, set difference, set complement, and Cartesian product.

## Birleşim
A ve B kümelerinin birleşimi, A'da, B'de veya hem A'da hem de B'de bulunan elemanların kümesidir. Yani, A ∪ B = {x|x ∈ A VEYA x ∈ B}.

Örnek: Eğer A = {11,12,13,14} ve B = {11,14,15} ise, A ∪ B = {11,12,13,14,15} olur. Ortak eleman yalnızca bir kez bulunur.

<img width="205" height="157" alt="image" src="https://github.com/user-attachments/assets/aaa1d682-eb3a-49c8-821e-ec19076c7e95" /> 


## Kesişim
A ve B kümelerinin kesişimi A ∩ B ile gösterilir. Hem A hem de B'de bulunan ortak  elemanların kümesidir. Yani :  A ∩ B = {x|x ∈ A VE x ∈ B}.


##  Fark/Bağıl Tamamlayıcı
A ve B kümelerinin küme farkı  yalnızca A kümesinde bulunan ancak B kümesinde bulunmayan elemanların kümesidir.  AB = {x|x ∈ A VE x ∉ B} şeklinde matematiksel olarak gösterilebilir. 

Örnek −   A = {9,8,12,13} ve B = {9,16,25} ise, (A B) = {8,12,13} ve (B A) = {16,25} olur.  

<img width="439" height="153" alt="a-b" src="https://github.com/user-attachments/assets/dda2a82c-1bb1-4e57-a0ad-aa614b687008" />


## Bir Kümenin Tamamlayıcısı
Bir A kümesinin tamamlayıcısı , A kümesinde olmayan elemanların kümesidir.     

Daha açık bir ifadeyle, A′ = (UA) burada U, tüm nesneleri içeren evrensel bir kümedir.

 ## Kartezyen Çarpım / Çapraz Çarpım
n sayıda A1, A2, An kümesinin Kartezyen çarpımı, A1 × A2...× An olarak gösterilir ve x1 ∈ A1, x2 ∈ A2, xn ∈ An olmak üzere tüm olası sıralı çiftler (x1, x2, xn) olarak tanımlanabilir.

## Klasik Kümelerin Özellikleri

Kümelerin özellikleri, elde etmek istediğimiz çözümlerin elde edilmesinde önemli bir rol oynar. 

Klasik kümelerin farklı özellikleri şunlardır:

## Değişme Özelliği
A ve B olmak üzere iki kümemiz varsa, bu özellik şunu ifade eder:

A∪B=B∪A \\
A∩B=B∩A

## Birleşme Özelliği
A, B ve C olmak üzere üç kümemiz olduğunda, bu özellik şunu ifade eder:

A∪(B∪C)=(A∪B)∪C \\

A∩(B∩C)=(A∩B)∩C



##  Dağılma Özelliği
A, B ve C olmak üzere üç kümemiz olduğunda, bu özellik şunu ifade eder:

A∪(B∩C)=(A∪B)∩(A∪C) \\

A∩(B∪C)=(A∩B)∪(A∩C)


## İdempotansiyel Özellik
Herhangi bir A kümesi için bu özellik şunu ifade eder:

A∪A=A \\

A∩A=A

## Birim Eleman Özelliği
A kümesi ve evrensel küme X için bu özellik şunu ifade eder:
A∪φ=A \\

A∩X=A \\

A∩φ=φ  \\

A∪X=X 

## Geçişlilik Özelliği
A, B ve C olmak üzere üç kümemiz olduğunda, bu özellik şunu ifade eder:

A ⊆ B ⊆ C , then A ⊆ C

---
