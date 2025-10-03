<h1>📊 Excel Analyzer Platform- ExcelAnalyzer.ai</h1>

## 🧠 Project Overview
ExcelAnalyzer.ai Platform is a powerful web application that allows users to upload Excel files (`.xls` / `.xlsx`), analyze the data, and create interactive 2D & 3D charts.
Users can dynamically select **X and Y axes** from column headers, choose chart types, and **download graphs as PNG/PDF**.  
Each user's history of uploads and analyses is saved in a personal dashboard. An **Admin panel** enables monitoring of users and managing data usage. 
The platform additionally provides smart insights, summaries, or reports from the uploaded data.  

---

## 🚀 Key Features

- Excel Upload & Parsing: Supports `.xls` and `.xlsx` via SheetJS/xlsx, with intelligent multi-sheet parsing.  
- User & Admin Authentication: Secure JWT-based login system.  
- Upload History Dashboard: Track all past analyses and files.  
- Data Mapping: Choose X/Y axes dynamically from Excel headers.  
- 2D & 3D Chart Generation: Bar, line, pie, scatter, and 3D column charts with interactive dashboards (hover, switch charts, filter data).  
- Chart Customization: Adjust colors, labels, and dimensions.  
- Downloadable Charts: Export graphs as PNG or compile into a single merged PDF.  
- AI Integration (Optional): Generate smart insights, summaries, and reports.  
- Secure Processing: Charts and data auto-expire after 12 hours for privacy.  
- Responsive Modern UI: Built with TailwindCSS for a sleek, mobile-friendly experience.  

---

## 🖼 Working

<div align="center">
  <img src="https://github.com/user-attachments/assets/9de558c0-c7b4-416b-b448-400bc7a5541c", width="48%">
  <img src="https://github.com/user-attachments/assets/3ab9cd86-a8d4-43f6-895c-d01ba28d63af" width="48%">
</div>

<div align="center">
  <img src="https://github.com/user-attachments/assets/f109ff82-95dd-47ac-85bc-b06377563372" width="48%">
  <img src="https://github.com/user-attachments/assets/d58582b5-6181-456c-acd3-0c9f3dc1c887" width="48%">
</div>

---

## 🛠 Tech Stack

### 🎨 Frontend
- React.js  
- Redux Toolkit  
- Tailwind CSS  
- Chart.js  
- Three.js  

### ⚙ Backend
- Node.js  
- Express.js  
- MongoDB  
- Multer (file upload)  
- SheetJS / xlsx  

### 🧰 Tools
- Postman (API testing)  
- Git & GitHub (version control)

---

## 🚀 Installation & Setup

### **1. Clone the Repository**
```bash
git clone https://github.com/Aditi-Ethiraj14/ExcelAnalyzer.ai.git
cd ExcelAnalyzer.ai
```

### **2. Configure Environment Variables**
Create a .env file inside the backend folder and add the following:
```bash
MONGO_URL=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
PORT=5000
```

### **3. Backend Setup**
```bash
cd backend
npm install
npm run dev
```
Backend will now run at http://localhost:5000

### **Frontend Setup**
```bash
cd frontend
npm install
npm run dev
```
Frontend will now run at http://localhost:5173

### **5. Access the Application**

Working video-

---

 ## 🔮 Future Improvements
- Natural Language → Chart (NLP-based visual query interface)
- Email report delivery with PDF attachments
- Scheduler for recurring uploads & auto-analytics
- AI assistant for business insights and suggestions  

---

## 📜 License
This project is licensed under the **MIT License**.
