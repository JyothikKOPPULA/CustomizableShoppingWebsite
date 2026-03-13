# 🛍️ AI-Powered Customizable 3D Shopping Platform

An intelligent 3D e-commerce customization platform that enables users to design and personalize virtual merchandise in real time. The platform combines interactive 3D visualization, AI-generated design assets, and modern web technologies to deliver a seamless and immersive product customization experience.

Users can dynamically customize swag items such as t-shirts, merchandise, or promotional products, apply colors, textures, and logos, and generate AI-assisted designs instantly before downloading or previewing their creations.

## 🎯 Overview

Traditional e-commerce platforms lack interactive product customization. This platform solves that by introducing a real-time 3D product design environment where users can visually experiment with colors, textures, and branding elements before finalizing their product.

By integrating AI-generated logos and textures, the platform also assists users in automatically generating creative design elements, reducing design effort and enhancing personalization.

The result is a next-generation customizable shopping experience that blends 3D graphics, AI assistance, and responsive UI design.

## 🚀 Key Features

### 🎨 Real-Time 3D Product Customization

**Interactive 3D Rendering**
- Visualize customizable products such as t-shirts in real time using optimized WebGL rendering.

**Dynamic Color Customization**
- Instantly change product colors with real-time updates in the 3D model.

**Theme Synchronization**
- Application UI dynamically adapts to the selected product theme and color.

### 🤖 AI-Powered Design Assistance

**AI Logo Generation**
- Generate custom logos using AI prompts and automatically apply them to products.

**AI Texture Generation**
- Create unique product textures with AI-generated visuals.

**Design Prompt Interface**
- Users can describe the design they want and receive generated visual assets.

### 🖼️ Custom Asset Integration

**Logo Upload**
- Upload personal or brand logos and project them onto the 3D product surface.

**Texture Upload**
- Apply custom images and patterns to enhance product aesthetics.

### ⚡ Enhanced User Experience

**Smooth Animations**
- Framer Motion provides fluid UI transitions and interactive effects.

**Responsive Interface**
- Optimized for desktop, tablet, and mobile devices.

**Export & Download**
- Download customized designs as images for production or sharing.

**Modular Architecture**
- Built with reusable components for scalability and maintainability.

## 🛠️ Tech Stack

| Layer | Technology |
|-------|-----------|
| **Frontend** | React.js |
| **3D Rendering** | Three.js, React Three Fiber, React Three Drei |
| **Styling & UI** | Tailwind CSS, Framer Motion |
| **Build Tool** | Vite |
| **Backend** | Node.js, Express.js |
| **AI Integration** | OpenAI API |
| **State Management** | Valtio |

## 🧠 System Architecture

```
User Interface (React + Tailwind)
        │
        ▼
3D Rendering Engine (Three.js + React Three Fiber)
        │
        ▼
State Management (Valtio)
        │
        ▼
Backend API (Node.js + Express)
        │
        ▼
AI Services (OpenAI API)
```

## 📋 Prerequisites

Ensure the following tools are installed:

- **Git**
- **Node.js** (v14 or higher)
- **npm** (Node Package Manager)

## ⚙️ Installation & Setup

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/JyothikKOPPULA/CustomizableShoppingWebsite.git
cd CustomizableShoppingWebsite
```

### 2️⃣ Install Dependencies

Install dependencies for both frontend and backend.

**Root:**
```bash
npm install
```

**Server:**
```bash
cd server
npm install
```

**Client:**
```bash
cd client
npm install
```

### 3️⃣ Configure Environment Variables

Create a `.env` file in the root directory:

```env
OPENAI_API_KEY=your_openai_api_key_here
```

You can generate your API key from the [OpenAI dashboard](https://platform.openai.com/api-keys).

### 4️⃣ Run the Application

**Start Backend:**
```bash
npm start
```

**Start Frontend** (in a separate terminal):
```bash
npm run dev
```

### 5️⃣ Launch the App

Visit: `http://localhost:5173`

## 📁 Project Structure

```
3D_customizer_website/
│
├── client/                    # React frontend
│   ├── components/            # Reusable UI components
│   ├── canvas/                # 3D canvas components
│   ├── pages/                 # Application pages
│   └── store/                 # State management
│
├── server/                    # Express backend
│   ├── routes/                # API routes
│   ├── controllers/           # Request handlers
│   └── utils/                 # Helper functions
│
├── public/                    # Static assets
├── package.json               # Root dependencies
└── README.md                  # Documentation
```

## 🔧 Environment Configuration

| Variable | Description |
|----------|-----------|
| `OPENAI_API_KEY` | API key used for AI logo and texture generation |

## 💡 Future Enhancements

- 🛒 E-commerce checkout integration
- ☁️ Cloud storage for saved designs
- 👕 Multiple customizable product types
- 🧠 Advanced generative AI design assistant
- 📦 AR preview for real-world visualization
- 💾 Design history and version control
- 🌍 Multi-language support


⭐ **If you find this project helpful, consider giving it a star!**

**Built with ❤️ using React.js, Three.js, and OpenAI**
