## Installation

### Prerequisites
Ensure you have the following installed:
- Python 3.x
- pip (Python package manager)
- Virtualenv (optional but recommended)

### Setup Instructions

1. **Clone the repository**
   ```bash
   git clone https://github.com/manojtharindu11/flask-intro.git
   cd flask-intro
   ```

2. **Create a virtual environment** (optional but recommended)
   ```bash
   py -3 -m venv .venv
   source venv/bin/activate   # On Windows use: venv\Scripts\activate
   ```

3. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

4. **Set environment variables**
   ```bash
   export FLASK_APP=app.py
   export FLASK_ENV=development  # Enables debug mode
   ```

5. **Run the application**
   ```bash
   flask run
   ```
   The app should now be running at `http://127.0.0.1:5000/`.
