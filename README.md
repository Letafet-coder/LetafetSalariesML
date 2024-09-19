# LetafetSalariesML

Supervised Kaggle Dosyası Linki: https://www.kaggle.com/code/letafetkarasu/letafetml-supervised  /n 
Unsupervised Kaggle Dosyası Linki: https://www.kaggle.com/code/letafetkarasu/letafetml-unsupervised   /n

   San Francisco yüksek yaşam maliyetiyle biliniyor.Bu veri setinde , şehirdeki çeşitli iş unvanlarının kazançlarına nasıl yansıdığını tahmin ettim.Bu verileri inceledim ve Gözetimli Öğrenmede Doğrusal Regresyon kullanmam gerektiğini anladım.Bu algoritmayı korelasyon matrisinde bulduğum pozitif değerlere göre seçtim.Gözetimsiz Öğrenmede k-Ortalama Kümeleme algoritmasını kullandım.  /n
  Veri setinde birden çok float olmayan değerler vardı onlara float değerlere çevirdim.NaN ve null değerleri 0 ile doldurdum.Bazı değerleri drop() ettim çünkü algoritmanın çalışmasını engelliyordu.  /n
  
  Doğrusal regresyon algoritmamda performans sonucunu Cross-validation score: 1.0 bu şekilde buldum.
    ![image](https://github.com/user-attachments/assets/2931c5e2-708c-4a21-b7b1-842148183d94)   

  Gözetimsiz öğrenmede Elbow metodu ile N cluster sayısının 3 olduğunu buldum.
    ![image](https://github.com/user-attachments/assets/366dbc12-0694-4527-be90-f198ff5bdb0d)  

  k-Ortalama Kümeleme algoritmamın grafiksel sonucu 
    ![image](https://github.com/user-attachments/assets/878009ea-e66b-4933-934c-37d94749b9b1)  


    Sonuç olarak çapraz doğrulamada aldığım sonuçlar 1.0'lık bir doğrulukla çalışmıştır.Bu, veriye mükemmel bir uyum sağladığını gösteriyor.Fakat model aşırı öğrenmiş  olabilir ve yeni, görülmemiş verilere karşı başarısız olabilir.Gözetimsizde ortalama sonuçlar aldım.

    


  
