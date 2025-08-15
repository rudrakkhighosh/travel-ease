
# Travel-Ease: A Tourism Website

**Travel-Ease** is a modern, responsive tourism website designed to help users explore popular tourist destinations and share reviews for various locations.

## ✨ Features
- Homepage – Overview with featured destinations and popular tourist spots.
- User Authentication – Register and log in securely.
- Tourism Destinations – Browse tourist destinations and itineraries.
- Review System – Logged-in users can leave reviews for their favorite places.
- Responsive Design– Works seamlessly on both desktop and mobile devices.

## 🛠 Tech Stack
- Frontend: HTML, CSS, JavaScript, React.js  
- Backend: Node.js, Express.js, MongoDB  
- Database:MongoDB (local or MongoDB Atlas for cloud)  

## 📦 Installation



### 1️⃣ Clone the Repository
```bash
git clone https://github.com/rudrakkhighosh/travel-ease.git
cd travel-ease
````

### 2️⃣ Install Dependencies

#### For the client (React frontend):

```bash
cd client
npm install
```

#### For the server (Node.js backend):

```bash
cd ../server
npm install
```

---

### 3️⃣ Run the Backend

```bash
cd server
set PORT=3000   # On Windows
# export PORT=3000  # On macOS/Linux
node index.js
```

---

### 4️⃣ Run the Frontend

Open a new terminal:

```bash
cd client
npm run dev
```

---

### 5️⃣ Access the Website

After running both the backend and frontend, open the link provided in the terminal (usually something like):

```
http://localhost:5173
```

---

## 📌 Notes

Make sure MongoDB is running locally, or configure MongoDB Atlas in your backend `.env` file.
Default backend port is **3000** (can be changed in `index.js` or environment variables).

