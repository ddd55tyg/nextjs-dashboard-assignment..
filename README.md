

# Next.js Dashboard Assignment

## Overview
This project is a responsive dashboard built with *Next.js, **Tailwind CSS, **Redux Toolkit, and **Recharts*.  
It includes authentication, a dynamic data table with filtering and sorting, data export options (PDF/XLSX), and Docker setup for deployment.

## Features
- *User Authentication* (mocked API)
- *Dynamic Data Table* with sorting, filtering, and pagination
- *Chart Visualization* using Recharts
- *Data Export* to PDF and Excel
- *Dockerized Environment*
- *Mobile Responsive* with Tailwind CSS

## Implementation Approach
1. Used *Next.js* for server-side rendering and routing.
2. Managed global state using *Redux Toolkit*.
3. Implemented UI components with *Tailwind CSS*.
4. Integrated *Recharts* for data visualization.
5. Added *jsPDF* and *xlsx* libraries for exporting table data.
6. Created *Dockerfile* and *docker-compose.yml* for containerization.


## Setup Instructions
```bash
# Clone the repository
git clone https://github.com/ddd55tyg/nextjs-dashboard-assignment..
cd nextjs-dashboard-assignment

# Install dependencies
npm install

# Run locally
npm run dev

# Or run with Docker
docker-compose up --build
