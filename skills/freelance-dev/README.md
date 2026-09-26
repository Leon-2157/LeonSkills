# freelance-dev

Skill kustom Google Antigravity untuk peran Senior Full Stack Freelance Developer. Menetapkan standar kerja, disiplin teknis, dan etika profesional bagi AI Coding Assistant dalam menangani proyek full-stack.

---

## Tujuan Pembuatan

Memberikan kerangka aturan yang konsisten dan tegas agar asisten AI bekerja selayaknya developer senior sungguhan: efisien, minimalis, profesional, dan berorientasi pada hasil yang siap produksi.

---

## Masalah yang Diselesaikan

- Respon AI yang bertele-tele, penuh basa-basi, dan membuang token.
- Kode yang over-engineered dengan lapisan abstraksi spekulatif.
- Komentar kode panjang yang menjelaskan hal teknis yang sudah jelas dari sintaksis.
- Penggunaan emoticon/emoji yang merusak profesionalisme tampilan kode dan website.
- Logo SVG rakitan AI yang tidak presisi dan tidak memenuhi standar brand.
- AI yang langsung mengedit kode tanpa konfirmasi saat menganalisis bug.
- Dokumentasi (README) yang terlalu panjang dan menduplikasi detail teknis internal.

---

## Fitur Utama

- Komunikasi Ultra-Compressed (zero-fluff, zero basa-basi).
- Zero Emoticon Policy (kode, UI, log, commit, respon).
- Standar komentar kode singkat (maksimal 1 baris deskriptif).
- Real Asset & Logo Policy (anti inline SVG rakitan AI).
- 8 Prinsip Rekayasa Perangkat Lunak Senior (termasuk Security Basics dan Progressive Disclosure).
- Progressive Disclosure pada seluruh lapisan (API, Error Response, Kode, Dokumentasi).
- Standar Dokumentasi README minimalis berbasis Progressive Disclosure.
- Ekosistem Full-Stack kondisional (Java, Python, Go, React, Angular, Tailwind CSS, Docker).
- 3 Intensity Level (lite, full, ultra).

---

## Panduan Pemasangan di Google Antigravity

Antigravity membaca skill dari file bernama `SKILL.md` (huruf kapital) di dalam folder sesuai nama skill.

### Pemasangan Global (Semua Proyek)

```bash
mkdir -p ~/.gemini/config/skills/freelance-dev
cp SKILL.md ~/.gemini/config/skills/freelance-dev/SKILL.md
```

### Pemasangan Khusus Proyek (Workspace-Only)

```bash
mkdir -p <direktori-proyek>/.agents/skills/freelance-dev
cp SKILL.md <direktori-proyek>/.agents/skills/freelance-dev/SKILL.md
```

---

## Cara Penggunaan

Setelah dipasang, Antigravity mendeteksi skill secara otomatis. Contoh pemanggilan:

```text
Gunakan skill freelance-dev untuk membangun backend auth service dengan Go.
```

Atau tentukan level intensitas:

```text
freelance-dev ultra
```

### Intensity Level

| Level | Perilaku |
| :--- | :--- |
| **lite** | Komunikasi formal lengkap. Komentar tetap 1 baris, penjelasan arsitektur lebih deskriptif. Cocok untuk diskusi dan onboarding. |
| **full** (Default) | Ultra-compressed. Seluruh prinsip aktif. Docker untuk service yang di-deploy. |
| **ultra** | Respon absolut minimal: kode/diff dan 1 baris status saja. Cocok untuk iterasi cepat. |

---

Untuk spesifikasi aturan lengkap, prinsip rekayasa, contoh implementasi teknis, dan standar eksekusi, buka berkas [SKILL.md](SKILL.md).
