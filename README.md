# 🚀 Full-Stack Angular Application with JSON Server

This project is a dynamic web application built using **Angular** for the frontend and **JSON Server** as a mock backend. It demonstrates a complete workflow for building, testing, and running a modern frontend project integrated with RESTful API capabilities for prototyping or development purposes.

---

## 📁 Folder Structure

```
src/
├── angular.json           # Angular CLI config
├── package.json           # Project metadata and dependencies
├── server.ts              # JSON Server and Express integration
├── prompts.md             # Notes, tasks, and planning prompts
├── tsconfig.json          # TypeScript config
├── tsconfig.app.json      # Angular-specific TypeScript config
├── tsconfig.spec.json     # Testing config
├── ...
```

---

## 🧰 Tech Stack

### 🔹 Frontend
- **Angular 17+**
- **TypeScript**
- **RxJS**
- **Bootstrap / CSS** (optional based on UI)

### 🔹 Backend
- **JSON Server** (Mock REST API)
- **Node.js** + **TypeScript**
- **CORS** and **Body-Parser** for middleware

---

## 📦 Installation & Setup

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/kvs-rishikesh/frontend-ecommerce.git
cd src
```

### 2️⃣ Install All Dependencies

```bash
npm install
```

---

## 💻 Running the App

### 🔹 Start Angular Frontend

```bash
ng serve
```

Visit: [http://localhost:4200](http://localhost:4200)

---

### 🔹 Start Backend (JSON Server)

```bash
json-server products.json
```

Visit: [http://localhost:3000](http://localhost:3000)

> Make sure `json-server` is installed globally:  
> `npm install -g json-server`

---

## ⚙️ Available Scripts

| Command               | Description                              |
|------------------------|------------------------------------------|
| `ng serve`             | Run Angular frontend                     |
| `json-server`          | Launch backend server (JSON Server)      |
| `ng build`             | Build app for production                 |
| `ng test`              | Run unit tests                           |
| `ng lint`              | Lint codebase                            |

---



## 📝 Developer Notes

- `prompts.md` includes brainstorming, pending tasks, and planning notes.
- Backend uses `json-server` to serve `products.json` or customized REST endpoints.
- You can create a json file and define collections like this:

```json
{
  "users": [
    { "id": 1, "name": "Satya", "email": "satya@example.com" }
  ],
  "posts": [
    { "id": 1, "title": "Hello Angular", "content": "Learning Angular rocks!" }
  ]
}
```

---


## 📌 Future Enhancements

- [ ] Connect to a real backend like Node.js + MongoDB or Firebase
- [ ] Implement JWT-based authentication
- [ ] Add routing guards and lazy loading
- [ ] Dockerize the app for containerized deployment

---

## 📬 Contact

For questions or collaboration:

> **Satya Rishikesh**  
> 📧 kvsrishikesh@hotmail.com 
> 💼 [LinkedIn](https://linkedin.com/in/hellosatyaa) | [GitHub](https://github.com/kvs-rishikesh)

---

## 🧠 Inspiration

This project is part of an initiative to master full-stack development and can evolve into a production-level application by replacing the mock server with real APIs.

---

## 🛠️ License

This project is open-source and available under the MIT License.
