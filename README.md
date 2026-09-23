# CYE Studio 5.1.0

Geliştirici: **yaaertu codeR**

CYE Studio, Windows x64 için yerel ve çevrimdışı çalışan masaüstü efekt ve görünüm motorudur. Duvar kâğıdını değiştirmeden görev çubuğu animasyonlarını, pencere auralarını, masaüstü widgetlarını, fare efektlerini ve Windows vurgu rengini yönetir.

## 5.1 içeriği

- **27 görev çubuğu sahnesi**, **18 pencere aurası**, **19 masaüstü widgetı**, **16 widget fontu** ve **20 Windows görünüm profili**
- Gerçek uygulama ikonları, hover büyütmesi ve ses tepkili hareket kullanan kompakt sistem dock’u
- AppBar tabanlı modern üst bar; uygulama pencereleri ve masaüstü ikonları barın altında kalmaz
- Widget için akıcı serbest sürükleme, ayrı kart/yazı ölçeği, renk ve gamer font seçenekleri
- Okunabilir koyu sağ tık menüsü; kart boyutu, yazı boyutu, font, animasyon, konum sıfırlama ve gizleme

Video modu YouTube, Netflix, Twitch, VLC ve benzeri medya oynatımını algılar. Video oynarken üst bar, dock, widget ve overlay efektleri arkaya çekilir; başka bir uygulamaya geçildiğinde medya sesi devam ediyorsa gizli kalır.

## Kurulum

1. Releases bölümünden `CYE Studio.exe` dosyasını indir.
2. Windows x64 bilgisayarda çalıştır.
3. Bir görünüm profili seç veya efektleri ayrı ayrı düzenle.
4. X düğmesi uygulamayı tepsiye indirir. Tam çıkış ve Windows renklerini geri yüklemek için **Kapat ve geri yükle** düğmesini kullan.

EXE kendi .NET 8 çalışma ortamını içerir; ek kurulum gerekmez.

## Performans ve gizlilik

Aura ve shell katmanları ayrı kare hızlarında sınırlandırılır. Tema geçişleri birleştirilip arka planda uygulanır; overlay pencereleri yalnızca durum değiştiğinde gizlenir. Ses tepkisi sadece yerel Windows çıkış seviye göstergesini okur; ses kaydetmez, saklamaz veya yüklemez.

Halka açık pakette kaynak kod, ekran görüntüsü veya video bulunmaz.

## Doğrulama

Yayın derlemesi 0 uyarı ve 0 hata ile üretildi. Dahili doğrulama **8/8** geçti.

`CYE Studio.exe` SHA256:

```text
5C15839BE9180EB656E7998213DE501C24C44483BA6EFF102603F75492C2D00F
```

Telif hakkı © 2026 **yaaertu codeR**. Tüm hakları saklıdır.
