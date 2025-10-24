# Learning Support Volunteers Website

A modern, responsive website for a volunteer group that supports foreign residents in Japan with learning assistance. Built with Next.js, React, TypeScript, and Tailwind CSS.

## Features

- 🌍 **Multi-language Support**: Japanese, English, Chinese, and Vietnamese
- 📱 **Responsive Design**: Works perfectly on desktop, tablet, and mobile devices
- 🎨 **Modern UI**: Clean, accessible design with soft colors and large, readable text
- ⚡ **Fast Performance**: Built with Next.js for optimal loading speeds
- ♿ **Accessible**: Designed with accessibility in mind for all age groups

## Sections

1. **Header**: Navigation menu and language switcher
2. **Hero Section**: Main call-to-action with two primary buttons
3. **About Us**: Group introduction and vision
4. **Activities**: Card layout showcasing main activities
5. **Join Us**: Two subsections for learners and volunteers
6. **Contact**: Contact form with dropdown selection
7. **Footer**: Contact information and social media links

## Tech Stack

- **Framework**: Next.js 14 with App Router
- **Language**: TypeScript
- **Styling**: Tailwind CSS
- **Font**: Inter (Google Fonts)
- **Icons**: Heroicons (SVG)

## Getting Started

### Prerequisites

- Node.js 18+ 
- npm or yarn

### Installation

1. **Clone or download the project files**

2. **Install dependencies**:
   ```bash
   npm install
   # or
   yarn install
   ```

3. **Run the development server**:
   ```bash
   npm run dev
   # or
   yarn dev
   ```

4. **Open your browser** and navigate to `http://localhost:3000`

## Project Structure

```
volunteer-support-site/
├── src/
│   ├── app/
│   │   ├── globals.css          # Global styles and Tailwind imports
│   │   ├── layout.tsx           # Root layout component
│   │   └── page.tsx             # Main page component
│   └── components/
│       ├── Header.tsx           # Navigation and language switcher
│       ├── Hero.tsx             # Hero section with main CTA
│       ├── About.tsx            # About us section
│       ├── Activities.tsx       # Activities showcase
│       ├── JoinUs.tsx           # Join us section
│       ├── Contact.tsx          # Contact form
│       └── Footer.tsx           # Footer with contact info
├── package.json                 # Dependencies and scripts
├── tailwind.config.js          # Tailwind CSS configuration
├── next.config.js              # Next.js configuration
├── tsconfig.json               # TypeScript configuration
└── README.md                   # This file
```

## Customization

### Colors
The color scheme can be customized in `tailwind.config.js`:
- Primary colors (blue): Used for main actions and accents
- Secondary colors (green): Used for secondary actions and highlights

### Content
All text content is stored in language-specific objects within each component. To modify content:
1. Find the component file
2. Locate the content object (e.g., `heroContent`, `aboutContent`)
3. Update the text for your desired language

### Images
Currently using placeholder elements. To add real images:
1. Place images in `public/` directory
2. Replace placeholder divs with `<Image>` components
3. Update alt text for accessibility

### Contact Form
The contact form currently logs to console. To make it functional:
1. Add form submission logic in `Contact.tsx`
2. Connect to your preferred backend service
3. Add email service integration (e.g., SendGrid, Mailgun)

## Deployment

### Vercel (Recommended)
1. Push code to GitHub
2. Connect repository to Vercel
3. Deploy automatically

### Other Platforms
The project can be deployed to any platform that supports Next.js:
- Netlify
- AWS Amplify
- DigitalOcean App Platform
- Traditional hosting with `npm run build`

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## Contributing

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Test thoroughly
5. Submit a pull request

## License

This project is open source and available under the [MIT License](LICENSE).

## Support

For questions or support, please contact the development team or create an issue in the repository.

---

**Note**: This is a template website. Please customize all content, images, and contact information to match your specific volunteer group's needs.
