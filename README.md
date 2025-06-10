# Hope Irving Church Website

A modern, responsive church website built with React, TypeScript, and Tailwind CSS.

## Features

- **Responsive Design**: Works perfectly on desktop, tablet, and mobile devices
- **Admin Dashboard**: Manage events, testimonials, livestream, and content
- **Livestream Integration**: YouTube livestream support with live indicators
- **Interactive Modals**: Prayer requests, giving, visit planning, and livestream viewing
- **Content Management**: Easy-to-use admin interface for updating church content
- **Modern UI**: Beautiful design with smooth animations and micro-interactions

## Technology Stack

- **Frontend**: React 18 with TypeScript
- **Styling**: Tailwind CSS with custom design system
- **Icons**: Lucide React
- **Build Tool**: Vite
- **Deployment**: Netlify

## Getting Started

1. Clone the repository:
```bash
git clone https://github.com/amith1551a/Fintechsolllc.git
cd Fintechsolllc
```

2. Install dependencies:
```bash
npm install
```

3. Start the development server:
```bash
npm run dev
```

4. Open your browser and navigate to `http://localhost:5173`

## Admin Access

The website includes an admin dashboard for managing content:

- **Username**: admin
- **Password**: HopeAdmin2024!

Or for pastoral access:
- **Username**: pastor  
- **Password**: HopeIrving2024!

## Project Structure

```
src/
├── components/           # React components
│   ├── admin/           # Admin dashboard components
│   ├── modals/          # Modal components
│   ├── About.tsx        # About section
│   ├── Events.tsx       # Events section
│   ├── Hero.tsx         # Hero section
│   ├── Header.tsx       # Navigation header
│   ├── Footer.tsx       # Footer
│   └── ...
├── types/               # TypeScript type definitions
├── utils/               # Utility functions
│   ├── auth.ts         # Authentication logic
│   └── storage.ts      # Local storage management
└── App.tsx             # Main application component
```

## Features Overview

### Public Features
- **Homepage**: Hero section with church information and service times
- **About**: Church mission, values, and pastoral message
- **Events**: Upcoming church events and weekly schedule
- **Testimonials**: Member stories and transformations
- **Connect**: Contact information and service details
- **Livestream**: Watch live services (when active)
- **Prayer Requests**: Submit prayer requests to the church
- **Giving**: Online giving interface (demo)
- **Visit Planning**: Plan your first visit with detailed form

### Admin Features
- **Event Management**: Create, edit, and delete church events
- **Testimonial Management**: Manage member stories and testimonials
- **Livestream Management**: Control live status and YouTube integration
- **Content Management**: Update hero text, about section, and church values
- **Secure Authentication**: Protected admin access

## Customization

### Colors
The website uses a custom color palette defined in `tailwind.config.js`:
- **Primary**: Blue tones for main branding
- **Gold**: Accent colors for highlights
- **Earth**: Warm tones for secondary elements

### Fonts
- **Sans-serif**: Inter for body text
- **Serif**: Playfair Display for headings

### Images
All images are sourced from Pexels and are properly licensed for use.

## Deployment

The website is configured for easy deployment to Netlify:

1. Build the project:
```bash
npm run build
```

2. Deploy the `dist` folder to your hosting provider

## Contributing

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Submit a pull request

## License

This project is licensed under the MIT License.

## Contact

For questions about this website, please contact:
- **Email**: d.king@hopeirving.org
- **Phone**: (214) 432-1599
- **Address**: 1646 W. Irving Blvd., Irving, TX 75061

---

Built with ❤️ for Hope Irving Church