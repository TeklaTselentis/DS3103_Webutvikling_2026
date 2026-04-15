# DS3103_Webutvikling_2026
Webutvikling eksamen 2026

# AirIndustries — Webutvikling eksamen (DS3103 V2026)

En fullstack webapplikasjon for registrering og administrasjon av flymodeller. Brukere kan søke, legge til, redigere og slette fly, samt laste opp bilder tilknyttet hver modell.

## Oppsett

### Backend

```bash
cd backend
dotnet restore
dotnet run
```

API kjører på `http://localhost:5000`. Swagger-dokumentasjon tilgjengelig på `http://localhost:5000/swagger`.

### Frontend

```bash
cd frontend
npm install
npm run dev
```

Frontend kjører på `http://localhost:5173`.

## Krav
- .NET 8 SDK eller nyere
- Node.js 18+
