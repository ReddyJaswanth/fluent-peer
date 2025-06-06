# Fluent Peer

## Overview
Fluent Peer is a modern language learning platform that connects users with language partners worldwide. Built with cutting-edge web technologies, it provides a seamless experience for real-time communication and language exchange.

## Features
- **Real-time Communication**: 
  - Video calls powered by Stream Video SDK
  - Chat functionality using Stream Chat
  - Real-time notifications and presence indicators
- **User Management**: 
  - Secure authentication system
  - Profile customization
  - Friend request system
- **Modern UI/UX**: 
  - Responsive design with Tailwind CSS
  - Beautiful components with DaisyUI
  - Dark/Light theme support
- **State Management**: 
  - Efficient state handling with Zustand
  - Data fetching with React Query

## Tech Stack
### Frontend
- **Core**: React 19 with Vite
- **Styling**: Tailwind CSS + DaisyUI
- **State Management**: Zustand
- **Data Fetching**: React Query
- **Real-time Communication**: Stream Video & Chat SDKs
- **Routing**: React Router
- **Build Tool**: Vite
- **Linting**: ESLint

### Backend
- **Runtime**: Node.js
- **API**: RESTful architecture
- **Authentication**: JWT-based auth system

## Getting Started

### Prerequisites
- Node.js (Latest LTS version recommended)
- npm or yarn package manager

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/fluent-peer.git
   cd fluent-peer
   ```

2. Install dependencies:
   ```bash
   # Install root dependencies
   npm install
   
   # Install frontend dependencies
   cd frontend
   npm install
   
   # Install backend dependencies
   cd ../backend
   npm install
   ```

3. Start the development servers:
   ```bash
   # Start backend server
   cd backend
   npm start
   
   # In a new terminal, start frontend server
   cd frontend
   npm run dev
   ```

4. Build for production:
   ```bash
   npm run build
   ```

## Contributing
We welcome contributions! Please follow these steps:
1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## License
This project is licensed under the MIT License - see the LICENSE file for details.