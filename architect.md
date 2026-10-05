# architect.md — power_bi Klasör Düzeni

Kod mimarisi yok; içerik düzeni:

```
theme/       <Ad>.json  (+ aynı adlı .png/.jpg önizleme)
templates/   <Konu/Yazar>.pbix
wow/         <Yıl/Hafta>.pbix   (Workout Wednesday, Fabric Days, World Championships)
```

## Tema JSON Yapısı (gözlenen alanlar)

`name` (142 dosyada), `dataColors` (102), `visualStyles` (72), `tableAccent`, `background`, `foreground`, `textClasses`, `good`/`neutral`/`bad`, `minimum`/`center`/`maximum` (sıralı renk skalası). Power BI rapor teması şeması: https://github.com/microsoft/powerbi-desktop-samples/tree/main/Report%20Theme%20JSON%20Schema

## Adlandırma

Dosya adları kaynağından geldiği gibi (boşluk, Unicode tire, emoji olabilir). Yeni eklemelerde önerilen: `<kategori>_<konu>_<kaynak>.pbix`, temalarda `<Ad> Theme.json` + `<Ad> Theme.png`.
