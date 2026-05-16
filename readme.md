# Smart Pilgrims Assistant App 🕊️

> An all-in-one Smart Pilgrim Assistant combining real-time crowd monitoring, AI-assisted navigation, SOS alerts, and seamless temple management. Designed to elevate the pilgrimage experience ensuring safety and convenience.

## 🚀 Features
- **Real-Time Crowd Management & Heatmaps**: Monitor density levels across zones using YOLOv8.
- **AI Chatbot & Audio Guide**: Interactive AI for answering queries and providing historical context in local languages.
- **Emergency and SOS Alerts**: Instant alerts sent to guardians and authorities.
- **Family Sync & Lost/Found**: Keep track of family members in crowded areas.
- **E-Tickets & Booking Systems**: Hassle-free Darshan ticket and parking slot bookings.

## 🛠️ Tech Stack
- **Frontend**: React.js, Vite, Tailwind CSS, Radix UI
- **Backend**: Node.js, Express.js, Socket.io, Firebase Admin
- **Database**: MySQL (Aiven) + Sequelize ORM
- **AI Engine**: Python, YOLOv8 (Crowd tracking), Text-to-Speech (TTS), Flask

## 📂 Project Structure
```
├── Backend/        # Node.js/Express server & API routes
│   └── config/     # Database and Cloudinary configurations
│   └── controllers/# Business logic
│   └── models/     # Sequelize Models
│   └── routes/     # Express route handlers
│   └── socket/     # Socket.io handlers
├── Frontend/       # Vite/React Frontend application
│   └── src/        # Components, Context, Pages, and Hooks
├── AI_Core/        # Python-based crowd tracking and AI tools
└── .github/        # Community & Contribution templates
```

## 💻 Getting Started
Please refer to our [INSTALLATION.md](./INSTALLATION.md) for detailed instructions on local setup, including how to configure the **Aiven MySQL Database**.

## 🤝 Contributing
We welcome contributions! Please follow these guidelines to make the process smooth:
- Read our [Contributing Guidelines](CONTRIBUTING.md) to understand our workflow.
- Adhere to the [Code of Conduct](CODE_OF_CONDUCT.md).
- Check out [Security/Vulnerability Reporting](SECURITY.md).

### First-Time Contributors
If you're a first-time contributor, check the `good first issue` label in our issues tab.

## 🛡️ License
This project is licensed under the MIT License - see the LICENSE file for details.

## 🙏 Acknowledgements
A special thanks to all open-source contributors and programs like **GSSoC** for supporting and enhancing community collaboration!
