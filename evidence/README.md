# Bukti Pengerjaan (Screenshot)

Folder ini berisi screenshot AWS Console dan terminal yang menjadi bukti tiap level. Penomoran gambar mengikuti laporan di [`docs/`](../docs/Laporan_Tugas1_Level1-3_Kelompok_I.pdf).

> **Catatan privasi:** ID akun AWS, alamat email pengirim pesan kontak, dan alamat IP publik anggota (rule SSH `/32`) sudah ditutup dengan kotak abu-abu sebelum dipublikasikan. Tidak ada password, secret key, atau access key pada gambar mana pun.


## Level 1: VPC dan EC2

| No | Gambar di laporan | Keterangan | File |
|---|---|---|---|
| 1 | Gambar 1.1 | Daftar lima IAM user milik anggota kelompok. | [`01_daftar-lima-iam-user-milik-anggota-kelompok.png`](level-1-vpc-ec2/01_daftar-lima-iam-user-milik-anggota-kelompok.png) |
| 2 | Gambar 2.1 | VPC pcm-kelompok-i-vpc berhasil dibuat. | [`02_vpc-vpc-berhasil-dibuat.png`](level-1-vpc-ec2/02_vpc-vpc-berhasil-dibuat.png) |
| 3 | Gambar 2.2 | Pengaturan VPC setelah DNS resolution dan DNS hostnames diaktifkan. | [`03_pengaturan-vpc-setelah-dns-resolution-dan-dns.png`](level-1-vpc-ec2/03_pengaturan-vpc-setelah-dns-resolution-dan-dns.png) |
| 4 | Gambar 2.3 | Daftar subnet, empat subnet pcm-kelompok-i dan tiga subnet bawaan VPC default. | [`04_daftar-subnet-empat-subnet-pcm-kelompok-i.png`](level-1-vpc-ec2/04_daftar-subnet-empat-subnet-pcm-kelompok-i.png) |
| 5 | Gambar 2.4 | Internet Gateway pcm-kelompok-i-igw dengan status Attached. | [`05_internet-gateway-igw-dengan-status-attached.png`](level-1-vpc-ec2/05_internet-gateway-igw-dengan-status-attached.png) |
| 6 | Gambar 2.5 | Route public-rt, 0.0.0.0/0 menuju igw dan 10.0.0.0/16 local. | [`06_route-public-rt-0-0-0-0.png`](level-1-vpc-ec2/06_route-public-rt-0-0-0-0.png) |
| 7 | Gambar 2.6 | Subnet association public-rt, yaitu public-a dan public-b. | [`07_subnet-association-public-rt-yaitu-public-a.png`](level-1-vpc-ec2/07_subnet-association-public-rt-yaitu-public-a.png) |
| 8 | Gambar 2.7 | Route private-rt, hanya route local 10.0.0.0/16. | [`08_route-private-rt-hanya-route-local-10.png`](level-1-vpc-ec2/08_route-private-rt-hanya-route-local-10.png) |
| 9 | Gambar 2.8 | Subnet association private-rt, yaitu private-a dan private-b. | [`09_subnet-association-private-rt-yaitu-private-a.png`](level-1-vpc-ec2/09_subnet-association-private-rt-yaitu-private-a.png) |
| 10 | Gambar 2.9 | Resource map VPC pcm-kelompok-i-vpc. | [`10_resource-map-vpc-vpc.png`](level-1-vpc-ec2/10_resource-map-vpc-vpc.png) |
| 11 | Gambar 3.1 | Inbound rules pcm-kelompok-i-web-sg (HTTP 80 dan SSH 22 dari IP anggota). | [`11_inbound-rules-web-sg-http-80-dan.png`](level-1-vpc-ec2/11_inbound-rules-web-sg-http-80-dan.png) |
| 12 | Gambar 4.1 | Elastic IP 16.78.139.41 berhasil di-associate ke instance EC2. | [`12_elastic-ip-16-78-139-41-berhasil.png`](level-1-vpc-ec2/12_elastic-ip-16-78-139-41-berhasil.png) |
| 13 | Gambar 4.2 | Detail instance pcm-kelompok-i-web, status Running dan 3/3 checks passed. | [`13_detail-instance-web-status-running-dan-3.png`](level-1-vpc-ec2/13_detail-instance-web-status-running-dan-3.png) |
| 14 | Gambar 5.1 | Berhasil masuk ke server lewat SSH, IP privat 10.0.1.67. | [`14_berhasil-masuk-ke-server-lewat-ssh-ip.png`](level-1-vpc-ec2/14_berhasil-masuk-ke-server-lewat-ssh-ip.png) |
| 15 | Gambar 6.1 | Hasil migrate, collectstatic, dan seed_pcm, lalu createsuperuser. | [`15_hasil-migrate-collectstatic-dan-seed-pcm-lalu.png`](level-1-vpc-ec2/15_hasil-migrate-collectstatic-dan-seed-pcm-lalu.png) |
| 16 | Gambar 7.1 | Status service pcm dan hasil curl ke Gunicorn, HTTP 200 OK. | [`16_status-service-pcm-dan-hasil-curl-ke.png`](level-1-vpc-ec2/16_status-service-pcm-dan-hasil-curl-ke.png) |
| 17 | Gambar 8.1 | Status service Nginx, active (running) dan enabled. | [`17_status-service-nginx-active-running-dan-enabled.png`](level-1-vpc-ec2/17_status-service-nginx-active-running-dan-enabled.png) |
| 18 | Gambar 9.1 | Beranda website PCM dengan tagline Deployed by kelompok-i di header. | [`18_beranda-website-pcm-dengan-tagline-deployed-by.png`](level-1-vpc-ec2/18_beranda-website-pcm-dengan-tagline-deployed-by.png) |
| 19 | Gambar 9.2 | Halaman /status/ yang menunjukkan Level 1 terdeteksi. | [`19_halaman-status-yang-menunjukkan-level-1-terdeteksi.png`](level-1-vpc-ec2/19_halaman-status-yang-menunjukkan-level-1-terdeteksi.png) |
| 20 | Gambar 9.3 | Tagline di header dan berita dengan gambar unggahan pada beranda. | [`20_tagline-di-header-dan-berita-dengan-gambar.png`](level-1-vpc-ec2/20_tagline-di-header-dan-berita-dengan-gambar.png) |

