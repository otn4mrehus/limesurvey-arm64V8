# Limesurvey-arm64V8
Limesurvey khusus dijalnkan sistem Armbian 64 Bit di STB Merk ZTE tipe B680H-v2.1

## Struktur Direktori File
```
+ Limesurvey
  - db/
  - app/
  - docker-compose.yaml
```
## Download source 
```
git clone https://github.com/otn4mrehus/limesurvey-arm64V8.git && \
cd limesurvey-arm64V8 && \
mkdir -p /root/PROJECT/db /root/PROJECT/app && \
chmod -R 777 /root/PROJECT/db  && \
chmod -R 777 /root/PROJECT/app

Note:
Direktori silakan sesuaikan sendiri :
/root/PROJECT/ atau ./
```
## Jalankan Docker Compose
#### Jalankan Project Stack Docker
```
docker-compose -p 'limesurvey' up --build -d
```
#### Running Project Stack Docker
###### <i>Pilih salah satu</i>
```
docker-compose -p 'limesurvey' stop | start | restart
```
#### Hapus Project Stack Docker
```
docker-compose -p 'limesurvey' down -v 
```
## Jalankan Limesurvey
```
127.0.0.1:8082/admin
```
## Administrator Limesurvey
```
Login: admin
Passw: admin123
```
