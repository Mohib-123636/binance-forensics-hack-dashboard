# binance-forensics-hack-dashboard

binance-forensics-hack-dashboard is an interactive on-chain forensics web application designed to trace and visualize simulated security incidents and illicit fund flows across multiple blockchains including Ethereum, Arbitrum, BNB Chain, and Solana.

Website link: https://binance-forensics-hack-dashboard.vercel.app
## 🚀 Features

* **Interactive Node Graph Visualizer:** Explore wallet clusters, bridge contracts, and DEX pools color-coded by asset status (Ingress, Frozen, Converted, Rescued).
* **Timeline Replay Slider:** Scrub through chronological exploit milestones block-by-block from the initial breach through asset freezes and seizures.
* **Multi-Chain Asset Flow Explorer:** Track cross-chain movements and monitor EVM altcoins, stablecoins, and native token splits.
* **Forensic Analytics Tables:** Detailed data grids categorizing frozen balances, gross conversion proceeds, and remaining unsecured token values with CSV export capabilities.
* **Live Event Feed:** Chronological log of transaction hops, alerts, and threat-intelligence status indicators.

## 🛠️ Tech Stack

* **Frontend:** Next.js (App Router), React, TypeScript
* **Styling & UI:** Tailwind CSS, Lucide React (Icons)
* **Data Visualization & Graphing:** React Flow / D3.js for interactive transaction node mapping

## 📁 Project Structure

```text
binance-forensics-hack-dashboard/
│
├── app/              # Next.js App Router pages & layouts
├── components/       # Reusable UI components (Graph, Timeline, Tables)
├── data/             # Mock forensic JSON datasets & transaction trees
├── public/           # Static assets, icons, and branding
└── styles/           # Global Tailwind CSS configurations & themes
