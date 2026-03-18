# AnonMate

Anonymous Chat & Video Calling Platform

AnonMate is a real-time communication platform that allows users to connect anonymously for text chat and video calls using peer-to-peer technology.

## Overview

AnonMate connects users randomly for anonymous conversations. Whether you want to chat text-based or have a video call, AnonMate provides a secure, anonymous way to communicate.

## Key Features

- Anonymous User Matching: Get instantly matched with random users
- Real-Time Text Chat: Communicate via instant messaging
- Peer-to-Peer Video Calling: Crystal clear video calls using WebRTC
- Socket.IO Integration: Reliable real-time communication
- Responsive Design: Works seamlessly on desktop and mobile

## Tech Stack

Frontend:
- React 18.2.0
- TypeScript 5.2.2
- Vite 5.1.6
- TailwindCSS 3.4.1
- Framer Motion 12.11.3

Real-Time Communication:
- Socket.IO Client 4.8.1
- WebRTC (for peer-to-peer video)

Development Tools:
- ESLint for code quality
- PostCSS for styling

## Installation

Prerequisites:
- Node.js (v16 or higher)
- npm or yarn

Steps:
1. Clone the repository
2. Navigate to the project directory
3. Install dependencies:
   npm install

## Getting Started

Development:
npm run dev

Build for production:
npm run build

Preview production build:
npm run preview

Lint code:
npm run lint

## Current Status

Completed:
- Basic chat functionality
- Socket.IO integration
- User matching system
- Message sending/receiving
- UI components with styling
- Landing page with features section

In Progress:
- WebRTC implementation for video calls
- Video chat UI components
- Advanced error handling
- Performance optimization

## Roadmap

1. WebRTC Implementation
   - Set up peer connections
   - Implement video/audio streams
   - Handle signaling through Socket.IO

2. UI Enhancements
   - Video chat controls (mute, camera toggle)
   - Loading states and user indicators
   - Responsive video interface

3. Error Handling
   - Socket disconnection handling
   - WebRTC connection failure recovery
   - User feedback for connection status

4. New Features
   - Skip functionality for new matches
   - Text/video mode preferences
   - User settings and preferences

5. Testing & Optimization
   - Multi-user concurrent testing
   - Video quality optimization
   - Performance under various network conditions

## Live Demo

Visit the live application at: https://anon-mate.vercel.app

## Contributing

Contributions are welcome! Please feel free to submit pull requests or open issues for bugs and feature requests.

## Support

For issues, questions, or suggestions, please open an issue on the GitHub repository.
