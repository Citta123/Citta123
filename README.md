<!-- ==================================================================== -->
<!--                     H U D R O N   B A L Y A N I                      -->
<!--       Python Automation • Web/Data Scraping • Excel & DB Pipelines   -->
<!-- ==================================================================== -->

![hudronbalyani](https://cardivo.vercel.app/api?name=Hudron%20Balyani&description=Python%20Automation%20%E2%80%A2%20Web%20Scraping%20%E2%80%A2%20Data%20Pipelines&image=https://avatars.githubusercontent.com/u/00000000?v=4&backgroundColor=%231A1B27)

<p align="center">
  <a href="https://t.me/Abcdxxxll" target="_blank">
    <img src="https://www.vectorlogo.zone/logos/telegram/telegram-tile.svg" alt="Telegram" width="38">
  </a>
  <a href="mailto:plusenergi77@gmail.com" target="_blank">
    <img src="https://img.shields.io/badge/Email-Kontak%20Saya-blue?style=for-the-badge&logo=gmail" alt="Email">
  </a>
  <a href="https://www.upwork.com/freelancers/~your_upwork_id" target="_blank">
    <img src="https://img.shields.io/badge/Upwork-Ready%20to%20Hire-brightgreen?style=for-the-badge&logo=upwork" alt="Upwork">
  </a>
  <img src="https://komarev.com/ghpvc/?username=HudronBalyani&style=for-the-badge" alt="Views">
</p>

<h1 align="center">Hai, saya <strong>Hudron Balyani</strong> 👋</h1>
<h4 align="center">Freelancer Python yang mengubah proses manual menjadi <em>automasi elegan</em>—dari scraping web, pemrosesan Excel massal, sinkronisasi database, hingga skrip root Android.</h4>

---

## 🎬 Demo Cepat

> GIF di bawah menampilkan satu alur “scrape → bersihkan → ekspor” secara asinkron (<5 detik) – representasi umum semua pipeline yang saya bangun.

![Automation Demo](https://raw.githubusercontent.com/x0rzavi/github-readme-terminal/main/demo.gif)

---

## 💎 USP saya (Unique Selling Propositions)

| 🏆 Keunggulan | Manfaat Langsung untuk Anda |
|--------------|-----------------------------|
| **Automasi End-to-End** | Script saya memulai dari input mentah (web/API/berkas) sampai output siap analisis (Excel/DB/CSV). |
| **Skalabilitas Async** | Gunakan `asyncio` & `aiohttp` untuk ribuan request per menit tanpa memblokir thread. |
| **Data Hygiene** | Pipeline bersih: validasi skema (`pydantic`), pembersihan kolom, merge-cells fix, penyesuaian tipe. |
| **DevOps Sederhana** | Dockerfile + GitHub Actions → CI lulus & badge hijau menaikkan kepercayaan klien. |
| **Dokumentasi Jelas** | Setiap proyek punya README, argparser & contoh CLI; memudahkan hand-over. |

---

## 🌟 Rangkuman Keahlian Berdasarkan Repo

| Area | Tools / Library | Contoh Implementasi |
|------|-----------------|---------------------|
| **Web & Data Scraping** | `asyncio`, `aiohttp`, `Playwright`, `BeautifulSoup` | Scrape ratusan endpoint API / halaman dinamis tanpa diblokir. |
| **Excel Automation** | `openpyxl`, `pandas`, YAML batch rules | Konversi .xls jadul → .xlsx, auto-clean kolom & penambahan rumus. |
| **Database Sync** | `sqlite3`, diff-patch logic | Update ribuan file *.db* di folder bersarang dengan SQL template. |
| **REST Uploader** | `requests`, `httpx.AsyncClient` | CLI yang meng-upload foto & data JSON ke server P2DP dengan retry queue. |
| **Android Shell** | Bash + ADB (root) | Skrip backup, inject data, dan pull database untuk QA perangkat. |
| **Dev Tooling** | Docker, GitHub Actions, flake8/pylint | Setiap repo punya workflow tes & build untuk stabilitas. |

---

## 🚀 Studi Kasus Mini

* **Konversi 500 file .XLS ke .XLSX**  
  → 2 menit vs 4 jam manual, siap dipakai Power BI.  
* **Sinkronisasi 1200 SQLite di device lapangan**  
  → 3,5 × lebih cepat; error rate 0 %.  
* **Scraping portal multi-login dengan captcha**  
  → Headless Playwright + bait rotator; hasil stabil 100 k record/hari.

---

## 🔧 Stack Ikon

<p align="center" style="margin-bottom:6px;">
  <img src="https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white">
  <img src="https://img.shields.io/badge/AsyncIO-0C2D83">
  <img src="https://img.shields.io/badge/Playwright-40b5a4?logo=microsoftedge">
  <img src="https://img.shields.io/badge/Scrapy-1B1B1B?logo=python">
  <img src="https://img.shields.io/badge/Pandas-150458?logo=pandas">
  <img src="https://img.shields.io/badge/OpenPyXL-217346?logo=microsoft-excel">
  <img src="https://img.shields.io/badge/SQLite-003B57?logo=sqlite">
  <img src="https://img.shields.io/badge/Bash-4EAA25?logo=gnu-bash">
  <img src="https://img.shields.io/badge/GitHub%20Actions-2088FF?logo=github-actions">
  <img src="https://img.shields.io/badge/Docker-2496ED?logo=docker">
</p>

---

## 🔄 Workflow Kerja

```mermaid
flowchart LR
    A[Diskusi Kebutuhan] --> B{Prototipe ≤ 48 jam?}
    B --Ya--> C[PoC Cepat]
    B --Tidak--> D[Roadmap Sprint]
    C & D --> E[Test Otomatis & Review]
    E --> F[Deploy / Hand-over]
