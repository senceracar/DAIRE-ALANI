# Daire Alanı ve Çevresi Hesaplama

Bu proje, kullanıcıdan bir daire yarıçapı (`r`) alır ve bu yarıçap kullanılarak dairenin alanını ve çevresini hesaplar. Program, Python'un yerleşik `math` modülünü kullanarak daha doğru bir π (pi) değeri ile hesaplamayı da destekler.

## Kullanımı

Programı çalıştırmak için Python yüklü bir ortamınızın olması gerekmektedir. Programı çalıştırdığınızda, dairenin yarıçapını santimetre cinsinden girmeniz istenir. Yarıçapı girdikten sonra, program dairenin alanını ve çevresini hesaplayıp sonuçları ekrana yazdırır.

### Adımlar

1. Programı başlatın.
2. `Dairenin yarıçapını giriniz (cm): ` yazısını gördüğünüzde, hesaplamak istediğiniz dairenin yarıçapını girin.
3. Program, girilen yarıçapa göre dairenin alanını ve çevresini hesaplayacak ve sonuçları ekrana yazdıracaktır.

## Kodun Çalışması

Program, temel olarak iki farklı hesaplama yöntemi sunar:

1. **Temel Hesaplama:** Bu yöntemde, π (pi) değeri olarak yaklaşık `3.14` kullanılır. Kullanıcıdan alınan `r` yarıçap değeri ile dairenin alanı ve çevresi hesaplanır.

```python
pi = 3.14
alan = pi * r ** 2
cevre = 2 * pi * r
```

2. **Gelişmiş Hesaplama:** Bu yöntemde, Python'un `math` modülündeki `math.pi` değeri kullanılarak daha doğru bir hesaplama yapılır.

```python
import math
alan = math.pi * r ** 2
cevre = 2 * math.pi * r
```

## Sonuçları Görüntüleme

Hesaplama sonuçları, dairenin alanı ve çevresi şeklinde, yuvarlanmış değerlerle birlikte ekrana yazdırılır. Alan metrekare cinsinden, çevre ise santimetre cinsinden gösterilir.

```
Dairenin alanı: 78.5 santimetrekaredir. Dairenin çevresi: 31.4 santimetredir.
```

## Katkıda Bulunma

Bu projeye katkıda bulunmak isteyenler, GitHub üzerinden pull request gönderebilirler. Her türlü geri bildirim ve katkı değerlidir.
