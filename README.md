# 🎹 Nimbus Keyboards

A modern, responsive, and animated 3D keyboard web application built with **Next.js 15**, **React 19**, **Tailwind CSS 4**, and **Three.js**.  
This project demonstrates professional frontend development with realistic 3D product rendering, animations, and modular architecture.

---

## 🌍 Live Demo

🔗 [https://nimbus-keyboards.vercel.app/](https://nimbus-keyboards.vercel.app/)

---

## 🚀 Features

- **Next.js 15 (App Router)** with Turbopack for blazing-fast dev experience.
- **React 19** with concurrent rendering.
- **Tailwind CSS v4** for modern utility-first styling.
- **3D Product Rendering** using `@react-three/fiber` and `@react-three/drei`.
- **Animations** powered by `GSAP` and `@gsap/react`.
- **Leva controls** for real-time 3D customization.
- **Stripe integration** for checkout and payments.
- **Prismic CMS** for content management with Slice Machine.
- **Radix UI Dialog** for accessible UI components.
- **SEO optimized** with Next.js best practices.
- **Deployed on Vercel** for global scale.

---

## 📂 Project Structure

```
📦 nimbus-keyboards
 ┣ 📂 src
 ┃ ┣ 📂 app
 ┃ ┃ ┣ 📂 success
 ┃ ┃ ┃ ┗ 📜 page.tsx
 ┃ ┃ ┣ 📜 layout.tsx
 ┃ ┃ ┗ 📜 globals.css
 ┃ ┣ 📂 components
 ┃ ┃ ┣ 📜 Navbar.tsx
 ┃ ┃ ┣ 📜 Footer.tsx
 ┃ ┃ ┣ 📜 Keyboard.tsx
 ┃ ┃ ┣ 📜 Switch.tsx
 ┃ ┃ ┣ 📜 Loader.tsx
 ┃ ┃ ┗ ... (other UI components)
 ┃ ┣ 📂 slices
 ┃ ┃ ┣ 📜 Hero.tsx
 ┃ ┃ ┣ 📜 Marquee.tsx
 ┃ ┃ ┣ 📜 SwitchPlayground.tsx
 ┃ ┃ ┣ 📜 Checkout.tsx
 ┃ ┃ ┗ ... (other slice components)
 ┃ ┣ 📂 utils
 ┃ ┃ ┗ 📜 helpers.ts
 ┣ 📂 public
 ┃ ┣ 📂 images
 ┃ ┗ 📜 favicon.ico
 ┣ 📜 package.json
 ┣ 📜 next.config.js
 ┣ 📜 tsconfig.json
 ┗ 📜 README.md
```

---

## 🛠 Tech Stack

- **Framework:** [Next.js 15](https://nextjs.org/)
- **Library:** [React 19](https://react.dev/)
- **Styling:** [Tailwind CSS 4](https://tailwindcss.com/)
- **3D Rendering:** [Three.js](https://threejs.org/) + [@react-three/fiber](https://docs.pmnd.rs/react-three-fiber/getting-started/introduction)
- **Animations:** [GSAP](https://gsap.com/)
- **CMS:** [Prismic](https://prismic.io/) + Slice Machine
- **UI Components:** [Radix UI](https://www.radix-ui.com/)
- **Payments:** [Stripe](https://stripe.com/)
- **Deployment:** [Vercel](https://vercel.com/)

---

## ⚙️ Installation & Setup

1. **Clone the repository:**

   ```bash
   git clone https://github.com/your-username/nimbus-keyboards.git
   cd nimbus-keyboards
   ```

2. **Install dependencies:**

   ```bash
   npm install
   ```

3. **Run development server:**

   ```bash
   npm run dev
   ```

   Project will be available at: [http://localhost:3000](http://localhost:3000)

4. **Build for production:**

   ```bash
   npm run build
   npm start
   ```

---

## 📦 Dependencies

From `package.json`:

```json
{
  "dependencies": {
    "@gsap/react": "^2.1.2",
    "@prismicio/client": "^7.19.1",
    "@prismicio/next": "^2.0.1",
    "@prismicio/react": "^3.2.1",
    "@radix-ui/react-dialog": "^1.1.15",
    "@react-three/drei": "^10.6.1",
    "@react-three/fiber": "^9.3.0",
    "@types/three": "^0.179.0",
    "clsx": "^2.1.1",
    "gsap": "^3.13.0",
    "leva": "^0.10.0",
    "next": "15.4.5",
    "react": "19.1.0",
    "react-dom": "19.1.0",
    "react-icons": "^5.5.0",
    "stripe": "^18.4.0",
    "three": "^0.179.1"
  },
  "devDependencies": {
    "@eslint/eslintrc": "^3",
    "@slicemachine/adapter-next": "^0.3.83",
    "@tailwindcss/postcss": "^4",
    "@types/node": "^20",
    "@types/react": "^19",
    "@types/react-dom": "^19",
    "eslint": "^9",
    "eslint-config-next": "15.4.5",
    "prettier": "^3.6.2",
    "prettier-plugin-tailwindcss": "^0.6.14",
    "slice-machine-ui": "^2.18.1",
    "tailwindcss": "^4",
    "typescript": "^5"
  }
}
```

---

## ✨ Author

**Fahad Ali**  
Frontend Developer | Pakistan  
📧 [fa6084904@gmail.com](mailto:fa6084904@gmail.com)  
🔗 [LinkedIn Profile](https://www.linkedin.com/in/fahad-ali-759700369/)

---

## 📌 Notes

- This project follows **modern frontend practices** with a focus on **3D rendering, animations, and modular components**.
