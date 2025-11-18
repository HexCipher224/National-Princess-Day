# 👑 National Princess Day Surprise

A delightful single-page Next.js site to celebrate National Princess Day with a special surprise message, beautiful animations, and confetti!

## ✨ Features

- 🎨 Beautiful pastel design with soft colors and rounded cards
- 🎭 Smooth animations using Framer Motion
- 🎊 Confetti celebration on gift reveal
- 📱 Fully responsive and mobile-first
- ♿ Accessible with keyboard navigation and ARIA labels
- 🔔 Toast notifications for user feedback
- 🖼️ Photo grid for memories
- 📋 Copy message functionality

## 🚀 Quick Start

### Prerequisites

- Node.js 18+ and npm/yarn/pnpm

### Installation

```bash
# Install dependencies
npm install

# Run development server
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) in your browser.

### Build for Production

```bash
# Create production build
npm run build

# Start production server
npm start
```

### Other Commands

```bash
# Run linter
npm run lint

# Format code
npm run format

# Run tests
npm test
```

## 🎨 Customization

### Edit the Message

Edit the message content in `data/message.ts`:

```typescript
export const messageData = {
  title: 'Happy National Princess Day 👑',
  subtitle: 'To my favorite princess — today, and every day.',
  body: `Your custom message here...`,
  // ...
};
```

### Change Colors

Update CSS variables in `styles/globals.css`:

```css
:root {
  --bg: #fff9ff;
  --primary: #ffb6e6;
  --accent: #ffd8a8;
  --text: #2d2d2d;
}
```

### Replace Images

Replace placeholder images in `components/PhotoGrid.tsx` or add your own images to `public/assets/`.

## 🚢 Deployment

### Deploy to Vercel (Recommended)

1. Push your code to GitHub
2. Go to [vercel.com](https://vercel.com)
3. Click "New Project" and import your repository
4. Vercel will automatically detect Next.js and deploy

**One-click deploy:**
[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=YOUR_REPO_URL)

### Deploy to Render

1. Create a new account at [render.com](https://render.com)
2. Click "New +" → "Web Service"
3. Connect your GitHub repository
4. Use these settings:
   - **Build Command:** `npm run build`
   - **Start Command:** `npm start`
   - **Environment:** Node

## 📁 Project Structure

```
princess-day/
├── components/
│   ├── Hero.tsx           # Hero section with crown animation
│   ├── MessageCard.tsx    # Animated message card
│   ├── PhotoGrid.tsx      # Photo grid/carousel
│   └── Confetti.tsx       # Confetti animation
├── data/
│   └── message.ts         # Message content (editable)
├── lib/
│   └── toast.ts           # Toast notifications
├── pages/
│   ├── _app.tsx           # App wrapper
│   └── index.tsx          # Main page
├── public/
│   └── assets/
│       └── crown.svg      # Crown illustration
├── styles/
│   └── globals.css        # Global styles & CSS variables
└── package.json
```

## 🛠️ Tech Stack

- **Next.js 14** - React framework
- **TypeScript** - Type safety
- **Tailwind CSS** - Utility-first styling
- **Framer Motion** - Smooth animations
- **React Hot Toast** - Toast notifications

## 📝 License

Made with 💕 for National Princess Day

