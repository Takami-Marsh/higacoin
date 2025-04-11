# Higacoin

A playful cryptocurrency and poker gaming platform created for students at HiGA School. This project was developed as a fun experiment to engage students in learning about digital currencies and card games in an entertaining way.

## Features

- Cryptocurrency Trading
  - Buy/Sell functionality
  - Real-time profit tracking
  - Trading history
- Interactive Poker Games
  - Local and online multiplayer modes
  - Complete deck of 52 cards
  - Player rankings
- User Management
  - Account creation and authentication
  - User profiles
  - Account balance tracking

## Directory Structure

```
.
├── higacoin.sql           # Database schema and data
├── index.php              # Main application entry point
├── higacoin_m/           # Mobile version of the application
│   ├── account.php       # Account management
│   ├── buy.php          # Cryptocurrency purchase
│   ├── trade.php        # Trading interface
│   ├── poker_home.php   # Poker game home
│   ├── poker_local.php  # Local multiplayer
│   ├── poker_online.php # Online multiplayer
│   └── ...
├── trump/               # Card assets directory
│   └── ...             # 52 playing card images
└── ユーザーマニュアル.pdf    # User manual (Japanese)
```

## Setup

1. Set up a PHP web server with MySQL support
2. Import `higacoin.sql` into your MySQL database
3. Configure your web server to point to the project root
4. Access the application through your web browser

## Technologies Used

- PHP
- MySQL
- HTML/CSS
- JavaScript (JSON API endpoints)

## Mobile Support

A dedicated mobile version is available in the `higacoin_m` directory, optimized for smaller screens and touch interfaces.

## License

See the [LICENSE](LICENSE) file for license rights and limitations.
