🏦 Bank Management System – Built with Python & Love for Clean Architecture
Hi there! 👋 I’m Megha, and this is a Command-Line Bank Management System I built using Python, SQLite, and SQLAlchemy. It's not just a coding exercise  it’s a complete mini-system that simulates real-world banking workflows, packed with core features you'd expect in a real bank app (minus the legal license 😄).
This project helped me dive deep into how secure systems are structured, how databases are managed, and how to build scalable, clean, and modular code  all through the lens of a CLI banking app.

🔍 What This Project Is All About
Think of this as a simple backend prototype for a banking system. You can:
Register or log in as a user or an admin
Manage multiple bank accounts
Deposit, withdraw, or transfer funds
See a complete transaction history
Admins can monitor users, view system-wide logs, and even disable accounts
All of this happens inside a secure, Python-powered terminal interface with bcrypt-secured passwords and real-time balance updates.

💡 What Makes This Project Different?
There are lots of banking system projects out there — especially in classrooms. But here’s what I tried to do differently:
Modular Code Structure: Everything’s broken down logically — from database to CLI logic. Easy to scale or upgrade.
Security-First: bcrypt is used for password hashing — no plaintext here.
Role-Based Access: Admins and users have separate permissions and views.
Real-Time Data Sync: Every transaction updates balances immediately and logs it for history.

⚙️ Tech Stack
Language: Python 3.x
Database: SQLite (easy to migrate to PostgreSQL)
ORM: SQLAlchemy
Security: bcrypt for password hashing
Interface: Command Line (CLI)

🏗️ How It's Structured
The project follows a clean, layered architecture:
graphql
Copy
Edit
bank_system/
│
├── auth/                  # Login & registration
├── db/                    # Database models & setup
├── operations/            # Banking and admin features
├── cli/                   # CLI flow and menus
├── utils/                 # Helper functions
└── README.md
Each part does its own job — no messy code piles here.

🚀 Getting Started
Here’s how you can run it locally:

bash
Copy
Edit
 Clone the repo
git clone https://github.com/yourusername/bank-management-system.git
cd bank-management-system

Create a virtual environment
python -m venv venv
source venv/bin/activate    # (Use venv\Scripts\activate on Windows)

 Install the dependencies
pip install -r requirements.txt
Run the CLI app
python cli/cli_app.py
It’s all set up for local testing — no complicated config.

🌱 What I Learned
This project pushed me to learn:

How to structure real-world backend project
Safe database interaction with SQLAlchemy
The importance of password hashing & session handling
Building for both users and admins with access control
Clean coding practices and modularity

🧩 Possible Upgrades (and yes, I’d love to do them!)
 GUI version using Tkinter or PyQt
 Web app version with Flask/Django
 PostgreSQL integration
 Loan management and interest calculations
 Account statement PDFs and notifications
 Unit testing with PyTest
This is just the beginning — I plan to keep building on it. 😊


 
