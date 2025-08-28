<div align="center">

# 📄 CV as code - YAML, Astro and TailwindCSS

[![CV Demo](https://img.shields.io/badge/CV-Live%20Demo-blue?style=for-the-badge&logo=astro)](https://cv.teixe.es)
[![GitHub License](https://img.shields.io/github/license/jorgeteixe/cv?style=for-the-badge)](LICENSE)
[![GitHub Stars](https://img.shields.io/github/stars/jorgeteixe/cv?style=for-the-badge)](https://github.com/jorgeteixe/cv/stargazers)
[![GitHub Forks](https://img.shields.io/github/forks/jorgeteixe/cv?style=for-the-badge)](https://github.com/jorgeteixe/cv/fork)

</div>

A minimalist, print-friendly CV template built with **Astro** and **TailwindCSS**. Perfect for developers who want a clean, professional resume that looks great both on screen and on paper.

## ✨ Features

- 🎨 **Minimalist Design** - Clean, professional layout with monospace fonts
- 🖨️ **Print Optimized** - Looks perfect when you hit `Ctrl+P`
- 📱 **Responsive** - Works great on all devices
- ⚡ **Fast** - Built with Astro for lightning-fast performance
- 🔧 **Easy to Customize** - Just edit the YAML file with your info

## 🚀 Quick Start

1. **Fork this repository**
2. **Clone your fork**

   ```bash
   git clone https://github.com/yourusername/cv.git
   cd cv
   ```

3. **Install dependencies**

   ```bash
   pnpm install
   # or npm install
   ```

4. **Edit your information**

   ```bash
   # Edit the CV data file
   vim src/data/cv.yaml
   ```

5. **Start developing**

   ```bash
   pnpm dev
   # or npm run dev
   ```

6. **Build for production**
   ```bash
   pnpm build
   # or npm run build
   ```

## 📝 Customization

All your CV information is stored in `src/data/cv.yaml`. Just update this file with your details:

- ✏️ Personal information (name, location, contacts)
- 💼 Work experience with highlights and technologies
- 🎓 Education background
- 🛠️ Skills organized by categories
- 🚀 Projects with descriptions and tech stacks

The template automatically generates a beautiful CV from your YAML data!

## 🏗️ Tech Stack

- **[Astro](https://astro.build/)** - Static site generator
- **[TailwindCSS](https://tailwindcss.com/)** - Utility-first CSS framework
- **[Roboto Mono](https://fonts.google.com/specimen/Roboto+Mono)** - Monospace font
- **[YAML](https://yaml.org/)** - Human-readable data format
- **TypeScript** - Type-safe JavaScript

## 🎨 Design Philosophy

This CV template follows these principles:

- **Minimalism** - Less is more. Focus on content, not decoration
- **Readability** - Easy to scan for recruiters and ATS systems
- **Print-First** - Designed to look professional when printed
- **Accessibility** - High contrast, clear typography
- **Monospace** - Consistent character spacing for a tech-focused aesthetic

## 🤝 Contributing

Found a bug? Have a cool feature idea? Contributions are welcome!

1. Fork the project
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📄 License

This project is open source and available under the [MIT License](LICENSE).
