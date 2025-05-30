# Customer Support System 🧠💬

A large-scale, real-time **Customer Support System** integrated with a simple **E-Commerce** platform. This was developed as our **ITI Graduation Project** (2025) with 7 fully connected apps using:

> **Node.js**, **MongoDB**, **Socket.IO**, **React**, **Angular**, and **Express**.

---

## 📽️ LinkedIn Showcase

🎬 Watch the full walkthrough of the live system here:  
🔗 [LinkedIn Post (Video Demo)](https://www.linkedin.com/posts/ziad-gamal_nodejs-socketio-mongodb-activity-7334142892787085313-T0eT)

---

## 🌐 Live Deployments

| App | Link |
|-----|------|
| **Agent Dashboard** | [customer-support-agent-react](https://customer-support-agent-react.vercel.app/) |
| **Admin Dashboard** | [customer-support-admin-angular](https://customer-support-admin-angular.vercel.app/) |
| **E-Commerce Store** | [ecommerce-react](https://ecommerce-react-two-pi.vercel.app/) |
| **E-Commerce Admin Panel** | [ecommerce-admin-react](https://ecommerce-admin-react.vercel.app/) |

---

## 🧩 System Modules (7 Repos)

| App | Description | GitHub |
|-----|-------------|--------|
| **Customer Support API** | Backend logic: authentication, real-time socket handling, agent/chat tracking, auto-reassigning | [customer-support-node](https://github.com/ZiadGamalDev/customer-support-node) |
| **Customer Chat App** | Angular app embedded in e-commerce site. Customers start live chat from frontend | [ecommerce-chat-angular](https://github.com/ZiadGamalDev/ecommerce-chat-angular) |
| **Agent Dashboard** | React dashboard where support agents handle live chats, statuses, and reassign tickets | [customer-support-agent-react](https://github.com/ZiadGamalDev/customer-support-agent-react) |
| **Admin Dashboard** | Angular admin panel to manage users, agents, and chat history | [customer-support-admin-angular](https://github.com/ZiadGamalDev/customer-support-admin-angular) |
| **E-Commerce API** | Simulated e-commerce backend to support frontend & provide customer data | [ecommerce-node](https://github.com/ZiadGamalDev/ecommerce-node) |
| **E-Commerce Web** | Simple React frontend (products, cart, orders) with embedded customer chat | [ecommerce-react](https://github.com/ZiadGamalDev/ecommerce-react) |
| **E-Commerce Admin Panel** | React admin panel to manage products/categories for testing | [ecommerce-admin-react](https://github.com/ZiadGamalDev/ecommerce-admin-react) |

---

## 📚 Documentation

- [`docs/Business-Model.pdf`](./docs/Business-Model.pdf) – Covers app roles, features, and workflow
- [`docs/ITI-Graduation-Project-Discussion.pdf`](./docs/ITI-Graduation-Project-Discussion.pdf) – System architecture and implementation logic

---

## 🧠 Highlights

- **Real-time Chat System** with Socket.IO
- **Dynamic Agent Assignment** with load balancing
- **Agent Statuses**: available, away, busy
- **Chat Ticket Management**: new, open, pending, resolved
- **Email Verification & Role Approval** system
- **MongoDB Tracking Logs** for chat & agent history
- Modular API structure with clean services, helpers, middleware, enums

---

## 👨‍💻 Tech Stack

| Layer | Tech |
|-------|------|
| Backend | Node.js, Express, MongoDB, Mongoose |
| Real-time | Socket.IO |
| Auth | JWT, Email Verification |
| Frontend | React, Angular |
| Styling | Bootstrap, SCSS |
| Deployment | Railway (API), Vercel (Web) |

---

## 🤝 Contributors

We were a team of 5 developers:

- [Ziad Gamal](https://github.com/ZiadGamalDev)
- [Ahmed Mostafa](https://github.com/3b3zeem)
- [Sara Khaled](https://github.com/sarah5aled152)
- [Sondos Omar](https://github.com/sondosomarr)
- [Ahmed Farag](https://github.com/iahmedfarag)

Repo contributions are distributed across our GitHub profiles, with main development logic by **Ziad Gamal**.

---

## ✅ Project Status

- ✅ Fully deployed and tested
- 🛠️ Used as a real-world graduation project
- 📦 Open for learning, forking, or extending

---

## 📜 License

This project is licensed under the MIT License. See the [LICENSE](./LICENSE) file for details.
