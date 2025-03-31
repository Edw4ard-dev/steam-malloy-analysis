# 🎮 Steam Malloy Analysis (v2)

This project analyzes a curated sample of Steam gaming platform data using [Malloy](https://malloydata.dev), a modern data modeling and querying language designed for exploration and visualization. All queries are organized for clarity and version control directly on GitHub, and can be run locally using Visual Studio Code.

---

## 📁 Project Structure

```
steam-malloy-analysis-v2/
├── data/
│   └── steam_data_sample.csv        # Sampled dataset (4,000 rows)
├── models/
│   └── steam.malloy                 # Malloy model definition
├── queries/
│   ├── question1.malloy             # Top 10 most frequent game names
│   ├── question2.malloy             # Top developers by game count
│   ├── question3.malloy             # Top genres
│   ├── question4.malloy             # Top publishers
│   ├── question5.malloy             # Top categories (e.g., Single-player)
│   ├── question6.malloy             # Most common tags
│   ├── question7.malloy             # Most frequent languages
│   └── question8.malloy             # Most common platforms
└── README.md                        # Project overview (this file)
```

---

## 🚀 How to Use

### 1. Clone the Project

```bash
git clone https://github.com/Edw4ard-dev/steam-malloy-analysis-v2.git
cd steam-malloy-analysis-v2
```

---

### 2. Open in Visual Studio Code

- Open the folder in VS Code
- Install the **Malloy extension** ([Marketplace link](https://marketplace.visualstudio.com/items?itemName=malloydata.malloy-vscode))

---

### 3. Run Any Query

- Navigate to the `queries/` folder
- Open any `questionX.malloy` file
- Click ▶ **Run Malloy** to view results and charts

---

## 📊 Analytical Insights Covered

| Query File         | What It Explores                                      |
|--------------------|--------------------------------------------------------|
| question1.malloy   | Top 10 most frequently occurring game names            |
| question2.malloy   | Developers with the most games in the dataset          |
| question3.malloy   | Most popular genres                                    |
| question4.malloy   | Leading publishers by game count                       |
| question5.malloy   | Most common game categories (e.g., Co-op, Multiplayer) |
| question6.malloy   | Most frequent tags applied to games                    |
| question7.malloy   | Languages most frequently supported                    |
| question8.malloy   | Most targeted platforms                                |

---

## 🔧 Tools Used

- **Malloy** — for data modeling and SQL-style querying
- **DuckDB** — in-memory SQL engine used by Malloy
- **Visual Studio Code** — for query execution and visualization
- **GitHub** — for code collaboration and version control

---

## 📬 Feedback & Contributions

Feel free to fork this repo, suggest improvements, or submit issues.  
You can also reach out via [GitHub Issues](https://github.com/Edw4ard-dev/steam-malloy-analysis-v2/issues).

---
