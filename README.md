# AI-Project
Fashion MNİST Veri Seti Üzerinde   K-Nearest Neighbors (KNN) ve Support Vector Machine (SVM) Modeli ile Sınıflandırma Modeli Oluşturma ve Eğitme.
Amaç:
Fashion MNİST veri setini kullanarak moda kıyafetlerinin sınıflandırılması için makine öğrenme modelini oluşturmayı ve eğitmeyi hedeflemektedir.
Veri Seti
Fashion MNIST: 28x28 piksel boyutunda, gri tonlamalı 70,000
moda kıyafeti görüntüsü içeren bir veri setidir.
Veri Ön İşleme
Fashion MNİST veri setini yükledikten sonra eğitim ve test veri seti olarak ayırdım ve görüntüleri 0-1 aralığında normalize ettim.
Bu görüntüleri görselleştirebilmek için matplotlib kütüphanesini kullandım.
Model Oluşturma ve Eğitme
Veri seti üzerinde KNN modelini oluşturdum ve eğittim. Test veri seti üzerinde tahmin yaptırdım ve doğruluk değerini hesaplattırdım. En son sınıflandırma raporunu yazdırdım. Bu modelde uyguladığım adımları Svm model için de aynı şekilde gerçekleştirdim.
Sonuçlar ve Değerlendirmeler
KNN ve SVM modelleri Fashion MNIST veri seti üzerinde başarılı bir şekilde eğitildi ve test edildi. Modellerin performanslarını iyileştirebilmek için , KNN modelinde ‘k’ değeri üzerinde değişiklikler yapılabilir. SVM modeli için kernel tipinde veya aşırı uyuma karşı hassasiyeti belirleyen C parametresi üzerinde çalışmalar yapılabilir.
KNN modeli :
Bu modelin sınıflandırılmasındaki çıktıya bakılarak model genel olarak iyi bir şekilde performans göstermektedir. başarısı oldukça yüksektir.
SVM modeli :
bu model her metrik için düşük performans gösterir. Doğruluk değeri oldukça düşük olduğundan daha iyi sonuçlar elde edebilmek için parametrelerin değerleri ile çeşitli çalışmalar yapılabilir.
