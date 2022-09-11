# Hisse_Senedi_Tahmini

<ul>
<li>Herkese merhaba Borsa da machine learning algoritmaları ile hacim tahmini ile alakalı proje geliştirmeye çalıştım.</li>
<li>Yapılan projeleri incelediğim de günlük tahmin (10 gün sonraki değeri vs.) şeklinde çok yoğun olarak kullanıldığını gördüm.</li>
<li>Algoritmalara baktığım zaman ise ML algoritmaları ve LSTM yapısının çok yoğun kullanıldığını tahminde iyi bir yere sahip olduğunu gördüm.</li>
<li><h6>(Uzun kısa süreli bellek (LSTM), değerleri rastgele aralıklarla hatırlayan bir tekrarlayan sinir ağı (RNN) bir mimarisidir)</h6></li>
</ul>
<h4>Not: </h4> Kodlarda bulunan hatalar düzenlenip güncellenecektir. 

Site: https://finance.yahoo.com/ sitesinden istediğiniz veriyi CSV formatında indirebiliyorsunuz.

Veri Seti : https://finance.yahoo.com/quote/TWTR/history?p=TWTR  Twitter verilerini kullandım.

Veri setine bakalım ;
<li> Borsa Yüksek - Düşük fiyat (H-L) </li>
<li> Borsa Kapanış - Açılış fiyatı (O-C) </li>
<li> Tahmini değer (Adj close) </li>
<li> volume </li>

