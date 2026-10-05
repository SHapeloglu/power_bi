# CLAUDE.md — power_bi (rapor & tema koleksiyonu)

Kod reposu değil: Power BI eğitim/danışmanlık için toplanmış **örnek rapor (.pbix) ve tema (.json)** arşivi. Çoğunluğu topluluk kaynaklı (Workout Wednesday, Fabric Days, PBI DataViz World Championships, blog/eğitim dosyaları).

- GitHub: https://github.com/SHapeloglu/power_bi — **PUBLIC repo**, ~217 MB `.git` (2026-05-04 web yüklemeleri)
- Mimari (klasör düzeni): `architect.md` · Görevler: `task.md` · Fikirler: `backlog.md` · Günlük: `session.md`

## İçerik

| Klasör | İçerik |
|---|---|
| `theme/` | ~146 tema JSON'u (+ önizleme PNG/JPG) — Power BI Desktop → Görünüm → Temalar → Temaya gözat |
| `templates/` | ~51 örnek dashboard .pbix (HR, satış, finans, otel, çağrı merkezi, IMF, takvim, KPI kartları, teknik ipuçları…) |
| `wow/` | ~38 Workout Wednesday / yarışma çözüm dosyası (2021–2026) |

## Çalışma Kuralları

- `.pbix` ikili dosya — burada açılıp düzenlenemez; yalnız Power BI Desktop (Windows). Claude'un yapabileceği: tema JSON'larını okuma/düzenleme/doğrulama, envanter ve kataloglama.
- Tema JSON'larında UTF-8 BOM yaygın; okurken `utf-8-sig` kullan. Yazarken BOM'suz UTF-8 de Power BI tarafından kabul edilir.
- **Public repo + üçüncü taraf dosyalar:** yeni dosya eklerken müşteri verisi içeren .pbix koyma; topluluk dosyalarının kaynağını/lisansını not et.
- Büyük ikili dosyalar repo boyutunu şişiriyor; yeni büyük .pbix için Git LFS düşün.
- Oturum sonunda `session.md`'ye kayıt düş, `task.md`'yi güncelle.
