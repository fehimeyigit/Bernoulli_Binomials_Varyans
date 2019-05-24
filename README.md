## Varyans
Varyans, verilerin aritmetik ortalamadan sapmalarının karelerinin toplamıdır.Varyans kavramı dağılıma ait her bir değerin dağılımın ortalamasından ne kadar uzak olduğuyla ilgilidir. Varyans söz konusu sapmaların ortalama değerini ölçmektedir.

X değişkeninin beklenen değeri μ = E(X) olmak üzere, varyans şöyle tanımlanır:

![Alex](https://github.com/fehimeyigit/Bernoulli_Binomials_Varyans/blob/master/img/4.JPG)

Matematik notasyon kullanılarak bir rassal değişken X için varyans ya Var(X)  σ2 olarak gösterilir.Bu tanımlama, eğer beklenen değer varsa, hem ayrık rassal değişkenler hem sürekli rassal değişkenler hem de karışık değişkenler için genel olarak doğrudur. Bu tanımdan ve beklenen değerlerin doğrusal olma niteliğinden varyans için şu formül çıkartılabilir:

![Alex](https://github.com/fehimeyigit/Bernoulli_Binomials_Varyans/blob/master/img/5.JPG)

## Bernoulli Dağılımı
Bir deneyde başarı ve başarısızlık diye nitelendirilen iki sonuçla ilgilenildiğinde bu deneye (iki sonuçlu) Bernoulli deneyi ya da Bernoulli denemesi denir.

başarı olasılığı -> p, (0<p<1)

başarısızlık olasılığı -> 1-p=q

başarı-başarısız/ sağlam-bozuk/ olumlu-olumsuz/ ölü-canlı

Bernoulli dağılımının olasılık fonksiyonu

![Alex](https://github.com/fehimeyigit/Bernoulli_Binomials_Varyans/blob/master/img/1.JPG)

şeklinde verilir.
 
 ![Alex](https://github.com/fehimeyigit/Bernoulli_Binomials_Varyans/blob/master/img/3.JPG)

Bernoulli dağılımın beklenen değer ve varyansı aşağıdaki gibidir:

![Alex](https://github.com/fehimeyigit/Bernoulli_Binomials_Varyans/blob/master/img/2.JPG)



### Örnek ###

Bir dersi alan öğrencilerin %60 ı dersten kalıyor ve % 40 ı dersten geçebiliyor.Öyleyse;

 a)X rasgele değişkenine ait PMF?
 
 b) Varyansını bulunuz.
 
 ### Çözüm ###

a)

![Alex](https://github.com/fehimeyigit/Bernoulli_Binomials_Varyans/blob/master/img/6.JPG)

grafik üzerinde gösterirsek;

![Alex](https://github.com/fehimeyigit/Bernoulli_Binomials_Varyans/blob/master/img/7.JPG)


b) Varyans hesabı ise;

Var(x)=p x q=0.4 x 0.6=0.24


## Binomial Dağılım ##

Başarı olasılığı olan bir Bernoulli denemesinin aynı şartlar altında (bağımsız olarak) n kez tekrarlanması ile oluşan deneye binom deneyi denir.

Binom deneyinin aşağıdaki koşulları sağlaması gerekir:

* Deney süresince örneklemde denek sayısı ya da deneme sayısı değişmez olmalıdır.

* Denemeler birbirinden bağımsızdır.

* Her denemede iki olası sonuç vardır (istenen ve istenmeyen olay).

* Her denemede ilgilenilen olay olasılığı p değişmezdir. Dolayısıyla istenmeyen olay olasılığı (q=1-p)  de değişmezdir.

Binom dağılımının olasılık fonksiyonu,

![Alex](https://github.com/fehimeyigit/Bernoulli_Binomials_Varyans/blob/master/img/8.JPG)

şeklinde verilir.

Binom dağılımının beklenen değer ve varyansı aşağıdaki gibidir:

E(x)=np

Var(x)=npq

### Örnek ###
##### Belli bir ameliyatın başarılı sonuçlanması olasılığı %80’dir. Ameliyat edilen 10 hastadan #####

![Alex](https://github.com/fehimeyigit/Bernoulli_Binomials_Varyans/blob/master/img/10.JPG)

![Alex](https://github.com/fehimeyigit/Bernoulli_Binomials_Varyans/blob/master/img/11.JPG)

sonucunu elde ederiz.
