# Mutsuko, Seiwo Tsukemasu!

> Satu bunga yang mewarnai kantor—Yamamori Mutsuko. Diam-diam, ia memendam perasaan pada atasannya… tapi tunggu dulu, apa nggak terlalu ekstrem caranya!? Beda usia diatasi dengan makanan penambah stamina! Inilah pembuka komedi romantis kantor penuh halu, dipersembahkan untuk seluruh pegawai kantoran yang kelelahan!

---

## Info

| | |
|---|---|
| Judul | Mutsuko, Seiwo Tsukemasu! |
| Judul Alternatif | むつ子、精をつけます！ |
| Author | Suu Anko |
| Tipe | Manga (Hitam Putih) |
| Status | Ongoing |
| Genre | Seinen · Comedy · Romance · Cooking · Office Workers · Slice of Life |
| Chapter | 3 chapter |

## Link

- [MangaDex](https://mangadex.org/title/a254e51d-d8de-4c9a-9bbc-f9c16bcb1f69/mutsuko-seiwo-tsukemasu)
- [Raw](https://comic-walker.com/detail/KC_007406_S/episodes/KC_0074060000300011_E?episodeType=latest)

---

## Struktur

```
Mutsuko/
├── manga-config.json     # Metadata manga
├── manga.json            # Data chapter (auto-generated)
├── manga-automation.js   # Script automation
├── encrypt-manifest.js   # Script enkripsi manifest
├── daily-views.json      # Data views harian
└── <chapter>/
    └── manifest.json     # Daftar halaman (encrypted)
```

## Automation

Semua proses berjalan otomatis via GitHub Actions:

1. Push chapter baru (folder + manifest.json)
2. `encrypt-manifest.yml` — enkripsi manifest
3. `manga-automation.yml` — regenerate manga.json
4. Trigger rebuild ke website utama
5. `sync-cover.yml` — sinkronisasi cover dari website

---

Bagian dari [Nurananto Scanlation](https://nuranantoscans.my.id)