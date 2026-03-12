# Shape Route Matcher

## Prerequisites

- Python 3.12 or higher

---

## Setup

### 1. Clone the repository

```bash
git clone https://github.com/yongchan08/shape-route-matcher.git
cd shape-route-matcher
```

---

### 2. Install uv

#### macOS

```bash
brew install uv
```

or

```bash
curl -LsSf https://astral.sh/uv/install.sh | sh
```

#### Windows (PowerShell)

```powershell
powershell -ExecutionPolicy ByPass -c "irm https://astral.sh/uv/install.ps1 | iex"
```

Verify installation:

```bash
uv --version
```

---

### 3. Create virtual environment

```bash
uv venv
```

---

### 4. Install dependencies

```bash
uv sync
```

---

### 5. Run the server

```bash
uv run uvicorn main:app --reload
```

or

```bash
uv run fastapi dev main.py
```

---

### 6. Access the API

| Description | URL |
|-------------|-----|
| Server | http://127.0.0.1:8000 |
| API Docs (Swagger) | http://127.0.0.1:8000/docs |
| API Docs (ReDoc) | http://127.0.0.1:8000/redoc |
