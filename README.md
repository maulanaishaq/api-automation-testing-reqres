# API Automation Testing with Postman & Newman

Proyek automation testing untuk REST API menggunakan **Postman Collection** dan **Newman CLI**.  
Repository ini mendemonstrasikan kemampuan **API testing otomatis** dengan berbagai skenario test case.

---

## 📋 Deskripsi
Repository ini berisi automation testing untuk API yang mencakup:
- Functional Testing  
- Integration Testing  
- Regression Testing  

Testing dikembangkan menggunakan **Postman** dan dijalankan secara otomatis menggunakan **Newman** untuk kebutuhan **CI/CD**.

---

## 🚀 Fitur
- ✅ Automated API testing dengan Postman Collection  
- ✅ Test scripts untuk validasi response  
- ✅ Environment variables untuk multiple environments  
- ✅ HTML report generation  

---

## 🛠️ Teknologi yang Digunakan
- **Postman** – API development & testing  
- **Newman** – Command-line runner untuk Postman  
- **Node.js** – Runtime environment  
- **Newman Reporter HTML / HTML Extra** – Report generator  

---

## 📁 Struktur Folder
```text
api-automation-testing/
├── collections/
│   └── API-Collection.postman_collection.json
├── environments/
│   └── dev-env.json
├── reports/
│   └── (HTML reports akan tersimpan di sini)
└── README.md
