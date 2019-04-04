
![CoLab](https://colab.research.google.com/assets/colab-badge.svg) [Link](https://colab.research.google.com/drive/1aLQmoL3Yu-UhQek108eJjTICwzU4Wpl6)
                     

# BayesTeoremi

Bayes Teoremi ile ilgili Örnek Soru ve Çözümü,  [**Soru Kaynağı**](http://www.baskent.edu.tr/~iserdem/dersler/258/Bolum2.pdf)

### Soru:

Bir hava üssünde tehlike olduğu zaman alarm sisteminin çalışma olasılığı 0.99, tehlike olmadığında alarm sisteminin çalışmama olasılığı 0.98 ve herhangi bir anda tehlike olma olasılığı da 0.003’tür. 

Hava üssündeki alarm çalıştığına göre, tehlike durumunun olma olasılığı nedir?

### Çözüm:

A: Alarm Sisteminin Çalışması,  A': Alarm Sisteminin ÇalışMAMAsı, 

B: Tehlike olması, B': Tehlike olMAMAsı
   
P(B) = 0.003, P(B') = 0.997, P(A | B) = 0.99, P(A' | B') = 0.98, P(A | B') = 0.02

Durum={Tehlike altında alarmın çalışması},   P(A|B)xP(B): 0.99x0.003=0.00297

Örnek Uzay={Alarmın çalışması},   P(A|B)xP(B)+P(A|B')xP(B'): 0.99x0.003+0.02x0.997=0.02291

Olasılık sonucu,    P(B|A)= P(A|B)xP(B) / P(A|B)xP(B)+P(A|B')xP(B')=0.12963771278917494

### Açıklama:

P(B|A)= P(BnA)/P(A)= P(A|B)xP(B)/P(A)

Verilen bilgilere göre tehlike olma olasılığı P(B), tehlike olmama olasılığı P'(B), tehlike altında alarmın çalışma olasılığı P(A|B) ve tehlike olmadığında alarmın çalışma olasılığı P(A|B') hesaplanır.

İstenilen durum, tehlike altında alarmın çalışma olasılığı P(A|B)xP(B)ve örnek uzay, alarmın çalışma durumu P(A|B)xP(B)+P(A|B')xP(B') şeklinde hesaplanır.

Son olarak bayes teoremi ile olasılık sonucu, P(B|A)= P(A|B)xP(B) / P(A|B)xP(B)+P(A|B')xP(B') formülü ile hesaplanarak sonuç bulunur.
