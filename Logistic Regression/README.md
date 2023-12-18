# Binary Classification için Lojistik Regresyon

## Genel Bakış
Lojistik Regresyon, isminde “regresyon” geçmesine rağmen bir sınıflandırma algoritmasıdır. Yani görseldeki hayvanın kedi mi, köpek mi olduğu veya verilmiş olan bilgilerin bir erkeğe mi yoksa bir kadına mı ait olduğunu tahmin etme gibi iki sınıflı sınıflandırma problemlerinde sıkça kullanılır.

Lineer regresyon ile arasındaki en büyük fark, lojistik regresyonun iki sınıfı birbirinden ayıracak çizgiyi nasıl uyguladığıdır (fit). Lineer regresyon, optimum çizgiyi çizmek için “En Küçük Kareler Yöntemi” (Least Squares) kullanırken, lojistik regresyon “Maksimum Olabilirlik” (Maximum Likelihood) kullanır.
![Lojistik Regresyon](https://miro.medium.com/v2/resize:fit:1400/format:webp/1*FgUTutnPXhx92LqdQVcMcw.jpeg)

## Lojistik Regresyon Fonksiyonu
Lojistik Regresyon, sınıflandırma yapmak için Sigmoid (Lojistik) Fonksiyonu kullanır. Sigmoid fonksiyonu “S” şeklinde bir eğridir.
![Sigmoid Fonksiyonu](https://miro.medium.com/v2/resize:fit:1400/format:webp/1*NloTSPs4pCMYDZ8G1kxhoQ.png)

## Kod Yapısı
Sağlanan Python kodu, lojistik regresyonu scikit-learn kütüphanesi kullanarak göstermektedir. İşte kodun ayrıntıları:

1. **Gerekli Kütüphanelerin İçe Aktarılması**
   - Sayısal işlemler için NumPy
   - Lojistik regresyon için scikit-learn'den LogisticRegression
   - Görselleştirmeler için Matplotlib ve Seaborn

2. **Örnek Veri Oluşturma**
   - Gösterim amaçlı sentetik veri oluşturma.

3. **Veriyi Eğitim ve Test Setlerine Ayırma**
   - scikit-learn'den train_test_split kullanarak veriyi böleme.

4. **Lojistik Regresyon Modelini Eğitme**
   - Modeli eğitim verisine uydurma.

5. **Tahminlerde Bulunma ve Doğruluk Değerini Değerlendirme**
   - Test seti üzerinde sonuçları tahmin etme ve doğruluk skorunu hesaplama.

6. **Karmaşıklık Matrisini Görselleştirme**
   - Karmaşıklık matrisini ısı haritası olarak çizme.

7. **Avantajlar:**
   - Uygulaması ve yorumlaması kolaydır.
   - Veri seti doğrusal olarak ayrılabiliyorsa oldukça iyi performans gösterir.
   - Büyük veri setlerinde overfit'e daha az meyillidir.

8. **Dezavantajlar:**
   - Gözlem sayısı özellik sayısından azsa, Lojistik Regresyon kullanılmamalıdır, aksi takdirde overfit olabilir.
   - Lojistik regresyonun ayrım yapabilmesi için veri setinin doğrusal olarak ayrılabiliyor olması lazım.

## Yazar Bilgisi
- **Yazar:** [Ahmet Yasin Tazegül](https://www.linkedin.com/in/ahmet-tazeg%C3%BCl-66b3a11b4/)
- **Bağlantı:** [İTÜ VBK](https://www.ituvbk.com/)
- ![İTÜ VBK Logosu](https://static.wixstatic.com/media/3ef854_11e098a45f1c4895a579489e193fd160~mv2.png/v1/fill/w_771,h_771,al_c,q_90,usm_0.66_1.00_0.01,enc_auto/3ef854_11e098a45f1c4895a579489e193fd160~mv2.png)
