# 🧪 Students API Test Cases

This repository contains **manual QA test cases** for a sample REST API (created with [JSON Server](https://github.com/typicode/json-server)).  
The project demonstrates how to design and document test cases for CRUD operations on a `students` resource.

---

## 📂 Contents
- `students_api_testcases.xlsx` → Excel sheet with **12 detailed test cases**.
- Covers:
  - ✅ Functional testing  
  - ⚠️ Negative testing  
  - 🔐 Validation testing  
  - 📊 Response verification  

---

## 📑 Sample Test Case Table

| TCID   | Title/Description     | URI           | HTTP Request | Status Code | Validation                          |
|--------|----------------------|---------------|--------------|-------------|-------------------------------------|
| TC001  | Get all students     | `/students`   | GET          | 200         | Response should return ≥ 1 student  |
| TC004  | Add new student      | `/students`   | POST         | 201         | Student created with unique ID      |
| TC007  | Update student (partial) | `/students/3` | PATCH        | 200         | Only updated field should change    |

📄 Full list of test cases is available in the Excel file.

---

## 🛠️ Skills Demonstrated
- Test case design (functional + negative + edge scenarios)  
- REST API testing concepts  
- Request/response validation  
- Documentation in Excel (industry-style format)  

---
## 🧰 Postman Collection
The repository also includes a ready-to-use Postman collection:

- File: `Students_API_Test_Cases.postman_collection.json`
- Import it into Postman (File → Import → Upload file) to run all API test cases directly.
