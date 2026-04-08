# Resume Matcher

A modern web application that helps match resumes with job descriptions using intelligent ATS (Applicant Tracking System) analysis.

## Features

- 📄 **Resume Upload & Analysis** - Upload resumes and get instant ATS compatibility analysis
- 🎯 **Job Description Matching** - Match your resume against job descriptions
- 📊 **Detailed Analytics** - View matching scores and improvement suggestions
- 🎨 **Modern UI** - Clean, responsive interface built with React and Tailwind CSS
- ⚡ **Fast Performance** - Built with Vite for lightning-fast development and production builds

## Tech Stack

- **Frontend**: React 18 + TypeScript
- **Build Tool**: Vite 5
- **Styling**: Tailwind CSS
- **Icons**: Lucide React
- **Linting**: ESLint

## Prerequisites

- Node.js (v16 or higher)
- npm or yarn

## Installation

```bash
# Clone the repository
git clone https://github.com/KashishPanchal/resume_maker_web.git
cd resumeMatcher-main

# Install dependencies
npm install
```

## Development

Start the development server:

```bash
npm run dev
```

The application will be available at `http://localhost:5173/`

## Building for Production

```bash
npm run build
```

## Available Scripts

- `npm run dev` - Start development server
- `npm run build` - Build for production
- `npm run preview` - Preview production build locally
- `npm run lint` - Run ESLint to check code quality

## Project Structure

```
├── src/
│   ├── components/          # React components
│   │   ├── ATSInfo.tsx
│   │   ├── Features.tsx
│   │   ├── Footer.tsx
│   │   ├── Header.tsx
│   │   ├── Hero.tsx
│   │   ├── HowItWorks.tsx
│   │   ├── Pricing.tsx
│   │   ├── ResultsSection.tsx
│   │   └── UploadSection.tsx
│   ├── App.tsx              # Main App component
│   ├── main.tsx             # Entry point
│   └── index.css            # Global styles
├── backend/                 # Backend resources
├── index.html               # HTML template
├── vite.config.ts           # Vite configuration
├── tailwind.config.js       # Tailwind CSS configuration
└── package.json             # Project dependencies
```

## Features Breakdown

### Resume Upload Section
- Drag and drop interface for easy file uploads
- Support for multiple resume formats
- Real-time validation

### ATS Analysis
- Keyword matching against job descriptions
- Score calculation based on relevant skills
- Actionable recommendations for improvement

### How It Works
- Step-by-step guide for users
- Interactive demonstration
- Best practices for resume optimization

### Pricing
- Flexible pricing tiers
- Feature comparison
- Enterprise options

## Deployment

The application can be deployed to various platforms:

### Vercel (Recommended)
```bash
npm run build
# Deploy the dist/ folder to Vercel
```

### Netlify
- Connect your GitHub repository
- Set build command: `npm run build`
- Set publish directory: `dist/`

### Traditional Server
```bash
npm run build
# Copy the dist/ folder to your web server
```

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is licensed under the MIT License.

## Contact

For questions or support, please reach out through the GitHub issues page.

---

**Made with ❤️ by Kashish Panchal**
