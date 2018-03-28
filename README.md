# KutuKutuBilyeAgirlikTakipSistemi
Bir kolide, içerisinde en az 10 adet olmak üzere farklı sayıda bilyelerin olduğu kutular bulunmaktadır. Farklı kutularda, farklı ağırlıkta bilyeler olabilmektedir. Ancak bir kutu içerisindeki bilyeler aynı ağırlıkta olmalıdır. Bir kutu içerisindeki bilyelerden yalnız 1 tanesinin ağırlığının diğerlerinden biraz farklı olması makul kabul edilmekteyken, 1 taneden daha çok bilyenin ağırlığının diğerlerinden farklı olması durumunda ise hatalı üretim olarak değerlendirilmekte ve kutu iade edilmektedir. 
 
Buna göre, bir kolideki bilye kutularında üretim hatası olup olmadığını, eğer üretim hatası yoksa kutudaki bilyelerin hepsinin eşit ağırlıkta mı, değilse farklı olan bilyenin diğerlerinden daha ağır mı daha hafif mi olduğunu tespit etmek ve koli ile ilgili bazı istatistiksel bilgiler elde etmek için bir program geliştirilmesi istenmektedir. Bunun için, önce bir kutudaki bilye sayısı (kullanıcı 10 ya da daha büyük bir değer girinceye kadar beklenmelidir) programa girilecek, daha sonra kutudaki her bilyenin miligram cinsinden tamsayı olarak ağırlığı (kullanıcı pozitif bir değer girinceye kadar beklenmelidir) programa girilecektir. Kutudaki bilyelerde üretim hatası olduğu tespit edildiği anda, kutuda kalan diğer bilyelerin ağırlıkları girilmeksizin bu durum kullanıcıya bildirilecek ve kutu iade edilmek üzere ayrılacaktır. Kutudaki bilyelerde üretim hatası yoksa; bilyelerin hepsi eşit ağırlıktaysa bilyelerin hepsinin eşit ağırlıkta olduğu, değilse farklı olan bilyenin diğerlerinden daha ağır ya da daha hafif olduğu ve pozitif değerler olarak ağırlık farkının değeri ve yüzdesi kullanıcıya bildirilecektir. 
 
Bir kutu bittikten sonra başka kutu olup olmadığı (kullanıcı evet için E veya e, hayır için ise H veya h harflerinden birisini girinceye kadar beklenmelidir) programa girilecektir. Tüm kutular bittikten sonra, aşağıdaki istatistiksel bilgiler ekrana yazdırılacaktır: 

 Üretim hatası olan kutu sayısı ve tüm kutular içindeki yüzdesi 

 İade edilen ve kabul edilen bilye sayıları 

 İçindeki tüm bilyelerin eşit ağırlıkta olduğu, 1 bilyenin diğerlerinden daha ağır olduğu 1 bilyenin diğerlerinden daha hafif olduğu kutuların sayıları ve üretim hatası olmayan kutular içindeki yüzdeleri 

 1 bilyenin diğerlerinden daha ağır olduğu kutulardaki ağır olan bilyelerin ağırlık farkı değerlerinin ve yüzdelerinin ortalamaları 

 1 bilyenin diğerlerinden daha hafif olduğu kutulardaki hafif olan bilyelerin ağırlık farkı değerlerinin ve yüzdelerinin ortalamaları 

 Tüm bilyelerin eşit ağırlıkta olduğu kutular arasında, içinde en çok bilye olan kutudaki bilye sayısı ve o kutudaki 1 bilyenin ağırlığı 

 Tüm bilyelerin eşit ağırlıkta olduğu kutular arasında, içinde en hafif bilyeler olan kutudaki bilye sayısı ve o kutudaki 1 bilyenin ağırlığı 

 Farklı olan bilyenin ağırlığının diğer bilyelerin ağırlığıyla arasındaki farkın değerinin en büyük olduğu farkın değeri, yüzdesi ve işareti (ağır ya da hafif) 

 Farklı olan bilyenin ağırlığının diğer bilyelerin ağırlığıyla arasındaki farkın yüzdesinin en büyük olduğu farkın değeri,  yüzdesi ve işareti (ağır ya da hafif) 
