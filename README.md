<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/banner-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="assets/banner.svg">
  <img alt="Hi" src="assets/banner.svg">
</picture>
&nbsp;

Final-year B.Tech CSE undergrad at the University of Kalyani. I enjoy designing and building practical, full-stack solutions to real-world problems. My toolkit includes **Python** (**FastAPI** / **Flask**) for the backend, paired with **SQL** or **NoSQL** databases. For the frontend, I have a working knowledge of **React**, or I can spin up a quick app with **Streamlit**. Lately I've been exploring AI frameworks like **LangChain**.

🟢 I'm currently seeking a remote internship where I can contribute to challenging backend problems. Feel free to review my [Resume](https://farhanr22.is-a.dev/Farhan-Rahaman-Resume.pdf), connect on [LinkedIn](https://linkedin.com/in/farhan-rahaman/), or reach out via [email](mailto:22farhanr@gmail.com).


## Skills

| Category       |                                                                                     |
| -------------- | ----------------------------------------------------------------------------------- |
| Languages      | ![Languages](https://skillicons.dev/icons?i=python,js,c)                            |
| Backend & AI   | ![Backend](https://skillicons.dev/icons?i=fastapi,flask,docker)&nbsp; ![Langchain](assets/langchain.svg)                       |
| Frontend       | ![Frontend](https://skillicons.dev/icons?i=react,materialui,bootstrap)              |
| Databases      | ![Databases](https://skillicons.dev/icons?i=postgres,mysql,sqlite,mongodb,supabase) |



## Featured Projects

### **JECAPrep.in** 
Co-founded a mock test platform for the WB JECA exam and led its complete technical development within a 4-person team. It provides JECA-format mock tests, topic-wise practice tests, and prep materials (PDFs), acquiring 13 paying users and generating ₹1,600+ in revenue over a 3-week launch. Built with Flask and PostgreSQL, the platform features auto-saving test sessions, secure paid content access (Caddy + X-Accel-Redirect), Google OAuth login, Razorpay payments, a comprehensive admin panel, and a CLI tool for structured test data ingestion.

- **[Visit JECAPrep.in &#10132;](https://jecaprep.in)**

### **Voyage'25 Fest Logistics** 

Built a logistics backend and automation suite for our departmental fest ***Voyage 2k25***, managing 120+ registrations, ₹1.2L+ in contributions, and 150+ item distributions. The system ingested payment and registration data from a couple of Google Sheets, provided an admin panel for payment verification, and a live booth page for on-site QR-based item distribution. Additionally, static profile pages were generated on GitHub Actions and deployed to Netlify, and a decoupled WhatsApp worker sent attendees their profile URLs.
- **[View on GitHub &#10132;](https://github.com/farhanr22/voyage-fest-logistics)**
- **[View a Demo Profile Page &#10132;](https://voyage2k25.netlify.app/p/HXSM)**
- **[Detailed Architecture Diagram &#10132;](https://github.com/farhanr22/voyage-fest-logistics/blob/main/assets/architecture_diagram.png)**

### **SocketPoll (Real-time Poll App)**

Developed a full-stack, real-time polling application using FastAPI and React, backed by a MongoDB database. It features live result updates via WebSockets, configurable voting durations, multiple-choice question support and a clean UI with customizable poll colors. Implemented bot and abuse protection by integrating Cloudflare Turnstile for captcha-less verification and using browser fingerprinting to deter duplicate votes.

- **[Try it out &#10132;](https://socketpoll.pages.dev)**
- **[View on GitHub &#10132;](https://github.com/farhanr22/socketpoll)**

### **Data Analysis Chatbot/Agent**
Developed a chatbot that enables users to explore and visualize the Titanic dataset. Built with FastAPI, Streamlit, and LangChain, the application features a ReAct agent that can choose between executing Pandas code for data analysis or generating Plotly visualizations (which are serialized on the backend and rendered in Streamlit). Chat history is maintained across sessions using a SQLite checkpointer, and the backend is containerized with Docker to isolate LLM-generated code.

- **[Try it out &#10132;](https://titanic-chatbot-22.streamlit.app/)**
- **[View on GitHub &#10132;](https://github.com/farhanr22/titanic-chatbot)**


### **Official Departmental Website & CMS** 

Developing the official website & CMS for the Dept. of CSE, in coordination with the HoD and Faculty. Built using Flask/PostgreSQL, it features an admin panel with RBAC, is containerized with Docker and has automated deployments via GitHub Actions. A key focus was reliability, with database and content backups to Google Drive managed via `rclone`, and site health and backup status monitored through [healthchecks.io](https://healthchecks.io) and [ntfy](https://ntfy.sh) alerts. 
- **[View the Testing Site &#10132;](https://cseku.soon.it)**

## Other Explorations

- **Conway's Game of Life —** An interactive, feature-rich visualizer in Lua/LÖVE2D with simulation controls, RLE import/export, custom ruleset support, and tweakable visuals. **[GitHub &#10132;](https://github.com/farhanr22/GameOfLife-Lua)**

- **Wolfram CA Scroller —** An infinite-scrolling cellular automata viewer in C, using a ring-buffer–inspired approach for efficient row updates. **[GitHub &#10132;](https://github.com/farhanr22/Wolfram-Scroller)**

- **Encrypted LAN Chat —** A Python/Tkinter TCP chat app featuring E2E-encrypted one-on-one messaging using a custom, simplified RSA implementation and group chats with Hamming Code-based error correction. **[GitHub &#10132;](https://github.com/farhanr22/Python-LAN-Chat)**

- **Airline Database System —** A MySQL-based DBMS project modeling airline operations, with an ER diagram, normalized schema, and analytical SQL queries, documented in a PDF report. **[GitHub &#10132;](https://github.com/farhanr22/Airline-DBMS)**
