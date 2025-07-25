# Learning Supabase with Python 🐍 + 🛡️

This repository documents my learning journey using [Supabase](https://supabase.com) with Python. Supabase is an open-source Firebase alternative that provides a Postgres database, authentication, and other backend services.

## 🚀 How to Run This Project

Follow these steps to get this project up and running on your local machine

### 1. Created Python Virtual Environment using `uv`

I used [`uv`](https://github.com/astral-sh/uv), a super-fast Python package manager, to create and manage a virtual environment:

```bash
uv venv
.venv\Scripts\activate
```

### 2. Install the Supabase Python Library

```bash
uv add supabase
```

This installs the official Supabase Python client from [supabase-community/supabase-py](https://github.com/supabase-community/supabase-py).

### 3. Connect to Supabase

```python
from supabase import create_client, Client

url = "https://<your-project>.supabase.co"
key = "your-api-key"

supabase: Client = create_client(url, key)
```

## 📦 What’s Included

✅ 📓 **[CRUD Operations in Supabase](./supabase_crud.ipynb)**

## 🔧 Requirements

- Python 3.8+
- Supabase account
- A Supabase project and database set up

## 📂 Project Structure (Example)

```
supabase-python-learn/
├── .venv/
├── supabase_crud.ipynb
├── main.py
└── README.md
```

## 💡 Resources

- [Supabase Docs](https://supabase.com/docs)
- [supabase-py GitHub](https://github.com/supabase/supabase-py)
