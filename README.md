# SuperDaire Sınıfı
`SuperDaire` sınıfı, 2D düzlemde daireyi temsil eden bir sınıftır ve bir merkez noktası ve yarıçapı içerir.

## Kurulum
`SuperDaire` sınıfını kullanmak için, sınıf dosyasını projenize ekleyin veya uygun bir paket içinde yer almasını sağlayın. Ayrıca, `Point` sınıfının da mevcut olması gerektiğinden emin olun.

## Kullanım
```java
// SuperDaire sınıfını kullanarak bir daire oluşturun
SuperDaire daire1 = new SuperDaire(5, 0, 0);

// Dairenin alanını ve çevresini hesaplayın
double alan = daire1.alan();
double cevre = daire1.cevre();

// Merkez noktanın orijinden uzaklığını hesaplayın
double merkezeUzaklik = daire1.merkezeUzaklik();
```

## Metodlar

### `double alan()`
Dairenin alanını hesaplar.

### `double cevre()`
Dairenin çevresini hesaplar.

### `double merkezeUzaklik()`
Dairenin merkez noktasının orijinden olan uzaklığını hesaplar.

### `double digerDaireyeUzaklik(SuperDaire digerDaire)`
Belirtilen başka bir `SuperDaire` nesnesine olan uzaklığı hesaplar.

## Örnek
```java
SuperDaire daire1 = new SuperDaire(5, 0, 0);
double alan = daire1.alan(); // alan = 78.54
double cevre = daire1.cevre(); // cevre = 31.42
double merkezeUzaklik = daire1.merkezeUzaklik(); // merkezeUzaklik = 0.0
```

---

Bu `readme.md` dosyası, `SuperDaire` sınıfının nasıl kullanılacağı ve sağladığı metodların nasıl kullanılacağı hakkında temel bilgileri içerir.
