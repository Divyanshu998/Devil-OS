# Devil-OS



# 🚀 DEVIL OS – AI-Powered Private Operating System Simulation

**React + Rust + Blockchain + AI Integration**

## 💡 Overview

DEVIL OS is a non-bootable simulated Operating System designed to behave like a real OS inside your browser. It provides a virtual desktop, AI assistant (DEV-EYE), system control center, file system simulator, and blockchain-secured audit system.

## 🏗️ Architecture

- **Frontend**: React.js + TypeScript + TailwindCSS
- **Backend**: Rust (Axum framework)
- **Blockchain**: Private Ethereum (Ganache)
- **Database**: SQLite
- **AI**: OpenAI API / Local LLM integration
- **Container**: Docker Compose

## 🚀 Quick Start

### Prerequisites
- Node.js 18+
- Rust 1.70+
- Docker & Docker Compose
- OpenAI API Key (optional, for AI features)

### Installation

1. Clone the repository
2. Install dependencies:
```bash
# Frontend
cd frontend
npm install

# Backend
cd ../backend
cargo build
```

3. Set up environment variables:
```bash
cp .env.example .env
# Edit .env with your configuration
```

4. Run with Docker Compose:
```bash
docker-compose up
```

5. Access DEVIL OS:
- Frontend: http://localhost:3000
- Backend API: http://localhost:8080
- Blockchain RPC: http://localhost:8545

## 🎯 Features

- 🔐 **Authentication**: JWT-based secure login
- 📊 **System Monitor**: Real-time CPU, memory, network stats
- 📂 **File System**: Virtual file manager with CRUD operations
- 🌐 **Network Monitor**: Simulated network traffic visualization
- 🔗 **Blockchain Ledger**: Immutable audit logs
- 🤖 **DEV-EYE Assistant**: AI-powered voice & text assistant
- ⚙️ **Settings & Policies**: Customizable themes and access controls

## 🤖 DEV-EYE AI Assistant

Your built-in cyber AI assistant with:
- Text and voice commands
- System analysis and optimization suggestions
- Natural language explanations of logs and metrics
- Automated system actions

## 📡 API Endpoints

| Endpoint | Method | Description |
|----------|--------|-------------|
| `/api/login` | POST | Authenticate user |
| `/api/system/stats` | GET | System metrics |
| `/api/files` | GET/POST | File operations |
| `/api/audit/logs` | GET | Blockchain ledger |
| `/api/ai/query` | POST | AI assistant chat |
| `/api/ai/automate` | POST | Execute AI commands |

## 🔒 Security

- Immutable blockchain event logs
- Encrypted database storage
- Sandboxed AI execution
- JWT token authentication

## 📦 Project Structure

```
DEVIL-OS/
├── frontend/          # React TypeScript application
├── backend/           # Rust Axum server
├── blockchain/        # Smart contracts & config
├── docker-compose.yml # Container orchestration
└── README.md
```

## 🛠️ Development

See individual README files in `frontend/` and `backend/` directories for detailed development instructions.

## 📄 License

MIT License - See LICENSE file for details
