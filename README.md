# Django Project Setup Guide

This guide explains how to clone this repository, set up a virtual environment, and install all required dependencies including Django.

---

## Getting Started
Open your terminal and run:

### 1. Clone the Repository

```bash
git clone https://github.com/ankur-raii/tweet-karo.git
cd tweet-karo
```

### 2. Setup Virtual Environment(For WINDOWS)

```bash
python -m venv venv
venv\Scripts\activate
```

### (For LINUX / macOS)
```bash
python3 -m venv venv
source venv/bin/activate
```

### 3. Install dependencies
```bash
pip install -r requirements.txt
```
### Freeze dependencies
```bash
pip freeze > requirements.txt
```

### 4. Run the project (at the local server)
```bash
cd tweetPost
python manage.py runserver
```

### NOTE:
## 1. If django is not installed using requirements, then install
```bash
cd tweet-karo
pip install django
```

## 2. If the error is showing pillow is not installed, then install it again in 
```bash
cd tweetPost  
python -m pip install Pillow
```

### Finally the project will run. Enjoy it.



