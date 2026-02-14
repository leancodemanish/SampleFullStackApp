# SampleFullStackApp

A full-stack web application with React frontend and .NET Web API backend.

## Structure

```
SampleFullStackApp/
├── Backend/      # .NET 10 Web API (port 5000)
├── frontend/     # React + Vite (port 5173)
└── README.md
```

## Prerequisites

- Node.js 25+
- .NET SDK 10+

## Getting Started

### Run Backend

```bash
cd Backend
dotnet run
```

API runs at: `http://localhost:5000`

### Run Frontend

```bash
cd frontend
npm run dev
```

App runs at: `http://localhost:5173`

## API Endpoints

| Method | Endpoint | Description |
|--------|----------|-------------|
| GET | /weatherforecast | Sample weather data |

## Development

### Backend
- Framework: ASP.NET Core 10
- Default template: Minimal API with WeatherForecast

### Frontend
- Framework: React 19
- Build tool: Vite
- Directory: `src/`
