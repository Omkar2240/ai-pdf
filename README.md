

# AI-PDF

**AI-PDF** is an intelligent document processing tool that uses artificial intelligence to analyze, extract, and interact with data from PDF files. It simplifies complex PDF handling workflows and provides a seamless user experience through a modern frontend and robust backend.

---

## 🚀 Features

* **AI-Powered Analysis**: Extract insights and structured data from PDF documents using cutting-edge AI models.
* **Customizable Workflows**: Tailor processing workflows to fit specific document requirements.
* **User-Friendly Interface**: Built with TailwindCSS for a clean and intuitive user experience.
* **FastAPI Backend**: High-performance API layer for document processing and AI inference.

---

## 📁 Repository Structure

```
AI-PDF-Chat/
├── backend/        # FastAPI-based backend
├── frontend/       # Next.js frontend using TailwindCSS
```

---

## 📦 Dependencies

### Backend

Dependencies listed in `requirements.txt`:

* `fastapi`
* `uvicorn`
* `crewai`
* `text`
* `python-dotenv`

### Frontend

Uses:

* TailwindCSS
* PostCSS
* React (likely via Next.js)

---

## 🛠️ Setup Instructions

### Prerequisites

* [Python](https://www.python.org/downloads/) (v3.8+)
* [Node.js](https://nodejs.org/) (v16+)
* `pip` and `npm` installed globally

---

### 🔧 Backend Setup

1. Navigate to the backend folder:

   ```bash
   cd AI-PDF-Chat/backend
   ```

2. Create and activate a virtual environment:

   ```bash
   python3 -m venv venv
   source venv/bin/activate     # On Windows: venv\Scripts\activate
   ```

3. Install the dependencies:

   ```bash
   pip install -r requirements.txt
   ```

4. Start the FastAPI server:

   ```bash
   uvicorn main:app --reload
   ```

---

### 🎨 Frontend Setup

1. Navigate to the frontend folder:

   ```bash
   cd AI-PDF-Chat/frontend
   ```

2. Install dependencies:

   ```bash
   npm install
   ```

3. Start the development server:

   ```bash
   npm run dev
   ```

---

## 🌐 Access the Application

* **Frontend**: [http://localhost:3000](http://localhost:3000)
* **Backend API**: [http://localhost:8000](http://localhost:8000)

---

