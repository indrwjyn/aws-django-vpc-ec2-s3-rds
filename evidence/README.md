# Galeri Bukti Pengerjaan

🇬🇧 **English version:** [README.en.md](README.en.md) · [← Kembali ke README utama](../README.md)

Seluruh screenshot AWS Console dan terminal yang menjadi bukti tiap level, ditampilkan langsung di halaman ini. Penomoran mengikuti [laporan](../docs/Laporan_Tugas1_Level1-3_Kelompok_I.pdf). Penjelasan tiap langkah ada di [Level 1](../docs/level-1-vpc-ec2.md), [Level 2](../docs/level-2-s3-iam.md), dan [Level 3](../docs/level-3-rds.md).

> **Catatan privasi:** ID akun AWS, email pengirim pesan kontak, dan IP publik anggota (rule SSH `/32`) sudah ditutup kotak abu-abu. Tidak ada password, secret key, atau access key pada gambar mana pun.


## Level 1: VPC dan EC2

### Gambar 1.1

<p align="center">
  <img src="level-1-vpc-ec2/01_daftar-lima-iam-user-milik-anggota-kelompok.png" alt="Daftar lima IAM user milik anggota kelompok." width="760"><br>
  <em>Daftar lima IAM user milik anggota kelompok.</em>
</p>

### Gambar 2.1

<p align="center">
  <img src="level-1-vpc-ec2/02_vpc-vpc-berhasil-dibuat.png" alt="VPC pcm-kelompok-i-vpc berhasil dibuat." width="760"><br>
  <em>VPC pcm-kelompok-i-vpc berhasil dibuat.</em>
</p>

### Gambar 2.2

<p align="center">
  <img src="level-1-vpc-ec2/03_pengaturan-vpc-setelah-dns-resolution-dan-dns.png" alt="Pengaturan VPC setelah DNS resolution dan DNS hostnames diaktifkan." width="760"><br>
  <em>Pengaturan VPC setelah DNS resolution dan DNS hostnames diaktifkan.</em>
</p>

### Gambar 2.3

<p align="center">
  <img src="level-1-vpc-ec2/04_daftar-subnet-empat-subnet-pcm-kelompok-i.png" alt="Daftar subnet, empat subnet pcm-kelompok-i dan tiga subnet bawaan VPC default." width="760"><br>
  <em>Daftar subnet, empat subnet pcm-kelompok-i dan tiga subnet bawaan VPC default.</em>
</p>

### Gambar 2.4

<p align="center">
  <img src="level-1-vpc-ec2/05_internet-gateway-igw-dengan-status-attached.png" alt="Internet Gateway pcm-kelompok-i-igw dengan status Attached." width="760"><br>
  <em>Internet Gateway pcm-kelompok-i-igw dengan status Attached.</em>
</p>

### Gambar 2.5

<p align="center">
  <img src="level-1-vpc-ec2/06_route-public-rt-0-0-0-0.png" alt="Route public-rt, 0.0.0.0/0 menuju igw dan 10.0.0.0/16 local." width="760"><br>
  <em>Route public-rt, 0.0.0.0/0 menuju igw dan 10.0.0.0/16 local.</em>
</p>

### Gambar 2.6

<p align="center">
  <img src="level-1-vpc-ec2/07_subnet-association-public-rt-yaitu-public-a.png" alt="Subnet association public-rt, yaitu public-a dan public-b." width="760"><br>
  <em>Subnet association public-rt, yaitu public-a dan public-b.</em>
</p>

### Gambar 2.7

<p align="center">
  <img src="level-1-vpc-ec2/08_route-private-rt-hanya-route-local-10.png" alt="Route private-rt, hanya route local 10.0.0.0/16." width="760"><br>
  <em>Route private-rt, hanya route local 10.0.0.0/16.</em>
</p>

### Gambar 2.8

<p align="center">
  <img src="level-1-vpc-ec2/09_subnet-association-private-rt-yaitu-private-a.png" alt="Subnet association private-rt, yaitu private-a dan private-b." width="760"><br>
  <em>Subnet association private-rt, yaitu private-a dan private-b.</em>
</p>

### Gambar 2.9

<p align="center">
  <img src="level-1-vpc-ec2/10_resource-map-vpc-vpc.png" alt="Resource map VPC pcm-kelompok-i-vpc." width="760"><br>
  <em>Resource map VPC pcm-kelompok-i-vpc.</em>
</p>

### Gambar 3.1

<p align="center">
  <img src="level-1-vpc-ec2/11_inbound-rules-web-sg-http-80-dan.png" alt="Inbound rules pcm-kelompok-i-web-sg (HTTP 80 dan SSH 22 dari IP anggota)." width="760"><br>
  <em>Inbound rules pcm-kelompok-i-web-sg (HTTP 80 dan SSH 22 dari IP anggota).</em>
