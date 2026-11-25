# Evidence Gallery

🇮🇩 **Versi Bahasa Indonesia:** [README.md](README.md) · [← Back to the main README](../README.en.md)

All AWS Console and terminal screenshots used as evidence for each level, displayed inline. Numbering follows the [report](../docs/Laporan_Tugas1_Level1-3_Kelompok_I.pdf), which is written in Indonesian. The step-by-step write-ups (also in Indonesian) are in [Level 1](../docs/level-1-vpc-ec2.md), [Level 2](../docs/level-2-s3-iam.md), and [Level 3](../docs/level-3-rds.md).

> **Privacy note:** AWS account IDs, the email addresses of contact form senders, and members' public IPs (the `/32` SSH rules) are covered with grey boxes. No passwords, secret keys, or access keys appear in any image.


## Level 1: VPC and EC2

### Figure 1.1

<p align="center">
  <img src="level-1-vpc-ec2/01_daftar-lima-iam-user-milik-anggota-kelompok.png" alt="The five IAM users of the group members." width="760"><br>
  <em>The five IAM users of the group members.</em>
</p>

### Figure 2.1

<p align="center">
  <img src="level-1-vpc-ec2/02_vpc-vpc-berhasil-dibuat.png" alt="VPC pcm-kelompok-i-vpc created successfully." width="760"><br>
  <em>VPC pcm-kelompok-i-vpc created successfully.</em>
</p>

### Figure 2.2

<p align="center">
  <img src="level-1-vpc-ec2/03_pengaturan-vpc-setelah-dns-resolution-dan-dns.png" alt="VPC settings after enabling DNS resolution and DNS hostnames." width="760"><br>
  <em>VPC settings after enabling DNS resolution and DNS hostnames.</em>
</p>

### Figure 2.3

<p align="center">
  <img src="level-1-vpc-ec2/04_daftar-subnet-empat-subnet-pcm-kelompok-i.png" alt="Subnet list: four pcm-kelompok-i subnets and the three default VPC subnets." width="760"><br>
  <em>Subnet list: four pcm-kelompok-i subnets and the three default VPC subnets.</em>
</p>

### Figure 2.4

<p align="center">
  <img src="level-1-vpc-ec2/05_internet-gateway-igw-dengan-status-attached.png" alt="Internet Gateway pcm-kelompok-i-igw with status Attached." width="760"><br>
  <em>Internet Gateway pcm-kelompok-i-igw with status Attached.</em>
</p>

### Figure 2.5

<p align="center">
  <img src="level-1-vpc-ec2/06_route-public-rt-0-0-0-0.png" alt="public-rt routes: 0.0.0.0/0 to the IGW and 10.0.0.0/16 local." width="760"><br>
  <em>public-rt routes: 0.0.0.0/0 to the IGW and 10.0.0.0/16 local.</em>
</p>

### Figure 2.6

<p align="center">
  <img src="level-1-vpc-ec2/07_subnet-association-public-rt-yaitu-public-a.png" alt="public-rt subnet associations: public-a and public-b." width="760"><br>
  <em>public-rt subnet associations: public-a and public-b.</em>
</p>

### Figure 2.7

<p align="center">
  <img src="level-1-vpc-ec2/08_route-private-rt-hanya-route-local-10.png" alt="private-rt routes: only the local route 10.0.0.0/16." width="760"><br>
  <em>private-rt routes: only the local route 10.0.0.0/16.</em>
</p>

### Figure 2.8

<p align="center">
  <img src="level-1-vpc-ec2/09_subnet-association-private-rt-yaitu-private-a.png" alt="private-rt subnet associations: private-a and private-b." width="760"><br>
  <em>private-rt subnet associations: private-a and private-b.</em>
</p>

### Figure 2.9

<p align="center">
  <img src="level-1-vpc-ec2/10_resource-map-vpc-vpc.png" alt="Resource map of VPC pcm-kelompok-i-vpc." width="760"><br>
  <em>Resource map of VPC pcm-kelompok-i-vpc.</em>
</p>

### Figure 3.1

<p align="center">
  <img src="level-1-vpc-ec2/11_inbound-rules-web-sg-http-80-dan.png" alt="Inbound rules of pcm-kelompok-i-web-sg (HTTP 80 and SSH 22 from member IPs)." width="760"><br>
  <em>Inbound rules of pcm-kelompok-i-web-sg (HTTP 80 and SSH 22 from member IPs).</em>
