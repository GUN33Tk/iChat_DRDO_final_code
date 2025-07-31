# iChat- Hybrid session and token management chatbot


## Tech Stack
- **Frontend:** React, Axios
- **Backend:** Node.js, Express
- **Database:** MongoDB with Mongoose

## How to Run
### 0. first change both package_frontend and backend files name to package.json and put them in their respective folders according to the file structure which is provided at the end of the readme file
### Working demo link- https://drive.google.com/file/d/1kSckxXu5b3o119jNVvxRoMdTdcVQyjPF/view?usp=drivesdk

### 1. Backend

```bash
cd backend
npm install cookie-parser
npm run dev

### 2. Frontend 
```bash
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
