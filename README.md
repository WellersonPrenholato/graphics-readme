# 📊 GitHub Language Statistics

<!-- BADGES:START -->
![Python](https://img.shields.io/badge/Python-29.96%25-3776AB?style=for-the-badge&logo=python&logoColor=white) ![JavaScript](https://img.shields.io/badge/JavaScript-24.84%25-F7DF1E?style=for-the-badge&logo=javascript&logoColor=white) ![C](https://img.shields.io/badge/C-24.41%25-A8B9CC?style=for-the-badge&logo=c&logoColor=white) ![TypeScript](https://img.shields.io/badge/TypeScript-10.78%25-3178C6?style=for-the-badge&logo=typescript&logoColor=white) ![Java](https://img.shields.io/badge/Java-6.32%25-ED8B00?style=for-the-badge&logo=java&logoColor=white) ![C++](https://img.shields.io/badge/C%2B%2B-3.69%25-00599C?style=for-the-badge&logo=c%2B%2B&logoColor=white)
<!-- BADGES:END -->

A Jupyter Notebook that connects to the GitHub API, collects language usage data from your repositories, and generates a pie chart of your most used programming languages.

## 🚀 Getting Started

### Prerequisites

- Python 3.8+
- A [GitHub Personal Access Token](https://github.com/settings/tokens) with `repo` scope

### Installation

```bash
# Clone the repository
git clone https://github.com/WellersonPrenholato/graphics-readme.git
cd graphics-readme

# Install dependencies
pip install -r requirements.txt

# Configure your token
cp .env.example .env
# Edit .env and add your GitHub token
```

### Usage

Open `script-statistics-github.ipynb` in Jupyter or VS Code and run all cells.

## 📊 Generated Result

<img src="https://github.com/WellersonPrenholato/graphics-readme/blob/master/linguages-statistics.png" alt="Language Statistics Chart">

## 🛠 Configuration

You can customize the script by editing these variables in the notebook:

| Variable | Description | Default |
|----------|-------------|---------|
| `EXCLUDE` | Languages to remove from chart | `HTML, CSS, Jupyter Notebook, PHP` |
| `TOP_N` | Number of top languages to display | `6` |
| `COLORS` | Colors for pie chart slices | Custom hex colors |

