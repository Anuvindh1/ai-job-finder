# AI Job Finder
A smart AI-powered job search web app that searches real remote tech jobs across multiple sources and summarizes them using AI.
![Python](https://img.shields.io/badge/Python-3.13-blue)

![Flask](https://img.shields.io/badge/Flask-3.0-green)

![AI](https://img.shields.io/badge/AI-Groq-purple)
## 🌟 Features
- 🔍 **Smart Search** — fuzzy matching so "developer" also finds "engineer", "programmer" etc.

- 🤖 **AI Summaries** — every job gets a one-line AI summary powered by Groq (Llama 3)

- 🌍 **Multiple Sources** — pulls jobs from Remotive and Adzuna simultaneously

- 🗺️ **Country Filter** — search jobs in India, USA, UK, Australia, Canada, Germany or worldwide

- 💼 **Job Type Filter** — filter by full-time, part-time, contract, internship

- 🌐 **Remote Filter** — show only remote-friendly jobs

- ✨ **Glassmorphism UI** — beautiful dark glass-effect cards with animations

- ⚡ **Fast** — all APIs fetched in parallel, AI summaries generated simultaneously

- 📄 **Load More** — paginated results with a load more button
## 🛠️ Tech Stack
| Layer | Technology |

|-------|-----------|

| Backend | Python, Flask |

| Frontend | HTML, CSS (Glassmorphism) |

| AI | Groq API (Llama 3.1 8B) |

| Job Data | Adzuna API, Remotive API |

| Concurrency | Python ThreadPoolExecutor |
## 🚀 Setup & Installation
### 1. Clone the repository
git clone https://github.com/Anuvindh1/ai-job-finder.git

cd ai-job-finder
### 2. Install dependencies
pip install -r requirements.txt
### 3. Get your free API keys
| API | Where to get it | Cost |

|-----|----------------|------|

| Groq | console.groq.com | Free |

| Adzuna | developer.adzuna.com | Free |
### 4. Create a .env file
Create a file called .env in the project root and add:
GROQ_API_KEY=your-groq-api-key-here

ADZUNA_APP_ID=your-adzuna-app-id-here

ADZUNA_API_KEY=your-adzuna-api-key-here
### 5. Run the app
python app.py
Then open your browser and go to http://localhost:5000
## 📁 Project Structure
ai-job-finder/

├── app.py

├── index.html

├── static/

│   └── style.css

├── requirements.txt

├── .env

├── .gitignore

└── README.md
## 💡 How It Works

User types a keyword e.g. "python developer"
App expands keyword using smart synonym mapping
Remotive and Adzuna APIs are queried simultaneously
Results are scored, deduplicated and ranked by relevance
AI generates a one-line summary for each job in parallel
Results displayed as beautiful glass cards with filters

## 🔮 Future Plans
- Add more job APIs (Jooble, JSearch)

- Email alerts for new matching jobs

- Save favourite jobs

- Resume match scoring
## 👨‍💻 Built By
Anuvindh Rajeevan P — built as a portfolio project to learn Python, Flask, and AI API integration.
Click the pencil icon to edit
Delete everything and paste the text above
Click "Commit changes"
