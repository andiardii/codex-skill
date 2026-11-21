# Codex Skills

[`$start`](start/SKILL.md) mengganti judul chat yang sedang terbuka di Codex desktop sesuai judul yang kamu ketik.

## Instalasi

Jika belum punya salinan repositori ini, jalankan perintah berikut di terminal.

```sh
git clone https://github.com/andiardii/codex-skill.git
cd codex-skill
```

Dari folder repositori, jalankan perintah berikut untuk memasang skill ke akun pengguna kamu di komputer ini.

```sh
mkdir -p ~/.agents/skills
cp -R start ~/.agents/skills/
```

Jika `$start` belum muncul di Codex, mulai ulang aplikasinya.

## Cara pakai

Buka chat yang ingin kamu ganti judulnya, lalu kirim perintah berikut di kolom chat Codex.

```text
$start Rencana Website Baru
```

Judul chat di sidebar akan berubah menjadi **Rencana Website Baru**. Ganti teks setelah `$start` dengan judul pilihanmu. Jika kamu mengirim `$start` saja, Codex akan meminta judulnya.

Skill ini dipanggil secara eksplisit dengan `$start` dan membutuhkan fitur penggantian judul chat di Codex desktop.
