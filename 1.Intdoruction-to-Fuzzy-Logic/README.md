# Introduction to Fuzzy Logic

---

## 🇹🇷 Amaç

Bu bölümde fuzzy logic (bulanık mantık) kavramı tanıtılır ve klasik mantıktan farkı
sezgisel ve uygulamaya dönük örneklerle açıklanır.

Bu bölümün sonunda okuyucu:

- Fuzzy logic nedir?
- Yapay zekâ içinde hangi alana girer?
- Hangi problemler için uygundur?

sorularına net cevap verebilir.

---

## 🇬🇧 Objective

This chapter introduces the concept of fuzzy logic and explains its difference
from classical logic using intuitive and practical examples.

By the end of this chapter, the reader will clearly understand:

- What fuzzy logic is,
- How it is positioned in artificial intelligence,
- Which types of problems it is suitable for.

---

## 🇹🇷 Fuzzy Logic nedir?

Fuzzy, bulanık anlamın gelmektedir. Ayrıca belirsizliği ifade etmektedir. Sürekli değişen  zaman, olay, işlev her zaman doğru değildir ve bu yüzden bu durumlar için bulanık olarak tanımlamamız gerekir. Fuzzy logic, doğruluk değerlerinin yalnızca 0 ve 1 ile sınırlı olmadığı,
0 ile 1 arasındaki tüm değerleri alabilen bir mantık yaklaşımıdır.

Gerçek hayattaki birçok kavram net sınırlar içermez.
Bu nedenle klasik mantık, belirsiz ve sözel kavramlarla çalışırken yetersiz kalır.

Fuzzy logic, bu belirsizliği matematiksel olarak modellemeyi amaçlar.

Bulanık mantık , insan gibi karar verme yöntemine benzer. Ayrıca belirsiz ve kesin olmayan bilgilerle ilgilenmektedir. Bu aslında gerçek dünya problemlerinin basitleştirilmiş hali ve boolean mantığındaki gibi doğru/yanlış veya 1/0 yerine doğruluk derecelerine dayanır. 

Bulanık mantık aslında bulanıklığı tanımlamak için kullanılan mantıktır. Bulanık Mantık, 1965 yılında Lofti A. Zadeh tarafından "Bulanık Kümeler" adlı araştırma makalesinde tanıtılmıştır. Kendisi Bulanık Mantığın babası olarak kabul edilir. 

---

## 🇬🇧 What is Fuzzy Logic?

Fuzzy means blurred or indistinct. It also expresses uncertainty. Constantly changing times, events, and functions are not always true, and therefore we need to define these situations as fuzzy. Fuzzy logic is a logic approach where truth values ​​are not limited to only 0 and 1, but can take all values ​​between 0 and 1.

Many concepts in real life do not have clear boundaries.
Therefore, classical logic is insufficient when working with ambiguous and verbal concepts.

Fuzzy logic aims to model this uncertainty mathematically.

Fuzzy logic is similar to human decision-making methods. It also deals with uncertain and imprecise information. It's essentially a simplified version of real-world problems, and instead of true/false or 1/0 like in Boolean logic, it relies on degrees of truth.

Fuzzy logic is essentially the logic used to describe ambiguity. Fuzzy logic was introduced in 1965 by Lofti A. Zadeh in his research paper "Fuzzy Sets." He is considered the father of fuzzy logic.

## 🇹🇷 Yapay zekâda fuzzy logic nereye girer?

Fuzzy logic, yapay zekâ içinde aşağıdaki başlıklar altında sınıflandırılır:

- Soft Computing (Yumuşak Hesaplama)
- Approximate Reasoning (Yaklaşık Akıl Yürütme)
- Rule-based Intelligent Systems (Kural Tabanlı Akıllı Sistemler)

Fuzzy logic bir makine öğrenmesi yöntemi değildir.
Veriden otomatik model öğrenmez.
Bunun yerine uzman bilgisi ve kurallar ile çalışır.

---

## 🇬🇧 Where does fuzzy logic belong in artificial intelligence?

Fuzzy logic is commonly classified under:

- Soft Computing
- Approximate Reasoning
- Rule-based intelligent systems

It is not a machine learning method.
Instead, it represents human knowledge using linguistic rules.

---

## 🇹🇷 Klasik mantık neden yeterli değildir?

