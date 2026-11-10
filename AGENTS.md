# AGENTS.md — sosyal (tanıtım videoları reposu)

Bu repo BKE Studio'nun sosyal medya içerik deposudur (herkese açık). Asıl iş kuralları
**davetiye-maker** reposundaki `AGENTS.md`'dedir ("Güncel iş düzeni"); bu dosya yalnız bu repoya özgü kuralları verir.

## Nereye ne

- `instagram/<YYYY-MM-DD>_<kısa-ad>/` — paylaşıma hazır Reels videoları ve kapakları (tarih + kısa ad, küçük harf, tire).
- `kaynak/<dil>/<tasarim-adi>/` — videoların ham parçaları (ekran kayıtları, ara görseller).
- Kod, prompt, belge ve durum dosyaları buraya konmaz → `davetiye-maker`.
- Davetiye/ilan görselleri buraya konmaz → `dijital-davetiye`.
- PC'de yol: `C:\Users\muzaf\Documents\GitHub\sosyal` (yeniden klonlama yok, başlarken yalnız `git pull`).

## Paylaşım kuralı

Hazırlanan her tanıtım/örnek video Metricool'dan (marka **"BKE Studio"**) Instagram, Facebook, TikTok ve Pinterest'te
**Reels** olarak, bol açıklama ve etiketle paylaşılır. Lisansı belirsiz müzik veya stok kullanılmaz.

## Git

- Her push'tan önce `git pull --rebase origin main`. Force push yok.
- Yalnız o işin dosyaları commit'lenir; ilgisiz yerel değişikliklere dokunulmaz.
- İş bitince kısa rapor, "bitti" ve "buluta (GitHub'a) da yollayayım mı?".
