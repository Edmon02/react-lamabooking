# LamaBooking-React  
[![License](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)  

> A hotel booking platform built with React (class components) — designed for simplicity and ease of use.  

## 📖 Description  
**LamaBooking-React** is a frontend booking application created 3 years ago to demonstrate core React concepts (e.g., component architecture, state management) and integrate with a hypothetical backend. While it doesn’t use modern tools like hooks or TypeScript, it serves as a foundational example for:  
- **UI Composition**: Reusable components (headers, property listings, search).  
- **Static Routing**: Multi-page navigation (home, hotel details, search results).  
- **Styling**: Vanilla CSS for modular design.  

**Note**: This project is unmaintained but open for contributions or modernization (e.g., migrating to functional components, adding API integrations).  

## 🛠️ Tech Stack  
- **Frontend**: React (class components), JavaScript  
- **Styling**: Vanilla CSS (no preprocessors)  
- **Build Tool**: Create-React-App (default setup)  

## 🚀 Quick Start  
1. Clone the repo:  
   ```bash  
   git clone https://github.com/your-username/react-lamabooking.git  
   cd react-lamabooking  
   ```  
2. Install dependencies and run:  
   ```bash  
   npm install  
   npm start  
   ```  

## 📂 Project Structure  
```  
react-lamabooking/  
├── src/  
│   ├── components/          # Reusable UI (Header, Footer, SearchItem)  
│   │   ├── featured/        # Featured properties section  
│   │   ├── navbar/          # Navigation bar  
│   │   └── ...  
│   ├── pages/               # Route-specific layouts  
│   │   ├── home/            # Landing page  
│   │   ├── hotel/           # Hotel details  
│   │   └── list/            # Search results  
│   ├── App.js               # Root component  
│   └── index.js             # Entry point  
├── public/                  # Static assets  
└── README.md  
```  

## 🤝 Contributing  
While this project is unmaintained, PRs are welcome for:  
- **Modernization**: Migrate to React hooks, TypeScript, or styled-components.  
- **Bug Fixes**: Address legacy issues (if any).  

**Steps**:  
1. Fork the repo.  
2. Create a branch (`git checkout -b feature/migrate-to-hooks`).  
3. Commit changes (`git commit -m "refactor: use functional components"`).  
4. Push and open a PR.  

## 📜 License  
[MIT](LICENSE) — Permissive for all use cases, including derivatives.
