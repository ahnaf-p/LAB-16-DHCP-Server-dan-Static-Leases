# LAB-16-DHCP-Server-dan-Static-Leases
Kamis 14 Agustus 2025

# DHCP Server dan Static Leases  
![logy]()
  Konfigurasi DHCP Server dan Static Leases  
 1. Setting DHCP Client agar Mikrotik terhubung ke intrnet melalui ether1 yang terhubung ke ISP.  
![ada](client.PNG)  
  2. Buat IP static untuk ether2  
![dasd](addresses.PNG)  
  3. Setup DHCP Server untuk membagikan IP ke client secara otomatis.  
![wasd](server.PNG)  
![setup](beress.PNG)  
  5. Setting DNS, masukan DNS google.  
![qwerty](dns.PNG)  
  6. Tambahkan Firewall NAT agar client bisa mengakses ke internet.  
![sdfs](api.PNG)  
  7. Pindah ke PC Client dan jangan lupa untuk setting IP nya jadi obtain auto.  
  8. Setelah selesai, sekarang cek ke PC client, apahak sudah dapat IP.  
     PC1:  
     ![dkaiojasd](CLIENTTT.PNG)  
     PC2:   
     ![fnsushe](ahnafcb.PNG)  
  9. Jika PC Client sudah mendapat IP, buka kembali Winboxnya  
  10. Buka **IP > DHCP SERVER > Lease**  
  ![static]()  
  11. Pilih MAC Client yang akan di static kan.  
  ![statics]()  
  12. Klik **Make static** agar perangkat itu punya IP yang tetap tanpa perlu setting IP manual.  
  13. Sekarang client yang sudah di config menjadi static lease akan mendapatkan IP yang sama terus walau mengunakan auto obtain.  

# Kesimpulan  
  DHCP Server membuat pengelolaan IP di jaringan jadi otomatis dan mudah, sementara Static Leases memberi kontrol lebih dengan memastikan perangkat penting punya IP tetap tanpa perlu setting manual di perangkat tersebut.  

