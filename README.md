API Automation Testing with Postman & Newman
Proyek automation testing untuk REST API menggunakan Postman Collection dan Newman CLI. Proyek ini mendemonstrasikan kemampuan testing API secara otomatis dengan berbagai skenario test case
📋 Deskripsi
Repository ini berisi automation testing untuk API yang mencakup functional testing, integration testing, dan regression testing. Testing dilakukan menggunakan Postman untuk development dan Newman untuk continuous integration.
🚀 Fitur

✅ Automated API testing dengan Postman Collection
✅ Test scripts untuk validasi response
✅ Environment variables untuk multiple environments
✅ HTML report generation

🛠️ Teknologi yang Digunakan

Postman - API development dan testing
Newman - Command line runner untuk Postman
Node.js - Runtime environment
Newman Reporter HTML - HTML report generator

📁 Struktur Folder
api-automation-testing/
├── collections/
│   └── API-Collection.postman_collection.json
├── environments/
│   ├── dev-env.json
├── reports/
│   └── (HTML reports akan tersimpan di sini)
└── README.md

🧪 Menjalankan Test
Menggunakan Postman

Import collection dari folder collections/
Import environment dari folder environments/
Pilih environment yang diinginkan
Jalankan collection

Menggunakan Newman (CLI)
Jalankan semua test:
bashnewman run collections/api-collection-reqres.json \ -e environments/dev_env.json

Jalan dengan HTML Report simple:
newman run collections/api-collection-reqres.json \ -e environments/dev_env.json \ -r html --reporter-html-export reports/test-report.html

Jalankan dengan HTML report extra:
bashnewman run collections/api-collection-reqres.json \ -e environments/dev_env.json \ -r htmlextra --reporter-htmlextra-export reports/test-report.html


📊 Test Coverage
Proyek ini mencakup testing untuk:

Authentication & Authorization

Login
Token validation

CRUD Operations

Create (POST)
Read (GET)
Update (PUT/PATCH)
Delete (DELETE)


Validation Testing
Status code validation
Response schema validation
Error handling
