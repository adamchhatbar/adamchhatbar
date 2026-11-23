<h1>Adam Chhatbar</h1>

**Founder & Lead Engineer, [Offset Technologies](https://offsettechs.com)** · Arusha, Tanzania · since 2016

I build business systems for East African shops, pharmacies and safari operators that run on ordinary shared hosting and keep selling when the network drops. Each one ships multi-tenant, bilingual (English/Kiswahili) and wired into mobile money, SMS and WhatsApp.

`Next.js` `TypeScript` `PHP 8` `MySQL` `Offline-first POS` `Multi-tenant SaaS` `Kiswahili i18n`

---

### Production systems

| System | Domain | Engineering highlights | Stack |
|---|---|---|---|
| **[Msafara](https://offsettechs.com/our-work/)** | Safari operations | Multi-tenant SaaS rented per company with plans, vehicle limits and read-only grace on expiry. Wialon GPS ingestion, Telegram bot alerts, SOS SMS, TALA permit and PAYE/NSSF payroll rules, nightly compressed backups. | HTML/JS · PHP 8.1 · MariaDB |
| **[Rahisi Auto](https://rahisiautocenter.online)** | Spare-parts retail | Fitment by chassis code, normalised OEM/cross-ref part search, multi-currency landed cost, garage credit with manager-PIN override, workshop job cards. Append-only stock ledger that can rebuild every balance. 193 end-to-end API tests. | Next.js 15 · React 19 · TS · PHP 8 · MySQL |
| **[DawaFlow](https://dawaflowtz.online)** | Pharmacy | Batch and expiry tracking with earliest-expiry picking, prescription and controlled-drug checks, till reconciliation per payment method, purchase-order to goods-received flow, multi-branch dashboard. | Next.js · Prisma · SQLite · Node |
| **Zana** | Hardware retail | Rentable multi-tenant shop system with per-business branding on one install, offline sales mode, barcode/QR labels, rental plans and billing console. | Next.js 15 · TS · Tailwind 4 · PHP 8 · MySQL |
| **Business Manager** | SMEs | Shared base system, customised per client: [Shamba Lulu](https://shambalulu.online) (maize farm) and [Naturaw Skin Co.](https://naturawskinco.store) (skincare & spa). Sales, invoicing, stock, customer credit, leads, appointments and P&L, with M-Pesa, Mixx, Airtel and HaloPesa capture. Weekly summary sent by email and WhatsApp Cloud API. | Next.js 16 · Radix UI · PHP 8 · MySQL |

**Shared architecture.** A static Next.js front end with a PHP/MySQL API, so it deploys to ordinary cPanel hosting with no Node on the server. Retail sales queue on the device and sync with a client-generated ID, so a sale never posts twice. Money is stored in whole shillings. Schema upgrades are additive and run on first request. Every release must pass a check that each UI string has a Kiswahili translation.

<sub>Client code is private. Demos and walkthroughs on request.</sub>

---

### Stack

| Area | Tools |
|---|---|
| Languages | TypeScript, JavaScript, PHP 8, SQL |
| Front end | Next.js (static export), React 19, Tailwind CSS 4, Radix UI |
| Back end & data | PHP REST APIs, MySQL/MariaDB, Prisma, SQLite |
| Hosting & ops | cPanel/LiteSpeed, Let's Encrypt, cron jobs, scripted PowerShell packaging and deploys |
| Integrations | Africa's Talking SMS, M-Pesa / Mixx / Airtel / HaloPesa, WhatsApp Cloud API, Telegram Bot API, Wialon GPS, BLE thermal printers |

---

### Writing

- [How to Choose the Right Business Management System in Tanzania](https://offsettechs.com/insights/) · Oct 2026
- [7 Things Every Business Website in Tanzania Needs to Win Customers](https://offsettechs.com/insights/) · Oct 2026
- [Digital Marketing for Tanzanian Businesses: Where to Start](https://offsettechs.com/insights/) · Nov 2026

---

### Contact

[offsettechs.com](https://offsettechs.com) · [inquiries@offsettechs.com](mailto:inquiries@offsettechs.com) · [WhatsApp](https://wa.me/255686294959)
