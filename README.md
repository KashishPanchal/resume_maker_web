# Resume Matcher

A modern web application that helps job seekers optimize their resumes by analyzing them against job descriptions using ATS (Applicant Tracking System) optimization techniques.

## Features

- **Resume Upload**: Upload your resume in multiple formats
- **Job Description Analysis**: Paste or upload job descriptions for position matching
- **ATS Optimization**: Get AI-powered recommendations to improve your resume's ATS compatibility
- **Keyword Matching**: Identify missing keywords and skills from job descriptions
- **Real-time Feedback**: Instant analysis and suggestions for improvements
- **Responsive Design**: Works seamlessly on desktop and mobile devices

## Tech Stack

### Frontend
- **React 18.3.1** - UI library
- **TypeScript 5.5.3** - Type safety
- **Vite 5.4.2** - Build tool and dev server
- **Tailwind CSS 3.4.1** - Styling
- **Lucide React 0.344.0** - Icon components

### Backend
- **Python** - Job scraper and data processing
- **Flask/Django** (optional) - API server

## Getting Started

### Prerequisites
- Node.js 16+ 
- npm or yarn
- Python 3.8+ (for backend)

### Installation

1. **Clone the repository**
```bash
git clone https://github.com/KashishPanchal/resume_maker_web.git
cd resumeMatcher-main
```

2. **Install dependencies**
```bash
npm install
```

3. **Start the development server**
```bash
npm run dev
```

The application will be available at `http://localhost:5173/`

## Available Scripts

- `npm run dev` - Start the development server
- `npm run build` - Build for production
- `npm run lint` - Run ESLint
- `npm run preview` - Preview the production build locally

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
│   ├── App.tsx             # Main app component
│   ├── main.tsx            # Entry point
│   └── index.css           # Global styles
├── backend/                 # Backend code
├── public/                  # Static assets
├── tailwind.config.js       # Tailwind configuration
├── tsconfig.json            # TypeScript configuration
├── vite.config.ts           # Vite configuration
└── package.json             # Project dependencies
```

## How It Works

1. **Upload Resume** - Users upload their resume (PDF, DOCX, TXT)
2. **Enter Job Description** - Paste the target job posting
3. **Analysis** - The app analyzes the resume against the job description
4. **Get Recommendations** - Receive AI-powered suggestions for optimization
5. **Improve** - Update resume based on feedback and retest

## Features in Detail

### Resume Analysis
- Extracts key information from resumes
- Identifies skills, experience, and education
- Analyzes formatting and structure

### ATS Compatibility
- Checks for ATS-unfriendly elements
- Suggests format improvements
- Validates keyword presence

### Job Matching
- Compares resume against job requirements
- Identifies skill gaps
- Suggests keyword additions

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

This project is open source and available under the MIT License.

## Contact & Support

For issues, feature requests, or questions:
- Open an issue on GitHub
- Contact: KashishPanchal

## Roadmap

- [ ] Advanced PDF parsing
- [ ] Multi-language support
- [ ] Resume templates
- [ ] Interview prep module
- [ ] Job board integration
- [ ] LinkedIn integration

---

**Happy resume optimizing! 🚀**
