# Memilih Port pada Host

Nmap mempunyai fitur untuk memilih Port apa saja yang ingin kita Scan, contohnya jika tadi kita Melakukan Port Scannning secara default pada scanme.nmap.org, maka ada banyak sekali port yang di Scan, tapi ada situasi ketika kita ingin Mengscan hanya salah satu port saja, misalkan kita ingin melakukan scanning hanya pada Port 80 HTTP

Perintahnya sebagai berikut: `nmap -p80 scanme.nmap.org`

Hasilnya sebagai berikut:

![Screenshot from 2022-11-30 20-05-59](https://user-images.githubusercontent.com/113501500/204804062-ba76a52e-820b-40b0-abc6-dede66100e52.png)

Disana terlihat hanya Port 80 saja yang di scan pada `scanme.nmap.org`, kalian juga bisa menggantinya dengan port yang lain misalnya port 80, 443, 21, dan sebagainya.

Nmap juga mempunyai beberapa format lainnya untuk melakukan Scanning, diantaranya:

1. Scanning Port lebih dari satu:

`nmap -p 25,123,53 <targethost>`

2. Scanning Port dengan mempunyai Rentang Port tertentu:

`nmap -p 1-500 <targethost>`

3. Scanning Port berdasarkan nama layanan:

`nmap -p http,smtp,ftp <targethost>`

4. Melakukan Scanning pada semua port (1-65535):

`nmap -p- <targethost>`

5. Scanning berdasarkan nama layanan dengan menggunakan wild-card:

`nmap -p http* <targethost>`

-----------------------------------------------------------------------------------------------------------------------------------------------------------
# OS
LINUX

------------------------------------------------------------
# Source:
- https://www.wildantechnoart.net/2017/05/cara-melakukan-port-scanning-dengan-Nmap.html

-------------------------------------------------------------
