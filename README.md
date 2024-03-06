Fetal Sağlık Durumu Sınıflandırma Projesi
Bu proje, Cardiotocogram (CTG) veri seti üzerinde fetal sağlık durumunu belirlemek amacıyla bir sınıflandırma problemini ele almaktadır. CTG, fetal sağlığı değerlendirmek için kullanılan bir tekniktir ve bu veri seti 2126 gözlem içermektedir. Fetal sağlık durumu, "Normal", "Suspect" ve "Pathological" olmak üzere üç sınıfa ayrılmıştır.

Problem Tanımı
Anne ve Fetüs ölümünü azaltma hedefi doğrultusunda, CTG veri seti üzerinden fetal sağlık durumunu sınıflandırmak, bu bilgiyi kullanarak erken müdahalede bulunmak ve anne ve fetüs ölüm oranlarını düşürmek amaçlanmaktadır.

T-Test:

Öncelikle, SVM ve Karar Ağaçları modellerinin performans metriklerinin ortalamalarını hesaplayacağız.

SVM için:

Accuracy
F1 Score
Sensitivity
Specificity
Karar Ağaçları için de aynı metrikleri hesaplayacağız.

Daha sonra, her metrik için SVM ve Karar Ağaçları modellerinin performansını karşılaştırmak için T-Test gerçekleştireceğiz.

İşlem adımları şunlar olacak:

SVM ve Karar Ağaçları modelleri için performans metriklerinin ortalamalarını hesaplayacağız.
Ardından, bu metriklerin standart sapmalarını ve model sayısını hesaplayacağız.
T-Test'i gerçekleştireceğiz ve sonuçları yorumlayacağız.
