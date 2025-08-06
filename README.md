# FlickFix – Movie Analytics Dashboard



## 🎯 Project Context: FlickFix Ticketing Platform

FlickFix is a new entrant in the online movie-ticketing space, competing against established aggregators.\
After six months in our launch market, FlickFix’s share of weekly ticket sales sits at **22%**, with aggressive growth targets set for the next quarter.\
This Tableau project was built for the Strategy & Growth team to uncover booking, revenue, and commission insights that will help FlickFix scale in a competitive landscape.

## 📊 Dashboard Purpose

The dashboard surfaces **end-to-end marketplace KPIs**—from ticket sales and revenue to per-show performance—so that marketing, operations, and finance teams can make rapid, data-driven decisions.

| Marketplace Lens        | Key Metrics Exposed                                       |
| ----------------------- | --------------------------------------------------------- |
| **Demand (Moviegoers)** | Ticket-ID count, weekly booking trend, channel mix        |
| **Supply (Venues)**     | Show-level revenue, average ticket price, occupancy proxy |
| **Platform Economics**  | Weekly commission trend, commission-to-sales ratio        |

## 🧩 Dashboard Features

- **Ticket Sales by Week** – Stacked bar tracking weekly bookings split by *Venue Type* (Movie vs. Broadway Show) and *Seller* (Organizer vs. Reseller).
- **Revenue by Week** – Parallel view showing gross sales in \$, enabling quick Revenue-per-Ticket calculations.
- **Commission by Week** – Isolates FlickFix’s earnings to monitor margin health.
- **Sales Channel Details** – Pivot table breaking down tickets, sales, commission, and average revenue across web, mobile, booth, and kiosk channels.
- **Ticket Sales by Show** – Drill-down table revealing top-grossing shows and venue performance to guide content procurement and marketing spend.

## 🔎 Use-Case Value

- **Optimize Marketing Spend 💸**   Identify high-conversion shows and allocate ads to top ROAS titles.  
- **Negotiate with Venues 🤝**   Use venue-specific revenue & commission data to craft win-win partnership terms.  
- **Expand Channel Mix 📱**   Compare web vs. app vs. offline booth sales to prioritize product features and outreach.  

## ✅ Sample Business Recommendations

1. Double down on **mobile push campaigns** for Broadway shows—mobile drives **65 %** of premium-ticket sales but only **40 %** of ad spend.  
2. Re-negotiate commission tiers with low-volume resellers to lift platform margin by \~3 pp.  
3. Pilot **dynamic pricing** on under-performing weekday movie slots to boost seat utilization.  

## 🛠️ Technologies Used

- **Tool:** Tableau Desktop Public Edition 2024.1  
- **Data Source:** Simulated ticketing dataset (SQL extract) covering 60 ticketing days, 38 sales channels, and 15 venues  
- **Methods:** Visual analytics, cohort slicing, margin analysis

## 🔗 Live Dashboard

👉 [Explore the interactive FlickFix dashboard on Tableau Public](https://public.tableau.com/app/profile/ashutosh.jagdale/viz/FlickFix-MovieAnalyticsDashboard/FinalReport)

## 📁 Repo Structure


```bash
FlickFix-Movie-Analytics-Dashboard/
│
├── assets/
│ └── FlickFixDashboardScreenshot.png # Dashboard image used in README
│
├── README.md # Project documentation (this file)
└── FlickFix_Movie_Analytics_Dashboard.twbx # Tableau workbook (optional)
