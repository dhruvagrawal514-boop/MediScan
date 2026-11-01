# MediScan

**Scan a medicine strip with your phone camera and find out in seconds whether it looks genuine.**

[Live demo](https://mediscan-47870.web.app/)

Counterfeit and expired medicines are a real risk in India, and most buyers have no quick way to check what they are holding. MediScan reads the packaging with AI and flags anything suspicious.

## Features

- **Camera scan:** capture the pack directly in the browser
- **AI extraction:** reads brand name and strength, batch number, expiry date, manufacturer, MRP and active ingredients from the image
- **Verdict:** each check is marked pass, warning or fail, including seal condition (intact, absent or tampered)
- **Expiry validation:** automatically checks the printed expiry date
- **Doc AI assistant:** ask questions about a medicine
- **Nearest verified pharmacy** via Google Maps
- **One-tap reporting** of suspected counterfeits

## Built with

React, TypeScript, Vite, Tailwind CSS, shadcn/ui, React Router, TanStack Query, Google Gemini API, Firebase Hosting

## Run locally

```bash
npm install
npm run dev
```
