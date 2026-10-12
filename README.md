# 📁 DocVault

**Never miss a document expiry again.**
DocVault is a web application where you can **store, organize, and save your important documents** — and get **notified before they expire**, so you can reissue them on time.



## 💡 Problem It Solves

Documents like IDs, licenses, insurance papers, certificates, and agreements all have expiry dates — and it's easy to forget them until it's too late.

DocVault keeps all your documents in one place, tracks their expiry dates, and reminds you when it's time to **reissue or renew** them.

---

## ✨ Features

- 📤 **Upload & save** documents (PDF, images, Word files, etc.)
- 🗂️ **Organize** documents into categories / folders
- ⏰ **Expiry tracking** — add an expiry date to every document
- 🔔 **Expiry alerts** — get notified when a document is about to expire or has expired
- 🚦 **Status labels** — Valid, Expiring Soon, Expired
- 🔄 **Reissue tracking** — mark a document as reissued and update its new expiry date
- 🔍 Search and filter documents
- 👁️ Preview and download documents
- 🗑️ Edit or delete stored documents
- 🔐 Secure user login
- 📱 Responsive design

---

## 🔄 How It Works

1. **Upload** a document and enter its expiry date.
2. DocVault **stores and organizes** it under the category you choose.
3. As the date approaches, the app shows an **"Expiring Soon"** alert.
4. Once expired (or before), you **reissue** the document.
5. **Upload the new copy** and update the expiry date — and the cycle continues.

---

## 🛠️ Tech Stack

| Layer      | Technology                           |
|------------|--------------------------------------|
| Frontend   | HTML, CSS, JavaScript, React.js      |
| Backend    | Node.js (Express.js)                 |
| Database   | MySQL                                |
| Other      |  JWT , multer                        |

---


## ✅ Prerequisites

- [Node.js](https://nodejs.org/) (v16 or higher)
- npm (comes with Node.js)
- Git
- sql databse 

---

## 🚀 Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/<your-username>/docvault.git
cd docvault
```

### 2. Set up the backend

```bash
cd server
npm install
```

Create a `.env` file inside the `server` folder:

```env
PORT=5000
DATABASE_URL=your_database_connection_string
JWT_SECRET=your_secret_key
```

Start the server:

```bash
npm start
```

The backend runs at `http://localhost:5000`.

### 3. Set up the frontend

Open a new terminal:

```bash
cd client
npm install
npm start
```

The frontend runs at `http://localhost:3000`.

---

## 🔌 API Endpoints

> Replace with your real routes.

| Method | Endpoint                      | Description                          |
|--------|-------------------------------|--------------------------------------|
| POST   | `/api/auth/register`          | Register a new user                  |
| POST   | `/api/auth/login`             | Log in a user                        |
| GET    | `/api/documents`              | Get all documents                    |
| POST   | `/api/documents`              | Upload a document with expiry date   |
| GET    | `/api/documents/:id`          | Get a single document                |
| PUT    | `/api/documents/:id`          | Update a document / reissue details  |
| DELETE | `/api/documents/:id`          | Delete a document                    |
| GET    | `/api/documents/expiring`     | Get documents expiring soon          |

---



## 🔮 Future Improvements

- Email / SMS / push notification reminders
- Auto-reminders at 30, 15, and 7 days before expiry
- Document sharing with family or team members
- OCR to auto-detect expiry dates from uploaded files

---

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch: `git checkout -b feature/your-feature`
3. Commit your changes: `git commit -m "Add your feature"`
4. Push to the branch: `git push origin feature/your-feature`
5. Open a Pull Request

---



## 👤 Author

**Shivam chavhan**




⭐ If you found this project useful, consider giving it a star!
