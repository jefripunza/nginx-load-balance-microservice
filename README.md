# NGINX Load Balance Microservice

**baca terlebih dahulu sampai bawah/selesai sebelum clone repo ini...**

---

## Folder Structure
```
load-balance
│
└─── api-gateway (this repo)
│       file project...
│
└─── a-service
│       file project...
│
└─── assets (create/generate)
│       data.json
│       more file...
│
└─── b-service
│       file project...
│
└─── logs (generate)
│       all log file... (generate)
│
└─── web-service
        more file...
```
![Folder Schemas (explorer)](git_assets/folder_schemas.png)

---

## How to Use
1. install Docker Desktop or Docker (whatever)
2. create container :
```bash
docker-compose up -d
```
3. create all container microservices testing (link bellow)

---

## Clone All Microservices Testing
- [Web Service](https://github.com/jefripunza/example-web-service.git)
- [A Service](https://github.com/jefripunza/example-a-service.git)
- [B Service](https://github.com/jefripunza/example-b-service.git)
![Schemas Routing (diagram)](git_assets/schema.jpg)

---

## URL Testing (result)
- React JS [http://localhost](http://localhost)
  ![React JS (root)](git_assets/react-js-root.png)
  ![React JS (more)](git_assets/react-js-more.png)
- A Service [http://localhost/api/a](http://localhost/api/a)
  ![Schemas Routing (diagram)](git_assets/a-service.png)
- B Service [http://localhost/api/b](http://localhost/api/b)
  ![Schemas Routing (diagram)](git_assets/b-service.png)
- Assets Folder [http://localhost/assets/data.json](http://localhost/assets/data.json)
  ![Assets Example](git_assets/assets.png)

Note :
- clone semua ini didalam 1 folder (seperti di **Folder Structure**)
- buatlah sebuah file **data.json** lalu isi dengan data json (whatever)
- masukan beberapa file di folder **assets** dan coba buka lewat endpoint **assets** seperti **data.json**
