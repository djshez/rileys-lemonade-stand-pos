# Riley's Lemonade Stand POS

A simple and modern point-of-sale system for tracking cash sales at Riley's Lemonade Stand. This application is designed to run from a USB drive or SD card for maximum portability.

## Features

- Record cash sales with timestamps
- View sales history in a clean, organized table
- Calculate total sales and revenue
- Export sales data to CSV
- Reset sales history when needed
- Runs directly from USB/SD card
- Works offline
- Data persists between sessions

## Getting Started

### Development

1. Install dependencies:
```bash
npm install
```

2. Run the development server:
```bash
npm run dev
```

3. Open [http://localhost:8000](http://localhost:8000) in your browser

### Creating a Portable Version

1. Build and export the application:
```bash
npm run build
```

2. Copy the contents of the 'out' directory to your USB drive or SD card

3. To use the application:
   - Insert the USB drive or SD card
   - Open the index.html file in a web browser
   - Start tracking your sales!

## Usage

1. Enter the sale amount in the input field
2. Click "Add Sale" to record the transaction
3. View the running total and sale history below
4. Export data to CSV when needed
5. Use the reset button to clear all data (with confirmation)

## Data Storage

All sales data is stored locally in your browser's localStorage. This means:
- Data persists between sessions
- No internet connection required
- Data is private to your device

## Technical Details

Built with:
- Next.js
- React
- TypeScript
- Tailwind CSS
- shadcn/ui components

## Notes

- The application works entirely offline
- All data is stored locally in the browser
- Clearing browser data will erase sales history
- Regular backups via CSV export are recommended
