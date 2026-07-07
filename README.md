# Windows için Basit Cmd Komutları

## Öğrenenler İçin Kontrol Listesi  

- [+] Komut İstemini (cmd.exe) Açma (windows + r)
- [+] Tüm Dizinleri/Dosyaları Listeleme (dir)
- [+] Dizin Değiştirme (cd)
- [+] Üst Dizine Çıkma (cd ..)
- [+] Kök Dizine Gitme (cd \)
- [+] Dizin Oluşturma (md)
- [+] Metin Dosyası Oluşturma (echo (yazılacak şey) > (ad).txt)
- [+] Metin Dosyasının İçeriğini Gösterme (more (ad).txt)
- [+] Dosya Silme (del (dosya).txt)
- [+] Dizin Silme (rd (dizin))
- [+] Konsol Ekranını Temizleme (cls)
- [+] Konsoldan Çıkma (exit)
- [+] ```TAB``` Tuşundan Yararlanma


## Örnekler
### Komut İstemini (Command Prompt) Açma
WIN + R (RUN/ÇALIŞTIR) > cmd [ENTER]\
ya da\
Başlat Menüsü > cmd [ENTER]

### dir - Directory
Mevcut dizinde (içinde bulunulan klasörde) yer alan tüm dosya ve dizinleri listeler.
```
dir
```

### cd - Change Directory
Mevcut dizini değiştirir.
```
C:\Users\Kullanici>cd desktop
C:\Users\Kullanici\Desktop>cd C:\Windows
C:\Windows>
```

### cd..
Bir üst dizine çıkar.
```
C:\Users\Kullanici\Desktop>cd..
C:\Users\Kullanici>
```

### cd\
Kök dizine gider.
```
C:\Users\Kullanici\Desktop>cd\
C:\>
```

### md - Make Directory
Dizin oluşturur.
```
md yazilarim
```

### echo
Girilen metni bir dosyaya kaydeder.
```
echo merhaba dünya > notlarım.txt
```

### more
Bir metin dosyasının içeriğini gösterir.
```
C:\Users\Kullanici\Desktop>more notlarım.txt
merhaba dünya
```

### del - delete
Adı/yolu verilen dosyayı siler.
```
del notlarım.txt
```

### rd - Remove Directory
Belirtilen dizini kaldırır.
```
rd çarşamba
```

### exit
Konsoldan çıkışı sağlar. (Konsol penceresini kapatır.)


### cls 
Konsol ekranını temizler.

> İPUCU: Konsol ekranında bir dosya adı ya da dizin adı yazarken ilk bir kaç harfini girdikten sonra ```TAB``` tuşuna basarsanız otomatik tamamlar.
