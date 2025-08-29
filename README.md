# Allen-Bradley L5X IP Scanner & Planner

A browser-based tool for scanning **Allen-Bradley L5X / XML** PLC project files.  
It extracts all IP addresses in use, links them to their corresponding modules/devices, groups them by first octet, and then suggests available IP addresses within those subnets.

Built as a **single HTML file** — no server, no dependencies, all processing is local in your browser.

---

##  Features
- **L5X/XML Parser** – Reads and parses your Allen-Bradley project files directly in the browser.
- **IP Discovery** – Extracts all IPv4 addresses and links them to module/device names with context.
- **Subnet Grouping** – Automatically groups IPs by first octet (e.g., 10.x.x.x, 192.x.x.x).
- **Used vs. Available IPs** – Displays existing IP assignments and generates available IPs within the same /24 or custom CIDR range.
- **Filters** – Exclude `.0`, `.1`, `.255`, or already-used addresses.
- **Export & Print** – Save results as CSV or print directly from the browser.
- **GM-Themed UI** – General Motors blue & white color scheme with official GM brandmark.
- **Branding** – Partnered with **Quaye Works** • © 2025.

---

##  Usage
1. Download or clone this repo.
2. Open `index.html` (the provided HTML file) in any modern browser (Chrome, Edge, Firefox).
3. Click **Load L5X / XML** and select your file.
4. Explore:
   - **IP Groups** by first octet.
   - **Used IPs** with module/device association.
   - **Available IPs** generated dynamically with filters.
5. Export to CSV or print your available IP plan.



## License
MIT License — free to use, modify, and share.

---

##  Credits
- **Quaye Works** – Development & distribution partner.  
- © 2025 Quaye Works
