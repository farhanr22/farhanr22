<picture>
  <source media="(prefers-color-scheme: dark)" srcset="banner-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="banner.svg">
  <img alt="Fallback image description" src="banner.svg">
</picture>
&nbsp;

I'm a final-year B.Tech CSE undergrad at the University of Kalyani. I enjoy designing and building practical, full-stack solutions to real-world problems, primarily using Python with Flask and SQLAlchemy.

I'm currently exploring async Python with FastAPI, learning NoSQL with MongoDB, and experimenting with React.

## Featured Projects

### &bull; **JECAPrep.in** 
Co-founded a mock test platform for the WB JECA exam and led its complete technical development within a 4-person team. It provides JECA-format mock tests, topic-wise practice tests, and prep materials (PDFs), acquiring 13 paying users and generating ₹1,600+ in revenue over a 3-week launch. Built with Flask and PostgreSQL, the platform features auto-saving test sessions, secure paid content access (Caddy + X-Accel-Redirect), Google OAuth login, Razorpay payments, a comprehensive admin panel, and a CLI tool for structured test data ingestion.

- **[Visit JECAPrep.in &#10132;](https://jecaprep.in)**

### &bull; **Voyage 2k25 Fest Logistics** 

Built a logistics backend and automation suite for our departmental fest ***Voyage 2k25***, managing 120+ registrations, ₹1.2L+ in contributions, and 150+ item distributions. The system ingested payment and registration data from a couple of Google Sheets, provided an admin panel for payment verification, and a live booth page for on-site QR-based item distribution. Additionally, static profile pages were generated on GitHub Actions and deployed to Netlify, and a decoupled WhatsApp worker sent attendees their profile URLs.
- **[View on GitHub &#10132;](https://github.com/farhanr22/voyage-fest-logistics)**
- **[View a Demo Profile Page &#10132;](https://voyage2k25.netlify.app/p/HXSM)**
- **[Detailed Architecture Diagram &#10132;](https://github.com/farhanr22/voyage-fest-logistics/blob/main/assets/architecture_diagram.png)**


### &bull; **Official Departmental Website** 

Developing the official website & CMS for the Dept. of CSE, in coordination with the HoD and Faculty. Built using Flask/PostgreSQL, it features an admin panel with RBAC, is containerized with Docker and has automated deployments via GitHub Actions. A key focus was reliability, with database and content backups to Google Drive managed via `rclone`, and site health and backup status monitored through [healthchecks.io](https://healthchecks.io) and [ntfy](https://ntfy.sh) alerts. 
- **[View the Testing Site &#10132;](https://cseku.soon.it)**

## Other Explorations

- **Conway's Game of Life —** An interactive, feature-rich visualizer in Lua/LÖVE2D with simulation controls, RLE import/export, custom ruleset support, and tweakable visuals. **[GitHub &#10132;](https://github.com/farhanr22/GameOfLife-Lua)**

- **Wolfram CA Scroller —** An infinite-scrolling cellular automata viewer in C, using a ring-buffer–inspired approach for efficient row updates. **[GitHub &#10132;](https://github.com/farhanr22/Wolfram-Scroller)**

- **Encrypted LAN Chat —** A Python/Tkinter TCP chat app featuring E2E-encrypted one-on-one messaging using a custom, simplified RSA implementation and group chats with Hamming Code-based error correction. **[GitHub &#10132;](https://github.com/farhanr22/Python-LAN-Chat)**

- **Airline Database System —** A MySQL-based DBMS project modeling airline operations, with an ER diagram, normalized schema, and analytical SQL queries, documented in a PDF report. **[GitHub &#10132;](https://github.com/farhanr22/Airline-DBMS)**