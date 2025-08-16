
# Google Drive Clone

A simple static web application that mimics the UI of Google Drive. Built with HTML, CSS (Materialize), and deployed using Firebase Hosting.

## Features
- Google Drive-inspired user interface
- Responsive design using Materialize CSS
- Search bar and navigation
- Static deployment (no backend logic)

## Demo
Live site: [https://drive-clone-29079.web.app/](https://drive-clone-29079.web.app/)

## Project Structure

```
Google-Drive-Clone/
├── public/
│   ├── index.html      # Main HTML file
│   └── style.css       # Custom styles
├── firebase.json       # Firebase Hosting config
├── .firebaserc         # Firebase project alias
├── package.json        # Project metadata and scripts
├── sandbox.config.json # CodeSandbox config
└── README.md           # Project documentation
```

## Getting Started

### Prerequisites
- [Node.js](https://nodejs.org/) (for local server)
- [Firebase CLI](https://firebase.google.com/docs/cli) (for deployment)

### Local Development
1. Clone the repository:
   ```bash
   git clone https://github.com/rohanraaj2/Google-Drive-Clone.git
   cd Google-Drive-Clone
   ```
2. Install dependencies:
   ```bash
   npm install
   ```
3. Start the local server:
   ```bash
   npm start
   ```
4. Open [http://localhost:5000](http://localhost:5000) in your browser.

### Deployment
1. Install Firebase CLI if you haven't:
   ```bash
   npm install -g firebase-tools
   ```
2. Login to Firebase:
   ```bash
   firebase login
   ```
3. Initialize (if needed) and deploy:
   ```bash
   firebase deploy
   ```
