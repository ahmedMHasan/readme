# 📚 Read Me

**Read Me** is a multilingual reading tracker web app designed to help readers, students, and educators log, organize, and reflect on their reading journeys in an engaging and structured way. Built with **React**, **TypeScript**, **Tailwind CSS**, and **i18next**, it supports multiple languages and offers a sleek, responsive UI.

---

## 🚀 Features

### 🌍 Multi-language Support
- Full **English**, **Turkish**, and **Arabic** support.
- RTL (Right-to-Left) layout support for Arabic.
- Language selection persists based on session or user preference.

### 📖 Track Your Reading
- Log every book you read with details like author, genre, and completion date.
- Add personal notes and reflections.
- Search and filter through your reading history.

### 🎯 Set Reading Goals
- Define annual reading targets.
- Track progress visually throughout the year.

### 👩‍🏫 Supervisor Monitoring
- Ideal for schools: Teachers or mentors can view and monitor student progress and notes.

---

## 🧭 Navigation

When users visit the site:
- **Authenticated users** are automatically redirected to the `/dashboard`.
- **Unauthenticated users** stay on the home page with clear calls to action: `Get Started` or `Sign In`.

---

## 🧩 Components Used

- **`LanguageSelector`** – Allows instant language switching from the navigation bar.
- **`Button`**, **`Card`**, **`CardContent`** – Styled using Shadcn UI and Tailwind for modern design.
- **`lucide-react`** icons – Used for clear and elegant feature representations.

---

## 🛠️ Tech Stack

- **Frontend:** React + TypeScript
- **Styling:** Tailwind CSS + Shadcn UI
- **Icons:** lucide-react
- **Routing:** React Router DOM
- **State & Auth:** Custom `AuthContext`
- **Internationalization:** i18next

---

## 🌈 Design Highlights

- Gradient backgrounds for a soft and inviting reading experience.
- Smooth entrance animations (`animate-in`, `fade-in`, `slide-in`) for UI elements.
- Responsive grid layout for feature cards.

---

## 🧪 Getting Started

1. **Clone the Repository**
   ```bash
   git clone https://github.com/yourusername/readme.git
   cd readme
   ```

2. **Install Dependencies**
   ```bash
   yarn install
   ```

3. **Run the Development Server**
   ```bash
   yarn dev
   ```

4. **Build for Production**
   ```bash
   yarn build
   ```

---

## 🌐 Deployment

This project is ready to be deployed on **GitHub Pages** or any static hosting platform. Create a new **public branch** for deployment, and ensure proper routing setup for React single-page applications.

---

## 💡 Future Enhancements

- Add social reading features (friends, comments, challenges)
- Export reading stats as PDF
- Dark mode toggle

---

## 👨‍💻 Author
**Ahmed Hasan** – Creator of Read Me, passionate about intuitive, multilingual educational tools.

---

## 🪪 License
MIT License – Feel free to use and modify as needed.

