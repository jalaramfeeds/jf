# jf — Jalaram Dashboard (purana, 2024)

Jalaram Feeds ka **sabse purana dashboard** — ERP se pehle ka (Apr-2024).
Sab **static HTML files** hai, koi backend nahi — sheet se banaye gaye
report/dashboard pages jo tab browser me kholte the.

**Ye repo ab legacy/archive hai — isme aage kaam nahi hota.**
Naya system in repos me hai:

- **[jf-erp-source](https://github.com/jalaramfeeds/jf-erp-source)** — poora ERP (Cloudflare Workers + D1): Sales, Purchase, Production, Labour, Lab, Gate
- **[jf-hr-source](https://github.com/jalaramfeeds/jf-hr-source)** — HR module (Employee Master, Hazari, Chhutti, Tankhwah)
- **[jf-truck-tracker](https://github.com/jalaramfeeds/jf-truck-tracker)** — gadi tracker

## Files (sab static HTML)

| File | Kya hai |
|---|---|
| `index.html` | Jalaram Dashboard — home (Daily Production, FY Report, Unit FY Report ke links) |
| `DAILY.html` | Jalaram Feeds — Daily Production |
| `FY.html` | Financial year report |
| `Allunit.html` / `UNIT.HTML` | Unit-wise dashboard (sab units / ek unit) |
| `k-31.html` `k41.html` `m9.html` `n101.html` | Unit pages — K-31, K-41, M-9, N-101 |
| `tapu.html` | TPAU unit ka invoice page |
| `city.html` | Task Delegation Dashboard |
| `production.html` / `unitproduction.html` | Production dashboards |
| `Invoice.html` / `new.html` | Invoice pages (Professional Invoice) |
| `Inv.html` | Invoice helper |
| `Material.html` | Jalaram Manufacturing Dashboard |
| `PGN.html` | PGN dashboard |
| `PGNORDER.html` | Monthly Order Totals Dashboard (Financial Year) |
| `Vehicle.html` | Vehicle dashboard |
| `Calender.html` | Calendar page |
