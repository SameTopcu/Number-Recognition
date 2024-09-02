# Hand Gesture Recognition System

## Proje Açıklaması

Bu proje, gerçek zamanlı el hareketi tanıma sistemi geliştirmek için OpenCV ve MediaPipe kullanır. Sistemin amacı, bir kameradan alınan görüntülerdeki parmak sayısını tespit etmek ve bu sayıya göre uygun bir görsel overlay'i eklemektir. Overlay resimleri, parmak sayısına göre değişir ve `parmakresimleri` adlı klasörde bulunur.

## Kullanılan Teknolojiler

- **OpenCV**: Görüntü işleme ve video yakalama.
- **MediaPipe**: El hareketlerini tespit etmek için.
- **Python**: Projeyi geliştirmek için kullanılan programlama dili.

## Kurulum

### Gereksinimler

- Python 3.x
- OpenCV
- MediaPipe

### Gereksinimlerin Yüklenmesi

Gerekli kütüphaneleri yüklemek için aşağıdaki komutları çalıştırın:

```bash
pip install opencv-python mediapipe
```

### Proje Dosyaları
- **ElizlemeModulu.py**: El tespiti ve parmak konumlarını bulma işlevlerini içeren modül.
- **main.py**: Ana uygulama kodu, kamera görüntülerini işleyip parmak sayılarına göre uygun overlay resimlerini gösterir.
- **parmakresimleri/**: Parmak sayısına göre gösterilecek overlay resimlerini içeren klasör.


## Kullanım

### Resimleri Hazırlama

`parmakresimleri` klasörüne, her parmak sayısı için birer resim ekleyin. Örnek olarak:

- `img1.jpg` – 1 parmak 
- `img2.jpg` – 2 parmak
- `img3.jpg` – 3 parmak
- `img4.jpg` – 4 parmak
- `img5.jpg` – 5 parmak
- ![image](https://github.com/user-attachments/assets/8a6d80fe-5793-441d-8b52-89c137e2650c)


### Uygulamayı Başlatma

Aşağıdaki komutu kullanarak uygulamayı başlatın:

```bash
python main.py
```
### Kamera Görüntüsü

Uygulama açıldığında, kameradan gelen görüntü üzerinde elinizdeki parmak sayısını gerçek zamanlı olarak göreceksiniz. Parmak sayısına göre uygun overlay resmi gösterilecektir.

### Uygulamayı Kapatma
Programı kapatmak için 'x' tuşuna basabilirsiniz

### Örnek Görüntüler 
![image](https://github.com/user-attachments/assets/04f76081-1709-4f00-8aed-3c877a716a72)

### Katkıda Bulunanlar
- Abdül Samed Topcu



