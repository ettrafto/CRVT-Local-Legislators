# BillTracker.org

**BillTracker.org** is an open-source web application that helps Vermont citizens and local journalists explore legislative activity in a clear and accessible way. The platform allows users to select one or more Vermont legislators, view the bills they sponsor, and see their voting records, all in one place.

## Features

- 📜 **Bill Search and Filters**: Search and filter bills by sponsor, topic, or district.
- 🗳️ **Voting Records**: View how each legislator voted on specific bills.
- 👥 **District View**: Select single or multiple legislative districts and see relevant activity.
- 🧩 **Expandable Cards**: Clickable bill cards that expand to show full details with smooth animations.
- ⚡ **Fast and Lightweight**: Designed to run locally or on simple servers for accessibility and ease of use.
- 🧰 **Non-technical Friendly**: Built with local editors and community members in mind.

## Technologies Used

- **Frontend**: React.js, Framer Motion, D3
- **Backend & Scraping**: Node.js, Playwright
- **Data Storage**: Local JSON files
- **Server**: Nginx (static file hosting)

## Getting Started

### Prerequisites

- Node.js (v18+ recommended)
- npm or yarn

### Installation

```bash
git clone https://github.com/your-username/billtracker.org.git
cd billtracker.org
npm install
npm start
