shadow-friend/
│
├── src/
│   ├── app/
│   │   ├── layout.tsx          // Main layout
│   │   ├── page.tsx            // Home page (Dashboard)
│   │   ├── api/
│   │   │   ├── start-bot/
│   │   │   │   └── route.ts    // API route to start the bot
│   │   │   ├── stop-bot/
│   │   │   │   └── route.ts    // API route to stop the bot
│   │
│   ├── components/
│   │   ├── BotStatus.tsx       // Component to show bot status
│   │   ├── TradeLog.tsx        // Component to show trade logs
│   │   ├── Settings.tsx        // Component to manage bot settings
│   │
│   ├── utils/
│   │   ├── arbitrage.ts        // Core arbitrage logic
│   │   ├── exchanges.ts        // Functions to interact with various exchanges
│   │   ├── db.ts               // Database connection and queries
│   │
│   └── styles/
│       ├── globals.css         // Global CSS
│
├── tailwind.config.js          // Tailwind CSS configuration
├── postcss.config.js           // PostCSS configuration
├── tsconfig.json               // TypeScript configuration
├── package.json                // Project dependencies and scripts
└── .env                        // Environment variables (e.g., for database URL)
