![CI](https://github.com/satnurz85-web/compose-ci-minggu11/actions/workflows/compose-check.yml/badge.svg)

Stack WordPress + MariaDB dengan CI GitHub Actions. Workflow 'compose-check.yml' memvalidasi 'docker-compose.yml' setiap push ke 'main' dan setiap Pull Request.

## Cara menjalankan

```
cp .env.example .env
docker compose up -d
```

Buka http://localhost:8080. Ganti kata sandi di '.env' sebelum dipakai. Untuk mematikan: 'docker compose down'.

## Bukti

### 1. Tab Actions dengan run hijau
![Actions hijau](docs/01-actions-hijau.png)

### 2. Detail job validate
![Detail job](docs/02-detail-job.png)

### 3. Halaman repo dan badge
![Repo dan badge](docs/03-repo-badge.png)

## Bonus

Run merah dibuat dengan sengaja di Pull Request #1 (indentasi 'docker-compose.yml' dirusak), lalu diperbaiki sampai hijau dan di-merge. Workflow juga menjalankan 'docker compose up -d', 'ps', dan 'down -v'.

## Sumber bantuan

Dibantu Claude (AI) untuk panduan langkah dan penyusunan laporan. Semua perintah saya jalankan sendiri.
