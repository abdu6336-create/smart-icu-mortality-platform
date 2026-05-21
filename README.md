# Smart ICU Mortality Prediction Platform
## منصة القيادة الصحية الذكية للوفيات

AI-powered executive healthcare intelligence platform for ICU mortality risk prediction, operational monitoring, smart alerts, and executive decision support.

## Overview
This project is an executive prototype for Jazan Health Cluster designed to support healthcare leadership and ICU teams through predictive analytics, mortality trend monitoring, smart risk scoring, hospital risk matrix, patient demographic analysis, and executive reporting.

## Features
- ICU mortality risk prediction
- Executive dashboard
- Hospital risk matrix
- Smart alerts
- 72-hour expected mortality forecast
- Mortality trend analysis
- Patient age and gender distribution
- Data quality score
- Executive quick brief
- Arabic and English voice narration
- Fullscreen cinematic presentation mode
- Excel import support
- Local data save and restore
- PDF export through browser print

## Current Status
This is an Executive Prototype / Proof of Concept version.

Suitable for:
- Executive presentation
- Innovation showcase
- Initial approval
- Demo before enterprise rebuild

Not yet production-ready.

## Recommended Enterprise Architecture
```text
frontend/     React + Vite
backend/      Node.js + Express
database/     SQL Server
ai-engine/    Python / Machine Learning
storage/      Internal server storage
security/     Authentication, RBAC, Audit Logs
```

## Future Roadmap
1. Convert HTML prototype to React
2. Build Node.js API layer
3. Add SQL Server database
4. Add authentication and role permissions
5. Add audit logs
6. Add real-time updates
7. Add AI model service
8. Add hospital-level access control
9. Add secure file upload
10. Deploy to Windows Server

## Prototype Technologies
- HTML5
- CSS3
- JavaScript
- XLSX.js
- SVG Charts
- Web Speech API
- Browser Local Storage

## Important Note
Do not use this prototype with sensitive production patient data before adding backend security, authentication, database governance, and audit logs.

## Author
Prepared by: Abdulmajeed Alzughaibi  
Health Informatics Specialist | Data Analyst | Healthcare Systems Developer


## Demo Login

Default prototype login credentials:

```text
Username: admin
Password: 1234
```

Alternative:

```text
Username: abdulmajeed
Password: 2026
```

> This login is for executive demo only. Production deployment requires backend authentication and role-based access control.

## Settings Page

The platform includes a second settings page:
- Change password
- Disable the entire system without deleting saved data
- Reactivate the system without data loss
- Logout

The password is stored locally in the browser for prototype use. Production requires backend authentication and RBAC.


## Calculation Methodology Page

The platform includes a third page explaining how each dashboard indicator is calculated:
- Overall risk score
- 72-hour expected mortality
- ICU occupancy
- Response time
- Hospital risk matrix
- Demographics
- Executive alerts
- Trend charts
- Executive brief
- Voice narration
