# 💫 Varunesh T - Portfolio Website

A modern, animated portfolio website built with Next.js, React, and Framer Motion. This project showcases my skills, projects, and experience as a Full-Stack Developer and ML Enthusiast.

![Portfolio Preview](https://img.shields.io/badge/Status-Live-brightgreen)
![Next.js](https://img.shields.io/badge/Next.js-14-black)
![React](https://img.shields.io/badge/React-18-blue)
![TypeScript](https://img.shields.io/badge/TypeScript-5-blue)
![Tailwind CSS](https://img.shields.io/badge/Tailwind-3-cyan)
![Framer Motion](https://img.shields.io/badge/Framer%20Motion-10-purple)

## 🌟 Features

### ✨ **Animations & Interactions**
- **Smooth Scroll Animations** - Powered by Framer Motion
- **Interactive Background** - Mouse-following gradient effects
- **Hover Animations** - Engaging micro-interactions
- **Staggered Animations** - Sequential element reveals
- **Floating Elements** - Subtle movement animations

### 🎨 **Modern UI Design**
- **Glassmorphism Effects** - Backdrop blur and transparency
- **Gradient Backgrounds** - Dynamic color schemes
- **Responsive Design** - Mobile-first approach
- **Dark Theme** - Professional purple/pink aesthetic
- **Typography** - Gradient text effects and modern fonts

### 📱 **Responsive Sections**
1. **Hero Section** - Animated introduction with rotating icon
2. **About Me** - Current focus with live status indicators
3. **Stats Dashboard** - Visual achievement metrics
4. **Featured Projects** - Interactive project showcase
5. **Tech Stack** - Animated technology grid
6. **Contact Section** - Social media integration

## 🚀 Quick Start

### Prerequisites
- Node.js 18+ 
- npm or yarn package manager

### Installation

1. **Clone the repository**
   \`\`\`bash
   git clone https://github.com/varunesharasu/portfolio.git
   cd portfolio
   \`\`\`

2. **Install dependencies**
   \`\`\`bash
   npm install
   # or
   yarn install
   \`\`\`

3. **Run the development server**
   \`\`\`bash
   npm run dev
   # or
   yarn dev
   \`\`\`

4. **Open your browser**
   Navigate to [http://localhost:3000](http://localhost:3000)

## 📁 Project Structure

\`\`\`
portfolio/
├── app/
│   ├── globals.css          # Global styles and Tailwind imports
│   ├── layout.tsx           # Root layout component
│   └── page.tsx             # Main portfolio page
├── components/
│   └── ui/                  # Reusable UI components
│       ├── badge.tsx
│       ├── button.tsx
│       └── card.tsx
├── lib/
│   └── utils.ts             # Utility functions
├── public/                  # Static assets
├── README.md               # Project documentation
├── next.config.js          # Next.js configuration
├── package.json            # Dependencies and scripts
├── tailwind.config.js      # Tailwind CSS configuration
└── tsconfig.json           # TypeScript configuration
\`\`\`

## 🛠️ Built With

### **Core Technologies**
- **[Next.js 14](https://nextjs.org/)** - React framework with App Router
- **[React 18](https://reactjs.org/)** - UI library with latest features
- **[TypeScript](https://www.typescriptlang.org/)** - Type-safe JavaScript
- **[Tailwind CSS](https://tailwindcss.com/)** - Utility-first CSS framework

### **Animation & UI**
- **[Framer Motion](https://www.framer.com/motion/)** - Production-ready motion library
- **[Lucide React](https://lucide.dev/)** - Beautiful & consistent icons
- **[shadcn/ui](https://ui.shadcn.com/)** - Re-usable components built with Radix UI

### **Styling & Design**
- **Glassmorphism** - Modern glass-like UI effects
- **CSS Grid & Flexbox** - Advanced layout techniques
- **Custom Animations** - Smooth transitions and micro-interactions
- **Responsive Design** - Mobile-first approach

## 🎨 Customization

### **Colors & Theme**
The portfolio uses a custom color scheme defined in `tailwind.config.js`:

\`\`\`javascript
// Primary colors
purple: '#8B5CF6'
pink: '#EC4899'
blue: '#3B82F6'

// Background gradients
from-slate-900 via-purple-900 to-slate-900
\`\`\`

### **Animation Settings**
Modify animation durations and effects in the main component:

\`\`\`typescript
// Example animation configuration
initial={{ opacity: 0, y: 50 }}
animate={{ opacity: 1, y: 0 }}
transition={{ duration: 0.8 }}
\`\`\`

### **Content Updates**
Update personal information in the main component arrays:

\`\`\`typescript
// Tech stack
const techStack = [
  { name: "React", icon: "⚛️", color: "bg-blue-500" },
  // Add your technologies here
]

// Projects
const projects = [
  {
    title: "Your Project",
    description: "Project description",
    tech: ["React", "Node.js"],
    // Add your projects here
  }
]
\`\`\`

## 📊 Performance

### **Lighthouse Scores**
- **Performance**: 95+
- **Accessibility**: 100
- **Best Practices**: 100
- **SEO**: 95+

### **Optimization Features**
- Next.js automatic code splitting
- Image optimization with Next.js Image component
- CSS-in-JS with zero runtime overhead
- Tree shaking for minimal bundle size

## 🚀 Deployment

### **Vercel (Recommended)**
1. Push your code to GitHub
2. Connect your repository to [Vercel](https://vercel.com)
3. Deploy with zero configuration

### **Netlify**
1. Build the project: `npm run build`
2. Deploy the `out` folder to [Netlify](https://netlify.com)

### **Manual Deployment**
\`\`\`bash
# Build for production
npm run build

# Start production server
npm start
\`\`\`

## 🔧 Scripts

\`\`\`bash
# Development server
npm run dev

# Production build
npm run build

# Start production server
npm start

# Lint code
npm run lint

# Type checking
npm run type-check
\`\`\`

## 📱 Browser Support

- **Chrome** 90+
- **Firefox** 88+
- **Safari** 14+
- **Edge** 90+

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the project
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 👨‍💻 About Me

**Varunesh T** - Full-Stack Developer & ML Enthusiast

- 🔭 Currently working on: **Resort Billing System**
- 🌱 Learning: **AWS, Docker, Model Deployment**
- 👯 Open to: **Collaborations & Mentorship**
- 💬 Ask me about: **React, Node.js, MySQL, UI/UX**
- ⚡ Fun fact: **Love experimenting with Photoshop manipulations**

## 🌐 Connect With Me

[![LinkedIn](https://img.shields.io/badge/LinkedIn-%230077B5.svg?logo=linkedin&logoColor=white)](https://linkedin.com/in/varunesh-t-4805b2345/)
[![Instagram](https://img.shields.io/badge/Instagram-%23E4405F.svg?logo=Instagram&logoColor=white)](https://instagram.com/_.varu_nesh._)
[![GitHub](https://img.shields.io/badge/GitHub-%23121011.svg?logo=github&logoColor=white)](https://github.com/varunesharasu)

## 🙏 Acknowledgments

- [Next.js Team](https://nextjs.org/) for the amazing framework
- [Vercel](https://vercel.com/) for seamless deployment
- [Framer Motion](https://www.framer.com/motion/) for beautiful animations
- [Tailwind CSS](https://tailwindcss.com/) for rapid styling
- [shadcn/ui](https://ui.shadcn.com/) for beautiful components

---

<div align="center">

**⭐ Star this repository if you found it helpful!**

Made with ❤️ by [Varunesh T](https://github.com/varunesharasu)

</div>
