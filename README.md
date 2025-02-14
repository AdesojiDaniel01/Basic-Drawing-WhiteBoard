README for Collaborative Whiteboard Project
Collaborative Whiteboard
A real-time, interactive collaborative whiteboard built with HTML, CSS, JavaScript, and Flask. This project allows users to draw, save sketches, and collaborate in real time.

Features
✅ User Authentication – Login & Signup functionality for user access.
✅ Real-time Collaboration – Users can share and work on a whiteboard together.
✅ Drawing Tools – Includes a pen, eraser, color picker, brush size control, and undo/redo functions.
✅ Save & Load Sketches – Users can save their whiteboards and reload them later.
✅ Export as PDF – Allows users to download their sketches.
✅ Dashboard Management – Users can manage multiple whiteboards from their dashboard.

Tech Stack
Frontend: HTML, CSS (Bootstrap), JavaScript (Socket.io, FontAwesome)
Backend: Flask (Python), Socket.io
Database: SQLite/PostgreSQL (optional for user authentication)
Installation & Setup
1. Clone the Repository
bash
Copy
Edit
git clone https://github.com/your-username/collaborative-whiteboard.git
cd collaborative-whiteboard
2. Set Up Virtual Environment
bash
Copy
Edit
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
3. Install Dependencies
bash
Copy
Edit
pip install -r requirements.txt
4. Run the Application
bash
Copy
Edit
python app.py
The server should start at: http://127.0.0.1:5000/

File Structure
bash
Copy
Edit
/collaborative-whiteboard
│── /static
│   ├── css/
│   ├── js/
│── /templates
│   ├── dashboard.html
│   ├── index.html
│   ├── login.html
│   ├── signup.html
│── app.py
│── requirements.txt
│── README.md
Usage
Signup/Login: Users create an account and sign in.
Create & Edit Whiteboards: Draw, erase, and modify sketches.
Save & Load Whiteboards: Store and retrieve previous whiteboards.
Export as PDF: Download sketches as PDF.

License
This project is open-source and available under the MIT License.
