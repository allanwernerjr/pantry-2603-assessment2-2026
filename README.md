## Local Development Setup

### 1. Clone the Repository

```bash
git clone <repository-url>
cd pantry
```

---

### 2. Create Virtual Environment

#### Windows

```bash
python -m venv .venv
.venv\Scripts\activate
```

#### Mac / Linux

```bash
python3 -m venv .venv
source .venv/bin/activate
```

---

### 3. Install Dependencies

```bash
pip install -r requirements.txt
```

---

### 4. Run the Application

```bash
python app.py
```

The application should now be available at:

```text
http://127.0.0.1:5000
```

---

### 5. Deactivate Virtual Environment

When finished:

```bash
deactivate
```
