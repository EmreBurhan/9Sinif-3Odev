# 9Sinif-3 Ödev

Aşağıdaki yönerge adımlarını lütfen uygulayın. 

## Bölüm 1 (İvmeli Hareket Yapan Cismin Konum Zaman Grafiğinin Çizimi)

1) Bu ödevi kendi hesabınıza fork edin. Sonra da kendi hesabınızdan bu repoya ait Issue kısmını açın. (Ödevleriniz hakkında size yorum bırakabilmem için gerekli.) 

2) 2.ödevinizde doğrusal bir denklemin (1.dereceden) grafiğini hem elle hem de Google Sheet ile çizdiniz. Bu sefer ikinci dereceden bir denklemi Google Sheet ile çizeceksiniz. İkinci dereceden denkleminiz *y = ax^2+b*x+c* şeklinde olacak. Burada a,b, ve c katsayılardır. 
3) [Bu Videoyu](https://www.youtube.com/watch?v=--1-cfnicJ8) izleyin ve ikinci derecede denklemin nasıl Google Sheet ile çizileceğini öğrenin. Bu videoda bir karenin kenar uzunluğu ile alanın değişme grafiği çizilmiştir. Yani bu video için denkleminiz *y = x^2* şeklinde değişmiş. Yani *a=1, b=0,c=0* dır. 

4) [Bu Video'nun](https://www.youtube.com/watch?v=fhIL18aHg8s&feature=youtu.be) 1.kısmını izliyerek (11-26 saniye arası) 1 kg'lık bir kütlenin  zaman-konum grafiğini çizecekseniz. Burada ivmeli (yavaşlayan) bir hareket olacağından konum-zaman grafiği 2.dereceden denklem olarak çıkacak. 2.dereceden bir denklemi elle çizmeyi 10.sınıf matematik dersinde öğreneceksiniz. Siz bu ödevde bilgisayardan yardım alacaksanız. Video izliyerek çıkardığım zaman-konum tablosu aşağıdaki gibidir. (Not: Video 60 FPS(frame pers second) ile çekilmiştir. O zaman her frame(çerçeve) 1/60 s'dir. Siz istediğiniz noktayı orijin olarak alabilirsiniz. Ben 7'inci frameden başladım ve kütlenin sol ucunu başlangıç noktası seçtim. (x=0, t=0) 

| Frame | Zaman(s) | Konum (m)|
|-------|----------| ---------|
| 7 (Başlangıç)| 0 |   0      |
| 14    | 7/60     |   0.2    |
| 18    | 11/60    |   0.295  |
| 23    | 16/60    |   0.4    |
| 25    | 18/60    |   0.44   |
| 28    | 21/60    |   0.49   |
| 33    | 26/60    |   0.55   |
| 38    | 31/60    |   0.61   | 
| 45    | 38/60    |   0.65   |
| 48    | 41/60    |   0.67   |
| 53    | 46/60    |   0.675  |

Yukarıdaki aldığım verilerin Google Sheet'deki çizimini [burada](https://docs.google.com/spreadsheets/d/1PFojWqpQKHUI6shl7_bbvQSjrb3AS6kleerbCbNNWVg/edit?usp=sharing) bulabilirsiniz. Bu grafiği çizmek için, grafiğin üzerine iki kere tıkladım. Açılan yan pencerede aşağıdaki değişiklikleri yaptım. 
*   Chart Editor ------> Chart type -------> Scatter chart
*   Customize ------> Trendline -------> Polynomial,  Polynnomial Degree=2, Label= Use Equation

Bulduğum ikinci dereceden denklem (x= konum, t=zaman, *x= at^2+b*t + c*) şu şekilde çıktı:
*x = -1.22*t^2 + 1.81*t + 3.92E-03*             

Yukarıdaki örneği kullanarak **kendi ölçümlerinizle** bir tablo oluşturun (hiç değilse birkaç frame benim ölçümlerinden farklı olsun.) Kullandığınız Google Sheet için [buraya](https://docs.google.com/spreadsheets/d/18M6OZoqBt7-vSQClRzC6GVjXPt2PfNbiiZ3y4GUEAzg/edit?usp=sharing) linki verdim. 

***GRAFİĞİ ÇİZDİĞİM TABLOM:***
| Frame | Zaman(s) | Konum (m)|
|-------|----------| ---------|
| 7 (Başlangıç)| 0 |   0      |
| 11    | 4/60     |   0.12   |
| 14    | 7/60     |   0.2    | 
| 16    | 9/60     |   0.25   |
| 19    | 12/60    |   0.32   |
| 21    | 14/60    |   0.36   |
| 24    | 17/60    |   0.42   |
| 28    | 21/60    |   0.49   | 
| 33    | 26/60    |   0.56   |
| 40    | 33/60    |   0.63   |
| 48    | 41/60    |   0.67   |
| 53    | 46/60    |   0,6745 |

a) Denklemim  ( y=konum, t=zaman, *y= at^2+b*t + c* ) = **y= -1,25t^2 + 1,83t + 2,27E-03**. 

Sizce a, b, ve c'nin fiziksel anlamları ne olabilir?  **Cevap:**  Bence a hızdaki değişimi belirleyen katsayı, c atılış hızı, b için ilk başta aklıma geçen zamanla ilişkili olabileceği geldi ama zamanı değiştirince değişmedi yani muhtemelen alınan yol ile bir ilişkisi var.

Sizce niçin a'nın değeri negatif?  **Cevap:** Hız azaldığı için olabilir. 

b) Hava sürtünmesini ihmal edersek, bu harakette ivme sabit midir?  
**Cevap:** Bu cevap hakkında daha iyi düşünmek için aklıma bir hız-zaman grafiği yapmak geldi eğer azalan hız doğrusal olarak azalıyorsa ivme sabit kalacaktır dedim ve ortalama hız-zaman grafiği yaptım hata yapmadığımı düşünüyorum ve grafiğe göre *ivme değişiyor*. Grafik ikinci bölüme de gerektiğinden onu ikinci bölümde bulabilirsiniz.

c) Video'daki cismin atılış hızı farklı olsaydı (diğer her şey aynı, kütle, yüzey, vb. Hava sürtünmesini ihmal edin), sizce formülde hangi terimler değişecekti? (a, b veya c)  **Cevap:** Eğer a, b ve c için yukarıda yaptığım tahminler doğruysa c kesinlikle değişirdi, hız artacağından b de değişirdi, ama a yine aynı şekilde yavaşlayan eşit kütleli cisimden dolayı değişmeyecekti diye düşünüyorum. 

