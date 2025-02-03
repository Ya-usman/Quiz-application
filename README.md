# React Quiz Application

A modern, interactive quiz application built with React, TypeScript, and Tailwind CSS. Test your knowledge with timed multiple-choice questions and track your progress!

Test the app : https://ornate-marzipan-f6ea82.netlify.app

## Features

- 📝 Multiple choice questions with automatic scoring
- ⏱️ 30-second timer for each question
- 🎯 Real-time score tracking
- 📊 Final results screen with percentage score
- 🎨 Modern, responsive UI with Tailwind CSS
- 🔄 Option to restart the quiz
- 💻 Built with TypeScript for type safety

## Tech Stack

- React 18
- TypeScript
- Tailwind CSS
- Vite
- Lucide React (for icons)

## Getting Started

### Prerequisites

- Node.js (v14 or higher)
- npm or yarn

### Installation

1. Clone the repository
```bash
git clone [your-repository-url]
```

2. Install dependencies
```bash
npm install
```

3. Start the development server
```bash
npm run dev
```

The application will be available at `http://localhost:5173`

### Building for Production

To create a production build:
```bash
npm run build
```

## Project Structure

```
src/
├── components/        # React components
│   ├── Question.tsx  # Question component
│   └── Result.tsx    # Results component
├── data/
│   └── questions.ts  # Quiz questions data
├── types/
│   └── quiz.ts       # TypeScript interfaces
├── App.tsx           # Main application component
└── main.tsx         # Application entry point
```

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - Yahaya Usman

## Acknowledgments

- Icons provided by [Lucide React](https://lucide.dev)
- Styling powered by [Tailwind CSS](https://tailwindcss.com)