</p>

### Gambar 4.1

<p align="center">
  <img src="level-1-vpc-ec2/12_elastic-ip-16-78-139-41-berhasil.png" alt="Elastic IP 16.78.139.41 berhasil di-associate ke instance EC2." width="760"><br>
  <em>Elastic IP 16.78.139.41 berhasil di-associate ke instance EC2.</em>
</p>

### Gambar 4.2

<p align="center">
  <img src="level-1-vpc-ec2/13_detail-instance-web-status-running-dan-3.png" alt="Detail instance pcm-kelompok-i-web, status Running dan 3/3 checks passed." width="760"><br>
  <em>Detail instance pcm-kelompok-i-web, status Running dan 3/3 checks passed.</em>
</p>

### Gambar 5.1

<p align="center">
  <img src="level-1-vpc-ec2/14_berhasil-masuk-ke-server-lewat-ssh-ip.png" alt="Berhasil masuk ke server lewat SSH, IP privat 10.0.1.67." width="760"><br>
  <em>Berhasil masuk ke server lewat SSH, IP privat 10.0.1.67.</em>
</p>

### Gambar 6.1

<p align="center">
  <img src="level-1-vpc-ec2/15_hasil-migrate-collectstatic-dan-seed-pcm-lalu.png" alt="Hasil migrate, collectstatic, dan seed_pcm, lalu createsuperuser." width="760"><br>
  <em>Hasil migrate, collectstatic, dan seed_pcm, lalu createsuperuser.</em>
</p>

### Gambar 7.1

<p align="center">
  <img src="level-1-vpc-ec2/16_status-service-pcm-dan-hasil-curl-ke.png" alt="Status service pcm dan hasil curl ke Gunicorn, HTTP 200 OK." width="760"><br>
  <em>Status service pcm dan hasil curl ke Gunicorn, HTTP 200 OK.</em>
</p>

### Gambar 8.1

<p align="center">
  <img src="level-1-vpc-ec2/17_status-service-nginx-active-running-dan-enabled.png" alt="Status service Nginx, active (running) dan enabled." width="760"><br>
  <em>Status service Nginx, active (running) dan enabled.</em>
</p>

### Gambar 9.1

<p align="center">
  <img src="level-1-vpc-ec2/18_beranda-website-pcm-dengan-tagline-deployed-by.png" alt="Beranda website PCM dengan tagline Deployed by kelompok-i di header." width="760"><br>
  <em>Beranda website PCM dengan tagline Deployed by kelompok-i di header.</em>
</p>

### Gambar 9.2

<p align="center">
  <img src="level-1-vpc-ec2/19_halaman-status-yang-menunjukkan-level-1-terdeteksi.png" alt="Halaman /status/ yang menunjukkan Level 1 terdeteksi." width="760"><br>
  <em>Halaman /status/ yang menunjukkan Level 1 terdeteksi.</em>
</p>

### Gambar 9.3

<p align="center">
  <img src="level-1-vpc-ec2/20_tagline-di-header-dan-berita-dengan-gambar.png" alt="Tagline di header dan berita dengan gambar unggahan pada beranda." width="760"><br>
  <em>Tagline di header dan berita dengan gambar unggahan pada beranda.</em>
</p>


## Level 2: S3 dan IAM Role

### Gambar L2.1.1

<p align="center">
  <img src="level-2-s3-iam/01_tab-permissions-bucket-block-all-public-access.png" alt="Tab Permissions bucket, Block all public access dimatikan." width="760"><br>
  <em>Tab Permissions bucket, Block all public access dimatikan.</em>
</p>

### Gambar L2.1.2

<p align="center">
  <img src="level-2-s3-iam/02_object-ownership-bucket-owner-enforced-acl-tidak.png" alt="Object Ownership bucket owner enforced, ACL tidak dipakai." width="760"><br>
  <em>Object Ownership bucket owner enforced, ACL tidak dipakai.</em>
</p>

### Gambar L2.1.3

<p align="center">
  <img src="level-2-s3-iam/03_isi-bucket-folder-media-dan-static.png" alt="Isi bucket, folder media/ dan static/." width="760"><br>
  <em>Isi bucket, folder media/ dan static/.</em>
</p>

### Gambar L2.2.1

