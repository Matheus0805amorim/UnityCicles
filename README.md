UnityCircles
Small circles, stronger connections.

UnityCircles is a front-end–only prototype designed for the Hack4Unity challenge. It groups users into small “microcircles” of 3–5 people and assigns weekly missions that encourage meaningful connection, reflection, and collaboration. Everything runs locally in the browser — no backend, no login, no external dependencies.

🚀 Demo

👉 Add your live link here (CodePen / GitHub Pages / hosted HTML)

📌 Features

🔹 Matchmaking based on user interests

🔹 Automatically generated microcircles with up to 5 members

🔹 Topic-aware weekly missions for connection building

🔹 Real-time session statistics (users, circles, averages)

🔹 Everything stored locally in localStorage

🔹 Modern UI using gradients + glassmorphism

🔹 100% front-end; no installation required

🧠 How It Works

UnityCircles uses a lightweight matching algorithm:

User enters:

Name

Interests

Availability

Optional “about me” bio

The algorithm:

Extracts the first interest as the topic

Finds a circle with the same topic and available space

If none exists, it creates a new circle

Assigns the user to the circle

Generates weekly missions based on the topic

Average members per circle are calculated as:

Average
=
Total Users
Total Circles
Average=
Total Circles
Total Users
	​


All data is stored inside:

{ users: [], circles: [] }


using the browser’s localStorage.

🛠️ Built With

HTML5

CSS3 (custom components, responsive layout, glassmorphism)

JavaScript (Vanilla)

localStorage Web API

DOM API

No frameworks.
No backend.
No external libraries.

📦 Installation & Usage
Option 1 — Open the HTML file

Just open the provided index.html file in any modern browser.

Option 2 — GitHub Pages

Upload the file to a GitHub repo

Enable GitHub Pages

Access your live version instantly

Option 3 — CodePen / Replit

Copy the contents into a CodePen or Replit HTML project.

📸 Screenshots

(Add your own screenshots here)

/screenshots/home.png
/screenshots/circle.png
/screenshots/stats.png

🧩 Project Structure
unitycircles/
│
├── index.html        # Complete front-end app (HTML, CSS, JS in one file)
├── README.md         # This file
└── screenshots/      # Optional folder for images

🧪 Testing

Open the page

Add multiple “fake users”

Watch the circles form dynamically

View live stats and mission generation

Everything resets when you click “Clear demo data”.

🔮 Roadmap

Backend for persistent circles

AI-assisted matchmaking

Optional anonymous mode

Real-time chat or voice rooms

Circle-to-circle collaboration

Facilitator tools (agendas, reflection prompts, conflict handling)

🤝 Contributing

Contributions, forks, and suggestions are welcome!
Feel free to open an issue or submit a pull request.

📄 License

MIT License — you may use, modify, and distribute freely.

❤️ Acknowledgments

Built for Hack4Unity — a challenge to bring people together through technology.

If you want, I can also generate:
✅ CONTRIBUTING.md
✅ CODE_OF_CONDUCT.md
✅ A logo for the project
Just ask.
