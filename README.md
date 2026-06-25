# SRMSS – Smart Route Management & Scheduling System (Frontend)

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![React](https://img.shields.io/badge/React-18-blue)](https://reactjs.org/)
[![TypeScript](https://img.shields.io/badge/TypeScript-5.0-blue)](https://www.typescriptlang.org/)
[![Tailwind CSS](https://img.shields.io/badge/Tailwind-3.0-38B2AC)](https://tailwindcss.com/)

A modern web application for bus transport management – admin dashboard and driver portal.

## 🚀 Features

### Admin Portal
- **Dashboard** – real‑time statistics, revenue, fleet utilisation.
- **Route Management** – create/edit routes, add stops, calculate distance using OpenRouteService.
- **Bus & Driver Management** – CRUD operations, status tracking, license expiry alerts.
- **Schedules** – single or multi‑trip schedule creation with conflict detection.
- **Live Bus Tracker** – map‑based view of all active buses (uses Leaflet + ORS geocoding).
- **Ticketing** – book, cancel, mark tickets as used; occupancy tracking.
- **Fuel Logs & Maintenance** – record fuel purchases and service history.
- **Reports** – generate fuel, revenue, operational reports (PDF/Excel).
- **Admin Users** – manage system administrators with role‑based permissions.
- **Settings** – profile, appearance, notifications, system preferences.

### Driver Portal
- **Login** – using email + NIC number (JWT authentication).
- **Current Schedule** – view assigned route, stops, progress.
- **Mark Arrival** – double‑tap confirmation, automatically updates schedule current/next stop.
- **Live Map** – displays bus position (if GPS available) and upcoming stop.
- **Shift End** – logout and session termination.

## 🛠️ Tech Stack

| Category          | Technology                                                                 |
|-------------------|----------------------------------------------------------------------------|
| Framework         | React 18                                                                    |
| Language          | TypeScript                                                                 |
| Build Tool        | Vite                                                                       |
| Styling           | Tailwind CSS + Custom colour palette                                       |
| Routing           | React Router v6                                                            |
| State Management  | React Context (AuthContext, DriverContext)                                 |
| HTTP Client       | Axios with interceptors (admin & driver token separation)                  |
| Maps              | Leaflet + OpenRouteService (geocoding and distance)                        |
| Charts            | Recharts (dashboard charts)                                                |
| Icons             | Remix Icon                                                                 |
| Notifications     | react‑hot‑toast                                                            |
| PDF/Excel Export  | (backend generates, frontend downloads)                                    |

## 📁 Project Structure
