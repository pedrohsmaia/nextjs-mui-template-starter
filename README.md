# 🚀 Next.js MUI Template Starter

[![Next.js](https://img.shields.io/badge/Next.js-15.3.2-black?style=flat-square&logo=next.js)](https://nextjs.org/)
[![Material-UI](https://img.shields.io/badge/Material--UI-7.1.0-blue?style=flat-square&logo=mui)](https://mui.com/)
[![TypeScript](https://img.shields.io/badge/TypeScript-5.0-blue?style=flat-square&logo=typescript)](https://www.typescriptlang.org/)
[![React](https://img.shields.io/badge/React-19.0-blue?style=flat-square&logo=react)](https://reactjs.org/)

A modern, production-ready **Next.js 15** starter template with **Material-UI (MUI) 7**, **TypeScript**, and **Tailwind CSS**. Perfect for building responsive web applications, dashboards, portfolios, and enterprise-grade React applications.

## ✨ Features

- 🔥 **Next.js 15** with App Router and Turbopack
- 🎨 **Material-UI (MUI) 7** - Latest version with enhanced theming
- 📘 **TypeScript** - Full type safety and IntelliSense
- 🎯 **Tailwind CSS 4** - Utility-first CSS framework
- 🚀 **Emotion** - CSS-in-JS library for styling
- 📱 **Responsive Design** - Mobile-first approach
- 🎭 **Custom Theme** - Pre-configured MUI theme
- 🔧 **ESLint** - Code linting and formatting
- ⚡ **Turbopack** - Ultra-fast bundler for development
- 🌙 **Dark/Light Mode** - Built-in theme switching
- 📦 **Optimized Bundle** - Production-ready build configuration

## 🚀 Quick Start

This repository was bootstrapped with [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app).

### Prerequisites

- Node.js 18+ 
- npm, yarn, or pnpm

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/pedrohsmaia/nextjs-mui-template-starter.git
   cd portfolio
   ```

2. **Install dependencies**
   ```bash
   npm install
   # or
   yarn install
   # or
   pnpm install
   ```

3. **Start development server**
   ```bash
   npm run dev
   # or
   yarn dev
   # or
   pnpm dev
   ```

4. **Open your browser**
   Navigate to [http://localhost:3000](http://localhost:3000) to see your application.

## 📁 Project Structure

```
├── src/
│   ├── app/
│   │   ├── layout.tsx      # Root layout with MUI theme
│   │   ├── page.tsx        # Home page
│   │   └── globals.css     # Global styles
│   └── theme.ts            # MUI theme configuration
├── public/                 # Static assets
├── package.json           # Dependencies and scripts
├── tsconfig.json          # TypeScript configuration
├── next.config.ts         # Next.js configuration
└── tailwind.config.js     # Tailwind CSS configuration
```

## 🎨 Customization

### Theme Configuration

Customize your MUI theme in `src/theme.ts`:

```typescript
import { createTheme } from '@mui/material/styles';

const theme = createTheme({
  palette: {
    primary: {
      main: '#1976d2',
    },
    secondary: {
      main: '#dc004e',
    },
  },
});
```

### Adding Components

Create new components in the `src/components/` directory and import them in your pages.

## 📦 Built With

- **[Next.js](https://nextjs.org/)** - React framework for production
- **[Material-UI](https://mui.com/)** - React UI component library
- **[TypeScript](https://www.typescriptlang.org/)** - Typed JavaScript
- **[Tailwind CSS](https://tailwindcss.com/)** - Utility-first CSS framework
- **[Emotion](https://emotion.sh/)** - CSS-in-JS library

## 🛠️ Available Scripts

- `npm run dev` - Start development server with Turbopack
- `npm run build` - Build for production
- `npm run start` - Start production server
- `npm run lint` - Run ESLint

## 📱 Responsive Design

This template is built with mobile-first responsive design principles using:
- MUI's responsive breakpoints
- Tailwind CSS responsive utilities
- Flexible grid layouts
- Optimized typography scaling

## 🔧 Configuration

### Environment Variables

Create a `.env.local` file for environment-specific variables:

```env
NEXT_PUBLIC_APP_NAME=Your App Name
NEXT_PUBLIC_APP_URL=https://yourapp.com
```

### SEO Optimization

The template includes:
- Meta tags configuration
- Open Graph tags
- Twitter Card support
- Structured data markup
- Sitemap generation

## 🚀 Deployment

### Vercel (Recommended)

1. Push your code to GitHub
2. Connect your repository to [Vercel](https://vercel.com)
3. Deploy with zero configuration

### Other Platforms

- **Netlify**: `npm run build && npm run export`
- **AWS Amplify**: Connect your Git repository
- **Docker**: Use the included Dockerfile

## 🤝 Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- [Next.js Team](https://nextjs.org/) for the amazing framework
- [Material-UI Team](https://mui.com/) for the beautiful components
- [Vercel](https://vercel.com/) for the deployment platform

## 📞 Support

- 🐛 Issues: [GitHub Issues](https://github.com/pedrohsmaia/nextjs-mui-template-starter/issues)
- 💬 Discussions: [GitHub Discussions](https://github.com/pedrohsmaia/nextjs-mui-template-starter/discussions)

---

⭐ **Star this repository if it helped you build something awesome!**
