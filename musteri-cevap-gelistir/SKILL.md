---
name: musteri-cevap-gelistir
description: Use when the user pastes a client's message (e-posta, Basecamp, Slack vb.) together with their own taslak cevabı and asks to improve/polish the reply — especially when technical/marketing context (GA4, GTM, Consent Mode, çerez yönetimi, SEO/analitik konuları vb.) should be added accurately without changing their voice or making promises they didn't make.
---

# Müşteri Cevabı Geliştirme

## Overview

Ajans veya danışman olarak müşterilere teknik pazarlama/analitik konularda (çerez yönetimi, GA4, GTM, Consent Mode vb.) cevap yazan kullanıcı için. Amaç, kullanıcının taslağını **kendi tonunu ve kararını koruyarak** daha net, doğru ve profesyonel hale getirmek.

Kullanıcının kendi yazım kalıplarını tanımlayan bir skill'i varsa (hitap, kapanış, sen/siz tercihi) onu esas al. Yoksa taslaktaki ve müşteri mesajındaki hitap ile kapanışı aynen koru.

## When to Use

- Kullanıcı bir müşteri mesajı ve kendi taslak cevabını yapıştırıp "bunu iyileştir" dediğinde.
- Cevaba eksik kalan teknik bir bağlamın (ör. Consent Mode nasıl çalışır, neden trafik/veri kaybı olur) kısa ve doğru şekilde eklenmesi gerektiğinde.

Kullanma: Kullanıcı içeriği kendisi yazıp yalnız görüş isterse normal sohbet yeterli.

## Core Pattern

1. **Müşteri mesajını ve taslağı oku.** Taslağın tonunu (kısa, direkt, ajans-müşteri resmiyeti) ve verdiği kararları (ör. "trafik kaybı kaçınılmaz") olduğu gibi koru; yalnız netleştir.
2. **Eksik veya belirsiz teknik noktayı bul.** Taslağın sözünü tutan, doğrulanabilir teknik detayı (ör. Consent Mode v2, basic/advanced mod farkı) ekle. Emin olmadığın teknik iddiayı uydurma; kullanıcıya sor ya da "kurulum sonrası teyit edelim" gibi açık bırak.
3. **Fazla uzatma.** Müşteriye gidecek bir metin bu. Teknik detay için madde imi uygun, ama gövde düz yazı kalsın.
4. **Tek, kullanıma hazır versiyon göster.** İstenirse alternatif ton/uzunluk sun.
5. **Panoya kopyala (varsa):** Son metni panoya kopyala; macOS'ta `pbcopy <<'EOF' ... EOF`, Linux'ta `xclip -selection clipboard` / `wl-copy`, Windows'ta `clip`. Araç yoksa bu adımı atla. Müşteriye gönderme (e-posta, Basecamp) her zaman kullanıcının elinde kalır.

## Quick Reference

| Durum | Yapılacak |
|---|---|
| Teknik iddia belirsiz | Uydurma; "teyit edelim" ile açık bırak veya kullanıcıya sor |
| Kullanıcının kararı (fiyat, süre, sorumluluk) | Değiştirme, yalnız ifadeyi netleştir |
| Metin çok uzadı | Madde imlerini azalt, gövdeyi kısalt |

## Common Mistakes

- Kullanıcının net kararını (ör. trafik kaybı kaçınılmazdır) yumuşatıp belirsizleştirmek.
- Emin olunmayan teknik detayı (versiyon numarası, kesin süre) kesin dille yazmak; belirsizse koşullu ifade kullan.
- Metni kendiliğinden e-posta/Basecamp üzerinden müşteriye göndermek.
