# 🏠 Enterprise-Grade Real Estate Rental App

A full-stack, scalable real estate rental application built with **Next.js**, **Node.js**, and **AWS** services. Inspired by Ed Roh's comprehensive tutorial, this application showcases best practices in modern full-stack development and deployment on the AWS cloud.

## 🚀 Live Demo

Coming soon...

---

## 📦 Tech Stack

### Frontend

- [Next.js](https://nextjs.org/)
- [React](https://react.dev/)
- [TypeScript](https://www.typescriptlang.org/)
- [Tailwind CSS](https://tailwindcss.com/)
- [Shadcn/UI](https://ui.shadcn.com/)
- [Framer Motion](https://www.framer.com/motion/)
- [React Hook Form](https://react-hook-form.com/)
- [Zod](https://zod.dev/)
- [Redux Toolkit + RTK Query](https://redux-toolkit.js.org/)
- [Mapbox GL](https://docs.mapbox.com/mapbox-gl-js/guides/)

### Backend

- [Node.js](https://nodejs.org/)
- [Express.js](https://expressjs.com/)
- [Prisma ORM](https://www.prisma.io/)
- [PostgreSQL](https://www.postgresql.org/) with [PostGIS](https://postgis.net/)
- [AWS RDS](https://aws.amazon.com/rds/)
- [AWS EC2](https://aws.amazon.com/ec2/)
- [AWS API Gateway](https://aws.amazon.com/api-gateway/)
- [AWS S3](https://aws.amazon.com/s3/)
- [AWS Amplify](https://docs.amplify.aws/)
- [AWS Cognito](https://aws.amazon.com/cognito/)

---

## ✨ Features

- 🔐 Secure authentication with AWS Cognito
- 📦 Scalable backend hosted on AWS EC2 and RDS
- 🏠 Property listings with images, geolocation, and advanced search
- 📍 Interactive maps using Mapbox GL
- 🗂️ Lease applications and management
- 🛠️ Admin settings and CRUD operations
- 🌐 Full mobile and desktop responsiveness
- ☁️ File uploads to AWS S3

---

## 📁 Project Structure

```
real-estate-app/
│
├── frontend/              # Next.js frontend
│   ├── components/        # UI components
│   ├── pages/             # Route pages
│   ├── app/               # Next.js 13+ app dir
│   └── ...
│
├── backend/               # Node.js API server
│   ├── src/
│   ├── prisma/            # Prisma schema & migrations
│   └── ...
│
├── infrastructure/        # AWS and deployment configuration
│
├── .env                  # Environment variables
└── README.md             # Project documentation
```

---

## ⚙️ Getting Started

### 1. Clone the Repo

```bash
git clone https://github.com/BRIKIAchraf/-Real-Estate-Web-App.git
cd real-estate-app
```

### 2. Environment Setup

Create `.env` files in both `frontend/` and `backend/` folders based on `.env.example` templates.

### 3. Install Dependencies

**Frontend:**

```bash
cd frontend
npm install
```

**Backend:**

```bash
cd ../backend
npm install
```

### 4. Run the App Locally

**Frontend:**

```bash
npm run dev
```

**Backend:**

```bash
npm run dev
```

---

## ☁️ AWS Deployment Overview

The app is fully deployable to AWS using:

- **EC2** for backend hosting
- **RDS (PostgreSQL)** for database
- **S3** for storing images
- **Cognito** for authentication
- **API Gateway** for routing
- **Amplify** for frontend CI/CD (optional)

> Refer to [AWS EC2 Instructions](https://github.com/BRIKIAchraf/-Real-Estate-Web-App/blob/main/server/aws-ec2-instructions.md) for detailed setup steps.

---

## 📚 Useful Resources

- 📘 **Completed Code:** https://github.com/ed-roh/real-estate-project
- 📊 **Architecture Diagrams:** https://www.edroh.com/subscribe/real-estate
- 🎨 **Design Assets:** https://drive.google.com/drive/folders/1KTtCn3...
- 🗺️ **Nominatim (Geocoding):** https://nominatim.org/release-docs/latest/
- 🧭 **Mapbox GL:** https://docs.mapbox.com/mapbox-gl-js/guides/
- 🔐 **AWS Cognito:** https://aws.amazon.com/cognito/

---

## 📸 Screenshots

Coming soon...

---

---

## 📝 License

This project is licensed under the MIT License.

---

## 🤝 Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you'd like to change.

---

## 📫 Contact

For inquiries, reach out via [LinkedIn](www.linkedin.com/in/achrafbriki) or open an issue.
