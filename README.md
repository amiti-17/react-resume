# React Resume - Tymofii Shkandiuk

A modern, responsive resume built with React and TypeScript, showcasing my professional experience, skills, and projects as a Full Stack Web Developer.

## 🚀 Live Demo

[View Live Resume](https://heartfelt-cheesecake-ea54e7.netlify.app)

## ✨ Features

- **Modern Tech Stack**: Built with React, TypeScript, and CSS Modules
- **Responsive Design**: Optimized for desktop and mobile viewing
- **Component Architecture**: Modular, maintainable codebase following React best practices
- **Continuous Deployment**: Auto-deploys from GitHub via Netlify

## 📁 Project Structure

```
src/
├── components/
│   ├── common/          # Shared components
│   │   └── ListRenderer.tsx
│   ├── Layout/          # Layout wrapper
│   ├── Sidebar/         # Sidebar sections
│   │   ├── index.tsx
│   │   ├── Profile.tsx
│   │   ├── Contact.tsx
│   │   ├── Skills.tsx
│   │   ├── Education.tsx
│   │   └── Hobbies.tsx
│   └── MainContent/     # Main content sections
│       ├── index.tsx
│       ├── About.tsx
│       ├── Experience.tsx
│       └── Projects.tsx
├── data/
│   └── resumeData.ts    # Resume data source
└── index.css            # Global styles & CSS variables
```

## 🎨 Customization

To customize with your own information:

1. Edit `src/data/resumeData.ts` with your personal information
2. Replace `public/profile.jpg` with your photo
3. Update colors in `src/index.css` CSS variables
4. Modify component styles in respective `.module.css` files

## 🚀 Deployment

This project is configured for deployment on Netlify:

1. Push to GitHub
2. Connect repository to Netlify
3. Netlify auto-detects build settings from `netlify.toml`
4. Continuous deployment triggers on every commit to `main`

### Build Settings (configured in netlify.toml)
- **Build command**: `npm run build`
- **Publish directory**: `build`
- **Node version**: 16+

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 👤 Author

**Tymofii Shkandiuk**
- GitHub: [@amiti-17](https://github.com/amiti-17)
- LinkedIn: [Tymofii Shkandiuk](https://www.linkedin.com/in/97706971)
- Email: timjobit@gmail.com

