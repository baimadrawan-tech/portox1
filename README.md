# Xalixia — Links & Projects

Website profil dan kumpulan link proyek digital Xalixia. Dibangun dengan **React + Vite + Tailwind CSS v4**.

## Demo

🌐 **Live:** https://xalixia.pages.dev (setelah deploy ke Cloudflare Pages)

## Development

```bash
# Install dependencies
npm install

# Jalankan dev server
npm run dev

# Build production
npm run build

# Preview build lokal
npm run preview
```

## Deploy ke Cloudflare Pages (via GitHub)

1. Push repo ini ke GitHub
2. Buka [Cloudflare Pages Dashboard](https://dash.cloudflare.com/pages)
3. Klik **Create a project** → **Connect to Git**
4. Pilih repo GitHub ini
5. Konfigurasi build:
   - **Build command:** `npm run build`
   - **Build output directory:** `dist`
   - **Root directory:** `/` (default)
6. Klik **Save and Deploy**

Cloudflare akan otomatis build & deploy setiap push ke branch `main`.

### Environment Variables (optional)

Tidak ada env vars required untuk project ini.

## Tech Stack

- **React 19** — UI library
- **Vite 8** — Build tool & dev server
- **Tailwind CSS v4** — Styling (via `@tailwindcss/vite`)
- **Lucide React** — Icons
- **TypeScript** — Type safety

## Project Structure

```
├── index.html          # HTML entry point
├── src/
│   ├── main.tsx        # React bootstrap
│   ├── App.tsx         # Main component (link hub)
│   └── styles.css      # Tailwind + custom styles
├── public/
│   └── xalixia-profile.png  # Profile photo
├── vite.config.ts      # Vite config
└── tsconfig.json       # TypeScript config
```

## Links Included

| Emoji | Project | Description |
|-------|---------|-------------|
| 📤 | Uploader | File upload service |
| ✦ | Xalixia Tools & AI | Tools & AI chat collection |
| ▦ | QR & PDF Tools | QR generator + PDF tools |
| 💸 | Xalixia Wallet | Finance tracker |
| 🧾 | QRIS Xalixia | Admin support page |
| 💌 | Appslovv | Couple web app |
| 🎵 | TikTok Downloader | Download TikTok no watermark |
| 🖥️ | Jasa Website | Website development services |
| 💬 | WhatsApp Contact | Direct chat link |

## License

MIT — bebas dipakai & dimodifikasi.