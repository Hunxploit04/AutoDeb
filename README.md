### AutoDeb
adalah tools yang di rancang untuk memberikan kemudahan dalam melakukan konfigurasi - konfigurasi server pada debian, terkhusus anak TKJ hehe 😄

<img src="https://github.com/Hunxploit04/DebAuto/blob/main/autodeb.png">

### Instalasi di linux (deb)
```
apt-get install git
```
lalu git repository ini : 
```
git clone https://github.com/Hunxploit04/AutoDeb.git
```
atau lebih mudahnya download zip nya **[ khusus windows ]**

jika sudah, kita berikan aksess tools ini :
```
chmod +x autodeb.sh
./autodeb.sh
```
lalu untuk jalankannya ketik A atau langsung enter : lalu ikuti rules yang ada di dalam tools ini 

**silahkan di coba 😄**

### Untuk Webmail atau Mail Server
disini saya memakai ranloop, untuk kalian yang belum ada bisa download langsung di web resminya : https://www.rainloop.net/repository/webmail/rainloop-latest.zip 

nah setelah terdownload kalian estrak dan rename namanya jadi **[ rainloop ]** lalu pindahkan file tersebut ke ```/var/www``` untuk perintah memindahkannya ketik ```mv rainloop /var/www/``` dan berikan aksess nya ```chmod 777 /var/www/rainloop -R```
