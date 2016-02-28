---
layout: post
title:  "Google Analytics ve UTM"
date:   2015-06-23 23:45:40 +0200
comments: true
categories: google analytics utm
---

![2015-06-23-google-utm](/images/2015-06-23-google-utm.png)


Eğer digital pazarlama yapacaksanız, Google Analytics olmazsa olmaz araçlardan bir tanesidir. Peki Analytics sizlere gelen ziyaretçilerin hangi reklam, banner veya platformdan hatta hangi düğmeden geldiğini nasıl anlayacaktır. İşte utm kodları bu işe yaramaktadır.

* **utm_source**: Mülkünüze trafik gönderen reklamveren, site, yayın ve benzeri öğeleri (ör. google, sehirarama, bulten4, ilantahtasi) tanımlar.
* **utm_medium**: Reklam veya pazarlama aracısıdır (ör. tbm, banner, e-posta bulteni).
* **utm_campaign**: Bir ürüne yönelik ayrı kampanya adı, slogan, promosyon kodu ve benzeri öğelerdir.
* **utm_term**: Ücretli arama anahtar kelimelerini tanımlar. Ücretli anahtar kelime kampanyalarını manuel olarak etiketliyorsanız, anahtar kelimeyi belirtmek için utm_term parametresini de kullanmanız gerekir.
* **utm_conten**: Benzer içeriği veya aynı reklam içindeki bağlantıları ayırt etmek için kullanılır. Örneğin, aynı e-posta iletisinde iki harekete geçirici mesaj bağlantınız varsa, utm_content parametresini kullanıp her biri için farklı değerler belirleyebilirsiniz. Böylece, hangi mesajın daha etkili olduğunu görebilirsiniz.

Ayrıca URL’leri yaratmak için Google’ın URL oluşturucusunu kullanabilirsiniz.

Kaynaklar

https://support.google.com/analytics/answer/1033863?hl=tr
