# Amerimart Manager Pro

Professional iPhone-friendly PWA demo for gas station store management.

## Features included
- Modern dashboard
- Reliable barcode scanner page using html5-qrcode
- Manual UPC/product search backup
- Product card with photo, price, cost, margin, shelf location
- Price change logging
- Cooler planogram doors/shelves
- Inventory table
- Daily tasks
- Cigarette order page
- Reports and print support
- Dark/light mode
- LocalStorage demo database

## Run locally
```bash
npm install
npm run dev
```

## Deploy to Vercel
1. Upload this folder to GitHub.
2. Go to Vercel.com and import the GitHub repo.
3. Framework: Vite.
4. Build command: `npm run build`.
5. Output directory: `dist`.

## Important iPhone camera note
Camera scanning requires HTTPS when deployed. It may not work from plain `http://` or local file preview on iPhone.
