# Segunda Casa - Property Management System

A modern property management system built with a comprehensive tech stack:

## Frontend
- React with TypeScript
- Vite for build tooling
- TailwindCSS for styling
- React Query for data fetching
- Zustand for state management
- TensorFlow.js for client-side ML features
- Recharts for data visualization

## Backend (Separate Repository)
- Java/Kotlin with Spring Boot
- PostgreSQL for main database
- Redis for caching
- RabbitMQ for message queuing

## Data Analysis (Separate Repository)
- Python with pandas, numpy, scikit-learn
- R for statistical analysis
- Jupyter Notebooks for data exploration
- TensorFlow/PyTorch for ML models

## Features
- Real-time availability tracking
- Smart pricing recommendations
- Predictive maintenance
- Customer behavior analysis
- Automated booking management
- Dynamic pricing optimization

## Getting Started

1. Clone the repository
2. Install dependencies:
   ```bash
   npm install
   ```
3. Start the development server:
   ```bash
   npm run dev
   ```

## Architecture

The system follows a microservices architecture:
- Frontend (React) communicates with backend services via REST APIs
- Backend services are containerized and orchestrated with Kubernetes
- ML models are served via dedicated API endpoints
- Real-time features use WebSocket connections
- Data analysis pipeline runs on scheduled intervals

## Contributing

Please read CONTRIBUTING.md for details on our code of conduct and the process for submitting pull requests.