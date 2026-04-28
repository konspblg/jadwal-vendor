# Cara Update ROB

Untuk menambahkan bulan baru, cukup tambahkan **2 baris kode** berikut:

## 1. Update di bagian `URLS`
Tambahkan 1 baris setelah baris ke-5:

```javascript
6: BASE + '?gid=XXXXXXXX&single=true&output=csv',
```

Ganti `XXXXXXXX` dengan **gid** dari sheet bulan Juni kamu.

---

## 2. Update di dropdown `monthSelect`
Tambahkan 1 baris setelah opsi bulan Mei:

```html
<option value="6">Juni 2026</option>
```

> ⚠️ Catatan:
> Dropdown bulan ini ada di **2 lokasi** (sticky area ROB), jadi pastikan kamu menambahkan baris ini di **keduanya**.
