# KharchaBook

> A simple, offline-first personal expense tracker built for Android, Windows, and modern web browsers.

No login. No cloud dependency. No subscription. Your financial data stays on your device.

![Version](https://img.shields.io/badge/version-v3.0-blue)
![License](https://img.shields.io/badge/license-MIT-green)
![Platform](https://img.shields.io/badge/platform-Web%20%7C%20Android-lightgrey)

---

## Features

* Track income and expenses
* Real-time balance calculation
* Receipt and bill photo attachment
* Monthly expense analytics
* Category-wise spending charts
* PDF report generation
* JSON backup and restore
* Local database using IndexedDB
* Mobile-friendly responsive design
* Single-file deployment
* No account required
* Works offline after loading

---

## Screenshots

Add screenshots after publishing the project.

```text
Home Screen
├── Current Balance
├── Total Income
├── Total Expenses
├── Add Income
├── Add Expense
└── Transaction History

Charts Screen
├── Monthly Spending Analysis
├── Income vs Expense
└── Category Breakdown

Backup Screen
├── Export Backup
├── Restore Backup
└── Database Statistics
```

---

## Installation

### Run Locally

Download the project and open:

```text
kharchabook.html
```

using any modern browser:

* Google Chrome
* Microsoft Edge
* Brave
* Firefox

No installation required.

---

### Deploy Online

You can host the application using:

* GitHub Pages
* Netlify
* Vercel

After deployment, access it from any device using the generated HTTPS URL.

---

## Data Storage

KharchaBook uses IndexedDB to store data locally on your device.

### Stored Information

* Income records
* Expense records
* Categories
* Receipt photos
* Application settings

### Data Persistence

| Action              | Data Retained  |
| ------------------- | -------------- |
| Browser restart     | Yes            |
| Device restart      | Yes            |
| Page refresh        | Yes            |
| Browser cache clear | Not guaranteed |
| Site data clear     | No             |
| Browser uninstall   | No             |
| Incognito mode      | No             |

### Backup Recommendation

Use the built-in Backup feature regularly.

```text
IndexedDB
    │
    ├── Export Backup
    │       │
    │       └── backup.json
    │
    └── Restore Backup
```

Keeping periodic JSON backups ensures your data can always be restored if browser storage is removed.

---

## Project Structure

```text
kharchabook/
│
├── kharchabook.html
└── README.md
```

The entire application is contained within a single HTML file.

---

## Technology Stack

| Technology     | Purpose           |
| -------------- | ----------------- |
| HTML5          | User Interface    |
| CSS3           | Styling           |
| JavaScript     | Application Logic |
| IndexedDB      | Local Database    |
| Canvas API     | Charts            |
| jsPDF          | PDF Generation    |
| FileReader API | Receipt Upload    |

---

## Categories

### Income

* Salary
* Freelance
* Rental Income
* Investment Return
* Gifts
* Other

### Expense

* Grocery
* Household
* Food & Dining
* Travel
* Medical
* Shopping
* Utilities
* Education
* Other

---

## PDF Reports

Generated PDF reports include:

* Account summary
* Total income
* Total expenses
* Current balance
* Monthly spending chart
* Transaction history
* Receipt indicators

---

## Privacy

* No server-side database
* No account registration
* No user tracking
* No analytics collection
* No advertisements
* No financial data transmitted externally

All information remains on the user's device unless exported manually.

---

## Roadmap

* [ ] Progressive Web App (PWA) support
* [ ] Service Worker integration
* [ ] Offline installation support
* [ ] CSV export
* [ ] Monthly budget alerts
* [ ] Recurring transactions
* [ ] Multiple accounts and wallets
* [ ] Data encryption

---

## Contributing

Contributions, suggestions, and feature requests are welcome.

1. Fork the repository
2. Create a feature branch
3. Commit your changes
4. Open a Pull Request

---

## License

MIT License

Feel free to use, modify, and distribute this project.

---

## Author

**Rajendra Jat**

Browser Support Engineer

---

If you find this project useful, consider giving it a star.
