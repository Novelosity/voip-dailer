VoIP Platform (voip-dailer)A modern VoIP (Voice over Internet Protocol) dialer platform built with a monorepo architecture. It features a lightning-fast client application built with React and Vite, and a robust backend powered by Express.js and WebSockets for seamless real-time communication.🚀 FeaturesReal-time Communication: Low-latency WebSocket connections for immediate signaling and data transfer.Modern Frontend: Optimized builds and a responsive UI tailored for rapid development using Vite and React.Robust Backend: Efficient backend signaling and connection management using Express.Monorepo Structure: Clean separation of concerns between the client and server within a unified repository.🛠️ Tech StackClient: React.js, ViteServer: Node.js, Express.js, WebSocketsPackage Management: npm📋 PrerequisitesBefore you begin, ensure you have met the following requirements:Node.js: Version 22.0.0 or higher is required.⚙️ Setup & InstallationClone the repository and install the dependencies for both the server and the client environments.# Clone the repository
git clone [https://github.com/Novelosity/voip-dailer.git](https://github.com/Novelosity/voip-dailer.git)
cd voip-dailer

# Install backend dependencies
npm --prefix server install

# Install frontend dependencies
npm --prefix client install
🔐 ConfigurationThe server requires specific environment variables to run properly.Navigate to the server directory.Duplicate the .env.example file and rename it to .env.Fill in the required environment variables inside the newly created .env file.cp server/.env.example server/.env
🚀 Running the ApplicationTo start the platform, you will need to run both the server and the client development scripts, ideally in two separate terminal windows.1. Start the Server:npm --prefix server run dev
2. Start the Client:npm --prefix client run dev
📂 Project Structurevoip-dailer/
├── client/          # Vite + React frontend application
│   ├── src/
│   ├── package.json
│   └── ...
├── server/          # Express + WebSocket backend application
│   ├── .env.example
│   ├── package.json
│   └── ...
├── package.json     # Root package configuration
└── README.md
🤝 ContributingContributions, issues, and feature requests are welcome! Feel free to check the issues page.
