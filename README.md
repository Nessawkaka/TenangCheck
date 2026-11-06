# TenangCheck

**Semak dahulu, sebelum klik.** / *Check first, then click.*

TenangCheck membantu sesiapa sahaja, daripada pelajar 20 tahun hingga warga emas 68 tahun, mengenal pasti mesej, nombor telefon dan panggilan scam sebelum bertindak.

https://nessawkaka.github.io/TenangCheck/

Prototaip untuk **MDEC–KAF Digital Bank Launchpad Accelerator** (KIRO Workshop & Innovation Challenge), Use Case 1: *Spot the Scam*.

## Ciri utama / Features

- **Semak**
  - **Mesej:** tampal mesej dan dapat verdict (Bahaya, Waspada atau Tiada tanda bahaya) beserta tanda yang dikesan. Ada 2 contoh mesej scam dan 2 contoh mesej sebenar.
  - **Nombor:** semak nombor dengan laporan demo, lapor nombor scammer tanpa log masuk (boleh ditarik balik), dan senarai amaran terkini.
  - **Panggilan:** 4 soalan pantas, demo Pengawal Panggilan (skrip automatik), dan mod mikrofon untuk cuba dengan suara sendiri.
- **Berita dan sumber rasmi:** carousel berita scam terkini dan laman rasmi yang berpusing sendiri, dengan butang ‹ ›.
- **Belajar:** Ciri-ciri scammer (termasuk contoh skrip panggilan scammer), Jenis scam (10 jenis dengan sumber rasmi), Kuiz, Fakta untuk dikongsi (kad kongsi serta mitos dan fakta), dan Sumber rasmi.
- **Kecemasan:** langkah segera bernombor dengan butang telefon bank (direktori ABM) dan 997, senarai "Sediakan sebelum menelefon", kenalan dipercayai, dan lapor nombor.
- BM/EN, 2 saiz tulisan (17px dan 20px), mod terang/gelap, mesra pembaca skrin dan papan kekunci.

## Cara guna / Run locally

Buka `index.html` dalam mana-mana pelayar web. Tiada build step, tiada backend.

## Deploy ke GitHub Pages

1. Muat naik `index.html`, `README.md` dan `.nojekyll` ke root repo (bukan dalam folder).
2. Pergi ke **Settings → Pages**.
3. Di bawah **Build and deployment**, pilih **Deploy from a branch**, branch `main`, folder `/ (root)`, kemudian **Save**.
4. Tunggu run dalam tab **Actions** jadi hijau. Pautan akan muncul di **Settings → Pages**.

Pautan terus ke bahagian tertentu: `#semak`, `#nombor`, `#call`, `#belajar`, `#jenis`, `#kuiz`, `#kongsi`, `#sumber`, `#kecemasan`. Pautan lama `#skrip` dan `#mitos` masih berfungsi.

## Data dan privasi

- Semakan mesej dibuat dalam pelayar menggunakan peraturan berwajaran. Mesej tidak dihantar ke mana-mana.
- Data laporan ialah **DEMO** (nombor rekaan). Laporan pengguna disimpan dalam `localStorage` peranti itu sahaja.
- Nombor hotline fraud bank disalin daripada direktori ABM.
- Berita dalam carousel dikemas kini secara manual (terakhir: 4 Nov 2026).

## Sumber rasmi

- [Semak Mule (PDRM)](https://semakmule.rmp.gov.my/)
- [BNM: Financial Scam Education](https://www.bnm.gov.my/financial-fraud-alerts)
- [NSRC FAQ (NFCC)](https://nfcc.jpm.gov.my/index.php/en/about-nsrc)
- [SC Investor Alert List](https://www.sc.com.my/investor-alert-list)
- [ABM Safe Online Banking](https://www.abm.org.my/safe-online-banking/)
- [ABM bank hotline directory](https://www.abm.org.my/safe-online-banking/directory/)

## Penafian / Disclaimer

Ini prototaip hackathon dan bukan perkhidmatan rasmi. Semakan boleh tersilap. Sentiasa sahkan melalui saluran rasmi: hotline 24 jam bank anda (nombor di belakang kad), 997 (NSRC) dan laporan polis dalam masa 24 jam.
