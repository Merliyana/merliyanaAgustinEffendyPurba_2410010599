# Tugas 2 Cloud - Docker Compose PHP App

Aplikasi web PHP sederhana yang berjalan di dalam Docker Container menggunakan Docker Compose.

## Struktur Folder

```
tugas-docker-compose/
├── src/
│   └── index.php        # File utama aplikasi PHP
├── Dockerfile           # Konfigurasi image Docker
├── docker-compose.yml   # Konfigurasi Docker Compose
└── README.md            # Dokumentasi ini
```

## Cara Menjalankan

### 1. Clone / Download repository ini

```bash
git clone <url-repo-kamu>
cd tugas-docker-compose
```

### 2. Jalankan dengan Docker Compose

```bash
docker compose up -d
```

> Flag `-d` artinya berjalan di background (detached mode)

### 3. Buka di browser

```
http://localhost:8080
```

## Perintah Berguna

| Perintah | Fungsi |
|---|---|
| `docker compose up -d` | Menjalankan container |
| `docker compose down` | Menghentikan container |
| `docker compose ps` | Melihat status container |
| `docker compose logs` | Melihat log container |
| `docker compose build` | Build ulang image |

## Teknologi

- **PHP** 8.2
- **Apache** Web Server
- **Docker** & **Docker Compose**