# Bölüm 2 (İvmeli Hareketin Ortalama Hız-Zaman Grafiği)
Bu sefer aynı cismin zaman-hız (ortalama hız) grafiğini çizeceksiniz. Bunun için *1.Bölümde* aldığımız sonuçları kullanacağız. Ortalama hızı bulmak için derste öğrendiğimiz ortalama hız formülünü (Delta x/ Delta t) kullanacağız. Google Sheet kullanarak hız-zaman grafiği nasıl çizildiğini anlamak için  [bu videoya](https://www.youtube.com/watch?v=67IsHRmcmfE&t) bakınız. Ortalama hız-zaman grafiğini çizilirken, ortalama hıza karşılık gelen zamanı nasıl belirleyeceksin? Bir andaki  ortalama hızı hesaplarken o noktadan önceki ve o noktadan sonraki (t,x) noktalarını kullanacaksın. Bu yüzden konum grafiğimde 11 veri noktam varken, hız-zaman grafiğinde veri noktam 9'a düştü. (İlk baştaki ve son baştaki noktalar için ortalama hızı hesaplayamam çünkü başlangıç noktasından önce ve bitiş noktasından sonraki (t,x) bilgilerine sahip değilim.)

Ben kendi verilerim için bir google sheet hazırladım. [Buraya](https://docs.google.com/spreadsheets/d/1fFw-F2NP9XpglTTEkqOjZETT7lD0iE9sqH3Da-srS9w/edit?usp=sharing) bakabilirsiniz. Ortalama hız grafiğini çizerken bu sefer 
*   Customize ------> Trendline -------> Linear, Label=Use Equation
kullandım. Konum-zaman grafiği 2.dereceden bir denklem iken, hız-zaman grafiği 1.dereceden (linear-doğrusal) denklem. 

1) Kendi aldığınız verileri kullanarak **ortalama hız-zaman** grafiğini Google çiziniz. [Buraya](https://docs.google.com/spreadsheets/d/1D0vh_vXDR_nFrfwGKrEHMXR1EtZW8Bft_MhmrsMVVLg/edit?usp=sharing) linki verdim.

2) Aynı Google Sheet'i kullanarak ivme verilerini Google Sheet'inize girin. (Bu sefer 7 tane ivme veriniz olacak.) İvme-zaman grafiğini çiziniz.

3) İvme'yi ne buldunuz? Bu ivme değerini kullanarak 1kg'lık cisim ile yüzey arasındaki kinetik sürtünme katsayısını bulunuz. 
**Cevap:** İvmeyi -2,49 buldum (Ortalama hız-zaman grafiğinin eğimini kullandım. Sürtünme katsayısını ise 0,249 buldum. Bunu bulurken kullandığım formüller:
* F= m.a
* Fsürtünme= m.g.k

# Bölüm 3 (Hala Beni Öldürmeyi Düşünmüyorsan)
1) Bu deneyde ölçüm hatalarım var. 
Zamandaki ölçüm hatam sizce kaç ms (mili saniye) nedir?

**Cevap:** 16,67 buldum.

Konumdaki ölçüm hatam sizce kaç cm'dir? 

**Cevap:** 0,025 buldum.

2) Acaba hiç grafik çizmeden sürtünme katsayısını bulabilir miydim?  (Cevap: Evet). 
Yardım:
* Düzgün ivmelenen bir cisim için alınan yol formülü x = (ilk hız+ son hız)/2*t, burdan cismin ilk hızını bulunuz. 
* Daha sonra iş-kinetik enerji teorimini kullanarak sürtünme kuvvetini bulun. Sürtünme kuvvetinden, kinetik sürtünme katsayısını bulunuz.

**Sonuç:** 0,229

**Yol:**

**NOT:** Son hız=0
![](https://github.com/EmreBurhan/9Sinif-3Odev/blob/master/%C3%A7%C3%B6z%C3%BCm.jpeg?raw=true)


3) Bu video'dan statik sürtünme katsayısını bulabilir miydim? 

**Cevap:** Bence hayır çünkü cismin harekete başladığı anı göremiyoruz.
