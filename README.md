# iChat- Hybrid session and token management chatbot


## Tech Stack
- **Frontend:** React, Axios
- **Backend:** Node.js, Express
- **Database:** MongoDB with Mongoose

## Project Steps and demo
### Working demo link- https://drive.google.com/file/d/1kSckxXu5b3o119jNVvxRoMdTdcVQyjPF/view?usp=drivesdk

### Steps to run 
```bash
### 1. Backend - open a terminal and run these

cd backend
npm install cookie-parser
npm run dev

### 2. Frontend - open another terminal and run these after backend, chatbot will start.

cd frontend
npm install js-cookie
npm start

## 3. folder structure
session-based-authentication-chatbot/
├── backend/
│   ├── models/
│   │   ├── Message.js         
│   │   └── Session.js         
│   ├── routes/
│   │   └── chat.js             
│   ├── server.js               
│   └── .env                    
│
├── frontend/
│   ├── src/
│   │   ├── components/ 
│   │   │   └── SessionList.jsx 
│   │   ├── App.jsx             
│   │   ├── index.js           
│   │   └── index.css          
│   └── package.json            
│ 
├── README.md                                   
