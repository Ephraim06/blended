# 💅 Bare & Blended by Ropa - Nail Business Tracker

A modern, full-featured Progressive Web App (PWA) for nail technicians to track clients, appointments, and revenue in USD. Built with a clean, Instagram-inspired design featuring dark/light mode, offline capability, and local storage persistence.

![Bare & Blended](https://i.ibb.co/svkdHgKn/bare-n-blended-modified.png)

## ✨ Features

### Core Functionality
- **Client Management** - Add, view, and delete clients
- **Appointment Tracking** - Schedule appointments with date, amount, and payment status
- **Revenue Dashboard** - Real-time total revenue, pending payments, monthly earnings
- **Payment Confirmation** - One-click "Pay" button to confirm client payments
- **Today's Overview** - Quick view of daily appointments
- **Transaction History** - Complete list of all appointments sorted by date

### UI/UX
- **Dark/Light Theme** - Toggle between modes with persistent preference
- **Clean, Modern Design** - Solid colors, subtle shadows, no gradients
- **Mobile-First Responsive** - Optimized for all screen sizes
- **Smooth Animations** - Micro-interactions for a polished feel
- **Modal Interfaces** - Clean modals for adding appointments and confirming deletions
- **Success States** - Visual feedback after completing actions
- **SVG Icons Only** - No emoji, professional iconography throughout

### Technical Features
- **Full PWA Support** - Installable on mobile devices, works offline
- **Local Storage** - All data persists in browser localStorage
- **Service Worker** - Caches assets for offline functionality
- **No Dependencies** - Single HTML file with Tailwind CSS CDN
- **Zero Backend** - Runs entirely in the browser

## 🚀 Quick Start

1. **Download the HTML file** or clone this repository
2. **Open in browser** - Double-click the file or serve with any web server
3. **Start tracking** - Add your first client and appointment

For mobile installation:
- **iOS Safari**: Tap Share → "Add to Home Screen"
- **Android Chrome**: Tap menu → "Install App" or "Add to Home Screen"

## 📱 PWA Installation

The app is a full Progressive Web App:

1. Open the site in your mobile browser
2. The browser will prompt to install (or use the menu)
3. Once installed, it works like a native app with offline support
4. The app icon appears on your home screen

**Offline Support**: The service worker caches essential assets, allowing the app to function without an internet connection. Data is stored locally.

## 🎨 Design System

### Colors
| Color | Hex | Usage |
|-------|-----|-------|
| Blend Brown | `#945034` | Primary brand color, buttons, headings |
| Blend Pink | `#FF9A9A` | Accent color, pending indicators |
| Deep Brown | `#7a4229` | Button hover states |

### Typography
- **Font Family**: Inter, system-ui, sans-serif
- **Headings**: Bold, tight tracking
- **Body**: Clean, readable sizing
- **Stats**: Tabular numbers for alignment

### Components
- **Cards**: White/dark background, subtle borders, 12px radius
- **Buttons**: 8px radius, solid colors, hover lift effect
- **Inputs**: Light gray background, focus ring with brand color
- **Modals**: Centered, backdrop blur, scale-in animation

## 📊 Data Structure

### Client Object
```javascript
{
  id: "unique_string",
  name: "Client Name"
}
