# Fuzzy Logic - Classical Set Theory
---
##  Amaç

Bir küme , farklı elemanlardan oluşan sıralanmamış bir koleksiyondur. Küme elemeanları küme parantezi kullanarak liste biçiminde yazılabilir. Eğer elemanlarnı sırası değişir, kümenin herhangi bir elemanı tekrarlanırsa kümede herhangi bir değişiklik olmaz.


---

##  Objective

A set is an unordered collection of distinct elements. The elements of a set can be written as a list using curly braces. If the order of the elements is changed, or if any element of the set is repeated, the set itself remains unchanged.

---
##  Bir Kümenin Matematiksel Gösterimi

 Roster or Tabular Form
 Bu formatta, bir küme tüm elemanlarının listesi olarak yazılır. Elemanlar küme parantezleri içine alınır ve virgülle ayrılır.

 in Roster or Tabular Form : 

 Alfabe Kümesi    : A = {x,y,z,t,w,v,y} \
 Sayıları Kümesi  : B = {1,2,3,4,5,6,7}
 
---



##  Mathematical Representation of a Set

 Roster or Tabular Form
 In this format, a set is written as a list of all its elements. The elements are enclosed in curly braces and separated by commas.

 in Roster or Tabular Form : 

 Set Alphabet : A = {x,y,z,t,w,v,y} \
 Set Numbers  : B = {1,2,3,4,5,6,7}
 
---
##  Küme Oluşturucu Gösterimi

  Küme elemanlarını ortak bir özelliği olarak tanımlanır.  A = {x:p(x)} şeklinde tanımlanır. 

  Örnek : {1,3,5,7,9} kümesi aşağıdaki gibi yazılır : 

  B = {x:1 ≤ x < 10 and (x%2) ≠ 0}
 
---
## Конструктор множеств

Элементы множества определяются общим свойством. Множество A определяется как A = {x:p(x)}.

Пример: Множество {1,3,5,7,9} записывается следующим образом:

B = {x:1 ≤ x < 10 и (x%2) ≠ 0}

---
##  Bir Kümenin Kardinalitesi

  Bir kümenin eleman sayısı   |S| ile gösterilir. Bu sayıya kardinal sayıda denmektedir.  Eğer bir kümenin sonsuz sayıfa eleman sayısı var ise eleman sayısı sonsuz olur. 
 
  X ve Y iki küme olsun.  |X| = |Y| ifadesi, X ve Y kümelerinin  aynı eleman sayısına sahip olduğunu gösterir. Bu durum iki kümenin eleman sayıları eşit olursa olur. Bu da demek oluyor ki matematiksel olarak açıklamak gerekirse  X'ten Y'ye birebir ve örten bir f fonksiyonu mevcuttur.

  |X| ≤ |Y| ifadesi, X kümesinin eleman sayısının Y kümesinin eleman sayısından küçük veya ona eşit olduğunu gösterir. Bu nedenle ,  X'ten Y'ye birebir bir f fonksiyonu mevcuttur.

  |X| < |Y| ifadesi, X kümesinin eleman sayısı Y kümesinin eleman sayısından az olduğunu gösterir. Burada, X'ten Y'ye tanımlı f fonksiyonu birebir (injektif) fonksiyondur, ancak birebir örten (biyektif) fonksiyon değildir.

  Eğer |X| ≤ |Y| ve |X| ≤ |Y| ise , |X| = |Y|. X ve Y kümeleri genellikle eşdeğer kümeler olarak adlandırılır.

 Küme TÜrleri

 Kümelerin bir çok türü bulunmaktadır. Bunlardan bazıları sonlu, sonsuz, alt küme, evrensel küme, öz küme, tek elemanlı kümeler olarak örnekler verilebilir.

 Sonlu Küme
 Belirli sayıda eleman içeren kümeye sonlu küme denir.

 Örnek − S = {x|x ∈ N ve 55 > x > 50}

 Sonsuz Küme
Sonsuz sayıda eleman içeren kümeye sonsuz küme denir.

Örnek − S = {x|x ∈ N ve x > 5}

Alt küme
Bir X kümesi, Y kümesinin bir alt kümesidir (X ⊆ Y), eğer X kümesinin her elemanı Y kümesinin de bir elemanıysa   alt küme şeklinde yazılabilir. 

Örnek 1 − X = {1,2,3,4} ve Y = {1,2} olsun. Burada Y kümesi, X kümesinin bir alt kümesidir çünkü Y kümesinin  elemanları X kümesinde bulunmaktadır. Bu nedenle, Y⊆X olarak yazılır.

Öz Alt Küme
Öz alt küme, bir kümenin alt kümesi ve ona eşit olmayan kümedir. X kümesi, Y kümesinin öz alt kümesidir; eğer X’in tüm elemanları Y’de bulunuyorsa ve X, Y’ye eşit değilse.

Örnek − X = {1,2,3,4,5,6} ve Y = {1,2} olsun. Burada Y ⊂ X'tir, çünkü Y'deki tüm elemanlar X'te de bulunur ve X'te Y'den daha büyük en az bir eleman vardır.

Evrensel Küme
Evrensel küme, belirli bir konuya ait tüm elemanları kapsayan en büyük kümedir ve o konudaki diğer tüm kümeler onun alt kümesidir; genellikle U ile gösterilir.Örneğin, yeryüzündeki tüm hayvanlar evrensel küme seçilirse, memeliler, balıklar ve böcekler bu kümenin alt kümeleri olur.



---