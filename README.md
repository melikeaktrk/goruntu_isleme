# Halluks Valgus Tespiti

Bu proje, ayak röntgen görüntülerinde halluks valgus (baş parmak çıkıntısı) tespitini hedefleyen bir görüntü işleme uygulamasıdır.
Python ve OpenCV kullanılarak görüntü ön işleme (histogram eşitleme, gürültü giderme, kontrast iyileştirme), Gaussian Mixture Model (GMM) ile segmentasyon ve SIFT algoritması ile özellik çıkarımı gerçekleştirilmiştir. 
Morfolojik işlemler yardımıyla kemik yapıları ayrıştırılmış ve IoU (Intersection over Union) metriği kullanılarak doğruluk analizi yapılmıştır.
Proje kapsamında test edilen görüntülerde başarılı sonuçlar elde edilmiştir.
Projeyi çalıştırmak için gerekli kütüphaneler (OpenCV, NumPy, Matplotlib, Scikit-learn) kurulmalı ve `19` dosyası çalıştırılmalıdır.
Daha fazla bilgi ve sorularınız için meliikeakturk1@gmail.com adresinden iletişime geçebilirsiniz.