</p>

### Figure 4.1

<p align="center">
  <img src="level-1-vpc-ec2/12_elastic-ip-16-78-139-41-berhasil.png" alt="Elastic IP associated with the EC2 instance." width="760"><br>
  <em>Elastic IP associated with the EC2 instance.</em>
</p>

### Figure 4.2

<p align="center">
  <img src="level-1-vpc-ec2/13_detail-instance-web-status-running-dan-3.png" alt="Instance pcm-kelompok-i-web, Running with 3/3 checks passed." width="760"><br>
  <em>Instance pcm-kelompok-i-web, Running with 3/3 checks passed.</em>
</p>

### Figure 5.1

<p align="center">
  <img src="level-1-vpc-ec2/14_berhasil-masuk-ke-server-lewat-ssh-ip.png" alt="Logged in to the server over SSH, private IP 10.0.1.67." width="760"><br>
  <em>Logged in to the server over SSH, private IP 10.0.1.67.</em>
</p>

### Figure 6.1

<p align="center">
  <img src="level-1-vpc-ec2/15_hasil-migrate-collectstatic-dan-seed-pcm-lalu.png" alt="Output of migrate, collectstatic, seed_pcm, then createsuperuser." width="760"><br>
  <em>Output of migrate, collectstatic, seed_pcm, then createsuperuser.</em>
</p>

### Figure 7.1

<p align="center">
  <img src="level-1-vpc-ec2/16_status-service-pcm-dan-hasil-curl-ke.png" alt="Status of the pcm service and a curl to Gunicorn returning HTTP 200 OK." width="760"><br>
  <em>Status of the pcm service and a curl to Gunicorn returning HTTP 200 OK.</em>
</p>

### Figure 8.1

<p align="center">
  <img src="level-1-vpc-ec2/17_status-service-nginx-active-running-dan-enabled.png" alt="Nginx service status, active (running) and enabled." width="760"><br>
  <em>Nginx service status, active (running) and enabled.</em>
</p>

### Figure 9.1

<p align="center">
  <img src="level-1-vpc-ec2/18_beranda-website-pcm-dengan-tagline-deployed-by.png" alt="The PCM homepage with the tagline "Deployed by kelompok-i" in the header." width="760"><br>
  <em>The PCM homepage with the tagline "Deployed by kelompok-i" in the header.</em>
</p>

### Figure 9.2

<p align="center">
  <img src="level-1-vpc-ec2/19_halaman-status-yang-menunjukkan-level-1-terdeteksi.png" alt="The /status/ page showing "Level 1 terdeteksi" (Level 1 detected)." width="760"><br>
  <em>The /status/ page showing "Level 1 terdeteksi" (Level 1 detected).</em>
</p>

### Figure 9.3

<p align="center">
  <img src="level-1-vpc-ec2/20_tagline-di-header-dan-berita-dengan-gambar.png" alt="Header tagline and a news item with an uploaded image on the homepage." width="760"><br>
  <em>Header tagline and a news item with an uploaded image on the homepage.</em>
</p>


## Level 2: S3 and IAM Role

### Figure L2.1.1

<p align="center">
  <img src="level-2-s3-iam/01_tab-permissions-bucket-block-all-public-access.png" alt="Bucket Permissions tab with Block all public access turned off." width="760"><br>
  <em>Bucket Permissions tab with Block all public access turned off.</em>
</p>

### Figure L2.1.2

<p align="center">
  <img src="level-2-s3-iam/02_object-ownership-bucket-owner-enforced-acl-tidak.png" alt="Object Ownership set to bucket owner enforced, ACLs not used." width="760"><br>
  <em>Object Ownership set to bucket owner enforced, ACLs not used.</em>
</p>

### Figure L2.1.3

<p align="center">
  <img src="level-2-s3-iam/03_isi-bucket-folder-media-dan-static.png" alt="Bucket contents: the media/ and static/ folders." width="760"><br>
  <em>Bucket contents: the media/ and static/ folders.</em>
</p>

### Figure L2.2.1

