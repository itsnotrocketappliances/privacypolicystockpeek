# privacypolicystockpeek

Stock Peek — Privacy Policy
Last updated: 12 November 2026. Stock Peek is a free Chrome extension by an individual hobbyist developer. It shows the stock price, delayed at least 15 minutes, of the company that owns the website you are visiting — if that company is publicly traded.

What Stock Peek does
When you click the Stock Peek icon, it reads the current tab's URL, looks the website's domain up in a list bundled with the extension (103 domains in version 0.2.0), and — if the company is found — fetches its stock quote from Finnhub using your own free Finnhub API key, which you enter in Settings. Prices are delayed at least 15 minutes and are never live. On your first visit to a company, the extension shows the previous close and says so plainly until a delayed price is available. Prices are for information only — not financial advice, and not for trading decisions.

Data we collect
We collect nothing. Stock Peek has no account, no analytics, no tracking, and no server of its own. It does not collect, store on any server, sell, or share your browsing history or any personal data.

Data stored on your device
Your Finnhub API key — stored only in your browser (chrome.storage.local). It is sent only to finnhub.io, to fetch quotes for tickers you look up. It is never sent anywhere else.
Site matches you confirm — if you pick a company for a site that is not in the bundled list and choose "Remember this match", that domain-to-ticker match is stored only in your browser.
Delayed-price cache — recent quotes are kept briefly in your browser so the extension can show a price that is at least 15 minutes old. This cache never leaves your browser.
Data sent to third parties
The only third party Stock Peek contacts is Finnhub (finnhub.io), and only when you use it: your key and the ticker being looked up are sent to Finnhub to fetch a quote and company profile. No browsing history is sent to Finnhub. Finnhub's own handling of that request is governed by Finnhub's Terms of Service and privacy policy. Stock Peek loads no remotely hosted code.

Permissions — why each one is needed
activeTab — to read the current tab's URL and identify which company owns the site you are on.
storage — to keep your Finnhub key, your remembered site matches, and the delayed-price cache in your browser only.
scripting — only when a domain is not in the bundled list, to read the page's public og:site_name / JSON-LD organisation name so Finnhub can be searched for a match.
Host permission for finnhub.io — to fetch quotes from Finnhub with your key.
Children
Stock Peek is not directed at children and collects no data from anyone.

Changes
If this policy changes, the updated version will be posted here with a new "last updated" date.

Contact
Questions about this policy or the extension: contact the developer through the Chrome Web Store listing.
