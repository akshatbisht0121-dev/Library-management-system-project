# Library-management-system-project
project/
├── backend/
│   ├── server.js          ← Express app, routes, JWT/bcrypt logic
│   ├── package.json
│   ├── package-lock.json
│   ├── seedbooks.js        ← one-time script to generate books.json
│   ├── books.json          ← acts as your "database"
│   ├── users.json
│   ├── issues.json
│   └── announcements.json
└── frontend/
    ├── index.html          ← markup + your JS (fetch calls to the API)
    └── styles.css           ← new file, extracted from index.html
