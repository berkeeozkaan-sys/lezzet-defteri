[LezzetDefteri-README.md](https://github.com/user-attachments/files/27535141/LezzetDefteri-README.md)

# Lezzet Defteri

Lezzet Defteri, SwiftUI ve SwiftData kullanılarak geliştirilen modern bir iOS yemek tarifi uygulamasıdır. Uygulama; tarif keşfi, kategori bazlı filtreleme, favori yönetimi, kişisel tarif ekleme, porsiyon hesaplama ve akıllı malzeme eşleştirme gibi işlevlerle kullanıcıya düzenli ve pratik bir tarif deneyimi sunar.

## Özellikler

- Tarifleri kategoriye göre listeleme ve filtreleme
- Tarif adı, özet ve içerik üzerinden arama
- Favori tarifleri kaydetme
- Kullanıcının kendi tariflerini ekleyebilmesi
- Akıllı Mutfak özelliği ile malzemeye göre tarif önerisi
- Porsiyona göre malzeme, kalori ve besin değeri güncelleme
- Tarif detay ekranında besin değerlerini görselleştirme
- Geniş görsel destekli tarif arşivi

## Kullanılan Teknolojiler

- Swift
- SwiftUI
- SwiftData
- Charts
- Xcode

## Proje Yapısı

```text
LezzetDefteri/
├── LezzetDefteriApp.swift
├── Models/
├── ViewModels/
├── Views/
└── Resources/
```

- `Models`: Tarif modeli, kategori yapıları ve örnek tarif verileri
- `ViewModels`: Veri yönetimi ve uygulama iş mantığı
- `Views`: Kullanıcının gördüğü ekranlar ve bileşenler
- `Resources`: Uygulama görselleri ve asset dosyaları

## Öne Çıkan Yapılar

- `Recipe`: Tarifin veri modeli
- `RecipeStore`: Arama, filtreleme, favoriler ve veri yönetimi
- `SmartKitchenView`: Malzeme seçimine göre tarif önerileri
- `RecipeDetailView`: Porsiyon ve besin değeri takibi

## Çalıştırma

1. Projeyi Xcode ile açın.
2. Uygun bir iPhone Simulator seçin.
3. `Run` ile projeyi başlatın.

## Not

Bu proje, modern iOS geliştirme yaklaşımıyla hazırlanmış bir tarif uygulaması örneğidir. Arayüz, veri yönetimi ve kullanıcı etkileşimi birlikte düşünülerek düzenlenmiştir.
