# Jarkom-Modul-4-2025-K21

Member :
1. Danuja Prasasta Bastu (5027241037)
2. Naila Cahyarani Idelia (5027241063)

<div align=center>

# Soal Modul 4

</div>

- [Topologi](#topologi)
- [VLSM](#VLSM)
- [CIDR](#CIDR)

## Topologi

Cisco Packet Tracer
<img width="1037" height="673" alt="Screenshot 2025-11-17 085017" src="https://github.com/user-attachments/assets/d251add0-91a3-4405-83d6-f5859ed28dc7" />

GNS3
<img width="1919" height="852" alt="image" src="https://github.com/user-attachments/assets/5512b3f3-53da-4657-8212-557353e9d33b" />

## VLSM

Step 1:
<img width="1048" height="603" alt="Screenshot 2025-11-18 010425" src="https://github.com/user-attachments/assets/0510225f-fd1e-407c-9b89-242dc26ce834" />
1. Kita menghitung subnet² yang ada di topologi
2. Setelah itu, kita menjumlahkan Host² yang telah kita subnetkan
3. Dari jumlah Host/IP itu awalnya kan masih acak, kita mengurutkan subnet berdasarkan kebutuhan IP dari terbesar ke terkecil
4. Lalu, kita bisa mengetahui prefix nya dengan rumus (2^n-2 ≥ Host/IP)
5. Jika sudah tau prefix nya kita juga bisa melihat Netmask dari contoh tabel

<img width="782" height="764" alt="image" src="https://github.com/user-attachments/assets/cb2403d4-3d0b-44a8-99e6-807e5dabaa76" />

Pohon VLSM
![WhatsApp Image 2025-11-18 at 09 13 56_13ebfabc](https://github.com/user-attachments/assets/7a627ce8-4950-48b2-b998-be69b7ba0a95)

Step 2:
<img width="808" height="579" alt="Screenshot 2025-11-18 073303" src="https://github.com/user-attachments/assets/c9d13a29-0a19-428e-a17b-b6411f181d58" />
1. Di VLSM kurang lebih sama isinya seperti Step 1 (Subnet & Netmask)
2. Untuk kelompok kami IP Prefix nya `10.74.0.0`. Jadi untuk menghitung bisa menggunakan pohon dari subnet besar memiliki NID 10.74.0.0 dengan netmask /22
3. Kita melakukan subnetting dengan menggunakan pohon tersebut untuk pembagian IP sesuai dengan kebutuhan masing-masing subnet yang ada.
