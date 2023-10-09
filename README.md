
# Sistem Informasi Bengkel Cat Berbasis Web

Project ini merupakan tugas akhir yang digunakan untuk memenuhi persyaratan kelulusan DII di AKN Pacitan

Dibangun menggunakan 
- Laravel 9
- Bootsrap 5

# Sistem Informasi Bengkel Cat Berbasis Web

![screencapture-si-bengkel-test-2023-10-09-18_33_08](https://github.com/Alvinn549/sistem-informasi-bengkel-cat-berbasis-web/assets/110670962/b07d0bee-6442-487b-bd2c-654c18d04b34)

![screencapture-si-bengkel-test-manage-menu-2023-10-09-18_34_59 (1)](https://github.com/Alvinn549/sistem-informasi-bengkel-cat-berbasis-web/assets/110670962/da0ebb77-beee-4fe4-a81d-4a48c69e3421)

![screencapture-si-bengkel-test-manage-users-2023-10-09-18_35_17](https://github.com/Alvinn549/sistem-informasi-bengkel-cat-berbasis-web/assets/110670962/590bfde3-21fb-4572-ab87-128bb7a0d1dd)

![screencapture-si-bengkel-test-manage-users-2023-10-09-18_35_28](https://github.com/Alvinn549/sistem-informasi-bengkel-cat-berbasis-web/assets/110670962/a24a4570-642b-4a79-9e29-2c99394d33c2)

![screencapture-si-bengkel-test-manage-berita-add-2023-10-09-18_36_31](https://github.com/Alvinn549/sistem-informasi-bengkel-cat-berbasis-web/assets/110670962/9b95c0a5-6790-43f5-b38b-c04721dac1ad)

![screencapture-si-bengkel-test-show-myVehicle-repairs-1-OxttPglVM7-2023-10-09-18_41_04](https://github.com/Alvinn549/sistem-informasi-bengkel-cat-berbasis-web/assets/110670962/4f7d34f7-4f47-499c-b2c1-8cd052f3a7b4)

## Default Account for testing

**Admin Default Account**

- username : admin1
- Password : admin12345

## Deployment

To deploy this project

1. **Clone Repository**

```bash
  git clone https://github.com/Alvinn549/sistem-informasi-bengkel-cat-berbasis-web

  cd sistem-informasi-bengkel-cat-berbasis-web

  composer install
```

2. **Buat file `.env`**

```bash
  cp .env.example .env
```

3. **Buka `.env` lalu ubah baris berikut sesuai dengan databasemu yang ingin dipakai**

```bash
  DB_PORT=3306
  DB_DATABASE=laravel
  DB_USERNAME=root
  DB_PASSWORD=
```

4. **Buka `.env` lalu tambahkan baris berikut**

```bash
  TIMEZONE=Asia/Jakarta
  INDONESIA=id
  FAKER_LOCALE=id_ID
  FILESYSTEM_DISK=public
```

5. **Generate app key**

```bash
  php artisan key:generate
```

6. **Jalankan migration dan seeder**

```bash
  php artisan migrate --seed
```

7. **Jalankan storage link**

```bash
  php artisan storage:link
```

8. **Jalankan website**

```bash
  php artisan serve
```
