## Contoh Pengujian Postman

### Create Category
POST /categories
Body (JSON):
{
  "name": "Elektronik"
}

### Create Product
POST /products
{
  "category_id": 1,
  "name": "Laptop",
  "price": 15000000
}

Ambil screenshot setiap request berhasil (status 200).
