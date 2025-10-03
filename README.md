<h1>📊 Excel Analyzer Platform- ExcelAnalyzer.ai</h1>

## 🧠 Project Overview
ExcelAnalyzer.ai Platform is a powerful web application that allows users to upload Excel files (`.xls` / `.xlsx`), analyze the data, and create interactive 2D & 3D charts.
Users can dynamically select **X and Y axes** from column headers, choose chart types, and **download graphs as PNG/PDF**.  
Each user's history of uploads and analyses is saved in a personal dashboard. An **Admin panel** enables monitoring of users and managing data usage. 
The platform additionally provides smart insights, summaries, or reports from the uploaded data.  

---

## 🚀 Key Features

📂 Excel Upload & Parsing – Supports `.xls` and `.xlsx` via SheetJS/xlsx, with intelligent multi-sheet parsing  
👤 User & Admin Authentication – Secure JWT-based login system  
📜 Upload History Dashboard – Track all past analyses and files  
📊 Data Mapping – Choose X/Y axes dynamically from Excel headers  
📈 2D & 3D Chart Generation – Bar, line, pie, scatter, and 3D column charts with interactive dashboards (hover, switch charts, filter data)  
🎨 Chart Customization – Adjust colors, labels, and dimensions  
📥 Downloadable Charts – Export graphs as PNG or compile into a single merged PDF  
✨ AI Integration (Optional) – Generate smart insights, summaries, and reports  
🔐 Secure Processing – Charts and data auto-expire after 12 hours for privacy  
🖥️ Responsive Modern UI – Built with TailwindCSS for a sleek, mobile-friendly experience  

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

## 📦 Installation & Setup


### 📥1. Clone the Repository

```bash
git clone https://github.com/Aditi-Ethiraj14/ExcelAnalyzer.ai.git
```

### 🖥2. Running Locally
To set up the project on your local machine, follow the steps below:

#### 🔹 Setup Frontend
```bash
cd frontend
npm install
npm run dev
```
# Runs at http://localhost:5173

#### 🔹 Setup Backend
```bash
cd backend
npm install
npm run dev
```
# Runs at http://localhost:5000

### 📱3. Access the Application:

Working link-

---

 ## 🔮 Future Improvements
- Natural Language → Chart (NLP-based visual query interface)
- Email report delivery with PDF attachments
- Scheduler for recurring uploads & auto-analytics
- AI assistant for business insights and suggestions  

