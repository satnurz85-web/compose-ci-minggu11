# compose-ci-minggu11

![CI](https://github.com/satnurz85-web/compose-ci-minggu11/actions/workflows/compose-check.yml/badge.svg)
## Bukti

### 1. Tab Actions dengan run hijau 
<img width="959" height="539" alt="image" src="https://github.com/user-attachments/assets/f6d633a0-e34e-4c2d-bc26-e6152cfe3b2e" />

### 2. Pull Request dengan check gagal (merah)
<img width="959" height="539" alt="Screenshot 2026-11-21 154054" src="https://github.com/user-attachments/assets/246dec92-b5bf-47a0-8b40-200416b303a6" />

### 3. Badge status
<img width="959" height="539" alt="image" src="https://github.com/user-attachments/assets/a1b4ee17-0f7b-43e6-838b-59c7ac5d7764" />

## Bonus: uji jalankan stack
<img width="959" height="539" alt="image" src="https://github.com/user-attachments/assets/132e0e27-e016-4740-b1be-60d4ba3cea58" />

Workflow juga menjalankan 'docker compose up -d', 'docker compose ps', 
lalu 'docker compose down -v' di runner GitHub untuk memastikan 
WordPress dan MariaDB benar-benar bisa berjalan.

### Bukti run hijau setelah bonus
<img width="959" height="536" alt="image" src="https://github.com/user-attachments/assets/aac904e5-8b7b-413e-b009-e3978d336857" />

Semua run di branch main berstatus hijau, termasuk run setelah
step 'docker compose up -d', 'docker compose ps', dan 'docker compose down -v' ditambahkan.
