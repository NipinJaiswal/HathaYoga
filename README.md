# Hatha Yoga by Sadhguru

![Hatha Yoga](https://images.unsplash.com/photo-1506126613408-eca07ce68773?ixlib=rb-1.2.1&auto=format&fit=crop&w=800&q=80)

A responsive web application showcasing Hatha Yoga based on Sadhguru's teachings with information sections and newsletter signup.

## About

This project aims to build a comprehensive platform for learning about Hatha Yoga through Sadhguru's teachings. The application provides information about the origins, science, and benefits of yoga, as well as available programs and resources.

## Features

- Responsive design that works on mobile, tablet, and desktop
- Informative sections about different aspects of Hatha Yoga
- Newsletter subscription functionality
- Program listings with details
- Testimonials from practitioners

## Tech Stack

- **Frontend**: React, Tailwind CSS, shadcn/ui components
- **Backend**: Express.js
- **State Management**: React Query
- **Forms**: React Hook Form with Zod validation
- **Storage**: In-memory database (can be extended to PostgreSQL)

## Getting Started

### Prerequisites

- Node.js (v20.x recommended)
- npm (v10.x recommended)

### Installation

1. Clone the repository:
   ```
   git clone <repository-url>
   ```

2. Install dependencies:
   ```
   npm install
   ```

3. Start the development server:
   ```
   npm run dev
   ```

4. Open your browser and navigate to:
   ```
   http://localhost:5000
   ```

## Project Structure

```
.
├── client/              # Frontend code
│   ├── src/
│   │   ├── components/  # Reusable UI components
│   │   ├── hooks/       # Custom React hooks
│   │   ├── lib/         # Utility functions
│   │   ├── pages/       # Page components
│   │   └── App.tsx      # Main component
│   └── index.html       # HTML entry point
├── server/              # Backend code
│   ├── index.ts         # Server entry point
│   ├── routes.ts        # API routes
│   ├── storage.ts       # Data storage
│   └── vite.ts          # Vite configuration
├── shared/              # Shared code
│   └── schema.ts        # Data models
└── comprehensiveDoc.md  # Detailed documentation
```

## Future Development

See [comprehensiveDoc.md](./comprehensiveDoc.md) for detailed plans on future development.

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgements

- [Sadhguru](https://isha.sadhguru.org/) for the teachings and inspiration
- [Tailwind CSS](https://tailwindcss.com/) for styling
- [shadcn/ui](https://ui.shadcn.com/) for UI components
- [React](https://reactjs.org/) for the UI library
- [Express.js](https://expressjs.com/) for the server