<p align="center">
  <img src="level-2-s3-iam/04_bucket-policy-getobject-hanya-untuk-static-dan.png" alt="Bucket policy granting GetObject only on static/* and media/*." width="760"><br>
  <em>Bucket policy granting GetObject only on static/* and media/*.</em>
</p>

### Figure L2.3.1

<p align="center">
  <img src="level-2-s3-iam/05_trust-relationship-role-hanya-ec2-amazonaws-com.png" alt="Role trust relationship: only ec2.amazonaws.com may assume the role." width="760"><br>
  <em>Role trust relationship: only ec2.amazonaws.com may assume the role.</em>
</p>

### Figure L2.3.2

<p align="center">
  <img src="level-2-s3-iam/06_inline-policy-pcm-s3-access-listbucket-dan.png" alt="Inline policy pcm-s3-access (ListBucket and ManageObjects)." width="760"><br>
  <em>Inline policy pcm-s3-access (ListBucket and ManageObjects).</em>
</p>

### Figure L2.3.3

<p align="center">
  <img src="level-2-s3-iam/07_detail-instance-iam-role-ec2-s3-role.png" alt="Instance details with the IAM role pcm-kelompok-i-ec2-s3-role attached." width="760"><br>
  <em>Instance details with the IAM role pcm-kelompok-i-ec2-s3-role attached.</em>
</p>

### Figure L2.4.1

<p align="center">
  <img src="level-2-s3-iam/08_hasil-aws-sts-get-caller-identity-identitasnya.png" alt="Output of aws sts get-caller-identity, showing an assumed-role identity." width="760"><br>
  <em>Output of aws sts get-caller-identity, showing an assumed-role identity.</em>
</p>

### Figure L2.5.1

<p align="center">
  <img src="level-2-s3-iam/09_hasil-sync-media-daftar-objek-di-s3.png" alt="Output of the media sync, the S3 object list, and collectstatic." width="760"><br>
  <em>Output of the media sync, the S3 object list, and collectstatic.</em>
</p>

### Figure L2.6.1

<p align="center">
  <img src="level-2-s3-iam/10_konfigurasi-s3-pada-env-dan-bukti-tidak.png" alt="S3 settings in .env and proof that no access key exists." width="760"><br>
  <em>S3 settings in .env and proof that no access key exists.</em>
</p>

### Figure L2.7.1

<p align="center">
  <img src="level-2-s3-iam/11_halaman-status-yang-menunjukkan-level-2-terdeteksi.png" alt="The /status/ page showing Level 2 detected and S3Storage." width="760"><br>
  <em>The /status/ page showing Level 2 detected and S3Storage.</em>
</p>

### Figure L2.7.2

<p align="center">
  <img src="level-2-s3-iam/12_page-source-beranda-css-dan-logo-dimuat.png" alt="Homepage page source: CSS and logo are loaded from S3." width="760"><br>
  <em>Homepage page source: CSS and logo are loaded from S3.</em>
</p>

### Figure L2.7.3

<p align="center">
  <img src="level-2-s3-iam/13_find-tidak-menemukan-file-di-disk-ec2.png" alt="find locates no file on the EC2 disk, while the file exists in S3." width="760"><br>
  <em>find locates no file on the EC2 disk, while the file exists in S3.</em>
</p>

### Figure L2.7.4

<p align="center">
  <img src="level-2-s3-iam/14_objek-uji-s3-png-pada-media-posts.png" alt="Object uji-s3.png under media/posts/2026/10/ in the S3 console." width="760"><br>
  <em>Object uji-s3.png under media/posts/2026/10/ in the S3 console.</em>
</p>

### Figure L2.7.5

<p align="center">
  <img src="level-2-s3-iam/15_static-css-style-css-terbuka-langsung-dari.png" alt="static/css/style.css opened directly from S3." width="760"><br>
  <em>static/css/style.css opened directly from S3.</em>
</p>

### Figure L2.7.6

<p align="center">
  <img src="level-2-s3-iam/16_media-profile-hero-jpg-terbuka-langsung-dari.png" alt="media/profile/hero.jpg opened directly from S3." width="760"><br>
  <em>media/profile/hero.jpg opened directly from S3.</em>
</p>

### Figure L2.7.7

<p align="center">
  <img src="level-2-s3-iam/17_mengakses-bucket-menghasilkan-accessdenied.png" alt="Opening the bucket root returns AccessDenied." width="760"><br>
  <em>Opening the bucket root returns AccessDenied.</em>
</p>


## Level 3: RDS PostgreSQL

### Figure L3.1.1

<p align="center">
  <img src="level-3-rds/01_security-group-db-sg-dengan-satu-inbound.png" alt="Security group pcm-kelompok-i-db-sg with a single PostgreSQL inbound rule on port 5432." width="760"><br>
  <em>Security group pcm-kelompok-i-db-sg with a single PostgreSQL inbound rule on port 5432.</em>
</p>

### Figure L3.2.1

<p align="center">
  <img src="level-3-rds/02_db-subnet-group-db-subnets-berisi-private.png" alt="DB subnet group pcm-kelompok-i-db-subnets containing private-a and private-b." width="760"><br>
  <em>DB subnet group pcm-kelompok-i-db-subnets containing private-a and private-b.</em>
</p>

### Figure L3.3.1

<p align="center">
  <img src="level-3-rds/03_instance-db-berstatus-available.png" alt="Instance pcm-kelompok-i-db with status Available." width="760"><br>
  <em>Instance pcm-kelompok-i-db with status Available.</em>
</p>

### Figure L3.3.2

<p align="center">
  <img src="level-3-rds/04_tab-connectivity-security-endpoint-database-pcm-dan.png" alt="Connectivity & security tab: endpoint, database pcm, and Internet access gateway Disabled." width="760"><br>
  <em>Connectivity & security tab: endpoint, database pcm, and Internet access gateway Disabled.</em>
</p>

### Figure L3.3.3

<p align="center">
  <img src="level-3-rds/05_detail-jaringan-rds-vpc-subnet-group-security.png" alt="RDS networking details: VPC, subnet group, security group, and Publicly accessible: No." width="760"><br>
  <em>RDS networking details: VPC, subnet group, security group, and Publicly accessible: No.</em>
</p>

### Figure L3.4.1

<p align="center">
  <img src="level-3-rds/06_koneksi-psql-dari-ec2-ke-rds-dengan.png" alt="psql connection from EC2 to RDS over SSL (TLSv1.3), database still empty." width="760"><br>
  <em>psql connection from EC2 to RDS over SSL (TLSv1.3), database still empty.</em>
</p>

### Figure L3.6.1

<p align="center">
  <img src="level-3-rds/07_daftar-19-tabel-di-rds-setelah-migrate.png" alt="The 19 tables in RDS after migrate and loaddata." width="760"><br>
  <em>The 19 tables in RDS after migrate and loaddata.</em>
</p>

### Figure L3.6.2

<p align="center">
  <img src="level-3-rds/08_query-di-rds-tiga-pesan-kontak-dan.png" alt="Queries on RDS: three contact messages and the admin user exist in the database." width="760"><br>
  <em>Queries on RDS: three contact messages and the admin user exist in the database.</em>
</p>

### Figure L3.6.3

<p align="center">
  <img src="level-3-rds/09_status-migrasi-aplikasi-dan-service-pcm-yang.png" alt="Migration status and the pcm service running on top of PostgreSQL." width="760"><br>
  <em>Migration status and the pcm service running on top of PostgreSQL.</em>
</p>

### Figure L3.7.1

<p align="center">
  <img src="level-3-rds/10_halaman-status-yang-menunjukkan-level-3-terdeteksi.png" alt="The /status/ page showing Level 3 detected and the PostgreSQL database on RDS." width="760"><br>
  <em>The /status/ page showing Level 3 detected and the PostgreSQL database on RDS.</em>
</p>

### Figure L3.7.2

<p align="center">
  <img src="level-3-rds/11_daftar-pesan-masuk-di-admin-tiga-pesan.png" alt="Admin inbox: the three messages from Level 1 are still there." width="760"><br>
  <em>Admin inbox: the three messages from Level 1 are still there.</em>
</p>

### Figure L3.7.3

<p align="center">
  <img src="level-3-rds/12_beranda-website-dengan-tagline-deployed-by-kelompok.png" alt="Homepage with the "Deployed by kelompok-i" tagline after the move to RDS." width="760"><br>
  <em>Homepage with the "Deployed by kelompok-i" tagline after the move to RDS.</em>
</p>

### Figure L3.7.4

<p align="center">
  <img src="level-3-rds/13_dari-laptop-endpoint-rds-hanya-menghasilkan-ip.png" alt="From a laptop, the RDS endpoint resolves only to the private IP 10.0.12.34 and port 5432 fails." width="760"><br>
  <em>From a laptop, the RDS endpoint resolves only to the private IP 10.0.12.34 and port 5432 fails.</em>
</p>
