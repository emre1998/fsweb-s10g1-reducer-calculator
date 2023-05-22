# Sorunu Anlamak:
1. 1 butonuna basılmasından, güncellenen değerimizin render edilmesine kadar olan uygulama adımları nelerdir? 
Her adım için kodun hangi bölümünün geçerli olduğunu listeleyin.
* Kullanıcı 1 butonuna tıkadı.
* actions içerisindeki add one methododu çalışır
* dispatch ile reducer trigger edilir ve state +1 edilip döndürülür.
* return edilen sonuç state.total içerisinde ekrana yazdırılır.
* TotalDisplay total artı 1'i gösterdi.