Klasik mantıkta bir önerme ya doğrudur ya da yanlıştır.

Örneğin:

- Hava sıcaktır
- Müşteri risklidir
- Çalışan başarılıdır

Bu ifadeler gerçek hayatta kesin sınırlar içermez.

Ancak klasik mantıkta bu tür kavramlar genellikle eşik değerlerle modellenir.

---

## 🇬🇧 Why is classical logic insufficient?

In classical logic, a statement is either true or false.

However, concepts such as:

- hot weather,
- risky customer,
- good performance,

do not have precise boundaries in real life.

They are usually modeled using thresholds, which may lead to information loss.

---

## 🇹🇷 Kısa sezgisel örnek

Bir müşterinin aylık geliri 29.500 TL olsun.

Bu gelirin "yüksek" olup olmadığı sorusu,
klasik mantıkta genellikle şu şekilde ele alınır:

Gelir ≥ 30.000 ise yüksek,
değilse yüksek değildir.

Bu yaklaşımda 29.500 ile 30.000 arasındaki fark,
insan algısına göre anlamsız olmasına rağmen,
sonuç tamamen değişir.

Fuzzy logic bu geçişleri yumuşak şekilde temsil eder.

---

## 🇬🇧 A short intuitive example

Suppose a customer earns 29,500.

In classical logic, we may define:

If income ≥ 30,000, then it is high.

This creates a sharp transition.
Fuzzy logic allows gradual transitions between concepts.

---

## 🇹🇷 Fuzzy logic’in temel fikri

Bir eleman bir kümeye:

- tamamen ait olabilir,
- hiç ait olmayabilir,
- kısmen ait olabilir.

Bu aitlik derecesi 0 ile 1 arasında bir değerle ifade edilir.

---

## 🇬🇧 Core idea of fuzzy logic

An element can belong to a set:

- fully,
- partially,
- or not at all.

The degree of membership is represented by a value between 0 and 1.

---

## 🇹🇷 Fuzzy sistemlerin temel bileşenleri

Tipik bir fuzzy sistem aşağıdaki dört ana adımdan oluşur:

1. Fuzzification
2. Rule base
3. Inference engine
4. Defuzzification

Bu adımlar ilerleyen bölümlerde detaylı olarak ele alınacaktır.

---

## 🇬🇧 Main components of a fuzzy system

A typical fuzzy system consists of four main stages:

1. Fuzzification
2. Rule base
3. Inference engine
4. Defuzzification

These components will be discussed in detail in the following chapters.

---

## 🇹🇷 Fuzzy logic ne zaman tercih edilmelidir?

Fuzzy logic aşağıdaki durumlarda özellikle uygundur:

- Problemin kesin matematiksel modeli yoksa,
- İnsan uzmanlığı ve sezgisi önemliyse,
- Giriş değişkenleri sözel kavramlarla ifade ediliyorsa,
- Karar sınırları net değilse.

---

## 🇬🇧 When should fuzzy logic be used?

Fuzzy logic is particularly suitable when:

- a precise mathematical model is not available,
- expert knowledge plays an important role,
- variables are described using linguistic terms,
- decision boundaries are not clearly defined.

---

## 🇹🇷 Bu eğitimin kapsamı

Bu eğitim serisi boyunca aşağıdaki konular ele alınacaktır:

- Fuzzy kümeler ve üyelik fonksiyonları
- Fuzzy mantık operatörleri ve kurallar
- Fuzzy çıkarım sistemleri
- Defuzzification yöntemleri
- Uçtan uca bir fuzzy karar sistemi örneği

Kod örnekleri Python ve C# dilleri ile ayrı ayrı sunulacaktır.

---

## 🇬🇧 Scope of this training

Throughout this training series, the following topics will be covered:

- Fuzzy sets and membership functions
- Fuzzy operators and rules
- Fuzzy inference systems
- Defuzzification methods
- A complete fuzzy decision system example

All implementations will be provided separately in Python and C#.

## 🇹🇷 Kaynaklar
Tutorialspoint : https://www.tutorialspoint.com/fuzzy_logic/fuzzy_logic_introduction.htm

## 🇬🇧 Resources
Tutorialspoint : https://www.tutorialspoint.com/fuzzy_logic/fuzzy_logic_introduction.htm
