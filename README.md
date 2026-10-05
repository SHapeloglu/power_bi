# Power BI — Örnek Rapor ve Tema Koleksiyonu

Power BI eğitimleri ve danışmanlık çalışmalarında ilham ve referans olarak kullanılan örnek raporlar (`.pbix`) ve rapor temaları (`.json`) arşivi.

## İçerik

| Klasör | İçerik |
|---|---|
| [`theme/`](theme) | ~146 rapor teması (JSON) ve çoğunun önizleme görseli (PNG/JPG) |
| [`templates/`](templates) | ~51 örnek dashboard: İK analitiği, satış, finans/gelir tablosu, otel ve konaklama, çağrı merkezi, hastane, e-ticaret, IMF dünya ekonomisi, takvim, KPI kartları, waffle/lollipop grafikleri, filtre ve toggle teknikleri… |
| [`wow/`](wow) | ~38 Workout Wednesday, Fabric Days ve PBI DataViz World Championships çözüm dosyası (2021–2026) |

## Kullanım

- **Tema uygulama:** Power BI Desktop → *Görünüm* → *Temalar* → *Temaya gözat* → `theme/` altındaki bir `.json` dosyasını seçin.
- **Raporu açma:** `.pbix` dosyalarını Power BI Desktop (Windows) ile açın.

## Notlar

- Dosyaların çoğu topluluk kaynaklıdır (Workout Wednesday, blog ve eğitim dosyaları); haklar ilgili yazarlarına aittir. Yeniden yayımlarken kaynak belirtin.
- Bazı tema dosyaları UTF-8 BOM içerir; Power BI sorunsuz okur. Şu dosyalar geçerli JSON değildir ve düzeltilmeyi bekliyor: `Financial Analytics Report Insights.json`, `Hotel Management Report Insights.json`, `IT & Cyber Securtiy Report Insights.json`.
- Müşteri verisi içeren rapor eklemeyin — repo herkese açıktır.
