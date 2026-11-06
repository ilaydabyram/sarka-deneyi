# Basit Sarkaç Deneyi – Yerçekimi İvmesinin Hesaplanması

## Proje Hakkında

Bu proje, basit sarkaç deneyinden yararlanarak yerçekimi ivmesini hesaplamak amacıyla Python kullanılarak geliştirilmiştir.

Kullanıcıdan sarkacın uzunluğu ve belirli sayıdaki salınımın toplam süresi alınır. Girilen ölçümler kullanılarak salınım periyodu ve yerçekimi ivmesi hesaplanır. Birden fazla ölçüm yapıldığında sonuçların ortalaması alınarak deney değerlendirilir.

## Kullanılan Teknolojiler

- Python 3
- Math kütüphanesi

## Kullanılan Fizik Formülü

Basit sarkacın periyot formülü:

T = 2π√(L/g)

Yerçekimi ivmesini hesaplamak için formül şu şekilde düzenlenir:

g = 4π²L / T²

**Değişkenler:**

- T: Salınım periyodu (saniye)
- L: Sarkacın uzunluğu (metre)
- g: Yerçekimi ivmesi (m/s²)

Dünya üzerindeki kabul edilen yerçekimi ivmesi yaklaşık 9.81 m/s²'dir.

## Özellikler

- Kullanıcıdan ölçüm değerlerini alma
- Bir salınımın periyodunu hesaplama
- Yerçekimi ivmesini hesaplama
- Birden fazla ölçüm gerçekleştirme
- Ölçümlerin ortalamasını hesaplama
- Sonuçların yüzde hata oranını bulma
- Deney sonuçlarını değerlendirme

## Nasıl Çalıştırılır?

1. Python 3'ün bilgisayarınızda kurulu olduğundan emin olun.
2. Proje dosyasını indirin.
3. Terminal üzerinden proje klasörüne gidin.
4. Aşağıdaki komutu çalıştırın:

```bash
python basit_sarkac_deneyi.py
```

## Örnek Kullanım

```text
--- BASİT SARKAÇ DENEYİ ---
Yerçekimi ivmesi hesaplama programı

Sarkacın uzunluğunu metre cinsinden girin: 0.50
Kaç ölçüm yapacaksınız?: 3

1. Ölçüm
10 salınımın toplam süresini girin (saniye): 14.2

Salınım periyodu: 1.420 saniye
Hesaplanan yerçekimi: 9.780 m/s²
```

## Not

Bu hesaplama, küçük salınım açıları için geçerli olan basit sarkaç modeline dayanır. Hava direnci ve ipin kütlesi ihmal edilmiştir. Gerçek deneylerde ölçüm hataları sonuçları etkileyebilir.

## Öğrenme Amaçları

Bu proje geliştirilirken Python'da fonksiyonlar, döngüler, koşullu ifadeler, listeler, hata kontrolü ve matematiksel işlemlerin kullanımı hedeflenmiştir.