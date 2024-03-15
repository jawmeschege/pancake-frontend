# 🥞 Crypto-Swap Wordpress Plugin

crypto-swap-plugin/
│
├── admin/
│   ├── admin-pages.php    # Admin pages for setup and configuration
│   └── onboarding.php     # Onboarding wizard logic
│
├── includes/
│   ├── api-integration.php    # Handles API integration with crypto exchanges
│   ├── shortcodes.php    # Shortcode implementation for integrating Next.js app
│   └── utils.php         # Utility functions for the plugin
│
├── nextjs-app/                # Next.js project directory (for development)
│   ├── pages/
│   ├── components/
│   ├── public/
│   └── ...                   # Standard Next.js project structure
│
├── public/
│   └── nextjs/                # Built Next.js app for production
│       ├── _next/
│       ├── index.html
│       └── ...
│
└── crypto-swap-plugin.php     # Main plugin file