## Level 2: S3 dan IAM Role

| No | Gambar di laporan | Keterangan | File |
|---|---|---|---|
| 1 | Gambar L2.1.1 | Tab Permissions bucket, Block all public access dimatikan. | [`01_tab-permissions-bucket-block-all-public-access.png`](level-2-s3-iam/01_tab-permissions-bucket-block-all-public-access.png) |
| 2 | Gambar L2.1.2 | Object Ownership bucket owner enforced, ACL tidak dipakai. | [`02_object-ownership-bucket-owner-enforced-acl-tidak.png`](level-2-s3-iam/02_object-ownership-bucket-owner-enforced-acl-tidak.png) |
| 3 | Gambar L2.1.3 | Isi bucket, folder media/ dan static/. | [`03_isi-bucket-folder-media-dan-static.png`](level-2-s3-iam/03_isi-bucket-folder-media-dan-static.png) |
| 4 | Gambar L2.2.1 | Bucket policy, GetObject hanya untuk static/* dan media/*. | [`04_bucket-policy-getobject-hanya-untuk-static-dan.png`](level-2-s3-iam/04_bucket-policy-getobject-hanya-untuk-static-dan.png) |
| 5 | Gambar L2.3.1 | Trust relationship role, hanya ec2.amazonaws.com yang boleh assume role. | [`05_trust-relationship-role-hanya-ec2-amazonaws-com.png`](level-2-s3-iam/05_trust-relationship-role-hanya-ec2-amazonaws-com.png) |
| 6 | Gambar L2.3.2 | Inline policy pcm-s3-access (ListBucket dan ManageObjects). | [`06_inline-policy-pcm-s3-access-listbucket-dan.png`](level-2-s3-iam/06_inline-policy-pcm-s3-access-listbucket-dan.png) |
| 7 | Gambar L2.3.3 | Detail instance, IAM role pcm-kelompok-i-ec2-s3-role terpasang. | [`07_detail-instance-iam-role-ec2-s3-role.png`](level-2-s3-iam/07_detail-instance-iam-role-ec2-s3-role.png) |
| 8 | Gambar L2.4.1 | Hasil aws sts get-caller-identity, identitasnya assumed-role. | [`08_hasil-aws-sts-get-caller-identity-identitasnya.png`](level-2-s3-iam/08_hasil-aws-sts-get-caller-identity-identitasnya.png) |
| 9 | Gambar L2.5.1 | Hasil sync media, daftar objek di S3, dan collectstatic. | [`09_hasil-sync-media-daftar-objek-di-s3.png`](level-2-s3-iam/09_hasil-sync-media-daftar-objek-di-s3.png) |
| 10 | Gambar L2.6.1 | Konfigurasi S3 pada .env dan bukti tidak ada access key. | [`10_konfigurasi-s3-pada-env-dan-bukti-tidak.png`](level-2-s3-iam/10_konfigurasi-s3-pada-env-dan-bukti-tidak.png) |
| 11 | Gambar L2.7.1 | Halaman /status/ yang menunjukkan Level 2 terdeteksi dan S3Storage. | [`11_halaman-status-yang-menunjukkan-level-2-terdeteksi.png`](level-2-s3-iam/11_halaman-status-yang-menunjukkan-level-2-terdeteksi.png) |
| 12 | Gambar L2.7.2 | Page source beranda, CSS dan logo dimuat dari S3. | [`12_page-source-beranda-css-dan-logo-dimuat.png`](level-2-s3-iam/12_page-source-beranda-css-dan-logo-dimuat.png) |
| 13 | Gambar L2.7.3 | find tidak menemukan file di disk EC2, tetapi file ada di S3. | [`13_find-tidak-menemukan-file-di-disk-ec2.png`](level-2-s3-iam/13_find-tidak-menemukan-file-di-disk-ec2.png) |
| 14 | Gambar L2.7.4 | Objek uji-s3.png pada media/posts/2026/10/ di konsol S3. | [`14_objek-uji-s3-png-pada-media-posts.png`](level-2-s3-iam/14_objek-uji-s3-png-pada-media-posts.png) |
| 15 | Gambar L2.7.5 | static/css/style.css terbuka langsung dari S3. | [`15_static-css-style-css-terbuka-langsung-dari.png`](level-2-s3-iam/15_static-css-style-css-terbuka-langsung-dari.png) |
| 16 | Gambar L2.7.6 | media/profile/hero.jpg terbuka langsung dari S3. | [`16_media-profile-hero-jpg-terbuka-langsung-dari.png`](level-2-s3-iam/16_media-profile-hero-jpg-terbuka-langsung-dari.png) |
| 17 | Gambar L2.7.7 | Mengakses bucket menghasilkan AccessDenied. | [`17_mengakses-bucket-menghasilkan-accessdenied.png`](level-2-s3-iam/17_mengakses-bucket-menghasilkan-accessdenied.png) |

## Level 3: RDS PostgreSQL

| No | Gambar di laporan | Keterangan | File |
|---|---|---|---|
| 1 | Gambar L3.1.1 | Security group pcm-kelompok-i-db-sg dengan satu inbound rule PostgreSQL port 5432. | [`01_security-group-db-sg-dengan-satu-inbound.png`](level-3-rds/01_security-group-db-sg-dengan-satu-inbound.png) |
| 2 | Gambar L3.2.1 | DB subnet group pcm-kelompok-i-db-subnets berisi private-a dan private-b. | [`02_db-subnet-group-db-subnets-berisi-private.png`](level-3-rds/02_db-subnet-group-db-subnets-berisi-private.png) |
| 3 | Gambar L3.3.1 | Instance pcm-kelompok-i-db berstatus Available. | [`03_instance-db-berstatus-available.png`](level-3-rds/03_instance-db-berstatus-available.png) |
| 4 | Gambar L3.3.2 | Tab Connectivity & security, endpoint, database pcm, dan Internet access gateway Disabled. | [`04_tab-connectivity-security-endpoint-database-pcm-dan.png`](level-3-rds/04_tab-connectivity-security-endpoint-database-pcm-dan.png) |
| 5 | Gambar L3.3.3 | Detail jaringan RDS, VPC, subnet group, security group, dan Publicly accessible No. | [`05_detail-jaringan-rds-vpc-subnet-group-security.png`](level-3-rds/05_detail-jaringan-rds-vpc-subnet-group-security.png) |
| 6 | Gambar L3.4.1 | Koneksi psql dari EC2 ke RDS dengan SSL (TLSv1.3), database masih kosong. | [`06_koneksi-psql-dari-ec2-ke-rds-dengan.png`](level-3-rds/06_koneksi-psql-dari-ec2-ke-rds-dengan.png) |
| 7 | Gambar L3.6.1 | Daftar 19 tabel di RDS setelah migrate dan loaddata. | [`07_daftar-19-tabel-di-rds-setelah-migrate.png`](level-3-rds/07_daftar-19-tabel-di-rds-setelah-migrate.png) |
| 8 | Gambar L3.6.2 | Query di RDS, tiga pesan kontak dan user admin ada di database. | [`08_query-di-rds-tiga-pesan-kontak-dan.png`](level-3-rds/08_query-di-rds-tiga-pesan-kontak-dan.png) |
| 9 | Gambar L3.6.3 | Status migrasi aplikasi dan service pcm yang berjalan di atas PostgreSQL. | [`09_status-migrasi-aplikasi-dan-service-pcm-yang.png`](level-3-rds/09_status-migrasi-aplikasi-dan-service-pcm-yang.png) |
| 10 | Gambar L3.7.1 | Halaman /status/ yang menunjukkan Level 3 terdeteksi dan database PostgreSQL di RDS. | [`10_halaman-status-yang-menunjukkan-level-3-terdeteksi.png`](level-3-rds/10_halaman-status-yang-menunjukkan-level-3-terdeteksi.png) |
| 11 | Gambar L3.7.2 | Daftar Pesan masuk di admin, tiga pesan dari Level 1 masih ada. | [`11_daftar-pesan-masuk-di-admin-tiga-pesan.png`](level-3-rds/11_daftar-pesan-masuk-di-admin-tiga-pesan.png) |
| 12 | Gambar L3.7.3 | Beranda website dengan tagline Deployed by kelompok-i setelah pindah ke RDS. | [`12_beranda-website-dengan-tagline-deployed-by-kelompok.png`](level-3-rds/12_beranda-website-dengan-tagline-deployed-by-kelompok.png) |
| 13 | Gambar L3.7.4 | Dari laptop, endpoint RDS hanya menghasilkan IP privat 10.0.12.34 dan koneksi port 5432 gagal. | [`13_dari-laptop-endpoint-rds-hanya-menghasilkan-ip.png`](level-3-rds/13_dari-laptop-endpoint-rds-hanya-menghasilkan-ip.png) |
