## _Html ve css özelliklerini kullanarak bir site oluşturdum. Öğrendiklerimi paylaşmak istedim._ <br>

[ ***BURADAN ULAŞABİLİRSİNİZ*** ](https://fidanmuhammed.github.io/full-stack-web-development-projects/Motivational-Sentence-Project/)

 <img src="./images/final.png">
<p>&nbsp</p>
<p>&nbsp</p>
Bu site bir tane resimden ve motive eden bir sözden oluşuyor. Resmi ortalamak için div kullandım. Ortalama işlemi epey uğraştırdı çünkü başta resmin genişliğini değiştirmemiştim. Eğer genişliği öylece bırakır manuel olarak değiştirmezseniz yani `width:auto` olduğu zaman bu tasarımlarınızda tutarlılığınızı engelleyebiliyor. Bu yüzden o kısmı `width:100%` olarak değiştirdim.
<p>&nbsp</p> 

**Neler öğrendim?**
- *Css'te text-transform kullanımı*
- *Boyut ayarlarken rem kullanımı*
- *width:auto özelliğinin önemi*
  
  
 text-transform: Metinlerin büyük harf, küçük harf veya her kelimenin ilk harfini büyük yaparak okunabilirliği ve estetiği artırır. Uzun yazılarda işinize yarayabilir. 
 
 <img src="./images/text-trs.png">

  ***
  rem: CSS'te kök font boyutuna göre değişim sağlar. Kullanıcıların tarayıcı ayarlarına göre font boyutunu değiştirmesi durumunda, tüm öğelerin orantılı olarak ölçeklenmesini mümkün kılar. `em` ise bulunduğu elementin font boyutuna bağlı olarak değiştiği için hatalar meydana getirebilir. 
  
  <img src="./images/em.png" width="630" height="300" >
  
  ***
  width kullanımı: `width: 100%` kullandığımız zaman resim veya öğe bulunduğu kapsayıcının genişliğine uyum sağlar. Eğer manuel olarak ayarlamazsak `width:auto` seçeneği varsayılan olduğu için aktif olur. Bu da
  sayfa düzenini bozabilir ve resmin boyutlanmasında sıkıntı yaşatabilir.
