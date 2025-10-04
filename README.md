Moneta — Currency Exchange Rate App

A lightweight web app for checking and converting currency exchange rates using plain HTML, CSS, and JavaScript.
It fetches real-time rates from a public API and displays conversion results instantly in a clean, responsive UI.

✨ Features

Convert between any two currencies.

Input custom amount, select “from” and “to” currencies.

Fetches live rates from a free exchange rate API.

Simple, responsive interface with only HTML, CSS, and JS (no frameworks).

Error handling for invalid inputs or failed API calls.

🧰 Tech Stack

HTML — structure

CSS — styling & responsive layout

JavaScript (Vanilla) — API calls & DOM updates

Exchange Rate API — e.g. ExchangeRate.host
 (or whichever API you used)

🔧 Getting Started

Clone the repo

git clone https://github.com/<your-username>/moneta.git
cd moneta


Open index.html in your browser
(No build tools or servers needed — it’s a static site.)

⚙️ Example API Call

If you’re using ExchangeRate.host
, an example request looks like:

GET https://api.exchangerate.host/convert?from=USD&to=EUR&amount=100


Response:

{
  "success": true,
  "query": { "from": "USD", "to": "EUR", "amount": 100 },
  "info": { "rate": 0.94 },
  "result": 94
}


Your JavaScript fetches this JSON and updates the UI with the conversion result.

📦 Deployment

Since Moneta is just static files, you can deploy it anywhere:

GitHub Pages (recommended)

Netlify / Vercel

Any static hosting service

For GitHub Pages:

Push your code to a GitHub repo

Go to Settings → Pages

Select branch main (or master) → /root

Save, and your app will be live at https://<username>.github.io/moneta/

📬 Contact

Author: [Bekam]
Repo: https://github.com/<bekamb7>/moneta
