# Main Square Musallah Website

A modern, responsive, single-page continuous-scrolling website designed for **Main Square Musallah** (Toronto, ON).

---

## Musallah Information

- **Opening Hours**: Open strictly around prayer times — **10 minutes before Iqamah until right after Jama'ah**. Closed between prayers.
- **Hallway Policy**: Praying or lingering in the residential hallways and elevator lobby is strictly prohibited.
- **Friday Jummah**: One single congregation at **2:00 PM** (Khutbah begins promptly at 2:00 PM).
- **Donations**: Cash donations only via the donation boxes inside the musallah hall (no Interac e-Transfer or online payments).
- **Updates**: WhatsApp community group via the on-page QR code and link.

---

## Sections Included

1. **Header & Navigation**: Sticky navbar with smooth-scrolling anchor links and mobile drawer menu.
2. **Hero Section**: Welcome banner, quick action buttons (*Prayer Times*, *Jummah 2 PM*, *WhatsApp Group*).
3. **Prayer Schedule**: Embedded real-time prayer schedule powered by [AthanPlus](https://timing.athanplus.com), access notes, and hallway policy banner.
4. **Jummah Prayer**: Highlighted single Friday prayer service at 2:00 PM.
5. **About Our Musallah**: Overview of the space, community focus, and accessibility.
6. **WhatsApp Community**: Direct link and QR code (`mainsqqr.png`) for daily iqamah updates.
7. **Services**: 5 daily prayers, Friday Jummah, Ramadan programs, and neighborhood etiquette.
8. **Support & Donations**: Clear notice for in-person cash donations in the musallah donation box.
9. **Hours & Location**: Specific opening hours around prayer times, transit directions (Main Street Subway & Danforth GO), and parking.
10. **Footer**: Navigation links and credits.

---

## Project Structure

```text
mainsq-masjid/
├── .gitignore       # Git ignore rules
├── index.html       # Single-page website
├── mainsqqr.png     # WhatsApp QR code image
└── README.md        # Project documentation
```

---

## Local Preview

Double-click `index.html` to open it in your browser, or start a local server:

```bash
# Using Python
python -m http.server 8000

# Using Node (npx)
npx serve .
```

---

## Deployment

Deployable via **GitHub Pages**, **Vercel**, or **Netlify**:
1. Push changes to the `main` branch.
2. In GitHub, navigate to **Settings** > **Pages**.
3. Under **Build and deployment**, select **Deploy from a branch** (`main` / root).