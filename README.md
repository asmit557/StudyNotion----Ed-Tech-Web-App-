# 🎓 StudyNotion – Learn, Grow, Succeed 🚀

![StudyNotion Banner](https://github.com/asmit557/StudyNotion----Ed-Tech-Web-App-/blob/main/public/logo.png)

> A full-stack Ed-Tech platform that enables students to enroll in and learn courses, while empowering educators to create and manage content. Built with **MERN stack**, integrated with **Razorpay**, **JWT Auth**, and powered by **Cloudinary** for media delivery.

---

## 📁 Tech Stack

### 🧠 Frontend

* ⚛️ **React 18** with React Router DOM
* 🧵 **Tailwind CSS** + Prettier Plugin for styling
* 🔄 **Redux Toolkit** for state management
* 📈 **Chart.js** + react-chartjs-2 for analytics
* 🧾 **React Markdown** for rich content
* 📼 **Video React** for media content
* 🧪 **React Testing Library**
* 🍞 **React Hot Toast** for notifications

### ⚙️ Backend

* 🌐 **Express.js**
* 🛡️ **JWT Authentication** with **cookie-parser**
* 🔒 **bcrypt & bcryptjs** for secure password hashing
* 💾 **MongoDB** with **Mongoose**
* ☁️ **Cloudinary** for image and video uploads
* ✉️ **Nodemailer** for email services
* 💸 **Razorpay** for secure payments
* 📩 **OTP-Generator** for 2FA

---

## 🚀 Features

### 👩‍🏫 Educator

* Create and manage courses
* Upload video lectures
* Manage pricing and publish content
* View student analytics with charts

### 🧑‍🎓 Student

* Browse and enroll in courses
* Track progress
* Leave reviews and ratings
* Get certificates (optional)

### 🛡️ Authentication

* JWT-based auth with secure cookies
* OTP verification on signup
* Forgot password with token-based reset

### 📸 Media

* Drag & drop file uploads with **react-dropzone**
* Image & video previews via **Cloudinary**

### 💳 Payments

* Razorpay Integration
* Secure checkout
* Transaction confirmation emails

### 📊 Dashboard

* Student & Instructor dashboards with insights
* Charts for analytics

---

## 📸 Screenshots

| Landing Page                                                                | Login Page                                                               | Profile Page                                                                 |
| --------------------------------------------------------------------------- | ------------------------------------------------------------------------- | ------------------------------------------------------------------------------- |
| ![landing](https://drive.google.com/file/d/1mDoh5hS85VFy-I2x75uRdIXIXoIe8tlU/view?usp=sharing) | ![Login](https://drive.google.com/file/d/1_QWGKo5sObhKkwexLxFKPjsgJPwWpXY1/view?usp=sharing) | ![Profile](https://drive.google.com/file/d/1gKhAuZkzJpNyBs-pxFbAFV_Xbc0oYAbH/view?usp=sharing) |

---

## 🛠️ Installation

### 📦 Clone the Repository

```bash
git clone https://github.com/asmit557/StudyNotion----Ed-Tech-Web-App-.git
cd studynotion
```

### 📁 Set Up Backend

```bash
cd server
npm install
cp .env.example .env
npm run dev
```

> Add your `MONGO_URI`, `CLOUDINARY_SECRET`, `RAZORPAY_KEY`, and other env variables

### 💻 Set Up Frontend

```bash
cd client
npm install
npm start
```

### 📌 Dev Together

Run both servers concurrently:

```bash
npm run dev  # from client root
```

---

## 💡 Notable Packages

| Package                          | Purpose                      |
| -------------------------------- | ---------------------------- |
| **jsonwebtoken**                 | Secure login sessions        |
| **cloudinary**                   | Image & video storage        |
| **react-type-animation**         | Eye-catching hero sections   |
| **react-rating-stars-component** | Review and ratings system    |
| **nodemailer**                   | Email handling               |
| **axios**                        | API calls                    |
| **razorpay**                     | Secure payment gateway       |
| **react-hook-form**              | Form handling and validation |

---

## 🤝 Contributing

Pull requests are welcome! For major changes, please open an issue first to discuss what you would like to change.

### 📋 To-Do:

* [ ] Add certificate generation 🎖️
* [ ] Add instructor analytics 📊
* [ ] Improve mobile responsiveness 📱

---

## 📄 License

This project is licensed under the ISC License.

---

## 🙏 Acknowledgements

Thanks to all the open-source packages and developers that make tools like this possible!

---

## 🌟 Star us on GitHub if you like it!

[![GitHub Repo stars](https://img.shields.io/github/stars/asmit557/StudyNotion----Ed-Tech-Web-App-?style=social)](https://github.com/asmit557/StudyNotion----Ed-Tech-Web-App-)

---

Made with ❤️ by [Asmit](https://github.com/asmit557)

