## Description
Mini project todo list merupakan implementasi dari gRPC API dan protobuf untuk interaksi atntara client dan server, juga penggunaan bot telegram sebagai interface untuk berkomunikasi dengan user. terdapat fitur yang menjadikan user lebih nyaman dan mudah dengan adanya deskripsi petunjuk penggunaan bot ini. bot ini menggunakan database Firebase dan dibantu juga dengan botfather untuk APInya.

## Composition :
* Phyton
* JSON

## Feature :

* Add
* Read
* Update
* Delete
* List

---
## How to Start

Step 1 :


#### Install Python Libraries
```bash
pip install grpcio grpcio-tools google-auth google-auth-oauthlib google-auth-httplib2 firebase-admin python-telegram-bot
```

Step 2 :

#### Compile file proto

```bash
 python -m grpc_tools.protoc -I . --python_out=. --grpc_python_out=. todo.proto
```

Step 3 :

#### jalankan Server

```bash
 python .\server.py  
```
Step 4 :
#### jalankan Client 
(*Note : buka client di terminal lain)

```bash
 python .\client.py  
```



## Documentation 

## Screenshots

![App Screenshot](https://i.ibb.co/LpTTFx8/Screenshot-34.png)
![App Screenshot](https://i.ibb.co/0nxqb1G/Screenshot-35.png)
