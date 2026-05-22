# COBY

COBY is a Streamlit-based local AI tutor app for Namibian learners, using Ollama for local LLM inference.

## Files

- `COBY v0.1 .py` - main Streamlit application
- `requirments.txt` - original dependency list
- `requirements.txt` - corrected dependency file
- `venv/` - Python virtual environment (ignored by git)
- `.gitignore` - files and folders excluded from version control

## Setup

1. Install Git for Windows: https://git-scm.com/download/win
2. Open PowerShell in this folder
3. Create and activate a virtual environment:

```powershell
python -m venv venv
.\venv\Scripts\Activate.ps1
```

4. Install dependencies:

```powershell
pip install -r requirements.txt
```

5. Start Ollama locally (if you have it installed):

```powershell
ollama run llama3
```

6. Run the Streamlit app:

```powershell
streamlit run "COBY v0.1 .py"
```

## GitHub repository instructions

Once Git is installed, run:

```powershell
git init
git add .
git commit -m "Initial commit"
```

If you also install GitHub CLI (`gh`), create and push a repo:

```powershell
gh auth login
gh repo create coby --public --source=. --remote=origin --push
```

If you prefer, you can also create an empty repository on GitHub and add it as a remote manually.
