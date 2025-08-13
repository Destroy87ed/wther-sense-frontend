
---

### **`backend/README.md`**
```md
# Weather Sense - Backend

The backend of this project is built using **Express.js** and **Node.js**, acting as the bridge between the React frontend and the MongoDB database.

It manages:
- User authentication (register/login)
- Weather API data retrieval
- Database storage and queries

The MongoDB database is hosted on **MongoDB Atlas** and contains:
- **Active Users**: Currently logged-in users
- **Registered Users**: User details including name, email, password, and city

---

## Installation

```bash
git clone https://github.com/kunaal-gupta/WeatherSense.git
cd server
npm install
