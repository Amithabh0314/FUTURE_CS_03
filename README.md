Task 3 of Future Intern in the track of Cyber Security

**Analyst:**``` Amithabh D.K```

**Task Summary:**
```
Built a secure file upload/download web portal using Flask with AES-256 encryption. Files uploaded are encrypted before storage and decrypted on-demand when downloaded. The application was deployed on Render.
```

**🧰 Tech Stack & Tools Used:**

```
Python Flask - Backend web framework for handling HTTP requests and routing

PyCryptodome - Cryptography library for AES-256 encryption/decryption

HTML/CSS/JavaScript - Frontend UI with responsive design

Bootstrap 5 - CSS framework for styling UI components

Font Awesome - Icon library for UI elements

Werkzeug - WSGI utilities and file handling

python-dotenv - Environment variable management

UUID - Unique identifier generation for files

Hashlib - SHA-256 hashing for file integrity checks

Socket - Network utilities for IP detection

Git & GitHub - Version control and code hosting
```

**How to setup:**

```
# Step 1: Clone the repository
git clone https://github.com/Amithabh0314/FUTURE_CS_03.git
cd FUTURE_CS_03

# Step 2: Set up a virtual environment
python3 -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

# Step 3: Install dependencies
pip install -r requirements.txt

# Step 4: Run the Flask app with SSL
python app.py
```
