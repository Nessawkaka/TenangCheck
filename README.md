# TenangCheck

**Semak dahulu, sebelum klik.** / *Check first, then click.*

TenangCheck membantu sesiapa sahaja, daripada pelajar 20 tahun hingga warga emas 68 tahun, mengenal pasti mesej, nombor telefon dan panggilan scam sebelum bertindak.

Prototaip untuk **MDEC–KAF Digital Bank Launchpad Accelerator** (KIRO Workshop & Innovation Challenge), Use Case 1: *Spot the Scam*.

## Ciri utama / Features

- **Semak:** semak mesej (9 contoh), nombor telefon (dengan laporan demo) dan panggilan (4 soalan + demo Pengawal Panggilan).
- **Lapor:** lapor nombor scammer tanpa log masuk, terus selepas menyemak nombor. Boleh ditarik balik.
- **Belajar:** 7 tanda scammer, 10 jenis scam dengan sumber rasmi, mitos dan fakta, skrip panggilan, kuiz dan kad kongsi.
- **Kecemasan:** langkah segera, senarai "Sediakan sebelum menelefon", pilih bank untuk hubungi hotline fraud, dan kenalan dipercayai.
- BM/EN, 4 saiz tulisan, mod Auto/Terang/Gelap, mesra pembaca skrin dan papan kekunci.

## Cara guna / Run locally

Buka `index.html` dalam mana-mana pelayar web. Tiada build step, tiada backend.

## Deploy ke GitHub Pages

1. Buat repo awam baharu dan muat naik `index.html`, `README.md` dan `.nojekyll`.
2. Pergi ke **Settings → Pages**.
3. Di bawah **Build and deployment**, pilih **Deploy from a branch**, branch `main`, folder `/ (root)`, kemudian **Save**.
4. Tunggu beberapa minit. Pautan akan muncul di halaman yang sama dalam bentuk `https://<username>.github.io/<nama-repo>/`.

Pautan terus ke bahagian tertentu: `#nombor`, `#call`, `#kuiz`, `#jenis`, `#mitos`, `#skrip`, `#kongsi`, `#sumber`, `#kecemasan`.

## Data dan privasi

- Semakan mesej dibuat dalam pelayar menggunakan peraturan berwajaran. Mesej tidak dihantar ke mana-mana.
- Data laporan ialah **DEMO** (nombor rekaan). Laporan pengguna disimpan dalam `localStorage` peranti itu sahaja.
- Nombor hotline fraud bank disalin daripada direktori ABM.

## Sumber rasmi

- [Semak Mule (PDRM)](https://semakmule.rmp.gov.my/)
- [BNM: Financial Scam Education](https://www.bnm.gov.my/financial-fraud-alerts)
- [NSRC FAQ (NFCC)](https://nfcc.jpm.gov.my/index.php/en/about-nsrc)
- [SC Investor Alert List](https://www.sc.com.my/investor-alert-list)
- [ABM Safe Online Banking](https://www.abm.org.my/safe-online-banking/)
- [ABM bank hotline directory](https://www.abm.org.my/safe-online-banking/directory/)

## Penafian / Disclaimer

Ini prototaip hackathon dan bukan perkhidmatan rasmi. Semakan boleh tersilap. Sentiasa sahkan melalui saluran rasmi: hotline 24 jam bank anda (nombor di belakang kad), 997 (NSRC) dan laporan polis dalam masa 24 jam.
