# VLAN Configuration

# Bagian 1: Melihat Konfigurasi VLAN Default
Langkah 1: Menampilkan VLAN saat ini.

Pada S1, keluarkan perintah yang menampilkan semua VLAN yang dikonfigurasi. Secara default, semua antarmuka ditetapkan ke VLAN 1.
<img width="396" alt="2024-03-27_14-30" src="https://github.com/Mugnitk/VLAN_Configuration/assets/126656674/95c01146-64a8-4ea4-b23c-472647c717de">

Langkah 2: Verifikasi konektivitas antara PC pada jaringan yang sama.
Perhatikan bahwa setiap PC dapat melakukan ping ke PC lain yang berbagi subnet yang sama.

PC1 dapat melakukan ping ke PC4

PC2 dapat melakukan ping ke PC5

PC3 dapat melakukan ping ke PC6

# Bagian 2: Mengkonfigurasi VLAN
Langkah 1: Buat dan beri nama VLAN pada S1.

a. Buat VLAN berikut ini. Nama-nama tersebut peka terhadap huruf besar-kecil dan harus sesuai dengan kebutuhan:
<img width="960" alt="2024-03-21_11-49" src="https://github.com/Mugnitk/VLAN_Configuration/assets/126656674/73667547-2dae-4d25-be84-880c2fb47205">

Langkah 2: Verifikasi konfigurasi VLAN.

Perintah mana yang hanya akan menampilkan nama VLAN, status, dan port terkait pada sakelar?
<img width="493" alt="2024-03-27_14-54" src="https://github.com/Mugnitk/VLAN_Configuration/assets/126656674/3ac4efa3-2b33-49a0-8176-0e6493a7a543">

Langkah 3: Buat VLAN pada S2 dan S3.

Gunakan perintah yang sama dari Langkah 1 untuk membuat dan memberi nama VLAN yang sama pada S2 dan S3.
# s2
<img width="543" alt="2024-03-27_14-50" src="https://github.com/Mugnitk/VLAN_Configuration/assets/126656674/1dae1bc8-b5a7-4735-81b4-f8c38954e0dd">

# s3
<img width="483" alt="2024-03-27_14-56" src="https://github.com/Mugnitk/VLAN_Configuration/assets/126656674/79a8fe7f-b5bb-4247-ac96-0dd70d31a70d">

# Bagian 3: Menetapkan VLAN ke Port

Langkah 1: Menetapkan VLAN ke port aktif pada S2.
<img width="958" alt="2024-03-25_13-43" src="https://github.com/Mugnitk/VLAN_Configuration/assets/126656674/3dfb4e1a-6926-4503-9c4b-e7ccb9238067">

Langkah 2: Tetapkan VLAN ke port aktif pada S3.

S3 menggunakan penetapan port akses VLAN yang sama dengan S2. Konfigurasikan antarmuka sebagai port akses dan tetapkan VLAN sebagai berikut:

VLAN 10: FastEthernet 0/11

VLAN 20: FastEthernet 0/18

VLAN 30: FastEthernet 0/6
<img width="954" alt="2024-03-25_13-35" src="https://github.com/Mugnitk/VLAN_Configuration/assets/126656674/2b7b71ff-552c-469c-a908-156f0470b774">

Langkah 3: Tetapkan VLAN SUARA ke FastEthernet 0/11 pada S3.

<img width="532" alt="2024-03-27_15-14" src="https://github.com/Mugnitk/VLAN_Configuration/assets/126656674/a7b6d8d6-2cdb-400b-8baf-b722c7db042e">

Langkah 4: Verifikasi hilangnya konektivitas.

Sebelumnya, PC yang berbagi jaringan yang sama dapat melakukan ping satu sama lain dengan sukses.
<img width="542" alt="2024-03-27_15-18" src="https://github.com/Mugnitk/VLAN_Configuration/assets/126656674/1a3fa25f-7a84-425f-9807-72f5d3e4503a">
