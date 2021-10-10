# 10ATBA ÖDEVLER
### Hafta 5
###### Kodlar:
```using System;
class ogrenciSistemi
{
    string adSoyad;
    int dogumTarihi;
    string dogumYeri;
    int okulNo;
    ogrenciSistemi()
    {
        Console.Write("Ad ve Soyad Giriniz: ");
        adSoyad = Console.ReadLine();
        Console.Write("Doğum Tarihinizi Giriniz: ");
        dogumTarihi = Convert.ToInt32(Console.ReadLine());
        Console.Write("Doğum Yerinizi Giriniz: ");
        dogumYeri = Console.ReadLine();
        Console.Write("Okul Numaranızı Giriniz: ");
        okulNo = Convert.ToInt32(Console.ReadLine());
        Console.WriteLine("****Öğrenci1 Adlı Nesne Oluşturuldu!****");
    }
    void bilgileriEkranaYaz()
    {
        Console.WriteLine("========== Öğrenci1 ===========");
        Console.WriteLine($"İsim Soyisim: {adSoyad}");
        Console.WriteLine($"Doğum Tarihi: {dogumTarihi}");
        Console.WriteLine($"Doğum Yeri: {dogumYeri}");
        Console.WriteLine($"Okul Numarası: {okulNo}");
    }
    void yasHesapla()
    {
        int yas;
        yas = 2021 - dogumTarihi;
        Console.WriteLine($"Yaş: {yas}");
    }

    static void Main(string[] args)
    {
        ogrenciSistemi ogrenci1 = new ogrenciSistemi();
        ogrenci1.bilgileriEkranaYaz();
        ogrenci1.yasHesapla();
        Console.Write("Sonlandırmak İçin Bir Tuşa Basın...");
        Console.ReadKey();
    }
}
```
###### Çıkış:
```
Ad ve Soyad Giriniz: Timuçin ÖZDEMİR
Doğum Tarihinizi Giriniz: 2006
Doğum Yerinizi Giriniz: Mersin
Okul Numaranızı Giriniz: 27
****Öğrenci1 Adlı Nesne Oluşturuldu!****
========== Öğrenci1 ===========
İsim Soyisim: Timuçin ÖZDEMİR
Doğum Tarihi: 2006
Doğum Yeri: Mersin
Okul Numarası: 27
Yaş: 15
Sonlandırmak İçin Bir Tuşa Basın...
```
### Şahin Mansuroğlu <3
