# GrowFi - Investment Portfolio Manager

GrowFi is a modern web application that provides a unified platform for managing and optimizing investment portfolios across multiple Indian financial platforms including Zerodha, MF Central, and Angel One. This project is currently in active development.

## Live Demo

Check out the live demo: [GrowFi App Demo](https://growfi-frontend.vercel.app)

## Project Vision

GrowFi aims to solve a common challenge for Indian investors - managing investments spread across different platforms. By providing a unified dashboard and powerful analytics tools, GrowFi helps investors make better-informed decisions and optimize their portfolio performance.

## Key Features

- **Unified Dashboard**: View all your investments in one place with detailed analytics
- **AI-Powered Insights**: Get personalized recommendations and risk assessments
- **Portfolio Comparison**: Compare different funds and stocks side by side
- **Trade Execution**: Buy, sell, or set up SIPs directly from the platform
- **Responsive Design**: Works seamlessly on desktop, tablet, and mobile devices

## Technology Stack

- **Frontend**: Next.js 14 (App Router), TypeScript, Tailwind CSS
- **State Management**: Context API with React Hooks
- **UI Animations**: CSS Transitions and Animations
- **Deployment**: Vercel
- **Authentication**: JWT-based authentication (currently simulated for demo)

## Development Status

This project is currently in **development/prototype phase**. The following components are functional:

- ✅ User authentication (simulated)
- ✅ Dashboard with portfolio overview
- ✅ Investment comparison tool
- ✅ Trading interface
- ✅ Portfolio insights
- ⚠️ API integration (in progress)
- ⚠️ Real-time data feeds (in progress)

## Getting Started

### Prerequisites

- Node.js 18.17 or later
- npm or yarn

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/Swayam-code/GrowFi-Frontend.git
   cd GrowFi-Frontend
   ```

2. Install dependencies:
   ```bash
   npm install
   # or
   yarn install
   ```

3. Run the development server:
   ```bash
   npm run dev
   # or
   yarn dev
   ```

4. Open [http://localhost:3000](http://localhost:3000) in your browser to see the application.

## Project Structure

```
GrowFi-Frontend/
├── public/             # Static assets
├── src/
│   ├── app/            # Next.js app router
│   │   ├── compare/    # Fund comparison page
│   │   ├── dashboard/  # Main portfolio dashboard
│   │   ├── login/      # Authentication pages
│   │   ├── signup/     # User registration
│   │   ├── trade/      # Buy/Sell execution
│   │   ├── layout.tsx  # Root layout
│   │   └── page.tsx    # Landing page
│   ├── components/     # Reusable UI components
│   ├── context/        # React context providers
│   └── styles/         # Global styles
├── tailwind.config.ts  # Tailwind CSS configuration
└── next.config.ts      # Next.js configuration
```

## Demo Access

Use the following credentials to access the demo:
- **Email**: demo@example.com
- **Password**: Any password will work

## Roadmap

- **Q2 2024**: 
  - Complete UI refinements
  - API integration with financial platforms
  - User profile management

- **Q3 2024**:
  - Advanced portfolio analysis
  - Real-time transaction tracking
  - Mobile responsiveness improvements

- **Q4 2024**:
  - SIP automation features
  - Tax optimization tools
  - Portfolio performance predictions

## Contributing

Contributions are welcome! If you're interested in improving GrowFi:

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## Technical Notes

- This project uses Next.js App Router with React Server Components
- For local development, make sure to check the required environment variables in `.env.example`
- The application has ESLint and TypeScript build errors disabled in the production environment
- React Suspense is used for handling component loading states

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Contact

For any inquiries about this project, please reach out to the project maintainer.