<p align="center">
  <img src="level-2-s3-iam/04_bucket-policy-getobject-hanya-untuk-static-dan.png" alt="Bucket policy, GetObject hanya untuk static/* dan media/*." width="760"><br>
  <em>Bucket policy, GetObject hanya untuk static/* dan media/*.</em>
</p>

### Gambar L2.3.1

<p align="center">
  <img src="level-2-s3-iam/05_trust-relationship-role-hanya-ec2-amazonaws-com.png" alt="Trust relationship role, hanya ec2.amazonaws.com yang boleh assume role." width="760"><br>
  <em>Trust relationship role, hanya ec2.amazonaws.com yang boleh assume role.</em>
</p>

### Gambar L2.3.2

<p align="center">
  <img src="level-2-s3-iam/06_inline-policy-pcm-s3-access-listbucket-dan.png" alt="Inline policy pcm-s3-access (ListBucket dan ManageObjects)." width="760"><br>
  <em>Inline policy pcm-s3-access (ListBucket dan ManageObjects).</em>
</p>

### Gambar L2.3.3

<p align="center">
  <img src="level-2-s3-iam/07_detail-instance-iam-role-ec2-s3-role.png" alt="Detail instance, IAM role pcm-kelompok-i-ec2-s3-role terpasang." width="760"><br>
  <em>Detail instance, IAM role pcm-kelompok-i-ec2-s3-role terpasang.</em>
</p>

### Gambar L2.4.1

<p align="center">
  <img src="level-2-s3-iam/08_hasil-aws-sts-get-caller-identity-identitasnya.png" alt="Hasil aws sts get-caller-identity, identitasnya assumed-role." width="760"><br>
  <em>Hasil aws sts get-caller-identity, identitasnya assumed-role.</em>
</p>

### Gambar L2.5.1

<p align="center">
  <img src="level-2-s3-iam/09_hasil-sync-media-daftar-objek-di-s3.png" alt="Hasil sync media, daftar objek di S3, dan collectstatic." width="760"><br>
  <em>Hasil sync media, daftar objek di S3, dan collectstatic.</em>
</p>

### Gambar L2.6.1

<p align="center">
  <img src="level-2-s3-iam/10_konfigurasi-s3-pada-env-dan-bukti-tidak.png" alt="Konfigurasi S3 pada .env dan bukti tidak ada access key." width="760"><br>
  <em>Konfigurasi S3 pada .env dan bukti tidak ada access key.</em>
</p>

### Gambar L2.7.1

<p align="center">
  <img src="level-2-s3-iam/11_halaman-status-yang-menunjukkan-level-2-terdeteksi.png" alt="Halaman /status/ yang menunjukkan Level 2 terdeteksi dan S3Storage." width="760"><br>
  <em>Halaman /status/ yang menunjukkan Level 2 terdeteksi dan S3Storage.</em>
</p>

### Gambar L2.7.2

<p align="center">
  <img src="level-2-s3-iam/12_page-source-beranda-css-dan-logo-dimuat.png" alt="Page source beranda, CSS dan logo dimuat dari S3." width="760"><br>
  <em>Page source beranda, CSS dan logo dimuat dari S3.</em>
</p>

### Gambar L2.7.3

<p align="center">
  <img src="level-2-s3-iam/13_find-tidak-menemukan-file-di-disk-ec2.png" alt="find tidak menemukan file di disk EC2, tetapi file ada di S3." width="760"><br>
  <em>find tidak menemukan file di disk EC2, tetapi file ada di S3.</em>
</p>

### Gambar L2.7.4

<p align="center">
  <img src="level-2-s3-iam/14_objek-uji-s3-png-pada-media-posts.png" alt="Objek uji-s3.png pada media/posts/2026/10/ di konsol S3." width="760"><br>
  <em>Objek uji-s3.png pada media/posts/2026/10/ di konsol S3.</em>
</p>

### Gambar L2.7.5

<p align="center">
  <img src="level-2-s3-iam/15_static-css-style-css-terbuka-langsung-dari.png" alt="static/css/style.css terbuka langsung dari S3." width="760"><br>
  <em>static/css/style.css terbuka langsung dari S3.</em>
</p>

### Gambar L2.7.6

<p align="center">
  <img src="level-2-s3-iam/16_media-profile-hero-jpg-terbuka-langsung-dari.png" alt="media/profile/hero.jpg terbuka langsung dari S3." width="760"><br>
  <em>media/profile/hero.jpg terbuka langsung dari S3.</em>
</p>

### Gambar L2.7.7

<p align="center">
  <img src="level-2-s3-iam/17_mengakses-bucket-menghasilkan-accessdenied.png" alt="Mengakses bucket menghasilkan AccessDenied." width="760"><br>
  <em>Mengakses bucket menghasilkan AccessDenied.</em>
</p>


## Level 3: RDS PostgreSQL

### Gambar L3.1.1

<p align="center">
  <img src="level-3-rds/01_security-group-db-sg-dengan-satu-inbound.png" alt="Security group pcm-kelompok-i-db-sg dengan satu inbound rule PostgreSQL port 5432." width="760"><br>
  <em>Security group pcm-kelompok-i-db-sg dengan satu inbound rule PostgreSQL port 5432.</em>
</p>

### Gambar L3.2.1

<p align="center">
  <img src="level-3-rds/02_db-subnet-group-db-subnets-berisi-private.png" alt="DB subnet group pcm-kelompok-i-db-subnets berisi private-a dan private-b." width="760"><br>
  <em>DB subnet group pcm-kelompok-i-db-subnets berisi private-a dan private-b.</em>
</p>

### Gambar L3.3.1

<p align="center">
  <img src="level-3-rds/03_instance-db-berstatus-available.png" alt="Instance pcm-kelompok-i-db berstatus Available." width="760"><br>
  <em>Instance pcm-kelompok-i-db berstatus Available.</em>
</p>

### Gambar L3.3.2

<p align="center">
  <img src="level-3-rds/04_tab-connectivity-security-endpoint-database-pcm-dan.png" alt="Tab Connectivity & security, endpoint, database pcm, dan Internet access gateway Disabled." width="760"><br>
  <em>Tab Connectivity & security, endpoint, database pcm, dan Internet access gateway Disabled.</em>
</p>

### Gambar L3.3.3

<p align="center">
  <img src="level-3-rds/05_detail-jaringan-rds-vpc-subnet-group-security.png" alt="Detail jaringan RDS, VPC, subnet group, security group, dan Publicly accessible No." width="760"><br>
  <em>Detail jaringan RDS, VPC, subnet group, security group, dan Publicly accessible No.</em>
</p>

### Gambar L3.4.1

<p align="center">
  <img src="level-3-rds/06_koneksi-psql-dari-ec2-ke-rds-dengan.png" alt="Koneksi psql dari EC2 ke RDS dengan SSL (TLSv1.3), database masih kosong." width="760"><br>
  <em>Koneksi psql dari EC2 ke RDS dengan SSL (TLSv1.3), database masih kosong.</em>
</p>

### Gambar L3.6.1

<p align="center">
  <img src="level-3-rds/07_daftar-19-tabel-di-rds-setelah-migrate.png" alt="Daftar 19 tabel di RDS setelah migrate dan loaddata." width="760"><br>
  <em>Daftar 19 tabel di RDS setelah migrate dan loaddata.</em>
</p>

### Gambar L3.6.2

<p align="center">
  <img src="level-3-rds/08_query-di-rds-tiga-pesan-kontak-dan.png" alt="Query di RDS, tiga pesan kontak dan user admin ada di database." width="760"><br>
  <em>Query di RDS, tiga pesan kontak dan user admin ada di database.</em>
</p>

### Gambar L3.6.3

<p align="center">
  <img src="level-3-rds/09_status-migrasi-aplikasi-dan-service-pcm-yang.png" alt="Status migrasi aplikasi dan service pcm yang berjalan di atas PostgreSQL." width="760"><br>
  <em>Status migrasi aplikasi dan service pcm yang berjalan di atas PostgreSQL.</em>
</p>

### Gambar L3.7.1

<p align="center">
  <img src="level-3-rds/10_halaman-status-yang-menunjukkan-level-3-terdeteksi.png" alt="Halaman /status/ yang menunjukkan Level 3 terdeteksi dan database PostgreSQL di RDS." width="760"><br>
  <em>Halaman /status/ yang menunjukkan Level 3 terdeteksi dan database PostgreSQL di RDS.</em>
</p>

### Gambar L3.7.2

<p align="center">
  <img src="level-3-rds/11_daftar-pesan-masuk-di-admin-tiga-pesan.png" alt="Daftar Pesan masuk di admin, tiga pesan dari Level 1 masih ada." width="760"><br>
  <em>Daftar Pesan masuk di admin, tiga pesan dari Level 1 masih ada.</em>
</p>

### Gambar L3.7.3

<p align="center">
  <img src="level-3-rds/12_beranda-website-dengan-tagline-deployed-by-kelompok.png" alt="Beranda website dengan tagline Deployed by kelompok-i setelah pindah ke RDS." width="760"><br>
  <em>Beranda website dengan tagline Deployed by kelompok-i setelah pindah ke RDS.</em>
</p>

### Gambar L3.7.4

<p align="center">
  <img src="level-3-rds/13_dari-laptop-endpoint-rds-hanya-menghasilkan-ip.png" alt="Dari laptop, endpoint RDS hanya menghasilkan IP privat 10.0.12.34 dan koneksi port 5432 gagal." width="760"><br>
  <em>Dari laptop, endpoint RDS hanya menghasilkan IP privat 10.0.12.34 dan koneksi port 5432 gagal.</em>
</p>
