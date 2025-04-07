# 🧠 AlgoSimulator

**AlgoSimulator** is a full-stack web application for visualizing and simulating classic algorithms (sorting, graph traversal, etc.).  
The project is built with **Angular Standalone** for the frontend, **Golang (Gin)** for the backend, and **MongoDB** as the database.

---

## 📦 Technologies Used

| Layer      | Stack                      |
|------------|----------------------------|
| Frontend   | Angular Standalone, Angular Material |
| Backend    | Go (Gin Framework)         |
| Database   | MongoDB                    |

---

## 🗂️ Project Structure

```
algo-simulator/
├── backend/          # Golang API
│   ├── controllers/
│   ├── routes/
│   ├── services/
│   ├── models/
│   └── main.go
├── frontend/         # Angular Standalone App
│   └── algo-simulator/
│       ├── src/
│       └── angular.json
└── README.md
```

---

## 🚀 Getting Started

### ⚙️ Backend

```bash
cd backend
go mod tidy
go run main.go
```

### 🌐 Frontend

```bash
cd frontend/algo-simulator
npm install
ng serve
```

---

## 🎯 Features (Planned)

- ✅ Step-by-step visualization for sorting and graph algorithms  
- 🔄 Algorithm input customization  
- 📊 Time complexity comparisons  
- 🧠 Tooltips and explanations  
- 🗃️ Simulation history (MongoDB)  
- 🛡️ User accounts (Future)

---

## 🧪 Example Algorithms

- Bubble Sort
- Quick Sort
- Merge Sort
- Dijkstra's Algorithm
- A* Pathfinding
- BFS / DFS

---

## 📚 License

MIT License

---

## 👨‍💻 Author

Developed by [Raphael Estrella](https://github.com/EstrellaRaphael) 🚀  
