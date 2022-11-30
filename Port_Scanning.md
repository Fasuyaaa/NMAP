# Port Scanning

Suatu sistem Keamanan jaringan sangatlah dibutuhkan khususnya bagi Sysadmin untuk melindungi Data-data yang penting pada server, untuk itu dibutuhkan Tools yang bisa Mengexploritasi jaringan untuk mencari kelemahan pada suatu sistem.
Berikut bagaimana cara melakukan Port Scanning pada suatu Host (Website, Komputer, Ponsel atau Server), port Scanning ini dilakukan untuk memeriksa status port apakah terbuka, tertutup atau dilindungi Firewall.
Disarankan Nmap sudah terinstall pada Linux kalian dan disarankan untuk menggunakan Kali Linux atau sejenisnya karena sudah terinstall Tools yang lengkap untuk Hacking/Penetration Testing.

-----------------------------------------------------------------------------------------------------------------------------------------------------------

# Scanning

Disini Target Scanning kita yaitu pada Website scanme.nmap.org (Bisa diubah dengan Host lain misalnya URL dari suatu website atau IP Addsess dari suatu Host) Untuk melakukan Port Scanning.

Perintahnya seperti berikut ini:
```nmap scanme.nmap.org```

Maka akan menghasilkan seperti berikut ini:

![Screenshot from 2022-11-30 19-39-34](https://user-images.githubusercontent.com/113501500/204798633-71636d0c-5d5a-4d42-91ec-cb0c4be3d115.png)

Keterangan:

- Terdapat 4 port terbuka: ```Port 22 ssh, Port 80 http, Port 9929 nping-echo, Port 31337 Elite```

- Terdapat 1 port yang tidak dapat ditentukan statusnya: ```Port 25 smtp```

Jika terdapat Port yang terbuka, itu manandakan ada aplikasi yang dapat menerima paket data dari pengirim dan kita bisa Mengakses Port tersebut contohnya jika Port 80 Http terbuka/Open, itu menandakan kita bisa mengakses Website tersebut dan jika Port 80 Close atau Filtered, kita tidak bisa mengakses website tersebut atau jika Port 22 SSH terbuka, kita bisa mengakses Port tersebut untuk melakukan Remote Host atau mengendalikan komputer dari jarak jauh.

-----------------------------------------------------------------------------------------------------------------------------------------------------------
# OS
LINUX

------------------------------------------------------------
# Source:
- https://www.wildantechnoart.net/2017/05/cara-melakukan-port-scanning-dengan-Nmap.html

-------------------------------------------------------------
