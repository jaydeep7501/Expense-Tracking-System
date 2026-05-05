<div align="center">

# 💸 Expense Management System

**A full-stack expense tracking app built with FastAPI + Streamlit**

![Python](https://img.shields.io/badge/Python-3.10+-3776AB?style=flat-square&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white)
![License](https://img.shields.io/badge/License-MIT-green?style=flat-square)
![Tests](https://img.shields.io/badge/Tests-Passing-brightgreen?style=flat-square)

</div>

---

## ✨ Features

| Feature | Description |
|---|---|
| ⚡ **FastAPI Backend** | High-performance async REST API with auto-generated docs at `/docs` |
| 📊 **Streamlit Frontend** | Interactive dashboard to track, filter, and visualize expenses |
| 🧪 **Test Coverage** | Frontend & backend tests included out of the box |
| 📁 **Clean Structure** | Modular layout designed for easy extension and contribution |

---

## 📁 Project Structure

```
💸 expense-management-system/
├── 📂 frontend/        # Streamlit application
├── 📂 backend/         # FastAPI server
├── 📂 tests/           # Unit & integration tests
├── 📄 requirements.txt
└── 📄 README.md
```

---

## 🚀 Quick Start

### 1. Clone the repository

```bash
git clone https://github.com/yourusername/expense-management-system.git
cd expense-management-system
```

### 2. Install dependencies

```bash
pip install -r requirements.txt
```

### 3. Start the FastAPI server

```bash
uvicorn server.server:app --reload
```

> API will be available at `http://localhost:8000`  
> Interactive docs at `http://localhost:8000/docs`

### 4. Launch the Streamlit app

```bash
streamlit run frontend/app.py
```

> App will be available at `http://localhost:8501`

---

## 🛠 Tech Stack

- **[Python 3.10+](https://python.org)** — Core language
- **[FastAPI](https://fastapi.tiangolo.com)** — REST API framework
- **[Streamlit](https://streamlit.io)** — Frontend dashboard
- **[Uvicorn](https://www.uvicorn.org)** — ASGI server
- **[Pytest](https://pytest.org)** — Testing framework

---

## 🧪 Running Tests

```bash
pytest tests/
```

---

## 🤝 Contributing

Pull requests are welcome! For major changes, please open an issue first to discuss what you'd like to change. Make sure to update tests as appropriate.

1. Fork the repo
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).

---

<div align="center">
Made with ❤️ — contributions welcome!
</div>
