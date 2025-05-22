# SentinelSecure Website

A modern, SEO-optimized website for SentinelSecure - a Managed Service Provider specializing in cybersecurity solutions. Built with Astro and Tailwind CSS v4 for excellent performance and modern design.

## 🚀 Features

- **Modern Tech Stack**: Built with Astro 5.x and Tailwind CSS v4
- **SEO Optimized**: Comprehensive meta tags, Open Graph, Twitter Cards, and JSON-LD structured data
- **Responsive Design**: Mobile-first responsive design that works on all devices
- **Fast Performance**: Static site generation with Astro for lightning-fast load times
- **Professional Design**: Clean, modern design with purple and pink gradient branding
- **Contact Form**: Functional contact form with validation
- **Accessibility**: WCAG compliant with proper semantic HTML and ARIA labels

## 📱 Pages

- **Home**: Hero section, services overview, statistics, and call-to-action
- **Services**: Detailed cybersecurity and managed IT services
- **About**: Company mission, team members, and core values
- **Contact**: Contact form, business information, and FAQs

## 🎨 Design System

### Colors
- **Primary**: Purple gradient (#9333ea to #db2777)
- **Secondary**: Pink accent colors
- **Text**: Gray scale (900, 700, 600, 500)
- **Background**: White with gradient accents

### Typography
- **Font Family**: Inter (Google Fonts)
- **Headings**: Bold weights with gradient text effects
- **Body**: Regular weight with proper line spacing

### Components
- **Buttons**: Primary and secondary button styles with hover effects
- **Cards**: Hover animations with shadow effects
- **Navigation**: Fixed header with mobile hamburger menu
- **Footer**: Multi-column layout with links and contact info

## 🛠️ Installation

1. **Clone the repository**
   ```bash
   git clone <repository-url>
   cd sentinelSecure-website
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Start development server**
   ```bash
   npm run dev
   ```

4. **Build for production**
   ```bash
   npm run build
   ```

5. **Preview production build**
   ```bash
   npm run preview
   ```

## 📁 Project Structure

```
/
├── public/
│   ├── SentinelSecure.svg       # Main logo
│   ├── favicon.ico              # Favicon
│   ├── android-chrome-*.png     # Android icons
│   ├── apple-touch-icon.png     # Apple touch icon
│   └── site.webmanifest         # Web app manifest
├── src/
│   ├── components/
│   │   ├── Header.astro         # Navigation header
│   │   └── Footer.astro         # Site footer
│   ├── layouts/
│   │   └── Layout.astro         # Base layout with SEO
│   ├── pages/
│   │   ├── index.astro          # Homepage
│   │   ├── services.astro       # Services page
│   │   ├── about.astro          # About page
│   │   └── contact.astro        # Contact page
│   └── styles/
│       └── global.css           # Global styles and Tailwind
├── astro.config.mjs             # Astro configuration
├── tailwind.config.js           # Tailwind configuration
└── package.json                 # Dependencies and scripts
```

## 🎯 SEO Features

### Meta Tags
- Comprehensive title and description tags
- Open Graph meta tags for social media
- Twitter Card support
- Canonical URLs
- Proper robots meta tags

### Structured Data
- JSON-LD structured data for organization
- Local business schema
- Service type definitions
- Contact information markup

### Performance
- Static site generation
- Optimized images and assets
- Minimal JavaScript bundle
- Fast CSS delivery

## 📧 Contact Form

The contact form includes:
- Client-side validation
- Required field checking
- Service selection dropdown
- Consent checkbox
- Success/error messaging

**Note**: The form currently shows a success alert. In production, you'll need to:
1. Set up a backend endpoint to handle form submissions
2. Configure email delivery (SMTP, SendGrid, etc.)
3. Add proper error handling and user feedback

## 🚀 Deployment

This is a static site that can be deployed to any static hosting service:

- **Netlify**: Connect your git repository for automatic deployments
- **Vercel**: Import project for seamless deployment
- **GitHub Pages**: Use GitHub Actions for automated builds
- **AWS S3**: Upload build files to S3 bucket
- **Any CDN**: Deploy built files to your preferred hosting

### Build Command
```bash
npm run build
```

### Output Directory
```
dist/
```

## 🔧 Customization

### Branding
- Update colors in `tailwind.config.js`
- Replace logo files in `public/` directory
- Modify company information in page content

### Content
- Edit page content in respective `.astro` files
- Update contact information in Layout.astro and contact page
- Modify services and team information as needed

### Styling
- Customize styles in `src/styles/global.css`
- Update component classes in individual files
- Modify responsive breakpoints in Tailwind config

## 📝 License

This project is proprietary software for SentinelSecure. All rights reserved.

## 🤝 Contributing

This is a private project for SentinelSecure. For modifications or updates, please contact the development team.

---

**Built with ❤️ for SentinelSecure**

```sh
npm create astro@latest -- --template minimal
```

[![Open in StackBlitz](https://developer.stackblitz.com/img/open_in_stackblitz.svg)](https://stackblitz.com/github/withastro/astro/tree/latest/examples/minimal)
[![Open with CodeSandbox](https://assets.codesandbox.io/github/button-edit-lime.svg)](https://codesandbox.io/p/sandbox/github/withastro/astro/tree/latest/examples/minimal)
[![Open in GitHub Codespaces](https://github.com/codespaces/badge.svg)](https://codespaces.new/withastro/astro?devcontainer_path=.devcontainer/minimal/devcontainer.json)

> 🧑‍🚀 **Seasoned astronaut?** Delete this file. Have fun!

## 🚀 Project Structure

Inside of your Astro project, you'll see the following folders and files:

```text
/
├── public/
├── src/
│   └── pages/
│       └── index.astro
└── package.json
```

Astro looks for `.astro` or `.md` files in the `src/pages/` directory. Each page is exposed as a route based on its file name.

There's nothing special about `src/components/`, but that's where we like to put any Astro/React/Vue/Svelte/Preact components.

Any static assets, like images, can be placed in the `public/` directory.

## 🧞 Commands

All commands are run from the root of the project, from a terminal:

| Command                   | Action                                           |
| :------------------------ | :----------------------------------------------- |
| `npm install`             | Installs dependencies                            |
| `npm run dev`             | Starts local dev server at `localhost:4321`      |
| `npm run build`           | Build your production site to `./dist/`          |
| `npm run preview`         | Preview your build locally, before deploying     |
| `npm run astro ...`       | Run CLI commands like `astro add`, `astro check` |
| `npm run astro -- --help` | Get help using the Astro CLI                     |

## 👀 Want to learn more?

Feel free to check [our documentation](https://docs.astro.build) or jump into our [Discord server](https://astro.build/chat).
