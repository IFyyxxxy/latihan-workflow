# Contributing Guide

## Branch Convention
Format: `<type>/<short-description>`

| Type | Kegunaan | Contoh |
| --- | --- | --- |
| `feature/` | Fitur baru | `feature/123-user-login` |
| `fix/` | Bug fix | `fix/cart-total` |
| `hotfix/` | Perbaikan darurat production | `hotfix/payment-down` |
| `refactor/` | Refactor kode | `refactor/order-service` |
| `docs/` | Dokumentasi | `docs/api-reference` |
| `test/` | Pengujian unit/integration | `test/checkout-flow` |
| `chore/` | Maintenance & dependensi | `chore/update-deps` |

**Aturan:** Huruf kecil semua, gunakan hyphen (-), sertakan nomor tiket jika ada, maks. 50 karakter.

## Commit Convention
Format: `<type>(<scope>): <subject>`

**Tipe:** `feat`, `fix`, `docs`, `style`, `refactor`, `perf`, `test`, `build`, `ci`, `chore`, `revert`

**Contoh:**
- `feat(auth): add JWT refresh token`
- `fix(cart): correct total calculation`
- `docs(readme): update installation steps`

**Aturan:** Subject lowercase, imperative mood, tanpa titik di akhir, maksimal 50 karakter.

## Pull Request & Code Review
- Judul PR menggunakan format Conventional Commits.
- Ukuran PR disarankan < 400 baris perubahan.
- Wajib minimal 1 approval reviewer sebelum di-merge.
- Gunakan metode **Squash Merge**.

## Larangan Utama
- Dilarang push langsung ke branch `main`.
- Dilarang commit message yang acak (`wip`, `fix`, `asdf`).
- Dilarang mengunggah file `.env`, `node_modules/`, atau kredensial rahasia.