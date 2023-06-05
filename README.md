
# Simple-crud-with-prisma-node-backend

silahkan di clone jika ingin mencobanya ini merupakan proyek simpel yang saya buat belajar prisma dan menggunakan front end react 




## Instalasi

jalankan terminal

```bash
  npm install 
  npm init 
  npx prisma generate
  node index
```

buat databasenya 
seperti di prisma


## API Reference

#### Get all items

```http
  GET http://localhost:5000/products/
```

| Parameter | Type     | Description                |
| :-------- | :------- | :------------------------- |
|  | `string` | **Required**. Your API key |

#### Get item

```http
  GET http://localhost:5000/products/id
```

| Parameter | Type     | Description                       |
| :-------- | :------- | :-------------------------------- |
| `id`      | `string` | **Required**. Id of item to fetch |

#### Tambah item

```http
  POST http://localhost:5000/products
```
Body raw json

{
    "name":"Product 34",
"price":565656
}

#### Update item

```http
  PATCH hhttp://localhost:5000/products/id
```
Body raw json

{
    "name":"Product 3 Update",
"price":565656343
}
#### Delete Item

```http
  DELETE http://localhost:5000/products/id
```

| Parameter | Type     | Description                       |
| :-------- | :------- | :-------------------------------- |
| `id`      | `string` | **Required**. Id of item to fetch |



Silahkan Clone Front end jika ingin menggunakan front end di 
https://github.com/BharaAyongPM/Simple-crud-with-react


## 🚀 About Me
I am a motivated and dedicated professional with experience in web development and computer networking. Currently, I am a sixth-semester student pursuing a degree in Computer Science at Universitas Bina Sarana Informatika. Throughout my academic journey, I have honed my skills and knowledge in cloud computing, particularly through my participation in the Cloud Computing Learning Path at Bangkit Academy, led by Google, Tokopedia, Gojek, and Traveloka.



